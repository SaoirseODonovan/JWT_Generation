# JWT_generation
JWT token generation and validation.
What is expected when running: Running the auto.sh script to generate the private key and the token.
![image](https://user-images.githubusercontent.com/74667820/190149846-05d6cdd7-6f5a-4bfb-8320-acc586959c1f.png)
If the script is prompted to run by a user who is not root, this output is generated.
![image](https://user-images.githubusercontent.com/74667820/190149969-8247b58f-cd13-46d2-b6fc-9e7816035549.png)
To validate that token, run the main.go file within the validate directory. It will use regex to compare token signatures to make sure that they match, make sure that the JWT token contains two ‘.’ And follows the expected syntax.
![image](https://user-images.githubusercontent.com/74667820/190150030-0be74a2a-703b-4d29-88b6-03e076af15a6.png)
When I altered the token.txt file and changed the token, this is the difference in the output when running the validation:
![image](https://user-images.githubusercontent.com/74667820/190150081-e8150a14-f8f5-4c7f-a01d-2122de1eebcc.png)
