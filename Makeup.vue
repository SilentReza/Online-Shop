<template>
    <div class="mt-4">
        <h5 class="text-center fw-bold">
            <i class="fa-solid fa-umbrella-beach ms-1"></i> کالاهای آرایشی
        </h5>
        <list class="mt-3" :src="card.src" :alt="card.alt" :title="card.title" :text="card.text"
            v-for="(card , index) in cardInfos" :key="index"></list>
    </div>
</template>

<script>
import list from './Shoplist.vue'
export default {
    name: "page-makeup",
    components: {
        list
    },
    data() {
        return {
            cardInfos: [
                { src: "", alt: "", title: "Random", text: "Random text Here to put" },
                { src: "", alt: "", title: "Random", text: "Random text Here to put" },
                { src: "", alt: "", title: "Random", text: "Random text Here to put" },
                { src: "", alt: "", title: "Random", text: "Random text Here to put" },
                { src: "", alt: "", title: "Random", text: "Random text Here to put" },
                { src: "", alt: "", title: "Random", text: "Random text Here to put" },
                { src: "", alt: "", title: "Random", text: "Random text Here to put" },
                { src: "", alt: "", title: "Random", text: "Random text Here to put" },
                { src: "", alt: "", title: "Random", text: "Random text Here to put" },
            ]
        }
    },
}
</script>

<style scoped>

</style>