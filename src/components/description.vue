<template>
    <v-expansion-panels variant="accordion" v-model="panel" style="height: 88vh; ">
        <v-expansion-panel value=1  :style="panel==1 ? 'height: 84%;' : panel==2 || panel==3 ? 'height: 8%;' : 'height: 34%;'">
            <template v-slot:title> 
                <h3>
                    Description générale sur le développeur web : 
                </h3>
            </template>
            <template v-slot:text> 
                <span style="font-size: 19px !important; line-height: 40px !important;">
                Le développeur web est chargé de <b> créer des sites internet, des logiciels ou des applications</b> en suivant un cahier des charges qu’il définit selon les désirs et les contraintes fixées par son client. Pour se faire, il a alors le choix du langage de programmation et/ou de la technologie à utiliser (HTML, CSS, C++, Python, Javascript etc.).
                <br/>
                Avant de rendre son projet, il doit alors tester la solution qu’il compte proposer à son client. Il peut également être chargé de rédiger un support d’aide pour les futurs utilisateurs.
                <br/>
                Un <b>développeur peut se spécialiser</b>, notamment en devenant développeur back end  (les bases de données, les serveurs) ou développeur front end (comme le design d’un site).
                </span>
            </template>
        </v-expansion-panel>
        <v-expansion-panel value=2 :style="panel==2 ? 'height: 84%;' : panel==1 || panel==3 ?  'height: 8%; ' : 'height: 33%;'">
            <template v-slot:title> 
                <h3>
                    la différence entre un développeur Back-end et un développeur front-end : 
                </h3>
            </template>
            <template v-slot:text> 
                <span class="d-flex justify-center align-center">
                    <video controls style="width: 66%;"> 
                        <source src="../assets/frontvsback.mp4" type="video/mp4">
                        Your browser does not support the video tag.
                    </video></span>
            </template>
        </v-expansion-panel>
        <v-expansion-panel value="3" :style="panel==3 ? 'height: 84%;' : panel==1 || panel==2 ?  'height: 8%;': 'height: 33%;'">
            <template v-slot:title> 
                <h3>
                    Description générale sur le Développeur Full-Stack?
                </h3>
            </template>
            <template v-slot:text> 
                <span style="font-size: 19px !important; line-height: 40px !important;">
                    Le développeur full stack est un développeur touche-à-tout et complet, qui travaille à la fois côté
                    Backend et Frontend. 
                <br/>
                    Le front-end est responsable de l'aspect visuel du site Web, tandis que le
                    back-end est responsable de la logique et de l'infrastructure du site.
                <br/>
                    Il connaît toute la chaîne de développement d’un logiciel ou d’un site web et
                    est à l’aise avec plusieurs langages et technologies.
                <br/>
                    Par définition, être « full stack » signifie travailler sur « toute la stack ».
                <br/>
                    Par extension, on peut dire que le développeur fullstack réalise ce que plusieurs développeurs
                    front-end et back-end font en équipe.
                <br/>
                    Ses connaissances vis-à-vis de l’ensemble des couches de la stack technique, de la pile de
                    technologie d’un projet, lui permettent de créer un site ou une app de A à Z.
                </span>
            </template>
        </v-expansion-panel>
        </v-expansion-panels>
</template>
  
<script>
export default {
    data() {
        return {
            dialog: false,
            panel:"1"
        }
    },
}
</script>
<style>
.v-expansion-panel{
   background-color: transparent; color: white;
}
</style>
  