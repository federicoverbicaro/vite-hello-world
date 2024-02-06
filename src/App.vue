<template>
    <div>
        <PrimoTitolo></PrimoTitolo>
        <ImgVite></ImgVite>
        <PrimoParagrafo></PrimoParagrafo>
    </div>
</template>


<script>
import PrimoTitolo from './components/PrimoTitolo.vue'
import ImgVite from './components/ImgVite.vue'
import PrimoParagrafo from './components/PrimoParagrafo.vue'
export default {

    components: {
        PrimoTitolo,
        ImgVite,
        PrimoParagrafo,
    }


}

</script>


<style>
div{
    padding: 70px;
}
</style>
