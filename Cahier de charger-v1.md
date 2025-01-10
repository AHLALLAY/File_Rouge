># _**Système de gestion d'une école privée**_

L'application web est une plateforme centralisée conçue pour simplifier et optimiser la gestion administrative, pédagogique et financière d'une école privée au Maroc, notamment pour les niveaux primaire et pré-primaire. Elle permet aux administrateurs, enseignants, parents et élèves d'interagir de manière efficace et transparente, tout en automatisant les tâches répétitives et en fournissant des outils de suivi et d'analyse.

# **Problématique**
Les écoles privées au Maroc, en particulier celles dédiées aux niveaux primaire et pré-primaire, font face à plusieurs défis :

1. **Gestion manuelle et chronophage** : Les processus administratifs (inscriptions, suivi des notes, gestion des paiements) sont souvent effectués manuellement, ce qui entraîne des erreurs et une perte de temps.

2. **Manque de communication** : La communication entre les enseignants, les parents et l'administration est souvent inefficace, ce qui nuit au suivi des élèves.

3. **Difficulté de suivi des performances** : Les enseignants et les parents ont du mal à suivre les progrès des élèves en temps réel.

4. **Gestion financière complexe** : Le suivi des frais de scolarité, des paiements et des rapports financiers est souvent désorganisé.

5. **Absence de centralisation des données** : Les informations sur les élèves, les enseignants et les classes sont dispersées, ce qui rend leur accès et leur gestion difficiles.

# **Solutions**
L'application web propose des solutions innovantes pour résoudre ces problèmes :

1. **Automatisation des processus administratifs**
    * **Inscriptions en ligne** : Les parents peuvent inscrire leurs enfants via une plateforme numérique, réduisant ainsi les délais et les erreurs.

    * **Gestion centralisée des données** : Toutes les informations (élèves, enseignants, classes) sont stockées dans une base de données unique et accessible.

2. **Amélioration de la communication**
    * **Messagerie intégrée** : Une messagerie permet aux enseignants, parents et administration d'échanger en temps réel.

    * **Notifications automatiques** : Les parents reçoivent des alertes pour les absences, les retards, les événements scolaires et les bulletins de notes.

3. **Suivi des performances des élèves**
    * **Saisie des notes en ligne** : Les enseignants peuvent saisir les notes directement dans l'application.

    * **Bulletins de notes numériques** : Les parents peuvent consulter les résultats de leurs enfants à tout moment.

    * **Statistiques et rapports** : L'application génère des rapports sur les performances des élèves pour aider les enseignants et les parents à identifier les points à améliorer.

4. **Gestion financière simplifiée**
    * **Suivi des paiements** : L'application permet de suivre les frais de scolarité et les paiements en ligne.

    * **Rapports financiers** : Des rapports automatisés aident l'administration à gérer les finances de l'école.

5. **Centralisation des données**
    * **Base de données unique** : Toutes les informations sont stockées dans un système centralisé, ce qui facilite leur accès et leur gestion.

    * **Tableau de bord interactif** : Les administrateurs et les enseignants ont accès à un tableau de bord pour visualiser les données clés (effectifs, performances, finances).

# **utilisateur**

## _Personnelles_
> __Admin__
1. Se connecter avec un email fixe.
2. Gérer les Personnelles :
    * Ajouter un personel _(Nom, prenom, date de naissance, address, diplôme, role, photo)_.
    * Suspend un personnel.
    * (Soft Delete) d'un personnel en cas de se quiter.
3. Gérer les élèves :
    * Générer les emplois de temps.
3. Consulter les rapports :
    * Afficher les absences des personnelles.
4. Gérer les transport.

> __Secrutaire__
1. Gérer les Documents :
    * Scanner les piece de justifications.
    * Imprimer des attestation.
    * Imprimer des relever de note.
    * (Soft Delete) d'un élève en cas de se quiter.

> __Professeur__
1. Se connecter :
    * Les coordonnées de connection vient de l'admin.
2. Noter les Absences.
3. Noter les Activités dans la classe _(cahier de text numérique)_ :
    * Le cours effectuer _(page, date, type)_.
    * Evaluations _(cours, date, durée)_.
4. Les documents pédagogique.
5. Demande 

## _Parents_
1. Avant d'entrer à l'école :
    * Consulter la page Home en cas d'un visiteur.
    * Envoyer demande d'inscrire un nouvelle enfant _(nom, prenom, niveau Scolaire, date de naissance, photo)_.
    * Demande d'inscription sera automatiquement  acceptée à condition de ne pas passer la capacité de maximale.
2. Après avoir rejoint l'école :
    * Consulter les activités à domicile de leur enfants.
    * Consulter les notes de leur enfants.

## _Elèves_
1. Se connecter :
    * Afficher les activités à domicile.
    * Afficher leur notes.
    * Afficher leur absences.



## **page**
1. Accueil :
    * Section hero : _paragraph de bienvenue avec un carrousel d'images presenter l'école._
    * Section informations _(l'équipe pédagogique, capacité maximale ...)_.
    * Section de demande de Stage.
    * Section pour afficher les offres d'emploi ou de stage.
    * Section de demande d'inscription.
2. Inscription :
    * Information demander : _nom complete, naissance, image_.

3. login
4. Admin
5. Professeur
6. Secrutaire