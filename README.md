# Statistics

## 환경 설정

Jupyter notebook 실행

```bash
git clone git@github.com:archmagece/archmagece-univ.git
docker run --rm -p 8888:8888 -v $(pwd)/archmagece-univ:/home/jovyan scriptonbasestar/sb-jupyter:version-20190914

docker run --rm -p 8888:8888 -v $(pwd)/archmagece-univ:/home/jovyan/work --notebook-dir=/home/jovyan/work scriptonbasestar/sb-jupyter:version-20190914
```
