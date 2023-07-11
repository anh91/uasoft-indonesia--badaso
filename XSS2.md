# uasoft-indonesia--badaso


# Description: Badaso v2.9.7 was discovered to contain a Cross Site Scripting (store XSS).

# Affected Component: All versions that are below Badaso v2.9.7

# Step to reproduce: 
Detection and Exploitation: 

1. Login to the dashboard 
2. Go to Racks and click on the action button => add a new book or edit book 
2. Inject payload : "' test <img src=\"" onerror="alert(1)"> to Title of book parameter and submit it. 
3. Go to Borrowing and add a new Borrowing or edit Borrowring then malicious is execute


POC: 


