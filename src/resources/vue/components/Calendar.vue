<template>
    <div>
        Vue.
    </div>
</template>

<script>
import CalendarCell from './CalendarCell.vue'
import moment from 'moment';

export default {
    name: 'Calendar',
    components: {
        CalendarCell
    },
    mounted: function () {
        console.log(moment());
    },
}
</script>

<style lang="scss" scoped>
</style>
