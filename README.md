# Desafio FastAPI - DIO e Vivo

Projeto baseado no repositório da [Nayanna Nara](https://github.com/digitalinnovationone/workout_api)

## MER do projeto
![MER](/mer.jpg "Modelagem de entidade e relacionamento")

## Tarefas do desafio:
    - adicionar query parameters nos endpoints
        - atleta
                - nome
                - cpf
    - customizar response de retorno de endpoints
        - get all
                - atleta
                    - nome
                    - centro_treinamento
                    - categoria
    - Manipular exceção de integridade dos dados em cada módulo/tabela
        - sqlalchemy.exc.IntegrityError e devolver a seguinte mensagem: “Já existe um atleta cadastrado com o cpf: x”
        - status_code: 303 
    - Adicionar paginação utilizando a lib: fastapi-pagination
        - limit e offset