<script>
export default {
    name: 'jumbotron'
};
</script>

<template>
    <div>
        <img src="../assets/vue.svg">
        <img src="/vite.svg">
    </div>
</template>

<style scoped>
img {
    width: 200px;
    margin: 0 20px;
}

div {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 300px;
    width: 500px;
    background-color: #1e2a4b;
    border-radius: 15px;
}
</style>