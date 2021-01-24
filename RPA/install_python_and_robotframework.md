


I am using a MacBook Pro on MAC OS X 10.11.6

### Ensure that you have Python3 installed:
+ Download the version of python for your computer.
  - **Your system and installation may be different**
    - If unsure how to proceed, consider using google and searching for ```<my operating system version> python 3 installation instructions```
    - i.e.  ```windows 10 python 3 installation instructions```
    - you should see instructions and videos on the topics to aid you.
  - To download Python3 I went to https://www.python.org/downloads and followed the link for the latest version for my mac.
    - ![](assets/notes-d5f8e4b7.png)
    - ![](assets/notes-c38f297e.png)
  - I ran the installation file and followed the prompts for my system.
    - Open the folder where you saved the download.
    - Double click the download file
      - ![](assets/notes-d37e664e.png)
    - Follow the on screen instructions
      - ![](assets/notes-d0d5f3fa.png)
      - ![](assets/notes-3054f234.png)
      - ![](assets/notes-e7673ae5.png)
      - ![](assets/notes-b6a8f282.png)
      - ![](assets/notes-97382687.png)
      - ![](assets/notes-753a1846.png)
    - Close the Install Python window
    - A window should pop up at the end of the installation with the SSL script. Be sure to kick that script off.
      - ![](assets/notes-b088346b.png)
      - ![](assets/notes-64896357.png)
+ Confirm that you have successfully installed Python on your system.
  - In my case, I will do so via terminal on my mac
    - ![](assets/notes-dd4fa97d.png)
    - ![](assets/notes-50d3e0e4.png)
  - I will first see if Python 3 is on my system
    - I can see that Python3 is installed on my system
      - ![](assets/notes-a4a82984.png)
  - I will then try and run Python3
    - ![](assets/notes-59d5f8d9.png)    
    - wahoo, eet verks!
  - exit
    - ![](assets/notes-85df1f7a.png)


+ Install and Verify robotframework

  - Install
    - ```pip3 install robotframework```
      - ![](assets/notes-a46eac72.png)
  - Verify
    - ```python3 -m robot --version```
      - ![](assets/notes-c2adb547.png)
  - In my situation I want to be able to call robot without python3 in the command.
    - to do this, I'm going to add the following directory to my path variable
      - I will edit my path statement in my user profile
        - ```vi /Users/username/.bash_profile```
        - for the path variable, I'll add the following to the front of the variable
          - ~/.local/bin/:
          - Before Edit:
            - ![](assets/notes-c7551d31.png)
          - After Edit:
            - ![](assets/notes-53d35e85.png)
  - I can now run the below command to verify robot is working:
    - ```robot --version```
      - ![](assets/notes-e3cf84ce.png)

I now have Python3 and Robot installed.

This is a good break for coffee. 
