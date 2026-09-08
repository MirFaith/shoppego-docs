# Notifications Parameter

This parameter allows you to change the text of the email/message notification that your customers will be able to do according to your convenience.

For example, you would want to create text like:

> **Order #SA123**\
> \
> **Shipping Information**\
> **Abu Ahmad**

You need to use the following parameters:

> **Order {{ name }}**\
> \
> **Shipping Information**\
> **{{ customer.first\_name }} {{ customer.last\_name }}**

For more information, the parameters you can use in the Commerce system are below.

These are the **parameters you can use for the&#x20;**<mark style="color:red;">**Subject**</mark>**&#x20;column in your notification template**:

This parameter can only be used for the notification of **Files ready for download, Order status changed, Checkout abandoned, Order review & Order packed**:

| <p><strong>Parameter:</strong> {{ store.name }}<br><strong>Description</strong>: The name of your store</p><p><strong>Example</strong>: Hartamas</p>                         |
| ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| <p><strong>Parameter:</strong> {{ store.email }}<br><strong>Description</strong>: Your store email</p><p><strong>Example</strong>: <hello@shoppego.com></p>                  |
| <p><strong>Parameter:</strong> {{ store.url }}<br><strong>Description</strong>: Link to your website</p><p><strong>Example</strong>: <https://hartamas.myshoppegram.com></p> |
| <p><strong>Parameter:</strong> {{ store.currency\_format }}<br><strong>Description</strong>: Currency format you use</p><p><strong>Example:</strong> MYR</p>                 |

This parameter can only be used for notifications of **Ordered shipped, Order status changed, Checkout abandoned, Order ready for pickup, Order review & Order packed**:

| <p><strong>Parameter:</strong> {{ customer.first\_name }}<br><strong>Description</strong>: Customer first name</p><p><strong>Example</strong>: Abu</p>       |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| <p><strong>Parameter:</strong> {{ customer.last\_name }}<br><strong>Description</strong>: Customer last name</p><p><strong>Example</strong>: Ahmad</p>       |
| <p><strong>Parameter:</strong> {{ customer.name }}<br><strong>Description</strong>: Customer's full name</p><p><strong>Example</strong>: Abu Ahmad</p>       |
| <p><strong>Parameter:</strong> {{ customer.email }}<br><strong>Description</strong>: Customer email</p><p><strong>Example</strong>: <abuahmad@gmail.com></p> |
| <p><strong>Parameter:</strong> {{ customer.phone }}<br><strong>Description</strong>: Customer phone number</p><p><strong>Example</strong>: 60123456789</p>   |

***

This is a **parameter that you can use on the&#x20;**<mark style="color:red;">**Body**</mark>**&#x20;column in your announcement template:**

| <p><strong>Parameter:</strong> {{ name }}<br><strong>Description</strong>: Order number</p><p><strong>Example</strong>: #SA123</p>                                                                                                                      |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| <p><strong>Parameter</strong>: {{ store.url }}</p><p><strong>Description</strong>: Link to your website</p><p><strong>Example</strong>: <https://hartamas.myshoppegram.com></p>                                                                         |
| <p><strong>Parameter</strong>: {{ store.name }}</p><p><strong>Description</strong>: The name of your store</p><p><strong>Example</strong>: Hartamas</p>                                                                                                 |
| <p><strong>Parameter</strong>: {{ store.email }}</p><p><strong>Description</strong>: Your store email</p><p><strong>Example</strong>: <hello@shoppego.com></p>                                                                                          |
| <p><strong>Parameter</strong>: {{ store.currency\_format }}</p><p><strong>Description</strong>: Currency format you use</p><p><strong>Example:</strong> MYR</p>                                                                                         |
| <p><strong>Parameter</strong>: {{ gateway\_details }}</p><p><strong>Description</strong>: Instructions on payment gateways</p><p><strong>Example</strong>: Payment can be made by direct bank transfer the amount to our bank details stated below.</p> |
| <p><strong>Parameter</strong>: {{ gateway\_name }}</p><p><strong>Description</strong>: Name of payment gateway/payment method used during checkout</p><p><strong>Example</strong>: Securepay</p>                                                        |
| <p><strong>Parameter</strong>: {{ gateway\_type }}</p><p><strong>Description</strong>: The type of payment gateway used</p><p><strong>Example</strong>: For COD and Bank deposits = manual</p><p>               For payment gateway = alternative</p>   |
| <p><strong>Parameter</strong>: {{ customer.first\_name }}</p><p><strong>Description</strong>: Customer first name</p><p><strong>Example</strong>: Abu</p>                                                                                               |
| <p><strong>Parameter</strong>: {{ customer.last\_name }}</p><p><strong>Description</strong>: Customer last name</p><p><strong>Example</strong>: Ahmad</p>                                                                                               |
| <p><strong>Parameter</strong>: {{ customer.name }}</p><p><strong>Description</strong>: Customer's full name</p><p><strong>Example</strong>: Abu Ahmad</p>                                                                                               |
| <p><strong>Parameter</strong>: {{ customer.email }}</p><p><strong>Description</strong>: Customer email</p><p><strong>Example</strong>: <abuahmad@gmail.com></p>                                                                                         |
| <p><strong>Parameter</strong>: {{ customer.phone }}</p><p><strong>Description</strong>: Customer phone number</p><p><strong>Example</strong>: 60123456789</p>                                                                                           |
| <p><strong>Parameter</strong>: {{ shipping\_address.first\_name }}</p><p><strong>Description</strong>: First name information entered in the shipping section</p><p><strong>Example</strong>: Nur</p>                                                   |
| <p><strong>Parameter</strong>: {{ shipping\_address.last\_name }}</p><p><strong>Description</strong>: Last name information entered in the shipping section</p><p><strong>Example</strong>: Rahimah</p>                                                 |
| <p><strong>Parameter</strong>: {{ shipping\_address.address }}</p><p><strong>Description</strong>: Address information entered in the Address section</p><p><strong>Example</strong>: Blok B 01-02-03</p>                                               |
| <p><strong>Parameter</strong>: {{ shipping\_address.address2 }} </p><p><strong>Description</strong>: Address information entered in the second Address line section (If any)</p><p><strong>Example</strong>: Jalan Permata Permai</p>                   |
| <p><strong>Parameter</strong>: {{ shipping\_address.city }}</p><p><strong>Description</strong>: City information entered in the City section</p><p><strong>Example</strong>: Selangor</p>                                                               |
| <p><strong>Parameter</strong>: {{ shipping\_address.state }}</p><p><strong>Description</strong>: County information entered in the State section</p><p><strong>Example</strong>: Cyberjaya</p>                                                          |
| <p><strong>Parameter</strong>: {{ shipping\_address.zip }}</p><p><strong>Description</strong>: Postal code information entered on Postcode/Zip</p><p><strong>Example</strong>: 63000</p>                                                                |

This parameter can only be used for **Order ready for pickup** notifications:

| <p><strong>Parameter</strong>: {{ pickup\_address.company }}<br><strong>Description</strong>: Your company name for pickup process<br><strong>Example</strong>: Hartamas</p>                                                                                |
| ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| <p><strong>Parameter</strong>: {{ pickup\_address.name}}<br><strong>Description</strong>: Your name for pickup process<br><strong>Example</strong>: Ali</p>                                                                                                 |
| <p><strong>Parameter</strong>: {{ pickup\_address.phone}}<br><strong>Description</strong>: Your company phone number for pickup process<br><strong>Example</strong>: 60123456789</p>                                                                        |
| <p><strong>Parameter</strong>: {{ pickup\_address.email}}<br><strong>Description</strong>: Your company email for pickup process<br><strong>Example</strong>: <hello@shoppego.com></p>                                                                      |
| <p><strong>Parameter</strong>: {{ pickup\_address.address}}<br><strong>Description</strong>: Your company address for pickup process<br><strong>Example</strong>: Blok B 01-02-03</p>                                                                       |
| <p><strong>Parameter</strong>: {{ pickup\_address.address2}}<br><strong>Description</strong>: Your company address information entered in the second Address line section for pickup process (If any)<br><strong>Example</strong>: Jalan Permata Permai</p> |
| <p><strong>Parameter</strong>: {{ pickup\_address.zip}}<br><strong>Description</strong>: Postal code information entered on Postcode/Zip for pickup process<br><strong>Example</strong>: 12300</p>                                                          |
| <p><strong>Parameter</strong>: {{ pickup\_address.city}}<br><strong>Description</strong>: City information entered in the City section for pickup process<br><strong>Example</strong>: Pasir Gudang</p>                                                     |
| <p><strong>Parameter</strong>: {{ pickup\_address.state}}<br><strong>Description</strong>: State information entered in the State section for pickup process<br><strong>Example</strong>: Johor Bahru</p>                                                   |
| <p><strong>Parameter</strong>: {{ pickup\_address.country}}<br><strong>Description</strong>: Country information entered in the Country section for pickup process<br><strong>Example</strong>: Malaysia</p>                                                |
| <p><strong>Parameter</strong>: {{ pickup\_address.instruction}}<br><strong>Description</strong>: Instruction for the customer<br><strong>Example</strong>: Please make sure you contact us 30 minutes before you come to pickup the items.</p>              |

This parameter can only be used for **Order shipped, Order status changed, Checkout abandoned, Order ready for pickup, Order review & Order packed notifications**:

| <p><strong>Parameter:</strong> {{ total\_price }}<br><strong>Description</strong>: The total price of the customer's order</p><p><strong>Example</strong>: 180.00</p>                                                          |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| <p><strong>Parameter</strong>: {{ total\_discount }}</p><p><strong>Description</strong>: Amount of discount that customers use in their order (If any)</p><p><strong>Example</strong>: 99.00</p>                               |
| <p><strong>Parameter</strong>: {{ shipping\_price }}</p><p><strong>Description</strong>: The total shipping price that the customer is charged (If any)</p><p><strong>Example</strong>: 8.00</p>                               |
| <p><strong>Parameter</strong>: {{ shipping\_method }}</p><p><strong>Description</strong>: The shipping name that the customer has chosen during the checkout page (If any)</p><p><strong>Example</strong>: Normal shipping</p> |

This parameter can only be used for **Order packed** notifications:

| <p><strong>Parameter:</strong> {{ requires\_shipping }}<br><strong>Description</strong>: Jika order itu memmpunyai shipping atau tidak</p><p><strong>Example</strong>: True(Untuk mempunyai shipping dan False(Untuk tidak mempunyai shipping)</p> |
| -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |

This parameter can only be used for **Checkout abandoned & Order review** notifications:

| <p><strong>Parameter:</strong> {{ currency }}<br><strong>Description</strong>: Currency format you use</p><p><strong>Example:</strong> MYR</p> |
| ---------------------------------------------------------------------------------------------------------------------------------------------- |

This parameter can only be used for **Order confirmation notification & File read for download**:

| <p><strong>Parameter:</strong> {{ files\[].name }}<br><strong>Description</strong>: Your file name</p><p><strong>Example</strong>: Ebook Percuma</p>                   |
| ---------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| <p><strong>Parameter:</strong> {{ files\[].url }}<br><strong>Description</strong>: Access link to your file</p><p><strong>Example</strong>: <https://shoppego.com></p> |

This parameter can only be used for notifications of Ordered shipped, Order status changed, Checkout abandoned, Order ready for pickup, Order review & Order packed:

| <p><strong>Parameter:</strong> {{ items\[].product.name }}<br><strong>Description</strong>: The name of the product purchased by the customer</p><p><strong>Example</strong>: T-shirt</p>   |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| <p><strong>Parameter:</strong> {{ items\[].name }}<br><strong>Description</strong>: The name of the product variant purchased by the customer</p><p><strong>Example</strong>: Putih</p>     |
| <p><strong>Parameter:</strong> {{ items\[].price }}<br><strong>Description</strong>: The price of your product</p><p><strong>Example</strong>: 50.00</p>                                    |
| <p><strong>Parameter:</strong> {{ items\[].quantity }}<br><strong>Description</strong>: The quantity of the product purchased by the customer</p><p><strong>Example</strong>: 2</p>         |
| <p><strong>Parameter:</strong> {{ items\[].subtotal }}<br><strong>Description</strong>: The total price of the product purchased by the customer</p><p><strong>Example</strong>: 100.00</p> |

This parameter can only be used for **Order shipped** notification:

| <p><strong>Parameter:</strong> {{ tracking\_url }}<br><strong>Description</strong>: Tracking URL for the courier you choose for the customer's order process</p><p><strong>Example</strong>: <https://www.ninjavan.co/en-my/tracking></p> |
| ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| <p><strong>Parameter:</strong> {{ tracking\_number }}<br><strong>Description</strong>: The customer's tracking number that you have entered during the Add tracking process</p><p><strong>Example</strong>: MY000000010NJVN</p>           |
| <p><strong>Parameter:</strong> {{ tracking\_company }}<br><strong>Description</strong>: The name of the company/shipping carrier you use during the Add tracking process</p><p><strong>Example</strong>: Ninjavan</p>                     |
