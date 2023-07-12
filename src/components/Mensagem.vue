<template>

<div class="alert alert-success" role="alert">
 {{ msg }}
</div>

</template>

<script>
export default {
    name: "Mensagem",

    props: {
        msg: String
    }
}


</script>