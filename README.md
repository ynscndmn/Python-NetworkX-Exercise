# 🕸️ Network Analysis & Knowledge Graphs with NetworkX

This project explores the power of graph theory using the `NetworkX` library in Python. It covers social network analysis, shortest path algorithms with reliability factors, and the implementation of a cinematic Knowledge Graph.

## 🔗 Notebook Link
You can access the original Google Colab notebook here:
[[Google Colab - NetworkX Project](](https://colab.research.google.com/drive/1MgsCVFPgLAOT4fHMs5HFPEvT4QtdcjVW)

---

## 🇺🇸 [ENGLISH]

###  Project Overview
This repository contains a comprehensive Python implementation of graph-based data structures. The project is divided into three main sections:
1. **Social Network Analysis:** Modeling relationships between professionals and analyzing the impact of "hub" nodes.
2. **Reliability-Based Pathfinding:** An advanced Dijkstra implementation that calculates the "Expected Time" by factoring in the probability of a person answering their phone.
3. **Knowledge Graph (KG):** A structured semantic network of directors, actors, and movies to demonstrate how modern AI understands context.

###  Key Features & Algorithms
* **Dijkstra's Algorithm:** Used for finding the shortest path between individuals.
* **Network Robustness:** Analyzes how the removal of a central node (like "Jack") increases the distance between other nodes.
* **BFS & DFS Traversal:** Demonstrates layer-by-layer and branch-deep search strategies.
* **Knowledge Graph Implementation:** Uses triples (Subject-Predicate-Object) to model complex relationships in the film industry.

###  Technical Details
* **Language:** Python
* **Libraries:** `networkx`, `matplotlib`, `numpy`
* **Formula for Reliability:** $$\text{Expected Time} = \frac{\text{Original Time}}{\text{Probability of Target Answering}}$$

---

## 🇹🇷 [TURKISH]

###  Proje Özeti
Bu çalışma, Python'daki `NetworkX` kütüphanesini kullanarak çizge (graph) teorisinin gücünü incelemektedir. Proje üç ana bölümden oluşmaktadır:
1. **Sosyal Ağ Analizi:** Profesyoneller arasındaki ilişkilerin modellenmesi ve "merkezi" düğümlerin ağ üzerindeki etkisinin analizi.
2. **Güvenilirlik Tabanlı Yol Bulma:** Bir kişinin telefona cevap verme olasılığını hesaba katarak "Beklenen Süre"yi hesaplayan gelişmiş bir Dijkstra uygulaması.
3. **Bilgi Grafiği (KG):** Modern yapay zekanın bağlamı nasıl anladığını göstermek için yönetmenler, oyuncular ve filmlerden oluşan yapılandırılmış anlamsal ağ.

###  Öne Çıkan Özellikler ve Algoritmalar
* **Dijkstra Algoritması:** Kişiler arasındaki en kısa yolu bulmak için kullanılmıştır.
* **Ağ Dayanıklılığı:** "Jack" gibi merkezi bir düğümün kaldırılmasının diğer düğümler arasındaki mesafeyi nasıl artırdığını analiz eder.
* **BFS ve DFS Gezinme:** Katman katman ve dal derinliğine göre arama stratejilerini gösterir.
* **Bilgi Grafiği Uygulaması:** Film endüstrisindeki karmaşık ilişkileri modellemek için üçlüleri (Özne-Yüklem-Nesne) kullanır.

###  Teknik Detaylar
* **Dil:** Python
* **Kütüphaneler:** `networkx`, `matplotlib`, `numpy`
* **Güvenilirlik Formülü:**
  $$\text{Beklenen Süre} = \frac{\text{Orijinal Süre}}{\text{Hedefin Cevap Verme Olasılığı}}$$

---

