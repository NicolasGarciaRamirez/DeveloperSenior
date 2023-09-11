# Senior Developer Test - NicoPay Ecosystem

Welcome to the exciting Senior Developer test within the vibrant NicoPay ecosystem! In this test, you will immerse yourself in integrating three essential components: the mysterious Tertiary Tree, the powerful NicoPay SDK, and the fearless NicoPay, our leading transactional system. Additionally, you will be tasked with incorporating the NicoPay SDK into the innovative PaymentsNico. Get ready for a challenging and exhilarating experience!

## The Tertiary Tree: A Multilevel Enigma
Our enigmatic Tertiary Tree is responsible for enabling a multilevel structure and user referencing within our system. Its key functions include:

- **Create User Nodes:** Allows the creation of nodes to represent users in the system.
- **Establish Relationships:** Facilitates the creation of multilevel relationships among users.
- **Search and Reference:** Enables searching and referencing users within the tree structure.
- **Update User Data:** Permits the modification of user attributes such as name, email, etc.

### Attribute Specifications
| Attribute          | Data Type     |
|--------------------|---------------|
| User ID            | Integer       |
| Name               | Text          |
| Email Address      | Text          |
| Level              | Integer       |
| Parent Nodes       | List of Integers |


## NicoPay SDK: The Power of Payments
The NicoPay SDK is our most valuable gem. Its primary functions include:

- **Load Balance:** Provides the ability to load balance into user accounts securely.
- **Balance Deduction:** Allows for balance deductions for transactions and purchases.
- **Transaction History:** Offers a record of all transactions conducted through the SDK.
- **Get Balance:** Permits users to query their current balance.

### Attribute Specifications
| Attribute          | Data Type     |
|--------------------|---------------|
| User ID            | Integer       |
| Amount             | Decimal       |
| Transaction Type   | Text          |
| Date and Time      | Date and Time |


## NicoPay - The Transactional Heartbeat
NicoPay, the heartbeat of our ecosystem, is a transactional system that enables users to load and deduct balance from their accounts, providing an experience similar to PayU. Its primary functions include:

- **Load Balance:** Allows users to add balance to their accounts from various payment sources.
- **Balance Deduction:** Facilitates balance deduction when users make transactions or purchases.
- **Transaction History:** Maintains a detailed record of all transactions made in user accounts.
- **Get Balance:** Permits users to check their current balance.
- **Transaction Verification:** Allows users to verify the status of a transaction.

### Attribute Specifications
| Attribute          | Data Type     |
|--------------------|---------------|
| User ID            | Integer       |
| Amount             | Decimal       |
| Transaction Type   | Text          |
| Date and Time      | Date and Time |
| Transaction Status | Text          |


## PaymentsNico: The Synchrony of Payments
In the thrilling PaymentsNico, you must incorporate the power of the NicoPay SDK to enable users to process payments effectively. Its primary functions include:

- **Process Payments:** Utilizes the NicoPay SDK to process user payments efficiently.
- **Payment Records:** Maintains a record of all payments made through PaymentsNico.
- **Transaction Notifications:** Notifies users about the status of their transactions and payments.
- **Check Payment History:** Allows users to view their payment history.

### Attribute Specifications
| Attribute          | Data Type     |
|--------------------|---------------|
| User ID            | Integer       |
| Amount             | Decimal       |
| Description        | Text          |
| Date and Time      | Date and Time |
| Transaction Status | Text          |


