# OTP Verification Program in Python
A simple Python program to generate and verify a 6-digit OTP (One-Time Password)

## Notes
* This is a basic OTP simulation program
* In real applications:

  * OTP is sent via SMS/Email
  * OTP is not shown on screen
  * OTP expires after some time

## Technologies Used
* Python
* Built-in `random` module

## How It Works
This program generates a random 6-digit OTP and asks the user to enter it for verification.

### Steps:

1. Generate a 6-digit OTP using `random.randint()`
2. Display the OTP on the screen
3. Take input from the user
4. Compare entered OTP with generated OTP
5. Show result (Verified / Wrong OTP)


## ====== Example Output ======

## Correct OTP

```
Your OTP is: 483921  
Enter OTP: 483921  
OTP Verified!
```

## Wrong OTP

```
Your OTP is: 726154  
Enter OTP: 123456  
Wrong OTP!
```

## Author
**Ayush Singh**
GitHub: https://github.com/ayush893singh
