# [Finals-Lab-Task-5](https://github.com/user-attachments/files/20139307/Finals.-.LabTask.5.-.Garcia.docx)
- This portfolio showcases the application of SQL views, stored procedures, and functions for effective database management and data manipulation. It includes tasks like filtering data through views, updating records via stored procedures, and retrieving information using functions.

## Step-by-Step Process:
1. **Setup MySQL Workbench:**

   * Open XAMPP and start the MySQL server.
   * Connect MySQL Workbench to the server.
   * Execute practice queries using the `democodes.sql` file.

2. **Use Inventory Database:**

   * Open the `inventory.sql` file to begin the tasks.

3. **Create Views:**

   * Create a view to display vendor information and products with in-date from 2002 onward.
   * Create a view for products with prices between 100-150.
   * Create a view to compute the total price for products sold by specific vendors.

4. **Create Stored Procedure:**

   * Create a stored procedure that updates the vendor name from 'Bryson, Inc.' to 'Bryson and Co'.

5. **Create Function:**

   * Create a function that takes vendor code and state as parameters to display product details.

6. **Execute and Document:**

   * Execute the SQL statements and capture screenshots of the commands and outputs.

# Screenshots of Codes and Outputs:
### 1. CREATE A VIEW that will display the vendors_code, vendors name, product
description p_indate, of all products with p_indate from 2002 onwards
- ![Image](https://github.com/user-attachments/assets/4136c7db-91b0-4f84-93b8-197eb55ced9d)
## Output
- ![Image](https://github.com/user-attachments/assets/0264e6e1-fb41-4c6f-8aab-231b32218170)

### 2. CREATE a VIEW that will display all products whose price range is between 100-150
- ![Image](https://github.com/user-attachments/assets/45e97ad5-3ef7-4a9c-8c4d-32e1f63191c4)
## Output
- ![Image](https://github.com/user-attachments/assets/9c5dac0e-ddb8-4586-857e-4d703d087d84)

### 3. Create a VIEW that will COMPUTE for the (TOTAL_PRICE) of ALL
PRODUCTS by getting the (P_ONHAND x P_PRICE) Sold by vendors with
the following v_code (21344, 23119 and 24288)
- ![Image](https://github.com/user-attachments/assets/0923620f-ba96-4f03-bb4b-dcd85673ace3)
## Output
- ![Image](https://github.com/user-attachments/assets/37046b80-fa26-4884-9b4b-d7e6fb620f50)

### 4. CREATE a STORED PROCEDURE that WILL take a SINGLE PARAMETER and
UPDATED the Name of Vendor ‘Bryson,Inc.’ to ‘Bryson and Co’.
- ![Image](https://github.com/user-attachments/assets/6209dc5e-85f7-4741-80ca-81eefb9d2da5)
## Output
- ![Image](https://github.com/user-attachments/assets/6201518f-ad89-4703-ad6f-b4066a4dcd93)

### 5. CREATE A Function that will take 2 parameters(v_code and
v_state) and display All the product description and price based on
the parameters passed to the function
- ![Image](https://github.com/user-attachments/assets/1c46f46d-5619-4495-958e-29614641a985)
## Output
- ![Image](https://github.com/user-attachments/assets/2c7694a6-f81c-4e8e-93af-60bacf54c379)
