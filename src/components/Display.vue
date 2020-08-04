<template>
  <div class="display">
      {{ value }}
  </div>
</template>

<script>
export default {
	props : ['value']


}
</script>

<style> 

.display {
		grid-column: 1 / 5;
		background-color: #0004;
		align-items: center;
		padding: 15px;
		font-size: 2.1em;
		overflow: hidden;
		color: aliceblue;
		text-overflow: ellipsis;	
		}
</style>