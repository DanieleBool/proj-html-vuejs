<template>
    <section>
        <div class="hero">
            <div class="side-img">
                <!-- <img src="../../assets/img/slider32x.jpg" alt="chef-1"> -->
            </div>
            <div class="descr">
                <h4>enjoy your meal at home</h4>
                <h1>Takeout now available</h1>
                <p>Pellentesque vitae viverra risus, sagittis. Venenatis ridiculus scelerisque nisi in urna nulla. Sit tempor a et nisl, ac felis.</p>
                <a class="button1" href="#"><i class="fas fa-car"></i> view takeout menu</a>
            </div>       
        </div>
    </section>
</template>

<script>

export default {
    name: 'takeout',
    components: {
  }
}
</script>

<style lang="scss" scoped>
@import '../../assets/style/partials/variables.scss';

    .hero{
        .navb{
            align-self: flex-start;
        }
        .descr{
            background-color: black;
            color: $wGray;
            width: 40%;
            padding: 7%;
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
            background-image: url('../../assets/img/slider72x-scaled.jpg');
            background-size: cover;
            width: 60%;
            // img{
            //     object-fit: cover;
            // }
        }
    }
</style>