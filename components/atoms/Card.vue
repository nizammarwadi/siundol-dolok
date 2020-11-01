<template>
    <div class="card" style="width: 18rem;">
        <img :src="item.urlToImage" class="card-img-top" alt="#">
        <div class="card-body">
            <h1 class="card-title">
                {{title}}
            </h1>
            <h4 class="card-content">
                {{content}}
            </h4>
            <p class="card-text">
                {{author}}
            </p>
            <p class="card-text">
                {{publishedAt}}
            </p>
        </div>
    </div>
    

</template>

<script>
export default {
    props: {
        urlToImage: '',
        title: '',
        content: '',
        author: '',
        publishedAt: '',
    }

}
</script>

<style>

</style>