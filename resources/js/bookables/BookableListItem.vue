<template>
    <div>
        <!-- 3rd call data from parent component -->
        <h1>{{itemTitle}}</h1>
        <p>{{itemContent}}</p>
    </div>
</template>
<script>
export default {
    //1st assign props
    props: {"itemTitle": String, "itemContent": String, "price": Number},
    mounted() {
        console.log(this.itemTitle);
        //this.itemTitle = "NEW TITLE";
        /* setTimeout(() => {
            this.itemTitle = "New Title";
        }, 1500); */
    }
}
</script>