<template>
    <div class="card w-100">
        <div class="card-body">
            
            <!-- 3rd call data from parent component -->
            <router-link :to="{name: 'bookable', params: {id: id} }">
                <h5 class="card-title">{{title}}</h5>
            </router-link>
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