# ML-Antivirus

[Run](https://i.imgur.com/PUk9GAp.png)

An antivirus powered by machine learning. The antivirus is first trained using 5 different machine learning algorithms and the best one is automatically chosen after training. The trained machine learning model is then saved for later use by the main script. 

## Usage

To train the antivirus,

```bash
python train.py
```

To run the antivirus,

```bash
python antivirus.py [PATH_TO_PE_FILE]
```