<template>
    <div class="card">
        <div class="card-body">
            <!-- 3rd call data from parent component -->
            <h5 class="card-title">{{itemTitle}}</h5>
            <p class="card-text">{{itemContent}}</p>
        </div>
    </div>
</template>
<script>
export default {
    //1st assign props
    props: {"itemTitle": String, "itemContent": String, "price": Number},
    
}
</script>