# screenshot_automator
Automake screenshot + keyboard key press within an app using just python. 

This notebook was created to make screenshot extract from a book using only python and original ebook reader.   
The usage is trivial:
1. Specify REGION of the screen to make screenshot (left, top, width, and height of the region to capture). You may use locate_position to find the correct pattern
2. Open the 3rd party app
3. Specify make_n_pages params with counter start, number of pages (iterations), and pass REGION
4. Run the notebook and make sure the focus is on the 3rd party app

Dependencies: ``` pip install pyautogui```
