# Language Detection App

### 1. Develop and save the model with this Colab

[Open Notebook](https://colab.research.google.com/drive/1cvE5SWsrMizNjEd20iqX8-pqHO8kxXe3?usp=sharing)

### 2. Create Docker container

```bash
docker build -t app-name .

docker run -p 80:80 app-name
```

### 3. Create Git repo

If you clone this repo this step is not needed. Or you can delete this git repo with `rm -rf .git` and start with a new one:

```bash
git init
git add .
git commit -m "initial commit"
git branch -M main
```
