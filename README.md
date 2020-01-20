

# Data Challenge MDI343 TELECOM PARISTECH

> The project aims to predict gender of person from a photo: 1: female, +1: male, 0: cannot be decided

## Challenge results:

[https://www.dropbox.com/s/uomf1gwrpeirhqi/challenge_debrief.pdf?dl=0]

## Project Description

The objective is to predict the gender of a person (man or woman) from characteristics extracted from a photo.
The data are provided by the company Morpho: http://www.morpho.com/fr.

The file that each must provide is a .txt file of 4991 lines: b 1, 0, -1 ...
where each line contains the prediction. Unlike a binary classification problem where y = 1 or y = -1, you have the ability to predict 0, which means you don't know. There are 4991 images in the validation set.

### Performance criteria

You can therefore respond for each image: man (y = 1), woman (y = -1) or I-don't-know (y = 0).
To make a mistake costs 10 points and not knowing costs 1 point.
### Learning data:

data / training_templates.csv

data / training_labels.txt

### Validation data:

data / testing_templates.csv
## Requirement

- Python 3.7.1
- numpy 1.18.1
- pandas 0.25.3
- matplotlib 3.1.1
- sklearn 0.22.1


## Usage example

launch Jupyter notebook into terminal:

    $ jupyter notebook

Then open notebook [Notebook.ipynb]([https://github.com/ericfokou/Data_Challenge_MDI343_TELECOM/blob/master/Notebook.ipynb])

## Release History

* 0.0.dev0
    * First development  release 

## Questions?

If you find a bug, feel free to write me [fokoub@gmail.com](mailto:fokoub@gmail.com).

## Contributing

Fork it:

	$ git clone https://github.com/ericfokou/Data_Viz_Income_inequalities

Then create your feature branch and commit your changes.

## Support

Eric FOKOU 

- email: [fokoub@gmail.com](mailto:fokoub@gmail.com)
- Twitter: <a href="http://twitter.com/fokou_eric" target="_blank">`@fokou_eric`</a>



