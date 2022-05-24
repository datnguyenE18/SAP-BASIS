* **Trong OOP:**  Một bản thiết kế chi tiết cho ngôi nhà giống như là mô tả một class. Tất cả những ngôi nhà được xây dựng dựa trên bản thiết kế đó là những object của class. Một ngôi nhà cụ thể là một instance

* **R/3 Instance:** Khi nghe đến từ Instance, phần lớn sẽ nghĩ đến một lớp Application Server
  
    Thuật ngữ Instance đồng nghĩa vớI Application Server
    
    Thuật ngữ Central instance nói đến lớp Database Server

    Nếu một Application Server và Database server được đặt trong cùng một máy tính, thuật ngữ Central instance nói đến máy tính nơi cả hai lớp được đặt trong đó. Trong hầu hết các thuật ngữ chung, một Instance là một Server . Đó là một tập hợp các xử lý của R/3 cung cấp cho hệ thống R/3

* **SAP Instance** is a group of resources:
  * Memory
  * Work Processes
  * Dispatcher
  * Gateway

* For one SAP system, there are **three types of instances:**
  * **Dialog instance:**
    * exists in the application layer to maintain the load on the server
    * Dialog instance exists on the different host. If a number of dialog instance increases hardware resources, dispatcher, workprocesses also increases so that more number of users can login at a tim

  * **Central Instance:**
    * also work as dialog instance. But the main thing is that it contains Enqueue and message servers. (All dialog instances communicate with central instance before requesting database with message server)
    * an instance is started, the dispatcher process attempts to establish a connection to the message server so that it can announce the services it provides (DIA, BTC, SPO, UPD, etc.)

  * **Database Instance:** accepts requests from central instance to fulfill the user’s requests. As lock management system provided by enqueue server, it will provide service to users

**SAP System** = Dialog Instance + Central Instance + Database Instance.
