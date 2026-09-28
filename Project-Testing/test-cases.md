### Test Case 1: User Registration
- Input: Name, Email, Password
- Expected: User account created successfully
- Result: Pass

### Test Case 2: User Login
- Input: Correct Email & Password
- Expected: Redirect to Dashboard
- Result: Pass
- Input: Wrong Password
- Expected: Show "Invalid Credentials"
- Result: Pass

### Test Case 3: Add Expense
- Input: Amount Rs.500, Category "Food", Date: Today
- Expected: Expense added and shown in dashboard pie chart
- Result: Pass

### Test Case 4: AI Auto-Categorization
- Input: Note = "Swiggy order 250"
- Expected: Auto-category should be "Food"
- Result: Pass (92% Accuracy)

### Test Case 5: Budget Limit Alert
- Input: Set Food budget Rs.2000, Add expense Rs.2100
- Expected: Alert message "You exceeded your Food budget by Rs.100!"
- Result: Pass

### Test Case 6: Invalid Data Handling
- Input: Negative amount -500
- Expected: Error "Amount cannot be negative"
- Result: Pass

### Test Case 7: Dashboard Loading
- Input: Open Dashboard page
- Expected: Charts load within 2 seconds
- Result: Pass
