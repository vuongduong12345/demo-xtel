<template>
    <div>
        <div>
            <v-avatar size="200">
                <v-img :src="img" contain></v-img>
            </v-avatar>
        </div>
        <div class="mt-5">
            <h2 class="textmember" align="center">{{textmember1}}</h2>
            <div>{{textmember2}}</div>
        </div>
    </div>
</template>
<script>
export default {
    props:['img','textmember1','textmember2']
}
</script>
<style lang="scss" scoped>
.textmember {
    color: #1976d2;
}
</style>