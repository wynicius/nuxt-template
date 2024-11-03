<template>
    <div>
        <h1>Welcome to the homepage</h1>
        <AppAlert>
        This is an auto-imported component
        </AppAlert>
        {{ apiSecret }}
    </div>
</template>

<script setup lang="ts">
const appConfig = useAppConfig()
const apiSecret = appConfig.apiSecret
</script>