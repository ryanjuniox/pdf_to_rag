# PDF to RAG Project

Sistema de Retrieval Augmented Generation (RAG) para processamento e consulta de documentos PDF.

## Estrutura do Projeto

```
pdf_to_rag/
├── src/                     # Código fonte principal
│   ├── data_processing/     # Processamento de PDFs com Unstructured
│   ├── embeddings/          # Geração de embeddings com SentenceTransformer
│   ├── vector_store/        # Gerenciamento do ChromaDB
│   ├── retrieval/           # Sistema de recuperação de documentos
│   ├── llm/                 # Integração com LLMs
│   ├── evaluation/          # Métricas e avaliação do sistema 
│   └── streamlit_app/       # Interface web com Streamlit    
├── tests/                   # Testes unitários
├── notebooks/               # Jupyter notebooks para experimentação
├── config/                  # Arquivos de configuração
└── docs/                    # Documentação do projeto
```

## Features Planejadas

### Core Features
- [ ] Processamento de PDFs com particionamento inteligente
- [ ] Geração de embeddings com SentenceTransformer
- [ ] Armazenamento vetorial com ChromaDB
- [ ] Sistema de recuperação de documentos relevantes
- [ ] Integração com LLMs para geração de respostas

### Interface Features
- [ ] Interface web interativa com Streamlit
- [ ] Chat bot para consultas

### Evaluation Features
- [ ] Métricas de avaliação de qualidade
- [ ] Sistema de feedback
- [ ] Análise de performance

## Instalação

```bash
pip install -r requirements.txt
```

## Uso

### API
```bash
uvicorn src.api.main:app --reload
```

### Streamlit App
```bash
streamlit run src/streamlit_app/main.py
```

## Contribuição

Este projeto está em desenvolvimento ativo. Consulte o `docs/diary.md` para acompanhar o progresso.
