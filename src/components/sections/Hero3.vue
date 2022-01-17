<template>
    <section>
        <div class="hero">
            <div class="descr">
                <h1>The best table in town</h1>
                <p>Pellentesque vitae viverra risus, sagittis. Venenatis ridiculus scelerisque nisi in urna nulla. Sit tempor a et nisl, ac felis.</p>
                <a class="button1" href="#">explore the menu</a>
            </div>       
        </div>
    </section>
</template>

<script>

export default {
    name: 'Hero3',
    components: {
  }
}
</script>

<style lang="scss" scoped>
@import '../../assets/style/partials/variables.scss';

    .hero{
        position: relative;
        background-image: url('../../assets/img/hero42x.jpg');
        background-size: cover;
        width: 100%;
        .descr{
            background-color: black;
            color: $wGray;
            width: 40%;
            padding: 7%;
            padding-top: 15%;
            position: absolute;
            h1{
                font-family: 'bebas neue';
                color: white;
                font-size: 75px;
                margin-bottom: 30px;
            }
            p{
                margin-bottom: 40px;
                font-family: 'Beba Neue';
            }
            
        }
    }
</style>