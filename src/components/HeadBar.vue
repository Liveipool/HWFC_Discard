<template>
	<div class="head-bar hwfc-blue-bg">
		<ul class="nav-list">
	      <li>
	        <v-link href="/">主页</v-link>
	        <v-link href="/introduction">球队介绍</v-link>
	        <v-link href="/members">球队成员</v-link>
	        <v-link href="/records">战绩记录</v-link>
	      </li>
	    </ul>
	</div>
</template>

<script>
  	import VLink from './VLink.vue'
	export default{
	    components: {
	      	VLink
	    }
	}
</script>

<style>
	.head-bar {
		margin: 0px;
		height: 80px;
	}
	.nav-list {
		width: 600px;
		margin-left: auto;
		margin-right: auto;
		font-size: 30px;
	}
	li {
		padding-top: 15px;
		list-style: none;
	}
</style>