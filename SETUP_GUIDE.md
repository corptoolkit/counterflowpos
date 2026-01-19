# CounterFlowPOS - Setup Guide

This guide will help you configure CounterFlowPOS for your restaurant. Follow these steps in order for the best setup experience.

## Table of Contents

1. [Initial Admin Setup](#initial-admin-setup)
2. [Company Profile Setup](#company-profile-setup)
3. [Employee Setup](#employee-setup)
4. [Catalog Setup](#catalog-setup)
5. [Discount Codes Setup](#discount-codes-setup)
6. [Menu Configuration](#menu-configuration)

---

## Initial Admin Setup

### Setting Up Admin Access

1. **First Launch**:
   - Launch CounterFlowPOS
   - You'll see the Login window

2. **Set Admin Code**:
   - The system will prompt you to set an admin code on first launch
   - Enter a secure code (e.g., "ADMIN123" or "RESTAURANT2024")
   - **Important**: Remember this code - you'll need it to access admin features
   - Click "OK" to save

3. **Login as Admin**:
   - Select "Admin" radio button
   - Enter your admin code
   - Click "Login"

---

## Company Profile Setup

### Configure Business Information

1. **Access Business Profile**:
   - From Admin Dashboard, click **Settings** → **Business Profile**

2. **Enter Business Information**:
   - **Business Name*** (Required): Enter your restaurant name
   - **Phone Number**: Enter your business phone number
   - **Email ID**: Enter your business email address
   - **Website URL**: Enter your website URL (if applicable)
   - **Address**: Enter your business address

3. **Save Profile**:
   - Click "Edit Business Profile" button
   - Fill in all fields
   - Click "Save"
   - This information will appear on all printed receipts

**Note**: Business Name is required. All other fields are optional but recommended for professional receipts.

---

## Employee Setup

### Adding Employees

1. **Navigate to Employee Management**:
   - From Admin Dashboard, click **Employees** → **Employee Management**

2. **Add New Employee**:
   - Click "Add Employee" button
   - Enter the following:
     - **Employee ID**: Auto-generated (or enter custom ID)
     - **Employee Name***: Full name of the employee
     - **Employee Code***: Unique code for login (e.g., "EMP001", "JOHN123")
   - Click "Save"

3. **Edit Employee**:
   - Select an employee from the list
   - Click "Edit Employee"
   - Modify information as needed
   - Click "Save"

4. **Delete Employee**:
   - Select an employee from the list
   - Click "Delete Employee"
   - Confirm deletion

**Best Practices**:
- Use consistent employee codes (e.g., EMP001, EMP002)
- Employee codes should be easy to remember
- Keep employee codes unique - duplicates are not allowed

---

## Catalog Setup

The catalog consists of three main components: Categories, Modifier Groups, and Products. Set them up in this order for best results.

### Step 1: Create Categories

1. **Navigate to Catalog Management**:
   - From Admin Dashboard, click **Catalog** → **Catalog Management**
   - Select the "Categories" tab

2. **Add Category**:
   - Click "Add Category" button
   - Enter:
     - **Name***: Category name (e.g., "Pizzas", "Drinks", "Sides")
     - **Description**: Optional description
     - **Sort Order**: Number for display order (lower numbers appear first)
     - **Tax Rate**: Tax percentage (e.g., 7.5 for 7.5%)
   - Click "Save"

3. **Edit/Delete Categories**:
   - Select a category and click "Edit Category" or "Delete Category"

### Step 2: Create Modifier Groups

1. **Select Modifier Groups Tab**:
   - In Catalog Management, click "Modifier Groups" tab

2. **Add Modifier Group**:
   - Click "Add Modifier Group" button
   - Enter:
     - **Name***: Group name (e.g., "Pizza Size", "Toppings", "Crust Type")
     - **Description**: Optional description
     - **Is Required**: Check if customers must select an option
     - **Selection Type**:
       - **Single**: Customer can select only one option (use RadioButtons)
       - **Multiple**: Customer can select multiple options (use CheckBoxes)
   - Click "Save"

3. **Add Modifier Options**:
   - After creating a modifier group, you can add options:
     - Click "Add Option" in the modifier group dialog
     - Enter:
       - **Name***: Option name (e.g., "Small", "Medium", "Large")
       - **Description**: Optional description
       - **Price Adjustment**: Additional cost (can be negative for discounts)
       - **Sort Order**: Display order
       - **Is Active**: Check to enable this option
     - Click "Save"

**Example Modifier Groups**:
- **Pizza Size** (Required, Single): Small (+$0.00), Medium (+$3.00), Large (+$6.00)
- **Toppings** (Optional, Multiple): Pepperoni (+$2.50), Mushrooms (+$1.50), etc.
- **Crust Type** (Required, Single): Thin Crust (+$0.00), Thick Crust (+$2.00)

### Step 3: Create Products

1. **Select Products Tab**:
   - In Catalog Management, click "Products" tab

2. **Add Product**:
   - Click "Add Product" button
   - Enter:
     - **Name***: Product name (e.g., "Cheese Pizza", "Coca Cola")
     - **Category***: Select from dropdown
     - **Description**: Product description
     - **Short Description**: Brief description
     - **Long Description**: Detailed description
     - **Image URL**: Link to product image (optional)
     - **Base Price***: Base price of the product
     - **Is Active**: Check to make product available
     - **Is Available**: Check if product is in stock

3. **Assign Modifier Groups**:
   - In the product dialog, scroll to "Modifier Groups"
   - Check the boxes for modifier groups that apply to this product
   - Example: For "Cheese Pizza", check "Pizza Size" and "Crust Type"

4. **Save Product**:
   - Click "Save" to create the product

**Product Setup Tips**:
- Base price should be the price without modifiers
- Modifier groups allow customization (size, toppings, etc.)
- Required modifier groups must have a selection before adding to order
- Inactive products won't appear in POS

---

## Discount Codes Setup

### Creating Discount Codes

1. **Navigate to Discount Management**:
   - From Admin Dashboard, click **Discounts** → **Discount Management**

2. **Add Discount Code**:
   - Click "Add Discount" button
   - Enter:
     - **Code***: Discount code (e.g., "SAVE10", "WELCOME20")
     - **Description**: What the discount is for
     - **Type***:
       - **Percentage**: Discount as percentage (e.g., 10 for 10% off)
       - **Fixed Amount**: Fixed dollar amount off (e.g., 5 for $5 off)
     - **Value***: Discount amount (percentage or dollar amount)
     - **Minimum Order Total**: Minimum order amount required (optional)
     - **Valid From**: Start date (optional)
     - **Valid To**: End date (optional)
     - **Max Uses**: Maximum number of times code can be used (optional)
     - **Active**: Check to enable the discount
   - Click "Save"

3. **Edit/Delete Discounts**:
   - Select a discount and click "Edit Discount" or "Delete Discount"

**Discount Examples**:
- **10% Off**: Type=Percentage, Value=10
- **$5 Off**: Type=Fixed Amount, Value=5
- **20% Off Orders Over $50**: Type=Percentage, Value=20, Min Order=$50

---

## Menu Configuration

### Creating Menus

1. **Navigate to Menu Management**:
   - From Admin Dashboard, click **Catalog** → **Menu Management**

2. **Create Menu**:
   - Click "Add Menu" button
   - Enter:
     - **Name***: Menu name (e.g., "Main Menu", "Lunch Menu")
     - **Description**: Menu description
     - **Is Active**: Check to enable menu
   - Click "Save"

3. **Add Categories to Menu**:
   - Select a menu from the list
   - Click "Add Category" button
   - Select a category from the dropdown
   - Click "Add"

4. **Add Products to Menu Categories**:
   - Select a category in the menu
   - Click "Add Product" button
   - Select a product from the dropdown
   - Enter:
     - **Price**: Menu-specific price (overrides base price)
     - **Sort Order**: Display order
   - Click "Add"

5. **Remove Items**:
   - Select a product or category
   - Click "Remove" button

---

## Quick Setup Checklist

Use this checklist to ensure complete setup:

- [ ] Set admin code
- [ ] Configure business profile (name, phone, address, email, website)
- [ ] Add at least one employee
- [ ] Create product categories
- [ ] Create modifier groups with options
- [ ] Create products and assign modifier groups
- [ ] Create at least one menu (optional)
- [ ] Set up discount codes (optional)
- [ ] Test employee login
- [ ] Test POS mode with a sample order
- [ ] Print a test receipt

---

## Tips for Success

1. **Start Simple**: Begin with a few products and expand gradually
2. **Use Consistent Naming**: Follow a naming convention for codes and IDs
3. **Test Thoroughly**: Test each feature after setup
4. **Backup Data**: The data folder is in `%AppData%\RestaurantScheduler\` - back it up regularly
5. **Document Your Setup**: Keep notes on your product codes and employee codes

---

## Common Setup Scenarios

### Pizza Restaurant Example

1. **Categories**: Pizzas, Sides, Drinks, Desserts
2. **Modifier Groups**:
   - Pizza Size (Required, Single): Small, Medium, Large
   - Crust Type (Required, Single): Thin, Thick, Stuffed
   - Toppings (Optional, Multiple): Pepperoni, Mushrooms, etc.
3. **Products**: Cheese Pizza, Pepperoni Pizza, etc.
4. **Assign**: Each pizza product gets "Pizza Size" and "Crust Type" modifier groups

### Coffee Shop Example

1. **Categories**: Beverages, Pastries, Sandwiches
2. **Modifier Groups**:
   - Size (Required, Single): Small, Medium, Large
   - Milk Type (Optional, Single): Whole, Skim, Almond
   - Add-ons (Optional, Multiple): Extra Shot, Whipped Cream
3. **Products**: Espresso, Latte, Cappuccino, etc.

---

## Next Steps

After completing setup:
1. Review the **User Guide** for detailed feature usage
2. Train your employees on the system
3. Start processing orders!

