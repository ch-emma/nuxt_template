<script setup>
// поменял использование апи ( также, когда мы используем useFetch лучше не вызывать тоаст, так как на сервере он не может появится => будут возникать ошибки)
const { auth } = useApi();

const isLogged = async () =>
{
	const { data, error } = await auth.isLogged();

	if (error.value || !data.value)
	{
		return;
	};
};

await isLogged();

// работа со стором
const { userStore } = useStore();

</script>

<template>
	<div class="show">
		<app-header></app-header>
		<app-attention></app-attention>
		<app-bookreceipts></app-bookreceipts>
		<app-newsletter></app-newsletter>
		<app-readyforpublic></app-readyforpublic>
		<app-widgets></app-widgets>
		<app-news></app-news>
		<app-footer></app-footer>
		<!-- использование иконок -->
		<!-- <icons-burger /> -->
	</div>
</template>

<script>
import Header from '@/components/header/header.vue'
import Attention from '@/components/attention/attention.vue'
import BookReceipts from '@/components/receipts/bookReceipts.vue';
import Newsletter from '~/components/newsletter/newsletter.vue';
import ReadyForPublic from '~/components/readyforpublic/readyForPublic.vue';
import Widgets from '~/components/widgets/widgets.vue';
import News from '@/components/news/news.vue';
import Footer from '@/components/footer/footer.vue';
export default {
	components: {
		"app-header": Header,
		"app-attention": Attention,
		"app-bookreceipts": BookReceipts,
		"app-newsletter": Newsletter,
		"app-readyforpublic": ReadyForPublic,
		"app-widgets": Widgets,
		"app-news": News,
		"app-footer": Footer
	}
}
</script>

<style lang="scss">
	.show
	{
		display: block;
		color: $darkblue;
		font-family: 'Roboto', serif;
		font-size: 14px;
		font-weight: 400;
		max-width: 1366px;
		background-color: #F9F9FA;

		@include mq($desktop)
		{
			display: block;
		}

		@include mq($mobile)
		{
			display: block;
		}
	}
</style>