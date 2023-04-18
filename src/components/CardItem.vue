<script>
export default {
    data() {
        return {
        }
    },
    props: {
        cardYu: Object,
    },
}
</script>

<template>
    <div class="card-yugioh-container">
        <img :src="cardYu.card_images[0].image_url" alt="Yu-gi-oh card">
        <div class="description-card">
            <div>
                <strong>name: </strong><em>{{ cardYu.name }}</em>
            </div>
        </div>
    </div>
</template>

<style lang="scss" scoped>
.card-yugioh-container {
    display: flex;
    flex-flow: row nowrap;
    gap: 5px;
    padding: 5px;
    border: 2px solid black;
    width: 380px;
    img {
        width: 150px;
    }
    .prices {
        ul {
            padding: 0;
            list-style-type: none;
        }
    }
}
</style>