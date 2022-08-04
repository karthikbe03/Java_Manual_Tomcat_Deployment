####  Java Web Application Manual Deployement in tomcat 

Steps:
** Prerequisite
    ** Proper Java version should be installed in Linux machine .
    
** Step 1:** Download the Eclipse IDE for Enterprise Java Developers, Click https://www.eclipse.org/downloads/packages/release/2020-09/r

![image](https://user-images.githubusercontent.com/1586154/182855716-a9348a4d-2bea-4ab9-a253-2ba02db01b9f.png)

** Step 2:** create the new dynamic web application project. New -> Dynamic Web Project
![image](https://user-images.githubusercontent.com/1586154/182857425-0343c84b-f764-4b75-94b3-63ad5bb5beeb.png)

** Step 3: ** Type your own Project Name  , Here we are using Project name as SimpleJavaWebApplication
![image](https://user-images.githubusercontent.com/1586154/182858034-407ae140-f3aa-4386-9734-fb79a6b25b9e.png)

** Step 4 : ** 
      * Click Next , No Change in first Window 
![image](https://user-images.githubusercontent.com/1586154/182858348-cf15efd4-c071-4d85-abed-edd05f7b36d7.png)


   * Check in the Genetrate web.xml deployment descriptor .

![image](https://user-images.githubusercontent.com/1586154/182858800-b5022693-365b-41e5-b616-86ea2ac6a38f.png)

* Click finish button .
![image](https://user-images.githubusercontent.com/1586154/182859337-5ccf9a6f-fb00-43e5-96d1-50d956f6c7c9.png)

** Step 4 : **  Now we can see the New project in Project Explorer.
![image](https://user-images.githubusercontent.com/1586154/182859719-bdf1ee0b-1fc0-4531-9b57-a4d863c9eeb9.png)

** Step 5 : ** Now expand the project 

![image](https://user-images.githubusercontent.com/1586154/182860363-001fff62-f69d-46f5-917f-ac404dd1bd86.png)

** Step 6 : ** Open the web.xml , Modify like below ( Keep only index.html).

![image](https://user-images.githubusercontent.com/1586154/182860865-2eccc378-e53b-4f38-9f95-c2fc0bb71d87.png)

** Step 7 : ** Create the index.html file , under the WebContent .
            ** Right click WebContent --> New --> HTML File 
            
            ![image](https://user-images.githubusercontent.com/1586154/182861432-19caee6f-be6c-4d59-acca-6917ca157303.png)

            ** Give the file name as index.html .
            ![image](https://user-images.githubusercontent.com/1586154/182861766-360d7563-1638-4b8a-ad18-453a623a5a75.png)

** Step 8 : ** Modify the index.html Like below , add you content whatever you need to display in Browser .

         ![image](https://user-images.githubusercontent.com/1586154/182862549-39c440a3-da5d-4fdf-8023-4270d2b689aa.png)
** Step 9 : ** Now Simple Project is ready , this needs to be deployed in Tomcat Server to see the page in Browser .

** Step 10 : ** Create the war file 
      * Select the Project 
   ![image](https://user-images.githubusercontent.com/1586154/182863154-c7824d24-ec43-4a87-b3e5-d1b09b4793e3.png)

     * Select File --> Export 
      ![image](https://user-images.githubusercontent.com/1586154/182863725-be26d8fd-d23a-4047-b334-415bd882d829.png)
      * War file 
      ![image](https://user-images.githubusercontent.com/1586154/182864029-fb81c98c-3413-4c3f-bd02-0e344f27a09d.png)
      Next 
      ![image](https://user-images.githubusercontent.com/1586154/182864360-aa2e3bf6-1b8b-4ea3-a724-313190118393.png)

      Select the destination and file 
      ![image](https://user-images.githubusercontent.com/1586154/182864763-4833da90-4375-4eda-891c-ca5ee466524f.png)
      Click save button 
      ![image](https://user-images.githubusercontent.com/1586154/182865132-5f572aa8-1160-423f-bee4-e765c0a24497.png)

Click Finish Button 
 ** Step 11 : ** Go to selected destication and check war file is present or not.
 ![image](https://user-images.githubusercontent.com/1586154/182865642-67a5ef1b-9990-414c-a7cb-27b4954556ca.png)
 
 ** Step 12 ** Now war file is ready , this has to be deployed in tomcat .
      * Go to webapps folder under apache-tomcat-8.5.81 
      ![image](https://user-images.githubusercontent.com/1586154/182866284-e0b75f64-19c3-42df-a66d-e35c0495f409.png)
      * Copy paste generated war file in this folder 
      
     ![image](https://user-images.githubusercontent.com/1586154/182866830-4f3fd9f2-ab30-4570-b147-c9ef542d848d.png)

** Step 13 ** Now Start the tomcat server 
      Go to bin folder 
   ![image](https://user-images.githubusercontent.com/1586154/182867107-3182a9bc-cd4b-4523-bb09-48b90141f0ac.png)

![image](https://user-images.githubusercontent.com/1586154/182867665-c9e1c116-7da3-4e6d-8225-16e39a9ece83.png)

** Start the server with ./catalina.sh start 

![image](https://user-images.githubusercontent.com/1586154/182868180-73f073dd-fa60-4778-bcd1-059af6fad784.png)

* Enter 
![image](https://user-images.githubusercontent.com/1586154/182868632-8dc2cc9f-61c5-4548-b2db-2fac1dda4517.png)


** Step 14 : ** Now tomcat started 

** Step 15 : ** Open the localhost with 8080 --> http://localhost:8080
![image](https://user-images.githubusercontent.com/1586154/182869287-b5d76ae0-9f85-4699-b218-fa17b71c5267.png)

** Step 16 : ** Change the ulr into http://localhost:8080/SimpleJavaWebApplication/
![image](https://user-images.githubusercontent.com/1586154/182869677-62f307b5-0398-451e-be81-74476bbb1098.png)


Webapplication runing now .






      



