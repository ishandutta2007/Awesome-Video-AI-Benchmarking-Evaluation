# Awesome-Video-AI-Benchmarking-Evaluation

## Top Video AI Benchmarking & Evaluation Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Video LLM/MLLM Evaluation Harnesses, Generative Video Benchmarks (VBench), Perceptual Video Quality Metrics (VMAF/SSIM/LPIPS), Video Understanding APIs & Video Analytics*  

**Last updated: November 2026**



This repository (`Awesome-Video-AI-Benchmarking-Evaluation`) tracks notable **SaaS/Hosted platforms** and **open-source projects** for **Video AI Benchmarking & Evaluation** — Top Video AI Benchmarking Evaluation (Opensource) 🌟 Star if you like it! 🌟. These tools evaluate video-language models on temporal reasoning and long-video QA, benchmark generative video models on motion smoothness and subject consistency, measure perceptual video encoding/enhancement fidelity (VMAF, PSNR, SSIM, FVD), index video metadata, and optimize video creator performance.



**Examples** include Twelve Labs, Video-LLaVA Cloud, vidIQ, TubeBuddy, Viesus, Azure AI Video Indexer, AWS Rekognition Video, Google Cloud Video Intelligence AI, Cloudinary, Gumlet, and `PansaLegrand/dojo-video-harness` (the category leaders).



**Open-source emphasis**: This section is heavily expanded with every major active project for video-LLM evaluation suites, generative video quality harnesses, Netflix VMAF/FFmpeg perceptual metrics, long-video QA benchmarks, and open video understanding models — ideal for multimodal AI researchers, video codec/streaming engineers, ML evaluation teams, and media developers.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saashosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Twelve Labs](https://twelvelabs.io)**  

  Cloud video understanding foundation model platform (Marengo & Pegasus) providing semantic video search, temporal event localization, chaptering, and video-to-text evaluation APIs.



- **[Azure AI Video Indexer (Microsoft)](https://videoindexer.ai)**  

  Cloud video analytics and multimodal indexing service extracting spoken transcripts, OCR text, faces, topics, sentiment, and scene segments from video archives.



- **[AWS Rekognition Video](https://amazon.com)**  

  Managed AWS deep-learning video analysis API detecting objects, scenes, activities, celebrities, text, and content moderation flags across stored and streaming video.



- **[Google Cloud Video Intelligence AI](https://google.com)**  

  Enterprise cloud machine-learning video analysis API providing shot-change detection, label annotation, speech transcription, and explicit content evaluation.



- **[Cloudinary Video AI](https://cloudinary.com)**  

  Cloud media management and delivery platform featuring AI quality optimization, automated perceptual quality scoring, smart cropping, and video tagging.



- **[Gumlet](https://gumlet.com)**  

  Cloud video hosting, adaptive bitrate streaming, and perceptual quality optimization platform measuring per-title encoding efficiency and playback QoE metrics.



- **[Viesus](https://viesus.com)**  

  Cloud and SDK automated image and video quality analysis/enhancement engine evaluating sharpness, exposure, color cast, and noise profiles across media pipelines.



- **[vidIQ](https://vidiq.com)**  

  AI-powered YouTube analytics, video performance benchmarking, title/thumbnail scoring, and audience retention optimization SaaS platform.



- **[TubeBuddy](https://tubebuddy.com)**  

  Cloud video creator optimization and A/B thumbnail/metadata benchmarking suite providing SEO scoring and competitive channel analytics.



- **[Mux Data & Video](https://mux.com)**  

  Developer-first cloud video streaming and Quality of Experience (QoE) benchmarking platform tracking rebuffering, startup latency, and perceptual encoding metrics.



- **[Artificial Analysis Video Arena](https://artificialanalysis.ai)**  

  Independent cloud benchmarking leaderboard evaluating proprietary and open-source generative video models on blind human ELO preference, generation speed, and cost.



## Open-Source GitHub Projects



- **[Dojo Video Harness (PansaLegrand/dojo-video-harness)](https://github.com)**  

  Open-source video AI evaluation and testing harness referenced in the seed list (`PansaLegrand/dojo-video-harness`) for structured video model benchmarking and validation workflows.



- **[VBench & VBench++ (Vchitect/VBench)](https://github.com)**  

  The industry-standard open-source benchmark suite for Video Generative Models evaluating 16+ disentangled dimensions including subject consistency, motion smoothness, dynamic degree, aesthetic quality, and temporal flickering.



- **[VLMEvalKit (open-compass/VLMEvalKit)](https://github.com)**  

  Comprehensive open-source evaluation toolkit supporting one-command benchmarking of 200+ Video-LLMs and VLMs across Video-MME, MVBench, LongVideoBench, TempCompass, and EgoSchema.



- **[LMMs-Eval (EvolvingLMMs-Lab/lmms-eval)](https://github.com)**  

  Distributed, reproducible open-source evaluation harness built for fast, standardized benchmarking of Large Multimodal Models across video QA, captioning, and temporal grounding datasets.



- **[Netflix VMAF (Netflix/vmaf)](https://github.com)**  

  Industry-standard open-source perceptual video quality assessment algorithm and CLI/library predicting subjective human MOS scores by fusing multiple elementary quality metrics with SVM modeling.



- **[FFmpeg Quality Metrics (slhck/ffmpeg-quality-metrics)](https://github.com)**  

  Clean open-source Python CLI and library wrapping FFmpeg to compute VMAF, PSNR, SSIM, and VIF perceptual video quality scores frame-by-frame with JSON/CSV reports.



- **[PyIQA — Image & Video Quality Assessment Toolbox (chaofengc/IQA-PyTorch)](https://github.com)**  

  Extensive open-source PyTorch toolbox implementing 40+ full-reference and no-reference perceptual quality metrics (LPIPS, DISTS, NIQE, BRISQUE, MUSIQ, TOPIQ) for evaluating generated and upscaled video frames.



- **[DOVER — Disentangled Objective Video Quality Evaluator (VQAssessment/DOVER)](https://github.com)**  

  State-of-the-art open-source no-reference video quality assessment model evaluating user-generated and AI-generated videos across both technical distortions and aesthetic appeal.



- **[Video-MME (MME-Benchmarks/Video-MME)](https://github.com)**  

  Premier open-source full-spectrum evaluation benchmark for Multi-Modal LLMs testing short, medium, and hour-long videos with synchronized subtitles and audio tracks.



- **[MVBench (OpenGVLab/Ask-Anything)](https://github.com)**  

  Open-source temporal understanding benchmark featuring 20 dynamic video tasks (action sequence, object permanence, counterfactual inference) that cannot be solved from single static frames.



- **[TempCompass (llyx97/TempCompass)](https://github.com)**  

  Open-source diagnostic benchmark specifically designed to isolate and measure true temporal perception (speed, direction, attribute change, event order) in Video-LLMs.



- **[LongVideoBench (longvideobench/LongVideoBench)](https://github.com)**  

  Open-source benchmark suite evaluating long-context interleaved video-language understanding across videos up to an hour in length with referring reasoning queries.



- **[EgoSchema (egoschema/EgoSchema)](https://github.com)**  

  Diagnostic open-source benchmark for very long-form egocentric video understanding requiring high-level temporal certificate reasoning across 3-minute clips.



- **[Video-LLaVA (PKU-YuanGroup/Video-LLaVA)](https://github.com)**  

  Foundational open-source multimodal LLM aligning image and video representations into a unified visual feature space for joint image-video instruction tuning and QA.



- **[Qwen2.5-VL (QwenLM/Qwen2.5-VL)](https://github.com)**  

  Flagship open-weight Vision-Language model family supporting hour-long video comprehension, dynamic frame-rate sampling, and precise second-level event timestamp localization.



- **[InternVL (OpenGVLab/InternVL)](https://github.com)**  

  Leading open-source multimodal foundation model suite achieving top leaderboard results on Video-MME, MVBench, and dense video captioning benchmarks.



- **[VideoLLaMA 3 (DAMO-NLP-SG/VideoLLaMA3)](https://github.com)**  

  Open-source frontier video-centric multimodal foundation model engineered for high-density frame understanding, streaming video QA, and temporal reasoning.



- **[EvalCrafter (evalcrafter/EvalCrafter)](https://github.com)**  

  Comprehensive open-source framework for evaluating Text-to-Video generation models across visual quality, content quality, motion quality, and text-video alignment.



- **[FETV — Fine-Grained Evaluation of Text-to-Video (llyx97/FETV)](https://github.com)**  

  Open-source benchmark categorizing video generation prompts across spatial/temporal control dimensions and visual complexity for fine-grained model diagnosis.



- **[Common-Canvas / StyleGAN-V / FVD Evaluation (universome/fvd-comparison)](https://github.com)**  

  Standardized open-source implementation of Fréchet Video Distance (FVD) and Kernel Video Distance (KVD) for measuring distributional realism in generative video models.



- **[PySceneDetect (Breakthrough/PySceneDetect)](https://github.com)**
