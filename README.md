# 🚀 API FastAPI com TDD, Pytest e MongoDB

Este projeto é uma **API desenvolvida em Python (FastAPI)** com
integração ao **MongoDB**, construída com foco em **Test-Driven
Development (TDD)**.\
O objetivo é aplicar práticas de testes utilizando **pytest** em
diferentes camadas: **Schemas, UseCases e Controllers**.

------------------------------------------------------------------------

## 🛠️ Tecnologias Utilizadas

-   [Python 3.11+](https://www.python.org/)
-   [FastAPI](https://fastapi.tiangolo.com/)
-   [MongoDB](https://www.mongodb.com/)
-   [Pytest](https://docs.pytest.org/)
-   [Pydantic](https://docs.pydantic.dev/)
-   [Uvicorn](https://www.uvicorn.org/)

------------------------------------------------------------------------

## 🎯 Objetivo do Projeto

-   Exercitar **conceitos de TDD** em APIs modernas.
-   Criar testes automatizados com `pytest`.
-   Estruturar testes para **Schemas, UseCases e Controllers**.
-   Praticar boas práticas de tratamento de exceções e mensagens
    amigáveis.

------------------------------------------------------------------------

## 🧪 Desafio Final

1.  **Create**
    -   Mapear uma exceção no momento da inserção no banco.\
    -   Caso ocorra erro de inserção, capturar a exceção na
        **Controller** e retornar uma mensagem amigável ao usuário.
2.  **Update (PATCH)**
    -   Modificar o método PATCH para:
        -   Retornar exceção **404** quando o dado não for encontrado.\
        -   Tratar a exceção no **Controller**, retornando mensagem
            amigável ao usuário.\
        -   Adicionar a **data de atualização (`updated_at`)** com a
            data/hora do momento do update.
3.  **Filtros**
    -   Implementar cadastro de produtos com preços diferentes.\
    -   Criar **filtros por preço**:
        -   `maior que`\
        -   `menor que`

------------------------------------------------------------------------

## ⚙️ Preparando o Ambiente

1.  Clone o repositório:

    ``` bash
    git clone https://github.com/seu-usuario/seu-repositorio.git
    cd seu-repositorio
    ```

2.  Crie e ative o ambiente virtual:

    ``` bash
    python -m venv venv
    source venv/bin/activate   # Linux/Mac
    venv\Scripts\activate      # Windows
    ```

3.  Instale as dependências:

    ``` bash
    pip install -r requirements.txt
    ```

4.  Execute a API:

    ``` bash
    uvicorn app.main:app --reload
    ```

5.  Rode os testes:

    ``` bash
    pytest -v
    ```

------------------------------------------------------------------------

## 📚 Documentações Úteis

-   [FastAPI](https://fastapi.tiangolo.com/)
-   [MongoDB](https://www.mongodb.com/docs/)
-   [Pytest](https://docs.pytest.org/)
-   [Pydantic](https://docs.pydantic.dev/)

