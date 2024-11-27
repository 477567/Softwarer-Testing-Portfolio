System Overview - Data Care
This system is designed to assist medical professionals in managing, visualising, and cleaning large datasets effectively. It provides a user-friendly interface to handle data from different sources, such as patient records, lab results, and medical scans. Key features include data visualisation tools, data cleaning functionalities, and the ability to digitise and extract information from handwritten and digital medical documents.
The primary goal of the system is to streamline the data analysis process for medical users, allowing them to make informed decisions quickly and efficiently. The system is built with accessibility and ease of use in mind, ensuring that even users with limited technical backgrounds can interact with it smoothly.


System
Accessibility
1.	As a Medical user, I want to have a clear landing page clarifying what that system does, so all users can get the system idea.
2.	As a Medical user, I want to ensure that the colour scheme is accessible for users.
3.	As a Medical user, I want to allow users to customise the appearance of the application to their preferences in either light or dark mood. 
4.	As a Medical user, I want to have a side menu showing all modules with names, so it would be easy to navigate between modules.
5.	As a Medical user, I want a visually appealing & easily accessed system, easily used by non technical users. 
6.	As a Medical user, I want to be able to minimise & maximise the displayed app screen as I can, ensuring a flexible view & smart layout. 


Performance
1.	As a Medical user, I want to optimise the application for large datasets to prevent performance issues.


Visualisation 
Data Upload
As a Medical User, I want to be able to upload files from a local device, considering that file a dataset proceeding to the cleaning or visualisation functionality.  
Acceptance Criteria
1.	The system should accept file formats in CSV, XLS, and XLSX.
2.	Upon successful upload, the file name should be displayed on the screen.
3.	If the file format is unsupported, an error message should be shown to the user.
4.	The uploaded dataset should be ready for immediate use in subsequent functionalities (visualisation, cleaning).

Visualisation Accessibility 
As a Medical user, I want to have a tooltip for every available plot, ensuring we’re choosing the right plot & information is accessible for different non technical backgrounds. 
Acceptance Criteria
1.	Each plot should have a tooltip including name, description, best use.
2.	Tooltips should appear when moving around the plot logo. 


Visualisation 
As a Medical user, I want the file available columns (dataset features) to be displayed in a drop down menu to choose features for each axis.
Acceptance Criteria
1.	The dropdown menu should display all available columns (features) from the dataset.
2.	The columns should be categorised as either numerical or categorical.
3.	The dropdown should update automatically when a new dataset is uploaded.





Validation of plot values
As a Medical user, I want each plot axis to be validated so that only numeric columns are displayed when selecting a plot that requires numeric axes, ensuring fewer user errors.
Acceptance Criteria
1.	When a plot requiring numerical values is selected, only numeric columns should be available in the dropdown menu.
2.	The columns shown should match the chosen plot required axes data types.

Plots Display Button
As a Medical user, I want a visually appealing button for plotting, ensuring it is clear and accessible.
Acceptance Criteria
1.	The plot button should be prominently placed on the interface.
2.	The button should change colour when hovered over or clicked.


Accessibility for plots display & use 
As a Medical User, I want to have a good size display box for the plots/graphs, ensuring it’s accessible & details are clear.
Acceptance Criteria
1.	The plot display box should resize dynamically based on the screen size.
2.	Users should have the option to zoom in.





Plots Save
As a Medical User, I want to have the option to save my plot locally and to the system to ensure a safe database for future reference.
Acceptance Criteria
1.	Users should be able to save the plot as a PNG, JPEG, or PDF file locally.
2.	The system should provide an option to save the plot to the database with a unique name.
3.	A confirmation message should appear after the plot is successfully saved.

Clear Plot 
As a Medical User, I want to have the option to clear the displayed plot to create another one.
Acceptance Criteria
1.	A clear button should be available next to the plot display.
2.	Clicking the clear button should remove the current plot from the display.

Cleaning
Dataset Display view 
As a Medical user, I want the uploaded dataset to be displayed scrolling up & down, ensuring a flexible view for the dataset. 

Acceptance Criteria
1.	The dataset should display in a table format with scrollable functionality.
2.	The user should be able to view both column headers and data entries while scrolling.
3.	The columns should automatically resize to fit different screen sizes.






Cleaning Options 
As a Medical user, I want to have 5 options to choose between them (Handling duplicates, Missings, Anomalies, Consistency, Unstandardized dates)

Acceptance Criteria
1.	Needed option for a specific dataset should be automatically detected. 
2.	Number of needed rows/columns to be cleaned is displayed beside each option. 
3.	Detailed explanations of each cleaning option should be available through tooltips
4.	Users should have the option to download the cleaned dataset.


Handling Data Consistency 
As a Medical user, I want the consistent columns to be handled by user choice to drop them.
Acceptance Criteria
1.	The system identifies consistent columns automatically.
2.	Users are presented with an option to drop or keep consistent columns.
3.	A confirmation prompt is displayed before columns are permanently dropped.
4.	If a column is dropped, it should be removed from the dataset and the change should be reflected in real-time.


Handling Data Missing 
As a Medical user, I want the missing data to be handled by user choice either to keep them depending on importance & severity or to fill them by mean & mode depending on the datatype or to drop. 
Acceptance Criteria
1.	The system identifies missings automatically.
2.	Users have the option to choose which column from columns containing missing would be handled from a drop down menu.
3.	Users have the option to choose to keep, fill by mean/mode, drop missings for each specific column.  
4.	Validation message should be shown before any action. 


Handling Anomalies 
As a Medical user, I want the Anomalies to be handled by user choice either to keep them depending on reality of the case or to normalise if it’s an error. 

Acceptance Criteria
1.	The system identifies anomalies automatically.
2.	Users should have the option to decide to keep if it's a real case or drop if it's a real error. 
3.	Validation message should be shown before any action. 


Entry
Data Entry Options
As a Medical user, I want to digitise handwritten and digital prescriptions so that the data can be textually saved to the system.
Acceptance Criteria:
1.	The system should support the extraction of text from both handwritten, digital prescriptions, lab results, and medical digital scans.
2.	Extracted data should be displayed in a structured format (text fields)
3.	The user should have the option to edit the extracted data before saving it.
4.	The user should have the option to clear / reset/ save extracted data. 


Data Entry Extraction Format
As a Medical user, I want the extracted information to be displayed and divided into sections like Personal Information and Medications.
Acceptance Criteria:
1.	Extracted data should be automatically divided into relevant sections.
2.	Sections should include Personal Information, Medications, and other relevant categories.
3.	An indicator should show if any standard data is missing (e.g., "Not Mentioned").



Data Retrieval 
As a Medical user, I want to retrieve saved data extracted from different medical statements, ensuring a safe data reference.
Acceptance Criteria:
1.	As a Medical user, I want data retrieval to be from a table, ensuring an integrated view.
2.	As a Medical user, I want retrieval search by any available key, ensuring seamless search. 
