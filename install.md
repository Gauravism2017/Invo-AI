[![Python 3.7](https://img.shields.io/badge/python-3.7-green.svg)](https://www.python.org/downloads/release/python-360/)
![](https://img.shields.io/badge/Grid2.0-Submission-brightgreen)
![](https://img.shields.io/badge/Grid2.0-Installation%20Instruction-blue)

# DOC SCANNER
A python command line application to convert scanned invoice pdf to spreadsheet

## Installation

Clone the git repository:

```
git clone https://github.com/AyushSomani001/Digital_Invoicing_Grid2.0.git
cd Digital_Invoicing_Grid2.0
```

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install requirements.

```bash
pip install -r requirements.txt
```
Using Conda 
```
conda install --file requirements.txt
```
#### Note:
We need to install tesseract and pass executable as argument or in ```{root}/cfg/cofing.py``` as ```TESS_EXEC``` \
For Windows we need to installer poppler , we can install using conda
```
conda install -c conda-forge poppler
```
#### Traindata used in this project. Use for better result [eng.traindata](https://github.com/tesseract-ocr/tessdata_best/raw/master/eng.traineddata). Place it in tessdata folder in tesseract-ocr installation folder.   
#### tesseract version used : v5.0.0



## Usage

```python
python invoice.py -i [pdf file name] -o [output folder]
```



