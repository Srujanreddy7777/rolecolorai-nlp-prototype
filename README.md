# RoleColorAI – Resume RoleColor NLP Prototype

## Overview

This project demonstrates a lightweight NLP prototype that identifies behavioral **RoleColor traits** from resume text.

Instead of focusing on job titles, RoleColorAI focuses on how a person contributes to a team:

- **Builder** → Strategy, architecture, innovation
- **Enabler** → Collaboration, coordination
- **Thriver** → Performance under pressure
- **Supportee** → Reliability and stability

The system uses a simple keyword-based NLP approach to score the resume across RoleColors, normalize the scores, and rewrite the resume summary based on the dominant trait.

This prototype intentionally uses simple and explainable NLP logic aligned with the 2-hour prototype expectation.

---

## Approach

1. Define RoleColor keyword mapping
2. Preprocess resume text
3. Score keyword presence across RoleColors
4. Normalize the scores
5. Rewrite resume summary using a template based on the dominant RoleColor

---

## How to Run

Open the notebook `RoleColorAI_NLP_Prototype.ipynb` in Google Colab and run all cells sequentially.

---

## Assumptions

- Keyword presence reflects behavioral signals in resume language
- Simple NLP is sufficient for prototype demonstration
- Summary rewriting is template-based

---

## Sample Output

(See notebook output section)
