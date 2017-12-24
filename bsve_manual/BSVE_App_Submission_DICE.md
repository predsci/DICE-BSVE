<!--This is the CSS for the entire document-->

<style>
	table.revision {width:100%; border-collapse: collapse;border: 2px solid lightgrey;}
	table.revision tr {background:white;}
	table.revision tr:nth-child(1) td {background:rgb(78,78,80); color:white; text-align:center;border: 1px solid #dddddd;padding: 8px;font-size: 150%;}
	table.revision tr td:nth-child(1) {text-align:center;padding: 8px;font-size: 150%;}
	table.revision tr td:nth-child(2) {text-align:center;padding: 8px;font-size: 150%;}
	table.revision tr td:nth-child(4) {text-align:center;padding: 8px;font-size: 150%;}
	table.revision tr td {border:1px solid #ccc;height:30px; text-align:center !important;padding: 8px;font-size: 150%;}
	table.revision .header td {background:#4e4e50 !important;color:#fff; text-align:center !important;height:37px;padding: 8px;;font-size: 150%;}
	
	ul li a {color: black; text-decoration: none; font-family: "Century Gothic"; font-size: 24px;}
	ul li{ padding-top: 10px; padding-top: 5px;}
	div.pagebreak {page-break-after: always;}
	
	hr {border-color: black;height: 0.0px;background-color: black;margin-bottom: 50px;margin-top: 10px;}
	h1, h2, h3, h4, h5, h6 {font-family: "Century Gothic"; font-weight: 100;}
	h1 {font-size:28px}
	h2 {margin-bottom: 0px; font-size: 26px;}
	h3 {margin-bottom: 0;font-size: 24px;}
	h4 {margin-top: 20px; margin-bottom: 0; font-size: 22px;}
	h5 {margin-top: 5px; margin-bottom: 0; font-size: 20px;}
	p {margin-top: 2px; margin-bottom: 10px; font-size:18px;}
	body {font-family: font-family: "Times New Roman";  margin-left: 50px; font-size:18px; margin-right: 50px; line-height:30px;}
	ul {margin-top: 0px; margin-bottom: 0px; padding-bottom: 10px}
	.toc > li:nth-child(1) {visibility: hidden;}
	.toc > li:nth-child(2) {visibility: hidden;}
	img.bsve-logo {width: 20%; margin-top: 4%;margin-left: 10px}
	div.bsve-logo-large-container {position: relative; margin-top: 20%; width: 100%; margin-left:0px;}
	div div.bsve-logo-large {position: relative; top: -12px; z-index: 990;}
	div.tool-name-container {position: absolute; top: 0px; width: 100%;height : 70%;}
	table.tool-name-table {   position: relative; width: 100%; height: 16%; text-align: right; font-size: 250%; color: white;  margin-left: -10%; z-index: 1000;}
	tr.tool-name-row {background:rgb(25,49,90); font-size: 50px;}
	
</style>


	
<!--Cover page for the Guide-->

<div>
	<img class="bsve-logo" src="Picture1.png" alt="logo here" width="260" height="70"/>
</div>
<div class="bsve-logo-large-container" style="">
	<div class="tool-name-container" >
		<table class="tool-name-table">
			<tr class="tool-name-row">
				<td style="border: 2px solid white;padding-right: 15px;">[TOOL NAME] GUIDE</td>
			</tr>
		</table>
	</div>
	<div class="bsve-logo-large">
		<img src="Picture2.png" alt="cover image" width="1014" height="780"/>
	</div>

</div>

<div class="pagebreak"></div>

<!--Add/remove table rows and edit the content to reflect the current state-->
## REVISION HISTORY
<hr/>

<table class="revision">
	<tr class="header">
		<td>Date</td>
		<td>Revision</td>
		<td>Description</td>
		<td>Approved By</td>
	</tr>
	<tr>
		<td>[mm/dd/yyyy]</td>
		<td>0.1</td>
		<td>Initial Draft</td>
		<td>[first name last name]</td>
	</tr>
	<tr>
		<td>[mm/dd/yyyy]</td>
		<td>1.0</td>
		<td>[short description of update]</td>
		<td>[first name last name]</td>
	</tr>
	<tr>
		<td>[mm/dd/yyyy]</td>
		<td>2.0</td>
		<td>[short description of update]</td>
		<td>[first name last name]</td>
	</tr>
</table>

<div class="pagebreak"></div>

## CONTENTS
<hr/>
<!--Auto generated Table of Contents - PLEASE DO NOT REMOVE the following tag-->

[TOC levels=3-5]

<div class="pagebreak"></div>

<center style="font-size:20px;">This page intentionally left blank</center>

<div class="pagebreak"></div>

<!--Please do NOT modify the section numbers-->

###	1	INTRODUCTION
<hr/>

####	1.1		Name

[Include version number of app currently available in the BSVE Live App
Store (not testing environment)]

####	1.2		App Type

[Provide the App Type selected on the developer portal]

####	1.3		App Store Categories

[Provide the App Store Categories selected on the developer portal]

####	1.4		Short Description

[Max. 200 characters. Provide a general description of the application.
Include the following information in this description:

-   The primary task(s) the application is meant to perform (e.g.,
    anomaly detection, prediction, forecasting, situational awareness,
    and monitoring domestic animal disease).
-   The benefit of the application to the BSVE community. Describe
    scenarios or situations where its analytical output supports BSVE
    users.
-   Potential users (e.g., U.S. military, first responders, and
    strategic command) and any assumptions the developers made about the
    users’ knowledge or experience. Describe the prerequisites to using
    the application, if any.]

####	1.5		Long Description

[Max. 1000 characters. List the application’s primary capabilities.
This description should expand on the primary task description included
in Section 1.1.]

####	1.6		User Access Levels

[Describe the different users and/or user groups and the restrictions
placed on system accessibility or application use for each group.]

####	1.7		Contact Information

[Organization, department, general phone number]

For more information, please contact:
[Name, title, phone, email]

For troubleshooting questions, please contact:
[Name, title, phone, email]

[*If the person for requesting more information and troubleshooting are
the same, combine the sections.*]

<div class="pagebreak"></div>

###	2	TECHNICAL OVERVIEW

<hr/>

####	2.1	System Architecture

[Describe and graphically illustrate the architecture of the system. If
feasible, use block diagrams to detail the application components, such
as data inputs, analytical engines (disclose any external sources, such
as packages or libraries), outputs, BSVE Services used etc.]

####	2.2	Data Flow

[Describe and graphically illustrate the high-level data workflow and
list data sources used. Be sure to distinguish between BSVE data sources
used and any external data services, static references datasets etc.
used. Provide information on data structure (e.g., temporal resolution
(daily, weekly), spatial resolution (county, state-wide, country-wide),
demographics (gender and age of patient)) and data format coupled with
screen shot examples of a dataset.]

####	2.3	BSVE Technologies

[This section is to be filled out to describe the manner in which your
App extends the BSVE platform in the specific areas listed below. This
information would be published via the SDK and made available to other
BSVE community developer so they may consume or interact with the new
resources you have created]

##### 2.3.1	Data Sources

[List any new BSVE data sources created as part of your submission.
Describe the data source, the nature of the data, contrast and
differentiate against any other similar BSVE data sources that may have
existed prior to your submission.

Describe how frequently the data needs to be updates, describe the
mechanism(s) implemented to achieve these updates. Talk about the volume
of data and projected growth of the data volume.

Describe the permissions applied to the data source to understand]

##### 2.3.2	Analytics (not yet implemented)

[List any new BSVE analytics created.

Describe the permissions applied to the new analytics apis. Describe how
other developers would be able to use this new analytic, what is the
input data, output data etc. Other information that would be relevant to
another developer that wants to use this new analytic api.

Reference the algorithms described below to describe which algorithm(s)
are implemented using which analytic API functions.]

##### 2.3.3	App-to-App Communication

[List the types of data and format that the app is able to receive or
send to other apps using the BSVE inter-app communication framework.]

##### 2.3.4	Federated Auto-Search

[Mention if the app is using this feature and briefly describe how it
works with your app]

<div class="pagebreak"></div>

<div id="userManual">
<!--This section will be extracted and displayed when your app is launched to the workbench users. PLEASE DO NOT MODIFY THE MAIN SECTION NUMBER-->

###	3	USER MANUAL

<hr/>

[Provide a user manual page that would appear in the BSVE help system
for users to see]

####	3.1		Introduction

[Describe the App’s purpose and what is the best use of the app is.
This may be similar to information provided in sections 1.4 and 1.5
above.]

####	3.2		Limitations and Assumptions

[State the application’s limitations and underlying assumptions.
Example of a limitation statement: The model requires at least 4
consecutive weekly case counts (1 month) for a proper forecast. Example
of an assumption statement: Tweets associated with “influenza” include
those with the following terms: “flu”, “cough”, and “sore throat”.]

####	3.3		Layout

[Walkthrough of available controls and layout of the app, describe the
function of each of the controls]

####	3.4 	Usage

*[Describe the different functions, modes, views of the app of the
application in the order of ‘most commonly used’ based upon the
developer’s judgment.]*

##### 3.4.1	Use Case / Mode / Function 1

##### 3.4.2	Use Case / Mode / Function 2

##### 3.4.3	Use Case / Mode / Function 3

[Explain what this mode/function achieves and what its output is. List
the steps required to perform the function with detailed instructions
and screen captures if necessary.

Include notes and warnings that provide relevant or supplemental
information about consequences of performing a step incorrectly (i.e.
the consequence of missing or invalid data). Place warnings before the
step to be taken, particularly minimum or required data or default input
settings. Notes may be placed before or after the corresponding step.

If relevant, indicate the time required for a calculation or simulation
to occur (e.g., a county-level simulation of ILI activity requires \~ 5
minutes, a state-level simulation requires \~ 50 minutes).

Provide a sample data source that will allow a user to follow along with
each tutorial and compare his/her results with those presented here.]

####	3.5		Algorithms

[If appropriate, describe the math and science behind the algorithm(s)
used in the application.

Provide a simple example to illustrate the analytical steps from the raw
input through several intermediate steps and finally to the final plot
or maps. For example, for an application that calculates the
exponentially weighted moving average of the past 4 weekly ILI cases,
show the calculations starting with the value of the past 4 weekly case
counts and state the coefficient for weighted decrease and equations
used.

Ensure that the user understands which algorithm(s) are used for each of
the use case/mode/function described in the section above

If multiple algorithms are used be clear to reference the above use
case/mode/function that each with the appropriate usage instructions.

Provide any external references as necessary.]

####	3.6		Verification and Validation

[Copy and paste the final verification and validation (V&V)
documentation you receive from the DTRA-assigned V&V entity that
reviewed the application.]

####	3.7		Frequently Asked Questions

[List common FAQs. An example showing proper format is below.]

Question?

*Answer*

####	3.8		Glossary

[List the terms and acronyms that require definition or explanation in
alphabetical order. Examples showing proper format are below.]

**Acronym**. Definition

**Term**. Definition

####	3.9		Publications

[List peer-reviewed journal articles, papers, and books based on the
application algorithm in American Psychological Association (APA)
format.]

</div>
<div class="pagebreak"></div>

###	APPENDIX A	SOURCE CODE

<hr/>

[Describe how to access the full source code of all parts of the BSVE
App. This should include any necessary instructions, build scripts,
dependencies to build etc. to be able to re-create a development
environment for the app and then be able to re-build the BSVE App using
the Developer Site to publish it to the BSVE App Store.]

<div class="pagebreak"></div>

###	APPENDIX B	INSTALLATION AND CONFIGURATION

<hr/>

[If the app can be hosted independently of the BSVE, list the steps
required to install and configure the application in detail and include
screen captures. Identify the software, drivers, and APIs that need to
be installed in order to run the application in an environment other
than BSVE.

List alternative ways to the download application software.]
