# SEUNG-JU NA

**Data / ML Engineering · Vision-Language Systems · Evaluation Pipelines**

I build data and evaluation pipelines for vision and language systems. I am
especially interested in turning messy source data into reproducible evidence:
defining what a model can claim, testing where it fails, and keeping those
boundaries visible in the result.

## Selected projects

### [Reading Assistant](https://github.com/realseungju/reading-assistant)

`Python` `Flask` `Raspberry Pi 5` `Google Vision OCR` `Gemini`

A reading companion that photographs a page of a physical book and turns it
into a summary, translation, quiz, and spoken audio. I led the five-person
industry-linked capstone team and owned system integration and the OCR path.

### [ChessLens](https://github.com/realseungju/Image2PGN)

`PyTorch` `OpenCV` `FEN` `Stockfish`

A local web app for turning a chess screenshot into a reviewed position and
exploring it with Stockfish. The pipeline covers board detection, perspective
correction, per-square CNN classification, and FEN reconstruction. Users can
correct the board, replay engine variations, and compare recorded historical
moves with engine recommendations.

A single image cannot recover a game's move history. Real-photo generalization
remains under validation. [Visual walkthrough](https://whichai.fyi/chesslens#image-flow)

### [shared-brain-lite](https://github.com/realseungju/shared-brain-lite)

`Python` `Git` `CI`

A Git-native memory and work contract for AI coding agents. It combines tiered
reading rules, task and session generators, and a lint gate that catches record
and privacy-boundary violations. Public synthetic examples demonstrate how
records are written and reused. [Interactive guide](https://whichai.fyi/shared-brain)

### [whichai.fyi](https://whichai.fyi/)

`HTML` `CSS` `JavaScript` `Cloudflare Pages`

A personal AI engineering site with project notes and visual walkthroughs.
ChessLens demonstrates image recognition and recorded-move replay; Shared Brain
shows how work survives a new session and lets visitors inspect example files.

## Research

### SketchSense — emotion information in children's drawing descriptions

`VLM` `Qwen2-VL` `InternVL3` `Llama` `OpenCV`

Built data and evaluation pipelines for VLM-generated descriptions of
children's drawings. The work uses controlled caption edits, similarity and
VQA-based scoring, visual judges, and human annotations to examine which
details are preserved and where automated evaluation misses errors.

Current work focuses on description fidelity and object grounding. These are
research evaluations, not clinical validation or a diagnostic system.

### [Virtual dental image generation](https://github.com/realseungju/Generating-a-Teeth-Image-with-Pix2pix)

`Pix2Pix` `GAN` `U-Net` `PatchGAN` `PSNR` `SSIM` `FID`

Prepared a 2D training set from 200 paired upper/lower intraoral scans, trained
the virtual-image generation component, and evaluated generated output against
the source images. My contribution covered data preparation, generation, and
verification; CR-Fill inpainting was a downstream stage outside my part.

## Publications and presentations

### Upcoming presentations — 2026

- **Poster presentation planned** — [ACK 2026 (Annual Conference of KIPS)](https://ack.kips.or.kr/),
  Sejong University, November 5, 2026.
- **Presentation planned** — [2026 IEEE International Conference on Big Data](https://bigdataieee.org/BigData2026/),
  Phoenix, Arizona, USA. Conference dates: December 14–17, 2026.

*Status as of October 28, 2026. Paper titles and author details are not listed yet.*

### Previous publications and presentations

- **First author, poster** — *A Study on Image Matching of Original and
  Generated Images*, ICAEIC-2023, Jeju, July 2023.
  [Conference gallery](https://ictaes.org/gallery/?vid=65)
- **First author, oral presentation** — *Comparative Analysis of Underwater
  Image Generation Using Pix2Pix*, KDBC 2023, Busan, November 2023.
  [Conference program](https://www.dbsociety.kr/kdbc/kdbc2023/)
- **Contributing author (4th of 5)** — *A Study on Deep Learning Model for
  Virtual Tooth Image Generation*, Database Research 38(3), 73–82, 2022.
  I contributed the image-generation component and its verification.
  [KCI record](https://www.kci.go.kr/kciportal/ci/sereArticleSearch/ciSereArtiView.kci?sereArticleSearchBean.artiId=ART002916725)

## Awards and certifications

- **Encouragement Award**, Intelligent Innovation Idea Competition, 2026 —
  *어르신의 말 한마디*
- **Excellence Award**, Mentor–Mentee Program, 2021
- **Encouragement Award**, AI Software Competition, 2021
- **SQLD (SQL Developer)**
- ITQ Excel, Internet, Hangeul, and PowerPoint · GTQ Graphic Technology Level 2
