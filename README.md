# Llama2_HealthTool_Chatbot

# How to run?
### STEPS:


##Clone the repository


Project repo: https://github.com/


### STEP 02- install the requirements

pip install -r requirements.txt


### Download the quantize model from the link provided in model folder & keep the model in the model directory:


## Download the Llama 2 Model:

llama-2-7b-chat.ggmlv3.q4_0.bin


## From the following link:
https://huggingface.co/TheBloke/Llama-2-7B-Chat-GGML/tree/main


## Download the Llama 2 Quantized Model:

Q4_K_M.gguf


## From the following link:
https://huggingface.co/armin06/qwen-7b-llm/tree/main


# run the following command
python ingest.py



# Finally run the following command
python app.py


- open up localhost:



### Techstack Used:

- Python
- LangChain
- Flask
- Meta Llama2
- FAISS CPU

### Run the finetune_model.ipynb in Colab. This file is for model fine tuning.
### Run the QuantizedModel.ipynb in Colab. This file is for model quantization.
