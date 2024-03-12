<!-- Banner Image -->
<img src="https://uohmivykqgnnbiouffke.supabase.co/storage/v1/object/public/landingpage/brevdevnotebooks.png" width="100%">

<!-- Links -->
<p align="center">
  <a href="https://console.brev.dev" style="color: #06b6d4;">Console</a> •
  <a href="https://brev.dev" style="color: #06b6d4;">Docs</a> •
  <a href="/" style="color: #06b6d4;">Templates</a> •
  <a href="https://discord.gg/NVDyv7TUgJ" style="color: #06b6d4;">Discord</a>
</p>

# Brev.dev Notebooks

This repo contains helpful AI/ML notebook templates. Each notebook has been coupled with the minimum GPU specs required to use them + setup scripts making a Brev template. Click the deploy badge on any notebook to deploy it.

## Notebooks

<!-- make a table  -->

| Notebook                                                                                                         | Description                                       | Min. GPU     | Deploy                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |
| ---------------------------------------------------------------------------------------------------------------- | ------------------------------------------------- | ------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
[AUTOMATIC1111 Stable Diffusion WebUI](https://github.com/brevdev/notebooks/blob/main/stable-diffusion-ui.ipynb) | Run Stable Diffusion WebUI, AUTOMATIC1111 | 1x A10G | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/brevdev/notebooks/blob/main/stable-diffusion-ui.ipynb) [![ Click here to deploy.](https://uohmivykqgnnbiouffke.supabase.co/storage/v1/object/public/landingpage/brevdeploynavy.svg)](https://console.brev.dev/environment/new?instance=A10G:g5.xlarge&name=gguf-export&file=https://github.com/brevdev/notebooks/raw/main/stable-diffusion-ui.ipynb&python=3.10&cuda=12.0.1) [![](https://uohmivykqgnnbiouffke.supabase.co/storage/v1/object/public/landingpage/youtubebadge.svg)](https://www.youtube.com/watch?v=Sf6PwCz6fbI) |
| [ControlNet on AUTOMATIC1111](https://github.com/brevdev/notebooks/blob/main/controlnet.ipynb) | Run ControlNet Models on Stable Diffusion WebUI | 1x A10G | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/brevdev/notebooks/blob/main/controlnet.ipynb) [![ Click here to deploy.](https://uohmivykqgnnbiouffke.supabase.co/storage/v1/object/public/landingpage/brevdeploynavy.svg)](https://console.brev.dev/environment/new?instance=A10G:g5.xlarge&name=gguf-export&file=https://github.com/brevdev/notebooks/raw/main/controlnet.ipynb&python=3.10&cuda=12.0.1) |
| [Finetune BioMistral](https://github.com/brevdev/notebooks/blob/main/biomistral-finetune.ipynb) | Finetune the BioMistral model on medical data | 1x A10G | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/brevdev/notebooks/blob/main/biomistral-finetune.ipynb) [![ Click here to deploy.](https://uohmivykqgnnbiouffke.supabase.co/storage/v1/object/public/landingpage/brevdeploynavy.svg)](https://console.brev.dev/environment/new?instance=A10G:g5.xlarge&name=gguf-export&file=https://github.com/brevdev/notebooks/raw/main/biomistral-finetune.ipynb&python=3.10&cuda=12.0.1) |
| [Deploy to Replicate](https://github.com/brevdev/notebooks/blob/main/deploy-to-replicate.ipynb) | Deploy Model to Replicate | any \|\| CPU | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/brevdev/notebooks/blob/main/deploy-to-replicate.ipynb) [![ Click here to deploy.](https://uohmivykqgnnbiouffke.supabase.co/storage/v1/object/public/landingpage/brevdeploynavy.svg)](https://console.brev.dev/environment/new?instance=n1-standard-1&panel=CPU&name=deploy&file=https://github.com/brevdev/notebooks/raw/main/deploy-to-replicate.ipynb&python=3.10&cuda=12.0.1) [![](https://uohmivykqgnnbiouffke.supabase.co/storage/v1/object/public/landingpage/youtubebadge.svg)](https://www.youtube.com/watch?v=eczHFcqx1ic) |
| [Run BioMistral](https://github.com/brevdev/notebooks/blob/main/biomistral.ipynb) | Run BioMistral | 1x A10G | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/brevdev/notebooks/blob/main/biomistral.ipynb) [![ Click here to deploy.](https://uohmivykqgnnbiouffke.supabase.co/storage/v1/object/public/landingpage/brevdeploynavy.svg)](https://console.brev.dev/environment/new?instance=A10G:g5.xlarge&name=biomistral&file=https://github.com/brevdev/notebooks/raw/main/biomistral.ipynb&python=3.10&cuda=12.0.1) |
| [Run Llama 2 70B](https://github.com/brevdev/notebooks/blob/main/llama2-finetune-own-data.ipynb) | Run Llama 2 70B, or any Llama 2 Model | 4x T4 | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/brevdev/notebooks/blob/main/llama2.ipynb) [![ Click here to deploy.](https://uohmivykqgnnbiouffke.supabase.co/storage/v1/object/public/landingpage/brevdeploynavy.svg)](https://console.brev.dev/environment/new?instance=T4:g4dn.12xlarge&diskStorage=512&name=llama2&file=https://github.com/brevdev/notebooks/raw/main/llama2.ipynb&python=3.10&cuda=12.0.1) |
| [Fine-tune BioMistral](https://github.com/brevdev/notebooks/blob/main/biomistral-finetune.ipynb) | A Guide to Fine-tuning BioMistral | 1x A10G | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/brevdev/notebooks/blob/main/biomistral-finetune.ipynb) [![ Click here to deploy.](https://uohmivykqgnnbiouffke.supabase.co/storage/v1/object/public/landingpage/brevdeploynavy.svg)](https://console.brev.dev/environment/new?instance=A10G:g5.xlarge&name=biomistral-finetune&file=https://github.com/brevdev/notebooks/raw/main/biomistral-finetune.ipynb&python=3.10&cuda=12.0.1) |
| [Fine-tune Llama 2](https://github.com/brevdev/notebooks/blob/main/llama2-finetune.ipynb) | A Guide to Fine-tuning Llama 2 | 1x A10G | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/brevdev/notebooks/blob/main/llama2-finetune.ipynb) [![ Click here to deploy.](https://uohmivykqgnnbiouffke.supabase.co/storage/v1/object/public/landingpage/brevdeploynavy.svg)](https://console.brev.dev/environment/new?instance=A10G:g5.xlarge&name=llama2-finetune&file=https://github.com/brevdev/notebooks/raw/main/llama2-finetune.ipynb&python=3.10&cuda=12.0.1) [![](https://uohmivykqgnnbiouffke.supabase.co/storage/v1/object/public/landingpage/youtubebadge.svg)](https://www.youtube.com/watch?v=lPLrODJjHUE) |
| [Fine-tune Llama 2 - Own Data](https://github.com/brevdev/notebooks/blob/main/llama2-finetune-own-data.ipynb) | Fine-tune Llama 2 on your own dataset | 1x A10G | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/brevdev/notebooks/blob/main/llama2-finetune-own-data.ipynb) [![ Click here to deploy.](https://uohmivykqgnnbiouffke.supabase.co/storage/v1/object/public/landingpage/brevdeploynavy.svg)](https://console.brev.dev/environment/new?instance=A10G:g5.xlarge&name=llama2-finetune-own-data&file=https://github.com/brevdev/notebooks/raw/main/llama2-finetune-own-data.ipynb&python=3.10&cuda=12.0.1) [![](https://uohmivykqgnnbiouffke.supabase.co/storage/v1/object/public/landingpage/youtubebadge.svg)](https://www.youtube.com/watch?v=lPLrODJjHUE) |
| [Fine-tune Mistral](https://github.com/brevdev/notebooks/blob/main/mistral-finetune.ipynb) | A Guide to Fine-tuning Mistral | 1x A10G | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/brevdev/notebooks/blob/main/mistral-finetune.ipynb) [![ Click here to deploy.](https://uohmivykqgnnbiouffke.supabase.co/storage/v1/object/public/landingpage/brevdeploynavy.svg)](https://console.brev.dev/environment/new?instance=A10G:g5.xlarge&name=mistral-finetune&file=https://github.com/brevdev/notebooks/raw/main/mistral-finetune.ipynb&python=3.10&cuda=12.0.1) |
| [Fine-tune Mistral using NVIDIA NeMO and PEFT](https://github.com/brevdev/notebooks/blob/main/mistral-finetune-nemo.ipynb) | Fine-tune Mistral using NVIDIA NeMO and PEFT | 1x A100 | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/brevdev/notebooks/blob/main/mistral-finetune-nemo.ipynb) [![ Click here to deploy.](https://uohmivykqgnnbiouffke.supabase.co/storage/v1/object/public/landingpage/brevdeploynavy.svg)](https://console.brev.dev/environment/new?instance=A100@a2-highgpu-1g:nvidia-tesla-a100:1&name=mistral-finetune-nemo&file=https://github.com/brevdev/notebooks/raw/main/mistral-finetune-own-data.ipynb&python=3.10&cuda=12.0.1) [![](https://uohmivykqgnnbiouffke.supabase.co/storage/v1/object/public/landingpage/youtubebadge.svg)](https://www.youtube.com/watch?v=kmkcNVvEz-k) |
| [Fine-tune Mistral - Own Data](https://github.com/brevdev/notebooks/blob/main/mistral-finetune-own-data.ipynb) | Fine-tune Mistral on your own dataset | 1x A10G | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/brevdev/notebooks/blob/main/mistral-finetune-own-data.ipynb) [![ Click here to deploy.](https://uohmivykqgnnbiouffke.supabase.co/storage/v1/object/public/landingpage/brevdeploynavy.svg)](https://console.brev.dev/environment/new?instance=A10G:g5.xlarge&name=mistral-finetune-own-data&file=https://github.com/brevdev/notebooks/raw/main/mistral-finetune-own-data.ipynb&python=3.10&cuda=12.0.1) [![](https://uohmivykqgnnbiouffke.supabase.co/storage/v1/object/public/landingpage/youtubebadge.svg)](https://www.youtube.com/watch?v=kmkcNVvEz-k) |
| [Fine-tune Mixtral (8x7B MoE)](https://github.com/brevdev/notebooks/blob/main/mixtral-finetune.ipynb) | A Guide to Fine-tuning Mixtral, Mistral's 8x7B MoE | 4x T4 | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/brevdev/notebooks/blob/main/mixtral-finetune.ipynb) [![ Click here to deploy.](https://uohmivykqgnnbiouffke.supabase.co/storage/v1/object/public/landingpage/brevdeploynavy.svg)](https://console.brev.dev/environment/new?instance=T4:g4dn.12xlarge&diskStorage=512&name=mistral-finetune&file=https://github.com/brevdev/notebooks/raw/main/mixtral-finetune.ipynb&python=3.10&cuda=12.0.1) [![](https://uohmivykqgnnbiouffke.supabase.co/storage/v1/object/public/landingpage/youtubebadge.svg)](https://www.youtube.com/watch?v=zbKz4g100SQ) | |
| [Fine-tune Mixtral (8x7B MoE) - Own Data](https://github.com/brevdev/notebooks/blob/main/mistral-finetune-own-data.ipynb) | A Guide to Fine-tuning Mixtral on your own dataset | 4x T4 | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/brevdev/notebooks/blob/main/mistral-finetune-own-data.ipynb) [![ Click here to deploy.](https://uohmivykqgnnbiouffke.supabase.co/storage/v1/object/public/landingpage/brevdeploynavy.svg)](https://console.brev.dev/environment/new?instance=T4:g4dn.12xlarge&diskStorage=512&name=mixtral-finetune-own-data&file=https://github.com/brevdev/notebooks/raw/main/mixtral-finetune-own-data.ipynb&python=3.10&cuda=12.0.1) |
| [Fine-tune Phi-2](https://github.com/brevdev/notebooks/blob/main/phi2-finetune.ipynb) | A Guide to Fine-tuning Phi-2 | 1x A10G | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/brevdev/notebooks/blob/main/phi2-finetune.ipynb) [![ Click here to deploy.](https://uohmivykqgnnbiouffke.supabase.co/storage/v1/object/public/landingpage/brevdeploynavy.svg)](https://console.brev.dev/environment/new?instance=A10G:g5.xlarge&name=phi2-finetune&file=https://github.com/brevdev/notebooks/raw/main/phi2-finetune.ipynb&python=3.10&cuda=12.0.1) [![](https://uohmivykqgnnbiouffke.supabase.co/storage/v1/object/public/landingpage/youtubebadge.svg)](https://www.youtube.com/watch?v=t55XrJddjLA) |
| [Fine-tune Phi-2 - Own Data](https://github.com/brevdev/notebooks/blob/main/phi2-finetune-own-data.ipynb) | Fine-tune Phi-2 on your own dataset | 1x A10G | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/brevdev/notebooks/blob/main/phi2-finetune-own-data.ipynb) [![ Click here to deploy.](https://uohmivykqgnnbiouffke.supabase.co/storage/v1/object/public/landingpage/brevdeploynavy.svg)](https://console.brev.dev/environment/new?instance=A10G:g5.xlarge&name=phi2-finetune-own-data&file=https://github.com/brevdev/notebooks/raw/main/phi2-finetune-own-data.ipynb&python=3.10&cuda=12.0.1) [![](https://uohmivykqgnnbiouffke.supabase.co/storage/v1/object/public/landingpage/youtubebadge.svg)](https://www.youtube.com/watch?v=t55XrJddjLA) |
| [GGUF Export FT Model](https://github.com/brevdev/notebooks/blob/main/gguf-export.ipynb) | Export your fine-tuned model to GGUF | 1x A10G | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/brevdev/notebooks/blob/main/gguf-export.ipynb) [![ Click here to deploy.](https://uohmivykqgnnbiouffke.supabase.co/storage/v1/object/public/landingpage/brevdeploynavy.svg)](https://console.brev.dev/environment/new?instance=A10G:g5.xlarge&name=gguf-export&file=https://github.com/brevdev/notebooks/raw/main/gguf-export.ipynb&python=3.10&cuda=12.0.1) |
| [Training Question/Answer models using NVIDIA NeMo ](https://github.com/brevdev/notebooks/blob/main/gguf-export.ipynb) | Use NeMo to train BERT, GPT, and S2S models for Q&A tasks | 1x A10G | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/brevdev/notebooks/blob/main/question_answer_nemo.ipynb) [![ Click here to deploy.](https://uohmivykqgnnbiouffke.supabase.co/storage/v1/object/public/landingpage/brevdeploynavy.svg)](https://console.brev.dev/environment/new?instance=A10G:g5.xlarge&name=gguf-export&file=https://github.com/brevdev/notebooks/raw/main/question_answer_nemo.ipynb&python=3.10&cuda=12.0.1) |
| [Julia Install](https://github.com/brevdev/notebooks/blob/main/julia-install.ipynb) | Easily Install Julia + Notebooks | any \|\| CPU | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/brevdev/notebooks/blob/main/julia-install.ipynb) [![ Click here to deploy.](https://uohmivykqgnnbiouffke.supabase.co/storage/v1/object/public/landingpage/brevdeploynavy.svg)](https://console.brev.dev/environment/new?instance=n1-standard-1&panel=CPU&name=julia&file=https://github.com/brevdev/notebooks/raw/main/julia-install.ipynb&python=3.10&cuda=12.0.1) |
| [Oobabooga LLM WebUI](https://github.com/brevdev/notebooks/blob/main/oobabooga.ipynb) | Run Oobabooga, the LLM WebUI (like AUTOMATIC1111) | 1x A10G | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/brevdev/notebooks/blob/main/oobabooga.ipynb) [![ Click here to deploy.](https://uohmivykqgnnbiouffke.supabase.co/storage/v1/object/public/landingpage/brevdeploynavy.svg)](https://console.brev.dev/environment/new?instance=A10G:g5.xlarge&name=gguf-export&file=https://github.com/brevdev/notebooks/raw/main/oobabooga.ipynb&python=3.10&cuda=12.0.1) |
| [PDF Chatbot (OCR)](https://github.com/brevdev/notebooks/blob/main/ocr-pdf-analysis.ipynb) | PDF Chatbot using OCR | 1x A10G | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/brevdev/notebooks/blob/main/ocr-pdf-analysis.ipynb) [![ Click here to deploy.](https://uohmivykqgnnbiouffke.supabase.co/storage/v1/object/public/landingpage/brevdeploynavy.svg)](https://console.brev.dev/environment/new?instance=A10G:g5.xlarge&name=pdf-analysis&file=https://github.com/brevdev/notebooks/raw/main/ocr-pdf-analysis.ipynb&python=3.10&cuda=12.0.1) |
| [Use TensorRT-LLM with Mistral](https://github.com/brevdev/notebooks/blob/main/tensorrt_mistral.ipynb) | Use NVIDIA TensorRT engine to run inference on Mistral-7B | 1x A10G | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/brevdev/notebooks/blob/main/tensorrt_mistral.ipynb) [![ Click here to deploy.](https://uohmivykqgnnbiouffke.supabase.co/storage/v1/object/public/landingpage/brevdeploynavy.svg)](https://console.brev.dev/environment/new?instance=A10G:g5.xlarge&diskStorage=256&file=https://github.com/brevdev/notebooks/raw/main/tensorrt_mistral.ipynb&python=3.10&cuda=12.0.1) |
| [Zephyr Chatbot](https://github.com/brevdev/notebooks/blob/main/zephyr-chatbot.ipynb) | Chatbot with Open Source Models | 1x A10G | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/brevdev/notebooks/blob/main/zephyr-chatbot.ipynb) [![ Click here to deploy.](https://uohmivykqgnnbiouffke.supabase.co/storage/v1/object/public/landingpage/brevdeploynavy.svg)](https://console.brev.dev/environment/new?instance=A10G:g5.2xlarge&diskStorage=256&file=https://github.com/brevdev/notebooks/raw/main/zephyr-chatbot.ipynb&python=3.10&cuda=12.0.1) |
| [StreamingLLM for Optimized Inference](https://github.com/brevdev/notebooks/blob/main/streamingllm-tensorrt.ipynb) | Use StreamingLLM for infinite length input without finetuning | 1x A10G | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/brevdev/notebooks/blob/main/streamingllm-tensorrt.ipynb) [![ Click here to deploy.](https://uohmivykqgnnbiouffke.supabase.co/storage/v1/object/public/landingpage/brevdeploynavy.svg)](https://console.brev.dev/environment/new?instance=A10G:g5.2xlarge&diskStorage=256&file=https://github.com/brevdev/notebooks/raw/main/streamingllm-tensorrt.ipynb&python=3.10&cuda=12.0.1) |

---

### What is Brev.dev?

Brev is a dev tool that makes it really easy to code on a GPU in the cloud. Brev does 3 things: provision, configure, and connect.

#### Provision:

Brev provisions a GPU for you. You don't have to worry about setting up a cloud account. We have solid GPU supply, but if you do have AWS or GCP, you can link them.

#### Configure:

Brev configures your GPU with the right drivers and libraries. Use our open source tool Verb to point and click the right python and CUDA versions.

#### Connect:

Brev.dev CLI automatically edits your ssh config so you can `ssh gpu-name` or run `brev open gpu-name` to open VS Code to the remote machine
