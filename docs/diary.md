# Projeto de RAG com PDF

## DAY ONE (06 ago)

Inicialmente, gostaria de realizar um projeto de RAG com um pdf, em Python. Futuramente, irei decidir qual será sua conclusão, talvez apresentar insights e algum processo de evaluation ou um chat bot.

Inicialmente penso em utilizar as seguintes ferramentas/libs:
- Unstructured: Lib para o particionamento do PDF.
- SentenceTransformer: Para embeddings.
- ChromaDB: Para armazenamento dos vetores.
- LLM: Futuramente alguma LLM para resposta, evaluation ou algo correlacionado.

Penso que também posso criar uma API ou realizar alguma visualização on-line com Streamlit. 

## DAY TWO (07 ago)

Hoje tive uma dificuldade maior com alguns conflitos de dependência. Infelizmente, para esse tipo de problema o ideal é ir testando as versões. Creio que há formas melhores para versionamento, mas até que consegui desempenhar um bom papel.

Entreguei então os embeddings através do SentenceTransformer e o armazenamento dos vetores no ChromaDB. Isso tudo feito via um notebook, para facilitar a implementação futura. É como se fosse uma prova de conceito das funcionalidades e, em seguida, irei implementar as features. 