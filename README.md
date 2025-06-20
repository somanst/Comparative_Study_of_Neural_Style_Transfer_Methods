# 🎨 Comparative Study of Neural Style Transfer Methods

**Final Report for AIN434: Fundamentals of Computational Photography**  
Hacettepe University — Spring 2025

Authored by: [Adam Sattout](https://github.com/somanst) & [Ezel Bayraktar](https://github.com/EzeLLM)

---

## 📄 Overview

This repository contains the final project report titled:

> **"A Comparative Study of Neural Style Transfer Methods"**

Neural Style Transfer (NST) is the task of synthesizing images that preserve the structure of a content image while mimicking the visual style of a reference image. In this study, we perform a comparative evaluation of three state-of-the-art style transfer methods:

- **StyleID**
- **StyleShot**
- **StyTr2**

We assess each model's strengths and limitations based on content preservation, style fidelity, and overall aesthetic quality, using both standard metrics and a novel evaluation strategy we introduce: **LLM as a Judge**, powered by GPT-4o Vision.

---

## 🧠 Key Contributions

- ✅ **Thorough Evaluation** of three modern, non-optimization-based NST models.
- 🎯 **Quantitative Benchmarking** using LPIPS, SSIM, and PSNR metrics.
- 💡 **Novel Subjective Evaluation Framework** — “LLM as a Judge”, where a multimodal language model scores stylizations on perceptual quality, akin to human judgment.
- 👩‍⚖️ **User Studies & Human Preferences** combined with LLM output to better understand the trade-offs of each model.
- 📊 **Clear Visual and Tabular Comparisons** illustrating model behavior across diverse content-style pairs.

---

## 📘 Report

The full report is available here:  
📄 [Comparative_Study_of_Neural_Style_Transfer_Methods.pdf](./Comparative_Study_of_Neural_Style_Transfer_Methods.pdf)

---

## 🤖 LLM-as-a-Judge Implementation

Our proposed **LLM-as-a-Judge** evaluation framework uses a multimodal GPT-4o model to rank stylized images based on human-aligned artistic criteria such as:

- Content Preservation  
- Style Faithfulness  
- Aesthetic Appeal  

You can explore the implementation and prompting code here:  
🔗 **GitHub Repository**: [EzeLLM/judge](https://github.com/EzeLLM/judge)

This tool enables scalable and reproducible evaluation of image generation models using large language models as critics, and was central to our study's evaluation pipeline.

---

## 👫 Authors

- [Adam Sattout](https://github.com/somanst) — AI Engineering Student at Hacettepe University  
- [Ezel Bayraktar](https://github.com/EzeLLM) — Computer Engineering Student at Hacettepe University