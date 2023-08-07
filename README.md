# ATM-MACHINE
balance = 10000000

print("""
      
      Welcome to ATM 
      
      
      choose your Transaction
      
      1).BALANCE
      2).WITHDRAW
      3).DEPOSIT
      4).EXIT
      """)

option = int(input("Enter Transaction"))

if(option == 1):
    
    print("your balance is : ", balance)

elif(option == 2):
    
    withdraw = float(input("Enter the amount : "))
    
    if(balance > withdraw):
        
        total = balance - withdraw
        
        print("success")
        
        print("your new balance is : ", total) 
   
    else:
        
        print("Insufficiant Fund")

elif(option == 3):
    
    deposit = float(input("Enter the amount :"))
    
    totalbalance = balance + deposit
    
    print("success")
    
    print("your new balance is : ", totalbalance)

elif(option == 4):
    
     print("Exit")

Output 1:
    
    Welcome to ATM


      choose your Transaction

      1).BALANCE
      
      2).WITHDRAW
      
      3).DEPOSIT
     
      4).EXIT

Enter Transaction1

your balance is :  10000000


Output 2:
Welcome to ATM


      choose your Transaction

      1).BALANCE
      
      2).WITHDRAW
      
      3).DEPOSIT
      
      4).EXIT

Enter Transaction2

Enter the amount : 20000

success

your new balance is :  9980000.0


Output 3:
Welcome to ATM


      choose your Transaction

      1).BALANCE
      
      2).WITHDRAW
      
      3).DEPOSIT
      
      4).EXIT

Enter Transaction3

Enter the amount :30000

success

your new balance is :  10030000.0

     
