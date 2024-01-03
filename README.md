# IATI-data-analyst-task

# My approach
I used VS Code to edit the XML file which I downloaded from this activity and used to run IATI Cove by reading the errors and constantly referring back the IATI activity standards version 2.03 and looking code lists  

# Through the above approach I have found:-

#	8 errors that were indicating a missing “measure” attributes.
	How I fixed?
I looked firstly read the description in the narrative element and secondly, read Albanian Country Program Document which is linked to the activity. I have add “measure” attribute with the code 2, the reason is the Albanian country document used percentage to state the percentage of school enrolment that is way I used code 2 which is percentage measurement based on the IATI standards code lists.

#	3 errors that were indicating a missing “measure” attributes 
	How I fixed?
By following the same approach I solved these three errors by adding measure attribute with the code 3 based on the description added in the narrative element which was referring the number of parents and caregiver that the program reached.

#	4 errors that ware indicating “location-id” elements were “code” attributes
	How I fixed?
I have looked the cod lists > locations but only found location types and location categories. Therefore I looked d-portal UNDP activities in Albania selected a succeeded activity which has no errors, and looked the code that UNDP has given Tirane Albania where the current activity curried out by the UNICEF is the same city and then got the code from the UNDP. I am not entirely sure where my approach is correct but that is how I got location code.

#	A code for “activity-scope” element was missing
	How I fixed?
By following same approach I refer the IATI standards code lists and added a “code” attribute with the code of 4 since the activity is focusing only Albania which makes the scope of this activity national level.

#	“vocabulary” attribute for humanitarian-scope element had invalid value
	How I fixed?
Looked IATI code lists and changed the value of the current vocabulary attribute value to “2-1” which is humanitarian plan according to the IATI standard code lists.

# How I would help them?

I would have indicate the importance of the quality data firstly helping the what was cause the above errors and also let them know that the IATI tools and systems are well prepared to help them to understand and improve the quality of the data published by IATI publisher, these available help includes but not limited to:
•	By helping their enquiry about the above errors, what they mean and how I fixed them.
•	Improving the quality of data http://dashboard.iatistandard.org/data_quality.html
