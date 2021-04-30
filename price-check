from selenium import webdriver
from time import sleep
from selenium.webdriver.common.keys import Keys
b=input("Please enter the short name of the stock price you want to learn.\n")
driver = webdriver.Chrome()
driver.get("https://tr.tradingview.com")
c=driver.find_element_by_xpath("/html/body/div[2]/div[3]/div/div[3]/form/label/tv-autocomplete/input")
c.send_keys(b)
c.send_keys(Keys.ENTER)
sleep(3)
i=0
print(driver.find_element_by_xpath("/html/body/div[2]/div[6]/div/header/div/div[3]/div[1]/div/div/div/div[1]/div[1]/span").text)
sleep(5)
driver.quit()
