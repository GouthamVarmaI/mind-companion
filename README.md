# Mind Companion: Mental Health Support Chatbot 🌟

Mind Companion is an AI-powered mental health chatbot built using Google's Gemma 2B model, designed to provide empathetic support and guidance in times of emotional distress. This model has been fine-tuned on counseling conversations with a focus on supportive, ethical responses.

## Overview 🎯

- **Model**: Fine-tuned Gemma 2B
- **Training Data**: 3,500+ counseling conversations
- **Purpose**: Provide initial emotional support and guidance
- **Focus**: Empathetic responses with safety considerations

## Features ✨

- Empathetic response generation
- Safety patterns and ethical considerations
- CPU-optimized inference
- User-friendly Gradio interface

## Important Note ⚠️

This chatbot is not a replacement for professional mental health care. It is designed as a supportive tool only. If you're experiencing serious mental health issues, please contact a qualified mental health professional.

## Technical Details 🔧

### Model Architecture
- Base Model: Google Gemma 2B
- Fine-tuning: LoRA with 4-bit quantization
- Optimization: CPU-friendly inference settings

### Performance
- Response Time: 15-30 seconds (CPU)
- Context Length: 128 tokens
- Temperature: 0.7 (balanced creativity and consistency)

## Usage 💻

1. **Local Setup**:
```bash
pip install -r requirements.txt
python app.py
```

2. **Requirements**:
- Python 3.8+
- PyTorch
- Transformers
- Gradio
- Accelerate


## License 📄
This project follows the licensing terms of the Gemma model and its components.

## Acknowledgments 🙏
- Google's Gemma Team for the base model
- Hugging Face for infrastructure
- Mental health professionals for guidance on ethical considerations

For more details, visit our [Hugging Face Model Page](https://huggingface.co/GouthamVarma/mentalhealth_conversational_chatbot)
