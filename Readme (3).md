# 🤖 Chatbot de Atendimento Automatizado
**Protótipo de classificação de intenções usando TensorFlow e NLTK**  

<div align="center">
  <img src="https://img.shields.io/badge/Python-3.8%2B-blue?logo=python" alt="Python">
  <img src="https://img.shields.io/badge/TensorFlow-2.10-orange?logo=tensorflow" alt="TensorFlow">
  <img src="https://img.shields.io/badge/NLTK-3.7-lightgrey?logo=nltk" alt="NLTK">
</div>

---

## 📝 **Descrição**  
Chatbot desenvolvido como parte de um desafio técnico. O sistema classifica intenções do usuário (como solicitações de troca, garantia e status de pedidos) usando redes neurais e processamento de linguagem natural (NLP).  

**Objetivo**: Demonstrar a aplicação de IA para otimizar atendimentos recorrentes em cenários operacionais e exercitar ferramentas adiquiridas ao longo dos cursos da DeepLearning.AI.  

---

## 🛠️ **Funcionalidades**  
- ✅ **Pré-processamento de texto**: Tokenização e lematização com NLTK.  
- ✅ **Modelo de classificação**: Rede neural com TensorFlow (2 camadas densas + dropout).  
- ✅ **Respostas automáticas**: Mapeamento de intenções para respostas pré-definidas.  
- ✅ **Exemplo de uso**:  
  ```python
  Input: "Quero trocar meu produto com defeito"
  Output: "Claro! Por favor, envie o número do seu pedido para prosseguirmos com a troca."
