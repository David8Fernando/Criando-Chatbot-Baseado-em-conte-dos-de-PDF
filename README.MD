# 🧠 Otimizando Modelos de Linguagem para Aplicações Generativas de IA com Azure AI Foundry

Este repositório é fruto do desafio prático da DIO com foco em **IA Generativa**, **Azure AI Foundry** e **construção de um chatbot baseado em PDFs**. Aqui você encontrará uma aplicação completa que permite fazer perguntas com base no conteúdo de documentos PDF, utilizando conceitos como **RAG (Retrieval Augmented Generation)**, **engenharia de prompt** e **fine-tuning**.

---

## 📌 Visão Geral do Projeto

Neste projeto, você irá:

✅ Explorar modelos do catálogo do Azure AI Foundry  
✅ Aprender a otimizá-los com **engenharia de prompt**  
✅ Aplicar técnicas como **RAG** para melhorar as respostas com base em dados reais  
✅ Realizar **fine-tuning** dos modelos para um domínio específico  
✅ Avaliar o desempenho dos modelos diretamente no Azure AI Foundry  
✅ Criar um **chatbot interativo com base no conteúdo de arquivos PDF**

---

## 📚 Cenário

Imagine que você é um estudante, prestes a escrever seu TCC. Você possui uma série de artigos científicos em PDF e precisa extrair informações e cruzar ideias de maneira eficiente. A solução? Criar um **chatbot inteligente que interpreta os PDFs e responde com base em seu conteúdo**

---

## 🎯 Objetivos

- [x] Carregar arquivos PDF com informações importantes  
- [x] Indexar o conteúdo com busca vetorial e embeddings  
- [x] Usar IA para responder perguntas contextuais baseadas nos documentos  
- [x] Criar um chat interativo funcional e customizável

---

## 🛠️ Tecnologias Utilizadas

- **Azure AI Foundry**

---

## 📂 Estrutura do Projeto

Selecione alguns artigos em pdf para análise. Escolhi artigos relacionado à Business Intelligence

--- 
## ☁️ Criação do grupo de recurso e recurso

Em Azure vamos criar um grupo de recurso e posteriormente criar o recurso **Azure AI Foundry**


O **Azure AI Foundry** é uma plataforma para desenvolvimento de IA no Microsoft Azure. Embora você possa provisionar recursos individuais dos serviços de IA do Azure e criar aplicativos que os consomem sem ele, a organização do projeto, o gerenciamento de recursos e os recursos de desenvolvimento de IA do Azure AI Foundry torna a maneira recomendada de criar todas as soluções menos simples.

O Azure AI Foundry fornece o portal do Azure AI Foundry, uma interface visual baseada na Web para trabalhar com projetos de IA. Ele também fornece o SDK do Azure AI Foundry, que você pode usar para criar soluções de IA programaticamente.

![azure](https://github.com/David8Fernando/Criando-Chatbot-Baseado-em-conte-dos-de-PDF/blob/main/img/img1.png)


Aguarde a criação do recurso

![Criação do Azure AI Foundry](https://github.com/David8Fernando/Criando-Chatbot-Baseado-em-conte-dos-de-PDF/blob/main/img/img2.png)


Assim que estiver disponibilizado o recurso clique Launch Azure AI Foundry e crie seu projeto

![Iniciar Azure AI Foundry](https://github.com/David8Fernando/Criando-Chatbot-Baseado-em-conte-dos-de-PDF/blob/main/img/img3.png)

Implante um modelo básico em **Modelos + pontos de extremidade**


![Modelo básico](https://github.com/David8Fernando/Criando-Chatbot-Baseado-em-conte-dos-de-PDF/blob/main/img/img4.png)

Selecione o modelo da OpenAI **gpt-4o** 

![Modelo básico](https://github.com/David8Fernando/Criando-Chatbot-Baseado-em-conte-dos-de-PDF/blob/main/img/img5.png)