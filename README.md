# OCR IMPLEMENTATION:
Optical Character Recognition (OCR) is the process of converting images containing text into machine-encoded text. In this project, we implement two approaches to OCR:

* EasyOCR: A lightweight, powerful, and easy-to-use OCR library.
* TrOCR: A transformer-based model for text recognition, known for its accuracy in challenging scenarios.
  
Both models perform well on handwritten and printed text but face challenges when dealing with curved text (e.g., text on spherical surfaces or wavy layouts). To address this limitation, we fine-tuned the TrOCR model on a custom dataset consisting of curved text images, improving its performance for this specific use case. The aim is to highlight the strengths and weaknesses of each approach and help users choose the best model for their specific needs.
