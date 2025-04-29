## 1. `db-vector-searcher`

This Logic App is responsible for providing our AI agent with the contextual information it needs to assist real estate advisors or trigger other internal tools.

### 🔍 Functionality

It receives two main inputs:
- **`entity_type`**: Indicates the type of entity to search (`property`, `project`, or `client`).
- **`query`**: The natural language query that will be vectorized.

The Logic App then:
1. Embeds the query using **Azure OpenAI embeddings**.
2. Performs a **vector search** against the appropriate table based on the entity type.
3. Returns the most relevant matches from the vector store.

---
