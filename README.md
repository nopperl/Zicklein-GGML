# Zicklein-GGML
<p align="center" width="100%">
<img src="zicklein-ggml.jpg" alt="a lean, scrawny llama at the oktoberfest" style="width: 20%; min-width: 300px; display: block; margin: auto;">
</p>

[GGML](https://github.com/ggerganov/ggml) conversion of [Zicklein](https://github.com/avocardio/zicklein) (a German [Alpaca](https://github.com/tatsu-lab/stanford_alpaca) LoRa for [LLaMA](https://github.com/facebookresearch/llama)). Compatible with [llama.cpp](https://github.com/ggerganov/llama.cpp) version master-2d43387 or later.

The model is stored on the [HuggingFace 🤗 Hub](https://huggingface.co/nopperl/alpaca-lora-7b-german-base-51k-ggml).

The script of the conversion process is in `convert.sh`. The model can be uploaded using `upload-model.sh`. Make sure to specify a commit message, e.g. `./upload_model.sh add new version`.

## Requirements
Install python3 and git, then install the python requirements in `requirements.txt`, e.g.:
```
pip install -r requirements.txt
```
