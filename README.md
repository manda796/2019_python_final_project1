# Python Final Project: Monkey Weight Tracker


### Objective
To generate a user-friendly primate weight tracker for our daily research log. The tracker is designed to record daily amount of water intake and weight for each individual primate. A graph will be generated to visualize water consumption and weight trends over time.

### Purpose
In our research, it is extremely important to monitor the general well-being of our primates while they are preforming tasks over long periods of time. We use water, food, and fruit (classified as treats) in a controlled setting as motivational factors to learn and preform adequately on visual and physical tasks. A primate's weight has a direct causal relationship with their intake of these rewards and a fine balance must be established between water/food intake and weight control. 

We cannot allow any primate to fall below a designated weight threshold, as it may be indicative of dehydration, fatigue, or illness, so a detailed daily log of this information must be kept. In our lab, we currently have physical records of these logs, which are extremely wasteful and limited in it's capabilities. The purpose of this project is to digitalize this process, allowing us to expand our ability to assess individual primates' trends through graphing and to create a more modernized method of saving, storing, and analyzing these key data sets. 


### How to Use
*Prerequisite: Have a .csv file for the individual primate prepared, this way the data will live update your record and run through the code simtaneously*
1. Launch GUI Home 
2. Begin with "Enter data" and press submit
3. Verify corresponding .csv file has been updated with latest entry
4. Navigate to the graphs of interest
5. Add more entries in "Enter data" and watch graph live update data


### Components of Code
Includes the following packages and their functionalities used in code:
* csv: stores and read .csv files of primate date; ability to upload .csv file for read-off
* matplotlib: generates graphs of water intake and weight over time
* pandas: stores, reads, and displays raw entries in python 
* numpy: store water amount and weight valuables as entries
* sklearn (Linear Regression): statistically analyze correlative relationships
* tkinter: generate interactive GUI for data input and graph output


### Example 
![Screenshot (14)](https://user-images.githubusercontent.com/55368407/70726634-64e72f00-1ccc-11ea-836e-0b17ccc9e1f8.png)


![Screenshot (25)](https://user-images.githubusercontent.com/55368407/70740468-3dea2680-1ce7-11ea-80dc-847ddcdad628.png)


![Screenshot (20)](https://user-images.githubusercontent.com/55368407/70739974-10e94400-1ce6-11ea-87fb-f96d9d93ed01.png)


![Screenshot (21)](https://user-images.githubusercontent.com/55368407/70740053-4aba4a80-1ce6-11ea-8d13-87508d342c5e.png)


![Screenshot (22)](https://user-images.githubusercontent.com/55368407/70740136-7dfcd980-1ce6-11ea-8bd9-b4859fea438c.png)


![Screenshot (23)](https://user-images.githubusercontent.com/55368407/70740222-af75a500-1ce6-11ea-9927-09fc6e8e6fca.png)


### Errors
Python 3.7 tkinter backend embedded with matplotlib is known to crash on macOS. There have also been some variations of errors whether the code is ran in Jupyter(Anaconda) or PyCharm while developing this project.

Source: https://github.com/matplotlib/matplotlib/issues/14999


### References
The following websites were used as reference for code with modifications to met the project's objective:
* https://pythonprogramming.net/how-to-embed-matplotlib-graph-tkinter-gui/
* https://pythonprogramming.net/embedding-live-matplotlib-graph-tkinter-gui/
