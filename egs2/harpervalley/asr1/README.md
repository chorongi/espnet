<!-- Generated by scripts/utils/show_asr_result.sh -->
# RESULTS
## Environments
- date: `Sat Apr 23 12:20:53 EDT 2022`
- python version: `3.7.11 (default, Jul 27 2021, 14:32:16)  [GCC 7.5.0]`
- espnet version: `espnet 0.10.7a1`
- pytorch version: `pytorch 1.9.0+cu102`
- Git hash: `0b1d15ebe0c36efcdf06d1b2e32361e3c8846cf6`
  - Commit date: `Tue Apr 5 10:46:40 2022 -0400`
- Pretrained Model: https://huggingface.co/espnet/YushiUeda_harpervalley_train_asr_hubert_raw_en_word

## asr_train_asr_raw_en_word
- config [conf/tuning/train_asr.yaml](conf/tuning/train_asr.yaml)
- token_type word

|dataset|Snt|Intent Classification (%)|
|---|---|---|
|inference_asr_model_valid.acc.ave_10best/test|1028|37.9|
|inference_asr_model_valid.acc.ave_10best/valid|1430|35.5|

## asr_train_asr_hubert_raw_en_word
- config [conf/tuning/train_asr_hubert.yaml](conf/tuning/train_asr_hubert.yaml)
- token_type word

|dataset|Snt|Intent Classification (%)|
|---|---|---|
|inference_asr_model_valid.acc.ave_10best/test|1028|46.0|
|inference_asr_model_valid.acc.ave_10best/valid|1430|46.6|
