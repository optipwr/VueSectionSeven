import

<template>
    <div>
        <p>Server Status: {{ status }}</p>
        <hr>
        <button @click="changeStatus">Change Status</button>
        <hr>
        <button @click="dataRequest">Click For Data</button>
    </div>
</template>

<script>
    export default {
        data: function() {
            return {
                status: 'Critical'
            }
        },
        methods: {
            changeStatus() {
                this.status = 'Normal';
            },
            dataRequest() {

            }
        }
    }
</script>

<style lang="css">
</style>
