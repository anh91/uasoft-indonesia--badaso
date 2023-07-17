uasoft-indonesia--badaso


# Description: Badaso v2.9.7 was discovered to contain a Cross Site Scripting (store XSS).

# Affected Component: All versions that are below Badaso v2.9.7

# Step to reproduce: 
Detection and Exploitation: 

1. log in to the dashboard with the account have the role Editor
2. Go to category => add new category or edit tag
2. Inject payload : "' test <img src=\"" onerror="alert()"> to title and submit. 
3. log in to the admin account to the dashboard and access to new post or edit port then malicious is execute

POC: 
![image](https://github.com/anh91/uasoft-indonesia--badaso/assets/132877337/2511528e-6a2a-47bb-9ebe-9a25213e6963)
![image](https://github.com/anh91/uasoft-indonesia--badaso/assets/132877337/3dad9895-34d2-4e40-91fb-cb52c02eba4c)



