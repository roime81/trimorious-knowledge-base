---
dataset_info:
  features:
  - name: doc_id
    dtype: string
  - name: title
    dtype: string
  - name: source
    dtype: string
  - name: section
    dtype: string
  - name: text
    dtype: string
  splits:
  - name: train
    num_bytes: 10749042
    num_examples: 7784
  download_size: 4368130
  dataset_size: 10749042
configs:
- config_name: default
  data_files:
  - split: train
    path: data/train-*
---
