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
    num_bytes: 334543
    num_examples: 301
  download_size: 147555
  dataset_size: 334543
configs:
- config_name: default
  data_files:
  - split: train
    path: data/train-*
---
