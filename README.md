## Run LLM models in  colab using TextGen-webui  :  

This repository contains a Colab notebook  that allows you to run Large Language Models (LLM) models with just one click.

in colab gpu (15Gvram) you can use :
- `13b model gguf quantized upto Q5_K_M(context up to 4K)`
- `7b model gguf quantized upto Q8_0(context up to 16K)`
- `<13b model GPTQ quantized` 
- `7b model GPTQ quantized` 
- you can use full precision `13b` , `7b` modeles but using flags like `--load-in-4bit` or `--load-in-8bit`  its slower then quantized versions but works well,so if u have quantized verions it will be better

## Available notebooks :
-Run gguf LLM models in TextGen-webui :  <a target="_blank" href="https://colab.research.google.com/github/seyf1elislam/LocalLLM_OneClick_Colab/blob/main/Run_gguf_LLM_models_in_TextGen_webui.ipynb"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a>

-Run GPTQ and fullprecision LLM models in TextGen-webui : <a target="_blank" href="https://colab.research.google.com/github/seyf1elislam/LocalLLM_OneClick_Colab/blob/main/Run_GPTQ_and_fullprecision_LLM_models_in_TextGen_webui.ipynb"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a>


## Getting Started

To get started with the LLM Model Runner, follow these steps:

1. Open the Colab notebook in Google Colab by clicking on the "Open in Colab" button at the top of the notebook.
<a target="_blank" href="https://colab.research.google.com/github/seyf1elislam/LocalLLM_OneClick_Colab/blob/main/Run_gguf_LLM_models_in_TextGen_webui.ipynb"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a>

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
