<template>
    <div>
        <span>
            <v-card width="90%" variant="text" class="mx-auto" flat>
                <v-card-title>Combien gagne un développeur web ?</v-card-title>
                <span>
                    <b>Le salaire d'un développeur web est variable.</b> S'il est salarié, son salaire dépend de son expérience et du type d'entreprise dans lequel il évolue. S'il est développeur web en freelance, ses revenus vont dépendre des compétences qu'il pourra mettre en avant et de la nature de la mission.
                </span> 
                <v-card-title>Voici les salaires moyens d'un développeur Full-Stack constatés à France et à Tunisie :</v-card-title>
                <table>
                    <thead>
                    <tr>
                        <th></th>
                        <th>Salaire/revenus à France</th>
                        <th>Salaire/revenus à Tunisie</th>
                    </tr>
                    </thead>
                    <tbody>
                    <tr>
                        <td style="background-color: #eaedfd; color: black;">Développeur Full-Stack salarié</td>
                        <td>2 500 € par mois en début de carrière <br/>
                            entre 3 400 € et 3 900 € en milieu et fin de carrière</td>
                        <td>1 500 TND par mois en début de carrière <br/>
                            entre 3 400 TND et 3 900 TND en milieu et fin de carrière
                        </td>
                    </tr>
                    </tbody>
                </table>
                <v-card-title>Voici les attentes salariales des candidats à l'offre Développeur Full Stack (Junior)</v-card-title>
                <span class="d-flex justify-center align-center"><img src="./../assets/RevenueJunior.png"/></span>
                <!-- <table>
                    <tr>
                        <td>Fourchette moyenne:</td>
                        <td>1244 - 1641 TND</td>
                    </tr>
                    <tr>
                        <td>Salaire moyen:</td>
                        <td>1443 TND</td>
                    </tr>
                    <tr>
                        <td>Salaire le plus bas:</td>
                        <td>700 TND</td>
                    </tr>
                    <tr>
                        <td>Salaire le plus élevé:</td>
                        <td>2500 TND</td>
                    </tr>
                </table> -->
            </v-card>
        </span>
    </div>
</template>
  
<script setup>
//
</script>
<style scoped>
span {
    display: flex;
    color: #FFFFFF;
    font-size: 18px;
    flex-wrap: wrap;
    text-align: justify !important;
    line-height: 40px;
}
.v-card-title {
    font-size: 24px !important;
    line-height: normal !important;
    padding-bottom: 5px !important;
    padding-top: 25px !important;
    margin-left: 10px;
    text-align: justify !important;
}
.v-card-text {
    font-size: 20px !important;
    line-height: normal !important;
    padding-bottom: 5px !important;
    padding-top: 5px !important;
    margin-left: 10px;
    text-align: justify !important;
}
thead{
    background-color: #3152e8;
}
table{
    width: 100%;
    text-align: center;
    font-weight: 500;
    border-spacing:0px
}

</style>