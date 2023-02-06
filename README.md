# Introduction of Data Science
*Semester: 20201*

## 1. Requirements

### Instance Information
- OS: Ubuntu 20.04 Focal
- RAM: 8GiB
- Python: 3.8.5
- Golang: 1.13

### 1.1. Database
***
***<u>NOTE</u>:** Database is used to store data crawled from IMDB* </br>
***
We use MongoDB to store movie info record as soon as record had been successfully collected. </br>
***
***<u>How to install</u>: https://docs.mongodb.com/manual/tutorial/install-mongodb-on-ubuntu/***
***

### 1.2. Golang
***
***<u>NOTE</u>:** Golang is a programming language that support not only simple but also powerfull concurrent programming* </br>
***
We use go-colly framework to crawl data</br>
***
***<u>How to install</u>: https://linuxconfig.org/how-to-install-go-on-ubuntu-20-04-focal-fossa-linux***
***

### 1.3. Python requirements
***
***<u>NOTE</u>:** Described in <u>requirements.txt</u>* </br>
***

## 2. Workflow

*Raw data: <u>raw.csv</u> and <u>currency.csv</u>* </br>
*Download: https://drive.google.com/drive/folders/1WEW67rR_inLGKVtElL-uNN7XGfvmEFrL?usp=sharing*</br>
<u>**NOTE**</u>: In this **data** directory, *raw.csv* includes only 1000/491793 sample.

### 2.1. Clean
*cleaning.ipynb*

### 2.2. Describe 
*visualizing.ipynb*

### 2.3. Preprocess
*preprocessing.ipynb*

### 2.4. Content-based
*content_based.ipynb*

### 2.5. Session-based
*session_based.ipynb*

## 3. How to run

### 3.1. Install requirements

```
pip3 install -r requirements.txt
```

### 3.2. Run


- This is lite version so you only need to run *<u>demo.ipynb</u>*

- Opional: For testing, you need to download data from URL above then run sequentially the following files:
    - cleaning.ipynb
    - preprocessing.ipynb
    - content_based.ipynb
    - session_based.ipynb
    - demo.ipynb