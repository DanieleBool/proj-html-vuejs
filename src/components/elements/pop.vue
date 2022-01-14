<template>
    <div id="pop">
        <div class="box">
            <i class="fab fa-atlassian"></i>
            <div>Demos</div>
        </div>
        <div class="box">
            <!-- <i class="fas fa-shopping-cart"></i> -->
            <span><span class="dollar">$</span>39</span>
            <div>On Sale</div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'pop',
}
</script>

<style lang="scss" scoped>
@import '../../assets/style/partials/variables.scss';

    #pop{
        top: 150px;
        right: 15px;
        z-index: 1;
        position: fixed;
        display: block;
        flex-direction: column;
        align-items: center;

        .box{
            background-color: whitesmoke;
            height: 65px;
            width: 65px;
            padding: 10px 6px;
            border-radius: 6px;
            text-align: center;
            font-size: 12px;
            font-weight: bold;
            cursor: pointer;
            margin-bottom: 10px;
            display: flex;
            flex-direction: column;
            align-content: center;
            justify-content: space-around;
            color: #767c81;
            box-shadow:10px 10px 90px grey;
            i{
                margin-top: 5px;
                font-size: 25px;
                cursor: pointer;
                margin-bottom: 6px;
                color: #33475c;
            }
            span{
                color: #65bc7b;
                font-family: arial;
                font-size: 26px;
                font-weight: bold;
                text-align: center;
                cursor: pointer;
                vertical-align: text-bottom;
                line-height: 27px;
                .dollar{
                    font-size: 16px;
                    line-height: 20px;
                    vertical-align: text-top;
                }
            }
        }
    }
</style>