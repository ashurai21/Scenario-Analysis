# Scenario-Analysis

This is to demonstarte that scenario manager block under value library can be used to find out all the possibilities at precast yard site. It will help site-management in taking critical decisions before implementing it into the reality.

**Creating scenarios using ExtendSim simulation**

**Step-1** Click on add factors (Model Inputs) tab.

Adding Processing time as Input. 

![image](https://user-images.githubusercontent.com/103962807/167310756-0bbf74c5-54fb-4903-9441-242bde3257ac.png)

NOTE: PT1, PT2, PT3, AND PT4 are the processing time.
Assuming average processing time will vary by one hour at each of the front. 

In practice, it may vary by large amount and differ in values (not exactly 1 hour at each station)

**Step-2** Click on add responses (Model Results) tab.

Adding Operational Performance Measures which includes capacity, process capacity, cycle time, flow rate, utilization, total idle time, and direct labour utilization as output.

![image](https://user-images.githubusercontent.com/103962807/167310874-6ab56925-7cbf-452a-9d38-5d8935847019.png)

**Step-3** Choose DOE Method to Full factorial design under Scenarios Tab.

**Step-4** Click on create scenarios.

![image](https://user-images.githubusercontent.com/103962807/167310940-e5654a1e-a1c1-4a9a-aab5-00214913d470.png)

A total of 16 scenarios is created in this case. It may vary depending upon the variability in processing time of stations.

**Step-5** Select all scenarios created.

![image](https://user-images.githubusercontent.com/103962807/167311127-3aa216c6-6a22-4466-b04b-1b4b87f3122b.png)

**Step-6** Click on Run Scenarios.

![image](https://user-images.githubusercontent.com/103962807/167310940-e5654a1e-a1c1-4a9a-aab5-00214913d470.png)

**Step-7** All possible values of operational performance measures values will be obtained.

![image](https://user-images.githubusercontent.com/103962807/167311302-dc62bf05-663a-4107-b76d-fdbe4801507a.png)

**Step-8** Click on Export tab.

![image](https://user-images.githubusercontent.com/103962807/167311372-8e038401-fe65-4165-87f9-e6a566b7efb1.png)

Select Report type to Excel.
Select use existing worksheet. 
Open excel spreadsheet in the background and saved it as scenario analysis.
Click on open to open scenario analysis spreadsheet under worksheet file. 

![image](https://user-images.githubusercontent.com/103962807/167311658-7ff46d6f-8ea1-461f-b760-45191d7c127d.png)

Rename sheet-1 to results and select results in use existing worksheet tab.

![image](https://user-images.githubusercontent.com/103962807/167311800-1f8dd6fd-c470-4695-b13e-f207824df421.png)

**Step-9** Click on export report to generate report in excel. 

![image](https://user-images.githubusercontent.com/103962807/167311867-8d74f995-e0c3-4bdf-bacd-528b99e3d3b8.png)

In this way, different scenarios can be analyzed just by single click in ExtendSim. 
