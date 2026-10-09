# Deutsch A1 – Mon Coach · version 2.0

Site personnel d’apprentissage de l’allemand A1 pour francophone. Le code fonctionne sur GitHub Pages, sans compte apprenant, abonnement, API ou serveur applicatif. Tous les fichiers de cette archive sont à placer à la racine de ton dépôt existant.

## Cette mise à jour

- Manuel personnel : 258 pages navigables après import de ton fichier `.deutsch`, agrandissement, notes, dernière page et repères de travail.
- Cahier par page : 363 repères d’activités avec aides méthodologiques en français ; réponses enregistrées séparément. Tu peux ajouter une fiche pour toute activité ou sous-question du manuel. La liste des repères ne constitue pas un inventaire exhaustif garanti : la page originale reste la référence.
- Introduction et 12 unités, explications françaises, vocabulaire, grammaire, dialogues, prononciation et missions de conversation.
- 312 cartes allemand/français. Les 104 premières expressions et leurs identifiants de révision restent compatibles avec la version précédente.
- 20 questions corrigées pour chaque unité et l’introduction : 260 questions au total. Trois bilans de 20 questions ; révision globale de 60 questions. Correction expliquée, score et meilleur résultat conservé.
- Mention **AUDIO** pour les activités d’écoute repérées ; référence exacte à lire sous le pictogramme du manuel. Champ pour noter le nom de ton fichier ou la piste. Table du CD apprenant accessible au PDF 257.
- Révisions : cartes après 1, 3, 7, 14 et 30 jours ; exercice difficile à revoir le lendemain ; exercice travaillé rappelé après 3 jours.
- Notes, réponses, références audio, scores et rappels inclus dans l’export de progression.

La méthodologie : comprendre → écouter → répéter → mémoriser → utiliser → tester → réviser. Travaille une page à la fois : lis la consigne, fais l’exercice du livre, écris tes réponses, puis reprends le point difficile le lendemain.

## Ce qui est corrigé

Les examens sont des exercices originaux du coach, alignés sur les thèmes du parcours ; ils ont une correction automatique et une explication. Quelques activités du manuel ont une aide corrigée vérifiée sur les pages et clairement présentée dans une section dédiée.

Les autres activités du livre utilisent un cahier de réponses et une grille d’autoévaluation. Le site ne contient pas un corrigé officiel complet du manuel et ne donne pas une note automatique à tes dialogues, rédactions ou réponses audio. Il ne faut pas interpréter « J’ai travaillé cet exercice » comme une validation par un correcteur. Le test global pédagogique n’est pas une certification ni une copie de l’examen officiel.

## Mettre à jour ton dépôt GitHub

1. Dans l’ancienne application, ouvre **Progrès → Exporter ma progression**, par précaution.
2. Télécharge puis extrais `Deutsch-A1-v2-Site-GitHub.zip`.
3. Ouvre ton dépôt `deutsche-`, onglet **Code**. Utilise **Add file → Upload files**, puis dépose tous les fichiers extraits à la racine, où se trouve déjà `index.html`. Envoie les fichiers, pas le ZIP et pas un dossier supplémentaire. Valide avec **Commit changes**.
4. Attends la réussite du déploiement GitHub Pages. Ouvre ton adresse habituelle, recharge, puis ferme et rouvre l’application installée si elle montre encore l’ancienne version. Le pied de page doit afficher **Version 2.0**.

Ne change pas les paramètres GitHub Pages d’un site qui fonctionne déjà. La mise à jour conserve la clé de sauvegarde et le cache des pages du manuel. Le nouveau service worker remplace seulement les fichiers du site. Exporte avant de supprimer des données dans les réglages du navigateur.

## Manuel et téléphone

Cette petite archive contient le site et ses aides ; elle ne contient pas les scans du livre. Si ton manuel est déjà importé dans l’application, tu le conserves. Sinon, dans **Manuel → Importer mon manuel**, choisis ton fichier personnel `manuel-personnel.deutsch`. Les packs fournis précédemment restent compatibles, y compris la version légère. Il faut l’importer séparément sur chaque appareil ; la synchronisation n’est pas automatique.

Garde ce fichier sur ton téléphone : si le navigateur efface son cache, tu peux le réimporter. Le manuel reste dans le cache local et n’est pas envoyé au serveur par cette application.

Pour installer : ouvre le site en HTTPS dans le navigateur et attends **Prêt hors connexion**. Sur Android, utilise le menu du navigateur pour installer / ajouter à l’écran d’accueil. Sur iPhone, ouvre dans Safari et utilise Partager → Sur l’écran d’accueil. L’application reste un site web installé ; ce n’est pas un APK.

## Tes audios

Tu possèdes les enregistrements : le site les indique avec **AUDIO**. Lis les questions avant de lancer ta piste dans ton lecteur audio du téléphone. Reviens dans le cahier, note la référence et écris tes réponses. Les fichiers audio du livre ne sont pas intégrés dans cette archive. La table du PDF 257 concerne le CD apprenant ; elle ne remplace pas les références des autres supports du manuel.

Les boutons **Écouter** des cartes et dialogues du coach utilisent une voix de synthèse allemande du téléphone. Ils sont indépendants de tes fichiers du manuel. Une voix allemande installée est nécessaire ; son fonctionnement hors ligne dépend du téléphone. Le dictaphone du coach permet de se réécouter, sans notation automatique.

## Repères du document

PDF 10 = livre p. 8. PDF 96 = livre p. 94. Le fichier fourni passe ensuite directement à la page imprimée 96, au PDF 97. Cette page imprimée 95 absente n’a pas été reconstituée. Les repères de chapitres et les numéros affichés tiennent compte de ce décalage. Les couvertures et la table des pistes ont des libellés particuliers.

## Fichiers

`index.html`, `style.css`, `content.js`, `reader.js`, `workbook-data.js`, `workbook.js`, `app.js`, `sw.js`, `manifest.webmanifest`, trois icônes et `.nojekyll` constituent le site. `README.md` et `LICENSE` fournissent la documentation. Aucun outil de compilation n’est nécessaire.

La navigation utilise des liens relatifs pour fonctionner dans le sous-dossier du dépôt. Les sauvegardes de progression restent sur l’appareil ; exporter puis importer permet de les transférer. Le cache du manuel et les audios personnels ne sont pas dans l’export de progression.

## Validation

Vérifications automatisées de génération des écrans et des 258 pages, réponses des 260 questions, réponses incorrectes, bilans, révisions espacées, validation des sauvegardes, conservation du format historique et import d’un pack de 258 pages. Les 12 ressources du site ont été vérifiées via un serveur local, avec récupération en cache sans réseau. Pas de test réalisé sur ton téléphone ni dans ton dépôt GitHub.

Le code et les aides pédagogiques originales sont sous licence MIT. Le manuel personnel et les enregistrements d’éditeur sont distincts de cette licence.
