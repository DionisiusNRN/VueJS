<template>
    <span>{{ this.prefix + Number.parseFloat(this.value).toFixed(this.precision) }}</span>
</template>

<script>
export default {
    props: { // tipe data yg dimasukkan harus sesuai dengan type
        // default value berfungsi utk meminilamisir kesalahan pada saat mendeklarasikan nilai pada props
        value: Number,
        prefix: {
            type: String,
            default: 'Rp'
        },
        precision: {
            type: Number,
            default: 2
        }
    },
}
</script>