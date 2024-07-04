**About**: Chatbot to answer questions from your uploaded PDF

**Steps:**
1. Source **Data** (PDF) Setup
2. Break your data (PDFs) into **CHUNKS**
3. Define **MODEL** & Setup Key `*[Model Used: gemini-1.5-flash]*`
4. Convert your data (chunks) into **EMBEDDINGS** `*[Embeddings Used: models/embedding-001]*`
5. Persist these embeddings in a **VECTOR DB** `*[Vector DB Used: Meta Faiss]*`
6. Ask Questions (Ques needs to be converted to same Embedding as well)
7. Extend the Q&A into a **CHATBOT*
