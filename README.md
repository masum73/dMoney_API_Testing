## Test Scenarios
* The Admin needs to log in with email admin@roadtocareer.net and pass 1234, which creates a token that will expire in one hour. 
* Admin creates two random Customers, an Agent, and a Merchant.
* System account: SYSTEM (range 10 TK to 10,000 TK) can deposit to the agent.
* The agent deposits money into one of the customers ' accounts.
* System account: SYSTEM (range 10 TK to 10,000 TK) can deposit to the customers.
* Check the customer's balance.
* Check the Agent's balance.
* Check the Merchant's balance.
* Send money from one Customer to another Customer.
* Withdraw any amount from a Customer to the Agent (range 10 TK to 10,000 TK).
* Check the Transaction statement using the customer account.
* Check the Transaction limit using the customer account.
* Check the Transaction balance using the customer account.
* Check all the Transaction lists.
* Search the transaction by tranxid. 
* Make a payment from the Customer to the Merchant.
* and many more with negative test scenarios. 


## API Endpoints
* https://dmoney.roadtocareer.net/api-docs/user/#/
* https://dmoney.roadtocareer.net/api-docs/transaction/#/

## Postman Integration Documentation
https://documenter.getpostman.com/view/12838371/2sB3BHk8yG

## Newman Report
<img width="917" height="863" alt="image" src="https://github.com/user-attachments/assets/4204f0d7-d4a3-4d27-99f5-eb70359a426e" />
<img width="917" height="842" alt="image" src="https://github.com/user-attachments/assets/24ed6e0d-693f-484a-a686-1eb074ce8d8c" />

