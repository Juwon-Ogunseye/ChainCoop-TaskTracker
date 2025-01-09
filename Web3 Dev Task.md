### Task Overview

#### **Integration Tasks**

1. **Integrate Celo Wallet**
    
    - Enable users to interact with the Celo blockchain for seamless transactions.
2. **Implement Smart Contracts**
    
    - Develop and deploy smart contracts for key functionalities.
3. **Smart Lock System**
    
    - Integrate a smart lock feature that automatically locks cryptocurrency whenever a user deposits Naira into their account.
4. **Naira-to-Crypto Conversion**
    
    - Build an internal system to convert users' deposited Naira into their selected cryptocurrency.

---

#### **Smart Contract Development Flow**

1. **Smart Contracts for Locking**
    
    - Create three separate smart contracts:
		1. One for **Lisk**
		2. One for **Celo**
		3. One for the **BTC Lightning Network**
1. **Savings Workflow**
    
    - **User Input:**  
        A user selects a monthly savings amount (e.g., 2000 Naira).  
        They specify:
        
        - An **end date** for their savings goal.
        - The type of savings plan:
            - **Strict Savings:**
                - The user is charged a 2% fee if they choose to break their savings before the end date.
            - **Flexible Savings:**
                - The user can withdraw their savings at any time without any charges.
    - **Savings Management:**
        
        - At the end date, users can withdraw their accumulated savings, including any cryptocurrency equivalent based on their selected conversion.