# Duplicate-check-without-script

For Duplicate check without scripting we need to use User defined Map function inside Business rules shape

![image](https://user-images.githubusercontent.com/97012694/147905582-085a047d-ad28-48cd-b585-e013cb14b249.png)

Business rule shape looks like this(note: plz ignore check status rule)

![image](https://user-images.githubusercontent.com/97012694/147905613-15101f8a-fa7c-4d94-8a0c-bb9cd1cecbd2.png)

Detect duplicate map function inputs: Key is the primary key and we need to add some random suffix to it

![image](https://user-images.githubusercontent.com/97012694/147905687-e659de3c-9002-4e72-b33b-58acd0b047f0.png)

User defined map function looks like this

![image](https://user-images.githubusercontent.com/97012694/147905922-2a0b3ed1-aa7f-4668-b566-cc2080b0143e.png)

We need to concat the keys and suffix and set the DPP and value as true. Refer the above image for ref.

