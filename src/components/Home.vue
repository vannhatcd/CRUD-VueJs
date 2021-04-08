<template>
    <div>
        <p>Server Status: {{ status }}</p>
        <hr>
        <button @click="status == 'Normal' ? changeStatus('Critical') : changeStatus()">Change Status</button>
    </div>
</template>

<script>
    export default {
        data () {
            return {
                status: 'Critical'
            }
        },
        methods: {
            changeStatus(data) {
                if(data) {
                    this.status = data;
                } else {
                    this.status = 'Normal';
                }
            }
        }
    }
</script>

<style scoped>
    div { 
        border: 1px solid red;
    } 
</style>