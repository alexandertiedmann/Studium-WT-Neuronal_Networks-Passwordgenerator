# Password-generator
Ein Passwort-Generator, der mithilfe einer RNN-Architektur Passwörter generiert.
Für weitere Informationen bitte ins Notebook schauen

## Getting Started

### Vorraussetzungen
```
Python 3.7
Jupyter Notebook
Pytorch
CUDA 10.0
```

### Installation
Nach der Installtion von Python 3 können via Commandline die Python-Packages installiert werden:
```
python -m pip install --upgrade pip
python -m pip install jupyter wget
```

Installation von PyTorch:
```
python -m pip install https://download.pytorch.org/whl/cu100/torch-1.1.0-cp37-cp37m-win_amd64.whl
python -m pip install https://download.pytorch.org/whl/cu100/torchvision-0.3.0-cp37-cp37m-win_amd64.whl
```

## Running
Die .ipynb-Datei kann nach der Installation der Vorraussetzungen per jupyter geöffnet werden.
Danach kann das Notebook mit einem Klick auf 'Run' ausgeführt werden.
```
jupyter notebook ./PasswordGenerator.ipynb
```

## Built With
* [PyTorch](https://pytorch.org/) - Deep Learning Library

## Authors
* **Alexander Tiedmann** - *Code* - [alexandertiedmann](https://github.com/alexandertiedmann)
* **Matthias Baidinger** - *Code* - [BaiMatthias](https://github.com/BaiMatthias)

See also the list of [contributors](https://github.com/alexandertiedmann/password-generator/contributors) who participated in this project.

## Acknowledgments

* [PyTorch Tutorial - char rnn classification](https://pytorch.org/tutorials/intermediate/char_rnn_classification_tutorial.html)
* [Password Lists](https://www.scrapmaker.com/)
