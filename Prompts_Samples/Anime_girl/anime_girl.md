# 🎨 Anime Character Test

**Prompt:**  
> anime girl, solo, upper body, soft lighting, detailed hair, expressive eyes, beautiful face, natural pose, studio background, ultra detailed, masterpiece, best quality, sharp focus, cinematic lighting, vibrant colors

**Negative Prompt:**  
> lowres, blurry, bad anatomy, extra limbs, text, watermark, worst quality, bad hands, distorted face

---

### ⚙️ Settings
- **Model:** RealisticVisionV60B1_v51HyperVAE.safetensors  
- **Sampling method:** Euler a  
- **Sampling steps:** 15  
- **CFG Scale:** 6.5  
- **Resolution:** 448×448  
- **Hires.fix:** OFF  
- **Batch count:** 1  
- **Batch size:** 1  

---

### 🖼️ Generated Image
![Anime girl](anime.png)

---

### 🧠 Notes
This test demonstrates how a realism-trained model like **RealisticVision** interprets stylized prompts.  
Despite being optimized for realism, it successfully generates anime-inspired results with sharp detail, natural lighting, and expressive facial rendering — all on a **CPU-only setup (Ryzen 5 8600G)**.

Render time remained fast and stable under the same optimized configuration as the photorealistic portrait test.
