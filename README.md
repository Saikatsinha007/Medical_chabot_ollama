
# 🩺 **Medical Chatbot with AI and Semantic Search** 🤖

![AI Chatbot](https://img.shields.io/badge/🤖%20AI-Powered%20Chatbot-blue?style=for-the-badge&logo=chatbot)
![Semantic Search](https://img.shields.io/badge/🔍%20Semantic%20Search-lightgreen?style=for-the-badge&logo=search)
![Streamlit Deployment](https://img.shields.io/badge/🚀%20Streamlit-Deployed-orange?style=for-the-badge&logo=streamlit)

---

## 🌟 **Overview**

This project features a state-of-the-art 🩺 **medical chatbot** that leverages AI and semantic search technologies to provide **real-time medical consultations**. Built with **Hugging Face’s T5 model** fine-tuned on medical data and integrated with the **Ollama model**, the chatbot can process up to **5 queries per minute** with high accuracy and contextual relevance.

🖼️ **Screenshot**:  
![Screenshot](https://github.com/user-attachments/assets/f5fbfb78-242e-4e61-babd-9d92979d85b8)

---

## ⚡ **Key Features**

- 🤖 **AI-Powered Chatbot**: Utilizes Hugging Face’s T5 model, fine-tuned for medical applications to ensure precise and context-aware responses.
- 🔍 **Semantic Search**: FAISS (Facebook AI Similarity Search) provides fast and efficient retrieval, with response times consistently under 300 ms.
- ⏱️ **Real-Time Query Handling**: Processes up to **5 queries per minute** with minimal latency.
- 🚀 **Streamlit Deployment**: Deployed with **Streamlit** for an intuitive user experience and real-time interaction.

---

## 📊 **Performance Metrics**

The chatbot’s effectiveness has been validated through comprehensive performance evaluations:

| 🏆 **Metric**    | 🎯 **Score** |
| ---------------- | ----------- |
| **Accuracy**     | 0.85         |
| **Precision**    | 0.87         |
| **Recall**       | 0.83         |
| **F1-Score**     | 0.85         |
| **BLEU Score**   | 0.82         |

🔍 These metrics highlight the model’s ability to generate **contextually relevant and accurate medical responses**.

---

## 🛠️ **Technical Architecture**

### 🔧 **Components Overview**

1. 🤖 **Language Model**: Hugging Face’s **T5 model**, fine-tuned on a comprehensive medical dataset.
2. 🔍 **Semantic Search**: **FAISS (Facebook AI Similarity Search)** enables fast, high-accuracy information retrieval.
3. ⚙️ **Query Processor**: **Ollama model** integration ensures efficient handling of multiple concurrent queries.
4. 💻 **User Interface**: **Streamlit** offers a responsive and user-friendly interface for smooth interactions.

### 🗂️ **Workflow Diagram**

```plaintext
User Query  -->  T5 Model  -->  FAISS Retrieval  -->  Contextual Response  -->  Streamlit Interface
```

---

## 🚀 **Installation and Setup**

1. 📦 Clone the repository:
   ```bash
   git clone <repository-url>
   ```
2. 📂 Navigate to the project directory:
   ```bash
   cd medical-chatbot
   ```
3. 📥 Install the necessary dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. ▶️ Launch the chatbot application:
   ```bash
   streamlit run medical_chatbot.py
   ```

---

## 🛡️ **Usage**

1. 🖥️ Launch the **Streamlit app**.
2. ✏️ Enter your medical query into the input field.
3. 🩺 Receive **contextually relevant and accurate medical responses** in real-time.

---

## 🚧 **Future Enhancements**

- 📈 **Model Refinement**: Additional fine-tuning using broader medical datasets to enhance response quality.
- 🌐 **Multilingual Capabilities**: Enable support for multiple languages to increase accessibility.
- 🔗 **API Integrations**: Connect with external medical databases and APIs for more comprehensive consultations.
- 🎤 **Voice Interaction**: Add voice recognition and response generation for hands-free interaction.

---

## 📜 **License**

This project is licensed under the **MIT License**.

---

## 🙌 **Acknowledgments**

- 🤖 **Hugging Face**: For their powerful T5 model.
- 📚 **FAISS**: For efficient and scalable semantic search capabilities.
- 🚀 **Streamlit**: For providing a simple, elegant, and responsive deployment platform.

---

![Thank You](https://img.shields.io/badge/🙏%20Thank%20You-For%20Your%20Support-green?style=for-the-badge)
