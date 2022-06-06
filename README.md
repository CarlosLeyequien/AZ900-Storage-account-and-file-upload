# Storage-account-and-file-upload
How to create a storage account in Azure and upload files

  1) Search for "storage" in portal.azure.com and click on "storage accounts"
  ![image](https://user-images.githubusercontent.com/105960409/172257050-822b3cc1-d750-4ead-abb6-5c4ab67dab59.png)
  
  2)Click on the +Create symbol 
  ![image](https://user-images.githubusercontent.com/105960409/172257154-371666ab-38d0-4ea1-911a-5c3ab877a875.png)
  
  3)Choose subscription, Resource group(Or create a new one), storage name, region, Performance and redundancy
  ![image](https://user-images.githubusercontent.com/105960409/172257275-51cdf4c5-9905-4faa-81fe-3e1fa78833d7.png)
    
    3.1 Region needs to be the closest one to the location for better performance
    3.2 Performance is whatever suits the needs
    3.3 Redundancy = locally(backup stored in local server), geo redundant (backup stored in another region), Zone redundant(Stored in the closest zone of availability), 
    Geo-Zone redundant(Stored in another region's zone of availability)
  
  4)Choose advanced options as needed
  
  ![image](https://user-images.githubusercontent.com/105960409/172257893-702886a1-40dc-47c8-b02a-37d17f9461ea.png)

    
    4.1 Networking gives you a choice on where the storage can be accessed from
    4.2 Data protection is what level of protection is needed depending on the needs of the solution
    4.3 Tags are optional
    
  5) Click "Review and create" which will give you a review page for all the choices you made for the solution, after reviewing, click create

  ![image](https://user-images.githubusercontent.com/105960409/172257973-3c9f43c4-f659-4cbf-8060-95e9bd20938d.png)

   
  6) The storage account has been created

  ![image](https://user-images.githubusercontent.com/105960409/172258065-90a66f2e-b264-42b2-bcb0-6d1b4e1e43bc.png)
  
**How to create a container**
  
  1) Access the account info by clicking on the "account name"

  ![image](https://user-images.githubusercontent.com/105960409/172258135-de667bd5-278a-4646-becf-5b9d8daaf16c.png)
  
  2) Click on "containers" on the left hand side column, under the "Data storage" submenu

  ![image](https://user-images.githubusercontent.com/105960409/172258425-5bbef1f1-f11f-48e4-86fe-fb1d92f26a4d.png)

  3) Click on the +Container option in the top left hand side of the content view:
  
  ![image](https://user-images.githubusercontent.com/105960409/172258554-81fbaa13-908f-4bfa-8842-cb2f3c00ee87.png)
  
  4) On the pop-up menu that appears on the right, type in the name and select the public access level as required, advanced options can be modified as needed

  ![image](https://user-images.githubusercontent.com/105960409/172258679-5b1d94cf-163f-4e1d-afc1-60d8502f6c57.png)

  5) Clcik on "create"

** How to upload a file**

  1) You need to be inside the Storage account, where the containers are stored, you will see the names of the containers you have created:

  ![image](https://user-images.githubusercontent.com/105960409/172258869-7494591a-b2c6-49b5-a083-7520b1cf4a11.png)

  2) Click on the container name

  ![image](https://user-images.githubusercontent.com/105960409/172258908-687032e7-d9e5-44e6-8236-adb83c78a1d3.png)

  3) You will see the content view of the container, click on ↑Upload on the options
  
  ![image](https://user-images.githubusercontent.com/105960409/172259043-30e43609-8abc-4933-9959-92e2bba094ab.png)

  4) A pop-up menu will appear, select the folder icon by the "select a fie" option on the top side of that menu:

  ![image](https://user-images.githubusercontent.com/105960409/172259171-70dd20bc-de34-47cf-91d9-e6ca68f16de1.png)

  5) Browse to the folder where your file is and select it, then select "open"

  ![image](https://user-images.githubusercontent.com/105960409/172259263-e8850027-6368-4dee-8b9b-a38275113761.png)

  6) The file will show in the "Files" part, you can modify the advanced options as needed, click on "upload"

  ![image](https://user-images.githubusercontent.com/105960409/172259379-e224ebd2-b95a-4109-b198-0d11c0850aff.png)

  7) Your file will now show on the content viewer of the storage solution:

  ![image](https://user-images.githubusercontent.com/105960409/172259438-b3726fa1-3914-4735-9221-5eba70856e9e.png)


  

