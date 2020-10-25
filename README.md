# EEG-analysis
### Experiment
	The goal of our experiment part was to collect two types of data from each of us. On both of them, we had to solve two tasks but during one of these experiments, we listened to music. For experiments, we divide into pairs: one is the object of the experiment and one is control everything (provide a task for solving, manage time, collect data and clean the device after the experiment). Because of this one pair can do only one experiment in one day. Before starting record EEG data we apply the gel to electrodes for a better connection and to get clear data. For correctly collecting data we had a protocol. By this protocol, in the beginning, we had two calibration parts when we record data during just sitting and relaxing with closed and with open eyes each for two minutes. After this, we start solving the tasks which were theoretical from the operating systems course. We had around 25 minutes for each task and the 10 minutes for resting between these tasks. The only problem we had was about the charging controller that connects electrodes and pc software because we charged it for a long time but it was still uncharged. Also, I can notice that it was some uncomfortable for me to solve the theoretical tasks from the course about which I do not know anything. So, solving the task turned to search the answers on google.


### Analysis
	The goal of our analysis was to measure the power of alpha, theta, and beta bands. I specified on the calculation Event-Related Desynchronization (ERD) and for each of two parts (Control and Music), I create four data frames that show the ERD with relaxing with closed and with open eyes for two tasks. In these data frames, I show the power of alpha, theta, and beta bands in different parts of our head (frontal, central, and temporal). And using this data I plotted bar graphs in which we can compare the power of bands in different parts of the brain. All coding part I made in google colab in notebook format because there I can execute code by parts and add text fields like comments and add there my conclusions of observation. As I used colab I made analysis using python and libraries mne to work with EEG data in .edf format, NumPy to execute arrays of number data, and pandas to convert data to convert numbers and dicts to the data frame and plot the graphs. Also, I used the GitHub repo (link) for inspiration and to look at how to use the mne library.
This is the results that I get during the analysis:


### Results
	The main result that I got during the analysis is a confirmation of statements that I read in articles.  if we calculate ERD using rest data with open eyes alpha band in the temporal part of our brain is going strange but with calibration with closed all looks normal
In article EEG alpha and theta oscillations reflect cognitive and memory performance a review and analysis and Understanding Programming Expertise also notice that they get better results using relaxation with closed eyes. (Note that desynchronization is reflected by positive ERD values, whereas event-related synchronization (ERS) is reflected by negative ERD values) And as we can see I have desynchronization in alpha band that means that tasks reflect attention and semantic memory performance.
If we will see on the part with closed eyes calibration then while solving tasks the theta power is increase and alpha power is decrease.
Also, the power of alpha-band with closed eyes in the frontal part (the region where most of your conscious thoughts and decisions are made) is much smaller than with open eyes
