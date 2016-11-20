<template>
	<div class="bottom-msg navbar-fixed-bottom">
		<div class="chi-msg">{{chiMsg}}</div>
		<div class="eng-msg">{{engMsg}}</div>
		<div class="copyright">{{copyright}}</div>
	</div>
</template>

<script>
	export default{
		name: 'bottom-msg',
		data () {
			return {
				chiMsg: '我在中大，混碗饭吃',
				engMsg: 'Hello World Football Club',
				copyright: '@Copyright Hello World Football Club'
			}
		}
	}
</script>

<style>
	.bottom-msg {
		font-family: cursive;
		font-weight: bold;
	}
	.chi-msg {
		text-align: center;
		color: #3399FF;
		font-size: 70px;
	}
	.eng-msg {
		text-align: center;
		color: #3399FF;
		font-size: 50px;
	}
	.copyright {
		background-color: #3399FF;
		color: #000000;
	}
</style>