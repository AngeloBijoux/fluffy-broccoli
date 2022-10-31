.. container:: WordSection1

   +-----------------------------------------------------------------------+
   | .. container::                                                        |
   |                                                                       |
   |    Core_QMS_RND_BCA_HuaweiB535-932                                    |
   +-----------------------------------------------------------------------+

   +-----------------------------------------------------------------------+
   | .. container::                                                        |
   |                                                                       |
   |    **Business Case Analysis**                                         |
   +-----------------------------------------------------------------------+

   ­­
   **Contents**

   `Introduction.2 <#_Toc70633935>`__

   `Scope of Testing.2 <#_Toc70633936>`__

   `Hardware.2 <#_Toc70633937>`__

   `Testing of Huawei B535-932.3 <#_Toc70633938>`__

   `Device Setup & Configuration.4 <#_Toc70633939>`__

   `Firmware Version.8 <#_Toc70633940>`__

   `LTE – APN Connectivity & Signal9 <#_Toc70633941>`__

   `Wireless & LAN Functionality.9 <#_Toc70633942>`__

   `SIP/VOIP Functionality & Capability using Vobi
   App.11 <#_Toc70633943>`__

   `Tunnelling Functionality.12 <#_Toc70633944>`__

   `Assignment of Static IPS.12 <#_Toc70633945>`__

   `Remote monitoring & configuration.13 <#_Toc70633946>`__

   `Conclusion.14 <#_Toc70633947>`__

    

    

    

    

    

    

    

    

    

    

    

    

    

    

    

    

    

    

    

    

    

    

    

    

    

    

    

    

    

    

   Introduction

   Huawei B535-932 (4G+ Cat6 AC1200 Wireless Dual Band Gigabit Router):

   ·      TP-Link's First 4G+ Router – supports 4G+ Cat6 to boost the
   data speeds of up to 300 Mbps\*

   ·      Full Gigabit Ports – provides reliable wired connections for
   bandwidth-intensive devices such as game consoles and STB

   ·      Plug a SIM card and play – no configurations needed,
   compatibility of SIM cards in 100+ countries are assured by years of
   field tests

   ·      Better Signal for Connections Everywhere – enjoy stable and
   efficient connections to every device thanks to the two external LTE
   antennas

   ·      Wi-Fi router mode – plug an Ethernet cable into the LAN/WAN
   port for flexible access as a backup option if you can't get a 4G
   connection

   ·      Supports TP-Link OneMeshTM – co-works with TP-Link OneMesh
   products to create a flexible and cost-efficient Mesh network

    

   Scope of Testing

   ·      Average download & upload speeds

   ·      Auto configuration of APN

   ·      Correct firmware to kickstart DMA process

   ·      SIM locked to physical address (Solid Feasibility)

   ·      Ease of use to change default password, SSID and Wi-Fi Key

   ·      Wi-Fi & Lan functionality

   ·      SIP/VOIP Functionality & Capability

   ·      Tunnelling Functionality 

   ·      Assignment of Static IPS

   ·      Remote monitoring & configuration

    

   Hardware

   Front of Device

    

   Back of Device

   Testing of Huawei B535-932

   Requirement is to test an MTN LTE-A SIM using the Huawei B535-932
   Router.

    

    

   Hardware used:

   ·      MTN LTE-A SIM

   ·      Routers: Huawei B535-932

    

    

   **Results:**

   ·      Average download & upload speeds – 47Mbps download, 23Mbps
   upload

   ·      Auto configuration of APN – Failed, APN needs to be manually
   configured.

   ·      Correct firmware to kickstart DMA process – 1.3.0 0.9.1
   v0001.0 Build 210126 Rel.66358n

   ·      SIM locked to physical address (Solid Feasibility) – Test
   Successful, SIM is locked to physical address

   ·      Ease of use to change default password, SSID and Wi-Fi Key –
   Test Successful, Wireless settings can be changed from Web GUI or
   Mobile App

   ·      Wi-Fi & Lan functionality - Test Successful

   ·      SIP/VOIP Functionality & Capability - Test Successful

   ·      Tunnelling Functionality – Cannot be tested

   ·      Assignment of Static IPS - Cannot be tested  

   ·      Remote monitoring & configuration - Cannot be tested

    

   .. rubric:: 
      :name: section

    

    

    

    

    

    

    

    

    

    

    

    

    

    

    

   Device Setup & Configuration

   1.    Attach the base to the router:

    

    

    

    

    

    

    

    

    

    

    

    

    

    

    

    

    

    

    

   2.    Ensure that you have a Micro-SIM or an adapter for your
   nano-SIM

    

    

    

    

    

    

   3.     Insert the sim card into the slot located on the underside of
   the device

    

    

   4.    Connect and power up the router

   5.    Login and begin configuring the router:

   | a.    
   | Using a Computer: Follow the Quick Setup Guide & Create the below
     APN under SIM

   b.    Using the iOS/Google App: Follow the Quick Setup Guide (TBC,
   once APN is added)

    

   6.    Check your internet connection status

   a.    Using a Computer:

    

   | 
   | From Quick Setup Menu:

    

   | 
   | From Menu -> Basic -> Internet:

   b.    Using the iOS App:

    

    

    

    

    

    

    

    

    

    

    

    

    

    

    

    

    

    

    

    

    

    

    

    

                                                                                                                  
         

    

    

    

    

    

    

    

    

    

    

   Firmware Version

   10.0.3.1(H195SP2C372)

    

   LTE – APN Connectivity & Signal

   **Comparison of LTE Connectivity & Signal Results: (Note: Results are
   calculated based on an average over 3 tests)**

    

   +-------------+-------------+-------------+-------------+-------------+
   | **Router**  | **Latency   | **Download  | **Upload    | **Signal    |
   |             | (ms)**      | (Mbps)**    | (Mbps)**    | Strength    |
   |             |             |             |             | (dBm)**     |
   +-------------+-------------+-------------+-------------+-------------+
   | Huawei      | 22.67       | 47          | 23          | -73         |
   | B535-932    |             |             |             |             |
   +-------------+-------------+-------------+-------------+-------------+
   | ZTE MF286C  | 24          | 19.93       | 10.19       | - 98        |
   +-------------+-------------+-------------+-------------+-------------+

    

   Wireless & LAN Functionality

   **Comparison of WiFi Speed Test Results:**

    

   **Wireless Range**

**Device Used:**

**Download (Mbps) – MR600**

**Download (Mbps) –MF286C**

**Upload (Mbps) – MR600**

**Upload (Mbps) –MF286C**

2.4GHZ

Laptop

53.8

38.7

38.2

66.9

Tablet

47.4

42.7

41

42.8

5GHZ

Laptop

365

324.5

353.3

300.9

Tablet

76.3

75.1

98.5

97

 

 

 

 

**Wireless Settings – Web GUI:**

 

On first startup you are prompted to perform initial configuration on
your wifi network

 

 

**LAN Settings – Web GUI:**

 

LAN settings can be found under Advanced->Router->DHCP

 

SIP/VOIP Functionality & Capability using Vobi App

**Results (MOS Average over 3 calls):**

·      Call 1 - 

o  Duration:

o  Number Dialled:

o  MOS Score:

·      Call 2 - 

o  Duration:

o  Number Dialled:

o  MOS Score:

·      Call 3 - 

o  Duration:

o  Number Dialled:

o  MOS Score:

 

Tunnelling Functionality

L2TP and PPTP configuration can be performed under Advanced->Router->VPN

 

**VPN Settings:**

 

 

Assignment of Static IP’s

Configuration of Static IP’s can be performed under Network settings->
Ethernet->Ethernet settings

 

 

 

 

 

 

 

 

 

 

 

 

 

Remote monitoring & configuration

The B535 does not offer any options in remote monitoring protocols
however it does support TR069 provisioning.This can be found under
Advanced->TR069 settings

 

**TR069:**

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

Conclusion

 

 

References

 

`Link to Images of Test Results – TP-Link
MR600 <https://voxtelecom-my.sharepoint.com/:f:/g/personal/sashin_tulsiram_voxtelecom_co_za/Emr9qo783fFPn0QPiKbVo-sBj2h4PDe-vUd_ZyFL4EtwTg?e=MZaYRx>`__

`Link to Images of Test Results – ZTE
MF286C <https://voxtelecom-my.sharepoint.com/:f:/g/personal/sashin_tulsiram_voxtelecom_co_za/ElQVf70z14dLnQySu2WO2uMBJo8vW_-5Tp2k12-KoYQG5A?e=UJVT0G>`__
