# Shopping_calculations
This is a simple python logic to calculate shopping mall bill.

print("Welcome!!!")
shirt_price = 120
pant_price = 200

quantity_shirt = int(input("Enter how many shirts you bought:" ))
quantity_pant = int(input("Enter how many pants you bought:" ))

subtotatl_shirts = quantity_shirt * shirt_price
subtotatl_pants = pant_price * quantity_pant

print("Total_amount_of_shirts:", subtotatl_shirts)
print("Total_amount_of_pants:", subtotatl_pants)

Total = subtotatl_shirts + subtotatl_pants

print("Your Total Amount:", Total)
print("Adding Discount:..")
discount = Total * 0.09
print("Your discount:", discount)
print("Calculating grand_total:..")
Grand_total = Total - discount
print("Your Grand Total:", Grand_total)
print("Pay:" , Grand_total)
print("Thank you for SHOPPING!!")
print("Visit Again")
