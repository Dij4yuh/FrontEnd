# 🌐 Base URL
# Base Url Frontend: https://front-end-phi-silk-29.vercel.app/
# Base Url Backend: https://inventory-store-vzin.onrender.com/


## 📊 Products API

| Method | Endpoint              | Description          | Status Codes |
|--------|-----------------------|----------------------|-------------|
| GET    | /api/products         | Get all products     | 200, 500    |
| GET    | /api/products/:id     | Get single product   | 200, 404    |
| POST   | /api/products         | Create new product   | 201, 400    |
| PUT    | /api/products/:id     | Update product       | 200, 404    |
| DELETE | /api/products/:id     | Delete product       | 204, 404    |

## 🚚 Suppliers API

| Method | Endpoint               | Description               | Request Body           | Response                  |
|--------|------------------------|---------------------------|-----------------------|---------------------------|
| GET    | /api/suppliers         | Get all suppliers         | -                     | Array of supplier objects |
| GET    | /api/suppliers/:id     | Get single supplier by ID | -                     | Single supplier object    |
| POST   | /api/suppliers         | Create new supplier       | { name, contact }     | Created supplier object   |
| PUT    | /api/suppliers/:id     | Update supplier by ID     | { name?, contact? }   | Updated supplier object   |
| DELETE | /api/suppliers/:id     | Delete supplier by ID     | -                     | 204 No Content            |

## 📋 Orders API

| Method | Endpoint           | Description             | Request Body                     | Response                |
|--------|------------------|-------------------------|---------------------------------|------------------------|
| GET    | /api/orders       | Get all orders          | -                               | Array of order objects  |
| GET    | /api/orders/:id   | Get single order by ID  | -                               | Single order object     |
| POST   | /api/orders       | Create new order        | { supplierId, items[], status? } | Created order object    |
| PUT    | /api/orders/:id   | Update order by ID      | { supplierId?, items[]?, status? } | Updated order object    |
| DELETE | /api/orders/:id   | Delete order by ID      | -                               | -                       |

# 🎯 Core Features

# 📦 Product Management

✅ CRUD Operations - Create, Read, Update, Delete products
✅ Stock Tracking - Real-time inventory with low-stock alerts (<20 units)
✅ SKU & Pricing - Product identifiers and price management

# 🚚 Supplier Management

✅ Supplier Directory - Store and manage supplier contact info
✅ Supplier-Product Link - Relate suppliers to products

# 🔄 Data Management
✅ Real-time Updates - Changes reflect immediately
✅ In-memory Storage - No database needed for demo
✅ Form Validation - Prevents invalid data entry

# 🎨 User Interface
✅ Responsive Design - Works on mobile & desktop
✅ Clean Dashboard - Separate sections for Products/Suppliers/Orders
✅ Visual Feedback - Success/error alerts and loading states

# 📸 Screenshot frontend
<img width="1222" height="953" alt="image" src="https://github.com/user-attachments/assets/ca55fa1c-129b-41c6-9017-409994bdf959" />

<img width="1238" height="965" alt="image" src="https://github.com/user-attachments/assets/b548bda7-ed8e-4859-b6af-7f6db386503c" />

<img width="1212" height="948" alt="image" src="https://github.com/user-attachments/assets/d908b0cf-a7f3-4e80-9f3d-b9080f355fef" />

<img width="1252" height="962" alt="image" src="https://github.com/user-attachments/assets/989677bc-b8a6-42bc-8ffa-9c8f877c79a3" />

