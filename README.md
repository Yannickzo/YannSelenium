Selenium Scripts are built to do some tedious tasks which can be automated using headless web browsers.
For example, Searching for some Questions on Different Search engines and storing results in a file by visiting each link. This task can take a long for a normal human being but with the help of selenium scripts one can easily do it
Now, Some of You may be wondering what is headless web browsers. It’s nothing but a browser that can be controlled using these selenium scripts for automation(web tasks).

How to Use selenium with Python and Linux Environment.
Python should already be installed. It can be 2.* or 3.* version. 
Steps: 
 

    Installing Selenium 
     
    Installing Webdrivers (headless) 
     
    Creating Simple Code 

Installing Selenium

Whatever Operating System You are Using Python command is Same for Installing Selenium Library.
First Method
Open Terminal/Cmd and Write Command as written Below
 

python -m pip install selenium


Installing Webdrivers

One Can Install Firefox, Chromium, PhantomJs(Deprecated Now), etc. 
 

    for using Firefox you may need to install GeckoDriver 
     
    for using Chrome you may need to install Chromium 
     

In this article, Firefox is used so One can Follow the Below Steps to Install:-
Steps for Linux:-
1. Go to the geckodriver releases page. Find the latest version of the driver for your platform and download it. 
For example: 
 

wget https://github.com/mozilla/geckodriver/releases/download/v0.24.0/geckodriver-v0.24.0-linux64.tar.gz

2. Extract the file with: 
 

tar -xvzf geckodriver*

3. Make it executable: 
 

chmod +x geckodriver

4. Move Files to usr/local/bin 
 

sudo mv geckodriver /usr/local/bin/