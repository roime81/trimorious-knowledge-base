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
    num_bytes: 740918
    num_examples: 543
  download_size: 308010
  dataset_size: 740918
configs:
- config_name: default
  data_files:
  - split: train
    path: data/train-*
---
