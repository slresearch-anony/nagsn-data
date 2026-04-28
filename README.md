# nagsn-data
A dataset of a star pattern recognition in wide-field cameras
The current data represents a representative subset, and the full content will be released after the paper is published.
```
	├── distortions/     # Distortion calibration data
    │   ├── Capture01/	 # Capture* represents the real calibration data
    │   ├── Capture02/
    │   ├── Capture03/
    │   ├── Sim6144_1/	 # Sim* represents the simulated distortion data
    │   ├── ......
    │   └── Sim12288_3/
	└── match/			 # The data for match
        ├── sims/		 # Simulation data
        │	├── 0/		 # 0\1\2\3 represent the distortion level
        │	│	├── 5/	 # 5\10\15\20 represent the outlier ratio(%).
        │	│	├── 10/
        │	│	├── 15/
        │	│	└── 20/
        │	├── 1/
        │	├── 2/
        │	└── 3/
        └── capd_list.txt # Real data we employed in paper
```
The `capd_list.txt` file lists the real data IDs used in this paper, with the corresponding paper being "Digitization of Astronomical Photographic Plates of China and Astrometric Measurement of Single-exposure Plates" (DOI: 10.1088/1674-4527/ad339d), and the original data can be accessed at: https://nadc.china-vo.org/res/r100742/.

The detailed description of the data will be continuously updated in the near future.
