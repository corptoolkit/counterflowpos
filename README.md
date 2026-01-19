# CounterFlowPos Lite
CounterFlowPOS Lite is a standalone Windows 10 or 11 POS &amp; Order management Application, handles Complex Menus, Shift Scheduling &amp; ClockIn/Clockout, Ingredients and Recipe Tracking . Just download the zip installer, register and setup! For a limited time it can be used Free.


# CounterFlowPOS Lite- Installation Guide

## System Requirements

- **Operating System**: Windows 10 or later
- **RAM**: Minimum 4GB (8GB recommended)
- **Disk Space**: 200MB free space
- **Display**: 1024x768 minimum resolution
- **Administrator Rights**: Required for installation

## Installation Steps

### One-Click MSI Installation

CounterFlowPOS uses a simple one-click MSI installer that handles all setup automatically, including .NET Runtime dependencies.

#### Step 1: Run the Installer

1. **Locate the Installer**:
   - locate the EULA.md file first and Agree to the End User license Agreement (EULA) first
   - Only if you agree move forward and Find the `setup.exe`  file
   - This is the installation package

3. **Start Installation**:
   - Double-click the Setup file
   - Windows may prompt for administrator permissions - click "Yes"

4. **Installation Wizard**:
   - The installation wizard will appear
   - Click "Next" to begin
   - Choose installation location (default is recommended)
   - Click "Install"

5. **Automatic Setup**:
   - The installer will automatically:
     - Install .NET 8.0 Desktop Runtime (if not already installed)
     - Install CounterFlowPOS application files
     - Create necessary shortcuts
     - Set up application registry entries

6. **Complete Installation**:
   - Wait for the installation to complete (usually 1-2 minutes)
   - Click "Finish" when done

#### Step 2: Launch Application

1. **From Start Menu**:
   - Click Windows Start button
   - Search for "CounterFlowPOS Lite - POS - Shift Management - Complex Menus, Ingredient, Recipes, Task" 
   - Click the application icon

2. **First Launch**:
   
   - The system automatically creates:
     - Data storage folder in `%AppData%\RestaurantScheduler\`
     - Default admin code (admin123)

#### Step 3: Initial Configuration

1. Accept the End User Licensing Agreement (EULA) and then Start the application again from windows Start menu.
2. Goto Counterflowpos.com and register to get the activation key.
3. Double-click the "CounterFlowPOS Lite" menu again to launch the application and use your emailid and the activation key
4. Double-click the "CounterFlowPOS Lite" menu again

5. **Login**:
   - Select "Admin" radio button
   - Enter your admin code
   - Click "Login"

## Data Storage

All application data is stored locally on your computer in:
```
%AppData%\RestaurantScheduler\
```

### Uninstallation

To uninstall CounterFlowPOS:

1. **Using Windows Settings**:
   - Open Windows Settings (Windows Key + I)
   - Go to "Apps" → "Apps & features"
   - Search for "CounterFlowPOS Lite"
   - Click on it and select "Uninstall"
   - Follow the uninstallation wizard

2. **Using Control Panel**:
   - Open Control Panel → Programs and Features
   - Find "CounterFlowPOS Lite"
   - Click "Uninstall"
   - Follow the prompts

3. **Delete Data (Optional)**:
   - After uninstallation, if you want to remove all data:
   - Navigate to: `%AppData%\RestaurantScheduler\`
   - Delete the entire folder
   - **Warning**: This will permanently delete all your data (orders, employees, products, etc.)

4. **Keep .NET Runtime**:
   - The uninstaller will NOT remove .NET 8.0 Runtime
   - This is intentional - other applications may need it
   - Only uninstall .NET Runtime manually if you're sure no other applications need it



After installation:
1. Review the **Setup Guide** to configure your business. Add the Business Profile, Add staff logins and schedule, Add Product Catalog (Categories, Modifier Groups, Products), Add Ingredients Inventory, Recipes
2. Read the **User Guide** to learn how to use the application
3. Set up your employees, products, and business profile
4. Start using CounterFlowPOS Lite!

