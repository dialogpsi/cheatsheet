Cheatsheet
==========

All Ideamart Pro Details Here
----

####End Points: Active Production 


|      SMS     | Url                                          | Local / Live  |
|:------------:|----------------------------------------------|---------------|
| SMS          | https://api.ideamart.io/sms/send               | Live - HTTPS  |
| USSD         | https://api.ideamart.io/sms/send               | Live - HTTPS  |
| LBS          | https://api.ideamart.io/lbs/locate             | Live - HTTPS  |
| Subscription - Reg/UnReg | https://api.ideamart.io/subscription/send      | Live - HTTPS  |
| Subscription - Status | https://api.ideamart.io/subscription/getStatus      | Live - HTTPS  |
| Subscription - Base | https://api.ideamart.io/subscription/query-base      | Live - HTTPS  |
| CAAS - Query | https://api.ideamart.io/caas/balance/query     | Live - HTTPS  |
| CAAS - Debit | https://api.ideamart.io/caas/direct/debit      | Live - HTTPS  |


####End Points: Simulator

|      SMS     | Url                                          | Local / Live  |
|:------------:|----------------------------------------------|---------------|
| SMS          | [http://localhost:7000/sms/send](http://localhost:7000/sms/send)              | Local - HTTPS |
| SMS          | [https://localhost:7447/sms/send](http://localhost:7447/sms/send)              | Local - HTTP  |
|              |     |       |     
| USSD         | [http://localhost:7000/ussd/send](http://localhost:7000/ussd/send)              | Local - HTTP  
| USSD         | [https://localhost:7447/ussd/send](https://localhost:7447/ussd/send)           | Local - HTTPS |
|              |     |       | 
| LBS          | [http://localhost:7000/lbs/locate](http://localhost:7000/lbs/locate)             | Local - HTTP  |
| LBS          | [https://localhost:7447/lbs/locate](https://localhost:7447/lbs/locate)            | Local - HTTPS |
|              |     |       | 
| CAAS - Query | [http://localhost:7000/caas/balance/query](http://localhost:7000/caas/balance/query)     | Local - HTTP  |
| CAAS - Query | [https://localhost:7447/caas/balance/query](https://localhost:7447/caas/balance/query)   | Local - HTTPS |
|              |     |       | 
| CAAS - Debit | [http://localhost:7000/caas/direct/debit](http://localhost:7000/caas/direct/debit)      | Local - HTTP  |
| CAAS - Debit | [https://localhost:7447/caas/direct/debit](https://localhost:7447/caas/direct/debit)     | Local - HTTPS |
|              |     |       | 
| Subscription - Reg/UnReg | https://localhost:7447/subscription/send      | Live - HTTPS  |
| Subscription - Reg/UnReg | http://localhost:7000/subscription/send  | Live - HTTP   |
|              |     |       | 
| Subscription - Status | https://localhost:7447/subscription/getStatus      | Live - HTTPS  |
| Subscription - Status | http://localhost:7000/subscription/getStatus  | Live - HTTP   |
|              |     |       | 
| Subscription - Base | https://localhost:7447/subscription/query-base      | Live - HTTPS  |
| Subscription - Base | http://localhost:7000/subscription/query-base  | Live - HTTP   |
----
###SMS

Production

- HTTPS - [https://api.ideamart.io/sms/send](https://api.ideamart.io/sms/send)

- HTTP  - [http://api.dialog.lk:8080/sms/send](http://api.dialog.lk:8080/sms/send)

Simulator

- HTTP  - [http://localhost:7000/sms/send](http://localhost:7000/sms/send)

----

###USSD

Production

- HTTPS - [https://api.ideamart.io/sms/send](https://api.ideamart.io/ussd/send)

- HTTP - [http://api.dialog.lk:8080/sms/send](http://api.dialog.lk:8080/ussd/send)

Simulator

- HTTP - [http://localhost:7000/ussd/send/](http://localhost:7000/ussd/send/)

- HTTPS - [https://localhost:7447/ussd/send/](https://localhost:7447/ussd/send/)

----
###Charging As A Service  (CAAS)

#### Query

- Production
HTTPS - [https://api.ideamart.io/caas/balance/query](https://api.ideamart.io/caas/balance/query)

- HTTP - [http://api.dialog.lk:8080/caas/balance/query](http://api.dialog.lk:8080/caas/balance/query)

Simulator

- HTTP - [http://localhost:7000/caas/balance/query](http://localhost:7000/caas/balance/query)

- HTTPS - [https://localhost:7447/caas/balance/query](https://localhost:7447/caas/balance/query)



----

#### Debit Check

Production

- HTTPS - [https://api.ideamart.io/caas/direct/debit](https://api.ideamart.io/caas/direct/debit)

- HTTP - [http://api.dialog.lk:8080/caas/direct/debit](http://api.dialog.lk:8080/caas/direct/debit)

Simulator

- HTTP - [http://127.0.0.1:7000/caas/direct/debit](http://127.0.0.1:7000/caas/direct/debit)

-----
###Subscription API
Production

HTTPS - [https://api.ideamart.io/subscription/send](https://api.ideamart.io/subscription/send)

HTTP - [http://api.dialog.lk:8080/subscription/send ](http://api.dialog.lk:8080/subscription/send)

----
###Location Based Services (LBS)
Production

- HTTPS - [https://api.ideamart.io/lbs/locate](https://api.ideamart.io/lbs/locate)

- HTTP - [http://api.dialog.lk:8080/lbs/locate](http://api.dialog.lk:8080/lbs/locate)

Simulator

- HTTP - [http://localhost:7000/lbs/locate](http://localhost:7000/lbs/locate)




----



