
# 📚 Caderno Temático: FastAPI com NotebookLM

🔗 **Acesso ao NotebookLM:**  
https://notebooklm.google.com/notebook/49fd2634-9884-408a-8a5e-8662a058e013

---

## 🎯 Contexto e Objetivos

Este projeto foi desenvolvido como parte de um desafio da DIO utilizando o NotebookLM como ferramenta de apoio aos estudos.

O tema escolhido foi **FastAPI**, framework moderno para criação de APIs em Python.

### Objetivos

- Aprender os fundamentos do FastAPI.
- Entender validação de dados com Pydantic.
- Conhecer boas práticas de desenvolvimento.
- Compreender diferenças entre FastAPI, Flask e Django.
- Entender o impacto de operações síncronas e assíncronas.
- Utilizar IA para revisão e esclarecimento de dúvidas.

---

# 📖 Curadoria de Fontes

As seguintes fontes foram utilizadas no NotebookLM para estudo e consulta sobre FastAPI:

### 1. Documentação Oficial FastAPI
https://fastapi.tiangolo.com/

### 2. Tutorial Oficial FastAPI
https://fastapi.tiangolo.com/tutorial/

### 3. Pydantic Validation Documentation
https://pydantic.dev/docs/validation/latest/get-started/

### 4. Comparativo entre Django, Flask e FastAPI
https://blog.jetbrains.com/pycharm/2025/02/django-flask-fastapi/

### 5. FastAPI Best Practices
https://auth0.com/blog/fastapi-best-practices/

### 6. FastAPI Async vs Sync Performance
https://pysolutions.dev/blog/fastapi-async-vs-sync-performance

---

# 🤖 Engenharia de Prompts

### Prompt 1

**Pergunta:**

> Com base nas fontes carregadas neste caderno, explique os conceitos fundamentais do FastAPI e apresente um resumo estruturado para iniciantes.

**Principais aprendizados:**

- FastAPI é um framework moderno para criação de APIs em Python.
- Utiliza Pydantic para validação de dados.
- Possui suporte nativo à programação assíncrona com `async` e `await`.
- Gera documentação automática através do Swagger (`/docs`) e ReDoc (`/redoc`).
- Oferece sistema de injeção de dependências para reutilização de componentes.

**Conceitos identificados:**

- Rotas e operações HTTP
- Path Parameters
- Query Parameters
- Request Body
- Schemas com Pydantic
- Status Codes
- Uvicorn
- Documentação automática

**Resultado:**

O prompt ajudou a consolidar uma visão geral da arquitetura do FastAPI e seus principais recursos.

---

### Prompt 2

**Pergunta:**

> Quais são os componentes mais importantes do FastAPI (rotas, parâmetros, Pydantic, validação de dados e documentação automática)? Explique cada um com exemplos simples.

**Principais aprendizados:**

- As rotas são definidas através de decoradores como `@app.get()` e `@app.post()`.
- O FastAPI diferencia automaticamente Path Parameters e Query Parameters.
- O Pydantic é utilizado para criar modelos de dados e validar informações recebidas.
- A validação acontece automaticamente através de Type Hints e modelos Pydantic.
- A documentação da API é gerada automaticamente através do Swagger (`/docs`) e ReDoc (`/redoc`).

**Resultado:**

O estudo permitiu compreender como o FastAPI organiza endpoints, valida dados e fornece documentação interativa sem necessidade de configurações adicionais.

**Dificuldade encontrada:**

Inicialmente havia confusão entre Path Parameters e Query Parameters. Os exemplos gerados pelo NotebookLM ajudaram a visualizar a diferença prática entre ambos.

---

### Prompt 3

**Pergunta:**

> Com base nas fontes deste caderno, quais são os erros mais comuns cometidos por iniciantes em FastAPI e quais boas práticas devem ser adotadas para evitá-los?

**Principais aprendizados:**

#### Erros comuns

- Uso incorreto de `async def` com operações bloqueantes.
- Ordem inadequada na definição das rotas.
- Senhas e configurações armazenadas diretamente no código.
- Exposição de dados sensíveis nas respostas da API.
- Falta de persistência por ausência do `commit()` no banco de dados.

#### Boas práticas

- Utilizar modelos Pydantic para validação de entrada e saída.
- Gerenciar configurações através de variáveis de ambiente.
- Organizar o projeto utilizando `APIRouter`.
- Aplicar injeção de dependências para recursos compartilhados.
- Utilizar hashing para armazenamento seguro de senhas.
- Implementar testes automatizados com `pytest` e `TestClient`.

**Resultado:**

O prompt ajudou a identificar erros frequentes e compreender práticas recomendadas para construir APIs mais seguras, organizadas e escaláveis.

**Dificuldade encontrada:**

Alguns conceitos relacionados à programação assíncrona e organização de projetos exigiram pesquisas complementares para melhor entendimento.

---

# 📘 Miniguia de Estudo

## O que é FastAPI?

FastAPI é um framework moderno para criação de APIs REST utilizando Python. Seu foco está em alta performance, validação automática de dados e produtividade no desenvolvimento.

### Principais Conceitos

- Rotas
- Métodos HTTP (GET, POST, PUT e DELETE)
- Path Parameters
- Query Parameters
- Pydantic
- Validação automática
- Injeção de dependências
- Programação assíncrona
- Documentação automática

### Documentação Automática

- `/docs` → Swagger UI
- `/redoc` → ReDoc

### Benefícios do FastAPI

- Alto desempenho.
- Código mais limpo através de Type Hints.
- Validação automática de dados.
- Documentação gerada automaticamente.
- Suporte nativo a operações assíncronas.

---

# 📚 Glossário

| Termo | Definição |
|---------|------------|
| API REST | Interface baseada em requisições HTTP |
| Endpoint | URL responsável por acessar um recurso |
| Pydantic | Biblioteca para validação de dados |
| OpenAPI | Padrão de documentação de APIs |
| Swagger | Interface gráfica para testes da API |
| Uvicorn | Servidor ASGI utilizado para executar aplicações FastAPI |
| Type Hints | Sistema de tipagem do Python |
| Async/Await | Recursos para programação assíncrona |

---

# 🚀 Prompts Reutilizáveis

- Explique o conceito de **[TEMA]** no FastAPI com exemplos práticos.
- Compare FastAPI com **[FRAMEWORK]** destacando vantagens e desvantagens.
- Crie um resumo estruturado sobre **[TEMA]**.
- Analise um código FastAPI e identifique melhorias.
- Gere exercícios práticos sobre FastAPI.
- Crie perguntas de entrevista sobre FastAPI com respostas comentadas.

---

# ✅ Conclusão

O NotebookLM facilitou o estudo do FastAPI ao permitir consultas rápidas, geração de resumos e revisão de conceitos importantes. A ferramenta auxiliou na organização do conhecimento, na compreensão de boas práticas e no entendimento de conceitos como validação de dados, documentação automática e programação assíncrona.
