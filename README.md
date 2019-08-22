# hello-world
A learning test on how to generate a repository on GitHub
this is my first time learning GitHub and how to add commits to my 

Copying a code 

class Account:

    def __init__(self,owner,balance=0):
        self.owner=owner
        self.balance=balance
        
    def __str__(self):
        return f'Account owner:   {self.owner}\nAccount balance: ${self.balance}'
    
    def deposit(self,deposit):
        self.balance += deposit
        print (f" Deposit of {deposit} accepted,\n your current balance is:{self.balance}) ")
        #print(f"your current balance is :{self.balance}")
    def withdraw(self, withdraw):
        if self.balance >= withdraw:
            self.balance -= withdraw
            print('Withdraw')
        else:
            print('Insuficient funds')
