# Agente Inteligente com Outputs Estruturados e Tool Calling

Este projeto implementa um **agente inteligente para um chatbot**, utilizando a **LangChain** e a LLM da **OpenAI**. O agente faz uso de **tool calling** para acessar chamadas de funções externas, sendo sua principal funcionalidade a **geração de embeddings** e a busca em documentos para encontrar informações relevantes em resposta às perguntas do usuário.


## Tecnologias Utilizadas
- Linguagem: Python 3.13
- Framework: LangChain
- Modelo de LLM: OpenAI
- Banco Vetorial: ChromaDB
- Modelo de Embeddings: Ollama mxbai-embed-large


## Instalação

1. Clone o repositório:

```bash
git clone https://github.com/giopelati/Structured_outputs.git
cd Structured_outputs
```

2. Crie um ambiente virtual e instale as dependências:

```bash
python3.13 -m venv venv
source venv/bin/activate  # No Windows use: venv\Scripts\activate
pip install -r requirements.txt
```

3. Execute o agente:

```bash
jupyter notebook Agents.ipynb
```

## Licença

[MIT](https://choosealicense.com/licenses/mit/)


## Informações de Copyright
A execução deste projeto deve ser autorizada. Ele não é público e seu uso é restrito conforme definido pelos proprietários.
