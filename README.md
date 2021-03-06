# MeOffendEs

This repository contains the data for the MeOffendEs@IberLEF task. All zip files are password-protected. Access to data will be granted to participants of [MeOffendEs](https://competitions.codalab.org/competitions/28679) workshop at IberLEF 2021. 

The folder `scorers` contains the programs for evaluating each dataset as used by Codalab competition.

## OffendEs subset corpus

- Development data (trial data): File **offendes-devdata.zip** (100 samples)
  * devdata1.tsv --> `comment_id, comment`
  * devdata2.tsv --> `comment_id, comment, label, influencer, influencer_gender, media`
  * devgold.tsv --> `comment_id, label, confidence_list`
  
  `confidence_list` is a list with four probability values (the sum up 1.0), one per each possible label in this order: `[NO_prob, NOM_prob, OFP_prob, OFG_prob]`

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

- Training data: File **mx-traindata.zip** (5060 samples)
  * mx-train-data-non-contextual.csv --> `tweets without contextual information, each row in this file is associated to a sample in the dataset, the first row (headers) should be discarded`
  *  mx-train-data-contextual.csv --> `tweets including contextual information, each row in this file is associated to a sample in the dataset, the first row (headers) should be discarded`
  * mx-train-names-csv  --> `Description of the information (columns) in mx-train-data-non-contextual.csv`
  * mx-train-vulgarity-label.csv  --> `Vulgarity label for each sample in the data files mx-train-data-contextual.csv and mx-train-data-non-contextual.csv, this information will be only available for trial and training data`
  * mx-train-outputs.sol --> `ground truth labels for samples in mx-train-data-contextual.csv and mx-train-data-non-contextual.csv`

- Test data: File **mx-test-data.zip** (2183 samples)
  * mx-test-data-non-contextual.csv --> `tweets without contextual information for the test set, each row in this file is associated to a sample in the dataset, the first row (headers) should be discarded`
  *  mx-test-data-contextual.csv --> `tweets including contextual information for the test set, each row in this file is associated to a sample in the dataset, the first row (headers) should be discarded`
  * mx-test-names-csv  --> `Description of the information (columns) in mx-test-data-non-contextual.csv`


