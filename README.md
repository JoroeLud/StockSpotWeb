# StockSpotWeb
Right-click the Databases node in Object Explorer and select Restore Database and restore PurchaseOrder.Bak
Copy server name and then paste it in appsettings.json and the string  should look like this
"DbConn": "Data Source=(your server name); Initial Catalog=CodesInventory; trusted_connection=yes;"
