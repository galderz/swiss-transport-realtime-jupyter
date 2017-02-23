# swiss transport station board analysis notebook

Here is a jupyter notebook to analyse the data linked to the talk https://www.slideshare.net/alexmass/swiss-transport-in-real-time-tribulations-in-the-big-data-stack presented at Softshake Genève in 2016 and VoxxedDay/Zürich 2017

### Contains:
  
  * `stationboard-analysis.ipynb`: the notebook
  * `data/stops.txt`: the list of stations with geographical coordinates

Load data (too large for github)
  * download [`station-boards-dump-4-months.tsv.gz`](https://extranet.octo.com/oft/viewfile.php?fileid=63dee48857eb22effaaef6230e1a45ec&dl=) with 4.5 months of logged data, and unzip it into `data/station-boards-dump-4-months.tsv`

### How to run

Launch jupyter from the repository where you cloned this repository and open `stationboard-analysis.ipynb`.
Just run the cells (it can take up to a few minutes to load the tsv and parse/add columns.

Et voilà!

### Author

Alexandre Masselot amasselot@octo.com