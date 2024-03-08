## Run LLM models in  colab using TextGen-webui  :  

This repository contains a Colab notebook  that allows you to run Large Language Models (LLM) models with just one click.

in colab gpu T4 (15Gvram) you can use :
- `13b model gguf quantized upto Q5_K_M(context up to 4K)`[Q5_K_M u can get about 10token/s]
- `11b model gguf quantized upto Q5_K_M(context up to 8K)`[Q5_K_M => 16~18 token/s] [Q8_0 => 11 token/s] 
- `7b model gguf quantized upto Q8_0(context up to 16K if the model support it) `[Q8_0 u can get upto 18~19token/s] 
- `13b model GPTQ quantized`
- `11b model GPTQ quantized`
- `7b model GPTQ quantized` [upto 17token/S]
- `7b model exllama2 quantized (context up to 16k if the model support it)` [with version 8bt u can get upto 23token/S]


## some Tips ?
> most mistral based models goes with 8k context length if u want to use longer context u need to make sure the models support longer context.

> if u want to run model higher then 13B (such as 20B,4x7b..) on colab u may need to reduce the offloaded gpu models to split the ram usage between gpu vram and system ram. (slower but it works 😉)

> if u dont have quantized version , you can use full precision  `7b` modeles with gptq notebook but make sure to  use flags  `--load-in-4bit` or `--load-in-8bit`  its slower then quantized versions but works well,so if u have quantized verions it will be better.

> if u want a creative answers from ur model then increase the temp(0.9\~1.25) and decrease the minp(0.05\~0.1) ,
> but when u need strict and accurate  answers decrease the temp(0.5\~0.7) and increase the min p (0.1\~0.2) 

## Available notebooks :
-Run gguf LLM models in TextGen-webui :  <a target="_blank" href="https://colab.research.google.com/github/seyf1elislam/LocalLLM_OneClick_Colab/blob/main/Run_any_gguf_model_in_TextGen_webui_v_01_03_2024.ipynb"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a>

-Run GPTQ and Exl2 LLM models in TextGen-webui : <a target="_blank" href="https://colab.research.google.com/github/seyf1elislam/LocalLLM_OneClick_Colab/blob/main/Run_any_GPTQ_quantized_models_in_TextGen_webui_01-03-2024.ipynb"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a>


## Getting Started

To get started with the LLM Model Runner, follow these steps:

1. Open the Colab notebook in Google Colab by clicking on the "Open in Colab" button at the top of the notebook.
<a target="_blank" href="https://colab.research.google.com/github/seyf1elislam/LocalLLM_OneClick_Colab/blob/main/Run_any_gguf_model_in_TextGen_webui_v_01_03_2024.ipynb"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a>

2. Choose The  model that you want from the list .

![image](https://github.com/seyf1elislam/LocalLLM_OneClick_Colab/assets/40665383/7b1186a3-55dc-46c3-9d71-c7886537b88e)

3.Choose quantization type:

![image](https://github.com/seyf1elislam/LocalLLM_OneClick_Colab/assets/40665383/bf912e18-5300-4880-b430-21b0e62d9c85)


4. Run the Cell and Visit the Generated link( `https://***.gradio.live` ) and start your Conversation with your favorite model !

## Requirements
- no Requirement just open Colab in Gpu mode

All the necessary dependencies will be automatically installed when you run the Colab notebook.


## License

All  Models license belongs to thier owners please follow the link of the Model repo and read its license if u need.

## Thanks <3 
- [TheBloke](https://huggingface.co/TheBloke) for their Quantized LLM models.
- [text-generation-webui](https://github.com/oobabooga/text-generation-webui) for their Great Ui 
