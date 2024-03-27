
# Text Recoginition Through Transformer Model

1.General OCR Model:

This model employs an encoder-decoder architecture to handle both general and specific image datasets.

The encoder processes the input image, extracting visual features.
The decoder takes these features and predicts the corresponding text sequence.

The specific details of the encoder and decoder architecture, training process, and evaluation metrics are not provided in the report you shared, but could be documented in the code itself.

2.Specific OCR Model (Built from Scratch):

 
•This model focuses on extracting text from Portable Document Format (PDF) images and Word documents (.docx).

•It employs separate Transformer encoders and decoders:
One encoder processes PDF image features.
The other encoder processes text embeddings from the DOCX content.
The decoder leverages both sets of encoded features to generate the predicted text, ensuring alignment between the visual content and the generated text.

•The report outlines the training process and suggests evaluation metrics like Character Error Rate (CER), Word Error Rate (WER), and BLEU Score (for captioning tasks).

