conda create -n youtube python=3.11 -y

conda activate youtube

pip install -r requirements.txt


## DVC

dvc init

dvc repro

dvc dag



## AWS

aws configure



### Json data demo in postman

http://localhost:5000/predict

```python
{
    "comments": ["This video is awsome! I loved a lot", "Very bad explanation. poor video"]
}
```



chrome://extensions


## How to get youtube api key from GCP

https://www.youtube.com/watch?v=i_FdiQMwKiw






echo "# Youtube-Sentiment-Chrome-Plugin-Mlops-Project" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/Arqamansari23/Youtube-Sentiment-Chrome-Plugin-Mlops-Project.git
git push -u origin main