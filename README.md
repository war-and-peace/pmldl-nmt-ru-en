# Neural Machine Translation: Russian-English

The repository contains two neural machine translation models developed for submission to the third assignment in Practical Machine Learning and Deep Learning course at Innopolis University. 



## Transformer model

The first model we used is the same model we developed for Practical Machine Learning and Deep Learning course project. In the project we trained a transformer model on **Yandex** dataset for English-Russian translation task. For this assignment we trained the same model for Russian-English task on the same dataset. The **GitHub** repository for the project can be found [here.](https://github.com/war-and-peace/neural-machine-translation)




## Facebook FAIR's transformer model

For the second model we chose a pretrained model that was developed by Facebook FAIR for the submission to WMT: Workshop on Statistical Machine Translation 2019. They competed in 4 tasks with this model: English-German, English-Russian (to and from, in both cases) and won in all of them. The model itself is very big (around 10 GBs) and we used it from Torch hub. The GitHub repository of the model can be found [here.](https://github.com/pytorch/fairseq)

### Reference

Nathan Ng, Kyra Yee, Alexei Baevski, Myle Ott, Michael Auli, & Sergey Edunov. (2019). Facebook FAIR's WMT19 News Translation Task Submission.
