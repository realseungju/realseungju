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

Reads a chessboard image into FEN for engine analysis: board detection, corner
correction, per-square CNN classification, and board reconstruction. The
project began as single-image PGN recovery, but I redefined the target after
establishing that one frame contains no move history. Real-photo generalization
is still under validation.

### [shared-brain-lite](https://github.com/realseungju/shared-brain-lite)

`Python` `Git` `CI`

A Git-native memory and work contract for AI coding agents. It combines tiered
reading rules, task and session generators, and a lint gate that catches record
and privacy-boundary violations. The public edition passes 21 automated checks.

## Research

### SketchSense — emotion information in children's drawing descriptions

`VLM` `Qwen2-VL` `InternVL3` `Llama` `OpenCV`

Built 10,860 natural-language descriptions of children's drawings and tested
whether those descriptions preserve information useful for emotion analysis.

- A description-based reader reached **Macro-F1 0.720 ± 0.012**, compared with
  **0.636 ± 0.010** for an eight-feature color baseline
  *(n=2,172; dev/eval 1,086 each; 20 repeated splits)*.
- Fine-grained caption errors were barely detected by CLIP and Prometheus
  *(relative sensitivity 0.00–0.09)*. A VQA-based probe recovered sensitivity
  to **0.16–0.51**.
- The classifier is a representation check. It does not establish clinical
  validity or directly evaluate emotion in generated drawings.

### [Virtual dental image generation](https://github.com/realseungju/Generating-a-Teeth-Image-with-Pix2pix)

`Pix2Pix` `GAN` `U-Net` `PatchGAN` `PSNR` `SSIM` `FID`

Prepared a 2D training set from 200 paired upper/lower intraoral scans, trained
the virtual-image generation component, and evaluated generated output against
the source images. My contribution covered data preparation, generation, and
verification; CR-Fill inpainting was a downstream stage outside my part.

## Publications and presentations

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
