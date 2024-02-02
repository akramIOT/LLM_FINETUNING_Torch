## FINE TUNING LLM's  and LLM  BASICS  COVERED IN THIS  PROJECT ####


## Google Colab can be used for those who don't have a GPU: 

Dependencies (assuming windows): `pip install pylzma numpy ipykernel jupyter torch --index-url https://download.pytorch.org/whl/cu118`

If you don't have an NVIDIA GPU, then the `device` parameter will default to `'cpu'` since `device = 'cuda' if torch.cuda.is_available() else 'cpu'`. If device is defaulting to `'cpu'` that is fine, you will just experience slower runtimes.

## OpenWebText Download - https://skylion007.github.io/OpenWebTextCorpus/

## Fine Tuning  LLM  Research Papers Reference:
Attention is All You Need - https://arxiv.org/pdf/1706.03762.pdf

A Survey of LLMs - https://arxiv.org/pdf/2303.18223.pdf

QLoRA: Efficient Finetuning of Quantized LLMs - https://arxiv.org/pdf/2305.14314.pdf

https://towardsdatascience.com/fine-tuning-large-language-models-llms-23473d763b91   -  This is a  very good  reference


