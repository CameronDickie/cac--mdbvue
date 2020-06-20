<template>
    <div>
        <mdb-container fluid>
            <mdb-media>
                <mdb-media-image src="/media-content/imgs/img-1.jpg" class="mx-auto w-response" alt="Generic Placeholder image" />
            </mdb-media>
            This is a test to see if routing is working as expected @home
        </mdb-container>
    </div>
</template>


<script>
import {
    mdbContainer,
    mdbMedia,
    mdbMediaImage
} from 'mdbvue'
export default {
    name: 'Home',
    components: {
        mdbContainer,
        mdbMedia,
        mdbMediaImage
    }
}
</script>

<style scoped>

</style>