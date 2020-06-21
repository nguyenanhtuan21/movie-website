<template>
  <div class="card" style="padding:5px;background: #333232;border-bottom:1px solid #5e5e5e">
                <div class="card-horizontal">
                    <div class="img-square-wrapper">
                        <img class="" src="https://bilutv.org/upload/images/2020/04/tai-sinh-2020_1587210736.jpg" alt="Card image cap" width="60px" height="60px">
                    </div>
                    <div class="card-body" style="padding:0 5px 5px 5px">
                        <a href="#" class="card-title title-card" >Thần điêu hiệp lữ</a>
                        <p class="card-text" style="font-size: 12px">Some quick example text to build on </p>
                    </div>
                </div>
            </div>
</template>

<script>
export default {
    name: 'CardNav'
}
</script>

<style scoped lang="scss">
    .card-horizontal {
    display: flex;
    flex: 1 1 auto;
    }

    .title-card{
        font-size: 14px;
        margin-bottom:0;
        color:#c2aa8d;
        cursor: pointer;

    }
    .title-card:hover{
        color: yellow !important;
    }
</style>