## Catchy Intro App

### Get an OpenAI API key

You can get your own OpenAI API key by following the following instructions:

1. Go to https://platform.openai.com/account/api-keys.
2. Click on the `+ Create new secret key` button.
3. Next, enter an identifier name (optional) and click on the `Create secret key` button.

### Enter the OpenAI API key in Streamlit Community Cloud

To set the OpenAI API key as an environment variable in Streamlit apps, do the following:

1. At the lower right corner, click on `< Manage app` then click on the vertical "..." followed by clicking on `Settings`.
2. This brings the **App settings**, next click on the `Secrets` tab and paste the API key into the text box as follows:

```sh
OPENAI_API_KEY='xxxxxxxxxx'
```

## Run it locally
Create virtual environment
```sh
virtualenv .venv
or
python -m venv .venv
```
Activate environment
```sh
source .venv/bin/activate
or
.venv/Scripts/activate
```
Install packages
```sh
pip install -r requirements.txt
```
Run streamlit application locally
```sh
streamlit run catchy_intro_bot.py
```