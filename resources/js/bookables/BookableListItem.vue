<template>
    <div class="card w-100">
        <div class="card-body">
            <!-- 3rd call data from parent component -->
            <h5 class="card-title">{{title}}</h5>
            <p class="card-text">{{description}}</p>
        </div>
    </div>
</template>
<script>
export default {
    //1st assign props
    props: {"title": String, "description": String, "id": Number},
    
}
</script>