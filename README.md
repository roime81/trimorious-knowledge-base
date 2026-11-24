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
    num_bytes: 775256
    num_examples: 543
  download_size: 308660
  dataset_size: 775256
configs:
- config_name: default
  data_files:
  - split: train
    path: data/train-*
---
