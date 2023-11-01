<script setup>
    import AvaliacaoComponent from './AvaliacaoComponent.vue';
</script>

<template>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@4.0.0/dist/css/bootstrap.min.css"
        integrity="sha384-Gn5384xqQ1aoWXA+058RXPxPg6fy4IWvTNh0E263XmFcJlSAwiGgFAW/dAiS6JXm" crossorigin="anonymous">
    <div class="principal">
        <img src="pneu.jpg" alt="pneu">

        <div class="resumo">
            <p> <h2>Pneu Formula by Pirelli Aro 15 Formula Evo 195/60R15 88H </h2></p>
            <p> Marca: Pirelli - Cód: 41376</p>
            <p> <h2>R$ 389,90</h2> à vista no PIX </p>
            <p>ou em até 12x de R$ 35,90 sem juros</p>

            <button>COMPRAR</button>
        </div>
    </div>

    <div class="tabela-container">
        <h1>Detalhes técnicos</h1>
        <div class="tabela">
            <table class="table table-striped">
                <tbody>
                    <tr>
                        <td>Marca</td>
                        <td>FORMULA</td>
                    </tr>
                    <tr>
                        <td>Fabricante</td>
                        <td>PIRELLI</td>
                    </tr>
                    <tr>
                        <td>Modelo</td>
                        <td>FORMULA EVO</td>
                    </tr>

                    <tr>
                        <td>Medida</td>
                        <td>195/60R15</td>
                    </tr>

                    <tr>
                        <td>Largura</td>
                        <td>195mm</td>
                    </tr>

                    <tr>
                        <td>Perfil</td>
                        <td>60%</td>
                    </tr>

                    <tr>
                        <td>Aro</td>
                        <td>15</td>
                    </tr>

                    <tr>
                        <td>Modelo</td>
                        <td>FORMULA EVO</td>
                    </tr>

                    <tr>
                        <td>Diâmetro total em mm</td>
                        <td>615.0</td>
                    </tr>

                    <tr>
                        <td>Índice de peso</td>
                        <td>88 - 560 kg</td>
                    </tr>

                    <tr>
                        <td>Índice de velocidade</td>
                        <td>H - 210 km/h</td>
                    </tr>

                    <tr>
                        <td>RFT = RunFlat</td>
                        <td>NÃO</td>
                    </tr>

                    <tr>
                        <td>Tipo de construção</td>
                        <td>RADIAL</td>
                    </tr>

                    <tr>
                        <td>Peso</td>
                        <td>7.88</td>
                    </tr>

                    <tr>
                        <td>Extra Load</td>
                        <td>NÃO</td>
                    </tr>

                    <tr>
                        <td>Protetor de bordas</td>
                        <td>NÃO</td>
                    </tr>

                    <tr>
                        <td>Sidewall</td>
                        <td>BSW LETRAS PRETAS</td>
                    </tr>

                    <tr>
                        <td>Tipo de terreno</td>
                        <td>HT</td>
                    </tr>

                    <tr>
                        <td>Tipo de Montagem</td>
                        <td>SEM CÂMARA</td>
                    </tr>

                    <tr>
                        <td>Desenho</td>
                        <td>Assimétrico</td>
                    </tr>

                    <tr>
                        <td>Garantia</td>
                        <td>5 anos Contra Defeito de Fabricação</td>
                    </tr>

                    <tr>
                        <td>Observações</td>
                        <td>Produto novo,Imagem meramente ilustrativa</td>
                    </tr>

                    <tr>
                        <td>Nota</td>
                        <td>4.8 /5</td>
                    </tr>
                    
                </tbody>
            </table>
        </div>
    </div>

    <AvaliacaoComponent></AvaliacaoComponent>
</template>

<style scoped>
body {
    font-family: Arial, Helvetica, sans-serif;
}
.principal {
    display: flex;
}

.resumo {
    border: 1px solid rgb(248, 246, 246);
}

button {
    background-color: green;
    color: white;
    text-shadow: 0 0 4px #ccc8c8;
    font-size: 15px;
    height: 50px;
    width: 300px;
    border-radius: 10px;
}

img {
    height: 400px;
}
</style>