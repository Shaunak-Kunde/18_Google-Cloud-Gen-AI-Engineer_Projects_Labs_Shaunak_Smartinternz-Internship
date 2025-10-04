# Smartinternz Internship - Google Cloud Gen AI Engineer

This repository contains all the advanced projects and guided labs that I implemented in the Google Cloud Skills Boost platform as part of my Google Cloud Gen AI Virtual Internship Program with Smartinternz. It covers my progress through both the introductory and advanced developer learning paths.

---

## ✅ Completed Learning Paths

* **Beginner: Introduction to Generative AI**
* **Advanced: Generative AI for Developers**

---
### 🎓 Learning Path

1.  **Introduction to Generative AI**
    <img width="272" height="290" alt="image" src="https://github.com/user-attachments/assets/34c4a529-9b19-43cd-a2d7-a5b77f094691" />

---
2.  **Introduction to Large Language Models**
    <img width="275" height="283" alt="image" src="https://github.com/user-attachments/assets/7ff0849e-6caa-4882-a411-7e26ac391fab" />


---
3.  **Introduction to Responsible AI**
    <img width="277" height="287" alt="image" src="https://github.com/user-attachments/assets/5bf82af0-e0e4-4242-b394-02c652e43ad3" />


---
4.  **Prompt Design in Vertex AI** (Skill Badge)
    <img width="361" height="290" alt="image" src="https://github.com/user-attachments/assets/62773649-79e9-49c9-b567-99f0ec64d46b" />


---
5.  **Responsible AI: Applying AI Principles with Google Cloud**
    <img width="272" height="282" alt="image" src="https://github.com/user-attachments/assets/39233916-17e6-4486-a089-df4429d95cb7" />

---

### Advanced: Generative AI for Developers

1.  **Introduction to Image Generation**
    <img width="273" height="286" alt="image" src="https://github.com/user-attachments/assets/1ae30884-6056-4544-b8d4-8745d40176f0" />


---
2.  **Attention Mechanism**
    <img width="272" height="285" alt="image" src="https://github.com/user-attachments/assets/4402e1b5-4cda-4317-88a3-2f4cdc48a6cb" />


---
3.  **Encoder-Decoder Architecture**
    <img width="270" height="284" alt="image" src="https://github.com/user-attachments/assets/aa93c195-14e6-4fc7-8a1f-420c3b66293c" />


---
4.  **Transformer Models and BERT Model**
    <img width="273" height="284" alt="image" src="https://github.com/user-attachments/assets/526f4cdb-79d2-45fb-9ee3-09e5a38f891b" />


---
5.  **Create Image Captioning Models**
    <img width="271" height="286" alt="image" src="https://github.com/user-attachments/assets/089e7f70-3b14-4452-a1f9-5b576d029f65" />


---
6.  **Introduction to Vertex AI Studio**
    <img width="274" height="284" alt="image" src="https://github.com/user-attachments/assets/f7edd16f-1ce8-470a-a487-e336a7be549b" />


---
7.  **Vector Search and Embeddings** (Skill Badge)
    <img width="271" height="287" alt="image" src="https://github.com/user-attachments/assets/88ee0803-fa85-4b96-9073-3349a3301c4b" />


---
8.  **Inspect Rich Documents with Gemini Multimodality and Multimodal RAG** (Skill Badge)
    <img width="365" height="290" alt="image" src="https://github.com/user-attachments/assets/6686bb41-2d13-4acc-944e-98fa2a615c7e" />

---
9.  **Responsible AI for Developers: Fairness & Bias**\n
    <img width="272" height="285" alt="image" src="https://github.com/user-attachments/assets/1c0f45c5-4481-4945-a4ad-13bafd5d4223" />


---
10. **Responsible AI for Developers: Interpretability & Transparency**
    <img width="272" height="281" alt="image" src="https://github.com/user-attachments/assets/4c62e240-6512-4785-a3c2-a88522f4205f" />

---
11. **Responsible AI for Developers: Privacy & Safety**
    <img width="273" height="281" alt="image" src="https://github.com/user-attachments/assets/e1925f2f-1cf3-493d-91be-4e5094406f6d" />

---
12. **Machine Learning Operations (MLOps) for Generative AI**
    <img width="277" height="282" alt="image" src="https://github.com/user-attachments/assets/a808babf-285b-47e2-b226-245c321f3027" />


---

## 🔬 Lab Notebooks & Summaries

Here is a breakdown of each lab notebook included in this repository, corresponding to the activities in the learning paths.

### `gemini_safety_ratings`

* **Summary:** This notebook from the "Privacy & Safety" module provides a hands-on approach to implementing crucial safety controls for generative AI applications. It demonstrates how to configure and adjust safety thresholds for various harm categories (like hate speech and harassment) and then test how the Gemini model's responses and safety ratings change, ensuring that applications built on the platform are both safe and responsible.

### `hybrid-search-v1.0.0`

* **Summary:** From the "Vector Search and Embeddings" lab, this notebook tackles the limitations of traditional search by implementing a more powerful hybrid system. It leverages vector embeddings for semantic understanding, combining the precision of keyword matching with the contextual richness of semantic search. This approach delivers superior, more relevant results for complex user queries that simple keyword systems would miss.

### `image-analysis`

* **Summary:** This notebook is a practical exercise in using the multimodal capabilities of Gemini for advanced image analysis. It shows how to provide an image to the model and then ask detailed questions about it using natural language prompts. This covers tasks like object identification, scene description, and extracting specific text or data from a picture, showcasing the powerful visual understanding capabilities of modern generative models.

### `inspect_rich_documents_w_gemini_multimodality_and_multimodal_rag-v1.0.0`

* **Summary:** As the core notebook for the "Inspect Rich Documents" skill badge, this lab tackles complex, mixed-media files. It demonstrates how to use Gemini's multimodal capabilities to parse and understand documents containing text, tables, and images. It then implements a Retrieval-Augmented Generation (RAG) system to "ground" the model's answers in the document's content, reducing hallucinations and enabling a powerful question-and-answer interface.

### `intro_genai_sdk`

* **Summary:** This notebook serves as the essential entry point for developers working with Google's generative models programmatically. It provides a step-by-step guide through the initial setup, including authenticating to Google Cloud and initializing the Vertex AI SDK. It covers the fundamental code patterns for sending prompts to a model and processing the generated text responses, establishing the core skills needed for all subsequent labs.

### `intro_multimodal_rag-v2.0.0`

* **Summary:** Building on the core concepts of RAG, this lab from the "Inspect Rich Documents" badge specifically focuses on its multimodal application. It teaches how to create a vector database that stores embeddings for both text and image data. The notebook then demonstrates how to build a system that retrieves the most relevant text or image chunks to comprehensively answer a user's query.

### `intro_prompt_design-v2.0.0`

* **Summary:** This foundational lab from the "Prompt Design in Vertex AI" badge focuses on the art and science of prompt engineering. It demonstrates how the structure, wording, and format of a prompt dramatically impact a model's output. The notebook covers various techniques like zero-shot, one-shot, and few-shot prompting for tasks like summarization, classification, and creative text generation, showing users how to effectively control and guide a model's behavior.

### `intro-textemb-vectorsearch-v1.0.0` (1 & 2)

* **Summary:** These notebooks are the core of the "Vector Search and Embeddings" course. They explain the concept of converting text into numerical representations called embeddings, which capture semantic meaning rather than just keywords. The labs guide the user through generating these embeddings using a foundational model and then indexing them in Vertex AI Vector Search for efficient, large-scale similarity searching, which is the backbone of modern recommendation engines.

### `min_diff_keras`

* **Summary:** Part of the "Responsible AI: Fairness & Bias" course, this lab provides a hands-on implementation of a key technique in Responsible AI. It demonstrates how to integrate the MinDiff framework within a TensorFlow/Keras training pipeline to actively reduce biases related to sensitive attributes. By adding a MinDiff loss component, the model learns to make predictions that are less correlated with those attributes, promoting greater fairness.

### `multimodal_retail_recommendations-v2.0.0`

* **Summary:** This practical, use-case-driven notebook shows the power of multimodal AI in an e-commerce context. It builds a sophisticated system that can provide product recommendations by understanding both text descriptions and product images simultaneously. This allows for more nuanced recommendations, such as finding visually similar items or products that match a complex, descriptive user query, which is beyond the capability of traditional systems.

### `privacy_dpsgd` (1)

* **Summary:** A key lab from the "Responsible AI: Privacy & Safety" module, this notebook provides a hands-on guide to training machine learning models with differential privacy. It shows how to implement Differentially Private Stochastic Gradient Descent (DP-SGD), a technique that adds statistical noise during training. This process formally guarantees that the model does not memorize sensitive information about any single individual from the training data.

### `tagline-generator`

* **Summary:** This is a fun and practical example of generative AI's creative capabilities. The notebook focuses on prompt engineering for a specific marketing task: creating compelling taglines. It demonstrates how to provide the model with context, examples (few-shot prompting), and constraints on tone and length to generate a variety of creative, relevant, and brand-aligned taglines for a given product or company.

### `xai_image_vertex`

* **Summary:** This lab from the "Interpretability & Transparency" course addresses the "black box" problem in AI. It demonstrates how to use Vertex AI's Explainable AI (XAI) features, such as Integrated Gradients, on image classification models. This allows developers to generate visual attribution maps, showing exactly which pixels in an image were most influential in a model's decision, thereby increasing transparency and trust.
