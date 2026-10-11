# 30-days-challenge

Algorithm: TripCalc
• Step 1: Start
• Step 2: Declare variables
Create floating-point variables to store distance, mileage, fuel_price, fuel_required, and total_cost.
• Step 3: Read inputs
	• Prompt the user and input the total distance in kilometers.
	• Prompt the user and input the vehicle's mileage (kilometers per liter).
	• Prompt the user and input the current fuel price per liter.
• Step 4: Calculate fuel required
	• Divide distance by mileage and store the result in fuel_required (\(\text{fuel\_required} = \frac{\text{distance}}{\text{mileage}}\)).
• Step 5: Calculate total fuel cost
	• Multiply fuel_required by fuel_price and store the result in total_cost (\(\text{total\_cost} = \text{fuel\_required} \times \text{fuel\_price}\)).
• Step 6: Display results
	• Print the calculated fuel_required and total_cost.
• Step 7: Stop






input
<img width="683" height="621" alt="Screenshot 2026-09-30 180915" src="https://github.com/user-attachments/assets/4bca81e4-2b05-4b45-91b0-cef2ecdfcadf" />
output
<img width="490" height="594" alt="Screenshot 2026-09-30 180841" src="https://github.com/user-attachments/assets/62089b83-d2a0-488b-b2da-1138f8fbd6df" />



CHALLENGE 3

ALGORITHM 

1. Start.

2. Declare purchaseamount and distance as floats, customertype as an integer, and discount percent,

discount_amount, amount after discount, delivery charge and final payable as floats initialised to 0.0. 3. Read the purchase amount, the customer type (1 = Student, 2 = Regular Customer) and the delivery distance in

km.

4. If the customer type is 1 and the purchase amount ≥ 2000 set the discount to 15%; if the purchase amount < 2000 set it to 10%.

5. If the customer type is 2 and the purchase amount ≥ 3000 set the discount to 8%; if the purchase amount < 3000 set it to 0%. For any other customer type print "Invalid customer" and set the discount to 0%.

6. Calculate discount_amount = (discount percent / 100.0) * purchaseamount and amount after discount = purchaseamount - discount_amount.

7. If the distance ≤ 5 km the delivery charge is Rs.40; else if the distance ≤ 15 km it is Rs.70; otherwise it is Rs.100.

8. Calculate final_payable = amount_after_discount + delivery_charge, display all the values with two decimals.
9. stop
    

INPUT


<img width="826" height="965" alt="Screenshot 2026-10-11 182043" src="https://github.com/user-attachments/assets/bd7caedc-9699-4c7b-a68d-a99d6d056e71" />



OUTPUT


<img width="549" height="1039" alt="Screenshot 2026-10-11 182251" src="https://github.com/user-attachments/assets/619f209b-351a-4172-801a-90c647d210c8" />

