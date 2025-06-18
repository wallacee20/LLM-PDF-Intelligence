# 📄 LLM-PDF-Intelligence
LLM PDF Intelligence é um pipeline inteligente construído em Python que transforma documentos PDF estáticos em insights acionáveis, combinando técnicas de Machine Learning com Modelos de Linguagem (LLMs) via API do Gemini. O projeto realiza extração, inferência, contextualização personalizada e geração de relatórios estruturados, facilitando a análise de dados não estruturados de forma automatizada e escalável.


Este projeto demonstra como transformar relatórios em PDF — que normalmente são estáticos e difíceis de explorar — em **fontes dinâmicas de insights**, utilizando **Machine Learning** e **Large Language Models (LLMs)** com a **API do Gemini 2.5 Pro**, diretamente em um **notebook Python**.

## 🚀 Objetivo

Extrair informações relevantes de documentos PDF e gerar análises automatizadas e contextualizadas, utilizando IA generativa. O foco está na análise econômica de textos longos, aplicando:
- Análise de Sentimentos
- Extração de Entidades (países, blocos econômicos)
- Sumarização e reescrita com personas específicas

---

## 🧠 Tecnologias e Ferramentas

- **Python 3.x**
- **Google Colab**
- **pdfminer.six** – Para extração de texto de PDFs
- **Gemini API (v2.5 Pro)** – Para inferência com LLMs
- **Google Generative AI SDK**
- **Pandas / JSON** – Para estruturação dos dados
- **ReportLab** – Para gerar um PDF final com os insights

---

## ⚙️ Pipeline de Processamento

1. **Extração de Texto**
   - Leitura e limpeza do conteúdo usando `pdfminer.six`.

2. **Pré-processamento**
   - Tratamento do texto, remoção de caracteres especiais e divisão em trechos para análise.

3. **Chamadas à API do Gemini**
   - Envio dos trechos para o modelo com prompts personalizados.
   - Uso de *personas* (ex: jornalista, economista) para adaptar a linguagem dos resumos.

4. **Análises Realizadas**
   - **Análise de Sentimentos**
   - **Extração de Entidades** (países, blocos econômicos)
   - **Sumarização e Reescrita Inteligente**

5. **Geração de Relatório Final**
   - Estruturação dos resultados em um novo PDF com os insights prontos para apresentação ou tomada de decisão.

---

## 📦 Estrutura do Projeto
