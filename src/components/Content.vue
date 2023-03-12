<template>
     <div>
        <Navigation/>
      <v-card tile class="back" height="200">
      </v-card>
   <!-- infos -->
          <v-card tile flat class="mx-6 my-6">
            <v-card class="mx-2 my-2 px-2 py-2 confirm-card">
                <v-card-text>
                <h2 class="titre">1. Objet</h2>
                <p>Cette méthode est destinée à déterminer la teneur en constituants non sulfonés dans les sulfates d'alcool gras ainsi que dans les acides sulfoniques d'alkylbenzène et les pâtes de LAS. Elle peut être utilisée pour les teneurs à partir de 0,1 %.</p>
                </v-card-text>
            </v-card>
            <v-card class="mx-2 my-2 px-2 py-2 confirm-card">
                <v-card-text>
                <h2 class="titre">2. Domaine d'application</h2>
                <p>Cette procédure s’applique au laboratoire Henkel Reghaia.</p>
                </v-card-text>
            </v-card>
             <v-card class="mx-2 my-2 px-2 py-2 confirm-card">
                <v-card-text>
                <h2 class="titre">3. Document de Référence</h2>
                 <v-list-item two-line>
                    <v-list-item-content>
                        <v-list-item-title><strong>- ISO 9000 :</strong></v-list-item-title>
                        <v-list-item-subtitle>Systèmes de management de la qualité — Principes essentiels et vocabulaire.</v-list-item-subtitle>
                        <v-list-item-title><strong>- ISO 9001 :</strong></v-list-item-title>
                        <v-list-item-subtitle>Systèmes de management de la qualité — Exigences.</v-list-item-subtitle>
                        <v-list-item-title><strong>- ISO 9002 :</strong></v-list-item-title>
                        <v-list-item-subtitle>Systèmes de management de la qualité — Lignes directrices pour l’application de l’ISO 9001:2015.</v-list-item-subtitle>
                    </v-list-item-content>
                </v-list-item>
                </v-card-text>
            </v-card>
            <v-card class="mx-2 my-2 px-2 py-2 confirm-card">
                <v-card-text>
                <h2 class="titre">4. Définitions et Abréviations</h2>
                <p>•LAS: Linear alkylbenzene sulfonate (alkybenzène sulfonate linéaire). <br>•FAS: Fatty alcohol sulfate (sulfate d'alcool gras).</p>
                </v-card-text>
            </v-card>
             <v-card class="mx-2 my-2 px-2 py-2 confirm-card">
                <v-card-text>
                <h2 class="titre">5. Responsabilités et Autorités</h2>
                <p>Le technicien contrôle qualité est responsable sur l’analyse. <br> Le responsable laboratoire est responsable sur la validation des méthodes.</p>
                </v-card-text>
            </v-card>
             <v-card class="mx-2 my-2 px-2 py-2 confirm-card">
                <v-card-text>
            <h2 class="titre">6. Processus</h2>
                <v-list-item>
                <v-list-item-content>
                    <v-list-item-title>1 - 	Résumé de la méthode</v-list-item-title>
                    <v-list-item-subtitle>Les constituants non sulfonés sont extraits du tensioactif au moyen d'un solvant et sont déterminés par gravimétrie après évaporation du solvant.</v-list-item-subtitle>
                    <v-list-item-title>2 - 	Réactifs</v-list-item-title>
                        <v-list-item>
                        <v-list-item-content>
                          <v-list-item-title>•Ethanol, 96 vol.-%, qualité analytique.</v-list-item-title>
                          <v-list-item-title>•Ethanol, 60 vol.-%.</v-list-item-title>
                          <v-list-item-title>•Ether de pétrole, point d'ébullition 30 - 50 °C (p. ex. Merck 101786).</v-list-item-title>
                          <v-list-item-title>•Sulfate de sodium, anhydre.</v-list-item-title>
                          <v-list-item-title>•Solution aqueuse d'hydroxyde de sodium, 30 %.</v-list-item-title>
                          <v-list-item-title>•Solution de phénolphthaléine, 1 % dans l'éthanol.</v-list-item-title>
                        </v-list-item-content>
                        </v-list-item> 
                    <v-list-item-title>3 - 	Appareillage</v-list-item-title>
                        <v-list-item>
                        <v-list-item-content>
                          <v-list-item-title>•Ampoules à décanter, 500 ml avec bouton rodé.</v-list-item-title>
                          <v-list-item-title>•Balance d'analyse.</v-list-item-title>
                          <v-list-item-title>•Equipement de laboratoire usuel .</v-list-item-title>
                        </v-list-item-content>
                        </v-list-item>
                    <v-list-item-title>4 - 	Procédé</v-list-item-title> 
                        <v-list-item>
                        <v-list-item-content>
                          <v-list-item-title>•Peser environ 5 g de la substance à analyser à 0,001 g près dans un bécher de 250 ml au moyen d'une balance d'analyse.</v-list-item-title>
                          <v-list-item-title>•Ajouter environ 50 ml d'eau d’ionisée chauffée à environ 70 °C. Après dissolution complète, ajouter 75 ml d'éthanol (96 vol.-%) tout en agitant.</v-list-item-title>
                          <v-list-item-title>•Transférer dans une ampoule à décanter de 500 ml et rincer avec de l'éthanol à 60 % jusqu'à atteindre un volume d'environ 300 ml.</v-list-item-title>
                          <v-list-item-title>•Contrôler à la phénolphtaléine si la solution est légèrement alcaline et ajuster, si nécessaire (en particulier en cas d'acides sulfoniques), avec une solution d'hydroxyde de sodium à 30 %.</v-list-item-title>
                          <v-list-item-title>•Laisser refroidir, ajouter 50 ml d'éther de pétrole, agiter fortement pendant 30 s et attendre la séparation des phases. (Pendant le mélangeage des deux phases, il se forme du gaz ; le laisser s'échapper à deux ou trois reprises.)</v-list-item-title>
                          <v-list-item-title>•Transférer la phase inférieure dans une seconde ampoule de décantation de 500 ml et extraire quatre autres fois avec 25 ml d'éther de pétrole. Collecter les phases d'éther de pétrole dans une ampoule de décantation propre et sèche, veiller à chaque fois à ce qu'aucune partie de la phase aqueuse (phase inférieure, rose) ne soit transférée avec la phase d'éther de pétrole.</v-list-item-title>
                          <v-list-item-title>•Laver les phases d'éther de pétrole combinées avec 50 ml d'éthanol à 60% et sécher plus de 10 g de sulfate de sodium anhydre pendant 30 min. en mélangeant.</v-list-item-title>
                          <v-list-item-title>•Filtrer à travers un filtre en papier et collecter le filtrat dans un bécher en verre de 150 ml qui a été séché auparavant dans une étuve à 100 °C, refroidi dans un dessiccateur et pesé. Laver cinq fois le sulfate de sodium avec 10 ml d'éther de pétrole.</v-list-item-title>
                          <v-list-item-title>•Dans un bain-marie ou sur une plaque chauffante, évaporer la majeure partie du solvant presque jusqu'à dessiccation. Eliminer soigneusement le reste de solvant au moyen d'un jet d'air et laisser refroidir dans un dessiccateur.</v-list-item-title>
                          <v-list-item-title>•Peser, chauffer à nouveau doucement tout en appliquant un jet d'air et repeser après refroidissement dans le dessiccateur.</v-list-item-title>
                        </v-list-item-content>
                        </v-list-item>
                      <v-list-item-subtitle>Le poids est considéré comme étant constant lorsque deux pesées successives ne divergent pas de plus de 1 mg.</v-list-item-subtitle>
                      <v-list-item-title>5 - 	Calculs et expression des résultats</v-list-item-title> 
                      <v-list-item-subtitle><strong> 5.1 - Calculs </strong></v-list-item-subtitle> 
                      <v-list-item-subtitle>Calculer le résultat comme suit :</v-list-item-subtitle> 
                      <v-list-item-subtitle>US = ((B-T) &#8725; W) * 100</v-list-item-subtitle> 
                      <v-list-item-subtitle>US = teneur en constituants non sulfonés [ % ]. <br> B = poids du bécher plus les constituants non sulfonés [ % ]. <br> T = poids du bécher vide [ g ]. <br> W = poids de l&#39;échantillon [ g ].</v-list-item-subtitle> 
                      <v-list-item-subtitle><strong> 5.2 Expression des résultats </strong></v-list-item-subtitle> 
                      <v-list-item-subtitle>Le résultat est exprimé en tant que constituants non sulfonés en pourcentage avec deux chiffres significatifs en se référant à cette méth8 Précision <br>Les résultats d&#39;une détermination sextuple des constituants non sulfonés dans un échantillon de sulfate d&#39;alcool gras sont indiqués ci-après:</v-list-item-subtitle> 
                      <v-list-item-subtitle>Nombre de mesures: N = 6</v-list-item-subtitle> 
                      <v-list-item-subtitle>Valeur moyenne: x&#772 = 0.4 %</v-list-item-subtitle> 
                      <v-list-item-subtitle>Ecart standard: &#963;<sub>n-1</sub>  = 0.03 %</v-list-item-subtitle> 
                      <v-list-item-subtitle>Coefficient de variation: V = 7.6 % rel.</v-list-item-subtitle> 
                      <v-list-item-title>6 - 	Sécurité</v-list-item-title>
                       <v-row>
                        <v-col cols="4" md="3">
                            Ethanol 
                        </v-col>
                        <v-col cols="4" md="3">
                            facilement inflammable <br> R: 11 <br> S: (2)-7-16
                        </v-col>
                    </v-row>

                    <v-row>
                        <v-col cols="4" md="3">
                            Ether de pétrole
                        </v-col>
                        <v-col cols="4" md="3">
                            facilement inflammable <br> R: 12 <br> S: (2)-9-16-29-33
                        </v-col>
                    </v-row>

                    <v-row>
                        <v-col cols="4" md="3">
                            Hydroxyde de sodium, 30 %
                        </v-col>
                        <v-col cols="4" md="3">
                            corrosif <br> R: 35 <br> S:(1/2)-26/37/39-45
                        </v-col>
                    </v-row>

                     <v-row>
                        <v-col cols="4" md="3">
                            Phénolphthaléine, 1% dans l&#39;éthanol
                        </v-col>
                        <v-col cols="4" md="3">
                            facilement inflammable <br> R: 11 <br> S: (2)-7-16
                        </v-col>
                    </v-row>
                    <v-list-item-subtitle>Pour de plus amples informations, veuillez consulter les instructions de sécurité locales correspondantes.</v-list-item-subtitle> 
                    <v-list-item-title>7 - 	Remarques</v-list-item-title>
                    <v-list-item-subtitle>Au lieu d&#39;utiliser un jet d&#39;air, vous pouvez placer le bécher dans une étuve à 60 °C pendant 30 - 40 min. Après refroidissement dans le dessiccateur, le bécher est pesé et la procédure est répétée jusqu&#39;à ce qu&#39;un poids constant soit atteint.</v-list-item-subtitle>
                </v-list-item-content>
                </v-list-item>
                </v-card-text>
            </v-card>
              <v-card class="mx-2 my-2 px-2 py-2 confirm-card">
                <v-card-text>
                    <h2 class="titre">7. Annexes</h2>
                 <v-simple-table>
                    <template v-slot:default>
                        <thead>
                            <tr>
                                <th class="text-left white--text tab"> Enregistrement </th>
                                <th class="text-left white--text tab"> Code </th>
                                <th class="text-left white--text tab"> Localisation </th>
                                <th class="text-left white--text tab"> Support </th>
                                <th class="text-left white--text tab"> Durée de conservation </th>
                            </tr>
                        </thead>
                        <tbody>
                            <tr v-for="item in things" :key="item.Enregistrement">
                                <td>{{ item.Enregistrement }}</td>
                                <td>{{ item.Code }}</td>
                                <td>{{ item.Localisation }}</td>
                                <td>{{ item.Support }}</td>
                                <td>{{ item.Durée}}</td>
                            </tr>
                        </tbody>
                    </template>
                </v-simple-table>
                </v-card-text>
            </v-card>
           </v-card>
             <!-- Footer -->
            <v-footer flat bottom padless>
                <v-col><strong>PR SHEQ VR A.5-01– Procédure de Veille Réglementaire</strong> <br> <div class="primary--text"> Propriété exclusive de HENKEL Algérie Unité de Production Réghaia. <br> Toute reproduction intégrale ou partielle ainsi que son utilisation par, ou la communication à, des tiers, sans accord préalable écrit de l’auteur est illicite.</div> Le R-SMI est responsable de la gestion et l’application de cette procédure.</v-col>
            </v-footer>
    </div>
</template>

<script>
  export default {
    name: 'HelloWorld',

    data: () => ({
         things: [
          {
            Enregistrement: 'Fiche de suivi incident qualité',
            Code: 'SD SHEQ TNC 4.3.12-10',
            Localisation: 'R-SMI SharePoint /REG SMI',
            Support: 'Fichier électronique',
            Durée: '03 ans'
          },
          {
            Enregistrement: ' ',
            Code: ' ',
            Localisation: 'R-SMI SharePoint /REG SMI',
            Support: 'Fichier électronique',
            Durée: '03 ans'
          },
          {
            Enregistrement: ' ',
            Code: ' ',
            Localisation: 'R-SMI SharePoint /REG SMI',
            Support: 'Fichier électronique',
            Durée: '03 ans'
          },
          {
            Enregistrement: ' ',
            Code: ' ',
            Localisation: 'R-SMI SharePoint /REG SMI',
            Support: 'Fichier électronique',
            Durée: '03 ans'
          },
          {
            Enregistrement: ' ',
            Code: ' ',
            Localisation: 'R-SMI SharePoint /REG SMI',
            Support: 'Fichier électronique',
            Durée: '03 ans'
          },
          {
            Enregistrement: ' ',
            Code: ' ',
            Localisation: 'R-SMI SharePoint /REG SMI',
            Support: 'Fichier électronique',
            Durée: '03 ans'
          },
          {
            Enregistrement: ' ',
            Code: ' ',
            Localisation: 'R-SMI SharePoint /REG SMI',
            Support: 'Fichier électronique',
            Durée: '03 ans'
          }
        ]

    }),
  }
</script>
<style scoped>
.confirm-card {
  overflow: hidden;
}
.titre{
    color: #ff0011;
}
.back{
    background: url('../../public/labo3.jpg');
}
.tab{
  background-color: #fa3722;
}
</style>