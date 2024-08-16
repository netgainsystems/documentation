---
title: "AIOps"
geekdocHIDDEN: false
slug: "ai"
weight: 10
---

AI and machine learning technologies are used for monitoring and anomaly detection within the network management platform. It is applied through machine learning jobs to identify and alert unusual or abnormal conditions in the system metrics.

# Anomaly Detection

It involves identifying data points and patterns that deviate from the norm within a dataset.

# Outlier Detection 

It involves identifying data points that are significantly different from the rest of the data.

# Same steps apply for both Anomaly and Outlier Detection.

![AI1](/cloud_vista/Ai/images/netgain/AI1.png)

---

Basic information includes:
* Job Name
* Description
* Type
* Details

# Add Job

Click on \<Metrics>,\<Metrics>\<Objects> then \<Device View>.


![AI2](/cloud_vista/Ai/images/netgain/AI2.png)

---

Select the sites and the Object that you want to create ML (Machine Learning) Jobs.

![AI3](/cloud_vista/Ai/images/netgain/AI3.png)

---

Copy the path.

![AI4](/cloud_vista/Ai/images/netgain/AI4.png)

---

Click on ![Icon](/cloud_vista/Ai/images/spog/AIICON3.PNG) to add Job.

![AI5](/cloud_vista/Ai/images/netgain/AI5.png)

---

Once clicked, a panel will appear to add Job.

![AI6](/cloud_vista/Ai/images/netgain/AI6.png)

---

Paste the copied path into the Parent FDN.

![AI7](/cloud_vista/Ai/images/netgain/AI7.png)

---

Input the remaining information (For Anomaly Detection).

![AI8](/cloud_vista/Ai/images/netgain/AI8.png)

Information includes:
* Name: name for your job
* Description: description of the job 
* Job Type: type of job (Select Metrics, other types are seldom used)
* Enabled: a toggle to enable or disable the job
* Seasonality: to account for regular, predictable patterns in the data
* Metrics name: the metric to be monitored
* Parent FDN: path of the job
* Reference Period: the time period over which data should be used to generate a baseline for anomaly detection
* Bounds: set criteria to trigger alerts 
* Generate alarm: define the criteria of alarm

---

(For Outlier Detection)

![AI9](/cloud_vista/Ai/images/netgain/AI9.png)

Information includes:
* Name: name of your job
* Description: description of the job 
* Job Type: type of job (Select Metrics, other types are seldom used)
* Enabled: a toggle to enable or disable the job 
* Seasonality: to account for regular predictable patterns in the data
* Metrics name: the metric to be monitored
* Parent FDN: path of the Job
* Reference Period: the time period over which data should be used to generate a baseline for anomaly detection
* Sensitivity (1-100): determines how easily the system identifies data points as outliers
* Generate alarm: define the criteria for alarm

---

Click on ![Icon](/cloud_vista/Ai/images/spog/AIICON2.PNG) to create the job.

![AI10](/cloud_vista/Ai/images/netgain/AI10.png)

---

Successful creation of Job.

![AI11](/cloud_vista/Ai/images/netgain/AI11.png)

---

# Edit Job

Hover over the job and click on ![Icon](/cloud_vista/Ai/images/spog/AIICON5.PNG) to edit the information of the Job.

![AI12](/cloud_vista/Ai/images/netgain/AI12.png)

---

# Delete Job

Hover over the job and click on ![Icon](/cloud_vista/Ai/images/spog/AIICON4.PNG) to delete the job.

![AI13](/cloud_vista/Ai/images/netgain/AI13.png)

---

# View Details of Job

Click on the Job Name.

![AI14](/cloud_vista/Ai/images/netgain/AI14.png)

---

Once clicked, the page will navigate to the dedicated page of the selected Job.

![AI15](/cloud_vista/Ai/images/netgain/AI15.png)

---

Click on the ![Icon](/cloud_vista/Ai/images/spog/AIICON1.PNG) to further view details of the Job.

![AI16](/cloud_vista/Ai/images/netgain/AI16.png)

---

Once clicked, the page will navigate to the dedicated page for further viewing of details of the Job (For Anomaly Detection).

![AI17](/cloud_vista/Ai/images/netgain/AI17.png)

---

Once anomalies are detected in the graph, it will trigger the alarms.

![AI18](/cloud_vista/Ai/images/netgain/AI18.png)

---

Click on \<Alerts>,\<Alerts> then \<Current> and select Anomaly Alarms to view the triggered alarms.

![AI19](/cloud_vista/Ai/images/netgain/AI19.png)

---

(For Outlier Detection)

![AI20](/cloud_vista/Ai/images/netgain/AI20.png)

---

Adjust the sensitivity to control how easily the system identifies data points as outliers.

![AI21](/cloud_vista/Ai/images/netgain/AI21.png)