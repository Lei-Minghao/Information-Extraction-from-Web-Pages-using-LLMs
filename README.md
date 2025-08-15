# Information Extraction from Web Pages using LLMs
This experiment explores the performance of Large Language
Models (LLMs) in extracting structured information from e-commerce product
pages. Three LLMs—Llama-3.2-11b, Mistral-3.1-24b, and Qwen-2.5-
72b—were tested across different platforms (Amazon, eBay, Temu), product
categories (fashion, electronics, beauty), input formats (HTML vs. screenshots),
and prompting strategies (zero-shot vs. few-shot). Results shows
that HTML input and few-shot prompting significantly improved performance,
with Qwen outperforming others due to its larger size. Errors were
most frequent with attributes like ”Object” and ”Material,” especially when
embedded in titles. A secondary LLM (DeepSeek-V3) validated the results,
showing strong alignment with human evaluation. Findings highlight the
potential of LLMs for reliable web information extraction.
