<template>
    <section>
        <div class="title">
            <h1>What critics are saying about us</h1>
        </div>
        <div class="container">
            <div class="side-img">
                <img src="../../assets/img/blog72x.jpg" alt="chef-1">
            </div>
            <div class="descr">
                <h4>Meggy stewart</h4>
                <h1>new york times</h1>
                <div>
                    <i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i>
                </div>
                <hr>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Sit eligendi laboriosam assumenda dolores ad magnam hic dolorem reprehenderit dignissimos? Accusantium quia quos aspernatur provident distinctio. Officiis repellat animi necessitatibus sequi!</p>
                <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit.</p>
                <a class="button1" href="#">read full article</a>
            </div>
        </div>
        <div class="container space">
            <div class="descr guardian">
                <h4>Mary maxey</h4>
                <h1>The Guardian</h1>
                <div>
                    <i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i>
                </div>
                <hr>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Sit eligendi laboriosam assumenda dolores ad magnam hic dolorem reprehenderit dignissimos.</p>
                <a class="button1" href="#">read full article</a>
            </div>
            <div class="descr globe">
                <h4>Patrick Monroe</h4>
                <h1>Globe anf mail</h1>
                <div>
                    <i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i>
                </div>
                <hr>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Sit eligendi laboriosam assumenda dolores ad magnam hic dolorem reprehenderit dignissimos.</p>
                <a class="button1" href="#">read full article</a>
            </div>
        </div>
    </section>
</template>

<script>

export default {
    name: 'critics',
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
    .container{
        display: flex;
        justify-content: center;
        margin-top: 100px;
        height: 630px;
        // object-fit: contain;
        width: 80%;
        justify-content: space-between;
        .descr{
            color: $wGray;
            width: 100%;
            padding: 8% 7%;
            background-color: black;
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
                font-size: 60px;
                margin-bottom: 30px;
            }
            div{
                i{
                    color: white;
                    margin-left: 5px;
                    // font-size: 14px;
                }
            }
            hr{
                width: 70px;
                color: white;
                margin: 40px 0;
            }
            p{
                margin-bottom: 40px;
                font-family: 'Beba Neue';
            }
        }
        .side-img{
            width: 99%;
            img{
                height: 100%;
                object-fit: contain;
            }
        }
        .guardian{
            background-image: linear-gradient(#000 15%, transparent, transparent),url('../../assets/img/info52x.jpg');
            background-size: cover;
            width: 45%;
        }
        .globe{
            width: 45%;
            background-image: linear-gradient(#000 15%, transparent, transparent),url('../../assets/img/info12x.jpg');
            background-size: cover;
        }
        .guardian, .globe{
            filter: brightness(90%);
        }
        .cont-space{
        display: flex;
        color: white;
        margin-top: 100px;
        height: 630px;
        width: 80%;
        justify-content: space-between;
        }
    }

</style>