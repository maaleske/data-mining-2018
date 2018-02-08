# data-mining-2018

Lecture on principles of data mining for the course "WETS1050 Environmental change in aquatic ecosystems" at JYU.

- [Introduction](./01-Introduction.ipynb)
- [Data processing](./02-Data_processing.ipynb)
- [Modeling](./03-Modeling.ipynb)
- [Model validation](./04-Validation.ipynb)

## Running the notebooks yourself

Easiest way is to use either [Anaconda or miniconda](https://anaconda.com), and install the required [dependencies](./requirements.txt) in a new environment using `conda create`:

```sh
conda create --name datamining2018 --file requirements.txt
```

Then activate the environment and run the notebook:

Linux:
```sh
. activate datamining2018
jupyter notebook
```

Windows:
```sh
activate datamining2018
jupyter notebook
```

### Contact

Matti A. Eskelinen (_matti.a.eskelinen at student.jyu.fi_)
Faculty of information technology, University of Jyväskylä
