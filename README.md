# Awesome AI List — AI Tools, Agent Skills, and GitHub Repositories

Find tools for running a local language model, editing video, generating images and speech, or adding an AI coding assistant to your workflow. This directory covers 114 GitHub repositories across 16 categories, from model libraries to everyday tools such as video editors and secret scanners.

## Find a Tool by Task

|                                         | Start here                                                                                                                                    |
| --------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------- |
| Build an offline chat app               | Serve a model with Ollama and connect it to Open WebUI. [Local LLMs and chat interfaces](#local-llms-and-chat-interfaces)                     |
| Turn a script into an educational video | Render scenes with Remotion, then trim and combine clips with FFmpeg. [Video editing and post-production](#video-editing-and-post-production) |
| Create artwork from a reference image   | Use IP-Adapter to guide image generation with a reference picture. [Image generation and control](#image-generation-and-control)              |
| Add an offline voice-over               | Generate narration from text with Piper. [Text-to-speech and voice synthesis](#text-to-speech-and-voice-synthesis)                            |
| Check a codebase for exposed secrets    | Scan Git history with Gitleaks. [Defensive security and secret detection](#defensive-security-and-secret-detection)                           |

## Browse All Categories

- [Reusable Agent Skills](#reusable-agent-skills) (3)
- [Local LLMs and Chat Interfaces](#local-llms-and-chat-interfaces) (3)
- [Model Development and Semantic Search](#model-development-and-semantic-search) (2)
- [AI Agent Workflows and Retrieval-Augmented Generation (RAG)](#ai-agent-workflows-and-retrieval-augmented-generation-rag) (2)
- [Evaluation and Observability](#evaluation-and-observability) (2)
- [Speech and Image Workflows](#speech-and-image-workflows) (2)
- [Video Editing and Post-Production](#video-editing-and-post-production) (10)
- [Video Generation and Animation](#video-generation-and-animation) (10)
- [Image Generation and Control](#image-generation-and-control) (10)
- [Image Editing and Restoration](#image-editing-and-restoration) (10)
- [AI Coding Assistants and Developer Tools](#ai-coding-assistants-and-developer-tools) (10)
- [Text-to-Speech and Voice Synthesis](#text-to-speech-and-voice-synthesis) (10)
- [Audio, Music, and Transcription](#audio-music-and-transcription) (10)
- [Defensive Security and Secret Detection](#defensive-security-and-secret-detection) (10)
- [Documents, OCR, and Data Extraction](#documents-ocr-and-data-extraction) (10)
- [AI Applications, Search, and Model Serving](#ai-applications-search-and-model-serving) (10)

Each entry links to its GitHub repository. Star counts are rounded snapshots recorded on November 17, 2026.

## Reusable Agent Skills

| Name                    | Link                                                 | Description                                                                                 | Repository Owner | GitHub Stars |
| ----------------------- | ---------------------------------------------------- | ------------------------------------------------------------------------------------------- | ---------------- | ------------ |
| **Anthropic Skills**    | [Visit](https://github.com/anthropics/skills)        | Provides reusable agent skills and a skill creator for packaging recurring tasks.           | anthropics       | 196.2k       |
| **Vercel Agent Skills** | [Visit](https://github.com/vercel-labs/agent-skills) | Guides coding agents through React performance reviews and other frontend tasks.            | vercel-labs      | 34.2k        |
| **Superpowers**         | [Visit](https://github.com/obra/superpowers)         | Provides coding agents with workflows for planning, systematic debugging, and verification. | obra             | 318.8k       |

## Local LLMs and Chat Interfaces

| Name           | Link                                              | Description                                                                    | Repository Owner | GitHub Stars |
| -------------- | ------------------------------------------------- | ------------------------------------------------------------------------------ | ---------------- | ------------ |
| **Ollama**     | [Visit](https://github.com/ollama/ollama)         | Serves language models locally through an HTTP API that applications can call. | ollama           | 187.3k       |
| **llama.cpp**  | [Visit](https://github.com/ggml-org/llama.cpp)    | Runs quantized GGUF language models on CPUs and GPUs.                          | ggml-org         | 135.4k       |
| **Open WebUI** | [Visit](https://github.com/open-webui/open-webui) | Provides a browser-based chat interface for Ollama and other model servers.    | open-webui       | 158.9k       |

## Model Development and Semantic Search

| Name                      | Link                                                          | Description                                                              | Repository Owner | GitHub Stars |
| ------------------------- | ------------------------------------------------------------- | ------------------------------------------------------------------------ | ---------------- | ------------ |
| **Transformers**          | [Visit](https://github.com/huggingface/transformers)          | Loads and fine-tunes pretrained models for text, image, and audio tasks. | huggingface      | 169.1k       |
| **Sentence Transformers** | [Visit](https://github.com/huggingface/sentence-transformers) | Encodes text for semantic search and reranks results by relevance.       | huggingface      | 19.3k        |

## AI Agent Workflows and Retrieval-Augmented Generation (RAG)

| Name           | Link                                               | Description                                                                                      | Repository Owner | GitHub Stars |
| -------------- | -------------------------------------------------- | ------------------------------------------------------------------------------------------------ | ---------------- | ------------ |
| **LangGraph**  | [Visit](https://github.com/langchain-ai/langgraph) | Coordinates multi-step agent workflows with checkpoints and human review.                        | langchain-ai     | 45.1k        |
| **LlamaIndex** | [Visit](https://github.com/run-llama/llama_index)  | Connects document collections to question-answering applications through indexing and retrieval. | run-llama        | 52.9k        |

## Evaluation and Observability

| Name          | Link                                            | Description                                                                                   | Repository Owner | GitHub Stars |
| ------------- | ----------------------------------------------- | --------------------------------------------------------------------------------------------- | ---------------- | ------------ |
| **Promptfoo** | [Visit](https://github.com/promptfoo/promptfoo) | Tests prompts and models against repeatable examples and assertions.                          | promptfoo        | 27.3k        |
| **Langfuse**  | [Visit](https://github.com/langfuse/langfuse)   | Traces model calls to help developers investigate response quality, latency, and token usage. | langfuse         | 37.5k        |

## Speech and Image Workflows

| Name        | Link                                          | Description                                                                   | Repository Owner | GitHub Stars |
| ----------- | --------------------------------------------- | ----------------------------------------------------------------------------- | ---------------- | ------------ |
| **Whisper** | [Visit](https://github.com/openai/whisper)    | Transcribes speech into timestamped text for subtitles and dubbing workflows. | openai           | 112.9k       |
| **ComfyUI** | [Visit](https://github.com/Comfy-Org/ComfyUI) | Connects visual nodes into reusable image-generation workflows.               | Comfy-Org        | 147.2k       |

## Video Editing and Post-Production

| Name              | Link                                                   | Description                                                                    | Repository Owner | GitHub Stars |
| ----------------- | ------------------------------------------------------ | ------------------------------------------------------------------------------ | ---------------- | ------------ |
| **FFmpeg**        | [Visit](https://github.com/FFmpeg/FFmpeg)              | Trim, transcode, and combine audio and video from the command line.            | FFmpeg           | 67.4k        |
| **remotion**      | [Visit](https://github.com/remotion-dev/remotion)      | Render React components as videos for repeatable explainers and product demos. | remotion-dev     | 73.7k        |
| **moviepy**       | [Visit](https://github.com/Zulko/moviepy)              | Script cuts, captions, overlays, and compositing in Python.                    | Zulko            | 15.2k        |
| **lossless-cut**  | [Visit](https://github.com/mifi/lossless-cut)          | Cut unwanted sections from recordings without re-encoding compatible streams.  | mifi             | 46.1k        |
| **shotcut**       | [Visit](https://github.com/mltframework/shotcut)       | Edit multiple tracks on a timeline and apply video and audio filters.          | mltframework     | 15.7k        |
| **kdenlive**      | [Visit](https://github.com/KDE/kdenlive)               | Assemble footage with proxy clips, transitions, and keyframed effects.         | KDE              | 6.1k         |
| **OpenShot**      | [Visit](https://github.com/OpenShot/openshot-qt)       | Combine clips, titles, and soundtracks in a desktop timeline editor.           | OpenShot         | 6.8k         |
| **olive**         | [Visit](https://github.com/olive-editor/olive)         | Edit and composite footage with a node-based desktop video editor.             | olive-editor     | 9.2k         |
| **auto-editor**   | [Visit](https://github.com/WyattBlue/auto-editor)      | Automatically shorten recordings by cutting sections with little or no sound.  | WyattBlue        | 6.0k         |
| **PySceneDetect** | [Visit](https://github.com/Breakthrough/PySceneDetect) | Detect shot boundaries and export timestamps for splitting long videos.        | Breakthrough     | 5.5k         |

## Video Generation and Animation

| Name                         | Link                                                       | Description                                                                         | Repository Owner | GitHub Stars |
| ---------------------------- | ---------------------------------------------------------- | ----------------------------------------------------------------------------------- | ---------------- | ------------ |
| **Wan2.1**                   | [Visit](https://github.com/Wan-Video/Wan2.1)               | Generate clips from text or still images with the Wan 2.1 model family.             | Wan-Video        | 17.4k        |
| **Wan2.2**                   | [Visit](https://github.com/Wan-Video/Wan2.2)               | Use Wan 2.2 models for text- and image-conditioned video generation.                | Wan-Video        | 18.7k        |
| **LTX-Video**                | [Visit](https://github.com/Lightricks/LTX-Video)           | Generate short video sequences with Lightricks’ latent video diffusion models.      | Lightricks       | 11.4k        |
| **CogVideo**                 | [Visit](https://github.com/zai-org/CogVideo)               | Turn written scene descriptions into clips with the CogVideo model family.          | zai-org          | 13.2k        |
| **Open-Sora**                | [Visit](https://github.com/hpcaitech/Open-Sora)            | Explore code and model configurations for training and running video generators.    | hpcaitech        | 29.9k        |
| **HunyuanVideo**             | [Visit](https://github.com/Tencent-Hunyuan/HunyuanVideo)   | Generate video from written prompts using Tencent’s HunyuanVideo models.            | Tencent-Hunyuan  | 12.8k        |
| **AnimateDiff**              | [Visit](https://github.com/guoyww/AnimateDiff)             | Animate compatible image diffusion models with motion modules.                      | guoyww           | 12.3k        |
| **FramePack**                | [Visit](https://github.com/lllyasviel/FramePack)           | Generate video progressively from an image using frame context from previous steps. | lllyasviel       | 17.4k        |
| **ComfyUI-WanVideoWrapper**  | [Visit](https://github.com/kijai/ComfyUI-WanVideoWrapper)  | Build Wan video-generation workflows inside ComfyUI.                                | kijai            | 6.8k         |
| **Deforum Stable Diffusion** | [Visit](https://github.com/dmarx/deforum-stable-diffusion) | Create diffusion animations with keyframed camera movement and changing prompts.    | dmarx            | 3            |

## Image Generation and Control

| Name                       | Link                                                             | Description                                                                   | Repository Owner  | GitHub Stars |
| -------------------------- | ---------------------------------------------------------------- | ----------------------------------------------------------------------------- | ----------------- | ------------ |
| **diffusers**              | [Visit](https://github.com/huggingface/diffusers)                | Build Python pipelines for diffusion-based image generation and editing.      | huggingface       | 34.9k        |
| **flux**                   | [Visit](https://github.com/black-forest-labs/flux)               | Run Black Forest Labs’ FLUX image models using the reference inference code.  | black-forest-labs | 26.1k        |
| **generative-models**      | [Visit](https://github.com/Stability-AI/generative-models)       | Experiment with Stability AI’s image generation model implementations.        | Stability-AI      | 27.3k        |
| **ControlNet**             | [Visit](https://github.com/lllyasviel/ControlNet)                | Guide a diffusion model with an edge map, depth map, or pose.                 | lllyasviel        | 34.2k        |
| **stable-diffusion-webui** | [Visit](https://github.com/AUTOMATIC1111/stable-diffusion-webui) | Generate and inpaint images through a browser interface for Stable Diffusion. | AUTOMATIC1111     | 165.3k       |
| **InvokeAI**               | [Visit](https://github.com/invoke-ai/InvokeAI)                   | Generate and refine images with a canvas and reusable workflows.              | invoke-ai         | 29.1k        |
| **HunyuanDiT**             | [Visit](https://github.com/Tencent-Hunyuan/HunyuanDiT)           | Generate images from English or Chinese prompts with HunyuanDiT.              | Tencent-Hunyuan   | 4.3k         |
| **stylegan3**              | [Visit](https://github.com/NVlabs/stylegan3)                     | Train or run a style-based generator for image synthesis experiments.         | NVlabs            | 6.9k         |
| **IP-Adapter**             | [Visit](https://github.com/tencent-ailab/IP-Adapter)             | Condition a diffusion model on a reference image alongside a text prompt.     | tencent-ailab     | 6.7k         |
| **latent-diffusion**       | [Visit](https://github.com/CompVis/latent-diffusion)             | Study and run the original latent diffusion approach to image synthesis.      | CompVis           | 14.2k        |

## Image Editing and Restoration

| Name                 | Link                                                          | Description                                                                         | Repository Owner | GitHub Stars |
| -------------------- | ------------------------------------------------------------- | ----------------------------------------------------------------------------------- | ---------------- | ------------ |
| **Real-ESRGAN**      | [Visit](https://github.com/xinntao/Real-ESRGAN)               | Upscale low-resolution photos and illustrations with pretrained restoration models. | xinntao          | 37.5k        |
| **GFPGAN**           | [Visit](https://github.com/TencentARC/GFPGAN)                 | Restore facial details in degraded photographs.                                     | TencentARC       | 37.7k        |
| **CodeFormer**       | [Visit](https://github.com/sczhou/CodeFormer)                 | Restore faces from low-quality images with a controllable fidelity setting.         | sczhou           | 18.2k        |
| **rembg**            | [Visit](https://github.com/danielgatis/rembg)                 | Remove image backgrounds from Python or the command line.                           | danielgatis      | 25.5k        |
| **segment-anything** | [Visit](https://github.com/facebookresearch/segment-anything) | Create object masks by selecting points or boxes in an image.                       | facebookresearch | 55.1k        |
| **sam2**             | [Visit](https://github.com/facebookresearch/sam2)             | Track a selected object across video frames and generate segmentation masks.        | facebookresearch | 20.2k        |
| **IOPaint**          | [Visit](https://github.com/Sanster/IOPaint)                   | Remove unwanted objects from images with an interactive inpainting interface.       | Sanster          | 23.3k        |
| **lama**             | [Visit](https://github.com/advimman/lama)                     | Fill masked areas in photos using large-mask inpainting models.                     | advimman         | 10.4k        |
| **Restormer**        | [Visit](https://github.com/swz30/Restormer)                   | Restore images affected by problems such as motion blur, rain, or noise.            | swz30            | 2.7k         |
| **SwinIR**           | [Visit](https://github.com/JingyunLiang/SwinIR)               | Apply transformer-based models to denoising, upscaling, and artifact removal.       | JingyunLiang     | 5.6k         |

## AI Coding Assistants and Developer Tools

| Name           | Link                                                 | Description                                                                             | Repository Owner | GitHub Stars |
| -------------- | ---------------------------------------------------- | --------------------------------------------------------------------------------------- | ---------------- | ------------ |
| **aider**      | [Visit](https://github.com/Aider-AI/aider)           | Ask a terminal coding assistant to edit files in a Git repository.                      | Aider-AI         | 50.2k        |
| **continue**   | [Visit](https://github.com/continuedev/continue)     | Configure AI-assisted coding workflows around your project and preferred models.        | continuedev      | 36.5k        |
| **cline**      | [Visit](https://github.com/cline/cline)              | Use an editor-based assistant to propose file changes and run development tasks.        | cline            | 71.7k        |
| **opencode**   | [Visit](https://github.com/anomalyco/opencode)       | Work with a terminal coding agent to navigate and modify a codebase.                    | anomalyco        | 227.4k       |
| **codex**      | [Visit](https://github.com/openai/codex)             | Use OpenAI’s coding agent from the command line to inspect and edit a project.          | openai           | 135.5k       |
| **gemini-cli** | [Visit](https://github.com/google-gemini/gemini-cli) | Use Gemini from the terminal to explain code and work on development tasks.             | google-gemini    | 108.9k       |
| **goose**      | [Visit](https://github.com/aaif-goose/goose)         | Connect a local development agent to tools for multi-step coding tasks.                 | aaif-goose       | 56.7k        |
| **OpenHands**  | [Visit](https://github.com/OpenHands/OpenHands)      | Run a software development agent for tasks such as fixing bugs or implementing changes. | OpenHands        | 93.6k        |
| **tabby**      | [Visit](https://github.com/TabbyML/tabby)            | Self-host a coding assistant that provides editor completions.                          | TabbyML          | 33.9k        |
| **spec-kit**   | [Visit](https://github.com/github/spec-kit)          | Turn feature requirements into specifications, implementation plans, and coding tasks.  | github           | 150.1k       |

## Text-to-Speech and Voice Synthesis

| Name            | Link                                               | Description                                                                      | Repository Owner | GitHub Stars |
| --------------- | -------------------------------------------------- | -------------------------------------------------------------------------------- | ---------------- | ------------ |
| **Coqui TTS**   | [Visit](https://github.com/coqui-ai/TTS)           | Train and run speech synthesis models using a Python toolkit.                    | coqui-ai         | 46.2k        |
| **kokoro**      | [Visit](https://github.com/hexgrad/kokoro)         | Generate spoken narration locally with a lightweight text-to-speech model.       | hexgrad          | 10.2k        |
| **Mozilla TTS** | [Visit](https://github.com/mozilla/TTS)            | Explore Mozilla’s research toolkit for training speech synthesis models.         | mozilla          | 10.2k        |
| **OpenVoice**   | [Visit](https://github.com/myshell-ai/OpenVoice)   | Generate speech with a reference voice and adjustable delivery.                  | myshell-ai       | 38.3k        |
| **F5-TTS**      | [Visit](https://github.com/SWivid/F5-TTS)          | Synthesize speech from text and a short voice reference.                         | SWivid           | 15.6k        |
| **CosyVoice**   | [Visit](https://github.com/QwenAudio/CosyVoice)    | Build multilingual speech synthesis workflows with reference-audio conditioning. | QwenAudio        | 24.4k        |
| **chatterbox**  | [Visit](https://github.com/resemble-ai/chatterbox) | Generate narration with controls for expressive delivery.                        | resemble-ai      | 27.9k        |
| **bark**        | [Visit](https://github.com/suno-ai/bark)           | Generate speech and other sounds from text prompts.                              | suno-ai          | 39.4k        |
| **piper1-gpl**  | [Visit](https://github.com/OHF-Voice/piper1-gpl)   | Run local text-to-speech voices for offline applications.                        | OHF-Voice        | 6.3k         |
| **fish-speech** | [Visit](https://github.com/fishaudio/fish-speech)  | Train or run neural speech synthesis models for expressive audio.                | fishaudio        | 33.8k        |

## Audio, Music, and Transcription

| Name               | Link                                                    | Description                                                                    | Repository Owner | GitHub Stars |
| ------------------ | ------------------------------------------------------- | ------------------------------------------------------------------------------ | ---------------- | ------------ |
| **audiocraft**     | [Visit](https://github.com/facebookresearch/audiocraft) | Generate music or sound effects from written descriptions.                     | facebookresearch | 23.9k        |
| **demucs**         | [Visit](https://github.com/facebookresearch/demucs)     | Separate a mixed recording into vocals, drums, bass, and other stems.          | facebookresearch | 10.4k        |
| **faster-whisper** | [Visit](https://github.com/SYSTRAN/faster-whisper)      | Transcribe recordings with a CTranslate2 implementation of Whisper.            | SYSTRAN          | 26.8k        |
| **whisper.cpp**    | [Visit](https://github.com/ggml-org/whisper.cpp)        | Run Whisper transcription locally through a C and C++ implementation.          | ggml-org         | 55.3k        |
| **whisperX**       | [Visit](https://github.com/m-bain/whisperX)             | Align transcripts to words and add speaker labels to long recordings.          | m-bain           | 25.4k        |
| **librosa**        | [Visit](https://github.com/librosa/librosa)             | Extract tempo, spectral features, and other measurements from audio in Python. | librosa          | 9.0k         |
| **audacity**       | [Visit](https://github.com/audacity/audacity)           | Record and edit waveforms for narration, music, and podcasts.                  | audacity         | 19.1k        |
| **basic-pitch**    | [Visit](https://github.com/spotify/basic-pitch)         | Convert recorded musical notes into MIDI for further editing.                  | spotify          | 6.1k         |
| **pyannote-audio** | [Visit](https://github.com/pyannote/pyannote-audio)     | Identify who spoke when in a multi-speaker recording.                          | pyannote         | 10.8k        |
| **GPT-SoVITS**     | [Visit](https://github.com/RVC-Boss/GPT-SoVITS)         | Synthesize speech in a reference voice from short audio samples.               | RVC-Boss         | 65.2k        |

## Defensive Security and Secret Detection

| Name                | Link                                                         | Description                                                                        | Repository Owner | GitHub Stars |
| ------------------- | ------------------------------------------------------------ | ---------------------------------------------------------------------------------- | ---------------- | ------------ |
| **trivy**           | [Visit](https://github.com/aquasecurity/trivy)               | Scan container images, dependencies, and infrastructure configuration for issues.  | aquasecurity     | 39.4k        |
| **grype**           | [Visit](https://github.com/anchore/grype)                    | Check packages and container images for known vulnerabilities.                     | anchore          | 13.3k        |
| **syft**            | [Visit](https://github.com/anchore/syft)                     | Generate a software bill of materials from a filesystem or container image.        | anchore          | 9.9k         |
| **gitleaks**        | [Visit](https://github.com/gitleaks/gitleaks)                | Detect accidentally committed passwords, tokens, and other secrets in Git history. | gitleaks         | 31.1k        |
| **trufflehog**      | [Visit](https://github.com/trufflesecurity/trufflehog)       | Find exposed credentials in source repositories and other supported inputs.        | trufflesecurity  | 29.4k        |
| **scorecard**       | [Visit](https://github.com/ossf/scorecard)                   | Assess open-source projects against automated supply-chain security checks.        | ossf             | 5.8k         |
| **osv-scanner**     | [Visit](https://github.com/google/osv-scanner)               | Match project dependencies against known issues in the OSV database.               | google           | 11.5k        |
| **DependencyCheck** | [Visit](https://github.com/dependency-check/DependencyCheck) | Check application dependencies against publicly disclosed vulnerabilities.         | dependency-check | 7.8k         |
| **cosign**          | [Visit](https://github.com/sigstore/cosign)                  | Sign container images and verify their signatures before deployment.               | sigstore         | 6.4k         |
| **bandit**          | [Visit](https://github.com/PyCQA/bandit)                     | Find common security issues in Python source code through static analysis.         | PyCQA            | 8.4k         |

## Documents, OCR, and Data Extraction

| Name             | Link                                                     | Description                                                                | Repository Owner | GitHub Stars |
| ---------------- | -------------------------------------------------------- | -------------------------------------------------------------------------- | ---------------- | ------------ |
| **docling**      | [Visit](https://github.com/docling-project/docling)      | Convert PDFs and office files into structured documents for AI pipelines.  | docling-project  | 70.7k        |
| **PaddleOCR**    | [Visit](https://github.com/PaddlePaddle/PaddleOCR)       | Recognize text and extract document structure from scanned pages.          | PaddlePaddle     | 92.8k        |
| **EasyOCR**      | [Visit](https://github.com/JaidedAI/EasyOCR)             | Read text from images with a Python OCR toolkit.                           | JaidedAI         | 30.1k        |
| **tesseract**    | [Visit](https://github.com/tesseract-ocr/tesseract)      | Extract printed text from scans using a local OCR engine.                  | tesseract-ocr    | 77.6k        |
| **markitdown**   | [Visit](https://github.com/microsoft/markitdown)         | Convert common document formats into Markdown for indexing and analysis.   | microsoft        | 195.8k       |
| **marker**       | [Visit](https://github.com/datalab-to/marker)            | Convert PDFs to Markdown while retaining layout elements such as tables.   | datalab-to       | 40.9k        |
| **MinerU**       | [Visit](https://github.com/opendatalab/MinerU)           | Extract document text, tables, and formulas into machine-readable formats. | opendatalab      | 83.8k        |
| **unstructured** | [Visit](https://github.com/Unstructured-IO/unstructured) | Split documents into typed elements for downstream search and retrieval.   | Unstructured-IO  | 15.8k        |
| **pdfplumber**   | [Visit](https://github.com/jsvine/pdfplumber)            | Inspect PDF text positions and extract tables with Python.                 | jsvine           | 10.9k        |
| **OCRmyPDF**     | [Visit](https://github.com/ocrmypdf/OCRmyPDF)            | Add a searchable OCR text layer to scanned PDF files.                      | ocrmypdf         | 35.3k        |

## AI Applications, Search, and Model Serving

| Name         | Link                                             | Description                                                                      | Repository Owner | GitHub Stars |
| ------------ | ------------------------------------------------ | -------------------------------------------------------------------------------- | ---------------- | ------------ |
| **dify**     | [Visit](https://github.com/langgenius/dify)      | Build AI applications with visual workflows, model connections, and retrieval.   | langgenius       | 161.3k       |
| **Flowise**  | [Visit](https://github.com/FlowiseAI/Flowise)    | Connect model calls, tools, and retrieval steps on a visual canvas.              | FlowiseAI        | 55.6k        |
| **langflow** | [Visit](https://github.com/langflow-ai/langflow) | Prototype AI applications as graphs of configurable components.                  | langflow-ai      | 156.7k       |
| **qdrant**   | [Visit](https://github.com/qdrant/qdrant)        | Store embeddings and retrieve similar items using vector search and filters.     | qdrant           | 35.6k        |
| **chroma**   | [Visit](https://github.com/chroma-core/chroma)   | Index embeddings and metadata for semantic search in an application.             | chroma-core      | 29.7k        |
| **milvus**   | [Visit](https://github.com/milvus-io/milvus)     | Serve similarity searches over large collections of vectors.                     | milvus-io        | 46.7k        |
| **vllm**     | [Visit](https://github.com/vllm-project/vllm)    | Serve language models with batched inference for concurrent requests.            | vllm-project     | 97.1k        |
| **sglang**   | [Visit](https://github.com/sgl-project/sglang)   | Run language and multimodal model inference with optimized serving components.   | sgl-project      | 39.0k        |
| **BentoML**  | [Visit](https://github.com/bentoml/BentoML)      | Package model inference code as deployable API services.                         | bentoml          | 8.9k         |
| **haystack** | [Visit](https://github.com/deepset-ai/haystack)  | Build question-answering pipelines from retrievers, models, and document stores. | deepset-ai       | 27.0k        |
