# FlightVideosDownloader
A Youtube Video scraper and downloader via python. The Python script pulls the Title of the video, the number of views. In addition to the information provided the program downloads the highest resoultion of the video and converts the file into an mp4 file. When downloaded, the file contains a png showing successful deployment to targeted folder. 

Ran via a command prompt in IntelliJ IDEA. The youtube link is copied either from the share link or the https:// web link in the browser and brought to the Terminal and then the link concatenated with the desired downloaded folder. In the windows command prompt which is the Terminal used, you must verify that the pytube package is installed, doing so via the command pip install pytube and then hitting enter. There will be a download interface shown with a respective progress bar below the command prompt used. 

Further design to this project would be the implemantation of a progress bar using the Python Package TQDM which "derives from the Arabic word taqaddum (تقدّم), meaning progress", basically allows the user to see the video being downloaded in real time. 
The link where I obtained the quote and information is provided: https://pypi.org/project/tqdm/  
