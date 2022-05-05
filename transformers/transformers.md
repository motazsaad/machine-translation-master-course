# Types of Transformers Models?

# Transformers architecture follows Encoder and Decoder structure.

Encoder receives input sequence and creates intermediate representation by applying embedding and attention mechanism.

Then, this intermediate representation or hidden state will pass through the decoder, and the decoder starts generating an output sequence.

In the case of Machine Translation, like English to French translation, the Encoder will process English sentences as input, apply the attention mechanism, and encode it in the intermediate representation.

This encoded input sequence then passes to the Decoder, generating the corresponding french sentence.

## There are three types of transformers models
1. Encoder Only
2. Decode Only
3. Encoder-Decoder

👉 Encoder Only
BERT leverages the Encoder architecture of the transformer. BERT takes text sequence as input. The BERT Encoder produces BERT embedding, which can be used to perform downstream tasks like Text classification or Named Entity Recognition.

👉 Decoder Only
GPT models leverage the decoder architecture of the transformer. Given the input sequence as prompt, GPT starts generating the response. Therefore, GPT models are best suitable for text or sequence generation.

👉 Encoder-Decoder
T5 is a model which uses both Encoder and Decoder architecture. It treats each task as text to text or sequence to sequence. E.g., In text classification, the Encoder takes text as input, and the Decoder generates text labels instead of classifying them.

📖 Leandro von Werra, Lewis Tunstall , and Thomas Wolf from Hugging Face wrote the excellent book “ Transformers Natural Language Processing with Transformers.”

The book covers transformers in detail and their different use cases like Text classification, Summarization, Text generation, etc.