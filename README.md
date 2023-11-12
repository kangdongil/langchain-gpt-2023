# 0.1 Project Requirements

- Git Settings

  ```shell
  git init .
  touch .gitignore
  ```

  - GitIgnore List
    - `env/`
    - `.env`

- Python Virtual Environment

  - [PACKAGE_LIST](https://gist.githubusercontent.com/serranoarevalo/72d77c36dde1cc3ffec34105eb666140/raw/d18ab867affcf7e122947d2b40dbd9934dd21186/requirements.txt)

    ```shell
    python -m venv ./env
    source env/Scripts/activate
    touch requirements.txt

    ...PASTE_PACKAGE_LIST

    pip install -r requirements.txt
    ```

- Environment File(`.env`)
  ```shell
  touch .env
  ```

# 1.0 LangChain 이해하기

- LLMs vs. Chat Models
  - Chat Models가 최적화되어 있어 비용이 저렴하므로 해당 모델을 사용한다
  ```python
  from langchain.llms import OpenAI # LLMs
  from langchain.chat_models import ChatOpenAI # Chat Model
  ```
