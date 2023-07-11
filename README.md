# uasoft-indonesia--badaso


# Description: Badaso v2.9.7 was discovered to contain a Cross Site Scripting (store XSS).

# Affected Component: All versions that are below Badaso v2.9.7

# Step to reproduce: 
Detection and Exploitation: 

1. Login to the dashboard 
2. Go to Racks and click on the action button => add a new rack
2. Inject payload : "' test <img src=\"" onerror="alert(1)"> to Rack Number parameter and submit it. 
3. Go to books and add a new book then malicious is execute


POC: 
![image](https://github.com/anh91/uasoft-indonesia--badaso/assets/132877337/9a3423b8-8c8d-4e3d-8c1a-9143390ac4d0)
![image](https://github.com/anh91/uasoft-indonesia--badaso/assets/132877337/01839383-0b82-4cdc-b1e5-f65ac47267a2)
![image](https://github.com/anh91/uasoft-indonesia--badaso/assets/132877337/8cf72c66-d713-4d09-b294-d9a632b9cf32)


