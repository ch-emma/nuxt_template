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
		<!-- использование иконок -->
		<!-- <icons-burger /> -->
	</div>
</template>

<script>
import Header from '@/components/header/header.vue'
	import Attention from '@/components/attention/attention.vue'
export default {
	components: {
		"app-header": Header,
		"app-attention": Attention
	}
}
</script>

<style lang="scss">
	.show
	{
		display: none;
		color: $darkblue;
		font-family: 'Roboto', serif;
		font-size: 14px;
		font-weight: 400;
		width: 1366px;
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