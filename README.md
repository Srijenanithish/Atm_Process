# Atm_Process
To program an Automated Teller Machine (ATM) to show the Main Menu specified below and perform some operations like Load Cash to ATM ,Show Customer Details and Show ATM Operations

#It is a Basic C program with some declarations

## Initialization of pre-processors
```include<stdio.h>
include<stdlib.h>
include<string.h>
```

## Initialization for the used Functions
```int load_cash();
int show_customer_details();
int show_atm_operations();
int Check_Balance(int);
int Withdraw_Money(int);
int Transfer_Money();
int check_ATM_balance();
int isvalid(int);
int user_account(int);
```

##Structure declarations for the Customer details and cash denominations
```
struct customer_entry{
    int acc_no;
    char Name[50];
    int pin;
    int acc_balance;

}s[100];
```
```
struct denominations{
    int two_thousands,five_hundreds,hundreds;

}m;
```
## After Declarations
```
The main function will be initialized and get an 
input from the user to perform the operations in a do While loop
```
```
Later getting the choice from the user and the declared fuctions will
be executed one by one according to the user's choice
```
## The Main Output will be
```
-----------Welcome to the ATM service--------------
1. Load cash to ATM
2. Show customer details
3. Show ATM Operations
4. Check ATM Balance
Enter Your Choice5. Quit
--------------------------------------------------

Enter your choice:
```
## Conclution
```
While entering each choice the user can load and can see the changes on the screen.
This will be usefull to make the transaction wise and in clear.
```





