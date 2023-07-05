<script>
export default {
    props: {
        comics: Array
    },
    data() {
        return {}
    }
}
</script>

<template>
    <div class="card-container">
        <div class="card" v-for="comic in comics" :key="comic.series">
            <figure>
                <img :src="comic.thumb" :alt="comic.series">
            </figure>
            <div>{{ comic.series }}</div>
        </div>
    </div>
</template>


<style>
.card-container {
    display: flex;
    flex-wrap: wrap;
    align-items: center;
    justify-content: center;
    margin: 50px;
    width: 90%;
    background-color: rgb(39, 38, 38);
    padding-bottom: 30px;
}

.card {
    flex-basis: calc(100% / 6);
    height: auto;
    display: flex;
    flex-direction: column;
    align-items: center;
    text-align: center;
    height: 200px;
    margin-top: 10px;
    padding: 0 10px
}

figure {
    height: 160px;
    width: 100px;
    margin: 10px 0 10px;
    cursor: pointer;
}

img {
    object-fit: cover;
    display: block;
    height: 100%;
    width: 100%;
    object-position: 50% 50%;
    border: 2px solid transparent;

    &:hover {
        border: 2px solid $blue;
    }

}
</style>





