# ahlt
Repository for the Advanced Human Language Technologies course at UPC

## Running 

`python3 baseline-NER.py [-h] [-l [L]] train_data_path output_file_name`


include flag `-l` to look up drug names in the drug list file

## Running the DDI classifier:
```
python3 feature_extractor.py ../../labAHLT/data/test > feats_test.dat
python3 feature_extractor.py ../../labAHLT/data/train > feats.dat
python3 learner.py feats.dat feats_test.dat output.dat
```

