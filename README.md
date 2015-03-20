# HardwareStore

This is a virtualized sample of a simple book store api.

There are two groups of request-response pairs: Customers and Orders.

The "Create Customer" request takes a request body of
{"name":"Clark","address":"Slough", "trade": "12-15-2013", "settle": "12-19-2013"}
and creates a customer.
When you come to execute this pair, you can pass in different customer details e.g. 
{"name":"Smith","address":"Windsor", "trade": "12-15-2013", "settle": "12-19-2013"}
and the POST will respond with these different details.

The same applies to the "Update Customer" PUT request.

The "Get customer details 1" and "Get customer details 2" demonstrate how the name of the customer
can be passed as a parameter in two different ways.

The "List all orders" fetches a list of all orders to the store.

You can sort, filter, select specific attributes, limit the number of items and change the format (XML to JSON and vice-versa) of the response from your REST API using system filter parameters provided by CA Virtual APi Cloud.  This is supported for GET requests with responses in XML or JSON format.  See https://communities.ca.com/docs/DOC-231150902?sr=inbox for more details.
