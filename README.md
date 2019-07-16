# finnish_ulmfit
Pretrained ulmfit for Finnish and a classification example.

This repository contains a pretrained UlmFit (https://arxiv.org/abs/1801.06146) model + an example notebook for using the model to create a classifier on text data (the data is in Finnish). The validation perplexity (calculated by exponentiating the validation cross entropy loss) was about 23.8. The model training was done using a single Tesla V100 GPU using the scripts from https://github.com/n-waves/ulmfit-multilingual . The training parameters were the defaults from the scripts with the modification of using a batch size of 200 and 10 epochs. Note that the large model files are stored using the git large file storage, so you need to set it up to download them. Check out https://git-lfs.github.com/

Training the model has been made possible by the work at Auria Biobank , located in the Turku University hospital and jointly owned by the hospital district of southwest Finland, hospital districts of Satakunta and Vaasa and the University of Turku.

Check out the websites: 

Auria biobank: https://www.auria.fi/en/index.php?lang=en

Auria Clinical informatics: https://www.auria.fi/tietopalvelu/en/index.php?lang=en
<pre>

</pre>

![Auria Biobank](/images/Logo_AURIA_2013_ENG.jpg)
