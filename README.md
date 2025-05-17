## 🌐 [English Version of README](README_EN.md)

# Sistema de Criação de Posts com Agentes Google Gemini

Este projeto demonstra um fluxo automatizado de criação de posts para Instagram utilizando múltiplos agentes de IA do Google Gemini. A cada etapa, um agente especializado executa uma tarefa: busca de notícias, planejamento de conteúdo, redação, revisão de qualidade e publicação automática.

## 🔨 Funcionalidades do Projeto

* **Agente 1 – Buscador de Notícias:** Pesquisa no Google as últimas novidades sobre um tópico.
* **Agente 2 – Planejador de Posts:** Define os pontos-chave e estrutura do conteúdo para o post.
* **Agente 3 – Redator de Post:** Gera o rascunho do texto para Instagram, com hashtags e tom apropriados.
* **Agente 4 – Revisor de Qualidade:** Verifica clareza, concisão e adequação do público-alvo.
* **Agente 5 – Publicador no Instagram:** Publica a imagem e legenda no Instagram Business via Graph API.

### Exemplo Visual do Projeto

> *Fluxo de agentes executando cada etapa em sequência, desde a consulta até a publicação no Instagram.*

## ✔️ Técnicas e Tecnologias Utilizadas

* **Python 3.11**
* **Google GenAI SDK** (`google-genai`)
* **Google ADK** (`google-adk`)
* **Facebook Business SDK** (`facebook-business`)
* **Jupyter Notebooks / Google Colab**
* **APIs REST (Graph API, Google Search)**

## 📁 Estrutura do Projeto

* **Imersão\_IA\_Alura\_+\_Google\_Gemini\_Aula\_04.ipynb**: Demonstração de uso básico do SDK Gemini.
* **Imersão\_IA\_Alura\_+*Google\_Gemini\_Aula\_05\_Agentes*(Final).ipynb**: Pipeline completo com 5 agentes.
* **LICENSE**: Termos de licença.
* **README.md**: Documentação do projeto (este arquivo).
* **README\_EN.md**: Versão em inglês da documentação.

## 🔗 Guia de Mergulho

* **Guia de Mergulho da Imersão IA:** [Acesse o Guia de Mergulho](https://grupoalura.notion.site/Imers-o-IA-Guia-de-Mergulho-1d2379bdd09b803982a5ee1abd89e0cb)

## 🎯 Recursos da Imersão IA – Aula 05

* **Google AI Studio:** [Acesse o Google AI Studio](https://ai.google.com/studio)
* **Obter API Key no Google AI Studio:** [Pegar API Key](https://ai.google.com/studio)
* **Google Colab:** [Acesse o Colab](https://colab.research.google.com)
* **Google Gemini:** [Experimente o Gemini](https://gemini.google.com)
* **Código base inicial da Aula 05:** \[Imersão\_IA\_Alura\_+\_Google\_Gemini\_Aula\_05\_Base.ipynb]
* **Código final da Aula 05:** \[Imersão\_IA\_Alura\_+*Google\_Gemini\_Aula\_05\_Agentes*(Final).ipynb]

## 🎓 Instrutores

* **Fabricio Carraro**, Program Manager
* **Luciano Martins**, Developer Advocate, Google IA
* **Valquíria Alencar**, Instrutora de Data Science

## 📚 Aulas da Imersão IA

* 🎥 **Masterclass:** Como a IA Aprendeu a Falar
* 🎬 **Aula 01:** O que uma IA de última geração pode fazer por você?
* 🎬 **Aula 02:** Como conversar com a IA e fazer ela trabalhar pra você
* 🎬 **Aula 03:** IA no seu dia a dia: do Google Calendar ao Drive com Gemini
* 🎬 **Aula 04:** Criando seu primeiro chatbot com IA generativa
* 🎬 **Aula 05:** Construindo agentes que resolvem tarefas por você

## 🛠️ Abrir e rodar o projeto

Para iniciar o projeto localmente, siga os passos abaixo:

1. **Clone o Repositório**:

   ```bash
   git clone <URL_DO_REPOSITORIO>
   cd <NOME_DO_PROJETO>
   ```

2. **Configure as credenciais**:

   * Defina a variável `GOOGLE_API_KEY` com sua chave de API do Google Gemini.
   * Defina `IG_ACCOUNT_ID` e `IG_ACCESS_TOKEN` para publicação no Instagram Business.

3. **Instale as dependências**:

   ```bash
   pip install -r requirements.txt
   ```

4. **Execute os notebooks**:

   * Abra os arquivos `.ipynb` no Google Colab ou em seu ambiente Jupyter.
   * Siga as instruções em cada célula na ordem.
s
## 🌐 Deploy

Este fluxo pode ser implantado em um servidor ou serviço de automação:

1. Configure um agendador (cron, Airflow) para executar periodicamente o notebook ou script Python.
2. Garanta que as variáveis de ambiente estejam disponíveis no ambiente de execução.
3. Monitore logs e resultados de publicação.

---

*Curso desenvolvido por Alura + Google Gemini*
