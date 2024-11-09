# Function to calculate the discounted price
def calculate_discount(price=1000, discount_amount=50):
    # Check if the discount amount is 50 or more
    if discount_amount >= 50:
        # Calculate the final price after applying the discount
        final_price = price - discount_amount
        return final_price
    else:
        # Return the original price if the discount is less than 50
        return price

# Set fixed values for the original price and discount amount
original_price = 1000  # Fixed price
discount_amount = 50   # Fixed discount amount

# Calculate and output the final price
final_price = calculate_discount(original_price, discount_amount)
final_price
