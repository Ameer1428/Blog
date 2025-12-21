## Day 02: Beyond Chatbots—The Rise of Agentic Design Patterns

### 🔍 The Shift: Prompting vs. Iterative Loops
Most developers are stuck in the "Input -> Output" paradigm. However, the 2025/26 frontier is **Iterative Agentic Workflows**. 

### 💡 Technical Insight: The "Critic" Pattern
The most effective way to eliminate hallucinations is not a better prompt, but a **Multi-Agent Orchestration**.
* **Sequential Chains:** Task A -> Task B -> Task C.
* **Routing:** An orchestrator decides which "Specialist" model (e.g., a Coding model vs. a Creative model) should handle the sub-task.
* **Self-Reflection:** The model is forced to critique its own output before showing it to the user.

### 🛠️ Tools to Watch (Late 2025 Edition)
If you want to build these, look into:
1.  **CrewAI / AutoGen:** The industry standards for multi-agent coordination.
2.  **LangGraph:** For building complex, stateful "cyclic" graphs (where AI can loop back until a condition is met).
3.  **NVIDIA Nemotron-3:** New open reasoning models specifically optimized for these "Agentic" workloads.

### 📊 Fact of the Day
According to recent 2025 benchmarks, **Agentic RAG** (where an AI agent chooses when and where to search for data) outperforms **Standard RAG** in complex reasoning tasks by nearly **40%**.
