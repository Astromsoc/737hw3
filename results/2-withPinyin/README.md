# Experiment 2: ASR with Pinyin (no tones)

This folder is for the Hanyu Pinyin-based model for ASR on Sichuan Dialect.

### Experiment Setup 

Use Hanyu Pinyin sequences in place of Chinese character sequences as outputs.

---

<!-- Generated by scripts/utils/show_asr_result.sh -->
# RESULTS - with Language Model
## Environments
- date: `Mon Mar 21 03:36:28 UTC 2022`
- python version: `3.9.10 | packaged by conda-forge | (main, Feb  1 2022, 21:24:11)  [GCC 9.4.0]`
- espnet version: `espnet 0.10.7a1`
- pytorch version: `pytorch 1.10.1`
- Git hash: `9620d878b966dce02f57d81f83fbb3eaa4b02ded`
  - Commit date: `Sun Mar 20 02:15:08 2022 -0400`

## asr_2_withPinyin_raw_sc_bpe350_sp
### WER

|dataset|Snt|Wrd|Corr|Sub|Del|Ins|Err|S.Err|
|---|---|---|---|---|---|---|---|---|
|inference_lm_lm_train_sc_bpe350_valid.loss.ave_asr_model_valid.acc.ave/dev_sc|583|7210|82.2|15.4|2.3|0.3|18.1|82.2|
|inference_lm_lm_train_sc_bpe350_valid.loss.ave_asr_model_valid.acc.ave/test_sc|586|6991|82.8|14.7|2.5|0.4|17.5|82.1|

### CER

|dataset|Snt|Wrd|Corr|Sub|Del|Ins|Err|S.Err|
|---|---|---|---|---|---|---|---|---|
|inference_lm_lm_train_sc_bpe350_valid.loss.ave_asr_model_valid.acc.ave/dev_sc|583|28129|92.9|3.3|3.7|1.6|8.7|82.2|
|inference_lm_lm_train_sc_bpe350_valid.loss.ave_asr_model_valid.acc.ave/test_sc|586|27164|93.0|3.2|3.8|1.7|8.7|82.1|

### TER

|dataset|Snt|Wrd|Corr|Sub|Del|Ins|Err|S.Err|
|---|---|---|---|---|---|---|---|---|
|inference_lm_lm_train_sc_bpe350_valid.loss.ave_asr_model_valid.acc.ave/dev_sc|583|7358|81.9|14.9|3.2|0.6|18.7|82.2|
|inference_lm_lm_train_sc_bpe350_valid.loss.ave_asr_model_valid.acc.ave/test_sc|586|7142|82.2|14.3|3.6|0.6|18.4|82.1|

---
<!-- Generated by scripts/utils/show_asr_result.sh -->
# RESULTS -- without Language Model
## Environments
- date: `Tue Mar 22 21:32:15 UTC 2022`
- python version: `3.9.10 | packaged by conda-forge | (main, Feb  1 2022, 21:24:11)  [GCC 9.4.0]`
- espnet version: `espnet 0.10.7a1`
- pytorch version: `pytorch 1.10.1`
- Git hash: `1991a25855821b8b61d775681aa0cdfd6161bbc8`
  - Commit date: `Mon Mar 21 22:19:19 2022 +0800`

## asr_2_withPinyin_raw_sc_bpe350_sp
### WER

|dataset|Snt|Wrd|Corr|Sub|Del|Ins|Err|S.Err|
|---|---|---|---|---|---|---|---|---|
|inference_asr_model_valid.acc.ave/dev_sc|583|7210|86.5|12.6|0.9|0.4|13.9|76.0|
|inference_asr_model_valid.acc.ave/test_sc|586|6991|86.6|12.6|0.9|0.4|13.8|76.3|

### CER

|dataset|Snt|Wrd|Corr|Sub|Del|Ins|Err|S.Err|
|---|---|---|---|---|---|---|---|---|
|inference_asr_model_valid.acc.ave/dev_sc|583|28129|95.8|2.2|2.0|1.5|5.7|76.0|
|inference_asr_model_valid.acc.ave/test_sc|586|27164|95.7|2.3|2.0|1.6|5.8|76.3|

### TER

|dataset|Snt|Wrd|Corr|Sub|Del|Ins|Err|S.Err|
|---|---|---|---|---|---|---|---|---|
|inference_asr_model_valid.acc.ave/dev_sc|583|7358|86.0|12.1|1.8|0.5|14.5|76.0|
|inference_asr_model_valid.acc.ave/test_sc|586|7142|85.9|12.2|2.0|0.5|14.7|76.3|

