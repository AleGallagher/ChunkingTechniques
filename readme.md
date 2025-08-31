# Chunking Techniques for Retrieval-Augmented Generation (RAG) 🚀

This project explores various **chunking techniques** and evaluates their effectiveness in the context of **Retrieval-Augmented Generation (RAG)** pipelines. The goal is to learn different chunking methods with its implementation, prons and cons.

### Key Files 📂
- **`chunking_methods.ipynb`**: 📝 Main notebook containing the implementation of chunking techniques, evaluation metrics, and visualizations.
- **`english_women_football.txt`**: 📜 Source text used for chunking and evaluation.
- **`chunks/`**: 📦 Directory containing chunked data files for different methods and configurations.
- **`chunks_evaluations/`**: 📊 Directory containing evaluation results for each chunking method.
- **`chunks_metrics.json`**: 📈 Summary of evaluation metrics for all chunking methods.
- **`questions.csv`**: ❓ Generated questions used for evaluating chunking methods.

## Chunking Techniques 🛠️
The following chunking methods are implemented and compared:
1. **Fixed-Size Chunking**: Splits text into fixed-size chunks, optionally with overlap.
2. **Recursive Chunking**: Recursively splits text while preserving semantic structure.
3. **Semantic Chunking**: Uses embeddings to create semantically meaningful chunks.
4. **LLM-Based Chunking**: Leverages a language model to intelligently split text.

## Evaluation Metrics 📏
The chunking methods are evaluated using the following metrics:
- **Faithfulness**: ✅ Measures factual accuracy of the retrieved chunks.
- **Relevancy**: 🔍 Assesses how well the chunks align with the query.
- **Context Relevancy**: 🧠 Evaluates the usefulness of the chunks for generating high-quality answers.
- **Response Time**: ⏱️ Measures the time taken to retrieve and process chunks.

## Results 📊
The evaluation results are summarized in `chunks_metrics.json` and visualized in the notebook. Key observations include:
- **Semantic Chunking** achieves the highest faithfulness and relevancy scores. 🌟
- **Recursive Chunking** balances context relevancy and accuracy. ⚖️
- **Fixed-Size Chunking** is fast but often splits text mid-sentence, losing semantic coherence. ⚡

## How to Run
1. Set up your .env file with the necessary API key of OPENAI_API_KEY.
2. Open and run the chunking_methods.ipynb in Jupyter or VS Code.
3. View the evaluation results in chunks_metrics.json or the visualizations in the notebook.

## License 📜
This project is licensed under the MIT License. See the LICENSE file for details.