<template>
    <div>Branding Page</div>
</template>

<script>
export default {
    data() {
        return {};
    },
    mounted() {
        let loader = this.$loading.show({
            // Optional parameters
            container: this.fullPage ? null : this.$refs.formContainer,
            canCancel: true,
            onCancel: this.onCancel,
        });
        // simulate AJAX
        setTimeout(() => {
            loader.hide();
        }, 2000);
    },
};
</script>

<style lang="scss">
</style>
