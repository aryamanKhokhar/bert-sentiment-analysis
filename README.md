# Bert-Sentiment-Analysis

**Sentiment analysis of text reviews using a fine-tuned BERT transformer in PyTorch.**

This project showcases a complete workflow to build a powerful sentiment classifier using BERT, covering:

- **Data preprocessing:** Text cleaning, tokenization, and encoding for BERT input  
- **Label mapping & dataset splitting:** Stratified train/validation/test splits  
- **Custom Dataset:** Efficient data batching with a PyTorch Dataset class  
- **Model design:** BERT backbone with dropout and a classification head  
- **Training:** Fine-tuning with AdamW optimizer and learning rate scheduling  
- **Evaluation:** Metrics tracking, loss visualization, and confusion matrix analysis  
- **Inference:** Making predictions on new reviews with class probabilities  
- **Model persistence:** Saving and loading the trained model for future use  

Ideal for intermediate PyTorch users looking to apply transformers for NLP classification tasks — easily adaptable to other datasets or text classification problems.
