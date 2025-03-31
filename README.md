# eBayInventoryPro

**eBayInventoryPro** is a lightweight web application designed to help eBay sellers track their active listings, manage inventory, and streamline item sales tracking. With easy import/export functionality and an intuitive interface, this app simplifies inventory management for eBay businesses.

\color{orange}no time to read all this crap? Just download the "inventoryv5.html" file above. open it in Chrome for the best experience.}$$


## Features

- **Add Inventory**: Automatically generate inventory numbers and add new items.
- **Update Quantities**: Easily update quantities directly in the inventory list.
- **Mark Items as Sold**: Keep track of sold items by updating their quantities.
- **Edit Item Descriptions**: Quickly modify the descriptions of your inventory items.
- **Delete Items**: Remove unwanted items from your inventory.
- **CSV Export/Import**: Export and import your inventory in CSV format for easy backup and restore.
- **Persistent Data**: Your inventory data is stored locally in your browser, ensuring it persists even after closing the app.

## How to Use

### Adding Inventory
1. Enter an inventory number (auto-increments).
2. Add a description for the item.
3. Click the "➕ Add" button to create a new item.

### Updating Inventory
1. Adjust quantities directly in the list.
2. Any changes made will be automatically saved.

### Marking Items as Sold
1. Click the "💵" icon to mark items as sold, decreasing the available quantity and increasing the sold quantity.

### Editing Items
1. Click the ✏️ icon next to an item to edit its description.

### Deleting Items
1. Click the ❌ icon to remove an item from the list.

### Exporting/Importing CSV
1. Export your inventory as a CSV file.
2. Import a CSV file to restore your inventory, including descriptions, quantities, and sold quantities.

### Clearing Data
1. Click the "Clear Data" button to erase all inventory data from the app.

## How to Download Active Listings from eBay and Import Them

1. **Download Your eBay Active Listings**:
   - Go to your eBay Seller Hub.
   - Click on "Reports" in the navigation menu.
   - Under "Download Report," select:
     - **Source**: Listings
     - **Type**: All Active Listings
   - Click "Download" and save the CSV file to your computer.

2. **Prepare Your CSV for Import**:
   - Open the downloaded CSV file.
   - Ensure it includes the following columns:
     - Item number (SKU)
     - Title (Description)
     - Quantity Available
   - Adjust the format if necessary to match the app’s required fields.

3. **Import to the Inventory Tracker App**:
   - In the app, click the "🔺 Restore" button to begin the import process.
   - Select the downloaded CSV file.
   - The app will parse the file and add each listing to your inventory.

4. **Review Your Inventory**:
   - Once imported, your eBay listings will appear in the app.
   - Edit descriptions, update quantities, and manage your inventory directly within the app.

## Installation

To get started with **eBayInventoryPro**:

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/eBayInventoryPro.git
