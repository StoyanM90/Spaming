import time
import pyautogui 


time.sleep(5)


num_spam = 10

for _ in range(num_spam):
  pyautogui.typewrite("Spam")
    pyautogui.press("enter")
    time.sleep(1) # Wait for 1 second between each spam message
