<template>
    <div class="loading">
        <i class="fa fa-spinner fa-pulse fa-3x fa-fw"></i>
    </div>
</template>

<script>
export default {
    name: 'loading',
    data() {
        return {
            
        }
    }
}
</script>

<style scoped>
.loading {
    display: flex;
    justify-content: center;
    align-items: center;
    width: 100%;
    height: 90vh;
}
</style>