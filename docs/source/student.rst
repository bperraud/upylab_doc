==================
Interface Etudiant
==================

Navigation
----------

Le bandeau du haut permet d'avoir accès aux informations sur votre compte et aussi à vous déconnecter.

Le bandeau de gauche permet de naviguer entre les rubriques ci-dessous. Cliquer sur le symbole :math:`\equiv` permet d'en réduire sa taille ou de le remettre à sa taille initiale.

Accueil
-------

Permet de chercher des cours ouverts auxquels vous pouvez vous inscrire et vous donne la liste des cours auxquels vous êtes déjà inscrits.

Rechercher un cours
~~~~~~~~~~~~~~~~~~~

Trois types de recherches de cours ouverts sont possibles :

- par mot-clé
- en cliquant sur ``Voir tous les cours``
- en cliquant sur ``Plus d'options`` pour faire une recherche par ``Titre ou mots clé``, ``Auteur`` ou ``Mnémonique`` du cours.

En cliquant sur un cours de la liste, vous pouvez voir sa description, ses informations de base et la liste, par chapitre, des exercices associés.

Vous n'avez accès qu'aux exercices associés à un cours auquel vous êtes inscrits. Pour avoir accès à tous les exercices du cours, vous devez cliquer sur l'intitulé du cours et ensuite vous y inscrire en cliquant sur le bouton ``S'inscrire au cours`` en haut à droite.

Mes cours
~~~~~~~~~

Donne la liste des cours auxquels vous êtes inscrits avec comme information pour chacun : ``Mnémonique``, ``Titre``, ``Professeur``, ``Progression``, ``Action``.

En cliquant sur l'oeil en pictogramme vous avez accès au cours et aux exercices associés (voir section : :ref:`realisation-dun-exercice`).

Liens Utiles
------------

Accès aux `modes d'emploi ainsi qu'aux vidéo des tutos <https://upylab2.ulb.ac.be/records>`__.

Mon compte
----------

Donne les information sur votre compte :

- Prénom
- Nom
- Nom d'utilisateur
- Adresse email

Vous permet également de changer de mot de passe (cliquer sur ``Changer de mot de passe``).

.. _realisation-dun-exercice:

Réalisation d'un exercice
-------------------------

Voir aussi : `Tutoriel sur lien utile <https://upylab2.ulb.ac.be/records>`__

Ayant cliqué sur le bouton (oeil) pour accéder à un cours auquel vous êtes inscrits, une liste d'exercices, découpée en chapitres, vous est proposée.

A gauche de chaque titre d'exercice, trois pictogrammes sont possibles :

- ``-`` gris qui signifie que vous n'avez pas tenter de solutionner l'exercice
- ❌ (croix rouge) qui signifie que vous avez tenté de solutionner l'exercice sans succès
- ✓ (coche vert) qui signifie que vous avez solutionné l'exercice

Pour essayer de solutionner un exercice, cliquez sur son nom dans la liste :

Fenêtre exercice
~~~~~~~~~~~~~~~~

On y trouve :

- Le titre de l'exercice
- L'auteur
- Le nombre d'essais que vous avez effectuer pour cet exercice (aucune limite n'est donné par l'outil sur le nombre d'essais par exercice)
- La date du dernier essai
- Résolu (oui ou non)
- Etiquettes donnant les compétences exercées dans l'exercice
- Enoncé : texte de l'énoncé
- Votre solution : sous fenêtre où vous devez mettre le code Python sensé solutionner l'exercice demandé et cliquer sur le bouton ``Valider``
- Conseils : qui seront affichés quand votre soumission sera solution à ce qui est demandé.
- Lorsque vous demandez de valider votre code, les résultats des tests sont affichés sur une colonne (en haut) à droite et l'exercice est validé ou non.

Principe
~~~~~~~~

Le principe consiste à lire l'énoncé de l'exercice concerné puis à résoudre le problème dans votre environnement de développement (IDE) favori. Une fois que vous vous êtes assurés que votre script répond aux exigences de l'énoncé, il faut le recopier dans la partie de fenêtre UpyLaB servant à cet effet (mini-fenêtre vide au départ, sinon qui contient votre dernière proposition de solution) pour le soumettre à évaluation en cliquant sur le bouton "Valider".

Quand l'utilisateur a cliqué sur le bouton "Valider", UpyLaB va demander à l'interpréteur Python 3 d'exécuter le code fourni. Il va ensuite comparer le résultat obtenu avec ce qui est attendu et le valider si les deux coïncident.

UpyLaB effectue un ou plusieurs tests selon les exercices, et ensuite, en fonction des résultats de ces tests, vous indique si le code soumis lui semble correct ou non par rapport à ce qui vous est demandé.

Aide
~~~~

Forum UpyLaB : Voir `le forum NSI le-juge-en-ligne-et-environnement-upylab <https://mooc-forums.inria.fr/moocnsi/>`__

ou dans la `FAQ du MOOC "Apprendre à coder avec Python" <https://upylab2.ulb.ac.be/pub/FAQ_mooc/>`__ (Attention certaines parties de la FAQ sont propres au MOOC).
