<template>
    <section class="container">
        <div class="title">
            <h1>Latest news & promotions</h1>
        </div>
        <div class="cards">
            <div>
                <div class="card-img">
                    <img src="../../assets/img/blog92x-400x458.jpg" alt="coffee">
                </div>
                <h3>The best table in town</h3>
                <p>Aenean ut aliquam turpis mauris.</p>
            </div>
            <div>
                <div class="card-img">
                <img src="../../assets/img/blog72x-400x458.jpg" alt="cousine">

                </div>
                <h3>Perfect For Groups</h3>
                <p>Quam eu massa condimentum.</p>
            </div>
            <div>
                <div class="card-img">
                <img src="../../assets/img/blog82x-400x458.jpg" alt="payment">

                </div>
                <h3>Fresh produce everyday</h3>
                <p>Hendrerit amet, volutpat leo non.</p>
            </div>
        </div>
    </section>
</template>

<script>

export default {
    name: 'news',
    components: {
  }
}
</script>

<style lang="scss" scoped>
@import '../../assets/style/partials/variables.scss';
    .title{
    margin-top: 100px;
    text-align: center;
    font-family: 'Bebas Neues';
    }
    .cards{
        display: flex;
        text-align: center;
        padding: 0 10%;
        margin-top: 100px;
        margin-bottom: 100px;
        justify-content: center;
        div{
            padding: 0 1%;
            width: 300px;
            .card-img{
                height: 400px;
                width: 100%;
                img{
                    margin-bottom: 30px;
                    width: 100%;
                    object-fit: cover;
                    height: 100%;
                }
            }
            h3{
                text-transform: uppercase;
                font-family: 'Bebas Neue';
                color: black;
                margin-top: 24px;
            }
            p{
                font-family: 'Lora';
            }
        }
    }
</style>