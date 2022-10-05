# Dmoney API Automation with Jmeter
### IDE used
    Apache Jmeter 5.5
    Postman

### Listing the APIs below that I have used for my testing:

|Method|                        Url	                                    | Decription	|Sample Valid Request Body|
|------|-------------------------------------------------------------------|--------------|------------------------|
| POST |https://dmoney.professionaltrainingbd.com/user/login      |User login |  JSON     |
| GET  |https://dmoney.professionaltrainingbd.com/user/list      |Get customer list |	 VOID  |
| POST |https://dmoney.professionaltrainingbd.com/user/create |Create customer | JSON   |
| GET  |https://dmoney.professionaltrainingbd.com/user/search?phone_number=${phone_number}	| Search user by phone number | VOID   |
| GET  |https://dmoney.professionaltrainingbd.com/user/search?id=${id} |  Search user by ID | VOID   |
| GET  |https://dmoney.professionaltrainingbd.com/user/search?email=${email}|Search user by email | VOID   |
| DEL  |https://dmoney.professionaltrainingbd.com/user/delete/${id}|Delete customer | VOID   |


## Postman collection
    https://www.getpostman.com/collections/a8f908e0ee1d77cb6f85

## Jmeter scripts:
    1. Write the scripts according to the postman collection
    2. Run the test in jmeter
#### Test Report
![Dmoney-API-TestReport](https://github.com/Foysal061/Dmoney-API-jmx/blob/main/Dmoney-API-TestReport.png)

