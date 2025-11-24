# VR-Mart: Virtual Reality Shopping System

A virtual reality–based shopping prototype built using Unity, designed to simulate the realistic in-store experience of browsing and interacting with products inside a VR mall. This project was developed as a final-year engineering project and extended into a published research paper.

---

## 🎯 Overview

- Built a fully functional VR shopping environment using **Unity & C#**.
- Designed around the idea of replicating physical shopping experiences during COVID-19 lockdowns.
- Includes the **design and prototype implementation** of a content-based recommender system using Python.
- Presented at the **International Conference on Communication and Intelligent Systems (ICCIS)** and published as a research paper.

---

## 🧪 Research Publication

This project resulted in the following published paper:

**“Virtual Reality Shopping System” – Published at ICCIS 2021**
📄 Research Paper: https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4096403
PDF available inside the `docs/` folder.

The research covers:
- Digital transformation of retail through VR  
- Human–computer interaction in immersive environments  
- Recommendation techniques for personalized product discovery  
- System architecture & evaluation  

---

## 🧱 Architecture

### 🔹 1. VR Application (Unity & C#)  
Implements the 3D mall environment:

- Multiple aisles and product categories  
- Product detail panels  
- Interaction events (pickup, inspect, browse)  
- Teleportation & UI navigation  

### 🔹 2. Recommender System Prototype (Python)  
A lightweight **content-based filtering engine**, implemented as a prototype.

- Uses product metadata (category, brand, price range, attributes) and user interaction history to build a user profile.  
- Content-based filtering: recommend items similar to those viewed/liked by the user using feature vectors and similarity measures (e.g. cosine similarity).  
- Intended integration: Unity app sends selected product ID / user history → recommender returns a ranked list of similar products.

---

## 🛠 Tech Stack

- **VR & Frontend:** Unity, C#, Node.js 
- **ML Prototype:** Python, Pandas, NumPy, Scikit-Learn  
- **Version Control:** Git, GitHub  
- **Documentation:** Research paper, reports, presentations (in `docs/`)  

---
