<template>
    <section>
        <div class="container">
            <div class="descr">
                <p><span class="bold">HAC TELLUS, FELIS RISUS AT</span> mattis mattis. Eget euismod semper eget tortor, donec amet, blandit. Tristique facilisi faucibus elementum feugiat in nam in feugiat. Ipsum odio etiam duis facilisis amet vulputate.</p>
                <h1>food is our common ground, a universal experience.</h1>
                <p>Tristique tempus condimentum diam donec. Condimentum ullamcorper sit elementum hendrerit mi nulla in consequat, ut. Metus, nullam scelerisque netus viverra dui.</p>
                <img src="../../assets/img/signature.jpg" alt="signature">
            </div>
            <div class="side-img">
                <img src="../../assets/img/info22x.jpg" alt="chef-1">
            </div>
        </div>

        <div class="cards">
            <div>
                <img src="../../assets/img/sushi-1.png" alt="sushi-1">
                <h3>The best table in town</h3>
                <p>Sed aenean egestas ut aliquam turpis mauris, molestie. Vitae tellus tempor sem id tempus neque, tellus turpis turpis. Morbi tortor id gravida aliquet.</p>
                <a class="button2" href="#">explore the menu</a>
            </div>
            <div>
                <img src="../../assets/img/sushi-2.png" alt="sushi-2">
                <h3>Perfect For Groups</h3>
                <p>Quam eu proin sit massa condimentum. Volutpat non pulvinar aliquet nunc. Orci elementum in aliquet a gravida vivamus aliquam turpis vitae.</p>
                <a class="button2" href="#">make a reservation</a>
            </div>
            <div>
                <img src="../../assets/img/sushi-3.png" alt="sushi-3">
                <h3>Fresh produce everyday</h3>
                <p>Hendrerit amet, volutpat leo non, commodo maecenas scelerisque tincidunt. Morbi vulputate morbi purus quisque sit sagittis orci elementum gravida.</p>
                <a class="button2" href="#">learn more about us</a>
            </div>
        </div>
    </section>
</template>

<script>

export default {
    name: 'options',
    components: {
  }
}
</script>

<style lang="scss" scoped>
@import '../../assets/style/partials/variables.scss';

    .container{
        height: 800px;
        display: flex;
        color: black;
        margin-top: 100px;
        .descr{
            background-color: white;
            width: 50%;
            padding: 5% 10%;
            // padding-top: 15%;
            h1{
                font-family: 'bebas neue';
                font-size: 50px;
                margin-bottom: 30px;
            }
            p{
                margin-bottom: 30px;
                font-family: 'Beba Neue';
                .bold{
                    font-weight: bold;
                }
            }
            img{
                width: 150px;
            }
        }
        .side-img{
            img{
                width: 80%;
                // height: 100%;
                object-fit: contain;
            }
            width: 50%;
        }
    }
    .cards{
        display: flex;
        text-align: center;
        padding: 0 10%;
        margin-top: 100px;
        margin-bottom: 100px;
        div{
            padding: 0 4%;
            img{
                margin-bottom: 30px;
            }
            h3{
                text-transform: uppercase;
                font-family: 'Bebas Neue';
                color: black;
                margin-bottom: 40px;
            }
            p{
                font-family: 'Lora';
                margin-bottom: 40px;
            }
        }
    }
</style>
