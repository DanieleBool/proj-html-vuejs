<template>
    <section class="container">
        <div class="page">
            <h1>Hors d'oeuvres</h1>
            <div>
                <h2>ahi salmon nigiri</h2>
                <p>Eget vulputate vitae quis rutrum blandit sed. Quam nulla sit lacinia.</p>
            </div>
                        <div>
                <h2>UMI MASU SALAD</h2>
                <p>Mollis ornare sit sapien, sodales. Cursus duis proin semper quisque.</p>
            </div>
                        <div>
                <h2>TEMAKI WITH CRAB</h2>
                <p>Ac vel, risus ornare senectus placerat duis amet dictumst tellus.</p>
            </div>
            <div>
                <h2>California Rolls</h2>
                <p>Ac vel, risus ornare senectus placerat duis amet dictumst tellus.</p>
            </div>
        </div>
        <div class="page back">
            <h1>Main course</h1>
            <div>
                <h2>baised abalone</h2>
                <p>Mollis ornare sit sapien, sodales. Cursus duis proin semper quisque.</p>
            </div>
                        <div>
                <h2>twice cooked pork</h2>
                <p>Ac vel, risus ornare senectus placerat duis amet dictumst tellus.</p>
            </div>
            <div>
                <h2>kung pao chicken</h2>
                <p>Quis duis sit dictum aliquam a velit enim. Tellus in sit augue aliquam.</p>
            </div>
            <div>
                <h2>Char siu & sushis</h2>
                <p>Feugiat rhoncus ipsum tristique purus diam, et dolor molestie.</p>
            </div>
        </div>
        <div class="page">
            <h1>Desserts</h1>
            <div>
                <h2>Chocolate ball cake</h2>
                <p>In pellentesque in felis massa vehicula. In sed euismod ut.</p>
            </div>
            <div>
                <h2>LIME PIE WITH CRUST</h2>
                <p>Mollis ornare sit sapien, sodales. Cursus duis proin semper quisque.</p>
            </div>
            <div>
                <h2>RASBERRY PEAR CAKE</h2>
                <p>Eget vulputate vitae quis rutrum blandit sed. Quam nulla sit.</p>
            </div>
            <div>
                <h2>Café Au Lait</h2>
                <p>Eget vulputate vitae quis rutrum blandit sed. Quam nulla sit.</p>
            </div>
        </div>
    </section>
</template>

<script>

export default {
    name: 'Menu',
    components: {
  }
}
</script>

<style lang="scss" scoped>
@import '../../assets/style/partials/variables.scss';

.container{
    display: flex;
    margin: 100px auto;
    .page{
        padding: 80px 70px;
        background-color: rgb(232,232,232);
        h1{
            font-family: 'Bebas Neue';
            margin-bottom: 50px;
        }
        h2{
            font-family: 'Bebas Neue';
            margin-bottom: 10px;
        }
        p{
            font-family: 'Lora';
            margin-bottom: 30px;
        }
    }
        .back{
            background-image: linear-gradient(#000 30%, transparent),url('../../assets/img/misc22x.jpg');
            background-size: cover;
            color: $wGray;
            filter: blur(60%);
            filter: brightness(70%);

            h1, h2{
                color: white;
            }

            transform: translatey(-40px);
        }
}
</style>