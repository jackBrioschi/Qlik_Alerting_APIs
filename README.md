<img src="img/alert.png" width="300" title="hover text" align="right">
<br>
<br>
<br>
<br>


# Qlik_Alerting_APIs

**Team**: Qlik Pre-sales OEM Team

**Developers**:
* Giacomo Brioschi 

# Introduction
In this project I'm going to show you how you can use the Alerting REST APIs to automatically insert a picture inside your alert and how y can automatically update it everyday without a manual interaction from the user interface.* 
<br>
For this purpose I wrote a Python script that uses REST APIs in order to:

* Login into Alerting Server
* Retrieve user alerts information
* Modify an alert body by inserting a base64 image
* Push the modification to Alerting server to overwrite the new information.

**At the moment of the work, the APIs were not officially exposed , hence everything done in this document is not officially supported.**
<br>
<img src="/img/flow.png" alt="drawing" width="800"/>
