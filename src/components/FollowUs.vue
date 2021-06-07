<template>
  <section>
      
    <button> 
        <p>sign-up now!</p>
    </button>

     <div>
        <h4>follow us</h4>
        <ul>
            <li>
                <a href="#">
                    <img src="../assets/img/footer-facebook.png" alt="">
                </a>
            </li>
            <li>
                <a href="#">
                    <img src="../assets/img/footer-twitter.png" alt="">
                </a>
            </li>
             <li>
                <a href="#">
                    <img src="../assets/img/footer-youtube.png" alt="">
                </a>
            </li>
             <li>
                <a href="#">
                    <img src="../assets/img/footer-pinterest.png" alt="">
                </a>
            </li>
            <li>
                <a href="#">
                    <img src="../assets/img/footer-periscope.png" alt="">
                </a>
            </li>
        </ul>
    </div>

   
  </section>
</template>

<script>
export default {
    name: "FollowUs"
}
</script>

<style lang="scss" scoped>
    section {
        height: 100px;
        max-width: 1170px;
        margin: 0 auto;
        display: flex;
        align-items: center;
        justify-content: space-between;
    }
    button {
        border: 2px solid #1462AC;
        padding: 8px;
        background-color: transparent;
        p {
            text-transform: uppercase;
            color: #fff;
        }
    }
    div {
        display: flex;
        align-items: center;
        font-size: 15px;
        text-transform: uppercase;
        color: #1462AC;
        img {
            height: 40px;
            margin: 0 4px;
        }
        ul {
            display: flex;
            list-style: none;
        }
    }



</style>