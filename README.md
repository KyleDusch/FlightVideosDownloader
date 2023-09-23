# FlightVideosDownloader
A Youtube Video scraper and downloader via python. The Python script pulls the Title of the video, the number of views. In addition to the information provided the program downloads the highest resoultion of the video and converts the file into an mp4 file. When downloaded, the file contains a png showing successful deployment to targeted folder. mp4 was chosen as I am able to obtain the video quality as well, instead of an mp3 which is only audio. I enjoy traveling so having this tool allows me to study and studying programming as well as I have high quality video content while on a long flight, so this tool has been super useful in my life currently. 

Ran via a command prompt in IntelliJ IDEA. The youtube link is copied either from the share link or the https:// web link in the browser and brought to the Terminal and then the link concatenated with the desired downloaded folder. In the windows command prompt which is the Terminal used, you must verify that the pytube package is installed, doing so via the command pip install pytube and then hitting enter. There will be a download interface shown with a respective progress bar below the command prompt used. 

Further design to this project would be the implemantation of a progress bar using the Python Package TQDM which "derives from the Arabic word taqaddum (تقدّم), meaning progress", basically allows the user to see the video being downloaded in real time. 
The link where I obtained the quote and information is provided: https://pypi.org/project/tqdm/  

![IntelliJ IDEA](https://img.shields.io/badge/IntelliJIDEA-000000.svg?style=for-the-badge&logo=intellij-idea&logoColor=white) 
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) 
![Windows Terminal](https://img.shields.io/badge/Windows%20Terminal-%234D4D4D.svg?style=for-the-badge&logo=windows-terminal&logoColor=white) 

