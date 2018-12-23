# Check Point App For Splunk

## Introduction:

Check Point brings an advanced and real-time threat analysis and reporting tool for Splunk.
The Check Point App for Splunk allows you to respond to security risks immediately and gain true insights about your network. 
You can collect and analyze millions of logs from all Check Point technologies and platforms across networks, Cloud, Endpoints and Mobile. 
This app uses the Check Point Log Exporter to seamlessly send logs from your Check Point log servers to your Splunk server.
Main features include: 
* Compatibility with Common Information Model (CIM).
* Compatibility with Splunk Enterprise Security.
* Provides Check Point SmartEvent dashboards out of the box (e.g., General Overview, Threat Prevention and the new Cyber Attack View).

## Prerequisites:

* Installation of Log Exporter on Check Point MGMT / Log Server - see [SK122323](https://supportcenter.checkpoint.com/supportcenter/portal?eventSubmit_doGoviewsolutiondetails=&solutionid=sk122323)
* Installation of [Common Information Model](https://splunkbase.splunk.com/app/1621/) (CIM) app from Splunkbase to support Splunk CIM format.

## Installation:

Install the Check Point App for Splunk on your Splunk servers. If you have a distributed environment, you must install it on each Splunk machine (forwarder, indexer, and search head).
1. Download the [Check Point App for Splunk](https://splunkbase.splunk.com/app/4293/) from Splunkbase.
2. Log in into your Splunk machine.
3. On the Apps left panel on your homepage, click “Manage Apps”.
4. Click “Install app from file” and select the downloaded tgz file.
5. Click Upload and wait until you receive a success notification.
After you install the app, you can find it in the Apps panel on your Splunk home page.

For more details about the app, please see [Check Point App for Splunk – User Guide](https://sc1.checkpoint.com/documents/App_for_Splunk/html_frameset.htm)

## Compatibility:

Splunk compatibility: 6.5 or later.

CIM compatibility: 4.5 or later.

## Contact:

Email: cp_splunk_app_support@checkpoint.com