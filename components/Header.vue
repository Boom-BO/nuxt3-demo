<template>
	<header>
		<nav class="header">
			<div class="header-content">
				<svg-icon class="icon-logo" name="logo"></svg-icon>
			</div>
			<div class="nav"></div>
		</nav>
	</header>
</template>

<script setup lang="ts"></script>
<style lang="scss" scoped>
.header {
	position: fixed;
	left: 0;
	top: 0;
	height: 100px;
	width: 100%;
	box-sizing: border-box;
	z-index: 99;
	transition: all 0.5s;

	&:hover {
		background-color: #fff;
	}

	&-content {
		width: 100%;
		padding: 0 100px;
		.icon-logo {
			float: left;
			height: 100px;
			width: auto;
		}
	}
}
@media screen and (max-width: 1680px) {
	.header-content {
		width: 93.705%;
		margin: 0 auto;
		padding: 0 20px;
	}
}
</style>
