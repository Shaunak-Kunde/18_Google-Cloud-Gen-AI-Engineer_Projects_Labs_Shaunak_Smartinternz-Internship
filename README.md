# Smartinternz Internship - Google Cloud Gen AI Engineer

This repository contains all the advanced projects and guided labs that I implemented in the Google Cloud Skills Boost platform as part of my Google Cloud Gen AI Virtual Internship Program with Smartinternz. It covers my progress through both the introductory and advanced developer learning paths.

---

## ✅ Completed Learning Paths

* **Beginner: Introduction to Generative AI**
* **Advanced: Generative AI for Developers**

---
### 🎓 Learning Path

# Below is the full list of courses, Cloud Labs and skill badges I completed within each learning path.

## Beginner: Introduction to Generative AI

1.  **Introduction to Generative AI**
2.  **Introduction to Large Language Models**
3.  **Introduction to Responsible AI**
   <img width="695" height="215" alt="image" src="https://github.com/user-attachments/assets/65c52972-8e72-46f2-8885-5254dcb3bc10" />
   
---
4.  **Prompt Design in Vertex AI** (Skill Badge)
 <img width="142" height="172" alt="image" src="https://github.com/user-attachments/assets/f612ca2c-355f-41df-8bf5-2c6f4dc541f6" />

---
5.  **Responsible AI: Applying AI Principles with Google Cloud**
   <img width="214" height="203" alt="image" src="https://github.com/user-attachments/assets/5d67f0bb-e0bd-4697-97cf-df567e8761ab" />

---
## Advanced: Generative AI for Developers

1.  **Introduction to Image Generation**<img width="154" height="191" alt="image" src="https://github.com/user-attachments/assets/25ea1d4d-3192-4d11-b538-a95a1b01bf27" />

2.  **Attention Mechanism**
3.  **Encoder-Decoder Architecture**
4.  **Transformer Models and BERT Model**
5.  **Create Image Captioning Models**
6.  **Introduction to Vertex AI Studio**
7.  **Vector Search and Embeddings** (Skill Badge)
8.  **Inspect Rich Documents with Gemini Multimodality and Multimodal RAG** (Skill Badge)
9.  **Responsible AI for Developers: Fairness & Bias**
10. **Responsible AI for Developers: Interpretability & Transparency**
11. **Responsible AI for Developers: Privacy & Safety**
12. **Machine Learning Operations (MLOps) for Generative AI**

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
