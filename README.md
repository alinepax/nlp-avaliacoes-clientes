# Análise de Sentimentos com NLP 🧠

Este projeto utiliza técnicas de Processamento de Linguagem Natural (NLP) para analisar sentimentos em avaliações de usuários. O modelo principal aplicado foi a Regressão Logística com vetorização TF-IDF.

## 🔍 Objetivo
Classificar avaliações como **positivas** ou **negativas** com base no conteúdo textual.

## 📁 Estrutura
- `Reviews_NLP.ipynb`: Notebook com todo o processo de análise e modelagem
- `data/`: Pasta com os dados utilizados

## 📊 Fonte dos Dados
Os dados utilizados foram retirados do conjunto [Brazilian E-Commerce Public Dataset by Olist](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce), disponível no Kaggle.  
O dataset inclui informações sobre pedidos, produtos, entregas e avaliações de clientes.

## ⚙️ Técnicas Utilizadas
- Pré-processamento de texto (remoção de stopwords, lematização).
- Vetorização com **TF-IDF**.
- Modelo de **Regressão Logística**.
- Avaliação com **acurácia**, **matriz de confusão** e **classification report**.

## 🧠 Insight Final
O modelo atingiu uma acurácia de aproximadamente **89%**, mostrando ótimo desempenho na identificação de sentimentos positivos. Há oportunidades de melhoria para equilibrar a detecção de avaliações negativas, o que pode ser alcançado com técnicas de balanceamento de classes ou modelos mais avançados como BERT.

---

## 📄 Licença

Este projeto está licenciado sob a [MIT License](LICENSE).

---

## 👩‍💻 Sobre a Autora

Desenvolvido por **[Aline Paz](https://github.com/alinepax)**  
📧 Email: aline.santospaz@gmail.com  
🎯 Este projeto faz parte do meu portfólio como profissional em transição para a área de Dados e Tecnologia.

---

⭐ Se você gostou, deixe uma estrela no repositório!
