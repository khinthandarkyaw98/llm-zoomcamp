# LLM Zoomcamp Saturn Cloud

Saturn Cloud starter code for LLM Zoomcamp 

The following parameters control the generation process, with default values provided via generate_params.get(key, default_value):
**max_length**: The maximum length of the generated sequence. Default is 100 tokens.
**num_beams**: The number of beams for beam search. More beams result in better quality at the expense of speed. Default is 5.
**do_sample**: Whether to use sampling instead of greedy decoding. Default is False.
**temperature**: Controls the randomness of predictions by scaling the logits before applying softmax. Higher values (e.g., 1.0) make the model more random, while lower values make it more deterministic. Default is 1.0.
**top_k**: The number of highest probability vocabulary tokens to keep for top-k-filtering. Default is 50.
**top_p**: If set to a probability (0.0 < top_p < 1.0), only the smallest set of tokens with cumulative probability top_p are kept for generation (nucleus sampling). Default is 0.95.