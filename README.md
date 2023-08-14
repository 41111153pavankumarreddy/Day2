DAY2 ASSIGNMENT
def calculate_bonus(salary, year_of_service): 
if year_of_service > 10:
 bonus_percentage = 0.10
 elif 6 <= year_of_service <= 10:
 bonus_percentage = 0.06
 else:
 bonus_percentage = 0.05
 bonus_amount = salary * bonus_percentage 
return bonus_amount 
salary = float(input("Enter your salary: "))
 year_of_service = int(input("Enter your year of service: ")) 
bonus_amount = calculate_bonus(salary, year_of_service)
 print(f"Your net bonus amount is: ${bonus_amount:.2f}")

OUTPUT
 Enter your salary:30000
 Enter your year of service: 5 
Your net bonus amount is: $1500.00

def calculate_discount(market_price):

if market_price > 10000:
    discount = 0.20
elif 7000<= market_price <= 10000:
    discount = 0.15
else:
    discount = 0.10
net_amount = market_price * discount
return net_amount 
market_price = float(input("Enter your market_price: ")) net_amount = calculate_discount(market_price) print(f"Your net amount is: ${net_amount:.2f}")

OUTPUT
 Enter your market_price: 10000
 Your net amount is: $1500.00

        # relational  operation
pavan_age = 30 sandeep_age = 32

pavan_age == sandeep_age

output

 False

pavan_age <= sandeep_age

output
 True

pavan_age >= sandeep_age

output 
False

pavan_age

output
 30

pavan_age < sandeep_age

output
 True

pavan_age > sandeep_age

output 
False

         logical operator


         AND
is_student = True
in_college = True 
in_school = False

is_student and in_college

output
 True

is_student and in_school

output
 False

in_college and in_school

output 

True

                OR
is_student = True
in_college = True 
in_school = False

is_student or in_college

output 
True

is_student or in_school

output

 True

in_college or in_school

output 

True

x = [3,4,5]
 y = [1,2,3] 
k = [3,4,5] 
z = x 
k = y 
print(x is not z) 
print(k is x) 
print(id(x)) 
print(id(y)) 
print(id(z)) 
print(id(k))

output
 False
 False 
2471496141632 
2471496147072 
2471496141632 
2471496147072

x = '112'
 y = '112'
 z = '115'
 if (x is not y): 
print('x is not y')
 else:
 print('x is y')
 if (x is not z):
 print('x is not z') 
else: print('x is z')
 if (y is not z): 
print('y is not z')
 else:
 print('y is z') 
print(id(x)) 
print(id(y)) 
print(id(z))

OUTPUT
 x is y
 x is not z
 y is not z
 2471461620272 
2471461620272 
2471461620528

           sorting element in list
avg_prices = [24,38,19,53,3,155,99]
 avg_prices.sort() 
avg_prices

OUTPUT 
[3, 19, 24, 38, 53, 99, 155]

products = ["chocolate", "cake", "bakery"]
 products.sort()
 products

OUTPUT
 ['bakery', 'cake', 'chocolate']

               
