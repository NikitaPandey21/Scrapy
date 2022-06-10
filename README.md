# Scrapy

## Intall Python and IDE

## on admin cmd 
pip install pipenv
Create Virtual environment: **virtualenv .  **
Activate virtual environment: **.\Scripts\activate**
Install Scrapy inside virtual Environment:** pip install Scrapy 
**

Create Scrapy project 
scrapy startproject <projectName>

packages to install 
pylint  -> analysis tool helps for programming error 
autopep8 -> formats python code 
ipython -> provided rich toolkit to help make python interactive 

command 
scrapy shell -> enter into scrapy terminal 
scrapy crawl <spiderName> -> to execute scrapy code, make sure you are at the level of scrapy.cfg

create spider 
scrapy genspider <spidername> <URL>
scrapy genspider -t <spiderType> <spidername> <URL>

list spider types 
scrapy genspider -l
