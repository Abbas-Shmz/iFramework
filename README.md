# StudioProject
Studio (**St**reet **U**sers **Di**rect **O**bservation) is an ongoing PhD project at Polytechnique Montréal 
developed under the supervision of [Prof. Nicolas Saunier](http://n.saunier.free.fr/saunier/) 
and [Dr. Owen Waygood](https://www.polymtl.ca/expertises/en/waygood-owen).
The aim of this project is to clean, validate, and analyze the trajectory of street users obtained from 
[TrafficIntelligence](https://trafficintelligence.confins.net) (TI), 
an open-source video analysis project developed at Polytechnique Montréal. 
TI uses video analytics to track and identify street users.

The Studio application offers a set of tools for evaluating urban streets in terms of their three primary 
functions: transit, access, and place. This evaluation is done through direct observation of street users. 
To this end, the Studio application employs a comprehensive framework, detailed in this 
[link](https://www.mdpi.com/2071-1050/14/12/7184),
as its underlying scheme to analyze the trajectories extracted through TI. Based on the framework, 
two spatial units including *screenline* and *zone* are applied in this application to capture the movement of 
street users. 

The StudioProject application is primarily designed for manipulating and analyzing the output trajectories 
of TI. However, it also offers tools for manual data collection through the review of video files.

The Studio application comprises two primary windows: a video player and an observation panel.

## Video player
The primary purpose of the video player window is to facilitate the review of collected videos for 
extracting necessary information. Additionally, this window provides various tools for tasks such as 
creating new projects, opening existing projects, and generating a mask file.

To store relevant details related to a study, such as the video's name, current time, application window 
size and position, database file name, metadata file path, and other associated information, users can 
save them in an XML file named project file with a *.prj extension. This project file allows users to 
preserve their work settings and conveniently reopen the application with the same configuration at a 
later time. 

The following image presents a snapshot of the video player window in the Studio application.

![Video player](https://github.com/Abbas-Shmz/StudioProject/blob/main/images/Studio_Video-player.jpg)

## Observation panel
The Studio application provides an observation panel, which includes multiple tabs and a side toolbar. 
This panel enables the recording and analysis of observations related to street users. 
The observations can be conducted by trained observers or by analyzing the trajectories obtained 
from the IT system.

### Trained observer
This method involves conducting observations on street users by employing trained observers to collect 
information. Observations can be recorded manually on the roadside or by reviewing videos. 
The collected data can be stored in a database using the tools provided in the observation panel. 
The database will be utilized to extract valuable information related to the main street functions. 
The image below displays the manual observation recording tools offered by the Studio application.

![Panel_1](https://github.com/Abbas-Shmz/StudioProject/blob/main/images/Studio_Panel_01.jpg)

### Analyzing the trajectories
The trajectories obtained from TI provide valuable information about the position, speed, acceleration, 
and type of street users. This information can be utilized to derive useful indicators that help in 
understanding how people utilize streets. 
To facilitate this analysis, the Studio application offers a set of tools for extracting the number of 
street users crossing screenlines or entering/exiting specific zones. 
These tools generate information that can be further utilized to derive indicators such as the count 
of street users passing through over time, the density of people in a particular area, and the number 
of accesses to specific zones, among others. The available tools are visually represented in the 
accompanying image.

![Panel_2](https://github.com/Abbas-Shmz/StudioProject/blob/main/images/Studio_Panel_02.jpg)

## Analysis toolbar
![Plot](https://github.com/Abbas-Shmz/StudioProject/blob/main/images/Studio_Plot.jpg)

![Table](https://github.com/Abbas-Shmz/StudioProject/blob/main/images/Studio_Table.jpg)

Icons made by <a href="https://www.flaticon.com/authors/freepik" title="Freepik">Freepik</a> from <a href="https://www.flaticon.com/" title="Flaticon"> www.flaticon.com</a>
