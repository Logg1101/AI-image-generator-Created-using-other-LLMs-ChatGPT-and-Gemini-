# AI Image Generator 🎨

**Owner:** Ankit — *LoGG*  
**Status:** Portfolio project / demo

---

## What this is

A local WebUI-based image generation project using Stable Diffusion (Automatic1111-style WebUI) to produce images from text prompts.  
This repo demonstrates practical knowledge of prompt engineering, model configuration, and the generation pipeline — useful for recruiters who want to see you can run, evaluate, and iterate on AI systems.

---

## Important transparency note (read this)

I want to be fully transparent: I **did not train or implement the core diffusion models from scratch**.  
- I used existing Stable Diffusion checkpoints and WebUI projects as the base.  
- I created prompt flows, tuned settings, integrated upscalers, tested outputs, and organized the project for reproducibility and demo.  
- I used **ChatGPT** and **Gemini** *as assistants* for prompt engineering, debugging suggestions, and small code snippets/config hints.  
If you're looking for someone who can assemble, configure, evaluate, and present ML projects—this is exactly that.

---

## Features / Capabilities

- `txt2img` — generate images from text prompts.  
- `img2img` — refine or upscale existing images (with denoising control).  
- Hires-fix + upscaler (RealESRGAN recommended) for sharper outputs.  
- Support for multiple samplers and step/CFG tuning for quality tradeoffs.  
- Checkpoint / LoRA loading and lightweight merging workflows.  
- Negative prompt support to reduce common artifacts.

---

