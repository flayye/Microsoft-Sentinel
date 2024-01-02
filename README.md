# Microsoft Sentinel Results:
<img src="/Sentinel/r3.PNG">

---

<img src="/Sentinel/r4.PNG">

---

<img src="/Sentinel/r5.PNG">

---

<img src="/Sentinel/r6.PNG">

## ChatGPT Playbook and Automation Rule
<img src="/Sentinel/r1.PNG">

---

<img src="/Sentinel/r2.PNG">

# Step-By-Step for Microsoft Sentinel Deployment

<details>
  <summary>Click to expand</summary>

## Step 1: Deploy Microsoft Sentinel
- Using the Microsoft Sentinel All In One for quick impletmentation
- https://github.com/Azure/Azure-Sentinel/tree/master/Tools/Sentinel-All-In-One

## Step 2: Configure Microsoft Sentinel
- Select the closest location, and choose a resource name 
- Limit 10 GB for daily ingestion 

<img src="/Sentinel/s5.PNG">

## Enable both options in settings and choose active directory
- Select **all** the choices in Content Hub and Data connectors

<img src="/Sentinel/s2.PNG">

## Enable scheduled alert and select all the severity
<img src="/Sentinel/s3.PNG">

## Here is a summary of the configuration
<img src="/Sentinel/s4.PNG">

## There will be errors occur for your deployment, related to invalid licence.
- It is still good to use even it said the deploymet failed.

<img src="/Sentinel/s6.PNG">

## Here is a quick look of Microsoft Sentinel
<img src="/Sentinel/s7.PNG">

</details>

# Tor IP Watchlist Configuration
<details>
  <summary>Click to expand</summary>

## Step 1: Enable both UEBA and Playbook permissions in Microsoft Sentinel setting
<img src="/Sentinel/s8.PNG">

---

<img src="/Sentinel/s9.PNG">

## Step 2: Create a new Watchlist
<img src="/Sentinel/s10.PNG">

## Step 3: Upload your custom Tor IP Watchlist
- Finshed the create
<img src="/Sentinel/s11.PNG">

## In KQL log, you can view all the IP address in your Watchlist
<img src="/Sentinel/s12.PNG">

</details>
