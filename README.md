# 🎨 Picasso LoRA Trainer – Fine-Tuning with AI  

This project fine-tunes Stable Diffusion XL using **LoRA** on a small dataset of **Picasso's paintings**. The goal is to teach the model to generate images **in Picasso’s style** with limited training data.

## 📌 About this project  
- **Base model used:** `Stable Diffusion XL (SDXL)`  
- **Dataset:** A selection of Picasso’s paintings  
- **Goal:** Train LoRA to generate images inspired by Picasso’s artistic style 
- **Comparison:** Two sets of 10 generated images with **two different prompts**  

---
## 📸 Generated Images

### 🎨 **Prompt 1: Bold Abstract Colors**
> _"A surrealist painting in the style of Picasso, abstract and colorful"_

<div style="display: flex; flex-wrap: wrap; gap: 10px;">
  <img src="generative_picasso/generated_picaso_1_20250221_133929.png" width="200">
  <img src="generative_picasso/generated_picaso_2_20250221_133940.png" width="200">
  <img src="generative_picasso/generated_picaso_3_20250221_133952.png" width="200">
  <img src="generative_picasso/generated_picaso_4_20250221_134003.png" width="200">
  <img src="generative_picasso/generated_picaso_5_20250221_134015.png" width="200">
  <img src="generative_picasso/generated_picaso_6_20250221_134026.png" width="200">
  <img src="generative_picasso/generated_picaso_7_20250221_134038.png" width="200">
  <img src="generative_picasso/generated_picaso_8_20250221_134049.png" width="200">
  <img src="generative_picasso/generated_picaso_9_20250221_134101.png" width="200">
  <img src="generative_picasso/generated_picaso_10_20250221_134113.png" width="200">
</div>

---

### 🎭 **Prompt 2: Pale Pastel Surrealist Portrait**
> _"A surrealist portrait of a woman in the style of Picasso, with pale pastel colors, abstract shapes, and delicate brush strokes, inspired by Picasso’s Blue Period."_


<div style="display: flex; flex-wrap: wrap; gap: 10px;">
  <img src="generative_picasso/generated_pale_picasso_1_20250221_134659.png" width="200">
  <img src="generative_picasso/generated_pale_picasso_2_20250221_134710.png" width="200">
  <img src="generative_picasso/generated_pale_picasso_3_20250221_134722.png" width="200">
  <img src="generative_picasso/generated_pale_picasso_4_20250221_134733.png" width="200">
  <img src="generative_picasso/generated_pale_picasso_5_20250221_134745.png" width="200">
  <img src="generative_picasso/generated_pale_picasso_6_20250221_134756.png" width="200">
  <img src="generative_picasso/generated_pale_picasso_7_20250221_134807.png" width="200">
  <img src="generative_picasso/generated_pale_picasso_8_20250221_134819.png" width="200">
  <img src="generative_picasso/generated_pale_picasso_9_20250221_134831.png" width="200">
  <img src="generative_picasso/generated_pale_picasso_10_20250221_134842.png" width="200">
</div>

---

## 📂 Project Files
- 📜 **Google Colab Notebook:** [`picasso_lora_trainer_xl.ipynb`](https://github.com/RominaSR/picasso-ai-lora-trainer/blob/main/picasso_lora_trainer_xl.ipynb)  
- 🖼️ **Generated Imagesfolder:** [`generative_picasso`](https://github.com/RominaSR/picasso-ai-lora-trainer/tree/main/generative_picasso)  
- 🧠 **Trained LoRA models:** [`Loras`](https://github.com/RominaSR/picasso-ai-lora-trainer/tree/main/Loras)  

---

## 🔗 References & Credits  
This project was built using:
- [Stable Diffusion XL (SDXL)](https://huggingface.co/stabilityai/stable-diffusion-xl-base-1.0)
- [kohya-ss LoRA Trainer](https://github.com/kohya-ss/sd-scripts)
- [LoRA Easy Training Scripts](https://github.com/derrian-distro/LoRA_Easy_Training_scripts_Backend/)
