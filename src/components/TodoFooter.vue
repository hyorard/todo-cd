<template>
  <div>
    <i v-on:click="clearAll" class="fas fa-dumpster"></i>
  </div>
</template>

<script>
export default {
	methods: {
		clearAll: function() {
			this.$emit('sendClearAllSig');
		},
	},
};
</script>

<style>
</style>