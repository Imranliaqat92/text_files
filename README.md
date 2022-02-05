# text_files
passwords files
####code
import pyautogui
from tkinter.constants import X
import time 
time.sleep(5)
file = open('opt.txt', 'r')

for each in file:
    pyautogui.click()
    pyautogui.typewrite(each)
    pyautogui.press('enter')
for i in range(4):
    pyautogui.press('backspace')

