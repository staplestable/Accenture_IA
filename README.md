# FCI - ChatBot
FCI ChatBot é um assistente virtual para todos que tem interesse nas informações gerais e específicas de cursos da FCI Mackenzie. 
Projeto feito durante o hackathon de IA da Accenture. 

**Update (05/10/2023):** O projeto foi colocado em 1º lugar.

Para continuarmos é preciso ter todas as dependências instaladas na máquina:
```
pip install --upgrade openai
pip install langchain
pip install PyPDF2
pip install tiktoken
pip install faiss-cpu
pip install streamlit
```
### Especifique sua API_KEY
Dentro da pasta api-keys, altere o arquivo openai.json especificando sua API_KEY para que o bot consiga acessar a API da OpenAI:

```
{
	"openai":[
		{
			"api_key": "insira aqui"
		}

	]
}
```

### Executando a aplicação
Para executar a aplicação, certifique-se que todas as dependências estão instaladas em sua máquina e que a API_KEY foi especificada no arquivo JSON, então use o comando:

```
streamlit run AccentureUI.py
```

