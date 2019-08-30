# 1. Getting Started
## <h3>1.1 Introduction</h3>
The goal of this visualization tool is to make 13C isotope tracing data more accessible by improving data presentation and streamlining analysis.
### <h3>1.1.1	What is isotope tracing?</h3>
AVI FILL THIS OUT

### <h3>1.1.2	Visualization Tool</h3>
<p>•	This tool simplifies the process of analyzing isotope tracing when the user uploads a JSON or CSV that contains isotope tracing data by placing it on a metabolic map. Features of the tool include:
<br>Automatically generate publication quality graphs of:
<br> &emsp;o	Mass isotopomer distribution
<br>&emsp;o	Metabolite abundance
<br>&emsp;o	Mole percent enrichment
<br>&emsp;o	Kinetic labeling and abundance
<br>•	Export graphs in svg format, allowing for seamless integration with adobe photoshop and illustrator.
<br>•	Correct for natural isotope abundance of 13C labeled datasets   
<br>•	Full control over data normalization and sample/condition grouping
<br>•	Simple CSV upload schema, requiring only minor modifications to be made from Metabolomic Core generated mass spec data
<br>•	Save and reload workspace allowing for the continuation of work at a later time and easy transfer of presentable data with collaborators. 
<br>    •	Integrated with Escher Maps, allowing for simple loading and editing of pathway maps.</p>

## <h3>1.2	Metabolic Maps</h3>
The tool currently has the TCA Cycle and _____ available. Other maps are available through the use of Escher, in order to understand how to get these maps use <a href="https://escher.readthedocs.io/en/stable/getting_started.html"> Escher Guide </a>   to import the desired map. Let us know which maps are needed here (make a link to a form of some sort) and we will work on adding it for you!

### <h3>1.2.1	Metabolic Map Editing</h3>
All of the changes to be made to the maps follow the same instructions as the Escher maps as they are the same, this set of dropdown menus at the top is where to start:

![Screenshot](/Images/MainMenu.png)
 
## <h3>1.3	Formatting Tracer Data</h3>
This portion of the guide will explain how to properly format data in order to be read by the Visualization Tool.

### <h3>1.3.1	Example File and Formatting</h3>
AVI FILL THIS OUT

## <h3>1.4	Importing Tracer Data</h3>
Now that the file is properly formatted, it is time to import the data to the tool!

### <h3>1.4.1	Loading the file</h3>
First click on the blue Import Tracing Data button in the bottom right of the screen.

![Screenshot](/Images/ImportTracing.png)

 
### <h3>1.4.2	Select File Type</h3>
Click Choose File of the chosen file type: JSON or CSV (Avi maybe add a line in between the sections to improve appearance) 
 
 ![Screenshot](/Images/FileUpload.png)
 
### <h3>1.4.3	Select the File</h3>
Browse through your files and select the properly formatted file with isotope tracing data and click open.

![Screenshot](/Images/FileSelection.png)

### <h3>1.4.4	Submitting Data</h3>
If the user is uploading data for the first time the Organize Groups popup will display, if they are uploading a JSON of a previously saved workspace then the previous workspace (graphs) will be upload.

### <h3>1.4.5	Organize Groups</h3>
Create group names and assign metabolites to groups. Click the white box next to group name and type the desired group name. Then click “Add Group”

![Screenshot](/Images/GroupCreation.png)
 
After Add Group:

![Screenshot](/Images/AddGroup.png)

 
#### <h3>1.4.5.1	Assign to Groups</h3>
Click and drag to the right below the desired group name, wait for the blue rectangle to appear and let go of the click.

![Screenshot](/Images/AssignGroup.png)
 
Click Submit to enter groups.
 
![Screenshot](/Images/SubmitGroup.png) 
Repeat these steps as needed.

### <h3>1.4.6	File Upload Properly?</h3> 
 If using BIGG IDs to label data if on the map it will show up in the cycle, but on left if not tied to it 

If the file uploaded properly bar graphs will appear around the metabolic map and a menu will appear in the top right of the screen.

Before Upload:

![Screenshot](/Images/MapBeforeUpload.png)
 
After Upload:

![Screenshot](/Images/MapAfterUpload.png)
 
## <h3>1.5	Navigate the Metabolic Map</h3>
Move around the map using the same methods described in the escher map documentation https://escher.readthedocs.io/en/stable/getting_started.html another way to access the documentation is by clicking the question mark at the top menu.

![Screenshot](/Images/MetabolicMapMenu.png)
 
## <h3>1.6  Making the Graph Options Appear</h3>
After importing the properly formatted file a drop down menu will appear in the top right of the map. To make the options appear the process is the same, hover over the desired button and left click to make the menu appear. Shown below is Graph Type.
While Hovering:

![Screenshot](/Images/MakeOptionsAppearHover.png)
 
After Click:

![Screenshot](/Images/MakeOptionsAppearClick.png)
 
## <h3>1.7 Removing the Drop Down Menu</h3>
To remove the options simply click on the current open menu or select any of the other drop down menu options available.
While Hovering:

![Screenshot](/Images/MakeOptionsAppearClick.png)
 
After Click:

![Screenshot](/Images/MakeOptionsAppearHover.png)
 