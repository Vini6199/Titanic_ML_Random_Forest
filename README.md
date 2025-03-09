# 🚢 Titanic Survival Prediction - Machine Learning com Random Forest

Este projeto utiliza **Random Forest** para prever a sobrevivência dos passageiros do Titanic com base em suas características. O modelo é avaliado utilizando **ROC AUC** e **AUC PR**, métricas importantes para avaliar classificadores, especialmente em cenários com desbalanceamento de classes.

---

## 📌 Objetivo

Criar um modelo de Machine Learning que consiga prever quais passageiros sobreviveram ao desastre do Titanic com base em variáveis como idade, sexo, valor pago e outras informações disponíveis no dataset.

---

## 🗂️ Dataset  

O dataset utilizado é uma versão do **Titanic - Machine Learning from Disaster** disponível no [Kaggle](https://www.kaggle.com/competitions/titanic). Ele contém informações sobre passageiros, incluindo:  

- **PassengerId**: Identificador único  
- **Survived**: (0 = Não sobreviveu, 1 = Sobreviveu)  
- **Pclass**: Classe da cabine (1ª, 2ª ou 3ª)  
- **Name**: Nome do passageiro  
- **Sex**: Gênero do passageiro  
- **Age**: Idade  
- **SibSp**: Número de irmãos/cônjuges a bordo  
- **Parch**: Número de pais/filhos a bordo  
- **Ticket**: Número do bilhete  
- **Fare**: Preço da passagem  
- **Cabin**: Número da cabine *(muitos valores ausentes)*  
- **Embarked**: Porto de embarque *(C = Cherbourg, Q = Queenstown, S = Southampton)*  
