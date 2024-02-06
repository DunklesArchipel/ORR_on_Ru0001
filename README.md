
This project contains the evaluated data files for the article
"Impact of the potential dependent surface adlayer composition on the ORR activity and H2O2 formation on Ru(0001) in acid electrolytes".

The subfolders contain the final figures found in the submitted manuscript and the supporting information.

Among the final PNG, also the SVG files are included which are based on the raw PNG obtained from the data evaluation.
The CSV contain the data for the individual traces in the figures, where ***r*** and ***b*** refer to the red and blue curves, respectively.

The YAML files contain the metadata associated with the investigated system, such as the electrolyte composition or the suppliers of the electrodes.
The YAML file also includes information on the units for the different columns including a description how the columns were generated.

For convenience the CSV and YAML have been packed into a frictionless based [unitpackage](https://echemdb.github.io/unitpackage/) (JSON file).
These can be loaded with [unitpackage](https://echemdb.github.io/unitpackage/) module, as illustrated in the [example notebook](./doc/explorer.ipynb).

To explore the content of this repository locally clone the repository:

```sh
git clone git@github.com:DunklesArchipel/ORR_on_Ru0001.git
```

The dependencies can be found in the [environment file](environment.yml).
If you have conda or mamba installed you can execute the notebook locally with jupyter.
Replace `conda` with `mamba`, respectively.

```sh
cd ORR_on_Ru0001
conda env create -f environment.yml
conda activate ru-orr
jupyter notebook
```

Select the respective file in the jupyter file browser and have fun.
