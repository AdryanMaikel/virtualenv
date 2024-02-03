# virtualenv

* Windows

    Criando virtualenv chamada python

    ```bash
    python -m venv python
    ```

    Ativando a virtualenv

    ```bash
    .\python\Scripts\activate
    ```

* Linux

    Criando virtualenv chamada python

    ```bash
    python3 -m venv python
    ```

    Ativando a virtualenv

    ```bash
    source python/bin/activate
    ```

----

## Bibliotecas

1. Instalar com pip

    ```bash
    pip install selenium
    ```

2. Remover com pip

    ```bash
    pip uninstall selenium
    ```

----

## Requirements.txt

1. Gerar arquivo requirements.txt

   ```bash
    pip freeze > requirements.txt
    ```

2. Instalar com requirements.txt

    ```bash
    pip install -r requirements.txt
    ```

3. Remover com requirements.txt

    ```bash
    pip uninstall -r requirements.txt -y
    ```

----
