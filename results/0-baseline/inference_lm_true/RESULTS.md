<!-- Generated by scripts/utils/show_asr_result.sh -->
# RESULTS
## Environments
- date: `Tue Mar 22 08:37:45 UTC 2022`
- python version: `3.9.10 | packaged by conda-forge | (main, Feb  1 2022, 21:24:11)  [GCC 9.4.0]`
- espnet version: `espnet 0.10.7a1`
- pytorch version: `pytorch 1.10.1`
- Git hash: `1991a25855821b8b61d775681aa0cdfd6161bbc8`
  - Commit date: `Mon Mar 21 22:19:19 2022 +0800`

## asr_0_baseline_raw_sc_bpe3000_sp
### WER

|dataset|Snt|Wrd|Corr|Sub|Del|Ins|Err|S.Err|
|---|---|---|---|---|---|---|---|---|
|inference_lm_lm_train_sc_bpe3000_valid.loss.ave_asr_model_valid.acc.ave/dev_sc|583|583|0.0|100.0|0.0|0.0|100.0|100.0|
|inference_lm_lm_train_sc_bpe3000_valid.loss.ave_asr_model_valid.acc.ave/test_sc|586|586|0.3|99.7|0.0|0.0|99.7|99.7|

### CER

|dataset|Snt|Wrd|Corr|Sub|Del|Ins|Err|S.Err|
|---|---|---|---|---|---|---|---|---|
|inference_lm_lm_train_sc_bpe3000_valid.loss.ave_asr_model_valid.acc.ave/dev_sc|583|7210|24.8|42.0|33.2|2.0|77.2|100.0|
|inference_lm_lm_train_sc_bpe3000_valid.loss.ave_asr_model_valid.acc.ave/test_sc|586|6991|25.6|42.7|31.6|1.7|76.0|99.7|

### TER

|dataset|Snt|Wrd|Corr|Sub|Del|Ins|Err|S.Err|
|---|---|---|---|---|---|---|---|---|
|inference_lm_lm_train_sc_bpe3000_valid.loss.ave_asr_model_valid.acc.ave/dev_sc|583|5812|19.1|44.7|36.1|1.1|82.0|100.0|
|inference_lm_lm_train_sc_bpe3000_valid.loss.ave_asr_model_valid.acc.ave/test_sc|586|5699|19.7|44.6|35.8|0.9|81.3|99.7|

