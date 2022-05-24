* Within one SAP instance, a number of Clients can be created

* No need to install separate softwares for each and every customer (Client is a ‘Customer’. in SAP. We can say that each customer maps to one client).It provides isolation ,one client cannot see the data of another client

* 100 and 200 clients can exist under one roof. We can create a number of clients in SAP Application (from 000 to 999)

* **Client contains:**
  * Application Data – the data are stored in the database tables
  * Customizing Data – data created by customers when they customize their systems
  * User Master Record – defines the authorizations assigned to a user. 

* **Advantages of Client concept:**
  * Enabling SAP SAS providers to install a small number of SAP Systems, but still cater to a large number of customers
  * Sharing hardware and software, multiple customers also use the same application solution, including administration and support ⇒ Save Cost
  * Clients help establish your SAP landscape. For instance, you can have a client for the development team, a client for a test team and a production client.

* **Three “standard clients”:**

  ![image](https://user-images.githubusercontent.com/43572616/169945836-fc2baa42-7766-4ac6-9c59-54daff571687.png)

  * **000 Client** (master client) :
    * We can find this clients in the system as soon as we install SAP r/3 software
    * It contains a simple organizational structure of a test company and includes parameters for all applications, standard settings, and configurations for the control of standard transactions and examples to be used in many different profiles of the business applications
    * It contains client independent data
  
  * **001 Client:**
    * A copy of the 000 client including the test company.
    * This client’s settings are client-independent if it is configured or customized.
    * People normally use 001 clients to create a new client
  
  * **066 Client:**
    * This client is called early watch client (Key: SAP EarlyWatch, EarlyWatch alert ). The SAP earlywatch alert is a diagnosis service, for solution monitoring of SAP and non-SAP systems in the SAP Solution Manager. Alert may contain Performance issue, average response time, current system load, Database administration,etc...
    
    * SAP EarlyWatch Alert is an automatic service analyzing the essential administrative areas of an SAP system. Alerts indicate critical situations and give solutions to improve performance and stability. SAP EarlyWatch Alert is most effective when activated for all SAP components in your solution. It gives an overview on KPIs and alerts on a weekly basis
