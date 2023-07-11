md# uasoft-indonesia--badaso


# Description: Badaso v2.9.7 was discovered to contain a Cross Site Scripting (store XSS).

# Affected Component: All versions that are below Badaso v2.9.7

# Step to reproduce: 
Detection and Exploitation: 

1. Login to the dashboard 
2. Go to Racks and click on the action button => add a new member or edit a member 
2. Inject payload : "' test <img src=\"" onerror="alert()"> to Name of member parameter and submit it. 
3. Go to Borrowing and add a new Borrowing or edit Borrowing then malicious is execute


POC: 
![image](https://github.com/anh91/uasoft-indonesia--badaso/assets/132877337/e13c887f-e23c-403e-bcd6-65fc01a41917)
![image](https://github.com/anh91/uasoft-indonesia--badaso/assets/132877337/b4a25e3f-7109-4e3e-99fb-cfb3fac0cf2d)


