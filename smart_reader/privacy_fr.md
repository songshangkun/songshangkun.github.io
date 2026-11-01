---
title: Politique de confidentialité
---

# Politique de confidentialité

**Dernière mise à jour :** 2026-10-31 · **Entrée en vigueur :** 2026-10-31

## 1. Qui nous sommes

Smart Reader (l'« Application ») est une application de lecture et d'étude qui fonctionne en local. Le responsable du traitement de vos données personnelles est **songshangkun** (« nous »), joignable à l'adresse : **中国河南省郑州市高新区科学大道银屏路正弘高新数码港熙园**.

Pour toute question, demande ou réclamation relative à la confidentialité, contactez-nous à **13808875@qq.com**.

## 2. L'essentiel

- Votre bibliothèque de lecture, les documents importés, les notes, les résumés et les réglages restent **sur votre appareil**. Nous n'exploitons aucun système de compte ni aucun serveur qui stockerait vos données de lecture.
- Nous **ne vendons pas** vos données personnelles et **ne** les utilisons **pas** pour de la publicité comportementale.
- Cette version de l'Application **ne contient ni SDK publicitaire ni SDK d'analyse** et **ne propose aucun achat intégré**.
- L'Application **ne demande aucune autorisation pour l'appareil photo, le microphone, la photothèque ou la localisation**. Les documents et images sont importés uniquement via le sélecteur de fichiers du système, et la reconnaissance de texte (OCR) s'exécute **entièrement sur votre appareil**.
- Les fonctions d'IA n'envoient que le texte que vous sélectionnez à un **point de terminaison LLM que vous configurez vous-même** — voir la section 4.

## 3. Informations que nous traitons

L'Application fonctionnant en local, la quasi-totalité des informations ne quitte pas votre appareil.

### 3.1 Informations stockées sur votre appareil

| Contenu | Finalité | Emplacement |
|---|---|---|
| Documents importés (PDF, EPUB, Office, texte, images) et leur texte extrait | Les ouvrir, les remettre en page et les relire | Bac à sable de l'Application (répertoire de support) |
| Fiches de bibliothèque : titres, formats, date d'importation, position de lecture | Afficher votre bibliothèque et reprendre où vous vous êtes arrêté | Base de données de l'appareil |
| Index local plein texte / de recherche et cache des résultats d'IA (explications, résumés, questions-réponses) | Rechercher dans vos documents et éviter des appels d'IA répétés | Base de données et répertoire d'index de l'appareil |
| Réglages de lecture et d'apparence (thème, langue, police, mode de tourne-page, actions rapides) | Mémoriser vos préférences | Préférences de l'appareil |
| Modèles vocaux (TTS) téléchargés | Lire les documents à voix haute hors connexion | Bac à sable de l'Application (répertoire des modèles) |
| Adresse du point de terminaison LLM, nom du modèle et clé API, si vous en configurez un | Appeler les fonctions d'IA que vous activez | Sur l'appareil, stockés sous forme obscurcie ; nous ne pouvons pas les lire |

Nous ne conservons aucune copie de ce qui précède sur un serveur et ne pouvons pas le restaurer pour vous. Pensez à faire vos propres sauvegardes.

### 3.2 Informations traitées uniquement lors de l'utilisation d'une fonction

- **Fichiers / Documents (facultatif).** Lors de l'importation d'un document ou d'une image, l'Application ne lit que les fichiers que vous choisissez dans le sélecteur du système. Rien n'est téléversé vers un serveur que nous exploitons.
- **Reconnaissance de texte sur l'appareil (OCR).** Les images et les pages PDF numérisées sont reconnues localement par le composant de reconnaissance de texte ML Kit de l'appareil. Les images ne quittent jamais votre appareil.
- **Synthèse vocale sur l'appareil (TTS).** Les documents sont lus par des modèles vocaux que vous téléchargez et exécutez localement. Le texte n'est envoyé nulle part.
- **Pas de microphone, pas d'appareil photo, pas de localisation.** L'Application n'enregistre pas d'audio, ne prend pas de photos et ne demande pas votre localisation.

### 3.3 Informations qui quittent votre appareil

Uniquement dans les cas suivants :

1. **Traitement par IA (facultatif).** Lorsque vous utilisez les explications, résumés, questions complémentaires ou actions rapides par IA, le texte sélectionné ou l'extrait pertinent est envoyé au **point de terminaison LLM que vous avez configuré** dans Réglages → Service d'IA. Le destinataire est le fournisseur que vous choisissez ; nous ne l'exploitons pas, nous ne pouvons pas lire l'adresse ni la clé que vous configurez et nous ne conservons aucune copie de ce que vous soumettez. Veuillez consulter la politique de confidentialité de ce fournisseur.
2. **Configuration à distance et fourniture de documents.** L'Application récupère des fichiers de configuration et des textes juridiques depuis les GitHub Pages du développeur, et des modèles vocaux depuis le dépôt de modèles (Hugging Face / hf-mirror). Ces requêtes ne contiennent ni le contenu de vos documents, ni votre historique de lecture, ni d'identifiant personnel.
3. **Accès réseau que vous déclenchez.** L'ouverture d'une image ou d'un lien dans un document ne téléverse rien en soi ; l'Application n'intègre aucun composant de navigation, de suivi ou de publicité.

## 4. Les fonctions d'IA, en clair

- **Point de terminaison LLM configuré par l'utilisateur (BYOK) :** les explications, résumés, traductions et questions-réponses sont produits en envoyant le texte sélectionné à l'**adresse et à la clé LLM que vous saisissez vous-même**. Le fournisseur est choisi par vous — nous ne l'exploitons pas et nous ne pouvons pas lire l'adresse ni la clé que vous configurez. Veuillez consulter la politique de confidentialité et de conservation de ce fournisseur, et ne transmettez pas par ce canal des informations que vous considérez comme confidentielles.
- **Traitement sur l'appareil :** l'extraction de texte, l'OCR, l'indexation plein texte et la synthèse vocale s'exécutent localement sur votre appareil. **Ces fonctions ne téléversent ni vos documents ni vos images.**

Vous pouvez désactiver les fonctions d'IA à tout moment ; la lecture, la recherche et la lecture à voix haute hors connexion continuent de fonctionner.

## 5. Pourquoi nous traitons vos informations

Nous traitons les informations uniquement pour : importer et afficher vos documents ; extraire et remettre en page le texte ; vous permettre de rechercher, annoter et organiser votre bibliothèque ; exécuter l'OCR et la synthèse vocale que vous demandez sur l'appareil ; appeler le point de terminaison d'IA que vous configurez ; et maintenir l'Application opérationnelle et sûre.

Nous n'utilisons ni vos documents ni votre historique de lecture pour entraîner des modèles, établir des profils ou cibler de la publicité.

## 6. Tiers susceptibles de recevoir des informations

| Destinataire | Reçoit | Finalité |
|---|---|---|
| Le fournisseur LLM que vous configurez | Le texte que vous soumettez pour une explication, un résumé ou des questions-réponses | Le traitement par IA que vous demandez |
| GitHub Pages / GitHub (développeur) | Requêtes de configuration et de textes juridiques (sans contenu de document) | Configuration à distance et fourniture de documents |
| Hugging Face / hf-mirror | Requêtes de téléchargement de modèles vocaux (sans contenu de document) | Fourniture des modèles TTS pour l'appareil |

Chaque destinataire est soumis à sa propre politique de confidentialité. Nous ne vendons ni ne louons de données personnelles à quiconque.

## 7. Durée de conservation

Vos documents, index, notes, caches d'IA et réglages restent sur votre appareil jusqu'à ce que vous les supprimiez, que vous retiriez le document de la bibliothèque ou que vous désinstalliez l'Application. Supprimer un document de la bibliothèque efface sa fiche, son fichier original et ses entrées d'index. La désinstallation efface tout définitivement ; nous ne conservons aucune copie et ne pouvons rien restaurer.

Le contenu que vous soumettez à votre fournisseur LLM est conservé selon la politique de conservation de ce fournisseur.

## 8. Sécurité

Vos données sont stockées dans le bac à sable de l'Application, protégées par la sécurité de votre appareil (code d'accès, chiffrement du disque). L'adresse et la clé du LLM sont stockées sous forme obscurcie sur l'appareil et ne nous sont jamais transmises. Aucune méthode de stockage n'est parfaitement sûre ; protégez votre appareil et faites des sauvegardes.

## 9. Enfants

L'Application ne s'adresse pas aux enfants. Nous ne collectons pas sciemment de données personnelles concernant des enfants en dessous de l'âge du consentement numérique dans leur juridiction (13 ans aux États-Unis, 16 ans dans une grande partie de l'EEE, et selon la réglementation locale ailleurs). Si vous pensez qu'un enfant nous a fourni des informations, contactez-nous et nous vous aiderons à les supprimer.

## 10. Vos droits

Vos droits dépendent de votre lieu de résidence. Où que vous soyez, vous pouvez à tout moment : refuser ou retirer les autorisations facultatives ; supprimer des documents et leurs données depuis l'Application ; cesser d'utiliser les fonctions d'IA ; ou nous adresser une demande.

Vos données étant locales, le moyen le plus rapide d'exercer l'accès, la rectification, la portabilité ou l'effacement est directement dans l'Application.

## 11. Modifications de cette politique

Nous pouvons mettre à jour cette politique. Le cas échéant, nous modifions la date ci-dessus et, en cas de changement substantiel, vous en informons dans l'Application. Continuer à utiliser l'Application après une mise à jour signifie que vous acceptez la politique révisée.

## 12. Contact

Questions et demandes relatives à la confidentialité : **13808875@qq.com**
Adresse postale : **中国河南省郑州市高新区科学大道银屏路正弘高新数码港熙园**
