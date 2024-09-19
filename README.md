# 100-2
print("Welcome to the tip calculator!")
bill = float(input("What was the total bill? $"))
tip = int(input("What percentage tip would you like to give? 10 12 15 "))
# tip_per = tip/ 100
# total_tip = tip_per * bill
# total_amount_paid = bill + total_tip
total_amount_paid = tip/100 * bill + bill
people = int(input("How many people to split the bill? "))
bill_split =  total_amount_paid / people
final_bill = round(bill_split,2)
print(f"the total amount to be paid by one person is: ${final_bill} ")

