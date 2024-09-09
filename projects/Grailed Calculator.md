---
layout: project
type: project
image: 
title: "FasterFashionAI"
date: 2024
published: true
labels:
  - Grailed
  - Finance
  - Fashion
  - Calculator
  - Program
summary: "This program calculates the seller's net earning fee"
---
--- 
Project Name: Grailed Calculator

The provided Java code defines a program titled `GrailedSellerEarningsCalculator`, which is designed to help sellers on the Grailed platform calculate their net earnings from selling items after various deductions. Here's a breakdown of the functionality and the impact of this program:

### Technical Analysis:

1. **Initialization and User Interaction**:
   - The program uses the `Scanner` class to capture input from the user through the console.
   - It greets the user and prompts them to enter necessary details such as the selling price of the item, state tax percentage of the buyer, and whether the payment is domestic or international.

2. **Calculations**:
   - **State Tax Calculation**: It computes the total cost of the item including state tax, which is calculated as `sellingPrice * (1 + stateTaxPercent / 100)`.
   - **Company Commission**: Grailed's commission is taken as 9% of the selling price (`sellingPrice * 0.09`).
   - **Payment Processing Fees**: Depending on whether the payment is domestic or international, the payment processing fee percentage changes between 3.49% and 4.99%, with an additional fixed fee of $0.49.
   - **Net Earnings**: It subtracts the sum of the company commission and payment processing fee from the selling price to determine the net earnings.

3. **Output**:
   - The results are formatted and displayed to the user showing the net earnings after all deductions.
   - The program allows the user to repeat the calculation as needed based on their input of "yes" or "no" when prompted to run another calculation.

4. **Loop and Closure**:
   - The calculations are enclosed in a `do-while` loop, which continues to execute as long as the user wishes to perform more calculations.
   - Once completed, the program closes the `Scanner` object to free up resources.

### Impact and Usefulness:

- **Practical Utility**: This program is highly practical for sellers on Grailed by providing them with a clear picture of their actual earnings after deductions. This helps in pricing strategies and understanding potential profits.
- **Financial Planning**: Sellers can better manage their financial expectations and accounting, ensuring there are no surprises in terms of net earnings.
- **User-Friendly**: The interactive nature of the program, coupled with clear prompts and the option to perform multiple calculations, enhances user experience.
- **Educational Value**: For new sellers, this tool educates them on various costs involved in selling online, such as state taxes, platform fees, and payment processing fees.

### Conclusion:

The `GrailedSellerEarningsCalculator` serves as a useful tool for online sellers to manage their finances more effectively, enhancing their selling experience on the Grailed platform. The program is robust, accounting for various scenarios and inputs, which makes it a valuable asset for anyone engaged in online sales where deductions can significantly affect net earnings.
