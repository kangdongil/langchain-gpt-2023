# How to use LangChain for AI-powered App

## 0.1 Project Requirements

### Python Virtual Environment

1. Create and activate a Python virtual environment:

```shell
python -m venv ./env
source env/Scripts/activate
```

2. Create a `requirements.txt` file and install python packages:

```shell
curl -sSL https://gist.githubusercontent.com/serranoarevalo/72d77c36dde1cc3ffec34105eb666140/raw/d18ab867affcf7e122947d2b40dbd9934dd21186/requirements.txt -o requirements.txt
```

### Manage OpenAI API Key in Environment File(`.env`)

1. Acquire OpenAI's Projects API keys([Link](https://platform.openai.com/organization/api-keys))

2. Create and add api_key into `.env` file

```shell
echo 'OPENAI_SECRET_KEY="[API_KEY]"' > .env
```

### Git Settings

1. Initalize the repository and create a `.gitignore` file:

```shell
git init .
touch .gitignore
```

2. Add the following entries to your `.gitignore` file:

- Python, JupyterNotebooks([Link](https://www.toptal.com/developers/gitignore/api/python,jupyternotebooks))
- Python Venv, Environment File

```shell
# Python Virtual Environment
env/

# Environment File
.env
```

### VSCode Settings

1. Install VScode Extensions

- `ms-python.python`
- `ms-toolsai.jupyer`