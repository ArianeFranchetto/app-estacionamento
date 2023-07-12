<template>
    <div id="carro-table">

        <nav class="navbar" style="border-radius: 10px; background-color: #e3f2fd; margin-top: 15px; padding: 15px;">
            <div class="container-fluid">
                <span class="navbar-text">
                    Nome da Pessoa:
                </span>
                <span class="navbar-text">
                    Nome do Carro:
                </span>
                <span class="navbar-text">
                    Placa do Carro:
                </span>
                <span class="navbar-text">
                    Horario de Entrada:
                </span>
                <span class="navbar-text">
                    Ações:
                </span>
            </div>
        </nav>


        <div id="carro-table-rows">

            <div class="carro-table-row">


                <div class="order-number"> </div>
                <div> teste </div>
                <div> teste</div>
                <div> teste</div>
                <div> teste</div>

                <div>

                    <select name="status" class="status">
                        <option value="">Status Carro </option>
                        <option> </option>
                    </select>

                    <button type="button" class="btn btn-danger">Deletar</button>



                </div>

            </div>

        </div>

    </div>
</template>

<script>
export default {
    name: "DashBoard"
}

</script>

<style scoped>
#carro-table {

    max-width: 1200px;
    margin: 0 auto;

}

#carro-table-heading,
#carro-table-rows .carro-table-row {
    display: flex;
    flex-wrap: wrap;
}

#carro-table-heading {
    font-weight: bold;
    padding: 12px;
    border-bottom: 3px solid rgba(53, 30, 180);
}

#carro-table-heading div,
.carro-table-row div {
    
    display: flex;
    flex-direction: row;
    justify-content: space-around;
    width: 100%;
}

.carro-table-row {
    width: 100%;
    padding: 12px;
    border-bottom: 1px solid rgba(53, 30, 180);

}

#carro-table-heading .order-id,
.carro-table-row .order-number {
    width: 5%;
}


select {
    padding: 10px 6px;
    margin-right: 12px;
}


</style>