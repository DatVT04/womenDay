```plaintext
+--------------+--------------+--------------+------------------+----------------+
|  Customer    |   System     |  Marketing   | Payment Gateway  | Shipping Unit  |
+--------------+--------------+--------------+------------------+----------------+
| Enter website                                                   |
| Select & add to cart                                           |
| Order                                                          |
| Input address                                                  |
+--------------+--------------+--------------+------------------+----------------+
|              | Receive order request                           |
|              | Check stock                                     |
+--------------+--------------+--------------+------------------+----------------+
|              |              | Stock available?                |
|              |              |   | Yes -> Proceed              |
|              |              |   | No -> Notify out of stock   |
+--------------+--------------+--------------+------------------+----------------+
|              | Send payment request                           |
|              |              |                                  |
|              |              |                                  |
|              |              |                                  |
|              |              |                                  |
|              |              |                                  |
+--------------+--------------+--------------+------------------+----------------+
|              |              |              | Payment Processing |
|              |              |              | Payment Success?   |
|              |              |              |   | Yes -> Confirm |
|              |              |              |   | No -> Retry/Cancel |
+--------------+--------------+--------------+------------------+----------------+
|              | Confirm successful transaction                 |
+--------------+--------------+--------------+------------------+----------------+
|              |              |              |                  | Packing Order  |
+--------------+--------------+--------------+------------------+----------------+
|              |              |              |                  | Shipping       |
+--------------+--------------+--------------+------------------+----------------+
| Receive Delivery                                                |
| End                                                             |
+--------------+--------------+--------------+------------------+----------------+
```

