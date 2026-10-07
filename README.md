# Awesome-Neural-Machine-Translation

# Top Neural Machine Translation (NMT) Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Machine Translation APIs, Localization Platforms & Self-Hosted NMT Engines*  
**Last updated: October 2026**

This repository tracks notable **commercial NMT and localization platforms** and **open-source projects** that translate text between languages — from simple API calls to full localization management systems with translation memory and machine translation integration.

**Examples** include Amazon Translate, DeepL Pro API, Google Cloud Translation API, Microsoft Azure AI Translator, Systran Enterprise, ModernMT, Unbabel, Smartling, Phrase, and Transifex (the category leaders).

**Open-source emphasis**: Neural machine translation is a strong open-source domain. **LibreTranslate** leads as the self-hosted translation API with 30+ languages and no proprietary dependencies . **OpenNMT** provides the reference NMT framework with 7k+ stars . **TranslateGemma** from Google delivers 55-language support under Apache 2.0 . **Tencent Hunyuan MT 1.5** achieves commercial-API-level quality with on-device deployment . **Weblate** and **Tolgee** power localization management . This section is heavily expanded.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[DeepL Pro API](https://www.deepl.com/)**  
  **The quality leader for European languages** — best-in-class fluency and nuance . **Best for high-quality translation of European language pairs**.

- **[Google Cloud Translation API](https://cloud.google.com/translate)**  
  **Google's NMT API** — 130+ languages with AutoML for custom models . **Best for broad language coverage**.

- **[Amazon Translate](https://aws.amazon.com/translate/)**  
  **AWS's neural machine translation** — 75+ languages with custom terminology and active custom translation . **Best for AWS-native translation**.

- **[Microsoft Azure AI Translator](https://azure.microsoft.com/en-us/products/ai-services/ai-translator)**  
  **Microsoft's translation service** — 100+ languages with custom translator and document translation . **Best for Microsoft ecosystem**.

- **[Systran Enterprise](https://www.systransoft.com/)**  
  **Enterprise translation platform** — on-premises and cloud with domain-specific models . **Best for regulated industries**.

- **[ModernMT](https://www.modernmt.com/)**  
  **Adaptive neural machine translation** — learns from translation memory in real time . **Best for localization workflows**.

- **[Unbabel](https://unbabel.com/)**  
  **AI-powered translation with human review** — combines MT with human editors for quality . **Best for customer support localization**.

- **[Smartling](https://www.smartling.com/)**  
  **Translation management platform** — global delivery with website and app localization . **Best for enterprise localization**.

- **[Phrase](https://phrase.com/)**  
  **Localization platform** — TMS with MT integration and developer-friendly APIs . **Best for software localization**.

- **[Transifex](https://www.transifex.com/)**  
  **Localization platform for agile teams** — continuous localization with GitHub integration . **Best for open-source and agile projects**.

## Open-Source GitHub Projects

### Machine Translation APIs

- **[LibreTranslate](https://github.com/LibreTranslate/LibreTranslate)**  
  **Free and open-source machine translation API**, AGPL-3.0 licensed with **16,000+ GitHub stars**  . **Entirely self-hosted, offline capable** — does not rely on proprietary providers like Google or Azure  . **Powered by Argos Translate** — supports **30+ languages** with automatic language detection and file translation (PDF, DOCX, PPTX)  . **REST API with JSON responses** — simple integration into any application  . **Docker deployment with one command**  . **The de facto open-source Google Translate alternative** . **Best for self-hosted translation with privacy**.

- **[Argos Translate](https://github.com/argosopentech/argos-translate)**  
  **The engine powering LibreTranslate**, MIT licensed . **Offline neural machine translation library in Python** . **OpenNMT-based models** . **Best for local translation in Python applications**.

### Neural Machine Translation Frameworks

- **[OpenNMT](https://github.com/OpenNMT/OpenNMT-py)**  
  **The reference open-source NMT framework**, MIT licensed with **7,000+ GitHub stars**  . **PyTorch and TensorFlow implementations** — OpenNMT-py and OpenNMT-tf  . **Full-featured NMT toolkit** — training, inference, and model deployment . **The most widely used NMT research framework** . **Best for training custom NMT models**.

- **[TranslateGemma](https://huggingface.co/google/translategemma)**  
  **Google's open-source translation model based on Gemma 3**, Apache 2.0 licensed  . **55 languages supported** including low-resource languages . **Three parameter sizes**: 4B (mobile/edge), 12B (consumer laptop), 27B (cloud)  . **Outperforms Gemma 3 27B baseline with only 12B parameters** — efficiency breakthrough . **Multimodal capability** — text translation improvements transfer to image translation  . **Best for efficient, high-quality translation**.

- **[Tencent Hunyuan MT 1.5](https://huggingface.co/Tencent-Hunyuan/Tencent-HY-MT1.5-1.8B)**  
  **Tencent's open-source translation models**, open-source  . **Two variants**: 1.8B (on-device, 1GB memory after quantization) and 7B (higher accuracy)  . **33 languages plus 5 Chinese dialects** — including Czech, Marathi, Estonian, Icelandic  . **Outperforms most commercial translation APIs** on FLORES-200 and WMT25 benchmarks  . **1.8B model processes 50 tokens in 0.18s** vs. ~0.4s for commercial models  . **Supports terminology libraries, long context, and format preservation**  . **Best for on-device and edge translation**.

- **[OPUS-MT (Helsinki-NLP)](https://huggingface.co/Helsinki-NLP)**  
  **Open-source translation models from University of Helsinki**, Apache-2.0 licensed  . **Hundreds of language pairs** — multilingual and bilingual models . **Marian NMT-based** — efficient C++ implementation . **Widely used in research and production** . **Best for broad language coverage**.

- **[TraductAL](https://github.com/Rogaton/TraductAL)**  
  **Offline neural machine translation system**, MIT licensed  . **65+ languages** via NLLB-200 and Apertus-8B models . **100% offline after setup** — no data leaves your machine . **Neuro-symbolic approach** — neural MT with Prolog-based validation  . **Web interface and CLI** . **Best for privacy-focused multilingual translation**.

### Localization Management Platforms

- **[Weblate](https://github.com/WeblateOrg/weblate)**  
  **Web-based continuous localization system**, GPL-3.0 licensed  . **Used by 2,500+ libre projects and companies** in 165+ countries  . **Tight version control integration** — Git, GitHub, GitLab, Bitbucket  . **Translation memory, machine translation, and review workflows** . **Hosted service available at weblate.org**  . **Best for open-source and enterprise localization**.

- **[Tolgee](https://github.com/tolgee/tolgee-platform)**  
  **Developer and translator friendly localization platform**, Apache-2.0 licensed  . **In-context translation** — edit translations directly in your app with ALT+click  . **Works in production** — translate deployed apps without redeployment  . **Machine translation integration** — DeepL, Google, AWS, Azure  . **AI translator with context awareness** — screenshots, translation memory, and project context  . **MCP server for AI coding assistants**  . **Best for developer-friendly localization**.

- **[Traduora](https://github.com/ever-co/ever-traduora)**  
  **Open translation management platform for teams**, AGPL-3.0 licensed  . **5-minute setup with Docker or Kubernetes**  . **Import/export to JSON, CSV, YAML, XLIFF, Gettext, Android XML**  . **REST API for workflow automation** . **Best for team translation management**.

- **[Accent](https://github.com/mirego/accent)**  
  **Developer-oriented translation tool**, BSD-3-Clause licensed  . **Elixir-based with Docker deployment** . **Best for developer-centric workflows**.

- **[FastAPI Rosetta](https://pypi.org/project/fastapi-rosetta/)**  
  **Translation management for FastAPI applications**, MIT licensed  . **GNU gettext (.po) file editing in browser** . **Machine translation via Google Cloud or OpenAI**  . **No Django dependency** . **Best for FastAPI projects**.

### Additional Strong Open-Source Options

- **Marian NMT** — Efficient C++ NMT implementation powering OPUS-MT .
- **CTranslate2** — Fast inference engine for Transformer models .
- **Argos Translate** — Offline translation engine for LibreTranslate .
- **OpenNMT-tf** — TensorFlow NMT implementation .
- **NLLB-200** — Meta's No Language Left Behind model (200 languages) .
- **Apertus-8B** — Swiss LLM for low-resource languages .
- **translate5** — Open-source translation system  .
- **Loco Translate** — WordPress translation plugin  .

**Frameworks for building custom NMT and localization solutions**: Combine **LibreTranslate** for self-hosted translation API with 30+ languages . Use **OpenNMT** for training custom NMT models . Deploy **Tencent Hunyuan MT 1.5** for on-device translation with commercial-API-level quality . Choose **TranslateGemma** for efficient 55-language support . Integrate **Weblate** or **Tolgee** for localization management . Use **TraductAL** for fully offline privacy-focused translation . Note that true enterprise NMT with human-in-the-loop (Unbabel), domain-adapted models (ModernMT), and full localization platforms (Smartling, Phrase) remains primarily commercial territory; open-source stacks provide strong translation engines, APIs, and management platforms that require integration for complete localization workflows.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Machine translation platforms process text that may contain sensitive information. **Self-hosted solutions keep data on your infrastructure** — LibreTranslate, TraductAL, and local models ensure no data leaves your servers . Cloud APIs send text to provider servers.
- **Translation quality varies significantly** by language pair, domain, and model. **Not for critical use** — professional translation may require human review . Evaluate models on your specific content before production.
- **License considerations**: LibreTranslate uses AGPL-3.0 , OpenNMT uses MIT , TranslateGemma uses Apache 2.0 , Weblate uses GPL-3.0 , and Tolgee uses Apache-2.0 . Verify licensing against your use case before committing.
- **Hardware requirements vary** — Tencent Hunyuan 1.8B runs on-device with 1GB memory after quantization ; TranslateGemma 27B requires H100 GPU/TPU for cloud deployment . Plan infrastructure accordingly.
- The open-source ecosystem provides strong translation engines, APIs, and management platforms, but **human-in-the-loop quality assurance, domain-adapted models, and enterprise localization workflows** remain primarily commercial offerings.

---

**Made for localization engineers, developers, and organizations seeking translation sovereignty.**  
Let's make neural machine translation more open, transparent, and accessible.
