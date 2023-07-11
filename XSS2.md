# uasoft-indonesia--badaso


# Description: Badaso v2.9.7 was discovered to contain a Cross Site Scripting (store XSS).

# Affected Component: All versions that are below Badaso v2.9.7

# Step to reproduce: 
Detection and Exploitation: 

1. Login to the dashboard 
2. Go to Racks and click on the action button => add a new book or edit book 
2. Inject payload : "' test <img src=\"" onerror="alert(5)"> to Title of book parameter and submit it. 
3. Go to Borrowing and add a new Borrowing or edit Borrowring then malicious is execute


POC: 
![image](https://github.com/anh91/uasoft-indonesia--badaso/assets/132877337/acf14463-d665-4572-9cd0-288ff21357d4)

![image](https://github.com/anh91/uasoft-indonesia--badaso/assets/132877337/ef6f72ab-cb2e-4a3a-a692-5c8440eeabc5)

