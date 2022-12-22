<template>
    <div>
        <span>
            <v-card-title>Quelle sont les Qualités et compétences nécessaires pour devenir développeur informatique ?</v-card-title>
            <v-card width="80%"  class="mb-auto" flat min-width="90%" style="background-color: transparent;">
                <v-carousel cycle height="400" hide-delimiter-background show-arrows="hover">
                    <v-carousel-item v-for="(title, i) in qualites" :key="i">
                        <v-sheet style="background-color: transparent;" height="100%">
                            <div class="d-flex fill-height justify-center align-center" style="color: #FFFFFF;">
                                <v-card width="90%" variant="outlined" class="mx-auto" flat>
                                    <v-card-item>
                                        <v-card-title>{{title}}</v-card-title>
                                    </v-card-item>
                                    <v-card-text>
                                        {{text[i]}}
                                    </v-card-text>
                                </v-card>
                            </div>
                        </v-sheet>
                    </v-carousel-item>
                </v-carousel>
            </v-card>
        </span>
    </div>
</template>
  
<script>
export default {
    data: () => ({
        text: [
            'Les missions techniques peuvent changer chaque jour. Le développeur full stack s’adapte à toutes les situations et trouve des solutions.',
            'Plus il connaît de langages informatiques, mieux il peut s’adapter. Principaux langages à maîtriser : HTML, CSS, PHP, JavaScript, SQL, jQuery, Java ou Node.JS.',
            'Il s’adapte aux principaux environnements de développement comme Symfony, CakePHP, Laravel, ou Bootstrap.',
            'Il sait utiliser les principaux systèmes de gestion comme WordPress, Magento ou Prestashop.',
            'Il est au courant des dernières évolutions et n’a pas peur d’investiguer pour trouver des solutions. « Il faut toujours être curieux et ne pas avoir peur de découvrir de nouvelles technologies ou de travailler sur des projets qui semblent compliqués »',
            'Il aime le jeu collectif. Il sait travailler avec des personnes qui ne connaissent rien au code. Il doit parfois collaborer avec des rédacteurs, des référenceurs, des designers, voire avec d’autres développeurs.'
        ],
        qualites: [
            'Adaptabilité :',
            'Maîtrise des principaux langages informatiques :',
            'Maîtrise des principaux frameworks :',
            'Maîtrise des principaux CMS :',
            'Curiosité :',
            'Esprit d’équipe :'
        ],
    }),
}
</script>
<style scoped>
span {
    display: flex;
    color: #FFFFFF;
    font-size: 18px;
    flex-wrap: wrap;
    text-align: justify !important;
    justify-content: center;
}

.v-card-title {
    font-size: 24px !important;
    line-height: normal !important;
    padding-bottom: 5px !important;
    padding-top: 5px !important;
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

.v-list-item {
    line-height: normal !important;
    font-family: Arial, Helvetica, sans-serif;
    font-weight: 100;
}
</style>