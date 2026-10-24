---
title: "Optimising speech recognition using LLMs: an application in the surgical domain"
authors:
  - "Nevin M. Matasyoh"
  - "admin"
  - "Franziska Mathis-Ullrich"
date: '2024-09-01'
publishDate: '2024-09-01'
publication_types: ["article-journal"]
publication: "*Current Directions in Biomedical Engineering*, 10"
abstract: "Abstract Automatic speech recognition (ASR), powered by deep learning techniques, is crucial for enhancing humancomputer interaction. However, its full potential remains unrealized in diverse real-world environments, with challenges such as dialects, accents, and domain-specific jargon, particularly in fields like surgery, persisting. Here, we investigate the potential of large language models (LLMs) as error correction modules for ASR.We leverage Whisper-medium or ASRLibriSpeech for speech recognition, and GPT-3.5 or GPT-4 for error correction.We employ various prompting methods, from zero-shot to few-shot with leading questions and sample medical terms to correct wrong transcriptions. Results, measured by word error rate (WER), reveal Whisper’s superior transcription accuracy over ASR-LibriSpeech, with a WER of 11.93% compared to 32.09%. GPT-3.5, with the few-shot with medical terms prompting method, further enhances performance, achieving a 64.29% and 37.83% WER-reduction for Whisper and ASR-LibriSpeech, respectively. Additionally, Whisper exhibits faster execution speed. Substituting GPT-3.5 with GPT- 4 further enhances transcription accuracy. Despite some few challenges, our approach demonstrates the potential of leveraging domain-specific knowledge through LLM prompting for accurate transcription, particularly in sophisticated domains like surgery."
featured: false
hugoblox:
  ids:
    doi: "10.1515/cdbme-2024-0112"
links:
  - type: pdf
    url: "https://www.degruyterbrill.com/document/doi/10.1515/cdbme-2024-0112/pdf"
---
