<template>
    <div class="Notification">
        {{ message }}
    </div>
</template>

<script>
    export default {
        data() {
            return { message: 'I am a notification' };
        }
    }
</script>

<style>
    .Notification {
        background: green;
        color: white;
    }
</style>