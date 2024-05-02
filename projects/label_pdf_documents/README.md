# Labeling of pdf documents
## Preview
![preview](https://github.com/krauhen/ai-playground/assets/167354464/bb485230-e1fd-476a-a00e-4eae0d39dd4f)

## Repositories used
- arXiv grabber/downloader: https://github.com/titipata/arxivpy
- PDF 2 image: https://github.com/Belval/pdf2image
- Open-Source labeling tool: https://github.com/HumanSignal/label-studio

## Influential Papers
- https://arxiv.org/pdf/2206.01062.pdf
- https://arxiv.org/pdf/1706.02337.pdf
- https://dl.acm.org/doi/pdf/10.1145/3219819.3219834

# Setup
## Install environments
```shell
$ python -m venv venv
$ source venv/bin/activate
$ pip install -r requirements.txt
```
## Start jupyterlab and mlflow
```shell
$ jupyterlab --port 9999 $
$ mlflow server --host 127.0.0.1 --port 8080 $
```
