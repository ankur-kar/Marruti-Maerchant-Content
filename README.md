# Marruti-Maerchant-Content
This uses the Google Content API to feed data into Maruti Merchant Center
The file content-api-key.json needs to be created based on the account details of the user.
The user needs to change the path of the API in the main file content.py
filename= path to 'content-api-key.json'.
The whole programme has been divided into 2 major funcitons- 
  a. - The insert function
      As the name suggests the funciton is required to insert products to the Merchant site.
      The parameter for the funciton are as shown below
      insert(itemid,title,description,link,imageLink,brand,color,condition,prodcat,value,adProducttype,customattval)
  b. -  The delete function
      As the name suggests the function deletes te required product from the Merchant list the only parameter it takes in the prodcut item       ID as shown
        delete(itemid)
########################################################################################################################################
This code is a property of AdGlobal30 PVt.Ltd.
########################################################################################################################################

