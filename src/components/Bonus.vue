<template>
    <div class="containerFullBlue">
        <section>
            <ul>
                <li v-for="(icon, index) in icons" :key="index">
                    <img :src=" require('../assets/img/' + icon.imgName )" alt="" >
                    <p> {{ icon.text }}</p>
                </li>
            </ul>

        </section>
    </div>
  
</template>

<script>
export default {
    name: "Bonus",
    data() {
        return {
            icons: [
                {
                    imgName: "buy-comics-digital-comics.png",
                    text: "digital comics"
                },
                {
                    imgName: "buy-comics-merchandise.png",
                    text: "dc merchandise"
                },
                {
                    imgName: "buy-comics-shop-locator.png",
                    text: "subscription"
                },
                {
                    imgName: "buy-comics-subscriptions.png",
                    text: "comic shop locator"
                },
                   {
                    imgName: "buy-dc-power-visa.svg",
                    text: "dc power visa"
                },
             
            ]
        }
    }
}
</script>

<style lang="scss" scoped>
    .containerFullBlue {
        background-color: #0C7CEC;
    }
    section {
        width: 1170px;
        margin: 0 auto;
        display: flex;
        justify-content: space-between;
        align-items: center;
    }

    ul {
        width: 100%;
        padding: 32px 0;
        display: flex;
        list-style: none;
        justify-content: space-around;
        

        li {
            display: flex ;
            align-items: center;
        }

        li p {
            color: #fff;
            text-transform: uppercase;
            font-size: 10px;
            font-weight: 400;
            margin-left: 8px;
        }
    }

    img {
        height: 40px;
    }
    
</style>