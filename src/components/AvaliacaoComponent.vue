<template>
    <div>
        <div class="containner">
            <h1 class="titulo">Avaliações positivas</h1>
            <div class="nome">
                <img src="@/assets/avaliacao.PNG">
                <p>Roberto Garcia</p>
                <p>20/10/2023</p>
            </div>

            <div class="comentario">
                <b> Ótimo pneu, passou 2 dias do prazo mas chegou certinho </b>
                <p>Pneu tem um bom desempenho na estradas </p>
            </div>
        </div>


        <div class="containner">
            <div class="nome">
                <img src="@/assets/avaliacao.PNG">
                <p>Diego Fagundes</p>
                <p>27/09/2023</p>
            </div>

            <div class="comentario">
                <b> Excelente produto !! </b>
                <p>Gostei da facilidade para realizar o pedido e o prazo de entrega super rápido</p>
            </div>
        </div>


        <div class="containner">
            <div class="nome">
                <img src="@/assets/avaliacao.PNG">
                <p>Elaine Castro</p>
                <p>15/09/2023</p>
            </div>

            <div class="comentario">
                <b> Ótimo site </b>
                <p>Fiquei um pouco de receio pois estou acostumada a comprar apenas em sites famosos mas vi as avaliações e resolvi arriscar.</p>
                <p>Ótima empresa e cumpre com os prazos e qualidade do produto</p>
            </div>
        </div>


    </div>
</template>


<style scoped>
.containner {
    display: flex;
    flex-direction: column;
    padding-left: 20px;
    width: 100%;
}

.comentario {
    border-bottom: 1px solid rgb(207, 205, 205);
}

@media(max-width: 430px) {
    .containner {
        margin-top: 20px;
        padding-left: 10px;
    }
   .titulo {
    font-size: 18px;
    font-weight: bold;
   }
}
</style>