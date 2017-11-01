<template>
    <div>
        Trade or View your Portfolio
        <h6>You may Save & Load your Data</h6>
        <h6>Click 'End Day' to begin a New Day!</h6>
        <hr>
        <p>Your Funds: {{ funds | currency }}</p>
    </div>
</template>

<script>
export default{
	computed: {
		funds(){
			return this.$store.getters.funds;
        }
    }
}
</script>

<style>

</style>

