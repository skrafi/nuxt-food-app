<template>
    <div>
        <label :for="select">What {{select}} do you like?</label>
        <select @change="updateValue" :name="select" :id="select">
            <option value>-- Please select a {{select}} --</option>
            <option v-for="option in selectOptions" :key="option" :value="option">{{option}}</option>
        </select>
    </div>
</template>
<script>
export default {
    props: {
        select: {
            type: String,
            default: 'cuisine'
        },
        selectOptions: {
            type: Array,
            default: () => ['tacos', 'pizza', 'dim sum']
        }
    },
    methods: {
        updateValue(event){
            this.$emit('changeSelect', event.target.value)
        }
    }
}
</script>
<style lang="scss" scoped>

</style>