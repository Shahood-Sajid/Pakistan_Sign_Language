How to run this repo:

Step 1: Clone this repo using this url https://github.com/Shahood-Sajid/pakistan_sign_language.git
Step 2: Create a virtual environment
Step 3: Activate the environment
Step 4: To simply run the application change directory to yolov5fish 
Step 5: Install the requirements using this command pip install -r requirements.txt
Step 6: Then open a code editor, open app.py file
Step 7: In line 15 model = torch.hub.load(), paste the directory path of yolov5 folder in the 1st parameter, and in the 3rd parameter paste the directory path of best.pt file which is located in yolov5 folder
eg. torch.hub.load("F:/pakistan_sign_language/yolov5", "custom", path ="F:/pakistan_sign_language/yolov5/best.pt", force_reload=True,source= 'local')
best.pt is the pre trained file for detection of pakistan sign language. (USE forward slash for the directory path i.e. /)
Step 8: Then in terminal run the application by using this command flask run.
Step 9: Copy the local address in the browser, and make signs