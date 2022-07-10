<template>
  <div class="photos">
    <div class="block_photo">

      <div class="block_columns">
        <div class="block_item">
          <div class="photo1"></div>
        </div>
      </div>

      <div class="block_columns1">
        <div class="block_item1">
          <div class="photo1"></div>
        </div>
      </div>

      <div class="block_columns">
        <div class="block_item">
          <div class="photo1"></div>
        </div>
      </div>

    <div class="block_columns1">
      <div class="block_item1">
        <div class="photo1"></div>
      </div>
    </div>

    <div class="block_columns">
      <div class="block_item">
        <div class="photo1"></div>
      </div>
    </div>

    <div class="block_columns1">
      <div class="block_item1">
        <div class="photo1"></div>
      </div>
    </div>

    </div>
  </div>
</template>

<style lang="css">
.photos {
  height: 100vh;
  width: 100%;
}
.block_columns{
  flex: 0 1 30%;
  height: 200px;
}
.block_columns1{
  flex: 0 1 30%;
  height: 500px;
}
.block_photo{
  position: relative;
  height: 45%;
  width: 90%;
  top: 5%;
  margin: 0 auto;
  display: flex;
  flex-wrap:wrap;
  justify-content: space-between;
}

.block_item{
  position: relative;
  width: 100%;
  height: 100%;
  align-items: center;
  border-radius: 7px;
}
.block_item1{
  width: 100%;
  height: 100%;
  border-radius: 7px;
}
.photo1{
  background-repeat     : no-repeat;
  background-size       : cover;
  background-position-x : 50%;
  background-position-y : 50%;
  width: 100%;
  height: 100%;
  background-image: url("assets/around.JPG");
  border-radius: 7px;
}
</style>
