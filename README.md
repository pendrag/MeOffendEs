# MeOffendEs

This repository contains the data for the MeOffendEs@IberLEF task. All zip files are password-protected. Access to data will be granted to participants of [MeOffendEs](https://competitions.codalab.org/competitions/28679) workshop at IberLEF 2021. 

## OffendEs subset corpus

- Development data (trial data): File **offendes-devdata.zip** (100 samples)
  * devdata1.tsv --> `comment_id, comment`
  * devdata2.tsv --> `comment_id, comment, label, influencer, influencer_gender, media`
  * devgold.tsv --> `comment_id, label, confidence`

- Train data: File **offendes-traindata.zip** (16,710 samples)
  * traindata1.tsv --> `comment_id, comment, label`
  * traindata2.tsv --> `comment_id, comment, label, influencer, influencer_gender, media`

- Test data: File **offendes-testdata.zip** (13,606 samples)
  * testdata1.tsv --> `comment_id, comment`
  * testdata2.tsv --> `comment_id, comment, influencer, influencer_gender, media`
  
## OffendMex subset corpus

- Development data (trial data): File **mx-devdata.zip** (76 samples)
  * mx-trial-data.csv --> `each row in this file is associated to a sample in the dataset, the first row (headers) should be discarded`
  * mx-trial-names-csv  --> `Description of the information (columns) in mx-trial-data.csv`
  * mx-trial-vulgarity-label.csv  --> `Vulgarity label for each sample in mx-trial-data.csv, this information will be only available for trial and training data`
  * mx-trial-outputs.sol --> `ground truth labels for samples in mx-trial-data.csv`
