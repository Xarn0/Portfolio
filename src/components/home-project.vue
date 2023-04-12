<template lang="pug">
include ../assets/pugmix/mixin.pug

section.container
    +CreateH("projects",true)
    .project-list
        +CreatCard("../static/image/craze.png","HTML SCSS Python","Myproject","описание","Live <~>",true,"Cached >=","https://xarn0.github.io/web-layout/")
        +CreatCard("../static/image/Leo.png","HTML SCSS Python","Myproject","описание","Live <~>",false,"Cached >=","https://xarn0.github.io/web-layout-1/")
        +CreatCard("../static/image/craze.png","HTML SCSS Python React Express Discord.js Flas Node.js Flask","Myproject","описание","Live <~>",false,"Cached >=")
</template>


<script>

export default{
    name:"home-project"
}

</script>
<style scoped lang="scss">
.project-list{
    display: flex;
    flex-wrap: wrap;
    gap: 10px;
  
    padding-bottom: 50px;
}
.project__btn{
    margin-left: 16px;
}
</style>