---
title: Politique de confidentialité
---

# Politique de confidentialité

**Dernière mise à jour :** 2026-09-09 · **Entrée en vigueur :** 2026-09-09

## 1. Qui nous sommes

NotePay est une application de suivi des dépenses de type « local-first » (« l'Application »). Le responsable de traitement des données à caractère personnel vous concernant est **songshangkun** (« nous »), joignable à l'adresse **中国河南省郑州市高新区科学大道银屏路正弘高新数码港熙园**.

Pour toute question, demande ou réclamation relative à la confidentialité, contactez-nous à l'adresse **13808875@qq.com**.

## 2. En bref

- Votre registre réside **sur votre appareil**. Nous n'exploitons aucun système de compte et aucun serveur dorsal enregistrant vos données comptables.
- Nous ne **vendons** pas vos données à caractère personnel et ne les utilisons **pas** à des fins de publicité comportementale.
- Cette version de l'Application **ne contient ni SDK publicitaire ni SDK d'analyse**.
- La localisation, l'appareil photo, la photothèque et le microphone sont **facultatifs** et utilisés uniquement lorsque vous invoquez la fonction correspondante. Nous ne suivons jamais votre position en arrière-plan.
- Les fonctions d'IA facultatives peuvent envoyer ce que vous écrivez, dites ou photographiez à une plateforme LLM agrégée tierce préconfigurée par le développeur pour votre région — voir section 4. Vous ne configurez pas vous-même cette adresse ni cette clé et vous ne le pouvez pas. Vous pouvez les désactiver.

## 3. Données que nous traitons

Puisque l'Application est de type « local-first », la plupart des informations ne quittent jamais votre appareil.

### 3.1 Données stockées sur votre appareil

| Quoi | Pourquoi | Où elles demeurent |
|---|---|---|
| Écritures : montant, catégorie, note, date, nom du lieu | Pour afficher votre registre, vos statistiques et vos budgets | Base de données locale |
| Registres et catégories que vous créez | Pour organiser vos données | Base de données locale |
| Paramètres de l'Application, y compris la langue et la région | Pour mémoriser vos préférences | Préférences locales |
| Planning des rappels | Pour vous notifier à l'heure que vous avez définie | Base de données locale et notifications locales |
| Clé du fournisseur d'IA (préconfigurée par le développeur selon la région) | Pour appeler les fonctions d'IA que vous activez | Sur l'appareil, **chiffrée** ; nous ne pouvons pas la lire |

Nous ne conservons aucune copie côté serveur des éléments ci-dessus et ne pouvons pas les restaurer pour vous. Veuillez conserver vos propres sauvegardes.

### 3.2 Données traitées uniquement lorsque vous utilisez une fonction précise

- **Localisation (facultative).** Lorsque vous associez un lieu à une écriture, l'Application lit vos coordonnées afin de résoudre un nom de lieu. Cette résolution est effectuée par AMap (Gaode) en Chine continentale et par Google Maps dans les autres régions, selon la région que vous avez configurée. Nous demandons la localisation **uniquement lorsque vous utilisez l'Application** — **jamais en arrière-plan**. Vous pouvez refuser l'autorisation ou désactiver entièrement la fonction cartographique ; le reste de l'Application continue de fonctionner.
- **Appareil photo et photothèque (facultatifs).** Lorsque vous photographiez ou choisissez un reçu, l'image est lue à des fins de reconnaissance. Les originaux ne sont pas téléversés vers l'un de nos serveurs.
- **Microphone (facultatif).** Lorsque vous utilisez la saisie vocale, l'audio est capturé et transcrit. La transcription est effectuée **sur votre appareil** à l'aide de modèles vocaux hors ligne que vous téléchargez ; l'audio n'est pas diffusé vers nos serveurs.

### 3.3 Données envoyées hors de votre appareil

Uniquement dans les cas suivants :

1. **Géocodage inverse** — la coordonnée que vous sélectionnez est envoyée à AMap ou à Google Maps afin d'obtenir un nom de lieu.
2. **Traitement par l'IA** — si vous activez l'IA distante, le texte, la transcription vocale ou l'image de reçu que vous soumettez est envoyé à une **plateforme LLM agrégée tierce** préconfigurée par le développeur pour votre région. Cette plateforme choisit le modèle utilisé pour chaque requête (le modèle n'est pas fixé par NotePay et peut varier). Ce fournisseur traite le contenu conformément à sa propre politique de confidentialité. Vous ne configurez pas vous-même cette adresse ni cette clé et vous ne le pouvez pas.
3. **Vérification d'achat** — les achats intégrés sont vérifiés par Apple ou Google. Nous ne recevons qu'une confirmation d'achat, jamais les coordonnées de votre carte de paiement.
4. **Configuration à distance et téléchargements de modèles** — l'Application récupère des fichiers de configuration, des modèles vocaux et, le cas échéant, des documents juridiques mis à jour. Ces requêtes ne contiennent pas le contenu de votre registre.

Nous n'exploitons ni SDK publicitaire ni SDK d'analyse ; aucun identifiant n'est donc partagé avec des réseaux publicitaires.

## 4. Les fonctions d'IA, en termes simples

L'Application peut exécuter l'IA soit **sur votre appareil**, soit via un **point de terminaison distant**.

- **Mode sur appareil :** votre contenu reste sur votre appareil. Rien n'est transmis.
- **Mode distant :** votre contenu est transmis à une **plateforme LLM agrégée tierce** sélectionnée pour votre région. Cette plateforme peut être située hors de votre pays et, pour chaque requête, achemine votre contenu vers le modèle qu'elle sélectionne — le modèle précis n'est pas choisi par NotePay et peut varier d'une requête à l'autre. La plateforme traite votre contenu conformément à sa propre politique de confidentialité et peut le conserver selon ses propres règles de conservation, auxquelles vous devez vous référer. **NotePay n'exploite aucun serveur, ne conserve aucune copie de votre contenu et n'enregistre rien de ce que vous soumettez.** Ne soumettez pas en mode distant des informations que vous considérez comme confidentielles.

Vous pouvez passer en mode sur appareil ou cesser d'utiliser les fonctions d'IA à tout moment dans les Paramètres.

## 5. Pourquoi nous traitons vos informations

Nous ne traitons vos informations que pour : enregistrer et afficher vos dépenses ; produire des statistiques, des budgets et des rappels ; résoudre des noms de lieux ; reconnaître les reçus et la voix lorsque vous le demandez ; vérifier les achats ; et maintenir l'Application en fonctionnement et en sécurité.

Nous n'utilisons pas le contenu de votre registre pour entraîner des modèles, pour établir votre profil ou pour cibler de la publicité.

## 6. Tiers susceptibles de recevoir des informations

| Destinataire | Ce qu'il reçoit | Finalité |
|---|---|---|
| AMap (Gaode) — région Chine continentale | Coordonnée que vous sélectionnez | Géocodage inverse |
| Google Maps — autres régions | Coordonnée que vous sélectionnez | Géocodage inverse |
| La plateforme LLM agrégée tierce préconfigurée par le développeur pour votre région | Texte, transcription ou image que vous soumettez | Traitement par l'IA que vous avez demandé |
| Apple App Store / Google Play | Jeton d'achat | Vérification d'achat |

Chaque destinataire est régi par sa propre politique de confidentialité. Nous ne vendons ni ne louons de données à caractère personnel à quiconque.

## 7. Durée de conservation de vos informations

Votre registre et vos paramètres demeurent sur votre appareil jusqu'à ce que vous supprimiez l'écriture, effaciez les données ou désinstalliez l'Application. La suppression ou la désinstallation les retire de façon permanente ; nous n'en conservons aucune copie et ne pouvons pas les récupérer.

Le contenu soumis à un plateforme LLM agrégée tierce distant est conservé selon la politique de conservation de ce fournisseur.

## 8. Sécurité

Vos données sont stockées dans une base de données locale protégée par la sécurité propre de votre appareil (code de l'appareil, chiffrement du disque). Votre clé de fournisseur d'IA, le cas échéant, est stockée de façon chiffrée sur l'appareil et n'est jamais transmise vers nous. Aucune méthode de stockage n'est parfaitement sûre ; veuillez donc protéger votre appareil et conserver des sauvegardes.

## 9. Mineurs

L'Application n'est pas destinée aux enfants. Nous ne collectons pas sciemment de données à caractère personnel auprès d'enfants n'ayant pas l'âge du consentement numérique dans leur juridiction (13 ans aux États-Unis, 16 ans dans une grande partie de l'EEE, et tel que défini localement ailleurs). Si vous pensez qu'un enfant nous a fourni des informations, contactez-nous et nous vous aiderons à les supprimer.

## 10. Vos droits

Vos droits dépendent de votre lieu de résidence ; la section propre à chaque région figurant à la suite du présent document les explique en détail. Où que vous soyez, vous pouvez à tout moment : refuser ou révoquer les autorisations facultatives ; exporter ou supprimer vos données depuis l'Application ; cesser d'utiliser les fonctions d'IA ; ou nous contacter avec une demande.

Puisque vos données sont locales, le moyen le plus rapide d'exercer l'accès, la rectification, la portabilité ou la suppression est directement dans l'Application.

## 11. Modifications de la présente politique

Nous pouvons mettre à jour la présente politique. Lorsque nous le faisons, nous modifions la date ci-dessus et, pour les modifications importantes, vous en informons dans l'Application. Continuer à utiliser l'Application après une mise à jour signifie que vous acceptez la politique révisée.

## 12. Contact

Questions et demandes relatives à la confidentialité : **13808875@qq.com**
Adresse postale : **中国河南省郑州市高新区科学大道银屏路正弘高新数码港熙园**

