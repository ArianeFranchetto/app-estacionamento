<template>
    <div>
        <form class="carro-form">
            <div class="mb-3">
                <label class="form-label">Nome:</label>
                <input type="text" class="form-control" style="width: 300px;" id="nome" v-model="nome"
                    placeholder="Informe o seu nome">
            </div>
            <div class="mb-3">
                <label class="form-label">Nome do Carro:</label>
                <input type="text" class="form-control" style="width: 300px;" id="nomeCarro" v-model="nomeCarro"
                    placeholder="Informe o seu carro">
            </div>
            <div class="mb-3">

                <label class="form-label">Horário de chegada:</label>
                <input type="text" class="form-control" style="width: 150px;" id="horario" v-model="horario"
                    placeholder="Informe o horário de chegada">
                <label class="form-label">Placa:</label>
                <input type="text" class="form-control" style="width: 150px;" id="placaCarro" v-model="placaCarro"
                    placeholder="Informe a placa">
            </div>

            <div class="form-text">Coloque todas as letras números.</div>

            <div class="mb-3 form-check">
                <input type="checkbox" class="form-check-input" id="concordoEmCompartilhar">
                <label class="form-check-label">Estou certo das informações acima.</label>
            </div>
            <button type="submit" class="btn btn-primary">Cadastrar</button>
        </form>
    </div>
</template>

<script>

export default {
    name: "CarroForm"
}
</script>

<style>
.carro-form {
    display: flex;
    align-items: center;
    flex-direction: column;
    

}


</style>