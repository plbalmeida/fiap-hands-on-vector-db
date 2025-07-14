💻 Hands-on: Banco de dados vetorial

### 📚 Descrição

Este projeto demonstra como usar o banco de dados vetorial [ChromaDB](https://www.trychroma.com/) para armazenar e consultar embeddings gerados a partir de dados de títulos da Netflix. Inclui também visualizações e explicações sobre os conceitos de RAG (Retrieval-Augmented Generation).

### 📂 Estrutura do Repositório

```
├── README.md         # Este arquivo
├── figures/          # Imagens e esquemas explicativos
│   ├── *.excalidraw  # Arquivos editáveis
│   └── *.png         # Visualizações 
├── notebook.ipynb    # Jupyter Notebook com análise e uso do ChromaDB
└── requirements.txt  # Dependências do projeto
```

### ⚙️ Setup do Projeto

#### 1. Clone o repositório

```bash
git clone https://github.com/plbalmeida/fiap-hands-on-vector-db.git
```

#### 2. Crie e ative um ambiente virtual

No **Linux/MacOS**:

```bash
python -m venv venv
source venv/bin/activate
```

No **Windows**:

```bash
python -m venv venv
venv\\Scripts\\activate
```

#### 3. Instale as dependências

```bash
pip install -r requirements.txt
```

#### 4. Crie o .env

Na raíz do repo crie o arquivo `.env` com a chave OpenAI necessário para realização de embeddings e uso de LLM.

```.env
OPENAI_API_KEY=<SUA CHAVE DA OPENAI>
```

#### 5. Execute o notebook

Abra o Jupyter Notebook ou VS Code com o kernel do ambiente ativado e execute o `notebook.ipynb`.

```bash
jupyter notebook notebook.ipynb
```