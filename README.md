# Text Generator

**Text Generator** is an `End-to-End NLP model` which can generate text based on given input deployed on **Streamlit**

**Model :** **`GPT-2`**

**Library :** **`🤗 Hugging Face `**

**Pre-Trained on :** **`English language using a causal language modeling (CLM)`**


## [View Deployed Demo on Streamlit](https://share.streamlit.io/srajanseth84/all-ml-projects-streamlit/main/app.py)
- Just open above link and select Text Generator


## Demo


![](extras/demo.gif.gif)


### A Few Examples

* The beautiful ruins of the ancient city of Persepolis (Iran) with the style of Van Gogh (The Starry Night) 
  <img src="images/">
* The tomb of Cyrus the great in Pasargadae with the style of a Ceramic Kashi from Ispahan 
  <img src="images/">
* A scientific study of a turbulent fluid with the style of a abstract blue fluid painting
  <img src = "images/">



## Run Locally


* Clone the project

```bash
  git clone https://github.com/srajanseth84/Text-Generator-using-GPT2.git
```

* Go to the project directory

```bash
  cd Text-Generator-using-GPT2
```
* Create venv

```bash
  python3 -m virtualenv venv 
```

* Activate the venv

```bash
  source venv/bin/activate
```

* Install dependencies

```bash
  pip install -r requirements.txt
```

* Start the server

```bash
  streamlit run app.py 
```

## GPT-2 MODEL DESCRIPTION

- GPT-2 is a transformers model pretrained on a very large corpus of English data in a **self-supervised fashion**. This means it was pretrained on the raw texts only, with no humans labelling them in any way (which is why it can use lots of publicly available data) with an automatic process to generate inputs and labels from those texts. More precisely, it was trained to guess the next word in sentences.

- More precisely, inputs are sequences of continuous text of a certain length and the targets are the same sequence, shifted one token (word or piece of word) to the right. The model uses internally a mask-mechanism to make sure the predictions for the token i only uses the inputs from 1 to i but not the future tokens.

- This way, the model learns an inner representation of the English language that can then be used to extract features useful for downstream tasks. The model is best at what it was pretrained for however, which is generating texts from a prompt.



## Dependencies

* [Tensorflow](https://github.com/tensorflow/tensorflow)
* [Hugging Face 🤗](https://huggingface.co/)
* [Streamlit](https://github.com/streamlit/streamlit)
* [GPT-2](https://huggingface.co/gpt2)  

## Tech Stack
* **Front-End**: [Streamlit](https://github.com/streamlit/streamlit)
* **Cloud**: [Streamlit Cloud](https://streamlit.io/cloud)
* **DL-Framework**: [Hugging Face](https://huggingface.co/)




## Reference

- [Hugging Face 🤗](https://huggingface.co/)
- [GPT-2](https://huggingface.co/gpt2) 

## Authors

- [@srajanseth84](https://github.com/srajanseth84)
