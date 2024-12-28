**Data Description** <br/>
This dataset was originally published in the paper: [Paper](https://arxiv.org/abs/1909.03242). We proposed an algorithm and applied several preprocessing steps to adapt it for our experiments (see our paper for details).


Summary of the MultiVerify dataset:

| Domain | Claim # | Refute | Support |
| ------ | ----- | -------- | -------- |
| Culture &  Entertainment | 4,988 | 3,934 | 854 |
| Science & Technology | 3,143 | 1,507 | 1436 |
| General | 8,968 | 5,951 | 3,017 |
| Politics | 9,967 | 6,701 | 3,266 |
| Social &  News | 3,380 | 2,155 | 1225 |



**Data Format** <br/>

The attributes of each claim are as follows:
claimID, claim, claimURL, reason, speaker, checker, tags, articleTitle, publishDate, claimDate, entities, image_path, label (0 = Refute, 1 = Support)

The attributes of each text evidence are:
id, ref_id (The claim id that this evidence document is relevant to), text

