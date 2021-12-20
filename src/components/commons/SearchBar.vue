<template>
    <div class="search-bar">
        <form class="d-flex" action="">
            <input v-model="searchText" class="form-control" type="text" name="" id="" placeholder="Search Disc">
            <button class="btn btn-danger mx-3" @click.prevent="$emit('search', searchText)">Search</button>
            <button class="btn btn-success">Reset</button>
        </form>
        
    </div>
</template>

<script>
export default {
    name:'SearchBar',
    data() {
        return{
            searchText: ''
        }
    }

}
</script>

<style lang="scss" scoped>

</style>