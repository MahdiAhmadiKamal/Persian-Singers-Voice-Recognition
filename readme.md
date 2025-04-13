# Persian Singers Voice Recognition 🎤🎼


<img src="pics\audio-preprocessing-feature-extraction-machine-learning-based-classification.png" width="600">

This deep learning project belongs to voice classification of 5 persian singers. This project is built with the aid of [pydub](https://github.com/jiaaro/pydub). Finally, a telegram bot has been created that receives the song and predicts the name of the singer.


## How to install
Run this command:
```
pip install -r requirements.txt
```

## How to run
+ Collect the voices of as many singers as you want in raw_data folder.
+ Perform post-processing on the data using `extract_vocals.ipynb` and `make_dataset.ipynb`.
+ Run this command to train model on your own dataset:

```
jupyter nbconvert --to script train.ipynb
```

+ Run this command to run telegram bot:

```
jupyter nbconvert --to script pydio_classifier_bot.ipynb
```

## Results

<img src="pics\output.png" width="500">

Output
| Accuracy | Categorical Ccrossentropy Loss |
| --------------- | --------------- |
| 0.84 | 0.73 |
