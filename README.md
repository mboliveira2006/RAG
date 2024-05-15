## Usando Modelos LLMs Localmente: Extraindo Informações de Documentos com RAG

**Introdução**

A técnica RAG (Retrieval Augmented Generation) permite extrair informações de documentos de forma eficiente, utilizando um modelo LLM local em vez de enviar seus dados para servidores de terceiros. Essa abordagem oferece diversos benefícios, como privacidade, segurança, eficiência e flexibilidade.

**Requisitos**

* Python 3.8 ou superior
* LangChain
* RAG
* Vector Data Base
* Ollama

**O que esse código faz?**

**1. Obter os dados**

Na pasta documento tem dois arquivos pdf usados como exemplo.

![image](https://github.com/mboliveira2006/RAG/assets/16489824/fadf2497-b810-4c1d-bbf3-9e7b6334f9c8)


**2. Pré-processamento do documento**

* Carrega o documento e divide em partes menores.

* Converte cada parte em um embedding e armazena no Vector Data Base.

**3. Extrair informações**

* Utiliza a técnica RAG para extrair informações do documento.
* Faz uma busca semântica no Vector Data Base para recuperar os trechos relevantes e envie-os ao modelo LLM para obter a resposta final.

**Recursos adicionais**

* Documentação do LangChain: https://api.python.langchain.com/
* Documentação do RAG: https://github.com/google/rag
* Documentação do Vector Data Base: https://vector-database.io/
* Documentação do Ollama: https://ollama.com/

**Exemplos de uso**

Este repositório pode ser utilizado para diversos casos de uso, como:

* Resumo automático de documentos
* Resposta a perguntas
* Extração de informações específicas
* Geração de texto

**Lei o artigo no linkedin**

[Usando modelos LLMs localmente](https://www.linkedin.com/pulse/usando-modelos-llms-localmente-marcelo-oliveira-xq33f/?trackingId=j7QPMF4lA0Qjs4gp2M9K8w%3D%3D)


**Contribuições**

Sinta-se à vontade para contribuir com este repositório enviando sugestões, correções ou novos recursos.
