<template>
	<div>
		<h1 class="page-header">로그인 페이지</h1>
		<LoginForm></LoginForm>
	</div>
</template>

<script>
import LoginForm from '@/components/LoginForm';

export default {
	components: { LoginForm },
	name: 'LoginPage',
};
</script>

<style scoped></style>
