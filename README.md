# Awesome-Contextual-AI-Sensory-Analytics

# Top Contextual AI & Sensory Analytics Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Emotion Recognition, Multimodal Sentiment Analysis & Affective Computing*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Contextual AI & Sensory Analytics**. These tools analyze human signals—facial expressions, voice, physiological data, and text—to infer emotional states, sentiment, engagement, and cognitive context. They are used in market research, UX testing, automotive safety, healthcare, and customer experience analytics.

**Examples** include Affectiva, Realeyes, MorphCast, Hume AI, Element Human, Entropik Tech, Sightcorp, Sensum, Empath, and Zoho Sense (the category leaders).

**Open-source emphasis**: This section highlights every major active project for self-hosted emotion recognition, open-source multimodal analysis, and community-driven affective computing—ideal for researchers, developers, and organizations seeking transparent, vendor-neutral sensory analytics without per-minute API pricing.

Contributions welcome! Open an PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

| Product | Description | Pricing (Starting) | Free Tier / Trial Limits |
|---------|-------------|-------------------|--------------------------|
| **[Hume AI](https://www.hume.ai/)** | AI toolkit for voice and emotion. Expression Measurement API analyzes facial expressions, vocal prosody, and text sentiment. Free tier includes limited TTS, EVI (Empathic Voice Interface), and 1 concurrent connection [citation:12]. | Free tier: $0/month; paid tiers (Starter, Creator, Pro, Scale, Business, Enterprise) available | **Free**: 10,000 TTS characters/month, 5 EVI minutes/month, 1 concurrent connection, unlimited voice cloning, 3 team seats, Discord support [citation:12] |
| **[Entropik Tech](https://www.entropik.io/)** | Emotion AI platform with hardware-free eye tracking and facial coding. Claims 95%+ accuracy. Used for consumer research, ad testing, and UX insights. Pricing is not public; demo required [citation:13]. | Quote-only (corporate pricing via demo) | **No free trial** per third-party listings [citation:7][citation:13] |
| **[Affectiva (Smart Eye)](https://www.affectiva.com/)** | Pioneer in emotion AI and facial expression recognition. Widely used in automotive (driver monitoring), media analytics, and market research. | Quote-only (enterprise contract) | No public free tier; demo via sales |
| **[Realeyes](https://www.realeyes.com/)** | Emotion AI for advertising and media measurement. Uses facial coding to predict attention and emotional response to video content. | Quote-only (enterprise contract) | No public free tier; demo via sales |
| **[MorphCast](https://www.morphcast.com/)** | Browser-based emotion recognition SDK. Analyzes facial expressions via webcam in real time without server-side processing. | Quote-only (SDK licensing) | Free trial available for SDK evaluation |
| **[Element Human](https://www.elementhuman.com/)** | Emotion and behavior analytics platform. Combines facial coding, voice analysis, and survey data for audience insights. | Quote-only (enterprise contract) | No public free tier; demo via sales |
| **[Sightcorp](https://sightcorp.com/)** | Computer vision and emotion recognition for audience measurement. Provides real-time audience analytics for digital signage and retail. | Quote-only (enterprise contract) | No public free tier; demo via sales |
| **[Sensum](https://www.sensum.co/)** | Implicit emotion measurement using wearable sensors (EDA, heart rate) combined with facial coding. Used in product testing and media research. | Quote-only (project-based pricing) | No public free tier; demo via sales |
| **[Empath](https://empath.ai/)** | AI-powered emotion analytics for customer experience. Analyzes voice and text interactions to detect frustration and satisfaction. | Quote-only (enterprise contract) | No public free tier; demo via sales |
| **[Zoho Sense](https://www.zoho.com/)** | Contextual AI within the Zoho ecosystem (limited public information available; part of Zoho's broader AI offerings). | Contact Zoho for pricing | Contact vendor |

## Open-Source GitHub Projects

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[ERML (Emotion Recognition ML)](https://github.com/sid-lakhani/erml)** | [![Stars](https://img.shields.io/github/stars/sid-lakhani/erml?style=social&color=white)](https://github.com/sid-lakhani/erml/stargazers) | Pip-installable Python SDK for facial emotion recognition. Analyzes images for 7 emotions (angry, disgust, fear, happy, sad, surprise, neutral). Trained on FER-2013. Lightweight—no camera or display logic included; drop into any project and pass a frame [citation:2]. |
| **[Emolysis](https://github.com/ControlNet/emolysis)** | [![Stars](https://img.shields.io/github/stars/ControlNet/emolysis?style=social&color=white)](https://github.com/ControlNet/emolysis/stargazers) | Python-based open-source group emotion analysis and visualization toolkit. Processes synchronized multimodal input (video) and maps to group-level emotion, valence, and arousal. Cross-platform (Android, iOS, Windows) with GUI for modality selection and target person filtering [citation:5]. |
| **[online-emotion-detection](https://pypi.org/project/online-emotion-detection/)** | [![Stars](https://img.shields.io/github/stars/sid-lakhani/online-emotion-detection?style=social&color=white)](https://github.com/sid-lakhani/online-emotion-detection/stargazers) | Production-grade Python package for real-time emotion detection. Ships a FastAPI service with unary (`/predict`) and streaming (`/stream`) endpoints, client proxies (unary and async), and runtime selection (PyTorch, TorchScript, ONNX, TensorRT). Supports AffectNet 7- or 8-class models with valence/arousal outputs [citation:9]. |
| **[BehaviorKit](https://github.com/IUB-RHouse/BehaviorKit)** | [![Stars](https://img.shields.io/github/stars/IUB-RHouse/BehaviorKit?style=social&color=white)](https://github.com/IUB-RHouse/BehaviorKit/stargazers) | Open-source plug-and-play module for real-time behavior analysis on robots. Bundles gaze tracking, transcription, textual sentiment, facial emotion (valence/arousal), and face/pose landmarks. Connects via WebSocket to ROS or custom clients [citation:14]. |

### Additional Strong Open-Source Options

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[LibEER](https://github.com/chaoyue123/LibEER)** | [![Stars](https://img.shields.io/github/stars/chaoyue123/LibEER?style=social&color=white)](https://github.com/chaoyue123/LibEER/stargazers) | Comprehensive benchmark and algorithm library for EEG-based emotion recognition. PyTorch implementations of 17 deep learning models across 6 datasets with standardized protocols for fair comparison [citation:8]. |
| **[LibEMER](https://github.com/chaoyue123/LibEMER)** | [![Stars](https://img.shields.io/github/stars/chaoyue123/LibEMER?style=social&color=white)](https://github.com/chaoyue123/LibEMER/stargazers) | Unified evaluation framework for EEG-based multimodal emotion recognition. Fully reproducible PyTorch implementations with standardized preprocessing and experimental setups [citation:1]. |
| **[CLARA](https://github.com/phuonglamgithub/CLARA)** | [![Stars](https://img.shields.io/github/stars/phuonglamgithub/CLARA?style=social&color=white)](https://github.com/phuonglamgithub/CLARA/stargazers) | Multimodal sentiment analysis framework using frozen CLIP and DeBERTa encoders with LoRA. Bidirectional co-attention for vision-language fusion. Achieves 83.16% on MVSA-Single with only 7.45% trainable parameters [citation:3]. |
| **[GExSent](https://github.com/Subhanshusethi/GExSENT-MOE)** | [![Stars](https://img.shields.io/github/stars/Subhanshusethi/GExSENT-MOE?style=social&color=white)](https://github.com/Subhanshusethi/GExSENT-MOE/stargazers) | Gated experts architecture for robust multimodal sentiment analysis. Combines CLIP and Modern BERT with Hierarchical Gated Mixture of Experts and Gated Attention Mechanism. Evaluated on MOSI, MOSEI, and Memotion [citation:15]. |

**Frameworks for building custom systems**: Combine **ERML** or **online-emotion-detection** for production facial emotion inference, **Emolysis** for group-level analysis, **LibEER** or **LibEMER** for EEG-based affective computing research, and **CLARA** or **GExSent** for multimodal sentiment fusion—all deployable via Python and Docker without per-minute API costs.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Sensory analytics platforms process biometric and facial data, which is subject to strict privacy regulations (GDPR, BIPA, CCPA). Ensure informed consent, data minimization, and local legal review before deployment.
- Commercial platforms (Affectiva, Realeyes, Entropik, etc.) are almost universally quote-only with no public pricing or free trials [citation:7][citation:13]. Open-source alternatives require ML expertise and infrastructure but offer full transparency and data control.

---

**Made for researchers, UX teams, market analysts, and developers building affective computing infrastructure.**  
Let's make contextual AI and sensory analytics more open, ethical, and accessible.
