# eCommTouch
The eCommTouch (e-commerce touch) dataset can be used for touch-bassed authenitcation.<br>
This dataset includes touch data from 105 users.

You can download the dataset at [Releases](https://github.com/yamanalab/eCommTouch/releases).

## Data
All data of eCommTouch is stored in the ```data``` folder.

The ```data.zip``` file contains the following two CSV files:
- ```rawdata.csv```: A file that compiles touch data obtained using the iPhone 8 Plus and iPhone XS.
- ```user_info.csv```: A file that compiles user information.

The ```features.zip``` file contains the feature file (```features.csv```) extracted for the baseline evaluation of eCommTouch.

All programs for feature extraction are located in the ```src``` folder.

```
│── README.md
├── data (After unzipping the 'data.zip' file)
│   │── README.md
│   │── rawdata.csv
│   └── user_info.csv
│
│── features (After unzipping the 'features.zip' file)
│   │── features.csv
│   │ (After executing 'src/datasets_xxx.ipynb')
│   │── 8PLUS_ALL_NORM.csv
│   │── 8PLUS_ALL.csv
│   │── 8PLUS_HOR_NORM.csv
│   │── 8PLUS_HOR.csv
│   │── 8PLUS_VER_NORM.csv
│   │── 8PLUS_VER.csv
│   │── ALL_ALL_NORM.csv
│   │── ALL_ALL.csv
│   │── ALL_HOR_NORM.csv
│   │── ALL_HOR.csv
│   │── ALL_VER_NORM.csv
│   │── ALL_VER.csv
│   │── XS_ALL_NORM.csv
│   │── XS_ALL.csv
│   │── XS_HOR_NORM.csv
│   │── XS_HOR.csv
│   │── XS_VER_NORM.csv
│   └── XS_VER.csv
│
└── src
    │── datasets_8PLUS.ipynb
    │── datasets_ALL.ipynb
    │── datasets_XS.ipynb
    └── feature_extraction.ipynb
```


## Requirements
**Python 3.7.8**
- pandas==1.1.4
- numpy==1.19.4
- tqdm==4.52.0


## Contributors
- [Masashi Kudo](https://orcid.org/0000-0002-1150-3565)
- Hayato Yamana
- Tsubasa Takahashi

## License
- [MIT License](./LICENSE)

## Acknowledgements
The research was supported by NII CRIS Joint Research 2022.
