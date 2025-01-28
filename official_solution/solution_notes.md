todo list

Check what happens when it loads a hf causal lm - does it copy stuff, would it be faster to save as composer model?

move tokenization into same python script as train to avoid re-importing libraries (maybe importing libraries takes awhile?)

cache tokenizer and copy it into the folder

throughput device tokens per sec usually 500