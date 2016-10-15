La fonction de test A/B dans CiviMail
==========================

La fonction A/B Testing de CiviMail vous donne la possibilité d’envoyer deux jeux de courriels de test à deux échantillons de destinataires aléatoires. Cette fonction permet d’étalonner et de valider le jeu de courriel qui sera finalement transmis, en fonction de la réaction des destinataires. CiviMail vous propose un jeu de métriques permettant d’analyser ces réactions.
Le présent chapitre présente les types de tests disponibles ainsi que la façon de les paramétrer.

Avant de débuter un Test A/B, assurez-vous que les destinataires ciblés soient bien définis dans une liste de diffusion. Pour en savoir plus la configuration d’une liste de diffusion, reportez-vous au chapitre *Groupes et Étiquettes*.

**Typologie des tests**

**Création d’un Test A/B**

Pour créer un Test A/B, sélectionner l’option de menu **Mailings > Nouveau Test A/B**. Dans l’écran de configuration, vous pouvez déterminer la campagne marketing correspondant à ce futur emailing (si tel est le cas). Vous devez, de même, indiquer le type de test à conduire (voir ci-dessus)

CiviMail propose trois types de tests différents :

-   Test relatif à la ligne **Objet du courriel**
-   Test relatif à la ligne **Expéditeur**
-   Test sur le **corps du courriel**


![image](../img/AB%20Testing.png)


Le deuxième écran (*Cibler* ou *Target*) vous permet de déterminer les destinataires de ces deux jeux de tests ainsi que le pourcentage de la distribution. Pour modifier le pourcentage il suffit de faire glisser les curseurs présents sur les barres horizontales qui, à leur tour, vont contrôler le pourcentage pour l’emailing final envoyé aux destinataires restant. Le total sera bien évidemment égal à 100%.

![image](../img/AB%20Testing%20Targeting.png)


Le troisième écran (*Composer* ou *Compose*) est contextuel et s’adapte en fonction du type de test à réaliser. Par exemple, si vous choisissez de réaliser un test relatif à la ligne *Expéditeur*, cet écran affichera deux lignes **Expéditeur** (Expéditeur (A) et Expéditeur (B)) :

![image](../img/AB%20Testing%20Compose%20Screen1.png)


si vous choisissez de réaliser un test relatif à la ligne **Objet**, vous aurez la possibilité de saisir deux sujets de courriels différents (Objet (A) et Objet (B)).

![image](../img/AB%20Testing%20by%20Subject1.png)


Si vous choisissez le test relatif aux corps d’emails différents, vous aurez alors un bouton *3. Compose (A)* et un bouton *4. Compose (B)* :

![image](../img/AB%20Testing%20by%20email1.png)


Choisissez un modèle de courriel existant. Une fois sélectionné et, les champs *Expéditeur* et *Objet* renseignés, **avant** d’envoyer le courriel final, faites un test en l’envoyant à un groupe de test ou à vous-même.

**Métriques**

À partir du moment où vos emailings de test sont terminés et envoyés, les résultats sont rendus disponibles. Pour y accéder, sélectionnez l’option de menu **Mailings > Gérer les Tests A/B**.
Dans le tableau de synthèse recensant tous les jeux de tests, cliquez l’option **Résultats** du test A/B que vous souhaitez analyser. Comme d’habitude, vous pouvez filtrer la liste affcihée via l’accordéon situé juste au-dessus de ce tableau.

L’écran de synthèse vous permet d’analyser les résultats de ce test. Plusieurs indicateurs sont présents avec, entre autres, le nombre de courriels bien arrivés, ouverts, de liens cliqués, de rebonds, de désinscription.
Vous pouvez, de même, en fonction des résultats, sélectionner le courriel qui sera finalement envoyé à vos destinataires.

**Le tableau recensant les jeux de tests**

![image](../img/AB%20Testing%20Results%20Page_1.png)



**L’écran de synthèse**

![image](../img/AB%20Testing%20Metrics.png)
