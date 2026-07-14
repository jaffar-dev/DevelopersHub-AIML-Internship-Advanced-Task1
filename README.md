# 📰 News Topic Classifier Using BERT (Advanced Task 1)

## 🎯 Objective
To fine-tune a state-of-the-art `bert-base-uncased` Transformer architecture to categorize unstructured text streams (news headlines) into distinct operational topics (World, Sports, Business, Sci/Tech).

## 🛠️ Methodology & Architecture
* **Tokenization**: Handled via Hugging Face's WordPiece encoder mapping sequence lengths cleanly up to 128 tokens.
* **Transfer Learning**: Loaded a base BERT checkpoint on a Google Colab T4 GPU instance, adjusting classification heads to manage 4 multi-class outputs.
* **Evaluation**: Monitored loss convergence over validation metrics using accuracy score mappings.

## 📈 Key Results
* **Performance**: The transformer achieved rapid text feature representation convergence within a single epoch.
* **Inference**: Showcases strong understanding of structural context variations across short sentence lengths.
