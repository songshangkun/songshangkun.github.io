---
title: Privacy Policy
---

# Privacy Policy

**Last updated:** 2026-11-13 · **Effective:** 2026-11-12

## 1. Who we are

RomeoAI (the "App") is a local-first reading and study app. The data controller responsible for your personal information is **songshangkun** ("we", "us", "our"), reachable at **中国河南省郑州市高新区科学大道银屏路正弘高新数码港熙园**.

For any privacy question, request or complaint, contact us at **13808875@qq.com**.

## 2. The short version

- Your reading library, imported documents, annotations, summaries and settings live **on your device**. We run no account system and no backend that stores your reading data.
- We **do not sell** your personal information and **do not** use it for behavioural advertising.
- This version of the App **contains no advertising SDK and no analytics SDK**. **Pro** is a one-time unlock purchased through the **App Store**; **Apple** processes the payment and we never see your payment details.
- **Web search** is optional and off by default. When you switch it on, only the question you typed — never your documents — is sent to a public search engine, and the results are always labelled **external source (unverified)**.
- The App requests the **microphone permission**, used solely for optional voice input and note recordings that are transcribed **on your device** by the streaming speech-recognition model, and the **camera permission**, used only when you choose "Scan & Send" to read the QR code shown by another RomeoAI device. Audio and camera frames are never uploaded. Photo-library and location permissions are not requested. Documents and images are imported through the system file picker, and OCR runs **entirely on your device**.
- AI features run either on an **LLM endpoint you configure yourself** or with an **on-device model you download to your device** — see section 4.

## 3. Information we handle

Because the App is local-first, almost all information never leaves your device.

### 3.1 Information stored on your device

| What | Why | Where it stays |
|---|---|---|
| Imported documents (PDF, EPUB, Office, text, images) and their extracted text | To open, reflow and read them again | App sandbox (application support directory) |
| Reading library records: titles, formats, import time, reading position | To show your library and resume where you stopped | On-device database |
| On-device full-text / retrieval index and AI result cache (explanations, summaries, Q&A) | To search your documents and avoid repeated AI calls | On-device database and index directory |
| Reading and appearance settings (theme, language, font, page-turn mode, quick actions) | To remember your preferences | On-device preferences |
| Downloaded speech (TTS) models | To read documents aloud offline | App sandbox (model directory) |
| LLM endpoint address, model name and API key, if you configure one | To call the AI features you enable | On-device, stored obfuscated; we cannot read it |
| Downloaded speech-recognition (ASR), on-device LLM and embedding models | Voice input, offline Q&A and semantic search | App sandbox (model directory) |
| Note recordings, chat history, summaries and shared notes | Replay recordings and continue studying | On-device database and app sandbox |

We hold no server-side copy of the above and cannot restore it for you. Please keep your own backups.

### 3.2 Information handled only when you use a specific feature

- **Files / Documents (optional).** When you import a document or an image, the App reads only the files you pick in the system file picker. Nothing is uploaded to a server we operate.
- **On-device text recognition (OCR).** Images and scanned PDF pages are recognised locally by the on-device ML Kit text-recognition component. Images never leave your device.
- **On-device speech synthesis (TTS).** Documents are read aloud by speech models you download and run locally. Text is not sent anywhere.
- **Voice input and note recordings (optional).** When you dictate text or attach a recording to a note, the App uses the microphone and a streaming speech-recognition model that runs **entirely on your device**. Audio is converted to text locally and is not uploaded. You may decline the microphone permission; reading, AI and other features keep working.
- **On-device models (optional).** You may download speech-recognition, speech-synthesis, embedding and small language models (GGUF). These files are stored in the App sandbox and run locally; your text and audio are not sent to us or to a model provider.

### 3.3 Information sent outside your device

Only in these cases:

1. **AI processing (optional).** When you use AI explanations, summaries, follow-up questions or quick actions, the text you selected or the relevant excerpt is sent to the **LLM endpoint you configured yourself** in Settings → AI Service. The recipient is the provider you choose; we do not operate it, cannot read the address or key you configure, and keep no copy of what you submit. Please review that provider's privacy policy.
2. **Remote configuration and document delivery.** The App fetches configuration files, legal documents and the optional app-recommendation list from the developer's GitHub Pages, and downloads speech, speech-recognition, embedding and on-device language models from the model repository (Hugging Face / hf-mirror). These requests carry no document content, reading history, audio or personal identifiers.
3. **Network requests you trigger.** Opening an image or link inside a document does not upload anything by itself; the App does not include browsing, tracking or advertising components.
4. **Web search (optional).** When you switch on web search in a Q&A screen, the question you typed (truncated to 200 characters) is sent to a public search engine — Bing for mainland China, DuckDuckGo or Bing elsewhere — to fetch results. Only result titles and short snippets are parsed; result pages themselves are not downloaded or stored. Your documents, excerpts, reading history and annotations are never included in that request. Queries are not written to any database we control; repeating the same question within 15 minutes may reuse a local in-memory cache. Web results are marked **external source (unverified)** — always check the original page.

## 4. AI features, in plain words

- **User-configured LLM endpoint (BYOK):** explanations, summaries, translations and Q&A are produced by sending the selected text to the **LLM address and key you enter yourself**. The provider is chosen by you — we neither operate it nor can we read the address or key you configure. Please review that provider's privacy and retention policy, and do not submit information you consider confidential through this channel.
- **On-device LLM model (optional):** explanations, summaries and Q&A can also be produced by a small GGUF model that you download and run locally. In that mode the text stays on your device and is not sent anywhere.
- **On-device processing:** text extraction, OCR, full-text and semantic indexing, speech synthesis, speech recognition and on-device model inference all run locally on your device. **Your documents, images and audio are not uploaded by these features.**
- **Web search is a separate switch.** It is off by default, works independently of AI features, and can be turned off at any time. With it off, questions and documents never leave your device for search purposes.

You can turn AI features off at any time; reading, search and offline speech keep working without them.

## 5. Why we process your information

We process information only to: import and display your documents; extract and reflow text; let you search, annotate and organise your library; run on-device OCR and speech synthesis you request; call the AI endpoint you configure; and keep the App working and secure.

We do not use your documents or reading history to train models, to profile you, or to target advertising.

## 6. Third parties that may receive information

| Recipient | What it receives | Purpose |
|---|---|---|
| The LLM provider you configure yourself | The text you submit for explanation, summary or Q&A | AI processing you requested |
| GitHub Pages / GitHub (developer) | Configuration, legal-document and app-recommendation requests (no document content) | Remote configuration, document delivery and app promotion |
| Hugging Face / hf-mirror | Speech, speech-recognition, embedding and on-device LLM model downloads (no document content) | On-device model delivery |
| The search engine you reach through web search (Bing / DuckDuckGo) | The question you submitted, only while web search is switched on | Retrieving external results you asked for |
| Apple (App Store) | Purchase and receipt data for the one-time Pro unlock | Processing your payment |

Each recipient is governed by its own privacy policy. We do not sell or rent personal information to anyone.

## 7. How long we keep information

Your documents, index, annotations, AI cache and settings remain on your device until you delete them, delete the document from your library, or uninstall the App. Deleting a document from the library removes its record, its original file and its index entries. Uninstalling removes everything permanently; we keep no copy and cannot recover it.

Content you submit to your configured LLM provider is retained according to that provider's retention policy. Search queries sent through web search are not stored by us; only a short-lived in-memory cache on your device is used.

## 8. Security

Your data is stored in the App's sandbox, protected by your device's own security (device passcode, disk encryption). The LLM endpoint address and key are stored obfuscated on the device and are never transmitted to us. No method of storage is perfectly secure, so please protect your device and keep backups.

## 9. Children

The App is not directed to children. We do not knowingly collect personal information from children under the age of digital consent in their jurisdiction (13 in the United States, 16 in much of the EEA, and as defined locally elsewhere). If you believe a child has provided us information, contact us and we will help remove it.

## 10. Your rights

Your rights depend on where you live. Wherever you are, you may at any time: decline or revoke optional permissions; delete documents and their data from within the App; stop using AI features; or contact us with a request.

Because your data is local, the fastest way to exercise access, correction, portability or deletion is directly in the App.

## 11. Changes to this policy

We may update this policy. When we do, we change the date above and, for material changes, notify you in the App. Continuing to use the App after an update means you accept the revised policy.

## 12. Contact

Privacy questions and requests: **13808875@qq.com**
Postal address: **中国河南省郑州市高新区科学大道银屏路正弘高新数码港熙园**
