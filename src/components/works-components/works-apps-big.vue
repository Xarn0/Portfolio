<template lang="pug">
include ../../assets/pugmix/mixin.pug
.conteiner.worksApps.public_margin
    .worksApps__header 
        +CreateH("complete-apps",false,false)
    .worksApps__content.public_margin 
        +CreatCard("../../static/image/work1.jpg","HTML SCSS Python","Myproject","описание","Live <~>",true,"Cached >=")
        +CreatCard("../../static/image/work1.jpg","HTML SCSS Python","Myproject","описание","Live <~>",true,"Cached >=")
        +CreatCard("../../static/image/work1.jpg","HTML SCSS Python Javascript php lflflf ","Myproject","описание","Live <~>",true,"Cached >=")
        +CreatCard("../../static/image/work1.jpg","HTML SCSS Python","Myproject","описание","Live <~>",true,"Cached >=")
</template>
<script>

export default {
    name:"works-apps-big",
    data(){
        return{

        }
    }
}

</script>

<style lang="scss" scoped>
.worksApps{
    &__content{
        display: flex;
        flex-wrap: wrap;
        gap: 10px;
        align-items: flex-start;
    }
    .card{
        align-self: start;
    }
}
.project__btn{
    margin-left: 16px;
}
</style>
