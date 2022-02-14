<template>
    <div>
        <!-- 2nd assign values to props -->
        <bookable-list-item item-title="Cheal Villa" item-content="A very cheap villa" :price="1000"></bookable-list-item>
        <bookable-list-item item-title="Cheal Villa 2" item-content="A very cheap villa2" :price="1500"></bookable-list-item>
    </div>
</template>

<script>
import BookableListItem from "./BookableListItem";
export default {
    components: {
        BookableListItem
    }
}
</script>