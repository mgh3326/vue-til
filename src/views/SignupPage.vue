<template>
	<div>
		<h1>회원 가입 페이지</h1>
		<signupForm></signupForm>
	</div>
</template>

<script>
import SignupForm from '@/components/SignupForm';
export default {
	name: 'SignupPage',
	components: {
		SignupForm,
	},
};
</script>

<style scoped></style>
