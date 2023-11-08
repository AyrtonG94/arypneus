<script setup>

</script>

<template>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css">

    <div class="form-containner">
        <div class="form-1">
            <form action="https://pay.sumup.com/b2c/XMZ1HY5FJM">
                <h2>Preencha os dados</h2>
                <div class="mb-3">
                    <label for="exampleInputEmail1" class="form-label">Nome</label>
                    <input type="text" class="form-control" id="exampleInputEmail1" aria-describedby="emailHelp" required>
                </div>

                <div class="mb-3">
                    <label for="exampleInputEmail1" class="form-label">CPF:</label>
                    <input type="number" class="form-control" id="exampleInputEmail1" aria-describedby="emailHelp" required maxlength="11">
                </div>

                <div class="mb-3">
                    <label for="exampleInputEmail1" class="form-label">Data de nascimento</label>
                    <input type="date" class="form-control" id="exampleInputEmail1" aria-describedby="emailHelp" required>
                </div>

                <div class="mb-3">
                    <label for="exampleInputEmail1" class="form-label">Email</label>
                    <input type="email" class="form-control" id="exampleInputEmail1" aria-describedby="emailHelp" required>
                    <div id="emailHelp" class="form-text">Clique em continuar para preencher o endereço de entrega e confirmar o pagamento.</div>

                </div>

               <div class="botao">
                    <button type="submit" class="btn btn-primary">Continuar</button>
                </div>
            </form>

            
        </div>


    </div>
</template>

<style>
.mb3 input {

}
@media(max-width: 430px) {
    .mb-3 {
        display: flex;
        flex-direction: column;
        align-items: center
    }

    
    .mb-3 input {
        width: 250px;

    }

    h2 {
        text-align: center;
        margin-bottom: 10px;
        font-family: Arial, Helvetica, sans-serif;
    }

    .botao {
        display: flex;
        justify-content: center;
        margin-bottom: 40px;
    }

    #emailHelp {
        font-size: 12px;
        text-align: center;
    }

}
</style>