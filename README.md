# Log Inspector
Log Inspector is Transformer model trained with Nginx log. Training data were classified with Isolation Forest.

Trained model is here: [huggingface.co/u-haru/log-inspector](https://huggingface.co/u-haru/log-inspector)

## Training
I used Google Colaboratory for training. If you use other environments, you will need to change the paths, filenames, etc.

1. Run IsolateAnnormalyLog.ipynb to parse log and train Isolation Forest model.
2. Run TransformAnnormalyLog.ipynb to train with predicted logs.

You may need to edit the code to improve the accuracy.
