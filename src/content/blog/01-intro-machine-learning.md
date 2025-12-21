---
title: 'Introdução ao Machine Learning'
description: 'Entendendo os fundamentos antes dos algoritmos'
pubDate: 'Dec 20 2025'
tags: ['ml-basics', 'teoria']
---

Quando falamos de Aprendizado de Máquina, se referimos a um modelo de inteligência artificial na qual aprende de forma autônama. E esse aprendizado pode ocorrer de diferentes formas. Os dois tipos principais são:

## 1. Aprendizado Supervisionado

É um treinamento no qual entregamos uma série de entradas (features, ou 'x') que já possuem consigo suas respostas (labels, ou 'y'). Ou seja, entregamos o "gabarito" para que o modelo saiba prever a resposta mais adequada para uma entrada na qual não se sabe a resposta ainda (ou o modelo não deve saber, já que ele tem que prever).

> Damos a ele a pergunta (x) e a resposta (y). O objetivo do modelo é aprender a mapear um para o outro.

**Exemplos**:
* **Regressão**: Quando queremos prever um número. (Ex.: Preço de casas, Temperatura)
* **Classificação**: Quando queremos prever uma categoria. (Ex.: "É um Cachorro ou um Gato?", "É um tumor ou não?")

## 2. Aprendizado Não-Supervisionado

Diferente do anterior, aqui não entregamos o gabarito. Nesse caso, o modelo irá receber os dados puros e irá precisar agrupar os dados conforme a similaridade entre eles sem saber o significado originalmente.

**Exemplo:**
* 1. **Clusterização**: O modelo analisa muitos dados (tipo mil) e separa em grupos (três, por exemplo), onde cada grupo possui padrões distintos. Isso é muito útil!
