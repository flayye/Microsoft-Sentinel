# Microsoft Sentinel

## Results:


# Step-By-Step Procedures for Microsoft Sentinel Deployment

<details>
  <summary>Click to expand</summary>

## Step 1: Deploy Microsoft Sentinel
- Using the Microsoft Sentinel All In One to quick impletmentation
- https://github.com/Azure/Azure-Sentinel/tree/master/Tools/Sentinel-All-In-One

<img src="/Sentinel/s1.PNG">

## Step 2: Configure Microsoft Sentinel
- Select the closest location, and choose a resource name 
- Limit 10 GB for daily ingestion 

<img src="/Sentinel/s5.PNG">

### Enable both options in settings and choose active directory
- Select **all** the choices in Content Hub and Data connectors

<img src="/Sentinel/s2.PNG">

### Enable scheduled alert and select all the severity
<img src="/Sentinel/s3.PNG">

### Here is a summary of the configuration
<img src="/Sentinel/s4.PNG">

### There will be errors occur for your deployment, related to invalid licence.
- It is still good to use even it said the deploymet failed.

<img src="/Sentinel/s6.PNG">

### Here is a quick look of incident page in Microsoft Sentinel
<img src="/Sentinel/s7.PNG">


</details>
