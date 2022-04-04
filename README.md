# DAKO-k22 Group Work

The group work for the Data analytics course in TUAS

## Task and background



## Train and test data

The data used is from [Kaggle Titanic ML Competition](https://www.kaggle.com/competitions/titanic), and Kaggle is used to evaluate our models as well. To use the notebook you must provide the data in `notebooks/data` directory. This is easily done by downloading the data zip file and extracting `train.csv` and `test.csv` from it into the data directory. Please note that the zip or it's contents should **not** be committed to the repository.

## Development environment

There is a `docker-compose.yml` file for those who want to use Docker as their development environment. Our project file `notebooks/dako-gw-grp2.ipynb` is available there, but feel free to use it outside of Docker as well.

The Docker environment can be started simply with `docker-compose -up` and stopped with `^c`.

