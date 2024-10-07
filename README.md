# Maps_Excel_Macro
To Split google maps service cost by key usage

Steps to Use the Cost Split Macro for Maps:
1. **Create a New Folder:** Download the template named “Maps_APL_Cost_Split_V1.0” and move it into the newly created folder.
2. **Create a “MMM_YYYY” Folder:** Inside the new folder, create another folder named using the format “**MMM_YYYY**”. This folder name will be used in cell **D5** of “Maps_APL_Cost_Split_V1.0”.
3. **Download Reports:** Download the Google billing report and monitoring dashboard data into the “MMM_YYYY” folder. (For Excel limitations on Mac, simply open and close the downloaded sheets).
4. **Update Keys_Lookup Sheet:** Open the template “Maps_APL_Cost_Split_V1.0” and update the “Keys_Lookup” sheet with your key names (Column A) and key values (Column B). This is a one-time update in the template for all existing project keys. If you create new keys for your application, update this sheet accordingly.
5. **Update the Report Month and File Path:** In the template, update the Report Month (in the “MMM_YYYY” format), the CSV file path (where the reports were downloaded), and the Path separator (use ****“/”** for Mac/Linux, and “\" for Windows**). For ex) ** CSV file path : /Users/User1/Downloads/Maps_Billing/Open_Sources/**  
6. **Run the Macro:** Click the “Map Cost Split” button.
7. **Refresh Data**: The macro will import all the downloaded files into the template and refresh the data in the “Maps_cost_split” sheet.


Please ensure that the billing report is downloaded with the renamed to "Maps_Billing_Reports.csv", and all other files are named according to their respective service names as show in the screenshot.


<img width="532" alt="image" src="https://github.com/user-attachments/assets/369cedef-19f4-4496-a2e7-d35f97bbcc5d">

Please do not alter/delete sheets "Maps_cost_split", "Keys_Lookup", "Calculation_sheets" and "Maps_Billing_Reports" to make sure the formula were not altered. 
