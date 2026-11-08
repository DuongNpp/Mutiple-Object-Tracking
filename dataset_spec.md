{DATASET_ROOT}/
├── train/
│   ├── <seq_name_01>/
│   │   ├── img1/
│   │   │   ├── 00000001.jpg 
│   │   │   ├── 00000002.jpg
│   │   │   └── ...
│   │   ├── gt/
│   │   │   └── gt.txt
│   │   └── seqinfo.ini
│   ├── <seq_name_02>/
│   └── ...
├── val/
│   ├── <seq_name_k>/
│   │   ├── img1/
│   │   │   └── ...
│   │   ├── gt/
│   │   │   └── gt.txt
│   │   └── seqinfo.ini
│   └── ...
├── test/
│   ├── <seq_name_m>/
│   │   ├── img1/
│   │   │   └── ...
│   │   └── seqinfo.ini  
│   └── ...
├── train_seqmap.txt
├── val_seqmap.txt
├── test_seqmap.txt
└── TrackEval/           