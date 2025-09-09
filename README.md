# Imers-o-Dev-Agentes-de-IA-Google
Meu repo de estudos sobre a Imersão Dev Agentes de IA Google

# Agentes de IA
Um agente é um recurso, para fazer uma atividade específica. 
Por ex, numa automação o agente vai estar conectado com uma inteligência. 

O agente vai ter a capacidade de interpretar um comando do usuário, e apartir disso vai ter modelos, executar uma tarefa e dar uma saída pro usuário.

O agente executa de forma autonoma. 
Pode ter um orquestrador de agentes por trás. 

# Classificação de intenções com IA
Aula 1

COLLAB: https://colab.research.google.com/drive/123afJWX6sZzhLnMIU4Ru42KjuSryB0xd?usp=sharing

# Projeto

!pip install -q --upgrade langchain langchain-google-genai google-generativeai
Libs: 
langchain
langchain-google-genai (do proprio google)
google-generativeai (sdk do google)

# Ferramentas
Google collab (python)
Google AI Studio (vamos conectar a ele via api key)


# Modelo que vamos usar
Modelos pra chat 
2.0
2.5

temperatura menor do modelo
pra coisas muito especificas

temperatura maior do modelo
para coisas mais criativas


# Começo do código
from google.colab import userdata
from langchain_google_genai import ChatGoogleGenerativeAI (modelos pra chat)

GOOGLE_API_KEY = userdata.get('GEMINI_API_KEY')

aqui neste trecho estamos conectando com a API Key e setando o modelo de chat

