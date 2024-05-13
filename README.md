# Sistema-de-busca-em-documentos
Criando um sistema para busca em documentos usando embeddings e a Gemini API
Criando um Sistema de Busca em Documentos usando Embeddings e a Gemini API
Este repositório contém um código para criar um sistema de busca em documentos usando embeddings de texto e a Gemini API. O sistema é capaz de encontrar o documento mais relevante com base em uma consulta de usuário.

Pré-requisitos
Antes de executar o código, é necessário ter as seguintes ferramentas instaladas:

Python 3
Pandas
Numpy
Google Generative AI
Você também precisará de uma chave de API válida da Google para acessar a Gemini API.

Instalação
Clone este repositório para sua máquina local.

Instale as dependências usando o pip:

Copy code
pip install pandas numpy google-generativeai
Configure sua chave de API da Google:

python
Copy code
import google.generativeai as genai
genai.configure(api_key="SUA_CHAVE_DE_API")
Como Usar
O código contido neste repositório consiste em várias etapas:

Definir os documentos que serão buscados.
Gerar embeddings para os documentos usando a função embed_fn.
Definir a função gerar_e_buscar_consulta para buscar o documento mais relevante com base na consulta do usuário.
Executar uma consulta de exemplo usando a função gerar_e_buscar_consulta.
Utilizar a Gemini API para reescrever o texto de forma mais descontraída.
Executando o Código
Para executar o código:

Certifique-se de que todas as dependências estejam instaladas.
Configure sua chave de API da Google.
Execute o script Python.
Licença
Este projeto está licenciado sob a Licença MIT - veja o arquivo LICENSE para mais detalhes.

Contribuindo
Contribuições são bem-vindas! Sinta-se à vontade para abrir problemas ou enviar solicitações de pull.
