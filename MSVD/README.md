# MSVD

dataset structure：
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
MSVD
 ├─ video_corpus.csv         # caption file in original dataset
 ├─ youtube_mapping.txt      # map original video name to video number
 ├─ annotation.json          # json format caption file
 ├─ sents_*_lc_nopunc.txt    # txt format caption files without punctuation (split to train|val|test)
 ├─ msvd_*_references.txt    # txt format caption files
 
 IMPORTANT:
 ├─ msvd_captions_*.pkl      # words,POS_tags ===> tokens
 ├─ msvd_vocab.pkl           # vocabulary file
 ├─ msvd_feature.h5          # features extracted by IRV2 and I3D, dimension: (1970, 26, 1536+1024)
 ├─ msvd_region_feature.h5   # features extracted by Faster RCNN, dimension: (1970, 26, 36, 2048)

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

