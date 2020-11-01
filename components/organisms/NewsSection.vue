<template>
    <div class="card" style="width: 18rem;">
        <div v-for="(item,index) in dataNews" :key="index">
            <Card
                :urlToImage="item.urlToImage"
                :title="item.title"
                :content="item.content"
                :author="item.author" 
                :publishedAt="item.publishedAt"
            />
        </div>
    </div>
    
</template>

<script>
import Card from '~/components/atoms/Card.vue'
import axios from 'axios'
export default {
    components: {
        Card: Card,
    },
    data() {
        return {
            dataNews: []
        }
    },
    mounted() {
        this.getDataNews()

    },
    methods: {
        getDataNews() {
            axios.get('http://newsapi.org/v2/top-headlines?country=id&apiKey=a050e54685b44bf89ec55dbb472ee1d2')
            .then(res=>{
                this.dataNews=res.data.articles
                console.log(this.dataNews);
            })
            .catch(err=>{
                console.log(err);
            })
        }
    }

}
</script>

<style>
    .col {
        margin-top: 70px;
    }

    

</style>