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
    num_bytes: 644666
    num_examples: 395
  download_size: 304050
  dataset_size: 644666
configs:
- config_name: default
  data_files:
  - split: train
    path: data/train-*
---
