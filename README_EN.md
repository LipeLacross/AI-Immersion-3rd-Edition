## 🌐 [Versão em Português do README](README.md)

# Instagram Post Creation System with Google Gemini Agents

This project demonstrates an automated pipeline for crafting Instagram posts using multiple Google Gemini AI agents. At each step, a specialized agent performs a task: news retrieval, content planning, drafting, quality review, and automatic publication.

## 🔨 Project Features

* **Agent 1 – News Fetcher:** Uses Google Search to retrieve the latest news on a given topic.
* **Agent 2 – Post Planner:** Defines key points and structures the content outline.
* **Agent 3 – Post Writer:** Generates an Instagram-ready draft, including hashtags and an appropriate tone.
* **Agent 4 – Quality Reviewer:** Checks clarity, conciseness, and audience fit.
* **Agent 5 – Instagram Publisher:** Publishes the image and caption to Instagram Business via the Graph API.

### Visual Example of the Workflow

> *A sequence of AI agents performing each stage, from initial research to final Instagram publication.*

## ✔️ Technologies and Tools Used

* **Python 3.11**
* **Google GenAI SDK** (`google-genai`)
* **Google ADK** (`google-adk`)
* **Facebook Business SDK** (`facebook-business`)
* **Jupyter Notebooks / Google Colab**
* **REST APIs (Graph API, Google Search)**

## 📁 Project Structure

* **Imersão\_IA\_Alura\_+\_Google\_Gemini\_Aula\_04.ipynb**: Basic usage of the Gemini SDK.
* **Imersão\_IA\_Alura\_+*Google\_Gemini\_Aula\_05\_Agentes*(Final).ipynb**: Full pipeline with 5 agents.
* **LICENSE**: License terms.
* **README.md**: Portuguese documentation (this file).
* **README\_EN.md**: English documentation (this file).

## 🔗 Deep Dive Guide

* **Imersão IA Deep Dive Guide:** [Access the Deep Dive Guide](https://grupoalura.notion.site/Imers-o-IA-Guia-de-Mergulho-1d2379bdd09b803982a5ee1abd89e0cb)

## 🎯 Immersion IA Resources

* **Google AI Studio:** [Visit Google AI Studio](https://ai.google.com/studio)
* **Get API Key in Google AI Studio:** [Obtain API Key](https://ai.google.com/studio)
* **Google Colab:** [Open Colab](https://colab.research.google.com)
* **Google Gemini:** [Try Gemini](https://gemini.google.com)

## 🎓 Instructors

* **Fabricio Carraro**, Program Manager
* **Luciano Martins**, Developer Advocate, Google AI
* **Valquíria Alencar**, Data Science Instructor

## 📚 Immersion IA Sessions

* 🎥 **Masterclass:** How AI Learned to Speak
* 🎬 **Session 01:** What Can a State-of-the-Art AI Do for You?
* 🎬 **Session 02:** How to Talk to AI and Make It Work for You
* 🎬 **Session 03:** AI in Your Daily Life: From Google Calendar to Drive with Gemini
* 🎬 **Session 04:** Building Your First Generative Chatbot
* 🎬 **Session 05:** Constructing Agents That Solve Tasks for You

## 🛠️ Getting Started

To run the project locally, follow these steps:

1. **Clone the repository:**

   ```bash
   git clone <REPOSITORY_URL>
   cd <PROJECT_NAME>
   ```

2. **Set up credentials:**

   * Export `GOOGLE_API_KEY` with your Google Gemini API key.
   * Export `IG_ACCOUNT_ID` and `IG_ACCESS_TOKEN` for Instagram Business publishing.

3. **Install dependencies:**

   ```bash
   pip install -r requirements.txt
   ```

4. **Run the notebooks:**

   * Open the `.ipynb` files in Google Colab or Jupyter.
   * Execute cells in order.

## 🌐 Deployment

This workflow can be deployed on a server or automation platform:

1. Schedule periodic execution (cron, Airflow).
2. Ensure environment variables are available.
3. Monitor logs and publication results.

---

*Course developed by Alura + Google Gemini*
