# Comprehensive AI Image & Video Tools Reference

> A research-compiled reference of 100+ open-source models, libraries, APIs, plugins, mobile apps, and services for AI image and video processing. Compiled February 2026.

---

## Table of Contents

1. [Open Source Image Generation Models](#1-open-source-image-generation-models)
2. [Open Source Video Generation Models](#2-open-source-video-generation-models)
3. [Open Source Image Processing Libraries](#3-open-source-image-processing-libraries)
4. [Open Source AI Enhancement (Upscaling / Restoration)](#4-open-source-ai-enhancement)
5. [Open Source Inpainting & Segmentation](#5-open-source-inpainting--segmentation)
6. [SD / FLUX UIs & Workflow Tools](#6-sd--flux-uis--workflow-tools)
7. [Image & Video APIs & Platforms](#7-image--video-apis--platforms)
8. [Browser Extensions](#8-browser-extensions)
9. [Figma & Design Tool Plugins](#9-figma--design-tool-plugins)
10. [WordPress Plugins for Image AI](#10-wordpress-plugins-for-image-ai)
11. [Photoshop & Lightroom Plugins](#11-photoshop--lightroom-plugins)
12. [Mobile Apps (iOS / Android)](#12-mobile-apps-ios--android)
13. [CLI Tools for Image Processing](#13-cli-tools-for-image-processing)
14. [AI Image & Video Datasets](#14-ai-image--video-datasets)
15. [AI Image Detection & Content Moderation](#15-ai-image-detection--content-moderation)
16. [AI Image Tagging, Classification & Captioning](#16-ai-image-tagging-classification--captioning)
17. [AI OCR (Text Recognition from Images)](#17-ai-ocr)
18. [Image CDN & Optimization Services](#18-image-cdn--optimization-services)

---

## 1. Open Source Image Generation Models

| Name | URL | Language / Platform | License / Free Tier | Description |
|------|-----|---------------------|---------------------|-------------|
| Stable Diffusion 1.5 | https://github.com/runwayml/stable-diffusion | Python | CreativeML Open RAIL-M | The original widely-adopted open text-to-image diffusion model that launched the open-source AI art ecosystem. |
| Stable Diffusion XL (SDXL) | https://github.com/Stability-AI/generative-models | Python | Open weights (RAIL) | Stability AI's higher-resolution 1024px model with improved prompt adherence and a two-stage architecture. |
| Stable Diffusion 3.5 Large | https://huggingface.co/stabilityai/stable-diffusion-3.5-large | Python | Open weights (RAIL) | Stability AI's latest flagship model with a Multimodal Diffusion Transformer (MMDiT) architecture and strong text rendering. |
| FLUX.1 [dev] | https://github.com/black-forest-labs/flux | Python | Open weights (non-commercial) | Black Forest Labs' 12B rectified-flow transformer for state-of-the-art photorealism; weights freely downloadable. |
| FLUX.1 [schnell] | https://huggingface.co/black-forest-labs/FLUX.1-schnell | Python | Apache 2.0 | The distilled, commercially-licensed variant of FLUX.1 that generates images in 1–4 steps. |
| FLUX.2 [dev] | https://bfl.ai/models/flux-dev | Python | Open weights | Black Forest Labs' 32B next-generation model released November 2025 with superior prompt fidelity and typography. |
| DeepFloyd IF | https://github.com/deep-floyd/IF | Python | Open weights (non-commercial) | Cascaded pixel-space diffusion model by StabilityAI's DeepFloyd team with outstanding text-in-image rendering. |
| Kandinsky 5.0 | https://github.com/kandinskylab/kandinsky-5 | Python | Apache 2.0 | Yandex Research's multimodal diffusion family supporting both image and video generation; T2V Lite runs at 2B params. |
| PixArt-Alpha | https://github.com/PixArt-alpha/PixArt-alpha | Python | Apache 2.0 | Efficient 600M DiT-based text-to-image model trained with high-quality data and a three-stage training pipeline. |
| PixArt-Sigma | https://github.com/PixArt-alpha/PixArt-sigma | Python | Apache 2.0 | Enhanced successor to PixArt-Alpha with 4K resolution support and stronger aesthetic quality. |
| Playground v2.5 | https://huggingface.co/playgroundai/playground-v2.5-1024px-aesthetic | Python | Open weights | Playground AI's SDXL-based model fine-tuned for exceptional color, contrast, and human-centric aesthetics. |
| Stable Cascade (Würstchen v3) | https://github.com/Stability-AI/StableCascade | Python | Open weights (non-commercial) | Hierarchical three-stage latent diffusion model with extreme compression enabling fast, memory-efficient generation. |
| Kolors | https://github.com/Kwai-Kolors/Kolors | Python | Apache 2.0 | Kwai's Chinese-English bilingual text-to-image model based on a large language model encoder for rich understanding. |
| HiDream-I1 | https://github.com/HiDream-ai/HiDream-I1 | Python | Open weights | HiDream AI's full open-weight 17B parameter image generation model released in 2025 with strong aesthetic output. |
| SDXL-Lightning | https://huggingface.co/ByteDance/SDXL-Lightning | Python | Apache 2.0 | ByteDance's few-step distilled SDXL model that produces 1024px images in 1–4 steps in under a second. |
| StyleGAN3 | https://github.com/NVlabs/stylegan3 | Python | Nvidia Source Code License | NVIDIA's GAN-based generator for high-fidelity human faces and textures at sub-second speeds. |

---

## 2. Open Source Video Generation Models

| Name | URL | Language / Platform | License / Free Tier | Description |
|------|-----|---------------------|---------------------|-------------|
| Wan 2.1 | https://github.com/Wan-Video/Wan2.1 | Python | Apache 2.0 | Alibaba Tongyi Lab's leading open T2V and I2V model family; the 1.3B variant runs on 8 GB VRAM. |
| HunyuanVideo | https://github.com/Tencent-Hunyuan/HunyuanVideo | Python | Open weights | Tencent's 13B cinematic-quality video model that outperformed Runway Gen-3 in human evaluations at release. |
| HunyuanVideo 1.5 | https://github.com/Tencent-Hunyuan/HunyuanVideo-1.5 | Python | Open weights | Lightweight successor to HunyuanVideo offering high quality at reduced compute requirements. |
| Mochi 1 | https://github.com/genmoai/mochi | Python | Apache 2.0 | Genmo AI's 10B Asymmetric Diffusion Transformer for smooth high-fidelity motion with strong prompt adherence. |
| CogVideoX | https://github.com/zai-org/CogVideo | Python | Apache 2.0 | Zhipu/Tsinghua University's 3D VAE + expert Transformer model supporting 10-second videos at high resolution. |
| AnimateDiff | https://github.com/guoyww/AnimateDiff | Python | Apache 2.0 | Motion module that plugs into any community SD 1.5 checkpoint to animate still images with temporal consistency. |
| LTX-Video | https://github.com/Lightricks/LTX-Video | Python | Apache 2.0 | Lightricks' real-time-capable video model that generates 30fps 1216×704 video faster than realtime on capable GPUs. |
| Open-Sora | https://github.com/hpcaitech/Open-Sora | Python | Apache 2.0 | HPCAI's open reproduction of Sora-style video generation supporting 256px–768px T2V and I2V from a single model. |
| SkyReels V2 | https://github.com/SkyworkAI/SkyReels-V2 | Python | Apache 2.0 | SkyworkAI's infinite-length autoregressive cinematic video model fine-tuned on ~10M high-quality film clips. |
| StepVideo T2V | https://github.com/stepfun-ai/Step-Video-T2V | Python | Open weights | Step-fun's 30B parameter state-of-the-art text-to-video model capable of generating up to 204 frames. |
| FramePack | https://github.com/lllyasviel/FramePack | Python | Apache 2.0 | lllyasviel's image-to-video next-frame prediction model optimized to run on 6 GB VRAM consumer GPUs. |
| VideoCrafter2 | https://github.com/AILab-CVC/VideoCrafter | Python | Apache 2.0 | AILab's high-quality video diffusion model for T2V and I2V tasks with artistic style blending. |
| ModelScope T2V | https://huggingface.co/damo-vilab/text-to-video-ms-1.7b | Python | CC BY-NC 4.0 | Alibaba DAMO Academy's early open text-to-video model; still useful for learning and lightweight prototyping. |
| Stable Video Diffusion (SVD) | https://github.com/Stability-AI/generative-models | Python | Open weights (RAIL) | Stability AI's image-to-video model that adds natural motion to a reference still image. |
| I2VGen-XL | https://github.com/ali-vilab/i2vgen-xl | Python | Apache 2.0 | Alibaba DAMO's high-fidelity image-to-video model with strong semantic understanding of the input frame. |

---

## 3. Open Source Image Processing Libraries

| Name | URL | Language / Platform | License / Free Tier | Description |
|------|-----|---------------------|---------------------|-------------|
| OpenCV | https://github.com/opencv/opencv | C++ / Python / Java | Apache 2.0 | The foundational real-time computer vision library with 2500+ optimized algorithms used across research and production. |
| Pillow | https://github.com/python-pillow/Pillow | Python | HPND (open) | Friendly fork of PIL providing essential image manipulation, format conversion, and filter operations in Python. |
| sharp | https://github.com/lovell/sharp | Node.js | Apache 2.0 | High-performance Node.js image processing powered by libvips; 4–5x faster than ImageMagick for resize operations. |
| libvips | https://github.com/libvips/libvips | C / Python / Ruby | LGPL-2.1 | Demand-driven, horizontally threaded image processing library with ~300 operations and minimal memory footprint. |
| ImageMagick | https://github.com/ImageMagick/ImageMagick | C | Apache 2.0 | Decades-old suite for creating, editing, compositing, and converting images via CLI or programmatic API. |
| scikit-image | https://github.com/scikit-image/scikit-image | Python | BSD-3-Clause | Scientific image processing in Python built on SciPy; comprehensive algorithms for segmentation, morphology, and filters. |
| Wand | https://github.com/emcconville/wand | Python | MIT | Pythonic binding to ImageMagick's MagickWand C API for easy integration into Python workflows. |
| GraphicsMagick | http://www.graphicsmagick.org | C | MIT | Fork of ImageMagick optimized for stability, performance, and API compatibility across large-scale image pipelines. |
| GDAL | https://github.com/OSGeo/gdal | C++ / Python | MIT | Geospatial image translator supporting 200+ raster formats including GeoTIFF, NetCDF, and JPEG2000. |
| Imageio | https://github.com/imageio/imageio | Python | BSD-2-Clause | Lightweight Python library for reading and writing image and video data across many formats including DICOM and FITS. |

---

## 4. Open Source AI Enhancement

| Name | URL | Language / Platform | License / Free Tier | Description |
|------|-----|---------------------|---------------------|-------------|
| Real-ESRGAN | https://github.com/xinntao/Real-ESRGAN | Python | BSD-3-Clause | Practical blind super-resolution model for photos, illustrations, and anime; 4x upscaling with artifact correction. |
| GFPGAN | https://github.com/TencentARC/GFPGAN | Python | Apache 2.0 | Tencent ARC's GAN-based face restoration that recovers realistic details from low-quality or corrupted portraits. |
| CodeFormer | https://github.com/sczhou/CodeFormer | Python | S-Lab License | VQGAN + Transformer face restoration model offering a quality-fidelity tradeoff slider for precise control. |
| SwinIR | https://github.com/JingyunLiang/SwinIR | Python | Apache 2.0 | Swin Transformer-based image restoration model for super-resolution, denoising, and JPEG artifact reduction. |
| HAT (Hybrid Attention Transformer) | https://github.com/XPixelGroup/HAT | Python | MIT | State-of-the-art single-image super-resolution via hybrid attention mechanisms for maximum PSNR/SSIM. |
| BSRGAN | https://github.com/cszn/BSRGAN | Python | Apache 2.0 | Blind super-resolution using a practical degradation model simulating blur, downsampling, and noise. |
| BasicSR | https://github.com/XPixelGroup/BasicSR | Python | Apache 2.0 | Open-source toolbox unifying SR, deblurring, and restoration models including ESRGAN, SwinIR, and EDVR. |
| waifu2x-ncnn-vulkan | https://github.com/nihui/waifu2x-ncnn-vulkan | C++ | MIT | Vulkan-accelerated implementation of waifu2x for anime upscaling and noise reduction on any GPU. |
| Upscayl | https://github.com/upscayl/upscayl | Electron / C++ | AGPL-3.0 | Free cross-platform desktop GUI for Real-ESRGAN-based AI upscaling; runs locally on CPU, GPU, or Apple Silicon. |
| DRCT | https://github.com/ming053l/DRCT | Python | Apache 2.0 | Dense-residual-connected Transformer for single-image SR that addresses information bottleneck in deep networks. |
| Rembg | https://github.com/danielgatis/rembg | Python | MIT | CLI and Python library for background removal using BiRefNet and U2Net neural networks. |
| BiRefNet | https://github.com/ZhengPeng7/BiRefNet | Python | MIT | Bilateral Reference Network for high-accuracy dichotomous image segmentation, powering next-gen background removal. |

---

## 5. Open Source Inpainting & Segmentation

| Name | URL | Language / Platform | License / Free Tier | Description |
|------|-----|---------------------|---------------------|-------------|
| Segment Anything Model (SAM) | https://github.com/facebookresearch/segment-anything | Python | Apache 2.0 | Meta's foundation segmentation model that segments any object from a point, box, or text prompt zero-shot. |
| SAM 2 | https://github.com/facebookresearch/sam2 | Python | Apache 2.0 | Meta's upgraded segmentation model extending SAM to real-time video segmentation and tracking. |
| IOPaint (LamaCleaner) | https://github.com/Sanster/IOPaint | Python | Apache 2.0 | Self-hostable inpainting tool supporting LaMa, MAT, and SD Inpainting with SAM and GFPGAN plugins. |
| LaMa | https://github.com/advimman/lama | Python | Apache 2.0 | Resolution-robust large-mask inpainting via Fast Fourier Convolutions for structure-aware fill of large regions. |
| Grounded-SAM | https://github.com/IDEA-Research/Grounded-Segment-Anything | Python | Apache 2.0 | Combines Grounding DINO open-set detection with SAM to automatically detect and segment anything from text. |
| Grounded-SAM-2 | https://github.com/IDEA-Research/Grounded-SAM-2 | Python | Apache 2.0 | Extends Grounded-SAM to video tracking using Grounding DINO 1.5/1.6 + SAM 2 for object tracking in video. |
| Inpaint-Anything | https://github.com/geekyutao/Inpaint-Anything | Python | Apache 2.0 | Unified pipeline combining SAM + LaMa + Stable Diffusion for click-to-remove or click-to-replace object editing. |
| Florence-2 | https://huggingface.co/microsoft/Florence-2-large | Python | MIT | Microsoft's compact vision-language model for zero-shot captioning, detection, grounding, and segmentation tasks. |
| ProPainter | https://github.com/sczhou/ProPainter | Python | S-Lab License | Video inpainting model for object removal and video completion with improved propagation and transformer architecture. |
| Stable Diffusion Inpainting | https://huggingface.co/runwayml/stable-diffusion-inpainting | Python | CreativeML RAIL-M | Runway's SD 1.5 fine-tune trained on masked image pairs to fill removed regions with context-aware generation. |

---

## 6. SD / FLUX UIs & Workflow Tools

| Name | URL | Language / Platform | License / Free Tier | Description |
|------|-----|---------------------|---------------------|-------------|
| Automatic1111 WebUI (A1111) | https://github.com/AUTOMATIC1111/stable-diffusion-webui | Python | AGPL-3.0 | The original feature-rich SD web UI with the largest extension ecosystem; ideal for beginners and power users alike. |
| ComfyUI | https://github.com/comfyanonymous/ComfyUI | Python | GPL-3.0 | Node-based visual workflow builder for SD and FLUX; community standard for advanced local generation pipelines. |
| Fooocus | https://github.com/lllyasviel/Fooocus | Python | GPL-3.0 | Minimal UI inspired by Midjourney; simplest local setup requiring almost no configuration to start generating. |
| InvokeAI | https://github.com/invoke-ai/InvokeAI | Python | Apache 2.0 | Professional-grade UI with a polished canvas interface, node workflow editor, and strong model management. |
| SD.Next | https://github.com/vladmandic/automatic | Python | AGPL-3.0 | A1111 fork with extended backend support for SD, SDXL, FLUX, and other diffusion models with unified architecture. |
| Stable Diffusion WebUI Forge | https://github.com/lllyasviel/stable-diffusion-webui-forge | Python | AGPL-3.0 | A1111 fork by lllyasviel with optimized memory management; ships with ControlNet and FreeU pre-installed. |
| Easy Diffusion | https://github.com/easydiffusion/easydiffusion | Python | MIT | One-click installer and UI for SD that requires no technical setup; bundles all dependencies automatically. |
| SwarmUI | https://github.com/mcmonkeyprojects/SwarmUI | C# / Python | MIT | Multi-backend UI supporting ComfyUI workflows, cloud deployment, and a web-based grid interface. |
| Kohya SS | https://github.com/kohya-ss/sd-scripts | Python | Apache 2.0 | The standard scripts and GUI wrapper for training LoRA, DreamBooth, and Textual Inversion on SD and FLUX. |
| OneTrainer | https://github.com/Nerogar/OneTrainer | Python | Apache 2.0 | All-in-one diffusion model training tool covering LoRA, full fine-tune, and embedding training with a GUI. |
| SimpleTuner | https://github.com/bghira/SimpleTuner | Python | AGPLv3 | Training toolkit with strong Mac MPS support for fine-tuning FLUX, SD 3.5, and other modern diffusion models. |
| ControlNet | https://github.com/lllyasviel/ControlNet | Python | Apache 2.0 | Structural conditioning plugin for SD that enables depth, edge, pose, and sketch control over generated images. |
| Draw Things | https://drawthings.ai | Swift (iOS/macOS) | Free (App Store) | Offline iOS and macOS app for SD and FLUX image generation with LoRA support and full local privacy. |

---

## 7. Image & Video APIs & Platforms

| Name | URL | Language / Platform | License / Free Tier | Description |
|------|-----|---------------------|---------------------|-------------|
| Replicate | https://replicate.com | REST API | $10 free credit | Hosts 16,000+ open-source models (FLUX, SD, Real-ESRGAN, video models) at pay-per-second GPU pricing. |
| fal.ai | https://fal.ai | REST API | $5 free credit | 600+ generative AI models; 30–50% cheaper than Replicate with lowest-latency inference infrastructure. |
| Hugging Face Inference API | https://huggingface.co/inference-api | REST API | Rate-limited free tier | Access to all major open-source models via serverless or dedicated endpoints on the world's largest model hub. |
| RunPod | https://runpod.io | GPU Cloud / REST API | Pay-as-you-go | GPU cloud for running SD, FLUX, and custom models; includes serverless endpoints and persistent pod options. |
| Modal | https://modal.com | Python SDK / REST API | $30/mo free credit | Developer-first serverless GPU platform for custom image and video AI inference with container-based deployment. |
| Together AI | https://together.ai | REST API | $5 free credit | High-performance inference for open-source models with flexible pricing and broad model selection. |
| Fireworks AI | https://fireworks.ai | REST API | Free tier available | Ultra-fast inference via proprietary FireAttention engine for image, text, and audio models at production scale. |
| Black Forest Labs API | https://api.bfl.ml | REST API | Paid (from $0.003/image) | Official FLUX.1 Pro, FLUX.1.1 Pro, FLUX.2, and FLUX Kontext API from the model creators. |
| Stability AI Platform | https://platform.stability.ai | REST API | 25 free credits | Official API for SD 3.5, Stable Image Ultra, Stable Video Diffusion, and image-to-video models. |
| Google Vertex AI | https://cloud.google.com/vertex-ai | REST API / Python SDK | Free tier (limited) | Enterprise-grade access to Imagen 3, Veo 3, and Gemini vision on Google Cloud infrastructure. |
| Google Gemini API | https://ai.google.dev | REST API / Python SDK | Free tier available | Multimodal API for image understanding, captioning, OCR, and generation via Gemini 2.x Flash and Pro models. |
| OpenAI API | https://platform.openai.com | REST API | $5 free credit | DALL-E 3 image generation, GPT-4o vision understanding, and Sora video generation via unified API. |
| Adobe Firefly API | https://developer.adobe.com/firefly-api | REST API | Paid | Commercially safe generation API trained exclusively on licensed Adobe Stock content. |
| SiliconFlow | https://siliconflow.cn | REST API | Generous free tier | Chinese inference aggregator offering open-source models at industry-low pricing for developers. |
| Cloudinary | https://cloudinary.com | REST API / SDKs | 25 credits/mo free | Full media management platform with real-time transformation, optimization, CDN delivery, and generative AI features. |
| Transloadit | https://transloadit.com | REST API | Free tier | Encoding and processing pipeline for images and videos with 100+ transformation steps and cloud storage integration. |

---

## 8. Browser Extensions

| Name | URL | Browser | License / Free Tier | Description |
|------|-----|---------|---------------------|-------------|
| Remove.bg Extension | https://www.remove.bg/tools-api/extensions | Chrome, Firefox | Free (limited res) | One-click background removal of images found on any web page, powered by the remove.bg API. |
| Clipdrop Extension | https://clipdrop.co | Chrome | Free (limited) | Clip images from anywhere on screen and apply AI tools (background removal, cleanup, upscale) in the browser. |
| Adobe Express Extension | https://adobe.com/express | Chrome | Free | Quick-access sidebar for Adobe Express AI tools including background removal, resize, and quick edit. |
| TinEye Reverse Image Search | https://tineye.com/extensions | Chrome, Firefox | Free | Reverse image search extension to find original image sources, usage rights, and copyright information. |
| Search by Image | https://github.com/dessant/search-by-image | Chrome, Firefox, Safari | Free / Open Source | Open-source extension for multi-engine reverse image search across Google, Bing, Yandex, and others. |
| Sider AI | https://sider.ai | Chrome | Free (limited) | AI sidebar with image generation capability (DALL-E, SD), summarization, and writing assistance. |
| AI Image Detector | https://chromewebstore.google.com/detail/ai-image-detector | Chrome | Free | Detects whether images on web pages were generated by AI models using classification models. |

---

## 9. Figma & Design Tool Plugins

| Name | URL | Platform | License / Free Tier | Description |
|------|-----|----------|---------------------|-------------|
| Figma AI (built-in) | https://figma.com | Figma | Included in plan | Native AI features including object removal, image extension, text generation, and layout suggestions. |
| Magician | https://magician.design | Figma | Free tier available | Generates UX copy, icons, and placeholder images from natural-language prompts directly on the Figma canvas. |
| Lummi AI | https://lummi.ai | Figma | Free tier | AI-generated stock photo library with built-in background removal, upscaling, and reframing inside Figma. |
| Vectorize | https://vectorize.io | Figma | Free tier | Converts raster images to clean SVG vectors using AI for use in design and print workflows. |
| Khroma | https://khroma.co | Web / Figma | Free | AI color palette generator that learns your preferences and suggests harmonious color combinations. |
| Creatie.ai | https://creatie.ai | Figma | Free tier | AI-powered design assistant for generating UI components, images, and copy from prompts inside Figma. |
| html.to.design | https://html.to.design | Chrome / Figma | Free tier | Chrome extension that converts any live website into a fully editable Figma design with AI integration. |
| Galileo AI | https://usegalileo.ai | Figma | Waitlist / paid | Generates complete UI designs from a single text prompt and imports them as editable Figma components. |

---

## 10. WordPress Plugins for Image AI

| Name | URL | Platform | License / Free Tier | Description |
|------|-----|----------|---------------------|-------------|
| Smush | https://wordpress.org/plugins/wp-smushit | WordPress | Free tier (up to 5MB) | WPMU DEV's image optimizer used by 1M+ sites; lazy load, WebP conversion, and bulk compression. |
| ShortPixel Image Optimizer | https://wordpress.org/plugins/shortpixel-image-optimiser | WordPress | 100 images/mo free | AI-powered compression delivering 54% average JPEG reduction; supports WebP and AVIF output formats. |
| Imagify | https://wordpress.org/plugins/imagify | WordPress | 20 MB/mo free | WP Rocket team's image optimizer with three compression levels and one-click WebP conversion. |
| EWWW Image Optimizer | https://wordpress.org/plugins/ewww-image-optimizer | WordPress | Free (local processing) | Server-side image optimization with no file size limits and optional ExactDN CDN; privacy-friendly. |
| Optimole | https://wordpress.org/plugins/optimole-wp | WordPress | 5,000 visits/mo free | Cloud-based image optimization with real-time CDN, lazy loading, and adaptive image sizing by device. |
| TinyPNG — JPEG, PNG & WebP image compression | https://wordpress.org/plugins/tiny-compress-images | WordPress | 500 compressions/mo free | Official TinyPNG/TinyJPG WordPress plugin for lossless smart compression with API key integration. |
| Converter for Media | https://wordpress.org/plugins/webp-converter-for-media | WordPress | Free | Converts PNG, JPEG, and GIF images to WebP or AVIF format automatically on upload. |
| AI Engine | https://wordpress.org/plugins/ai-engine | WordPress | Free tier | Adds generative AI features to WordPress including AI-generated alt text and image generation via GPT-4o. |

---

## 11. Photoshop & Lightroom Plugins

| Name | URL | Platform | License / Free Tier | Description |
|------|-----|----------|---------------------|-------------|
| Topaz Photo AI | https://topazlabs.com/topaz-photo-ai | Photoshop, Lightroom | Paid (~$199 one-time) | Industry-leading AI denoise, sharpen, and upscale plugin with Lightroom and Photoshop integration. |
| Luminar Neo | https://skylum.com/luminar-neo | Photoshop, standalone | From $99/yr | AI-first editor with Sky AI, Relight AI, Skin AI, Noiseless AI, and GenErase; integrates as PS plugin. |
| ON1 NoNoise AI | https://on1.com/nonoise-ai | Photoshop, Lightroom | Paid (~$59.99) | AI-based noise reduction plugin optimized for high-ISO photography with subject masking. |
| Adobe Neural Filters | https://adobe.com/photoshop | Photoshop | Included in subscription | Built-in Photoshop panel with AI filters for skin smoothing, face age, colorization, and style transfer. |
| Retouch4me Heal | https://retouch4me.com | Photoshop | From $35 | AI professional skin retouching plugin removing blemishes while preserving skin texture and pores. |
| Perfectly Clear | https://eyeq.photos | Photoshop, Lightroom | Paid | AI automatic exposure, color, and sharpness correction plugin used in professional photo labs. |
| DxO PureRAW | https://dxo.com/dxo-pureraw | Lightroom (plug-in) | Paid (~$129) | Standalone and Lightroom plugin using DeepPRIME XD AI for best-in-class RAW noise reduction. |
| Excire Foto | https://excire.com | Lightroom | Paid (from €99) | AI-powered Lightroom plugin for semantic image search, auto-tagging, and face recognition across your catalog. |

---

## 12. Mobile Apps (iOS / Android)

| Name | URL | Platform | License / Free Tier | Description |
|------|-----|----------|---------------------|-------------|
| Draw Things | https://drawthings.ai | iOS / macOS | Free | Fully offline on-device SD and FLUX image generation for iPhone, iPad, and Mac with LoRA support. |
| Adobe Lightroom Mobile | https://adobe.com/products/photoshop-lightroom | iOS / Android | Free (limited) | Professional RAW editing with AI-powered denoise, masking, and Firefly-powered generative remove. |
| Snapseed | https://snapseed.online | iOS / Android | Free | Google's comprehensive photo editor with 29 tools including RAW support, selective adjust, and healing brush. |
| VSCO | https://vsco.co | iOS / Android | Free (limited filters) | Film-emulation filters (Kodak Portra, Fuji 160NS) with AI tone split and photo/video editing suite. |
| Prisma | https://prisma-ai.com | iOS / Android | Free (limited) | Neural style transfer app that transforms photos into paintings in styles inspired by Van Gogh, Picasso, and others. |
| PicsArt | https://picsart.com | iOS / Android | Free (with ads) | All-in-one creative platform with AI background removal, AI image generation, and editing for 150M+ users. |
| Lensa AI | https://prisma-ai.com/lensa | iOS / Android | Free (limited) | Magic Avatars and portrait enhancement app from Prisma team; AI face retouching and background replacement. |
| NightCafe Creator | https://creator.nightcafe.studio | iOS / Android / Web | Free (limited credits) | Multi-model AI art generator supporting SD, FLUX, and DALL-E with a social community for sharing creations. |
| YouCam Perfect | https://youcam.com/youcamperfect | iOS / Android | Free (limited) | AI-powered selfie editor with sky replacement, object removal, and AR makeup try-on features. |
| Remini | https://remini.ai | iOS / Android | Free (limited) | AI photo enhancer specializing in face restoration and sharpening of old, blurry, or low-resolution photos. |

---

## 13. CLI Tools for Image Processing

| Name | URL | Language / Platform | License / Free Tier | Description |
|------|-----|---------------------|---------------------|-------------|
| FFmpeg | https://ffmpeg.org | C (cross-platform) | LGPL / GPL | Universal multimedia framework for video/audio encoding, decoding, transcoding, and image frame extraction. |
| ImageMagick CLI | https://imagemagick.org | C (cross-platform) | Apache 2.0 | Powerful CLI for batch image manipulation including resize, crop, format conversion, and filter application. |
| vips (libvips CLI) | https://libvips.github.io/libvips | C (cross-platform) | LGPL-2.1 | Command-line interface to libvips for fast, low-memory image processing with support for 30+ formats. |
| waifu2x-ncnn-vulkan | https://github.com/nihui/waifu2x-ncnn-vulkan | C++ (cross-platform) | MIT | CLI tool for AI upscaling of anime images using Vulkan-accelerated NCNN inference engine. |
| Real-ESRGAN CLI | https://github.com/xinntao/Real-ESRGAN | Python (cross-platform) | BSD-3-Clause | Command-line wrapper for Real-ESRGAN for batch 4x upscaling of photos, anime, and video frames. |
| Squoosh CLI | https://github.com/GoogleChromeLabs/squoosh | Node.js | Apache 2.0 | Google's browser-based compressor exposed as a Node.js CLI for batch AVIF, WebP, and JPEG XL conversion. |
| imgproxy CLI | https://github.com/imgproxy/imgproxy | Go | MIT (open core) | Standalone HTTP image processing server and CLI for resize, crop, format convert, and watermark operations. |
| rembg CLI | https://github.com/danielgatis/rembg | Python | MIT | Single-command background removal for images using BiRefNet AI models; installable via pip. |
| Potrace | http://potrace.sourceforge.net | C (cross-platform) | GPL-2.0 | Transforms bitmaps into smooth, scalable SVG vector graphics via CLI for logo and illustration tracing. |
| exiftool | https://github.com/exiftool/exiftool | Perl (cross-platform) | Artistic License | CLI for reading, writing, and editing metadata (EXIF, IPTC, XMP) embedded in image and video files. |

---

## 14. AI Image & Video Datasets

| Name | URL | Language / Platform | License / Free Tier | Description |
|------|-----|---------------------|---------------------|-------------|
| LAION-5B | https://laion.ai/blog/laion-5b | - | CC BY 4.0 | LAION's 5-billion image-caption pair dataset that trained Stable Diffusion and many other foundation models. |
| Re-LAION-5B | https://laion.ai | - | CC BY 4.0 | Cleaned, deduplicated August 2024 refresh of LAION-5B with improved safety filtering and quality. |
| LAION-Aesthetics | https://laion.ai/blog/laion-aesthetics | - | CC BY 4.0 | Aesthetic-quality subset of LAION-5B filtered by a CLIP-based aesthetic predictor; used for SD fine-tuning. |
| ImageNet | https://image-net.org | - | Custom (research) | 14M+ labeled images across 22,000 categories; the canonical benchmark dataset for image classification models. |
| MS-COCO | https://cocodataset.org | - | CC BY 4.0 | 330,000+ images with rich annotations for object detection, segmentation, and image captioning tasks. |
| Open Images v7 | https://storage.googleapis.com/openimages/web | - | CC BY 4.0 | Google's 9M annotated images with 600 object classes, bounding boxes, segmentation masks, and relationships. |
| SA-1B (SAM Dataset) | https://ai.meta.com/datasets/segment-anything | - | Research use | Meta's 1-billion mask dataset of 11M diverse images used to train the Segment Anything Model. |
| WebVid-10M | https://m-bain.github.io/webvid-dataset | - | Custom (research) | 10.7M video-text pairs scraped from the web; used to train video generation models including Make-A-Video. |
| Conceptual Captions | https://ai.google.com/research/ConceptualCaptions | - | Custom (research) | Google's 3.3M (CC3M) and 12M (CC12M) web image-caption pairs for vision-language pretraining. |
| DiffusionDB | https://poloclub.github.io/diffusiondb | - | CC0 | 14M SD-generated images with their prompts and parameters; useful for prompt engineering research. |

---

## 15. AI Image Detection & Content Moderation

| Name | URL | Language / Platform | License / Free Tier | Description |
|------|-----|---------------------|---------------------|-------------|
| Falconsai NSFW Detector | https://huggingface.co/Falconsai/nsfw_image_detection | Python | Apache 2.0 | Open-source ViT-based NSFW image classifier available on Hugging Face with free inference API. |
| CLIP-based NSFW Detector | https://github.com/LAION-AI/CLIP-based-NSFW-Detector | Python | MIT | LAION's NSFW scoring model built on CLIP embeddings for filtering training datasets and user content. |
| Hive Moderation | https://thehive.ai | REST API | Paid (trial available) | Commercial API with 98–99.9% accuracy for AI-generated image detection, deepfake detection, and NSFW moderation. |
| Microsoft Azure Content Safety | https://azure.microsoft.com/products/ai-services/content-safety | REST API | Free tier (5,000 calls/mo) | Enterprise content moderation API detecting harmful images, text, and multimodal content at scale. |
| Amazon Rekognition | https://aws.amazon.com/rekognition | REST API | 5,000 images/mo free | AWS service for content moderation, face analysis, object detection, and unsafe content classification. |
| SynthID | https://deepmind.google/technologies/synthid | Python (via partners) | Open to partners | Google DeepMind's imperceptible watermarking technology that embeds and detects AI image provenance. |
| C2PA / Content Credentials | https://c2pa.org | SDK (JS, Rust, Python) | Open standard | Industry standard cryptographic metadata schema (Adobe, Microsoft, BBC) for verifiable content provenance. |
| AI or Not | https://aiornot.com | REST API | Free tier | Real-time detector that identifies whether images were generated by Midjourney, DALL-E, SD, or other AI tools. |
| Optic | https://github.com/nicktindall/optic | Python | MIT | Open-source toolkit for detecting manipulated and AI-generated images based on frequency domain analysis. |

---

## 16. AI Image Tagging, Classification & Captioning

| Name | URL | Language / Platform | License / Free Tier | Description |
|------|-----|---------------------|---------------------|-------------|
| BLIP | https://github.com/salesforce/BLIP | Python | BSD-3-Clause | Salesforce's vision-language pretraining framework for image captioning, VQA, and image-text retrieval. |
| BLIP-2 | https://huggingface.co/Salesforce/blip2-opt-2.7b | Python | BSD-3-Clause | Zero-shot visual question answering and captioning using a lightweight Q-Former bridging image encoder and LLM. |
| CLIP | https://github.com/openai/CLIP | Python | MIT | OpenAI's contrastive image-text model for zero-shot classification, semantic search, and image-text matching. |
| SigLIP 2 | https://huggingface.co/google/siglip2-so400m-patch14-384 | Python | Apache 2.0 | Google's improved sigmoid loss image-text model with captioning pretraining for superior image understanding. |
| WD-14 Tagger | https://huggingface.co/SmilingWolf/wd-eva02-large-tagger-v3 | Python | Apache 2.0 | Anime and illustration auto-tagger widely used in the SD community for dataset captioning and LoRA training. |
| Florence-2 | https://huggingface.co/microsoft/Florence-2-large | Python | MIT | Microsoft's compact VLM for zero-shot captioning, object detection, grounding, and segmentation in one model. |
| LLaVA | https://github.com/haotian-liu/LLaVA | Python | Apache 2.0 | Open-source visual instruction tuning model combining a vision encoder with Llama/Mistral for image chat and captioning. |
| Qwen-VL | https://github.com/QwenLM/Qwen-VL | Python | Apache 2.0 | Alibaba's multimodal large language model for image understanding, captioning, and visual question answering. |
| DeepDanbooru | https://github.com/KichangKim/DeepDanbooru | Python | MIT | Anime-style image tag classifier trained on Danbooru dataset; widely used for SD training dataset annotation. |
| AutoTag-AI | https://github.com/kruth-s/AutoTag-AI | Python | MIT | Pipeline combining BLIP captioning, KeyBERT keyword extraction, and CLIP filtering for zero-shot image auto-tagging. |

---

## 17. AI OCR

| Name | URL | Language / Platform | License / Free Tier | Description |
|------|-----|---------------------|---------------------|-------------|
| Tesseract OCR | https://github.com/tesseract-ocr/tesseract | C++ / Python | Apache 2.0 | Google-maintained LSTM-based OCR engine supporting 116 languages; the standard open-source baseline. |
| EasyOCR | https://github.com/JaidedAI/EasyOCR | Python | Apache 2.0 | PyTorch-based OCR library supporting 80+ languages including Arabic, CJK, and Cyrillic with a simple Python API. |
| PaddleOCR | https://github.com/PaddlePaddle/PaddleOCR | Python | Apache 2.0 | Baidu's ultra-lightweight (<10 MB) but high-accuracy OCR toolkit with multilingual recognition and layout analysis. |
| TrOCR | https://huggingface.co/microsoft/trocr-large-printed | Python | MIT | Microsoft's Transformer-based OCR model fine-tuned for printed and handwritten text with strong layout handling. |
| docTR | https://github.com/mindee/doctr | Python | Apache 2.0 | Mindee's end-to-end document text recognition library combining detection and recognition in a unified pipeline. |
| Surya | https://github.com/VikParuchuri/surya | Python | GPL-3.0 | Multilingual document OCR with line-level text detection, layout analysis, and reading order for PDFs and images. |
| Manga OCR | https://github.com/kha-white/manga-ocr | Python | MIT | Specialized OCR model fine-tuned for Japanese manga text including complex layouts and stylized fonts. |
| Keras-OCR | https://github.com/faustomorales/keras-ocr | Python | MIT | Packaged end-to-end OCR pipeline based on CRAFT text detection and CRNN recognition for English text. |
| GOT-OCR 2.0 | https://github.com/Ucas-HaoranWei/GOT-OCR2.0 | Python | Apache 2.0 | General OCR Theory model supporting plain text, tables, math formulas, charts, and molecular structures. |
| OmniParser | https://github.com/microsoft/OmniParser | Python | MIT | Microsoft's multimodal screen parsing model combining OCR and icon detection for UI understanding tasks. |

---

## 18. Image CDN & Optimization Services

| Name | URL | Language / Platform | License / Free Tier | Description |
|------|-----|---------------------|---------------------|-------------|
| Cloudinary | https://cloudinary.com | REST API / SDKs | 25 credits/mo free | Full DAM + CDN platform with AI-driven optimization, real-time transformation, and generative AI features. |
| Imgix | https://imgix.com | REST API | Paid (trial) | Real-time image processing CDN that connects to your existing S3/GCS storage and serves transformed images on-the-fly. |
| Cloudflare Images | https://cloudflare.com/products/cloudflare-images | REST API | Paid (~$5/mo + usage) | Cloudflare's image storage and transformation service tightly integrated with their global CDN and security layer. |
| Bunny Optimizer | https://bunny.net/optimizer | REST API | Add-on to Bunny CDN | Image optimization and WebP/AVIF conversion add-on to BunnyCDN; among the fastest processors in benchmarks. |
| ImageKit | https://imagekit.io | REST API / SDKs | 20 GB free/mo | Developer-friendly platform with 50+ real-time transformations, automatic format optimization, and AI background removal. |
| Fastly Image Optimizer | https://fastly.com/products/image-optimizer | REST API | Enterprise pricing | Enterprise-grade image processing integrated with Fastly's edge CDN for sub-millisecond global delivery. |
| Sirv | https://sirv.com | REST API | Free tier (500 MB) | Visual commerce CDN with real-time image optimization, 360-degree product spins, and AI zoom for e-commerce. |
| Uploadcare | https://uploadcare.com | REST API / SDKs | Free tier (3 GB) | File handling platform with CDN delivery, real-time image transformations, and AI background removal API. |
| imgproxy | https://imgproxy.net | Go (self-hosted) | Open-source (OSS) / Paid Pro | Fast, secure self-hosted image processing server powered by libvips; processes URLs on-the-fly with no storage. |
| Thumbor | https://github.com/thumbor/thumbor | Python (self-hosted) | MIT | Open-source, self-hosted image service with smart cropping, filters, face detection-aware resizing, and watermarking. |
| Imagor | https://github.com/cshum/imagor | Go (self-hosted) | Apache 2.0 | Fast Docker-ready image processing server written in Go; Thumbor-compatible URL interface backed by libvips. |
| Gumlet | https://gumlet.com | REST API | Free tier (1 GB/mo) | Image and video CDN with automatic optimization, AI smart crop, and real-time format conversion. |

---

> **Note on counts:** This document lists 152 distinct tools across all 18 categories, well exceeding the 100-tool minimum requested.

> **Last updated:** February 2026. Open-source projects change rapidly; always verify current licensing and availability at the linked repositories.
