# OC-P07-Analyser_les_indicateurs_égalité_femme_homme


Analyse des indicateurs de l'égalité femme/homme avec Knime. Retrouver dans ce repo le Workflow Knime (*Projet 7.knwf*). Les données nécéssaires à la réalisation de ce projet ont été enregistrées dans le dossier data du workflow ce qui permet d'y faire appel via un chemin relatif et de pouvoir l'exporter sans problème.
Ce Workflow comprend différents nodes permettant l'analyse des différents indicateurs ainsi que des méthanodes et component permettant l'utilisation de widgets et rendant les illustrations interactives.

## Scénario du projet
Vous êtes data analyst dans un cabinet de consultant spécialisé dans la transformation digitale des entreprises. Le cabinet compte déjà plus de 150 salariés et est en plein développement. Dans ce contexte économique, le recrutement de consultants expérimentés devient un véritable enjeu stratégique.

Ce matin, en arrivant à votre poste de travail, vous recevez un courriel de Laura, la directrice des ressources humaines avec en copie Vincent, contrôleur de gestion sociale :
### Besoins de l'entreprise:
Chaque année avant le 1er mars, les entreprises d’au moins 50 salariés doivent calculer et publier sur leur site Internet leur index de l’égalité femmes-hommes. Comme tu le sais, nous sommes en phase de croissance importante, et il me semble important d’avoir une politique volontariste pour développer l’égalité femmes-hommes dans notre cabinet. Cela nous permettra d’améliorer notre marque employeur et d’attirer plus facilement des talents.

J’aimerais donc que tu aides Vincent à automatiser la création d’un rapport diagnostique sur l’égalité professionnelle femmes hommes. Pour cela, il m’a suggéré l’utilisation de KNIME. J’aurais donc besoin que, à partir des fichiers des données (en pièce jointe) issues de notre Système d’Informations des Ressources Humaines (SIRH), tu lui prépares un workflow avec le logiciel KNIME qui crée les graphiques du diagnostic.
[Le site du ministère du Travail](https://travail-emploi.gouv.fr/IMG/pdf/guide_egalite_tpe_pme_2021.pdf) donne de nombreuses informations pour établir un diagnostic. Regarde notamment le document de [présentation de lʼoutil Diagnostic Égalité](https://s3-eu-west-1.amazonaws.com/static.oc-static.com/prod/courses/files/parcours-data-analyst/Pre%CC%81sentation+outil+Diagnostic+E%CC%81galite%CC%81.pdf) dans lequel tu trouveras une liste des indicateurs à surveiller. Pas besoin de tous les extraire, mais dans un premier temps choisis-en au minimum 5 dans la liste que ton workflow devra générer.

Aussi, je te rappelle que les données issues du SIRH ne sont pas anonymisées, alors il faudra les traiter pour que ton rapport [respecte le RGPD](https://www.cnil.fr/cnil-direct/question/quels-sont-les-grands-principes-des-regles-de-protection-des-donnees?visiteur=part).

Dès que tu auras terminé, nous ferons un point ensemble avec Vincent pour que tu nous présentes le fonctionnement de ton workflow ainsi que les graphiques générés.
### **Livrable:**
1. Workflow Knime.