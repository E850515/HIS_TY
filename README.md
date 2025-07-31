# HIS_TY
Host Interface Specification - Taiyo Yuden project

# Interface API URL List
This document describes the API endpoints used for the Taiyo Yuden project, specifically for the integration with the Kardex WES system. The API endpoints are categorized based on their functionality and the systems they interact with.

### 3.1 Articl Master 

    Sender  [Taiyo Yuden WMS]: 10.x.x.x:8080/api/xxx/
    Reciever     [Kardex WES]: 10.x.x.x:8080/api/skuMaster/


### 3.2 Purchase Order

    Sender  [Taiyo Yuden WMS]: 10.x.x.x:8080/api/xxx/ 
    Reciever     [Kardex WES]: 10.x.x.x:8080/api/putAwayRequest/


### 3.3 Picking Order

    Sender  [Taiyo Yuden WMS]: 10.x.x.x:8080/api/xxx/ 
    Reciever     [Kardex WES]: 10.x.x.x:8080/api/orderPickingRequest/


### 3.4 Inventory List

    Sender  [Taiyo Yuden WMS]: 10.x.x.x:8080/api/xxx/ 
    Reciever     [Kardex WES]: 10.x.x.x:8080/api/inventoryList/


# Host Interface Schedule
    [25.08.13] First WMS meeting

    [25.12.18] WMS Integration Test
    ; using host system

    [25.01.27] Go live - Kardex WES 

    [25.02.13] Fianal Acceptance