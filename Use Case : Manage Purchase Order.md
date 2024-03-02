# Purchase Order Management System

## Overview

The Purchase Order Management System is designed to facilitate the creation, viewing, updating, and deletion of purchase orders. The application utilizes Fiori elements and incorporates F4 helps for value assistance.

## Functional Requirements

### 1. Purchase Order Header (Master)

- Purchase Order ID (Primary Key, Auto-generated)
- Vendor ID (F4 help from Vendor Master)
- Purchase Date
- Delivery Date
- Status (Open, In Progress, Closed)

### 2. Purchase Order Line Item - Products (Child)

- Line Item ID (Primary Key, Auto-generated)
- Purchase Order ID (Foreign Key)
- Product ID (F4 help from Product Master)
- Quantity
- Price

### 3. Purchase Order Line Item - Services (Child)

- Line Item ID (Primary Key, Auto-generated)
- Purchase Order ID (Foreign Key)
- Service ID (F4 help from Service Master)
- Hours
- Rate

### 4. Vendor Master

- Vendor ID (Primary Key)
- Name
- Address
- Contact Details

### 5. Product Master

- Product ID (Primary Key)
- Description
- Price

### 6. Service Master

- Service ID (Primary Key)
- Description
- Rate

## Fiori Elements Object Page

The object page for a purchase order consists of four facets:

1. **Header Information:** Displays the header information of the purchase order.
2. **Product Line Items:** Presents a table of all product line items for the purchase order.
3. **Service Line Items:** Shows a table of all service line items for the purchase order.
4. **Vendor Information:** Provides detailed information about the vendor.
