<template>
    <div>
        <div class="card border-0">
            <div class="row">
                <div class="col-md-3 col-4 placeholder">
                    <img :src="src" :alt="alt" class="card-img border-0">
                </div>
                <div class="col-md-9 col-8">
                    <div class="card-body">
                        <h5 class="card-title placeholder">
                            {{title}}
                        </h5>
                        <div class="placeholder-grow">
                            <p class="card-text placeholder">
                                {{text}}
                            </p>
                        </div>
                        <button class="mt-3 mb-3 btn btn-primary float-start">
                            <i class="fa-solid fa-credit-card"></i> سفارش
                        </button>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: "page-lists",
    props: ['src', 'alt', 'title', 'text']
}
</script>

<style scoped>

</style>