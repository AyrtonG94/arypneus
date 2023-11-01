<template>
    <div>
        <div class="containner">
            <h1>Avaliações positivas</h1>
            <div class="nome">
                <img src="avaliacao.PNG">
                <p>Roberto Garcia</p>
                <p>20/10/2023</p>
            </div>

            <div class="comentario">
                <b> Ótimo pneu demora um pouco pra chegar mais chega </b>
                <p>Pneu bom bom desempenho na estradas </p>
            </div>
        </div>


        <div class="containner">
            <div class="nome">
                <img src="avaliacao.PNG">
                <p>Diego Fagundes</p>
                <p>15/09/2023</p>
            </div>

            <div class="comentario">
                <b> Excelente produto !! </b>
                <p>Gostei da facilidade para realizar o pedido e o prazo de entrega super rápido</p>
            </div>
        </div>


        <div class="containner">
            <div class="nome">
                <img src="avaliacao.PNG">
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
</style>