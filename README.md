# HIV evolution
Semester research project in the framework of training at the Institute of bioinformatics.

# Goals and objectives of the project:
The main goal of the project is to study the physicochemical properties of HIVa during its evolution 
and to predict these properties in the future.

# Data
The main data source is https://hiv.biozentrum.unibas.ch/ HIV sequencing data by day.

And https://www.uniprot.org/ proteomes of viruses, people and bacteria.

# Methods
For the research, machine learning methods were used, namely a random forest trained at the amino acid frequencies of 
protein from proteomes of organisms taken from the site https://www.uniprot.org/. In order to track physico-chemical changes, 
data from the site were used https://hiv.biozentrum.unibas.ch/ , protein virulence was predicted by the constructed classifier. As well as some 
physico-chemical properties of HIV.

# Results
Example region V3 virulence reduction:

![](https://i.ibb.co/zJqcDTf/2019-12-17-09-12-01.png)

# Dependencies
- OS: Any Linux kernel system
- Python >= 3.7
- scikit-learn
- numpy
- matplotlib
- seaborn
- pickle

**As well as all their dependencies.

# Gratitude
Institute of Bioinformatics, as well as supervisor Tsvetkov V.O. for the opportunity to work on the project, 
as well as A. Kravets for help and discussion.
