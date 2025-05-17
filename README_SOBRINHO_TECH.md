# Sobrinho Tech 🤖

Sobrinho Tech é um chatbot baseado em Inteligência Artificial, criado para ajudar pessoas a resolverem dúvidas de tecnologia do dia a dia de maneira simples e acessível. O projeto utiliza o modelo Gemini, da Google, via biblioteca `google-genai` no Google Colab, para entregar respostas claras, passo a passo, sem termos técnicos — perfeito para leigos, idosos ou qualquer pessoa que queira descomplicar o mundo digital!

## 🚀 Como funciona?

- O chatbot responde dúvidas sobre instalação de apps, configurações básicas, uso de aplicativos populares, dicas de segurança digital e muito mais.
- As respostas são sempre em linguagem fácil, didática, focada no público leigo.

## 🛠️ Como rodar

1. **Clone o repositório:**
    ```bash
    git clone https://github.com/seu-usuario/sobrinho-tech.git
    ```
2. **Abra o arquivo `chatbotsobrinhotech.py` no Google Colab** (ou suba no seu próprio Colab).

3. **Instale a dependência:**
    ```python
    !pip install google-genai
    ```

4. **Configure sua API KEY do Google Gemini:**
    - Gere uma API Key em: https://aistudio.google.com/app/apikey
    - No Colab, adicione sua chave nas variáveis de ambiente, usando:
      ```python
      from google.colab import userdata
      os.environ['GOOGLE_API_KEY'] = userdata.get('GOOGLE_API_KEY')
      ```
    - Ou substitua diretamente pelo valor da sua chave.

5. **Execute as células do notebook ou o script Python.**

## 💡 Exemplos de perguntas

- “Como baixar o WhatsApp?”
- “Como atualizar o sistema do celular?”
- “O que é Wi-Fi e como conectar?”
- “Como identificar golpes no WhatsApp?”

## 🔒 Segurança

O Sobrinho Tech não armazena dados pessoais. Todas as respostas são geradas em tempo real via API do Google Gemini.

## 📄 Licença

MIT License

---

*Feito com 💻 e ☕ por Fred.*
