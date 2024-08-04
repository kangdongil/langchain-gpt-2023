# How to use LangChain for AI-powered App

## 0.1 Project Requirements

### Python Virtual Environment

1. Create and activate a Python virtual environment:

```shell
python -m venv ./env
source env/Scripts/activate
```

2. Create a `requirements.txt` file:

```shell
touch requirements.txt
```

3. Download the Package List and paste its contents into `requirements.txt`:

- [PACKAGE_LIST](https://gist.githubusercontent.com/serranoarevalo/72d77c36dde1cc3ffec34105eb666140/raw/d18ab867affcf7e122947d2b40dbd9934dd21186/requirements.txt)

4. Install the packages from `requirements.txt`:

```shell
pip install -r requirements.txt
```

### Environment File(`.env`)

1. Create an `.env` file:

```shell
touch .env
```

### Git Settings

1. Initalize the repository and create a `.gitignore` file:

```shell
git init .
touch .gitignore
```

2. Add the following entries to your `.gitignore` file:

```
# Environmental Folder and File
env/
`.env
```
