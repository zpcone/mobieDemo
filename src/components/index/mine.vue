<template>
	<div class="mine">
		<div class="user">

		</div>

	</div>
</template>

<script>
</script>

<style lang="less">
	.mine{
		min-height: 100%;
    background-color: white;
    border: 1px solid red;
		.user{
      position: absolute;
      transform:translateX(-50px);
      top:200px;
      left:50%;
      width: 100px;
      height: 100px;
      background: green;
      margin: 0 auto;
		}
	}
</style>
