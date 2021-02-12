# MeOffendEs

This repository contains the data for the MeOffendEs@IberLEF task.

## OffendEs subset corpus


- Development data (trial data): 100 samples
  * devdata1.tsv --> `comment_id, comment`
  * devdata2.tsv --> `comment_id, comment, label, influencer, influencer_gender, media`
  * devgold.tsv --> `comment_id, label, confidence`

- Train data: 16,710 samples
  * traindata1.tsv --> `comment_id, comment, label`
  * traindata2.tsv --> `comment_id, comment, label, influencer, influencer_gender, media`

- Test data: 13,606 samples
  * testdata1.tsv --> `comment_id, comment`
  * testdata2.tsv --> `comment_id, comment, influencer, influencer_gender, media`
