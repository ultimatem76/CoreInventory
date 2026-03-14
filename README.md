

<h1>CoreInventory – Inventory Management System</h1>
<p align="center">
  <img src="ui/1.png" alt="Description of image"  width="1080" height="720" >
</p>

<p>
CoreInventory is a modular Inventory Management System (IMS) designed to digitize and streamline
stock operations within a business. It replaces manual registers, spreadsheets, and fragmented
tracking methods with a centralized, real-time inventory management application.
</p>

<p align="center">
  <img src="ui/2.png" alt="Description of image"  width="1080" height="720" >
</p>

<h3>Inventory Dashboard</h3>
<p>The dashboard provides a real-time overview of stock operations including:</p>

<ul>
<li>Total products in stock</li>
<li>Low stock / out-of-stock alerts</li>
<li>Pending receipts</li>
<li>Pending deliveries</li>
<li>Scheduled internal transfers</li>
</ul>
<p align="center">
  <img src="ui/3.png" alt="Description of image"  width="1080" height="720" >
</p>

<p><strong>Dynamic Filters</strong></p>
<ul>
<li>Document type (Receipts, Deliveries, Internal Transfers, Adjustments)</li>
<li>Status (Draft, Waiting, Ready, Done, Cancelled)</li>
<li>Warehouse or location</li>
<li>Product category</li>
</ul>

<p align="center">
  <img src="ui/4.png" alt="Description of image"  width="1080" height="720" >
</p>

<h2>System Modules</h2>

<h3>1. Product Management</h3>
<ul>
<li>Create and update products</li>
<li>Assign SKU / Product code</li>
<li>Define product categories</li>
<li>Set unit of measure</li>
<li>Add initial stock (optional)</li>
<li>View stock availability by location</li>
</ul>

<p align="center">
  <img src="ui/5.png" alt="Description of image"  width="1080" height="720" >
</p>

<h3>2. Receipts (Incoming Stock)</h3>

<p>Handles stock received from suppliers.</p>

<p><strong>Workflow</strong></p>
<ol>
<li>Create a receipt order</li>
<li>Add supplier and products</li>
<li>Enter quantity received</li>
<li>Validate receipt → stock increases automatically</li>
</ol>

<p align="center">
  <img src="ui/6.png" alt="Description of image"  width="1080" height="720" >
</p>

<p><strong>Example:</strong></p>
<p>Receive 50 units of Steel Rods → Stock +50</p>

<h3>3. Delivery Orders (Outgoing Stock)</h3>

<p><strong>Workflow</strong></p>
<ol>
<li>Pick items</li>
<li>Pack items</li>
<li>Validate delivery → stock decreases automatically</li>
</ol>

<p align="center">
  <img src="ui/7.png" alt="Description of image"  width="1080" height="720" >
</p>

<p><strong>Example:</strong></p>
<p>Sales order for 10 chairs → Stock -10</p>

<h3>4. Internal Transfers</h3>
<p>Move stock inside the organization.</p>

<ul>
<li>Main Warehouse → Production Floor</li>
<li>Rack A → Rack B</li>
<li>Warehouse 1 → Warehouse 2</li>
</ul>

<p>All movements are recorded in the stock ledger.</p>

<h3>5. Stock Adjustments</h3>

<p>Used to correct mismatches between system stock and physical counts.</p>

<ol>
<li>Select product and location</li>
<li>Enter counted quantity</li>
<li>System updates inventory and logs adjustment</li>
</ol>

<p><strong>Example:</strong></p>
<p>3 kg steel damaged → Stock -3</p>

<h2>Navigation Structure</h2>

<ul>
<li>Dashboard</li>
<li>Products</li>
<li>Operations
<ul>
<li>Receipts</li>
<li>Delivery Orders</li>
<li>Inventory Adjustments</li>
<li>Move History</li>
</ul>
</li>
<li>Settings
<ul>
<li>Warehouse Management</li>
</ul>
</li>
</ul>

<h3>Profile Menu</h3>
<ul>
<li>My Profile</li>
<li>Logout</li>
</ul>

<h2>Additional Features</h2>
<ul>
<li>Low stock alerts</li>
<li>Multi-warehouse support</li>
<li>SKU search</li>
<li>Smart filtering system</li>
<li>Stock movement ledger</li>
</ul>

<h2>Inventory Flow Example</h2>

<ol>
<li>
<strong>Receive Goods</strong><br>
Receive 100 kg steel → Stock +100
</li>

<li>
<strong>Internal Transfer</strong><br>
Move from Main Store → Production Rack (stock unchanged)
</li>

<li>
<strong>Delivery</strong><br>
Deliver 20 steel frames → Stock -20
</li>

<li>
<strong>Adjustment</strong><br>
3 kg steel damaged → Stock -3
</li>
</ol>

<p>All actions are logged in the inventory ledger.</p>

