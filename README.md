# Cargador Genérico de Tablas - CGT
Private Repository

### Repository
Set remote and clone:
```bash
git clone git@github.com:edronald7/aws-data-ingest-cgt.git
git remote set-url origin git@github.com:edronald7/aws-data-ingest-cgt.git

git add .
git commit -m "Stage ..."
git push origin 
```

Python version: 3.8x
## Libraries & OS
IDE Jupyter Lab, libraries:
- numpy
- pandas

Installing:
```bash
pip install -r requirements.txt
```

O.S.: Debian / Ubuntu / MacOS

## Execution
Edit the date ranges in tha python file Model2FA.py:
```python
...
if __name__=='__main__':

    n_samples_per_day = 10

    start_date = date(2021, 1, 1)
    end_date = date(2021, 3, 31)
...
```
Run on console:
```bash
$ python Model2FA.py

```



## Team 
- edronald7@gmail.com

2022 Oct