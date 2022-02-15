# CSV file to SQL database through Azure 

### Azure Portal
Go to https://portal.azure.com/

- Create a new Azure SQL server.<br/>
- In Azure SQL server Add client IP in Security Settings under Firewalls and virtual networks.<br/>
- Create a new SQL database.

### Azure Data Studio
- Install [Azure Data Studio](https://docs.microsoft.com/en-us/sql/azure-data-studio/download-azure-data-studio?view=sql-server-ver15)
- Create a Connection <br/>
<image width=400 src=https://user-images.githubusercontent.com/44158648/154156180-0a158cde-a66a-4227-8710-dc80598e21e3.png>
Install Extension "SQL Server Import"

Click on our database and Import Wizard: <br/>
<img width="500" alt="image" src="https://user-images.githubusercontent.com/44158648/154161831-2e3680ac-0e8f-4c38-91be-d8cdcc23eb88.png"><br/>
Preview Data: <br/>
<img width="600" alt="image" src="https://user-images.githubusercontent.com/44158648/154158046-44c797b1-3e63-4d44-bede-227e3b547c65.png"><br/>
Modify Data Types if necessary: <br/>
<img width="600" alt="image" src="https://user-images.githubusercontent.com/44158648/154158172-9aedbe2d-f32c-4857-b0be-0f88725b59aa.png"><br/>
Import Data<br/>
<img width="350" alt="image" src="https://user-images.githubusercontent.com/44158648/154161321-42fe29ad-27a3-4e92-9d26-fdb48c7a7671.png"><br/>
Done
