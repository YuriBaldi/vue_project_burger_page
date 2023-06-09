<template>
    <div id="main-banner">
        <h1>Make Your Burger</h1>

    </div>
</template>

<script>
export default {
    name: "Banner"

}
</script>

<style scoped>
#main-banner{
    background-image: url("https://storage.googleapis.com/domain-images/bfbafc25-e125-4cc2-b749-33feac13ffd2/mobile_4fcaf624-b3c5-40e9-b4a5-333cce63c0a2.jpg");
    background-position:0-250px;
    background-size: cover;
    height: 400px;
    display: flex;
    align-items: center;
    justify-content: flex-start;
}

#main-banner h1{
    color: #fff;
    text-align: center;
    font-size: 45px;
    background-color: #fcba03;
    padding: 20px 40px;
}
</style>