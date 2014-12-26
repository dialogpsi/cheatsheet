Cheatsheet
==========

######All Ideamart Pro Details Here
----

######Below are endpoints


|      SMS     | Url                                          | Local / Live  |
|:------------:|----------------------------------------------|---------------|
| SMS          | https://api.dialog.lk/sms/send               | Live - HTTPS  |
| SMS          | http://api.dialog.lk:8080/sms/send           | Live - HTTP   |
| SMS          | [http://localhost:7000/sms/send](http://localhost:7000/sms/send)              | Local - HTTPS |
| SMS          | [https://localhost:7447/sms/send](http://localhost:7447/sms/send)              | Local - HTTP  |
| USSD         | https://api.dialog.lk/sms/send               | Live - HTTPS  |
| USSD         | http://api.dialog.lk:8080/sms/send           | Live - HTTP   |
| USSD         | [http://localhost:7000/ussd/send](http://localhost:7000/ussd/send)              | Local - HTTP  |
| USSD         | [https://localhost:7447/ussd/send](https://localhost:7447/ussd/send)           | Local - HTTPS |
| LBS          | https://api.dialog.lk/lbs/locate             | Live - HTTPS  |
| LBS          | http://api.dialog.lk:8080/lbs/locate         | Live - HTTP   |
| LBS          | [http://localhost:7000/lbs/locate](http://localhost:7000/lbs/locate)             | Local - HTTP  |
| LBS          | [https://localhost:7447/lbs/locate](https://localhost:7447/lbs/locate)            | Local - HTTPS |
| CAAS - Query | https://api.dialog.lk/caas/balance/query     | Live - HTTPS  |
| CAAS - Query | http://api.dialog.lk:8080/caas/balance/query | Live - HTTP   |
| CAAS - Query | [http://localhost:7000/caas/balance/query](http://localhost:7000/caas/balance/query)     | Local - HTTP  |
| CAAS - Query | [https://localhost:7447/caas/balance/query](https://localhost:7447/caas/balance/query)   | Local - HTTPS |
| CAAS - Debit | https://api.dialog.lk/caas/direct/debit      | Live - HTTPS  |
| CAAS - Debit | http://api.dialog.lk:8080/caas/direct/debit  | Live - HTTP   |
| CAAS - Debit | [http://localhost:7000/caas/direct/debit](http://localhost:7000/caas/direct/debit)      | Local - HTTP  |
| CAAS - Debit | [https://localhost:7447/caas/direct/debit](https://localhost:7447/caas/direct/debit)     | Local - HTTPS |
| Subscription | https://api.dialog.lk/subscription/send      | Live - HTTPS  |
| Subscription | http://api.dialog.lk:8080/subscription/send  | Live - HTTP   |


----
###SMS

Production

HTTPS - [https://api.dialog.lk/sms/send](https://api.dialog.lk/sms/send)

HTTP  - [http://api.dialog.lk:8080/sms/send](http://api.dialog.lk:8080/sms/send)


Simulator

HTTP  - [http://localhost:7000/sms/send](http://localhost:7000/sms/send)

----

###USSD

Production

HTTPS - [https://api.dialog.lk/sms/send](https://api.dialog.lk/ussd/send)

HTTP - [http://api.dialog.lk:8080/sms/send](http://api.dialog.lk:8080/ussd/send)


Simulator

HTTP - [http://localhost:7000/ussd/send/](http://localhost:7000/ussd/send/)

HTTPS - [https://localhost:7447/ussd/send/](https://localhost:7447/ussd/send/)

----

###Charging As A Service  (CAAS)

#### Query

Production

HTTPS - [https://api.dialog.lk/caas/balance/query](https://api.dialog.lk/caas/balance/query)

HTTP - [http://api.dialog.lk:8080/caas/balance/query](http://api.dialog.lk:8080/caas/balance/query)


Simulator

HTTP - [http://localhost:7000/caas/balance/query](http://localhost:7000/caas/balance/query)


HTTPS - [https://localhost:7447/caas/balance/query](https://localhost:7447/caas/balance/query)



----




#### Debit Check

Production

HTTPS - [https://api.dialog.lk/caas/direct/debit](https://api.dialog.lk/caas/direct/debit)

HTTP - [http://api.dialog.lk:8080/caas/direct/debit](http://api.dialog.lk:8080/caas/direct/debit)


Simulator

HTTP - [http://127.0.0.1:7000/caas/direct/debit](http://127.0.0.1:7000/caas/direct/debit)

-----
###Subscription API

Production

HTTPS - [https://api.dialog.lk/subscription/send](https://api.dialog.lk/subscription/send)

HTTP - [http://api.dialog.lk:8080/subscription/send ](http://api.dialog.lk:8080/subscription/send)


----
###Location Based Services (LBS)

Production

HTTPS - [https://api.dialog.lk/lbs/locate](https://api.dialog.lk/lbs/locate)

HTTP - [http://api.dialog.lk:8080/lbs/locate](http://api.dialog.lk:8080/lbs/locate)


Simulator

HTTP - [http://localhost:7000/lbs/locate](http://localhost:7000/lbs/locate)

----



