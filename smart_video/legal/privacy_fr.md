---
title: Politique de confidentialité
---

# Politique de confidentialité

**Dernière mise à jour :** 2026-10-13 · **Entrée en vigueur :** 2026-10-13

## 1\. Qui nous sommes

Smart Video est un lecteur multimédia intelligent local-first (Stocké localement en priorité) pour apprenants en langues (« l'Application »). Le responsable du traitement de vos informations personnelles est **songshangkun** (« nous »), joignable à l'adresse **中国河南省郑州市高新区科学大道银屏路正弘高新数码港熙园**.

Pour toute question, demande ou réclamation relative à la confidentialité, contactez-nous à **13808875@qq.com**.

## 2\. En résumé

  * Votre bibliothèque multimédia, vos sous-titres, vos notes et vos dossiers d'étude résident **sur votre appareil**. Nous n'exploitons aucun système de compte et aucun serveur back-end ne stocke vos données d'étude.
  * Nous **ne vendons pas** vos informations personnelles et ne les utilisons **pas** à des fins de publicité comportementale.
  * Cette version de l'Application **ne contient aucun SDK publicitaire ni aucun SDK d'analyse**.
  * L'accès à la photothèque et aux fichiers est **facultatif** et n'est utilisé que lorsque vous importez ou exportez des médias. Nous n'accédons jamais à l'appareil photo, au microphone ou à votre position.
  * Les fonctions d'IA envoient le texte que vous sélectionnez à un **point de terminaison LLM que vous configurez vous-même** — voir la section 4. La reconnaissance vocale sur l'appareil ne quitte jamais votre appareil.



## 3\. Informations que nous traitons

Comme l'Application est de type local-first, la plupart des informations ne quittent jamais votre appareil.

### 3.1 Informations stockées sur votre appareil

Quoi | Pourquoi | Où elles restent  
---|---|---  
Entrées de la bibliothèque multimédia : références de fichiers, noms, URL importées / liens HLS, position de lecture | Pour vous permettre de rouvrir et de reprendre vos médias d'étude | Base de données sur l'appareil (sandbox de l'application)  
Fichiers de sous-titres et cache de transcription | Pour afficher les sous-titres et permettre la recherche de mots | Base de données sur l'appareil  
Cache d'explication et de résumé IA (mots, phrases, résumés de médias) | Pour afficher les résultats précédents sans rappeler l'IA | Base de données sur l'appareil  
Dossiers d'étude de mots / flashcards et plannings de révision | Pour alimenter la révision par répétition espacée | Base de données sur l'appareil  
Notes que vous créez | Pour conserver vos notes d'étude | Sur l'appareil (mémoire / stockage local)  
Paramètres de l'application, y compris le thème, la langue et le style de sous-titres | Pour mémoriser vos préférences | Préférences sur l'appareil  
Adresse et clé du point de terminaison LLM, si vous en configurez un | Pour appeler les fonctions d'IA que vous activez | Sur l'appareil, **chiffré** ; nous ne pouvons pas le lire  
  
Nous ne détenons aucune copie côté serveur des éléments ci-dessus et ne pouvons pas les restaurer pour vous. Veuillez conserver vos propres sauvegardes.

### 3.2 Informations traitées uniquement lorsque vous utilisez une fonction précise

  * **Photothèque (facultatif).** Lorsque vous importez des médias, l'Application lit les vidéos / l'audio que vous sélectionnez dans votre photothèque. Lorsque vous exportez du matériel d'étude, l'Application écrit dans votre photothèque. Nous ne parcourons jamais votre photothèque en arrière-plan. Vous pouvez refuser l'autorisation ; le reste de l'Application continue de fonctionner.
  * **Fichiers / Documents (facultatif).** Lorsque vous importez des médias ou des documents locaux, l'Application lit les fichiers que vous choisissez dans l'application Fichiers / Sur mon iPhone. Rien n'est téléversé vers un serveur que nous exploitons.
  * **Aucun microphone, aucun appareil photo, aucune localisation.** Smart Video ne demande ni n'utilise le microphone, l'appareil photo ou les services de localisation. La reconnaissance vocale s'exécute sur l'audio _déjà présent dans votre fichier multimédia importé_ à l'aide de modèles sur l'appareil — elle n'enregistre jamais depuis le microphone.
  * **Diagnostic optionnel (désactivé par défaut).** L'Application propose un commutateur optionnel « Partager les diagnostics » dans les Réglages. Il reste désactivé jusqu'à ce que vous l'activiez. Lorsqu'il est activé, l'Application peut préparer un court rapport de diagnostic non personnel et vous aider à l'envoyer par e-mail au développeur — voir le point 5 de la section 3.3.



### 3.3 Informations envoyées hors de votre appareil

Uniquement dans les cas suivants :

  1. **Traitement par IA.** Lorsque vous utilisez les fonctions d'IA (traduction de sous-titres, explication de mots et de phrases, résumé et questions-réponses de suivi), le texte que vous sélectionnez est envoyé au **point de terminaison LLM que vous configurez vous-même** dans Réglages → Bibliothèque de modèles → Serveur LLM. Le destinataire est le fournisseur que vous choisissez ; nous ne l'exploitons pas, ne pouvons pas lire l'adresse ou la clé que vous configurez, et ne conservons aucune copie de ce que vous soumettez. Veuillez consulter la politique de confidentialité de ce fournisseur.
  2. **Reconnaissance vocale (sur l'appareil).** La transcription s'exécute localement avec les modèles sherpa que vous téléchargez dans la Bibliothèque de modèles. L'audio et le texte **ne sont pas** envoyés nulle part.
  3. **Vérification d'achat.** Les achats intégrés sont vérifiés par la boutique d'applications sur votre appareil (actuellement l'Apple App Store). Nous recevons uniquement une confirmation d'achat, jamais les coordonnées de votre carte de paiement.
  4. **Configuration à distance et téléchargements de modèles.** L'Application récupère des fichiers de configuration et les modèles ASR (sherpa) sur l'appareil depuis les GitHub Pages / GitHub du développeur. Ces requêtes ne transportent ni vos médias ni votre contenu d'étude.
  5. **Diagnostic optionnel (uniquement si vous l'activez).** Si vous activez « Partager les diagnostics » dans les Réglages, l'Application peut collecter au plus tous les 7 jours un instantané minimal et non personnel — version de l'application, version du système d'exploitation, langue de l'appareil, un identifiant anonyme aléatoire, le type d'événement et un horodatage — et ouvrir un brouillon d'e-mail prérempli dans votre application de messagerie adressé à la boîte du développeur. **Rien n'est transmis automatiquement : l'e-mail n'est envoyé que lorsque vous appuyez explicitement sur envoyer.** Nous ne collectons jamais votre adresse e-mail, adresse IP, localisation GPS, identifiant publicitaire, numéro de série de l'appareil ou informations de compte, et nous n'exploitons aucun serveur recevant ces données.



Nous n'exploitons pas de SDK publicitaires ou d'analyse, donc aucun identifiant n'est partagé avec des réseaux publicitaires.

## 4\. Les fonctions d'IA, en termes simples

Smart Video propose deux types de traitement par IA :

  * **Reconnaissance vocale sur l'appareil (ASR) :** la transcription s'exécute sur votre appareil avec un modèle sherpa que vous téléchargez. **Votre audio et votre texte ne quittent jamais votre appareil — rien n'est transmis.**
  * **Point de terminaison LLM configuré par l'utilisateur (BYOK) :** la traduction, l'explication et le résumé sont produits en envoyant le texte sélectionné à l'**adresse et à la clé LLM que vous saisissez vous-même** dans Réglages → Bibliothèque de modèles → Serveur LLM. Le fournisseur est choisi par vous — nous ne l'exploitons pas et ne pouvons pas lire l'adresse ou la clé que vous configurez. Veuillez consulter la politique de confidentialité et de conservation de ce fournisseur, et ne soumettez pas par ce canal des informations que vous considérez comme confidentielles.



Vous pouvez désactiver les fonctions d'IA à tout moment dans les Réglages ; le lecteur, les sous-titres et les outils d'étude locaux continuent de fonctionner sans IA.

## 5\. Pourquoi nous traitons vos informations

Nous traitons les informations uniquement pour : importer et lire vos médias ; afficher les sous-titres et permettre la recherche de mots ; exécuter la transcription sur l'appareil que vous demandez ; appeler le point de terminaison IA que vous configurez ; vérifier les achats ; et maintenir l'Application en fonctionnement et sécurisée.

Nous n'utilisons pas votre contenu d'étude pour entraîner des modèles, pour établir votre profil ou pour cibler de la publicité.

## 6\. Tiers susceptibles de recevoir des informations

Destinataire | Ce qu'il reçoit | Finalité  
---|---|---  
Le fournisseur LLM que vous configurez vous-même | Le texte que vous soumettez pour traduction / explication / résumé | Traitement IA demandé  
Apple App Store | Jeton d'achat | Vérification d'achat  
GitHub Pages / GitHub (développeur) | Requêtes de téléchargement de configuration et de modèles (aucun contenu multimédia) | Configuration à distance et livraison du modèle ASR sur l'appareil  
  
Chaque destinataire est régi par sa propre politique de confidentialité. Nous ne vendons ni ne louons d'informations personnelles à quiconque.

## 7\. Combien de temps nous conservons les informations

Votre bibliothèque, vos sous-titres, vos notes et vos dossiers d'étude restent sur votre appareil jusqu'à ce que vous les supprimiez, effaciez les données ou désinstalliez l'Application. La suppression ou la désinstallation les retire de façon permanente ; nous ne conservons aucune copie et ne pouvons pas les récupérer.

Le contenu que vous soumettez à votre fournisseur LLM configuré est conservé conformément à la politique de conservation de ce fournisseur.

## 8\. Sécurité

Vos données sont stockées dans une base de données locale protégée par la sécurité propre de votre appareil (code d'accès de l'appareil, chiffrement du disque). L'adresse et la clé du point de terminaison LLM sont stockées de façon chiffrée sur l'appareil et ne nous sont jamais transmises. Aucune méthode de stockage n'est parfaitement sûre, aussi veuillez protéger votre appareil et conserver des sauvegardes.

## 9\. Enfants

L'Application n'est pas destinée aux enfants. Nous ne recueillons pas sciemment d'informations personnelles auprès d'enfants n'ayant pas atteint l'âge du consentement numérique dans leur juridiction (13 ans aux États-Unis, 16 ans dans une grande partie de l'EEE, et tel que défini localement ailleurs). Si vous pensez qu'un enfant nous a fourni des informations, contactez-nous et nous vous aiderons à les supprimer.

## 10\. Vos droits

Vos droits dépendent de votre lieu de résidence ; la section spécifique à la région figurant à la suite du présent document les explique en détail. Où que vous soyez, vous pouvez à tout moment : refuser ou révoquer les autorisations facultatives ; exporter ou supprimer vos données depuis l'Application ; cesser d'utiliser les fonctions d'IA ; ou nous contacter avec une demande.

Comme vos données sont locales, le moyen le plus rapide d'exercer l'accès, la rectification, la portabilité ou la suppression est directement dans l'Application.

## 11\. Modifications de cette politique

Nous pouvons mettre à jour cette politique. Lorsque nous le faisons, nous modifions la date ci-dessus et, pour les changements importants, vous en informons dans l'Application. Continuer à utiliser l'Application après une mise à jour signifie que vous acceptez la politique révisée.

## 12\. Contact

Questions et demandes relatives à la confidentialité : **13808875@qq.com**  
Adresse postale : **中国河南省郑州市高新区科学大道银屏路正弘高新数码港熙园**
