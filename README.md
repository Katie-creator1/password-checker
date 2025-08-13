# password-checker
## What It Does

- This Python script checks if one or more passwords have been exposed in known data breaches by querying the Have I Been       Pwned API.

- It uses the k-anonymity method to send only the first 5 characters of a SHA-1 hash of your password to the API.

- The API returns possible matches, and the script checks if your full hash appears in the results.

- If found, it displays how many times that password has been seen in breaches, allowing you to know if you should change it.

## Skills Practiced

- Secure API usage with k-anonymity to protect sensitive input.

- SHA-1 hashing for password privacy before sending data.

- HTTP requests and error handling with requests.

- String manipulation and slicing for hash processing.

- Command-line arguments with sys.argv.

## Technologies Used

- Python 3

- requests – For making HTTP calls to the API.

- hashlib – For generating SHA-1 hashes.

- Have I Been Pwned API – For checking password breach status.

## What I Learned

- How to interact with a real-world public API safely.

- How k-anonymity helps protect privacy in sensitive lookups.

- How to hash and manipulate strings for security purposes.

- Error handling for network requests.

- How to use command-line arguments to make scripts flexible.
