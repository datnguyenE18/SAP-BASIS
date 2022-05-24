* Tạo 3 Folder tương ứng với 3 môi trường **DEV, QAS, PRE_PROD:**
  * Chuột phải vào Local --> chọn Add new subfolder
    ![image](https://user-images.githubusercontent.com/43572616/169942249-e872f0c1-2b17-4932-8848-0ede1cb6db39.png)
  
#### DEV & QAS:

* Tại Folder DEV và QAS chọn New --> Connection:

    ![image](https://user-images.githubusercontent.com/43572616/169942354-712df644-8823-44bd-b6ee-998876f52ce6.png)
    
    ![image](https://user-images.githubusercontent.com/43572616/169942402-5ffea290-ded5-463f-a262-f20f862cd63f.png)

* **Nhập thông tin:**
  * Description (Name)
  * Application server (Group/Server)
  * Instance number 
  * System ID (SID)
  * SAProuter string (option)

  ![image](https://user-images.githubusercontent.com/43572616/169942579-34e633e8-df73-4e9d-b6ef-038b7ec57728.png)

* **Next … & Finish**

#### PRE_PROD:

  ![image](https://user-images.githubusercontent.com/43572616/169942734-2e453d6b-eb7c-44a9-adec-efb40796dda2.png)

* Chọn copy.bat:
    ![image](https://user-images.githubusercontent.com/43572616/169942791-71be77f2-bfa7-4be8-9f4d-05e6dd9f96fc.png)

* Copy 2 file **SapLogonTree.xml** và **SAPUILandscapegGLOBAL.xml** vào thư mục:

     C:\Users\%username%\AppData\Roaming\SAP\Common
