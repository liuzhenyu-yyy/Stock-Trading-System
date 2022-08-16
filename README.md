# Stock Trading Simulator
 A simple stock trading simulator website based on [Flask web framework](https://flask.palletsprojects.com/en/2.2.x/). Multiple operations including qouting, purchasing, selling coule be performed to simulate real stock operations.
 
 <img align="center" src="https://raw.githubusercontent.com/liuzhenyu-yyy/Stock-Trading-System/main/assets/demo.png" width=800/>
 
## Description

 This is my final project in "	Introduction to Computer Science and Programming"  Course of [Prof. Junlin Lu](https://cs.pku.edu.cn/info/1179/1481.htm) in the spring semaster of 2018, adopted from the [finance lab](https://docs.cs50.net/2018/x/psets/7/finance/finance.html) in CS50 course of Harvard University. Here we developed a website to simulate stock trading operations with friendly graphical user interface.
 
## Dependency

 The website is built with [Flask web framework](https://flask.palletsprojects.com/en/2.2.x/) of Python. The website runs on following dependencies:
 - SQL
 - cs50
 - Flask
 - Flask-Session
 In addition, the software works only on Linux or Mac OS system. For windows users, please consider virtual machine or windows subsystem linux.
 
## Start the web page
To start the stock trading simulator website, clone the repo or download all the files into the folder `Stock-Trading-System`.
After installing all dependencies, change working directory to `Stock-Trading-System` and run：

```
flask run
```
 <img align="center" src="https://raw.githubusercontent.com/liuzhenyu-yyy/Stock-Trading-System/main/assets/run.png" width=1000/>
 
Then the website could be accessed with the URL outputted by `flask`, typically http://127.0.0.1:5000

## Demostrations:
### Login page:
 <img align="center" src="https://raw.githubusercontent.com/liuzhenyu-yyy/Stock-Trading-System/main/assets/login.png" width=700/>

### Purchase:
 <img align="center" src="https://raw.githubusercontent.com/liuzhenyu-yyy/Stock-Trading-System/main/assets/buy.png" width=700/>

### Sell:
 <img align="center" src="https://raw.githubusercontent.com/liuzhenyu-yyy/Stock-Trading-System/main/assets/sell.png" width=700/>
 
 ### History:
 <img align="center" src="https://raw.githubusercontent.com/liuzhenyu-yyy/Stock-Trading-System/main/assets/history.png" width=700/>
