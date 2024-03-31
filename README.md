# dotnetcore-ecommerce

## Function Requirements

### Login with Anonymous (GUF) & Registered User
- Platform Users (Admin/Maintainer), Retail Users (End Users), Anonymous Users (limited functionality)

#### General Functionality

- **Product Catalog Management**: 
  - Provides functionality for managing products available on the website, including their descriptions, images, prices, and other relevant information.
- **Inventory Management Related to Catalog**:
  - **Search**: Enables users to search for specific products within the catalog based on various criteria.
  - **Add/Remove/Mark as Unavailable**: Allows administrators to add new products, remove existing ones, and mark products as unavailable when necessary.
  - **Inventory Reporting**: Generates reports detailing the current status of inventory, including stock levels, sales trends, and other relevant metrics.
  - **Reconciliation of Inventory**: Ensures consistency between recorded inventory levels and actual stock on hand through periodic reconciliation processes.
- **Cart Management**:
  - Enables users to add multiple products to their shopping carts for convenient checkout.
- **Checkout Scenario with Login/GUF**:
  - **Enforce Login before Checkout**: Requires users to log in or proceed as a guest (if allowed) before initiating the checkout process.
  - **Inventory Check before Checkout**: Verifies product availability and updates inventory levels before allowing users to proceed with payment.
  - **Lock Products in the Cart**: Temporarily reserves selected products in the user's cart for a specified duration (e.g., 10 minutes) to prevent overselling during the checkout process.
  - **Retry Payment Option**: Provides users with the ability to retry failed payment transactions without losing their cart contents.
  - **Send Email Notifications with Order Details**: Sends confirmation emails to users upon successful completion of an order, providing them with order details and transaction summaries.
- **Order Management**:
  - **Order History Management**: Maintains a comprehensive record of all previous orders placed by users for reference and tracking purposes.
  - **Order Cancellations**: Allows users to cancel orders within a specified timeframe, with appropriate updates to inventory and payment status.
- **User Details Management**:
  - Facilitates the management of user profiles, including shipping and billing addresses, contact information, and password reset functionalities.
  - **Username (Email)/Password Management**: Enables users to update their login credentials securely.
  - **Create New Catalog Type**: Allows administrators to define and manage different types or categories of products within the catalog.
- **Payment Service**:
  - Manages payment transactions securely, providing users with various payment options and processing payments in compliance with relevant regulations.
  - **Transaction Details**: Records transaction details, including the last four digits of the card used for payment, for reference and auditing purposes.
  - **Generation of Reconciliation Reports**: Generates detailed reports reconciling payment transactions with order records and inventory updates for accounting and auditing purposes.

## Future Enhancements:

1. Search/Delivery/Service - Region Separation
2. Integration of Third-Party Sellers
3. Additional Features for Business Users (Sellers)
