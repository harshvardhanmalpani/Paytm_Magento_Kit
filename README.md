# Paytm_Magento_Kit
### For successful setup in Magento 2.2x  (Tested in 2.2.2 at the time of writing)
- Go to ***Stores > Order Status > Create New Order Status***
    - In the field `Status Code`, input - *unpaid*
    - In the `Status Field`, input say - *Pending*
    - Save it.

 - After saving it, Click on ***Assign Status to State***
    - In `Order Status`, choose the latest status you just created - *unpaid*
    - In `Order State`, choose *processing*

## DO NOT forget
- `Use Order Status As Default` - **YES**
- `Visible On Storefront` - **YES**
---

- In ***Store > Configuration > Sales > Payment Methods > Paytm**
    - Choose `New Order Status`	as *Processing*
