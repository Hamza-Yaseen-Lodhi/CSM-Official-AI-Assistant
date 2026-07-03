# Retrieval Process

The CSM Official AI Assistant follows a Retrieval-Augmented Generation (RAG) workflow to generate accurate responses.

## Workflow

1. Customer submits a question.
2. Botpress receives the request.
3. The system searches the indexed Vector Knowledge Base.
4. Relevant website content is retrieved.
5. If necessary, Web Search provides additional context.
6. OpenAI generates a response using the retrieved information.
7. The response is returned to the customer.
8. Conversation logs and analytics are stored for monitoring and future improvements.

---

## Retrieval Pipeline

Customer Question
        ↓
Botpress AI Assistant
        ↓
Vector Knowledge Base
        ↓
Website Crawled Content
        ↓
(Optional) Web Search
        ↓
OpenAI Language Model
        ↓
AI Response
        ↓
Analytics & Conversation Logs