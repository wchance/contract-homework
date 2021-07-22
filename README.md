# Looks like we have made our First Contract!

### 1_AssociatedProfitSplitter.sol
We created a smart contract that splits the msg.value equally to 3 predefined addresses and returns any change to msg.sender.  

1.  Deployed Smart Contract 0x5a7927E98D2634d8338ea3543FC4Cbd112aFCA52

    Deposits are split equally amongst these addresses
    _ONE        0x6F04fA00Da809De1c80169b6dcAD70221Ec5f67f 
    _TWO        0xd14F4d983b134DCF0Fdb622d96B193E6B3FA3050
    _THREE      0x2b485Bc20176AC20ea7C346AD2afA8C517fc7895

    ![Deployed](Images/1.0_deploy_contract.PNG)

2.  Deposited 1.00 ETH to smart contract 0x5a7927E98D2634d8338ea3543FC4Cbd112aFCA52
    ![Deposit 1 ETH](Images/1.1_deposit_to_contract.PNG)

3.  Confirmed on Ropsten 
    ![Confirmed](Images/1.2_deposit_confirmation.PNG)

### 2_TieredProfitSplitter.sol
In this smart contract example we split the msg.value unevenly amongst different employees using basis points.

### 3_DeferredEquityPlan.sol
In this smart contract we keep track of employees stock incentive plan and use date to insure the employee is distributed annually.


