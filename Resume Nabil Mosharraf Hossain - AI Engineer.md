# Nabil Mosharraf Hossain

**Kuala Lumpur, Malaysia** · +601161981135 · [nabil6391@gmail.com](mailto:nabil6391@gmail.com)
[nabilmh.com](https://nabilmh.com) · [LinkedIn](https://www.linkedin.com/in/nabil6391/) · [GitHub](https://github.com/nabil6391) (500+ stars) · [Medium](https://nabil6391.medium.com/) (100k reads) · [Substack](https://nabilmh.substack.com/)

---

## Summary

My research sits at the intersection of Islamic technology, applied AI, and natural language processing, with a focus on building tools that serve Muslim communities at scale. As co-founder and CEO of Greentech Apps Foundation (GTAF), a UK-registered charity with 13M+ users globally, I lead applied research in Quranic & Islamic NLP, AI infrastructure for Islamic apps, and FaithTech user behaviour analytics.

A thread that runs through all my work is a deep interest in **optimisation** — finding the bottleneck and eliminating it. This shows up everywhere: reducing a Quran word-by-word view from seconds to milliseconds, shrinking an Android app from 21MB to 4MB, cutting a photo picker from 4 seconds to 150ms, improving a job platform's home screen load by 25%, or applying the Needleman-Wunsch algorithm to align audio with text at word-level precision.

MSc Computer Science (Applied Computing), University Malaya.

---

## Research Areas

**Quranic & Islamic NLP**
- Wav2Vec2-based Quranic ASR pipeline for real-time recitation tracking (WER: 0.08)
- Automated Seerah-Hadith mapping using LLMs and vector search (published Dec 2024)
- Hadith search engine evaluation using IR metrics (nDCG, MAP)
- Culturally-aligned automated response generation for Islamic app reviews (ABSA + Hybrid RAG)

**AI Infrastructure for Islamic Apps**
- Co-authored "Inside GTAF's AI Stack" (2025): LLM-powered customer support automation, Quranic audio segmentation, knowledge graph generation linking Quran, Hadith, and Seerah
- Improved auto-reply performance 4x using SetFit over full LLMs
- OPUS to CAF audio converter in Golang/Swift for Apple ecosystem bandwidth optimisation

**User Behaviour & FaithTech Analytics**
- Led data analysis behind "Quran Planner Habits" (2025): insights from 50,000+ real reading plans on completion rates, engagement patterns, and optimal reading targets

---

## Publications

- **ADAB: A Culturally-Aligned Automated Response Generation Framework for Islamic App Reviews by Integrating ABSA and Hybrid RAG** — ResearchGate, 2024
  [doi.org/researchgate/398941570](https://www.researchgate.net/publication/398941570_ADAB_A_Culturally-Aligned_Automated_Response_Generation_Framework_for_Islamic_App_Reviews_by_Integrating_ABSA_and_Hybrid_RAG)

- **A Novel LLM-Based Approach for Automated Seerah-Hadith Mapping: Connecting Islamic Historical Narratives Through Vector Search and Semantic Analysis** — ResearchGate, Dec 2024
  [researchgate.net/publication/388780641](https://www.researchgate.net/publication/388780641_A_Novel_LLM-Based_Approach_for_Automated_Seerah-Hadith_Mapping_Connecting_Islamic_Historical_Narratives_Through_Vector_Search_and_Semantic_Analysis)

- **Speech Recognition Using an End-to-End Transformer Model for Quran Recitation** — ResearchGate
  [doi.org/10.13140/RG.2.2.26323.28965](https://doi.org/10.13140/RG.2.2.26323.28965)

- **Optimizing my Opus to CAF Converter in Go: A 40% Performance Boost** — Substack
  [nabilmh.substack.com](https://nabilmh.substack.com/p/optimizing-my-opus-to-caf-converter)

- **Creating Audiobooks by Aligning Audio with Text** — Medium
  [medium.com](https://nabil6391.medium.com/creating-audiobooks-by-aligning-audio-with-text-7027ec39a10)

- **Text Similarity Algorithms for Matching Islamic Hadith Documents** — Medium
  [medium.com](https://nabil6391.medium.com/text-similarity-algorithms-for-matching-islamic-hadith-documents-for-hadith-interlinking-1c8034452727)

- **Comparison of String Encryption Performance using Symmetric Methods in Android** — Medium
  [medium.com](https://nabil6391.medium.com/comparison-of-string-encryption-performance-using-asymmetric-methods-in-android-936f84763570)

---

## Experience

### Jobstreet by SEEK — Senior Software Engineer & AI Specialist
*July 2023 – Present | Malaysia (Australia HQ)*

- Won **AI Trailblazer Award** for developing AI Interview Prep tool at internal hackathon
- Improved Main Screen Loading performance by **25%** through optimised data processing
- Scaled app to 2M MAU; team of 30 across Australia, Hong Kong, Philippines, and Malaysia
- Stack: Kotlin, Jetpack Compose, GraphQL, Node.js, TypeScript; test coverage >70%

### Photobook Worldwide Sdn Bhd — Lead Android Developer
*Nov 2019 – July 2023 | Malaysia*

- Optimised photo picker load from **4 seconds to 150ms** using Kotlin coroutines, IO threading, better file descriptor reuse, and lazy batch loading (150 images at a time)
- Led agile team of 5 Android developers; developed new editor foundation enabling 6 additional photo editor types
- Implemented CI/CD with Jenkins automating 90+ daily UI tests, reducing regression bugs by **75%**
- Spearheaded Jetpack Compose adoption, cutting development time from 3 to 1.5 months

### Greentech Apps Foundation — Co-Founder & CTO, later R&D Lead
*Jan 2015 – Oct 2019 (Full-time CTO); Nov 2022 – June 2024 (Part-time R&D Lead) | UK (Remote)*

- Scaled platform to **50M+ downloads and 2M+ Monthly Active Users**
- Built and led cross-functional engineering teams of 15 developers; interviewed 50+ candidates
- Spearheaded R&D in speech recognition, NLP, and Arabic text processing:
  - Fine-tuned Meta's wav2vec2.0 for Quran tajweed mispronunciation detection (WER: 0.08)
  - Built word-level audio timestamp pipeline using Needleman-Wunsch force alignment
  - Built OPUS to CAF converter in Golang/Swift for Apple ecosystem bandwidth savings
  - Implemented open-source LLMs for customer support; 4x improvement with SetFit
  - Custom Word-by-Word Quran view with full-text search (SQLite FTS) and gapless audio playback
- Implemented C++ NDK solution for Arabic text rendering on older Android devices
- Established seasonal code freezes during Ramadan with strategic roadmap planning

### MyCash Online (SG) Pte Ltd — Senior Android Developer
*Jan 2018 – Aug 2018 | Malaysia*

- Reduced app size from **21MB to 4MB** using ProGuard and optimisation techniques
- Integrated MOL (Malaysia) and Poli (Australia) payment gateways
- MVVM architecture with DataBinding; focus on security and privacy

---

## Open Source

- **GraphView** — Flutter graph visualisation library (Tree, Directed, Layered layouts)
  470+ stars · 11.9k+ pub downloads · [GitHub](https://github.com/nabil6391/graphview) · [pub.dev](https://pub.dev/packages/graphview)

- **FlutterDownloadManager** — Cross-platform download manager with resumable, parallel & batch support
  69+ stars · 4.63k+ pub downloads · [GitHub](https://github.com/nabil6391/flutter_download_manager) · [pub.dev](https://pub.dev/packages/flutter_download_manager)

- **LottieSwipeRefreshLayout** — Custom SwipeRefreshLayout with Lottie animation support
  [GitHub](https://github.com/nabil6391/LottieSwipeRefreshLayout)

---

## Education

**University Malaya** — MSc Computer Science (Applied Computing), 2019–2022

**American International University-Bangladesh** — BSc Electrical & Electronics Engineering, 2011–2014
CGPA 3.94/4.0 · Magna Cum Laude

---

## Skills

| Area | Technologies |
|---|---|
| AI/ML | Speech Recognition (wav2vec2), NLP, Hugging Face Transformers, Fine-tuning, SetFit, LLM Integration, Force Alignment |
| Languages | Python, Java (10+ yrs), Kotlin (8+ yrs), Dart (7+ yrs), JavaScript, Golang |
| Mobile | Android (10+ yrs), Flutter (7+ yrs), Jetpack Compose, C++ NDK |
| Backend | Node.js, TypeScript, GraphQL, Elasticsearch |
| Research | IR metrics (nDCG, MAP), RAG, Vector Search, ABSA |

**Languages:** English (IELTS 7.5) · Bengali
