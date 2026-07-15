print("Hellooo, this is task 1 'Instant Discount System'")
total = float(input("Please enter the total purchase amount: "))

if total < 100:
    discount_value = 0.0
    ntotal = total
elif total >= 100 and total < 500:
    discount_value = total * 0.10
    ntotal = total - discount_value
else:  # Any value 500 or more
    discount_value = total * 0.20
    ntotal = total - discount_value

# Output in clean English
print(f"Your available discount value is: {discount_value} EGP")
print(f"The total amount due after discount is: {ntotal} EGP")
