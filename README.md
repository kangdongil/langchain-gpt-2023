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
