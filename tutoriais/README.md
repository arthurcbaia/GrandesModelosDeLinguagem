# Tutoriais

O arquivo ["RAG+LLMs.pdf"](./tutoriais/RAG+LLMs.pdf) é um tutorial detalhado que ensina como usar o modelo de linguagem GPT-3.5 com o framework LlamaIndex para criar um sistema de recuperação de informações. Ele aborda vários tópicos, incluindo:

- **Modelo de Embed**: Explica como os modelos de embed são usados para representar documentos e consultas de forma numérica que captura a semântica do texto. O modelo e5 é usado neste contexto, que é considerado o melhor modelo multilíngue de código aberto para a tarefa de recuperação de informação semântica[1].

- **Configuração**: Define um contexto de serviço global no LlamaIndex, que agrupa vários componentes usados em conjunto para realizar tarefas no LlamaIndex, incluindo o modelo de linguagem grande (LLM) e o modelo de embeddings[1].

- **Ingestão de Dados**: Descreve como os dados são ingeridos diretamente de um diretório para a criação da base de embeddings, que é então usada para criar um índice[1].

- **Configuração do Retriever**: Explica como o VectorIndexRetriever no LlamaIndex usa um LLM para definir automaticamente os parâmetros de consulta do armazenamento de vetores[1].

- **Escolha do tipo de resposta gerada pela LLM**: Descreve como a função get response synthesizer gera uma resposta a partir de um LLM, usando uma consulta do usuário e um conjunto de trechos de texto[1].

- **Motor de Busca e Criação de Resposta**: Explica como o RetrieverQueryEngine combina uma consulta em linguagem natural com a recuperação de uma resposta relevante[1].

- **Exemplos de Perguntas e Respostas**: Fornece exemplos de perguntas e respostas geradas pelo sistema, demonstrando sua eficácia na recuperação de informações relevantes[1].

Em resumo, o arquivo serve como um guia passo a passo para a criação de um sistema de recuperação de informações usando o modelo de linguagem GPT-3.5 e o framework LlamaIndex. Ele é destinado a ser usado em um repositório educacional para ajudar os usuários a entender como essas ferramentas podem ser usadas para criar sistemas de recuperação de informações eficazes.
