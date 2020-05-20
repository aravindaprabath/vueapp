<template>
	<div class="menu-wrapper">
		<div>
			<router-link to="/"><p>HOME</p></router-link>
		</div>
		<div>
			<router-link to="/menu1"><p>info</p></router-link>
		</div>
		<div @click="counter">{{ name }}</div>
		<!-- <button @click="counter">{{ counter }}</button> -->
	</div>
</template>

<script>
export default {
	data: function() {
		return {
			name: "aravinda",
			counter: this.countFunc,
		};
	},

	methods: {
		countFunc() {
			alert("count func called");
		},
	},
};
</script>

<style lang="scss" scoped>
.menu-wrapper {
	width: 100%;
	height	:50px;
	display: flex;
	align-items: center;


	div{
		padding: 5px 10px;
		border: 1px solid green;
		margin-right: 5px;
	}

}
</style>
