uasoft-indonesia--badaso


# Description: Badaso v2.9.7 was discovered to contain a Cross Site Scripting (store XSS).

# Affected Component: All versions that are below Badaso v2.9.7

# Step to reproduce: 
Detection and Exploitation: 

1. log in to the dashboard with the account have the role Editor
2. Go to category => add new category or edit category
2. Inject payload : "' test <img src=\"" onerror="alert()"> to title and submit. 
3. log in to admin account to the dashboard and access to new post or edit port or new Category or Category edit  then malicious is execute

POC: 
![image](https://github.com/anh91/uasoft-indonesia--badaso/assets/132877337/3f50cce1-124b-4825-8780-c602fd544c5d)
![image](https://github.com/anh91/uasoft-indonesia--badaso/assets/132877337/eed5d544-1887-4fd8-ae22-cefde6d05f8d)



