# Restaurant-Automation-System 
we have to create a case study over the above topic
It should include 
1.SRS Document
2.SA/SD Document
3.UML-Based design
             *****
             The **Restaurant Automation System (RAS)** is designed to automate key operations of a restaurant, including order processing, billing, inventory management, and accounting. Below is a breakdown of the system's key features and functionalities based on the requirements provided:

### Core Features:
1. **Order Processing**:
   - Sales clerks input the item code and quantity sold for each order.
   - The system generates bills for customers once food items are ordered.
   - The system updates the sales and inventory based on sold items.

2. **Billing**:
   - The system automatically generates bills based on the items sold.
   - It maintains a history of all sales transactions for record-keeping and reporting purposes.

3. **Inventory Management**:
   - The system tracks ingredient usage when items are sold and adjusts the stock accordingly.
   - It monitors the stock levels of ingredients and automatically generates purchase orders when stock falls below a calculated threshold.
     - The threshold is calculated based on the average consumption of the ingredient over the past three days, ensuring at least two days of stock is maintained.
   - It manages restocking by recording purchase orders and invoice details for ingredients received.
   - Automatic check generation if sufficient cash balance is available when invoices are entered.

4. **Price Management**:
   - The system maintains the prices of all menu items.
   - Managers can modify prices, and the changes are reflected in billing and reporting.

5. **Supply Ordering**:
   - Daily automatic generation of purchase orders for ingredients that are below the stock threshold.

6. **Financial Management**:
   - Monthly sales receipt and expense reports can be generated upon request by the manager.
   - The system tracks cash balance and invoices to ensure accurate financial reporting and expense management.

7. **Menu Management**:
   - The system is capable of printing a menu card displaying all menu items and their respective prices.

### Reports & Analytics:
- **Sales Reports**: 
   - The system can generate sales reports for different items, providing insights into the most popular items and overall sales performance.
- **Inventory Reports**:
   - Reports on inventory levels, including ingredients that are running low, and purchase orders generated.
- **Financial Reports**:
   - Monthly reports detailing sales receipts and expenses to assist in accounting and financial decision-making.

### User Roles:
1. **Sales Clerk**:
   - Enters orders (item code, quantity sold).
   - Issues bills for customers.
   
2. **Manager**:
   - Can change item prices.
   - Can request reports (sales, expenses, inventory).
   - Oversees stock levels and purchase orders.

### Data Flow:
1. **Input**: 
   - Sales clerk inputs item code and quantity sold.
   - System automatically updates stock levels based on consumption.
   - Manager inputs price updates or generates reports.
   
2. **Processing**:
   - Bills are generated for customers.
   - Stock levels are recalculated based on sales and ingredient issuance.
   - Purchase orders are generated when stock falls below the threshold.
   - Threshold values are recalculated daily based on recent consumption data.
   
3. **Output**:
   - Bills for customers.
   - Purchase orders for suppliers.
   - Reports for sales, expenses, and inventory.
   - Printed menu card with updated prices.

