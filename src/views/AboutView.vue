<template>
  <div class="img-about">
    <img src="https://lifestyle.campus-star.com/app/uploads/2015/01/bg.jpg" alt="">
  </div>

  <div class="con">
    <div class="item">
        <p>Item1</p>
    </div>
    <div class="item">
        <p>Item2</p>
    </div>
    <div class="item">
        <p>Item3</p>
    </div>
    <div class="item">
        <p>Item4</p>
    </div>
</div>
</template>

<style scoped>
.img-about img{
  min-height: 50px;
  height: 450px;
  width: 100%;
  padding: 30px;
  border-radius: 20px;
}

.con{
  background-color: antiquewhite;
  width: 100%;
  height: 250px;
  display: flex;
  flex-direction: row;
  flex-wrap: wrap;
}

.con .item{
  padding: 10px;
  text-align: center;
  width: 25%;
}


</style>
