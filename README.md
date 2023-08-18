## UltimateOneClickColab 13B_LLM:  

This repository contains a Colab notebook  that allows you to run Language Model (LLM) models with just one click. The notebook provides hundreds of pre-trained LLM models with a friendly interface.

For now, I added 127 models Gmml 13b , but I'll  add more soon.
All the most famous models exist, such as:
- TheBloke/WizardLM-13B-V1.2-GGML
- TheBloke/WizardLM-13B-V1.1-GGML
- TheBloke/wizard-vicuna-13B-GGML
- TheBloke/Llama-2-13B-chat-GGML
- TheBloke/OpenAssistant-Llama2-13B-Orca-8K-3319-GGML
- TheBloke/Chronos-Beluga-v2-13B-GGML
- TheBloke/MythoMax-L2-13B-GGML
- and much more.
## Available notebooks :
-(New - contains all quantizations of gmml) UltimateOneClick_LocalLLM_13B_GGML_(127_Models) => <a target="_blank" href="https://colab.research.google.com/github/seyf1elislam/LocalLLM_UltimateOneClick_Colab/blob/main/UltimateOneClick_LocalLLM_13B_GGML_(127_Models).ipynb"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a>

-(old - contains only Gmml Q5_K_M versions) UltimateOneClick LocalLLM 13B GGML Q5_K_M_(111_Models) => <a target="_blank" href="https://colab.research.google.com/github/seyf1elislam/LocalLLM_UltimateOneClick_Colab/blob/main/UltimateOneClick_LocalLLM_13B_GGML_Q5_K_M_(111_Models).ipynb"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a> 
## Features

- One-click setup: The Colab notebook is designed to be easily set up with just one click. It automatically installs the required dependencies and downloads the necessary model files.
- More than 127 Pre-trained and finetuned 13b LLM models: The notebook includes various pre-trained and finetuned LLM models, including LLama2 13b chat, WizardLm1.2, and much more. It currently includes 13B LLM models (127 model GGML all versions). Additionally, 13B GPTQ models will be added soon.
- User interface: The notebook integrates with the [Text Generation WebUI](https://github.com/oobabooga/text-generation-webui) for a user-friendly interface to interact with the LLM models.


## Getting Started

To get started with the LLM Model Runner, follow these steps:

1. Open the Colab notebook in Google Colab by clicking on the "Open in Colab" button at the top of the notebook.
<a target="_blank" href="https://colab.research.google.com/github/seyf1elislam/LocalLLM_UltimateOneClick_Colab/blob/main/UltimateOneClick_LocalLLM_13B_GGML_(127_Models).ipynb"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a>
2. Choose The 13b LLM model that you want from the list (+127 13Bmodels).

![image](https://github.com/seyf1elislam/LocalLLM_UltimateOneClick_Colab/assets/40665383/ceb36323-380d-4868-90da-b1d735d07643)

3.Choose quantization type:

![image](https://github.com/seyf1elislam/LocalLLM_UltimateOneClick_Colab/assets/40665383/c1f9a784-1e62-4411-92fa-6c892388ed7c)


4. Run the Cell and Visit the Generated link( https://***.gradio.live ) and start your Conversation with your favorite model !

## Requirements
- no Requirement just open Colab in Gpu mode

All the necessary dependencies will be automatically installed when you run the Colab notebook.


## License

All  Models license belongs to thier owners please follow the link of the Model repo and read its license if u need.

## Thanks <3

### Special thanks to 
- [TheBloke](https://huggingface.co/TheBloke) for their Quantized LLM models.
- [text-generation-webui](https://github.com/oobabooga/text-generation-webui) for their Great Ui 
- [Troyanovsky](https://github.com/Troyanovsky)

# Models Source : 

* [TheBloke/13B-BlueMethod-GGML](https://huggingface.co/TheBloke/13B-BlueMethod-GGML/tree/main)
* [TheBloke/13B-Chimera-GGML](https://huggingface.co/TheBloke/13B-Chimera-GGML/tree/main)
* [TheBloke/13B-HyperMantis-GGML](https://huggingface.co/TheBloke/13B-HyperMantis-GGML/tree/main)
* [TheBloke/13B-Legerdemain-L2-GGML](https://huggingface.co/TheBloke/13B-Legerdemain-L2-GGML/tree/main)
* [TheBloke/13B-Ouroboros-GGML](https://huggingface.co/TheBloke/13B-Ouroboros-GGML/tree/main)
* [TheBloke/Airochronos-L2-13B-GGML](https://huggingface.co/TheBloke/Airochronos-L2-13B-GGML/tree/main)
* [TheBloke/Airolima-Chronos-Grad-L2-13B-GGML](https://huggingface.co/TheBloke/Airolima-Chronos-Grad-L2-13B-GGML/tree/main)
* [TheBloke/AlpacaCielo-13B-GGML](https://huggingface.co/TheBloke/AlpacaCielo-13B-GGML/tree/main)
* [TheBloke/Baize-v2-13B-SuperHOT-8K-GGML](https://huggingface.co/TheBloke/Baize-v2-13B-SuperHOT-8K-GGML/tree/main)
* [TheBloke/BigTranslate-13B-GGML](https://huggingface.co/TheBloke/BigTranslate-13B-GGML/tree/main)
* [TheBloke/CAMEL-13B-Combined-Data-GGML](https://huggingface.co/TheBloke/CAMEL-13B-Combined-Data-GGML/tree/main)
* [TheBloke/CAMEL-13B-Combined-Data-SuperHOT-8K-GGML](https://huggingface.co/TheBloke/CAMEL-13B-Combined-Data-SuperHOT-8K-GGML/tree/main)
* [TheBloke/CAMEL-13B-Role-Playing-Data-GGML](https://huggingface.co/TheBloke/CAMEL-13B-Role-Playing-Data-GGML/tree/main)
* [TheBloke/CAMEL-13B-Role-Playing-Data-SuperHOT-8K-GGML](https://huggingface.co/TheBloke/CAMEL-13B-Role-Playing-Data-SuperHOT-8K-GGML/tree/main)
* [TheBloke/Camel-Platypus2-13B-GGML](https://huggingface.co/TheBloke/Camel-Platypus2-13B-GGML/tree/main)
* [TheBloke/Chronoboros-Grad-L2-13B-GGML](https://huggingface.co/TheBloke/Chronoboros-Grad-L2-13B-GGML/tree/main)
* [TheBloke/Chronohermes-Grad-L2-13B-GGML](https://huggingface.co/TheBloke/Chronohermes-Grad-L2-13B-GGML/tree/main)
* [TheBloke/Chronolima-Airo-Grad-L2-13B-GGML](https://huggingface.co/TheBloke/Chronolima-Airo-Grad-L2-13B-GGML/tree/main)
* [TheBloke/Chronos-13B-SuperHOT-8K-GGML](https://huggingface.co/TheBloke/Chronos-13B-SuperHOT-8K-GGML/tree/main)
* [TheBloke/Chronos-13B-v2-GGML](https://huggingface.co/TheBloke/Chronos-13B-v2-GGML/tree/main)
* [TheBloke/Chronos-Beluga-v2-13B-GGML](https://huggingface.co/TheBloke/Chronos-Beluga-v2-13B-GGML/tree/main)
* [TheBloke/Chronos-Hermes-13B-SuperHOT-8K-GGML](https://huggingface.co/TheBloke/Chronos-Hermes-13B-SuperHOT-8K-GGML/tree/main)
* [TheBloke/Chronos-Hermes-13B-v2-GGML](https://huggingface.co/TheBloke/Chronos-Hermes-13B-v2-GGML/tree/main)
* [TheBloke/CodeUp-Llama-2-13B-Chat-HF-GGML](https://huggingface.co/TheBloke/CodeUp-Llama-2-13B-Chat-HF-GGML/tree/main)
* [TheBloke/Dolphin-Llama-13B-GGML](https://huggingface.co/TheBloke/Dolphin-Llama-13B-GGML/tree/main)
* [TheBloke/Firefly-Llama2-13B-v1.2-GGML](https://huggingface.co/TheBloke/Firefly-Llama2-13B-v1.2-GGML/tree/main)
* [TheBloke/GPT4All-13B-Snoozy-SuperHOT-8K-GGML](https://huggingface.co/TheBloke/GPT4All-13B-Snoozy-SuperHOT-8K-GGML/tree/main)
* [TheBloke/GPT4All-13B-snoozy-GGML](https://huggingface.co/TheBloke/GPT4All-13B-snoozy-GGML/tree/main)
* [TheBloke/Hermes-LLongMA-2-13B-8K-GGML](https://huggingface.co/TheBloke/Hermes-LLongMA-2-13B-8K-GGML/tree/main)
* [TheBloke/Huginn-13B-GGML](https://huggingface.co/TheBloke/Huginn-13B-GGML/tree/main)
* [TheBloke/Karen_theEditor_13B-GGML](https://huggingface.co/TheBloke/Karen_theEditor_13B-GGML/tree/main)
* [TheBloke/Kimiko-13B-GGML](https://huggingface.co/TheBloke/Kimiko-13B-GGML/tree/main)
* [TheBloke/Koala-13B-SuperHOT-8K-GGML](https://huggingface.co/TheBloke/Koala-13B-SuperHOT-8K-GGML/tree/main)
* [TheBloke/LLaMa-13B-GGML](https://huggingface.co/TheBloke/LLaMa-13B-GGML/tree/main)
* [TheBloke/Llama-2-13B-GGML](https://huggingface.co/TheBloke/Llama-2-13B-GGML/tree/main)
* [TheBloke/Llama-2-13B-chat-GGML](https://huggingface.co/TheBloke/Llama-2-13B-chat-GGML/tree/main)
* [TheBloke/LongChat-13B-GGML](https://huggingface.co/TheBloke/LongChat-13B-GGML/tree/main)
* [TheBloke/Manticore-13B-Chat-Pyg-Guanaco-SuperHOT-8K-GGML](https://huggingface.co/TheBloke/Manticore-13B-Chat-Pyg-Guanaco-SuperHOT-8K-GGML/tree/main)
* [TheBloke/Manticore-13B-Chat-Pyg-SuperHOT-8K-GGML](https://huggingface.co/TheBloke/Manticore-13B-Chat-Pyg-SuperHOT-8K-GGML/tree/main)
* [TheBloke/Manticore-13B-GGML](https://huggingface.co/TheBloke/Manticore-13B-GGML/tree/main)
* [TheBloke/Manticore-13B-SuperHOT-8K-GGML](https://huggingface.co/TheBloke/Manticore-13B-SuperHOT-8K-GGML/tree/main)
* [TheBloke/Minotaur-13B-fixed-SuperHOT-8K-GGML](https://huggingface.co/TheBloke/Minotaur-13B-fixed-SuperHOT-8K-GGML/tree/main)
* [TheBloke/MythoBoros-13B-GGML](https://huggingface.co/TheBloke/MythoBoros-13B-GGML/tree/main)
* [TheBloke/MythoLogic-13B-GGML](https://huggingface.co/TheBloke/MythoLogic-13B-GGML/tree/main)
* [TheBloke/MythoLogic-L2-13B-GGML](https://huggingface.co/TheBloke/MythoLogic-L2-13B-GGML/tree/main)
* [TheBloke/MythoMax-L2-13B-GGML](https://huggingface.co/TheBloke/MythoMax-L2-13B-GGML/tree/main)
* [TheBloke/MythoMix-L2-13B-GGML](https://huggingface.co/TheBloke/MythoMix-L2-13B-GGML/tree/main)
* [TheBloke/Nous-Hermes-13B-GGML](https://huggingface.co/TheBloke/Nous-Hermes-13B-GGML/tree/main)
* [TheBloke/OpenAssistant-Llama2-13B-Orca-8K-3319-GGML](https://huggingface.co/TheBloke/OpenAssistant-Llama2-13B-Orca-8K-3319-GGML/tree/main)
* [TheBloke/OpenAssistant-Llama2-13B-Orca-v2-8K-3166-GGML](https://huggingface.co/TheBloke/OpenAssistant-Llama2-13B-Orca-v2-8K-3166-GGML/tree/main)
* [TheBloke/OpenOrca-Preview1-13B-GGML](https://huggingface.co/TheBloke/OpenOrca-Preview1-13B-GGML/tree/main)
* [TheBloke/OpenOrcaxOpenChat-Preview2-13B-GGML](https://huggingface.co/TheBloke/OpenOrcaxOpenChat-Preview2-13B-GGML/tree/main)
* [TheBloke/Platypus2-13B-GGML](https://huggingface.co/TheBloke/Platypus2-13B-GGML/tree/main)
* [TheBloke/Project-Baize-v2-13B-GGML](https://huggingface.co/TheBloke/Project-Baize-v2-13B-GGML/tree/main)
* [TheBloke/Pygmalion-13B-SuperHOT-8K-GGML](https://huggingface.co/TheBloke/Pygmalion-13B-SuperHOT-8K-GGML/tree/main)
* [TheBloke/Redmond-Puffin-13B-GGML](https://huggingface.co/TheBloke/Redmond-Puffin-13B-GGML/tree/main)
* [TheBloke/Robin-13B-v2-SuperHOT-8K-GGML](https://huggingface.co/TheBloke/Robin-13B-v2-SuperHOT-8K-GGML/tree/main)
* [TheBloke/Samantha-13B-SuperHOT-8K-GGML](https://huggingface.co/TheBloke/Samantha-13B-SuperHOT-8K-GGML/tree/main)
* [TheBloke/Selfee-13B-GGML](https://huggingface.co/TheBloke/Selfee-13B-GGML/tree/main)
* [TheBloke/Selfee-13B-GGML-DOI](https://huggingface.co/TheBloke/Selfee-13B-GGML-DOI/tree/main)
* [TheBloke/Selfee-13B-SuperHOT-8K-GGML](https://huggingface.co/TheBloke/Selfee-13B-SuperHOT-8K-GGML/tree/main)
* [TheBloke/Stable-Platypus2-13B-GGML](https://huggingface.co/TheBloke/Stable-Platypus2-13B-GGML/tree/main)
* [TheBloke/StableBeluga-13B-GGML](https://huggingface.co/TheBloke/StableBeluga-13B-GGML/tree/main)
* [TheBloke/Tulu-13B-SuperHOT-8K-GGML](https://huggingface.co/TheBloke/Tulu-13B-SuperHOT-8K-GGML/tree/main)
* [TheBloke/UltraLM-13B-GGML](https://huggingface.co/TheBloke/UltraLM-13B-GGML/tree/main)
* [TheBloke/Vicuna-13B-CoT-GGML](https://huggingface.co/TheBloke/Vicuna-13B-CoT-GGML/tree/main)
* [TheBloke/Vicuna-13B-v1.3-German-GGML](https://huggingface.co/TheBloke/Vicuna-13B-v1.3-German-GGML/tree/main)
* [TheBloke/Vigogne-2-13B-Instruct-GGML](https://huggingface.co/TheBloke/Vigogne-2-13B-Instruct-GGML/tree/main)
* [TheBloke/Vigogne-Instruct-13B-GGML](https://huggingface.co/TheBloke/Vigogne-Instruct-13B-GGML/tree/main)
* [TheBloke/Wizard-Vicuna-13B-Uncensored-GGML](https://huggingface.co/TheBloke/Wizard-Vicuna-13B-Uncensored-GGML/tree/main)
* [TheBloke/Wizard-Vicuna-13B-Uncensored-SuperHOT-8K-GGML](https://huggingface.co/TheBloke/Wizard-Vicuna-13B-Uncensored-SuperHOT-8K-GGML/tree/main)
* [TheBloke/WizardLM-1.0-Uncensored-Llama2-13B-GGML](https://huggingface.co/TheBloke/WizardLM-1.0-Uncensored-Llama2-13B-GGML/tree/main)
* [TheBloke/WizardLM-13B-Uncensored-GGML](https://huggingface.co/TheBloke/WizardLM-13B-Uncensored-GGML/tree/main)
* [TheBloke/WizardLM-13B-V1-0-Uncensored-SuperHOT-8K-GGML](https://huggingface.co/TheBloke/WizardLM-13B-V1-0-Uncensored-SuperHOT-8K-GGML/tree/main)
* [TheBloke/WizardLM-13B-V1-1-SuperHOT-8K-GGML](https://huggingface.co/TheBloke/WizardLM-13B-V1-1-SuperHOT-8K-GGML/tree/main)
* [TheBloke/WizardLM-13B-V1.0-Uncensored-GGML](https://huggingface.co/TheBloke/WizardLM-13B-V1.0-Uncensored-GGML/tree/main)
* [TheBloke/WizardLM-13B-V1.1-GGML](https://huggingface.co/TheBloke/WizardLM-13B-V1.1-GGML/tree/main)
* [TheBloke/WizardLM-13B-V1.2-GGML](https://huggingface.co/TheBloke/WizardLM-13B-V1.2-GGML/tree/main)
* [TheBloke/WizardMath-13B-V1.0-GGML](https://huggingface.co/TheBloke/WizardMath-13B-V1.0-GGML/tree/main)
* [TheBloke/airoboros-13B-1.1-GGML](https://huggingface.co/TheBloke/airoboros-13B-1.1-GGML/tree/main)
* [TheBloke/airoboros-13B-gpt4-1.2-GGML](https://huggingface.co/TheBloke/airoboros-13B-gpt4-1.2-GGML/tree/main)
* [TheBloke/airoboros-13B-gpt4-1.3-GGML](https://huggingface.co/TheBloke/airoboros-13B-gpt4-1.3-GGML/tree/main)
* [TheBloke/airoboros-13B-gpt4-1.4-GGML](https://huggingface.co/TheBloke/airoboros-13B-gpt4-1.4-GGML/tree/main)
* [TheBloke/airoboros-13b-gpt4-GGML](https://huggingface.co/TheBloke/airoboros-13b-gpt4-GGML/tree/main)
* [TheBloke/airoboros-l2-13B-gpt4-1.4.1-GGML](https://huggingface.co/TheBloke/airoboros-l2-13B-gpt4-1.4.1-GGML/tree/main)
* [TheBloke/airoboros-l2-13b-gpt4-2.0-GGML](https://huggingface.co/TheBloke/airoboros-l2-13b-gpt4-2.0-GGML/tree/main)
* [TheBloke/airoboros-l2-13b-gpt4-m2.0-GGML](https://huggingface.co/TheBloke/airoboros-l2-13b-gpt4-m2.0-GGML/tree/main)
* [TheBloke/based-13b-GGML](https://huggingface.co/TheBloke/based-13b-GGML/tree/main)
* [TheBloke/chronos-13B-GGML](https://huggingface.co/TheBloke/chronos-13B-GGML/tree/main)
* [TheBloke/chronos-hermes-13B-GGML](https://huggingface.co/TheBloke/chronos-hermes-13B-GGML/tree/main)
* [TheBloke/chronos-wizardlm-uc-scot-st-13B-GGML](https://huggingface.co/TheBloke/chronos-wizardlm-uc-scot-st-13B-GGML/tree/main)
* [TheBloke/gpt4-x-alpaca-13B-GGML](https://huggingface.co/TheBloke/gpt4-x-alpaca-13B-GGML/tree/main)
* [TheBloke/gpt4-x-vicuna-13B-GGML](https://huggingface.co/TheBloke/gpt4-x-vicuna-13B-GGML/tree/main)
* [TheBloke/guanaco-13B-GGML](https://huggingface.co/TheBloke/guanaco-13B-GGML/tree/main)
* [TheBloke/h2ogpt-4096-llama2-13B-GGML](https://huggingface.co/TheBloke/h2ogpt-4096-llama2-13B-GGML/tree/main)
* [TheBloke/h2ogpt-4096-llama2-13B-chat-GGML](https://huggingface.co/TheBloke/h2ogpt-4096-llama2-13B-chat-GGML/tree/main)
* [TheBloke/koala-13B-GGML](https://huggingface.co/TheBloke/koala-13B-GGML/tree/main)
* [TheBloke/llama-13b-supercot-GGML](https://huggingface.co/TheBloke/llama-13b-supercot-GGML/tree/main)
* [TheBloke/llama-2-13B-German-Assistant-v2-GGML](https://huggingface.co/TheBloke/llama-2-13B-German-Assistant-v2-GGML/tree/main)
* [TheBloke/llama-2-13B-Guanaco-QLoRA-GGML](https://huggingface.co/TheBloke/llama-2-13B-Guanaco-QLoRA-GGML/tree/main)
* [TheBloke/manticore-13b-chat-pyg-GGML](https://huggingface.co/TheBloke/manticore-13b-chat-pyg-GGML/tree/main)
* [TheBloke/medalpaca-13B-GGML](https://huggingface.co/TheBloke/medalpaca-13B-GGML/tree/main)
* [TheBloke/minotaur-13B-GGML](https://huggingface.co/TheBloke/minotaur-13B-GGML/tree/main)
* [TheBloke/minotaur-13B-fixed-GGML](https://huggingface.co/TheBloke/minotaur-13B-fixed-GGML/tree/main)
* [TheBloke/open-llama-13b-open-instruct-GGML](https://huggingface.co/TheBloke/open-llama-13b-open-instruct-GGML/tree/main)
* [TheBloke/orca_mini_13B-GGML](https://huggingface.co/TheBloke/orca_mini_13B-GGML/tree/main)
* [TheBloke/orca_mini_v2_13b-GGML](https://huggingface.co/TheBloke/orca_mini_v2_13b-GGML/tree/main)
* [TheBloke/orca_mini_v3_13B-GGML](https://huggingface.co/TheBloke/orca_mini_v3_13B-GGML/tree/main)
* [TheBloke/robin-13B-v2-GGML](https://huggingface.co/TheBloke/robin-13B-v2-GGML/tree/main)
* [TheBloke/samantha-1.1-llama-13B-GGML](https://huggingface.co/TheBloke/samantha-1.1-llama-13B-GGML/tree/main)
* [TheBloke/samantha-13B-GGML](https://huggingface.co/TheBloke/samantha-13B-GGML/tree/main)
* [TheBloke/stable-vicuna-13B-GGML](https://huggingface.co/TheBloke/stable-vicuna-13B-GGML/tree/main)
* [TheBloke/tulu-13B-GGML](https://huggingface.co/TheBloke/tulu-13B-GGML/tree/main)
* [TheBloke/vicuna-13B-v1.5-16K-GGML](https://huggingface.co/TheBloke/vicuna-13B-v1.5-16K-GGML/tree/main)
* [TheBloke/vicuna-13B-v1.5-GGML](https://huggingface.co/TheBloke/vicuna-13B-v1.5-GGML/tree/main)
* [TheBloke/vicuna-13b-1.1-GGML](https://huggingface.co/TheBloke/vicuna-13b-1.1-GGML/tree/main)
* [TheBloke/vicuna-13b-v1.3.0-GGML](https://huggingface.co/TheBloke/vicuna-13b-v1.3.0-GGML/tree/main)
* [TheBloke/wizard-mega-13B-GGML](https://huggingface.co/TheBloke/wizard-mega-13B-GGML/tree/main)
* [TheBloke/wizard-vicuna-13B-GGML](https://huggingface.co/TheBloke/wizard-vicuna-13B-GGML/tree/main)
* [TheBloke/wizard-vicuna-13B-SuperHOT-8K-GGML](https://huggingface.co/TheBloke/wizard-vicuna-13B-SuperHOT-8K-GGML/tree/main)
* [TheBloke/wizardLM-13B-1.0-GGML](https://huggingface.co/TheBloke/wizardLM-13B-1.0-GGML/tree/main)
