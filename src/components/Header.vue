<template>
  <header>
        <img src="../assets/img/dc-logo.png" alt="">
        
        <ul>
            <li v-for="(link, index) in links" :key="index">
                <a :class=" { active : isActive === true} " :href="link.ref"> {{ link.navName }}</a>
            </li>
        </ul>

  </header>
</template>

<script>
export default {
    name: "Header",
    data() {
        return {
            links: [
                {
                    ref: "#charater",
                    navName: "charater",
                    isActive: false 
                },
                {
                    ref: "#comics",
                    navName: "comics",
                    isActive: true 
                },
                {
                    ref: "#movies",
                    navName: "movies",
                    isActive: false 
                },
                {
                    ref: "#tv",
                    navName: "tv",
                    isActive: false 
                },
                {
                    ref: "#games",
                    navName: "games",
                    isActive: false 
                },
                {
                    ref: "#collectibles",
                    navName: "collectibles",
                    isActive: false 
                },
                {
                    ref: "#videos",
                    navName: "videos",
                    isActive: false 
                },
                {
                    ref: "#fans",
                    navName: "fans",
                    isActive: false 
                },
                {
                    ref: "#news",
                    navName: "news",
                    isActive: false 
                },
                {
                    ref: "#shop",
                    navName: "shop",
                    isActive: false 
                }
            ]
        }
    }
}
</script>

<style lang="scss" scoped>

    header {
        max-width: 1170px;
        height: 100px;
        margin: 0 auto;
        display: flex;
        justify-content: space-between;
        align-items: center;
        border: 1px solid black;
    }
    img {
        height: 80%;
    }

    li {
        display: inline;
        list-style: none;

        a {
            text-transform: uppercase;
            text-decoration: none;
            font-weight: 700;
            font-size: 14px;
            padding: 32px 8px;
            border: 1px solid rgb(3, 105, 194);
            color: black;
        }
    }

    ul li a:active {
        
        color: red;
        
    }


</style>