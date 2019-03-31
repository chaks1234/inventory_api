# inventory_api
This is inmplemention of api for a inventory in django



 # To Add a New Random Inventory (This can be called manually or from any script)
 http://localhost:8000/inventory/add

 # To List all the Inventories, with pagination (parameters are self explanatory)
 http://localhost:8000/inventory/list/?page_size=100;page_number=1

 # To Purchase any particular Inventory (paramters are self Explanatory)
 http://localhost:8000/inventory/purchase/?invId=randomString;quantity=50

 Notes :
 1) Look at the requirements from requirements.txt
 2) Project implemented in django
 3) The Responses are being generated in JsonFormat (simply to save time. Can add UI with little more effort)
 4) Made an API to add Inventory as it makes more sense and provides more flexibility than a seperate script to do the same
 5) You can run by command:
 	python manage.py runserver
