# 第7組 Homework 5 optional (Heroku)
組員：黃志翰、陳璽文、秦立謙

## Step 1 : Git clone & environment setting
首先先將我們HW5的成果clone下來(不是使用老師的L16檔案)，並安裝需要的套件(Heidi SQL + pip install + Herohu Sign up)

pip install 
gunicorn   
Flask 
Jinja2
psycopg2 
sklearn 
pandas  
numpy 

![](https://github.com/Coldtee/AIoT_hw5_optional/blob/master/optional%20img/1.png)

## Step 2 : Git clone & environment setting
參考老師影片與程式碼，將原本是mysql的部分改為psycopg2的語法

![](https://github.com/Coldtee/AIoT_hw5_optional/blob/master/optional%20img/2.png)

## Step 3 : Heroku postgres設定
參考老師影片與程式碼，將原本是mysql的部分改為psycopg2的語法
![](https://github.com/Coldtee/AIoT_hw5_optional/blob/master/optional%20img/3.png)
![](https://github.com/Coldtee/AIoT_hw5_optional/blob/master/optional%20img/4.png)
![](https://github.com/Coldtee/AIoT_hw5_optional/blob/master/optional%20img/5.png)
![](https://github.com/Coldtee/AIoT_hw5_optional/blob/master/optional%20img/6.png)

## Step 4 : Heidi sql設定與Heroku postgres連線
因為
將postgres的Database Credentials填入heidi sql中
![](https://github.com/Coldtee/AIoT_hw5_optional/blob/master/optional%20img/7.png)
![](https://github.com/Coldtee/AIoT_hw5_optional/blob/master/optional%20img/8.png)
![](https://github.com/Coldtee/AIoT_hw5_optional/blob/master/optional%20img/9.png)
![](https://github.com/Coldtee/AIoT_hw5_optional/blob/master/optional%20img/10.png)
![](https://github.com/Coldtee/AIoT_hw5_optional/blob/master/optional%20img/11.png)
![](https://github.com/Coldtee/AIoT_hw5_optional/blob/master/optional%20img/12.png)

因為sql有語法不同，所以要修改一些細節部分(例如'id' -> id)
修改方法是參考老師影片中當老師匯入postgres.sql, 看上面的sql語法作修改
![](https://github.com/Coldtee/AIoT_hw5_optional/blob/master/optional%20img/13.png)

## Step 5 : VScode 設定
將postgres的Database Credentials填入vscode中
![](https://github.com/Coldtee/AIoT_hw5_optional/blob/master/optional%20img/14.png)

## Step 6 : Local執行
![](https://github.com/Coldtee/AIoT_hw5_optional/blob/master/optional%20img/15.png)
![](https://github.com/Coldtee/AIoT_hw5_optional/blob/master/optional%20img/16.gif)

## Step 7 : Heroku & Github 連結
![](https://github.com/Coldtee/AIoT_hw5_optional/blob/master/optional%20img/17.png)
![](https://github.com/Coldtee/AIoT_hw5_optional/blob/master/optional%20img/18.png)
![](https://github.com/Coldtee/AIoT_hw5_optional/blob/master/optional%20img/19.png)
![](https://github.com/Coldtee/AIoT_hw5_optional/blob/master/optional%20img/20.png)

因為我是用自己組別的HW5，又Heroku deploy brench需要requirementS和runtime等來判斷語言，所以複製老師的檔案，才能Deploy成功。
沒有requirements.txt(s很重要):
![](https://github.com/Coldtee/AIoT_hw5_optional/blob/master/optional%20img/21.png)
有requirements.txt，成功(s很重要):
![](https://github.com/Coldtee/AIoT_hw5_optional/blob/master/optional%20img/22.png)
![](https://github.com/Coldtee/AIoT_hw5_optional/blob/master/optional%20img/23.png)

## Step 8 : 成果
同樣因為我是用自己組別的HW5，所以要加入Procfile(不是txt檔，否則會出現app error!)
![](https://github.com/Coldtee/AIoT_hw5_optional/blob/master/optional%20img/24.png)

web: https://aiothw5optional.herokuapp.com/