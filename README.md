# Multilingual E-commerce Platform with Indic Language Support

This project aims to create a more inclusive and accessible online commerce experience by supporting Indic languages for input and output, including text, voice, and image interfaces.

## Features

1. **Natural Language Processing (NLP) and Speech Recognition:**
   - Utilizes Hugging Face Transformers for NLP tasks.
   - Implements speech recognition for voice inputs in multiple Indic languages.

2. **Image Recognition and Text Extraction:**
   - Integrates OCR techniques to extract relevant text from images containing Indic language text.

3. **Language Translation:**
   - Utilizes transformer models for bidirectional language translation between Indic languages and English.

4. **User Interface (UI) Integration:**
   - Implements a user-friendly interface using Tkinter.
   - Supports text, voice, and image inputs and provides outputs in the selected language through the same medium.

5. **Linguistic Collation Algorithm:**
   - Develops an algorithm for linguistic collation in Indic languages, considering variations and dialects.

6. **Open Fonts for Indic Languages:**
   - Incorporates open-source fonts for clear rendering of Indic scripts in text and image outputs.

7. **Pipelined Architecture with Transformers:**
   - Evaluates the use of pipelined architectures, leveraging transformer models with text2vec capabilities.

## Assumptions

- Adequate training data for Indic languages is available for NLP and translation models.
- Availability of pretrained transformer models for Indic languages.
- Users have devices capable of supporting voice input and output in their preferred language.

## Dependencies

Ensure that you have the required dependencies installed using the following:

```bash
pip install transformers pillow pytesseract langid indic-transliteration
```

## Usage

1. Run the script.
2. Follow the prompts to interact with the multilingual e-commerce platform through the graphical user interface.

## Test Cases

1. **Search & Discovery - Text Input:**
   - Enter a product query in your language.
   - Examine the displayed search result.

2. **Payment Confirmation:**
   - Enter payment details in your language.
   - Observe the payment confirmation details.

3. **Post Order Update:**
   - Enter an order status update in your language.
   - Check the displayed post-order update.

4. **Customer Service Query:**
   - Enter a customer service query in your language.
   - Review the displayed customer service query.

## Acknowledgments

- This project utilizes various open-source libraries and models. See the code comments for specific attributions.

## Contributing

Feel free to contribute to the project by opening issues or submitting pull requests.


