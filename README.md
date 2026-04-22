# 📊 TP2 — Prévision financière avec Transformers

## 📌 Description

Ce projet explore l’utilisation des modèles Transformer pour analyser des textes financiers.  
L’objectif est de classifier automatiquement le sentiment de phrases financières en trois catégories :  
**positif**, **négatif** ou **neutre**.

Pour cela, nous utilisons **FinBERT**, un modèle spécialisé en finance basé sur l’architecture BERT.

---

## 🎯 Objectifs

- Comprendre l’application des Transformers en NLP financier  
- Utiliser un modèle pré-entraîné (FinBERT)  
- Prédire le sentiment de textes financiers réels  

---

## 📊 Dataset

Nous utilisons le dataset **Financial PhraseBank**, composé de **4837 phrases financières** annotées par des experts :

- ✅ Positif  
- ❌ Négatif  
- ⚪ Neutre  

---


### 📁 Description des dossiers

- **notebooks/** : démonstrations et tests (FinBERT, attention, etc.)
- **data/** : dataset utilisé pour l’analyse
- **src/** : scripts Python (préprocessing, modèle)
- **README.md** : description du projet

## 🤖 Modèle utilisé

**FinBERT** — https://huggingface.co/ProsusAI/finbert

- Architecture : Transformer (BERT — encodeur)  
- Spécialisé en finance  
- Tâche : classification de sentiment  

👉 Exemple :

```text
Input : "The company reported strong earnings this quarter"
Output : Positive
````

---

## 🚀 Utilisation

### Installation

```bash
pip install transformers torch
````

## 🔗 Références

- Vaswani, A. et al. (2017). *Attention Is All You Need*.  
- Devlin, J. et al. (2018). *BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding*.  
- Araci, D. (2019). *FinBERT: Financial Sentiment Analysis with BERT*.  

---

## 👥 Auteurs

