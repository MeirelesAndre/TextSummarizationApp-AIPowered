# 📜 Resumo de Texto com LangChain e Claude 3 Opus

Este projeto utiliza a biblioteca [LangChain](https://python.langchain.com/) e a API da [Anthropic](https://www.anthropic.com/) para realizar a **sumarização automática de textos**.  

## 🛠 Tecnologias Utilizadas

- [LangChain](https://python.langchain.com/) - Framework para aplicações com modelos de linguagem  
- [Anthropic Claude 3 Opus](https://www.anthropic.com/index/claude-3) - Modelo de IA para processamento de texto  
- [Python dotenv](https://pypi.org/project/python-dotenv/) - Carregamento de variáveis de ambiente  
- [OS](https://docs.python.org/3/library/os.html) - Manipulação do sistema operacional  

## 🚀 Funcionalidades  

✔️ Fatiamento de um texto longo em partes menores  
✔️ Criação de documentos a partir do texto dividido  
✔️ Sumarização do conteúdo utilizando um modelo de IA avançado  

## 📦 Instalação  

1. Clone este repositório:  
   ```bash
   git clone https://github.com/seu-usuario/nome-do-repositorio.git
   cd nome-do-repositorio
   ```

2. Crie um ambiente virtual e ative-o:  
   ```bash
   python -m venv venv
   source venv/bin/activate  # Linux/Mac
   venv\Scripts\activate  # Windows
   ```

3. Instale as dependências:  
   ```bash
   pip install -r requirements.txt
   ```

4. Crie um arquivo `.env` e adicione sua chave da API da Anthropic:  
   ```
   ANTHROPIC_API_KEY=SUA_CHAVE_AQUI
   ```

## 📝 Como Usar  

1. Execute o script Python:  
   ```bash
   python main.py
   ```

2. O resumo do texto será exibido no console.  

## 📌 Estrutura do Código  

- **Importação das bibliotecas** necessárias  
- **Carregamento da chave da API** via `.env`  
- **Criação do modelo de IA** usando `ChatAnthropic`  
- **Fatiamento do texto** com `CharacterTextSplitter`  
- **Criação de documentos** com `Document`  
- **Execução da sumarização** com `load_summarize_chain`  

## 🎯 Exemplo de Entrada  

```text
São Jorge foi um soldado romano venerado como mártir cristão...
```

## 📋 Exemplo de Saída  

```text
São Jorge foi um soldado romano e mártir cristão, conhecido por sua devoção e coragem...
```

## 📜 Licença  

Este projeto é de código aberto e está licenciado sob os termos da [MIT License](LICENSE).  

---

Caso tenha alguma dúvida ou sugestão, fique à vontade para abrir uma issue! 🚀