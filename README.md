# online-shopping project using python
this project works with 3 files (users.csv, receipts.csv, malls.csv)

## format of each file
#### users.csv:


```diff
role,username,password

manager,0999***5358,a665a45920422f9d417e4867efdc4fb8a04a1f3fff1fa07e998e86f7f7a27ae3

customer,0999***2121,03ac674216f3e15c761ee1a5e255f067953623c8b388b4459e13f978d7c846f4
```

#### malls.csv:
```diff
manager,name,opening_time,closing_time,all_products,blocked_customers

09995555358,refah,7:00,22:00,"[{'barcode': '1', 'price': 15.0, 'brand': 'pegah', 'name': 'shir', 'available': 13, 'expiration_date': '1400/7/15'}]",[]

09991112121,jambo,8:00,23:00,"[{'barcode': '1', 'price': 14.0, 'brand': 'kaleh', 'name': 'panir', 'available': 3, 'expiration_date': '1400/6/2'}]",[]
```


#### reciepts.csv:
```diff
customer,all_receipts

09354104101,"[{'mall': 'refah', 'customer': '09354104101', 'purchased_products': [{'name': 'panir', 'price': 20, 'quantity': 2}], 'date': '1400/10/27', 'hour': '12:56', 'sum_prices': 40}]"

09121111112,"[{'mall': 'Ofogh', 'customer': '09121111112', 'purchased_products': [{'name': 'panir', 'price': 20, 'quantity': 1}, {'name': 'chips', 'price': 30, 'quantity': 1}], 'date': '1400/9/27', 'hour': '13:56', 'sum_prices': 50}]"

09121133112,"[{'mall': 'refah', 'customer': '09121133112', 'purchased_products': [{'name': 'khameh', 'price': 20, 'quantity': 1}], 'date': '1400/10/27', 'hour': '10:56', 'sum_prices': 20}, {'mall': 'refah', 'customer': '09121133112', 'purchased_products': [{'name': 'pofak', 'price': 10, 'quantity': 1}], 'date': '1400/11/02', 'hour': '17:56', 'sum_prices': 10}]"
```







