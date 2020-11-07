<template>
      <div :id=id class="col s12 resume__article">
          <div class="col s5">
              <img class="resume__article__image" :src="require(`@/assets/img/${photo}.png`)" alt=""/>
          </div>
          <div class="col s7">
              <div class="col s12 resume__article__text">
                 <p class="resume__article__title">{{title}}</p>
                  <span class="resume__article__price--active">{{price}}</span>
                    <span class="resume__article__price--old">{{price_old}}</span>
              </div>
              <div class="col s10 resume__article__amount">
                  <button class="resume__article__amount__button" >-</button>
                  <span class="resume__article__amount__text">{{amount}}</span>
                  <button class="resume__article__amount__button">+</button>
              </div>
          </div>
      </div>
</template>

<script>
export default {
    name:"Article",
    props:{
        id:Number,
        photo:String,
        title:String,
        price:String,
        price_old:String,
        amount:{
            type:String,
            default:"1"
        }
    }

}
</script>

<style src="./styles.css"/>