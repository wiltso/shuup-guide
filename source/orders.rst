.. _Orders:

Orders
======

Creating an Order
~~~~~~~~~~~~~~~~~

Orders can be made in one of two ways:
   By a customer through the shop front
   By a merchant through the Shuup Admin.

To create an order through the Shuup Admin:
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

1. Navigate to the Orders admin page by clicking `Orders` under the
   `Orders` category from the Shuup Admin menu.

   .. image:: orders/orders-location-in-menu.png



2. Click the `New order` button on the Order admin toolbar.

   .. image:: orders/new-order-button-location.png



3. Under the **Customer details** section, search the customer by name 
   or email, to select the customer click on the name.
   
   If you click the search icon, it launch the customer selection popup
   wehere you also can search for the customer.
   
   By leaveing the field blank it will create a new customer along with the order.

   If you select the wrong customer you can either 
   search for the correct one and select that customer again or
   by clicking the bin icon that will remove the customer.

   .. image:: orders/customer-selection.png


   When the customer is select correctly you will be able to view the customers details.

   .. image:: orders/customer-selection-complete.png

3.1. Fill in the rest of the customer details.
   This includes the billing and shipping address.

4. Under the **Order contents** section, you will select all 
   order lines witch the order will contain.

   If you want to add an existing product to the order,
   search for with the input filed, or by clicking the search icon to bring up
   the product popup window.

   .. image:: orders/order-product-selection.png

   Here you will again need to click on the product you want to add to the order.


   If you want to add a blank order line to the order click `Add new line`.
   These can either be of type `product`, `other`, or `text/comment`.

   .. image:: orders/blank-order-line.png


   Here are the types of lines you can create in an order:

   Product line
      A product, quantity, and any pricing or discount information
   Other line
      A miscellaneous priced line
   Text/Comment line
      A non-priced text line

6. Select a shipping and payment method for the order from the
   `Shipping Methods` dropdown and the `Payment Method` dropdown.

   .. image:: orders/new-order-select-ship-and-payment.png

7. Click the `Proceed` button to create the order.

   .. image:: orders/proceed-button.png

.. note::
   You must select shipping and payment methods for each order.

.. note::
   Method rules, taxes and possible extra discounts are calculated after proceeding.


Editing an Order
~~~~~~~~~~~~~~~~

1. Navigate to the Orders admin page by clicking `Orders` under the
   `Orders` category from the Shuup Admin menu.

   .. image:: orders/orders-menu.png

2. Select the order that you wish to edit.

   .. image:: orders/select-order.png

3. Click `Edit Order` in the order toolbar.

   .. image:: orders/edit-order-button.png

4. Make any desired changes to the order contents as done when
   `Creating an Order`_.

   .. image:: orders/edit-order-contents.png

6. Click the `Proceed` button to save the order contents.

   .. image:: orders/proceed-button.png


Order Shipments
~~~~~~~~~~~~~~~

Creating an Order Shipment
^^^^^^^^^^^^^^^^^^^^^^^^^^

To create an order shipment:

1. Navigate to the Orders admin page by clicking `Orders` under the
   `Orders` category from the Shuup Admin menu.

   .. image:: orders/orders-menu.png

2. Select the order for which you want to create a shipment.

   .. image:: orders/select-order.png

3. Click `Create Shipment` in the order toolbar.

   .. image:: orders/create-shipment-dropdown.png

4. For each product, select the quantity of that product to include
   in the shipment.
   To easily select all remaining unshipped quantities, click `Set All
   Products To Ship`.

   .. image:: orders/create-shipment.png

5. Select a product supplier from the dropdown menu.

   .. image:: orders/supplier.png

6. Click the `Create Shipment` button to create the shipment.

Printing a Delivery Slip
^^^^^^^^^^^^^^^^^^^^^^^^

To print a delivery slip for an order shipment:

1. Navigate to the Orders admin page by clicking `Orders` under the
   `Orders` category from the Shuup Admin menu.

   .. image:: orders/orders-menu.png

2. Select the order which delivery slip you want to print.

   .. image:: orders/select-order.png

3. If you haven't already done so, create an order shipment.

   See `Creating an Order Shipment`_.
4. Click `Printouts` tab on the left-hand side of the screen

..   .. image:: orders/print-button.png

5. Click `Get Delivery Slip HTML` for the order shipment you would like to
   print (there will be one available for each shipment).

..   .. image:: orders/get-delivery-slip.png

6. You will now be taken to the delivery slip, which you can
   either print or save to your computer from your browser menu.

..   .. image:: orders/delivery-slip.png

Order Payments
~~~~~~~~~~~~~~

Creating an Order Payment
^^^^^^^^^^^^^^^^^^^^^^^^^

To create an order payment:

1. Navigate to the Orders admin page by clicking `Orders` under the
   `Orders` category from the Shuup Admin menu.

   .. image:: orders/orders-menu.png

2. Select the order for which you want to create a payment.

   .. image:: orders/select-order.png

3. Click `Create Payment` in the order toolbar.

   .. image:: orders/create-payment-dropdown.png

4. Enter the amount of the payment in the `Payment amount` field or
   click `Get Remaining Total` to automatically fill will remaining
   unpaid total.

   .. image:: orders/create-payment.png

6. Click the `Create Payment` button to create the payment.

Viewing Order Payments
^^^^^^^^^^^^^^^^^^^^^^

To view all payments for an order:

1. Navigate to the Orders admin page by clicking `Orders` under the
   `Orders` category from the Shuup Admin menu.

   .. image:: orders/orders-menu.png

2. Select the order whose payments you want to view.

   .. image:: orders/select-order.png

3. Click the `Payments` tab on the left-hand side of the screen.

   .. image:: orders/payments-tab.png

.. note::
   The `Payment` tab won't be available unless a payment has been created.

4. Details will be listed for all payments associated with that order.

   .. image:: orders/payments.png

Order Refunds
~~~~~~~~~~~~~

.. note::

   Orders can only be refunded once at least one payment has been
   created for the order.

   However, refund amounts are not restricted by existing payment
   amounts, meaning it is possible to refund more than has been
   actually paid.

   If an order cannot be refunded, it will not be visible in the
   `Actions` dropdown menu.

.. note::

   Once a refund has been created, it will appear as a refund line
   in the `Order Contents` tab.

Creating a Partial Refund
*************************

To create a partial refund for a particular amount or to refund
particular order line amounts:

1. Navigate to the Orders admin page by clicking `Orders` under the
   `Orders` category from the Shuup Admin menu.

   .. image:: orders/orders-menu.png

2. Select the order for which you want to create a refund.

   .. image:: orders/select-order.png

3. Click `Create Refund` in the `Actions` dropdown in the admin
   page's toolbar.

   .. image:: orders/create-refund-dropdown.png

4. To create a refund for a particular line, select the matching line
   number from the `Line number` dropdown field.

   .. image:: orders/refund-line-form.png

   When refunding a product line, a field will appear to enter the
   quantity, as well as whether to restock the refunded products.

   .. note::
      A separate refund line will be created if returning both a
      quantity and an amount for a particular line.

5. Click the `Add More Refunds` button to add additional refund forms.

   .. image:: orders/add-more-refunds-button.png

6. Click the `Create Refund` to add the entered refund amounts to the
   order.

Creating a Full Refund
**********************

To create a full refund for an order:

1. Navigate to the Orders admin page by clicking `Orders` under the
   `Orders` category from the Shuup Admin menu.

   .. image:: orders/orders-menu.png

2. Select the order for which you want to create a refund.

   .. image:: orders/select-order.png

3. Click `Create Refund` in the `Actions` dropdown in the admin
   page's toolbar.

   .. image:: orders/create-refund-dropdown.png


4. Click the `Refund Entire Order` button in the admin page's toolbar.

   .. image:: orders/refund-entire-order-button.png

5. Review the order and refund amount information. To restock returned
   products, make sure the `Restock products` checkbox is selected.

6. Click the `Confirm Refund` to create a refund in the full amount.

Canceling an Order
~~~~~~~~~~~~~~~~~~

.. note::
   Only unpaid and unshipped orders can be canceled.

To cancel an order:

1. Navigate to the Orders admin page by clicking `Orders` under the
   `Orders` category from the Shuup Admin menu.

   .. image:: orders/orders-menu.png

2. Select the order that you want to cancel.

   .. image:: orders/select-order.png

3. Click `Set Status` in the order toolbar.

..   .. image:: orders/cancel-order-button.png

4. Click `Canceled` in the dropdown menu.

The order will now be marked as `canceled` in the Orders admin list.

Completing an Order
~~~~~~~~~~~~~~~~~~~

.. note::
   Only fully shipped orders chan be completed.

To set an order as complete:

1. Navigate to the Orders admin page by clicking `Orders` under the
   `Orders` category from the Shuup Admin menu.

   .. image:: orders/orders-menu.png

2. Select the order you want to set complete.

   .. image:: orders/select-order.png

3. Click `Set Status` in the order toolbar.

..   .. image:: orders/set-complete-button.png

4. Click `Complete` in the dropdown menu.

The order will now be marked as `completed`.

Printing an Order Confirmation
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

1. Navigate to the Orders admin page by clicking `Orders` under the 
   `Orders` category from the Shuup Admin menu.

   .. image:: orders/orders-menu.png

2. Select the order whose confirmation you want to print.

   .. image:: orders/select-order.png

3. Click `Printouts` tab on the left-hand side of the screen.

..   .. image:: orders/print-button.png

4. Select `Get Order Confirmation HTML` from the dropdown menu.

..   .. image:: orders/get-order-confirmation.png

5. You will now be taken to the order confirmation, which you
   can either print or save to your computer from your browser menu.

..   .. image:: orders/order-confirmation.png
