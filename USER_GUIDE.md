# CounterFlowPOS - User Guide

Complete guide to using CounterFlowPOS for daily restaurant operations.

## Table of Contents

1. [Login and Navigation](#login-and-navigation)
2. [Admin Features](#admin-features)
3. [Employee Features](#employee-features)
4. [Point of Sale (POS)](#point-of-sale-pos)
5. [Order Management](#order-management)
6. [Reports and Exports](#reports-and-exports)
7. [Tips and Best Practices](#tips-and-best-practices)

---

## Login and Navigation

### Login Process

1. **Launch Application**:
   - Double-click `RestaurantScheduler.exe`
   - Login window appears

2. **Admin Login**:
   - Select "Admin" radio button
   - Enter admin code
   - Click "Login"
   - Access to all features

3. **Employee Login**:
   - Select "Employee" radio button
   - Enter employee code (assigned by admin)
   - Click "Login"
   - Access to employee features

### Navigation

- **Menu Bar**: Top of screen with main sections
- **Content Area**: Main workspace below menu
- **Logout**: Click "Logout" in menu to return to login screen

---

## Admin Features

### Admin Dashboard Overview

The Admin Dashboard provides access to:
- **POS**: Point of Sale system
- **Catalog**: Product and menu management
- **Employees**: Staff management and scheduling
- **Orders**: Order history and sales reports
- **Discounts**: Discount code management
- **Settings**: Business profile configuration

### Employee Management

**Location**: Employees → Employee Management

**Add Employee**:
1. Click "Add Employee"
2. Enter Employee Name and Employee Code
3. Click "Save"

**Edit Employee**:
1. Select employee from list
2. Click "Edit Employee"
3. Modify information
4. Click "Save"

**Delete Employee**:
1. Select employee
2. Click "Delete Employee"
3. Confirm deletion

### Shift Scheduling

**Location**: Employees → Shift Scheduling

**Create Weekly Schedule**:
1. Use date picker to select week
2. For each employee and day:
   - Check "Scheduled" checkbox
   - Enter Start Time (HH:mm format, e.g., "09:00")
   - Enter End Time (HH:mm format, e.g., "17:00")
3. Click "Save Week Schedule"

**Navigate Weeks**:
- Use "Previous Week" and "Next Week" buttons
- Or use date picker to jump to specific week

**Delete Week Schedule**:
- Select week
- Click "Delete Week Schedule"
- Confirm deletion

**Export Schedule**:
- Click "Export Schedule to CSV" in Employees menu
- Select week to export
- Choose save location
- CSV file contains all employee schedules

### Task Management

**Location**: Employees → Task Management

**Assign Task**:
1. Click "Assign Task"
2. Select:
   - Employee
   - Task Type (Kitchen, Service, Cleaning)
   - Description
3. Click "Save"

**View Task Details**:
- Select task from list
- Click "View Details"
- See task information and status

**Verify Task**:
- Select completed task
- Click "Verify Task" to mark as verified

**Filter Tasks**:
- Use status filter dropdown
- View: All, Assigned, In Progress, Completed, Verified

### Catalog Management

**Location**: Catalog → Catalog Management

#### Categories Tab

**Add Category**:
1. Click "Add Category"
2. Enter Name, Description, Sort Order, Tax Rate
3. Click "Save"

#### Modifier Groups Tab

**Add Modifier Group**:
1. Click "Add Modifier Group"
2. Enter Name, Description
3. Set Is Required (if customers must select)
4. Set Selection Type (Single or Multiple)
5. Click "Save"

**Add Modifier Options**:
1. In modifier group dialog, click "Add Option"
2. Enter Name, Description, Price Adjustment, Sort Order
3. Click "Save"

#### Products Tab

**Add Product**:
1. Click "Add Product"
2. Enter product details
3. Select Category
4. Check modifier groups that apply
5. Click "Save"

**Edit Product**:
- Select product
- Click "Edit Product"
- Modify and save

### Menu Management

**Location**: Catalog → Menu Management

**Create Menu**:
1. Click "Add Menu"
2. Enter Name and Description
3. Click "Save"

**Add Categories to Menu**:
1. Select menu
2. Click "Add Category"
3. Select category from dropdown
4. Click "Add"

**Add Products to Menu**:
1. Select menu category
2. Click "Add Product"
3. Select product
4. Enter menu-specific price and sort order
5. Click "Add"

### Ingredients Management

**Location**: Catalog → Ingredients Management

**Add Ingredient**:
1. Click "Add Ingredient"
2. Enter:
   - Item ID (internal identifier)
   - Name
   - Quantity On Hand
   - Reorder Quantity
   - Unit (e.g., "lbs", "oz", "units")
3. Click "Save"

**Adjust Quantity**:
1. Select ingredient
2. Click "Checkout" or "Restock"
3. Enter quantity change
4. Add notes (optional)
5. Click "Save"

**Generate Purchase Order**:
1. Click "Generate Purchase Order Report"
2. View items that need reordering
3. Export to CSV if needed

### Discount Management

**Location**: Discounts → Discount Management

**Create Discount**:
1. Click "Add Discount"
2. Enter Code, Description, Type, Value
3. Set optional restrictions (min order, dates, max uses)
4. Click "Save"

**Edit/Delete Discount**:
- Select discount
- Click "Edit Discount" or "Delete Discount"

### Business Profile

**Location**: Settings → Business Profile

**Edit Profile**:
1. Click "Edit Business Profile"
2. Update:
   - Business Name (required)
   - Phone Number
   - Email ID
   - Website URL
   - Address
3. Click "Save"
4. Information appears on all receipts

### Order Management

**Location**: Orders → Order Management

**View Orders**:
- Orders displayed in table
- Shows: Order #, Customer, Type, Source, Status, Total, Date

**Filter by Date**:
1. Select Start Date and End Date
2. Orders automatically filter
3. Click "Reset to Current Month" to reset

**View Order Details**:
1. Select order
2. Click "View Details"
3. See complete order information
4. Click "Print Order" to print receipt

**Edit Order**:
1. Select order (must not be "Completed")
2. Click "Edit Order"
3. Change Order Status
4. Click "Save"

**Delete Order**:
1. Select order
2. Click "Delete Order"
3. Confirm deletion

### Sales Report

**Location**: Orders → Sales Report

**Generate Report**:
1. Select Start Date and End Date
2. Click "Generate Report"
3. View sales data in table
4. See summary totals at bottom

**Export to CSV**:
1. Generate report first
2. Click "Export to CSV"
3. Choose save location
4. CSV contains all order details

**Print Report**:
1. Generate report
2. Click "Print Report"
3. Select printer
4. Print sales report

### Export Monthly Hours

**Location**: Employees → Export Monthly Hours

1. Select month and year
2. Click "Export"
3. Choose save location
4. CSV file contains employee hours grouped by month

---

## Employee Features

### Employee Dashboard Overview

Employees have access to:
- **Clock In/Out**: Time tracking
- **My Tasks**: View and complete assigned tasks
- **Menu Management**: View menus
- **Ingredients Management**: View inventory
- **POS Mode**: Process orders

### Clock In/Out

**Location**: Employee Dashboard → Clock In/Out

**Clock In**:
1. View your weekly schedule
2. Click "Clock In" button
3. System validates you're within valid shift time (allows 15 minutes early)
4. Clock-in time recorded

**Clock Out**:
1. Click "Clock Out" button
2. Clock-out time recorded
3. Hours calculated automatically

**View Schedule**:
- Weekly schedule displayed
- Shows all your shifts for the week
- Displays start and end times

**Note**: You can only clock in during valid shift times (up to 15 minutes before shift starts)

### My Tasks

**Location**: Employee Dashboard → My Tasks

**View Tasks**:
- See all tasks assigned to you
- Filter by status: All, Assigned, In Progress, Completed

**Start Task**:
1. Select task
2. Click "Start Task"
3. Status changes to "In Progress"

**Complete Task**:
1. Select task
2. Click "Complete Task"
3. Add comments (optional)
4. Status changes to "Completed"

**View Task Details**:
- Select task
- Click "View Details"
- See full task information

### POS Mode (Employee Access)

Employees can access POS mode to process orders. See [Point of Sale (POS)](#point-of-sale-pos) section below.

---

## Point of Sale (POS)

### Accessing POS Mode

**Admin**: POS → POS Mode
**Employee**: Employee Dashboard → POS Mode

### Creating an Order

1. **Select Category**:
   - Left panel: Click a category (e.g., "Pizzas", "Drinks")
   - Products in that category appear below

2. **Select Product**:
   - Click a product from the list
   - Product details appear in center panel

3. **Customize Product**:
   - **Required Modifiers**: Must select one option (RadioButtons)
   - **Optional Modifiers**: Can select multiple (CheckBoxes)
   - Price updates automatically as you select modifiers

4. **Add to Order**:
   - Click "Add to Order" button
   - Item appears in right panel order summary

5. **Repeat**: Add more items as needed

### Managing Order

**View Order Items**:
- Right panel shows all items
- Expand item to see modifiers
- Quantity, price, and total displayed

**Remove Item**:
- Click "Remove" button next to item
- Item removed from order

**Clear Entire Order**:
- Click "Clear Order" button
- Confirm action
- All items removed

### Customer Selection (Optional)

1. **Select Existing Customer**:
   - Click "Select Customer" button
   - Search by name, phone, or email
   - Select customer from list
   - Customer name appears below buttons

2. **Add New Customer**:
   - Click "New Customer" button
   - Enter: Name (required), Phone, Email, Address
   - Click "Save"
   - Customer automatically selected

### Applying Discount

1. **Enter Discount Code**:
   - Type discount code in "Discount Code" field
   - Click "Apply" button

2. **View Discount**:
   - If valid, discount appears in order summary
   - Discount amount shown in green
   - Message confirms discount applied

3. **Invalid Code**:
   - Error message appears
   - Code must be active, within date range, and meet minimum order

### Completing Order

1. **Review Order**:
   - Check all items and quantities
   - Verify customer (if selected)
   - Confirm discount (if applied)

2. **Complete Order**:
   - Click "Complete Order" button
   - Order saved to system
   - Order number generated

3. **Print Receipt**:
   - Dialog asks if you want to print
   - Click "Yes" to print
   - Select printer
   - Receipt prints with business info and order details

4. **Order Cleared**:
   - Order items cleared
   - Ready for next order

### Print Receipt (After Order)

- Click "Print Receipt" button (if order completed)
- Select printer
- Receipt includes:
  - Business name and contact info
  - Order number and date
  - Customer information (if attached)
  - All items with modifiers
  - Subtotal, tax, discount, total

---

## Order Management

### Viewing Orders

**Location**: Orders → Order Management

**Order List**:
- All orders displayed in table
- Columns: Order #, Customer, Type, Source, Status, Total, Date
- Status color-coded:
  - Blue: New
  - Orange: Pending
  - Purple: In Kitchen
  - Green: Ready
  - Gray: Completed
  - Red: Cancelled

**Date Filtering**:
- Select Start Date and End Date
- Orders automatically filter
- Click "Reset to Current Month" to reset

**Refresh**:
- Click "Refresh" button to reload orders

### Order Details

**View Details**:
1. Select order from list
2. Click "View Details"
3. See:
   - Order number and status
   - Customer information (name and phone)
   - All line items with modifiers
   - Financial summary (subtotal, tax, discount, total)
4. Click "Print Order" to print receipt
5. Click "Close" when done

### Edit Order

**Change Status**:
1. Select order (cannot be "Completed")
2. Click "Edit Order"
3. Select new status from dropdown
4. Click "Save"
5. Order updated

**Note**: Only order status can be edited. To modify items, delete and recreate order.

### Delete Order

1. Select order
2. Click "Delete Order"
3. Confirm deletion
4. Order permanently removed

---

## Reports and Exports

### Sales Report

**Location**: Orders → Sales Report

**Generate Report**:
1. Select date range (Start Date and End Date)
2. Click "Generate Report"
3. View:
   - All orders in date range
   - Summary totals (orders, revenue, tax, discounts)

**Export to CSV**:
1. Generate report first
2. Click "Export to CSV"
3. Choose save location
4. CSV file contains detailed order data

**Print Report**:
1. Generate report
2. Click "Print Report"
3. Select printer
4. Print formatted sales report

### Export Schedule

**Location**: Employees → Export Schedule to CSV

1. Select week to export
2. Click "Export"
3. Choose save location
4. CSV contains all employee schedules for selected week

### Export Monthly Hours

**Location**: Employees → Export Monthly Hours

1. Select month and year
2. Click "Export"
3. Choose save location
4. CSV contains employee hours grouped by month
5. Useful for payroll processing

---

## Tips and Best Practices

### Daily Operations

1. **Start of Day**:
   - Employees clock in
   - Check ingredient inventory
   - Review daily tasks

2. **During Service**:
   - Use POS mode for all orders
   - Attach customers for better tracking
   - Apply discounts when applicable
   - Print receipts for customers

3. **End of Day**:
   - Employees clock out
   - Review completed tasks
   - Check sales report
   - Verify all orders processed

### Best Practices

1. **Customer Management**:
   - Always select customer when possible
   - Customer info helps with order tracking
   - Phone numbers useful for order inquiries

2. **Product Setup**:
   - Use clear, descriptive names
   - Set appropriate base prices
   - Assign relevant modifier groups
   - Keep products active/inactive as needed

3. **Order Processing**:
   - Verify items before completing order
   - Always print receipts
   - Check customer information
   - Apply discounts correctly

4. **Inventory Management**:
   - Regularly update ingredient quantities
   - Set appropriate reorder levels
   - Generate purchase orders when needed
   - Use checkout/restock features

5. **Task Management**:
   - Assign tasks with clear descriptions
   - Employees should add comments when completing
   - Verify completed tasks regularly
   - Use task status to track progress

### Keyboard Shortcuts

- **Tab**: Move between fields
- **Enter**: Submit forms, complete actions
- **Escape**: Cancel dialogs
- **Ctrl+S**: Save (in some dialogs)

### Troubleshooting

**Order Not Saving**:
- Check if order has items
- Verify all required modifiers selected
- Ensure customer selected (if required)

**Cannot Clock In**:
- Check if within valid shift time
- Verify schedule is set for that day
- System allows 15 minutes early clock-in

**Product Not Appearing**:
- Check if product is "Active"
- Verify product is in selected category
- Ensure product is "Available"

**Discount Not Working**:
- Verify discount code is active
- Check date range (if set)
- Ensure order meets minimum total
- Check if max uses exceeded

---

## Support and Help

### Getting Help

1. **Review Documentation**:
   - Installation Guide
   - Setup Guide
   - This User Guide

2. **Check Data**:
   - Verify data files exist in `%AppData%\RestaurantScheduler\`
   - Ensure files are not corrupted

3. **Common Issues**:
   - Application won't start: Check .NET Runtime
   - Data not saving: Check file permissions
   - Slow performance: Close other applications

### Data Backup

**Backup Location**: `%AppData%\RestaurantScheduler\`

**Backup Regularly**:
- Copy entire folder to backup location
- Backup before major updates
- Keep multiple backup copies

**Restore Backup**:
- Stop application
- Replace `%AppData%\RestaurantScheduler\` folder with backup
- Restart application

---

## Quick Reference

### Admin Quick Actions

- **Add Employee**: Employees → Employee Management → Add Employee
- **Create Schedule**: Employees → Shift Scheduling → Select Week → Enter Times → Save
- **Add Product**: Catalog → Catalog Management → Products → Add Product
- **View Orders**: Orders → Order Management
- **Sales Report**: Orders → Sales Report → Generate Report
- **Edit Business Profile**: Settings → Business Profile → Edit

### Employee Quick Actions

- **Clock In**: Employee Dashboard → Clock In/Out → Clock In
- **View Tasks**: Employee Dashboard → My Tasks
- **Process Order**: Employee Dashboard → POS Mode
- **Clock Out**: Employee Dashboard → Clock In/Out → Clock Out

### POS Quick Actions

1. Select Category → Select Product
2. Customize with modifiers
3. Add to Order
4. (Optional) Select Customer
5. (Optional) Apply Discount
6. Complete Order
7. Print Receipt

---

This completes the User Guide. Refer to specific sections as needed during daily operations.

