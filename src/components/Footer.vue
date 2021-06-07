<template>
  <footer>
      <div>
          <section>
        <h3>Dc Comics</h3>
        <ul>
            <li>
                <p>charater</p>
            </li>
            <li>
                <p>comics</p>
            </li>
            <li>
                <p>movies</p>
            </li>
            <li>
                <p>TV</p>
            </li>
            <li>
                <p>games</p>
            </li>
            <li>
                <p>videos</p>
            </li>
            <li>
                <p>news</p>
            </li>
        </ul>
        <h3>shop</h3>
        <ul>
            <li>
                <p>shop DC</p>
            </li>
            <li>
                <p>shop DC collectibles</p>
            </li>
        </ul>
    </section>
    <section class="marginLftRgt">
        <h3>dc</h3>
        <ul>
            <li>
                <p>Term of use</p>
            </li>
            <li>
                <p>privacy policy (new)</p>
            </li>
            <li>
                <p>ad choices</p>
            </li>
            <li>
                <p>advertising</p>
            </li>
            <li>
                <p>jobs</p>
            </li>
            <li>
                <p>subscriptions</p>
            </li>
            <li>
                <p>talent workshops</p>
            </li>
            <li>
                <p>Cpsc certificates</p>
            </li>
            <li>
                <p>ratings</p>
            </li>
            <li>
                <p>shop help</p>
            </li>
            <li>
                <p>contact us</p>
            </li>
        </ul>
    </section>

    <section>
        <h3>Dc Comics</h3>
        <ul>
            <li>
                <p>charater</p>
            </li>
            <li>
                <p>comics</p>
            </li>
            <li>
                <p>movies</p>
            </li>
            <li>
                <p>TV</p>
            </li>
            <li>
                <p>games</p>
            </li>
        </ul>
      
    </section>
      </div>
    

  </footer>
</template>

<script>
export default {
    name: "Footer"
}
</script>

<style lang="scss" scoped>
    footer {
        max-width: 1170px;
        margin: 0 auto;
        
        color: #fff;
    }

    div {
        display: flex;
        align-items: flex-start;
    }

    section {
        margin: 32px 0;

        h3 {
            margin-bottom: 16px;
            text-transform: uppercase;
            font-size: 16px;
        }

        ul {
            list-style: none;
            margin-bottom: 16px;

            li {
                margin-bottom: 8px;
            }
                p {
                    color: #ccc;
                    font-size: 14px;
                    text-transform: capitalize;
                }
        }

    }
    .marginLftRgt {
        margin: 32px 32px;
    }

</style>