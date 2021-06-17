# first-coding


from urllib.request import urlopen
from urllib.parse import quote_plus

from bs4 import BeautifulSoup
from selenium import webdriver
import pandas as pd
import time

from selenium.webdriver.chrome.webdriver import WebDriver
from selenium.webdriver.common.keys import Keys
from selenium.webdriver.support.ui import WebDriverWait
from selenium.webdriver.support import expected_conditions as EC
from selenium.webdriver.common.by import By

import re
import csv
import random


driver = webdriver.Chrome(executable_path='(driver) chromedriver.exe') #가상 크롬 드라이버 열기



driver.close()  # 가상브라우저 닫히는 코드.
driver.quit() # 가상브라우저 끄는 코드.
