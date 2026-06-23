# WikiBio-mini dataset generation


## Usage
The notebook `generate-wikibio-mini-dataset.ipynb` generates `wikibio-mini.csv`.
- Cleans data to reduce size and ensure that every item has the same metadata (first name, nationality, etc.)
- Uses AI-generated code (prompts in comments) to show an AI-assisted workflow



## Sources
Data drawn from WikiBio:
> Neural Text Generation from Structured Data with Application to the Biography Domain
>
> Rémi Lebret, David Grangier and Michael Auli, EMNLP 2016
>
> http://arxiv.org/abs/1603.07771

Based on the license of the above data, the condensed dataset in `wikibio-mini-csv` is also licensed under [Creative Commons Attribution-ShareAlike 3.0 Unported License](https://github.com/rlebret/wikipedia-biography-dataset/blob/master/LICENSE.txt).

More information about the data source is here: https://lebret.ch/wikipedia-biography-dataset/
