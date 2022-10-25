# journal_3_checkout_bugfix
Opencart Journal 3 framework self checkout bugfix.

Theme checkout has huge bugs!

- session sometimes not close after success order
so the customer can update placed order, or destory it.

- Vue.js handling processing logic errors
it can destory the order data 
and so on generate huge DB query ammont
it can slow down the whole server.

Video about the issues , and how to fix it:
***coming soon.. ***

**if you have any better idea, please let me know :)

