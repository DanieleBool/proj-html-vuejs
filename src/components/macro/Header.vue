<template>
    <header>
        <section class="container">
            <navBar/>   
        </section>
        
        <section class="hero">
            <pop/>
            <div class="descr">
                <h4>The best table in town</h4>
                <h1>FINE DINING EXPERIENCE</h1>
                <p>Pellentesque vitae viverra risus, sagittis. Venenatis ridiculus scelerisque nisi in urna nulla. Sit tempor a et nisl, ac felis.</p>
                <a class="button1" href="#">explore the menu</a>
            </div>
            <div class="side-img"></div>
        </section>
    </header>
</template>

<script>
import navBar from '../elements/navBar.vue';
import pop from '../elements/pop.vue';


export default {
    name: 'Header',
    components: {
    navBar,
    pop,
  }
}
</script>

<style lang="scss" scoped>
@import '../../assets/style/partials/variables.scss';
    // .container{
    //     // z-index: 2;
    //     // position: fixed;
    // }
    .hero{
        // height: 800px;
        // display: flex;
        .navb{
            align-self: flex-start;
        }
        .descr{
            background-color: black;
            color: $wGray;
            width: 40%;
            padding: 10%;
            padding-top: 15%;
            h4{
                text-transform: uppercase;
                font-size: 11px;
                font-weight: 600;
                margin-bottom: 30px;
                font-family: sans-serif;
            }
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
        .side-img{
            background-image: url('../../assets/img/slider52x.jpg');
            background-size: cover;
            filter: brightness(66%);
            width: 60%;
        }
    }
</style>
