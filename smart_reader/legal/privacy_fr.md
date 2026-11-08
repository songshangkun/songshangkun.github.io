---
title: Politique de confidentialité
---

# Politique de confidentialité

**Dernière mise à jour :** 2026-11-08 · **Entrée en vigueur :** 2026-11-08

## 1. Qui nous sommes

Smart Reader (l'« Application ») est une application de lecture et d'étude qui fonctionne en local. Le responsable du traitement de vos données personnelles est **songshangkun** (« nous »), joignable à l'adresse : **中国河南省郑州市高新区科学大道银屏路正弘高新数码港熙园**.

Pour toute question, demande ou réclamation relative à la confidentialité, contactez-nous à **13808875@qq.com**.

## 2. L'essentiel

- Votre bibliothèque de lecture, les documents importés, les notes, les résumés et les réglages restent **sur votre appareil**. Nous n'exploitons aucun système de compte ni aucun serveur qui stockerait vos données de lecture.
- Nous **ne vendons pas** vos données personnelles et **ne** les utilisons **pas** pour de la publicité comportementale.
- Cette version de l'Application **ne contient ni SDK publicitaire ni SDK d'analyse** et **ne propose aucun achat intégré**.
- L'Application **ne demande que l'autorisation du microphone**, utilisée uniquement pour la saisie vocale facultative et les enregistrements de notes, transcrits **sur votre appareil** par le modèle de reconnaissance vocale en streaming. L'audio n'est jamais téléversé. Aucune autorisation pour l'appareil photo, la photothèque ou la localisation n'est demandée. Les documents et images sont importés uniquement via le sélecteur de fichiers du système, et l'OCR s'exécute **entièrement sur votre appareil**.
- Les fonctions d'IA s'exécutent sur un **point de terminaison LLM que vous configurez vous-même** ou avec un **modèle local que vous téléchargez sur votre appareil** — voir la section 4.

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
| Modèles de reconnaissance vocale (ASR), LLM local et d'embeddings téléchargés | Saisie vocale, questions-réponses hors ligne et recherche sémantique | Bac à sable de l'Application (répertoire des modèles) |
| Enregistrements de notes, historique de discussion, résumés et notes partagées | Réécouter les enregistrements et poursuivre l'apprentissage | Base de données de l'appareil et bac à sable de l'Application |

Nous ne conservons aucune copie de ce qui précède sur un serveur et ne pouvons pas le restaurer pour vous. Pensez à faire vos propres sauvegardes.

### 3.2 Informations traitées uniquement lors de l'utilisation d'une fonction

- **Fichiers / Documents (facultatif).** Lors de l'importation d'un document ou d'une image, l'Application ne lit que les fichiers que vous choisissez dans le sélecteur du système. Rien n'est téléversé vers un serveur que nous exploitons.
- **Reconnaissance de texte sur l'appareil (OCR).** Les images et les pages PDF numérisées sont reconnues localement par le composant de reconnaissance de texte ML Kit de l'appareil. Les images ne quittent jamais votre appareil.
- **Synthèse vocale sur l'appareil (TTS).** Les documents sont lus par des modèles vocaux que vous téléchargez et exécutez localement. Le texte n'est envoyé nulle part.
- **Saisie vocale et enregistrements de notes (facultatif).** Lorsque vous dictez du texte ou joignez un enregistrement à une note, l'Application utilise le microphone et un modèle de reconnaissance vocale en streaming qui s'exécute **entièrement sur votre appareil**. L'audio est converti en texte localement et n'est pas téléversé. Vous pouvez refuser l'autorisation du microphone ; la lecture, l'IA et les autres fonctions continuent de fonctionner.
- **Modèles sur l'appareil (facultatif).** Vous pouvez télécharger des modèles de reconnaissance vocale, de synthèse vocale, d'embeddings et de petits modèles de langage (GGUF). Ces fichiers sont stockés dans le bac à sable de l'Application et s'exécutent localement ; votre texte et votre audio ne nous sont pas envoyés ni à un fournisseur de modèles.

### 3.3 Informations qui quittent votre appareil

Uniquement dans les cas suivants :

1. **Traitement par IA (facultatif).** Lorsque vous utilisez les explications, résumés, questions complémentaires ou actions rapides par IA, le texte sélectionné ou l'extrait pertinent est envoyé au **point de terminaison LLM que vous avez configuré** dans Réglages → Service d'IA. Le destinataire est le fournisseur que vous choisissez ; nous ne l'exploitons pas, nous ne pouvons pas lire l'adresse ni la clé que vous configurez et nous ne conservons aucune copie de ce que vous soumettez. Veuillez consulter la politique de confidentialité de ce fournisseur.
2. **Configuration à distance et fourniture de documents.** L'Application récupère des fichiers de configuration, des textes juridiques et la liste facultative d'applications recommandées depuis les GitHub Pages du développeur, et télécharge des modèles vocaux, de reconnaissance vocale, d'embeddings et de langage locaux depuis le dépôt de modèles (Hugging Face / hf-mirror). Ces requêtes ne contiennent ni le contenu de vos documents, ni votre historique de lecture, ni d'audio, ni d'identifiant personnel.
3. **Accès réseau que vous déclenchez.** L'ouverture d'une image ou d'un lien dans un document ne téléverse rien en soi ; l'Application n'intègre aucun composant de navigation, de suivi ou de publicité.

## 4. Les fonctions d'IA, en clair

- **Point de terminaison LLM configuré par l'utilisateur (BYOK) :** les explications, résumés, traductions et questions-réponses sont produits en envoyant le texte sélectionné à l'**adresse et à la clé LLM que vous saisissez vous-même**. Le fournisseur est choisi par vous — nous ne l'exploitons pas et nous ne pouvons pas lire l'adresse ni la clé que vous configurez. Veuillez consulter la politique de confidentialité et de conservation de ce fournisseur, et ne transmettez pas par ce canal des informations que vous considérez comme confidentielles.
- **Modèle LLM local (facultatif) :** les explications, résumés et questions-réponses peuvent aussi être produits par un petit modèle GGUF que vous téléchargez et exécutez localement. Dans ce mode, le texte reste sur votre appareil et n'est envoyé nulle part.
- **Traitement sur l'appareil :** l'extraction de texte, l'OCR, l'indexation plein texte et sémantique, la synthèse vocale, la reconnaissance vocale et l'inférence de modèles locaux s'exécutent localement sur votre appareil. **Ces fonctions ne téléversent ni vos documents, ni vos images, ni votre audio.**

Vous pouvez désactiver les fonctions d'IA à tout moment ; la lecture, la recherche et la lecture à voix haute hors connexion continuent de fonctionner.

## 5. Pourquoi nous traitons vos informations

Nous traitons les informations uniquement pour : importer et afficher vos documents ; extraire et remettre en page le texte ; vous permettre de rechercher, annoter et organiser votre bibliothèque ; exécuter l'OCR et la synthèse vocale que vous demandez sur l'appareil ; appeler le point de terminaison d'IA que vous configurez ; et maintenir l'Application opérationnelle et sûre.

Nous n'utilisons ni vos documents ni votre historique de lecture pour entraîner des modèles, établir des profils ou cibler de la publicité.

## 6. Tiers susceptibles de recevoir des informations

| Destinataire | Reçoit | Finalité |
|---|---|---|
| Le fournisseur LLM que vous configurez | Le texte que vous soumettez pour une explication, un résumé ou des questions-réponses | Le traitement par IA que vous demandez |
| GitHub Pages / GitHub (développeur) | Requêtes de configuration, de textes juridiques et d'applications recommandées (sans contenu de document) | Configuration à distance, fourniture de documents et promotion d'applications |
| Hugging Face / hf-mirror | Requêtes de téléchargement de modèles vocaux, de reconnaissance vocale, d'embeddings et de LLM locaux (sans contenu de document) | Fourniture de modèles pour l'appareil |

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
