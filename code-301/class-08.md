# Class 08 Reading Notes

## API Design Best Practices

1) REST stands for Representation State Transfer

2)REST API's are designed around resources such as objects, data or service that can be accessed by the client

3)An identifier for REST resource is a URL that uniquely identifies the resource such as 'https://amazon.com/orders/20'

4)The most common HTTP verb's are customer/order/products/item

5)The URL should be based on a reference to what the resource is going to be

6)'https://amazon.com/orders/20'

7)A chatty web API requires the client to send multiple requests to find all the data that they require.

8)GET sends a 200 (OK) when it is successful.

9)GET sends a 404 (NOT FOUND) when unsuccessful.

10)POST returns a 201(CREATED) when successful

11)Delete sends a 204(NO CONTENT) when successful