# Operators Project

### Objective

Understand and apply basic operators in Java.

### Problem

Create a program that calculates the total price of items, applies a tax, updates the stock using assignment operators, and checks if the user is eligible for a discount.

### Implementation

- Create three variables: `price = 100.0`, `quantity = 3`, and `couponActive = true`.
- Calculate the total by **multiplying the price and quantity**.
- **Apply a 15% VAT** tax (0.15) to the total by **using the multiplication assignment operator**.
- Determine if the user qualifies for free shipping by **checking if the total is greater than 300** `OR` **if the couponActive is true**.
- Determine if the user is a VIP buyer by **checking if the quantity is greater than or equal to 4** `AND` **if the total is greater than 350**.

```java
public class Main {
    public static void main(String[] args) {
        /* add your code here */
    }
}
```
**Expected Output:**
```
Total (Without Tax): 300.0
Total (With Tax): 345.0
Free Shipping Eligible: true
VIP Buyer Status: false
```
