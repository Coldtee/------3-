# 第7組 Homework 5
組員：黃志翰、陳璽文、秦立謙

## Step 1 : Development Environment Setup
下載vs code，並於開啟後將需要的套件都安裝完畢。
1. Please install vs code, register github, install git for windows
2. (check-point 1) github create a new repository (aiot0524)
3. go to vs code clone this repository (choose new branch) 
4. vs code 安裝 python extension 
5. pip install flask, pandas, sklearn 
  * 快捷鍵 ctrl+shift+p ===> package manager 叫出 (git clone....)
  * 快捷鍵 ctrl+' ==> 叫出終端機 
6. (check-point 2) 為了要upload local file to github from local要終端機 C:> 設定下面 (不設定 branch default ='main')
   * C:> git config --global user.name "Huan Chen"
   * C:> git config --global user.email huanchen1107@gmail.com
   * C:> git commit -m "first commit"
   * C:> git remote add origin git@github.com:huanchen1107/aiot0524.git
7. Remeber to turn on xampp/MySQL (Apache is not necessary)

## Step 2 : flask test
理解老師程式碼後，使用老師提供的程式碼測試，並先上傳至github確保操作無誤。

執行結果:
![alt text](https://github.com/Coldtee/AIoT_hw5/blob/main/img/1.png)
![alt text](https://github.com/Coldtee/AIoT_hw5/blob/main/img/2.png)

## Step 3 : model training
利用老師L12給的資料( training.csv, training600.csv )訓練模型(在Colab上)。
訓練過程:
![alt text](https://github.com/Coldtee/AIoT_hw5/blob/main/img/3.png)
![alt text](https://github.com/Coldtee/AIoT_hw5/blob/main/img/4.png)
![alt text](https://github.com/Coldtee/AIoT_hw5/blob/main/img/5.png)
![alt text](https://github.com/Coldtee/AIoT_hw5/blob/main/img/6.png)

## Step 4 : 將模型導入程式
將我們訓練後的成果導入專案內，並上傳至github
![alt text](https://github.com/Coldtee/AIoT_hw5/blob/main/img/7.png)

## Step 5 : 完成
完成囉！
執行結果:
![alt text](https://github.com/Coldtee/AIoT_hw5/blob/main/img/8.png)
![alt text](https://github.com/Coldtee/AIoT_hw5/blob/main/img/9.png)
![alt text](https://github.com/Coldtee/AIoT_hw5/blob/main/img/10.gif)


