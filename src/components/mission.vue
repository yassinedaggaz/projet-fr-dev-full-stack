<template>
    <div>
        <span>
            <v-card width="90%" variant="text" class="mx-auto" flat>
                <v-card-item>
                    <v-card-title>Quelles sont les missions du développeur full stack?</v-card-title>
                    <!-- <v-card-subtitle>This is a subtitle</v-card-subtitle> -->
                </v-card-item>
                <v-card-text>
                    Le développeur full stack occupe de nombreuses responsabilités dans différents domaines : 
                </v-card-text><v-card-text style="padding-left: 40px !important;">
                    back-end, front-end, UX/UI, architecture et même infrastructure. 
                </v-card-text><v-card-text>
                    Il travaille sur chaque étape de conception d'un site ou d'une application, de son développement à sa production, faisant de lui un développeur multifonction.

                </v-card-text><v-card-text>
                    Dans le cadre de ses missions, le développeur full stack peut être amené à :
                </v-card-text>
                    <v-list-item v-for="(item, i) in items" :key="i" :value="item" style="min-height: 18px !important; height: max-content !important; padding: 0px 0px 0px 50px !important;">
                        <v-list-item-title v-text="'► ' + item.text"></v-list-item-title>
                    </v-list-item>
                <v-card-text>
                    Le rôle et les missions confiées au développeur full stack varient d'un poste à l'autre, en fonction des besoins de l'entreprise, du secteur d'activité dans lequel il évolue et de sa propre expertise.
                </v-card-text>
            </v-card>
        </span>
    </div>
</template>
  
<script>
    export default {
        data: () => ({
            items: [
                { text: 'Concevoir le cahier des charges du projet de développement web.' },
                { text: 'Identifier les moyens techniques et humains nécessaires.' },
                { text: 'Concevoir la structure du site (back-end) et son design (front-end).' },
                { text: "Développer des API ou interfaces de programmation d'applications."},
                { text: 'Créer des serveurs.' },
                { text: "Faire de l'intégration de contenus." },
                { text: 'Optimiser le référencement SEO.'},
                { text: "Vérifier la maintenance du site ou de l'application." },
                { text: 'Se tenir au courant des dernières innovations technologiques.'},
                { text: 'Traiter les erreurs techniques.'},
                { text: 'Prendre en charge la formation des utilisateurs.' },
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
.v-list-item{
    line-height: normal !important;
    font-family: Arial, Helvetica, sans-serif;
    font-weight: 100;
}
</style>