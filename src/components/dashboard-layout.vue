<template>
	<div>
		<div class="menubar">
			<top-menu></top-menu>
		</div>

		<div class="middleContainer">
			<div class="leftMenu">
				<side-menu></side-menu>
			</div>
			<div class="mainContainer">
				<router-view></router-view>
			</div>
		</div>
		<div class="footer">Footer</div>
	</div>
</template>

<script>
import TopMenu from "./top-menu.vue";
import SideMenu from "./side-menu.vue";

export default {
	components: {
		"top-menu": TopMenu,
		"side-menu": SideMenu,
	},

	data:function(){
		return{
			name:"ara",
			same:"sdfsdff",
		}
	},
	methods:{
		names() {
			console.log("name")
		},
		game(){
			console.log("game")
		}
	}
};
</script>
<style lang="scss" scoped>


.middleContainer {
	display: flex;
	border: 1px solid green;
}

.leftMenu {
	flex: 2;
}

.mainContainer {
	flex: 5;
}



	.footer{
		height: 50px;
		background:gray;
	}
</style>
