## Run LLM models in colab using TextGen-webui and KoboldCpp :  

This repository contains a Colab notebook  that allows you to run Large Language Models (LLM) models with just one click.
## Changes : 
- Add new models and fixes (for textGen notebook)
- Add new notebook for  koboldcpp <a target="_blank" href="https://colab.research.google.com/github/seyf1elislam/LocalLLM_OneClick_Colab/blob/main/awesome_koboldcpp_notebook.ipynb"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a>
- Openai gpt-oss-20b support:
  - They both use llama.cpp, and it has supported it since merge  [15091](https://github.com/ggml-org/llama.cpp/pull/15091) yesterday
  - TextGenwebui support it at v3.9
  - Koboldcpp will suport it  soon  

## Available notebooks :
-Run gguf LLM models in KoboldCpp (recommended⭐⭐⭐,faster):  <a target="_blank" href="https://colab.research.google.com/github/seyf1elislam/LocalLLM_OneClick_Colab/blob/main/awesome_koboldcpp_notebook.ipynb"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a>


-Run gguf LLM models in TextGen-webui(recommended⭐⭐) :  <a target="_blank" href="https://colab.research.google.com/github/seyf1elislam/LocalLLM_OneClick_Colab/blob/main/Run_any_gguf_model_in_TextGen_webui.ipynb"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a>



-Run GPTQ and Exl2 LLM models in TextGen-webui (not recommended) : <a target="_blank" href="https://colab.research.google.com/github/seyf1elislam/LocalLLM_OneClick_Colab/blob/main/Run_any_GPTQ_quantized_models_in_TextGen_webui.ipynb"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a>



## Quantized models Sources :
check those 🤗 huggingface repos :
- [mradermacher](https://huggingface.co/mradermacher) (GGUF).
- [bartowski](https://huggingface.co/bartowski) (GGUF)
- [LongStriker](https://huggingface.co/LoneStriker)  (exl2,gguf)
- [QuantFactory](https://huggingface.co/QuantFactory) (GGUF)  
- [using search gguf](https://huggingface.co/models?sort=trending&search=gguf)  here u can find all gguf files on  huggingface.

## Good models to try :
 you can try these :  
- [unsloth/gemma-3-12b-it-GGUF](https://huggingface.co/unsloth/gemma-3-12b-it-GGUF) 12B model Q5_K_M / Q4_K_M (⭐🔥) .
- [unsloth/Qwen3-8B-GGUF](https://huggingface.co/unsloth/Qwen3-8B-GGUF) 8B model Q8_0 / Q6_k (⭐🔥) .
- [unsloth/gpt-oss-20b-GGUF](https://huggingface.co/unsloth/gpt-oss-20b-GGUF) 20B model Q4_K_M (⭐🔥) .
- [unsloth/Qwen3-14B-GGUF](https://huggingface.co/unsloth/Qwen3-14B-GGUF) 14B model Q5_K_M / Q4_K_M (⭐🔥) .
- [unsloth/Qwen3-4B-Instruct-2507-GGUF](https://huggingface.co/unsloth/Qwen3-4B-Instruct-2507-GGUF) 4B model Q8_0 / Q6_k (⭐🔥) .
  
old but gold  : 
- [QuantFactory/Mistral-Nemo-Instruct-2407-GGUF](https://huggingface.co/QuantFactory/Mistral-Nemo-Instruct-2407-GGUF) 12B model Q5_K_M / Q4_K_M (⭐🔥) .
- [bartowski/Mistral-Small-Instruct-2409-GGUF](https://huggingface.co/bartowski/Mistral-Small-Instruct-2409-GGUF) this is 22B u can use it 3KM in 15g vram (⭐🔥) .
- [Meta-Llama-3.1-8B-Instruct-GGUF](https://huggingface.co/bartowski/Meta-Llama-3.1-8B-Instruct-GGUF) Q8_0 (⭐🔥) .
- [Meta-Llama-3-8B-Instruct-GGUF](https://huggingface.co/QuantFactory/Meta-Llama-3-8B-Instruct-GGUF)  Q8_0  (⭐🔥) .
- [gemma-2-9b-it-GGUF](https://huggingface.co/bartowski/gemma-2-9b-it-GGUF)  Q8_0/Q6   (⭐🔥) .

## Some Tips 

in free colab gpu T4  (15G vram) you can use :
 - 22b model quantized upto Q3_K_M(`context up to 8K`)
 - 12b model quantized upto Q5_K_M(`context up to 16K`)
 - 8b/7b model quantized upto Q8_0(`context up to 16k if the model support it`)
- 7b/8b model exl2 quantized  6bpw (`context up to 16k if the model support it`)
- 12b model exl2 quantized 4bpw  
> most older models goes with 8k context length if u want to use longer context u need to make sure the models support longer context.

> if you want to run model higher then 20B (such as 20B,4x7b..) on colab you may need to reduce the offloaded gpu models to split the ram usage between gpu vram and system ram. (slower but it works 😉)

> if you dont have quantized version , you can use full precision  `7b` modeles with gptq notebook but make sure to  use flags  `--load-in-4bit` or `--load-in-8bit`  its slower then quantized versions but works well,so if u have quantized verions it will be better.

> in case of exl2 you can use `--cache_4bit` to save up some vram.
> if you want a creative answers  increase the temp(0.9 ~ 1.25) and decrease the minp(0.05\~0.1) 
> if you want a strict and accurate  answers decrease the temp(0.3~0.5) and increase the min p (0.15\~0.25) 


## Getting Started

To get started with the LLM Model Runner, follow these steps:

1. Open the Colab notebook in Google Colab by clicking on the "Open in Colab" button at the top of the notebook.
<a target="_blank" href="https://colab.research.google.com/github/seyf1elislam/LocalLLM_OneClick_Colab/blob/main/Run_any_gguf_model_in_TextGen_webui.ipynb"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a>

2. Choose The  model that you want from the list .

![image](https://github.com/seyf1elislam/LocalLLM_OneClick_Colab/assets/40665383/7b1186a3-55dc-46c3-9d71-c7886537b88e)

3.Choose quantization type:

![image](https://github.com/seyf1elislam/LocalLLM_OneClick_Colab/assets/40665383/bf912e18-5300-4880-b430-21b0e62d9c85)


4. Run the Cell and Visit the Generated link( `https://***.gradio.live` ) and start your Conversation with your favorite model !

## Requirements
- no Requirement just open Colab in Gpu mode

All the necessary dependencies will be automatically installed when you run the Colab notebook.

## Thanks ❤️ 
- [llamacpp](https://github.com/ggml-org/llama.cpp)  — the backbone of the open-source LLM community.
- [text-generation-webui](https://github.com/oobabooga/text-generation-webui) and [KoboldCpp](https://github.com/LostRuins/koboldcpp) for their nice UIs .
