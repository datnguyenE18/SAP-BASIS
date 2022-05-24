* When data is distributed between different systems, each system within a network has to be clearly identifiable. The “logical system” deals with this issue

* A logical system is an application system in which the applications work together on a common database. In SAP terms, the logical system is a client.

* The logical system name is used to identify a system uniquely within the network, two systems cannot have the same name if they are connected to each other as BW systems or as source systems, or if there are plans to connect them in any way.

* Logical system names should be: **< System-ID >CLNT< Client >**
  
  **E.g.** PBGCLNT100

* Example for production system logical system name might be:

      SID – PBG
SID Description – 

    P=Production(type) ,

    B=BW(component) ,

    G=Germany.(plant name)
