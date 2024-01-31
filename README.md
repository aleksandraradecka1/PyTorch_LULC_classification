## Planet: Understanding the Amazon from Space 🌳🛰️
#### Use satellite data to track the human footprint in the Amazon rainforest

![](planet_examples.jpg)

#### Goal:
to tag satellite data chips with information on atmospheric conditions and land use/land cover by performing image multioutput classification

#### Data:
- 3-band, 8-bit satellite data chips of size 256x256 pixels, being parts of Planet's '*visual product*' created based on imagery from ISS and Flock 2 satellite, characterized by GSD of app. 3.7 m, saved in *.jpg* format [1]
- training data annotation *.csv* file [1]

#### Study area and time:
data collected:
- over '*Amazon basin which includes Brazil, Peru, Uruguay, Colombia, Venezuela, Guyana, Bolivia, and Ecuador*' [1]
- '*between January 1, 2016 and February 1, 2017*' [1]

#### Processing steps:
part 1: EDA and data pre-processing
1. Downloading the source data using Kaggle API and unzipping it
2. Analyzing the training annotation file
3. Analyzing the training images

part 2: Baseline model - in progress <br>
part 3: PyTorch CNN models - in progress

#### Sources: 
[1] Kaggle competiton *Planet: Understanding the Amazon from Space*, section Data: https://www.kaggle.com/competitions/planet-understanding-the-amazon-from-space/data <br> 
[2] Kaggle API usage advices: https://stackoverflow.com/questions/55934733/documentation-for-kaggle-api-within-python <br>
[3] TorrentP Python library's GitHub page: https://github.com/iw4p/torrentp <br>
[4] Kaggle competiton *Planet: Understanding the Amazon from Space*, section Discussion: https://www.kaggle.com/competitions/planet-understanding-the-amazon-from-space/discussion <br> 
[5] Kaggle dataset *planets_dataset*: https://www.kaggle.com/datasets/nikitarom/planets-dataset <br>
[6] Introductory Jupyter Notebook presenting information on the source data; prepared by Planet: https://github.com/planetlabs/planet-amazon-deforestation/blob/master/planet_chip_examples.ipynb <br>
[7] multiprocessing Python library's GitHub page: https://docs.python.org/3/library/multiprocessing.html#module-multiprocessing <br>
[8] Jason Brownlee's SuperFastPython blog post: https://superfastpython.com/numpy-multithreaded-parallelism/ <br>
[9] dask Python library's GitHub page: https://docs.dask.org/en/stable/ <br>
[10] segment-anything Python library's GitHub page: https://github.com/facebookresearch/segment-anything
