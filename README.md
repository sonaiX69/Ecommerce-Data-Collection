
# Ecommerce Data Collection🌌

Welcome to this repo, this repo will be collectiong data on Ecommerce products and its customers.

![](https://i.pinimg.com/564x/83/46/dc/8346dcb07a2984d98b9d221aaa57098c.jpg)

## Collection Requirement :

1 : Products 

2 : Customers

### Products Model :

```http
  [
    {
        "product":"PRODUCT_NAME (string)",
        "category":"CATEGORY_TYPE (string)",
        "price":PRICE (number),
        "company":"COMPANY_NAME (string)"
    },
]
```

#### Products Model Example :

```http
[
    {
        "product":"Milk",
        "category":"Grocery",
        "price":40,
        "company":"Amul Dairy"
    },
    {
        "product":"Bread",
        "category":"Grocery",
        "price":20,
        "company":"Brittania"
    }
]
```

### Customer Model :

```http
   {
        "customer":"CUSTOMER_NAME (string)",
        "purchased":{
            "CATEGORY_TYPE_1 (string)":[
                "PRODUCT_NAME_1 (string)","PRODUCT_NAME_2 (string)"
            ],
            "CATEGORY_TYPE_2 (string)":[
                "PRODUCT_NAME_1 (string)","PRODUCT_NAME_2 (string)"
            ],
            "CATEGORY_TYPE_3 (string)":[
                "PRODUCT_NAME_1 (string)","PRODUCT_NAME_2 (string)"
            ]
        }
    }
```

#### Customer Model Example :

```http
[
    {
        "customer":"Riya Mandal",
        "purchased":{
            "grocery":[
                "milk","bread","butter","biscuit"
            ],
            "vegetables":[
                "potato","onion","garlic"
            ],
            "electronics":[
                "battery","ear-phone"
            ]
        }
    }
]
```


## Contribute 2 this repository : 

For a successfull "PULL REQUEST(PR)" 

all you have to do is fork down my repo in your local machine & contribute data to [products.json & customer.json] and push send a PR with proof(ss)

#### Remember :

That in products.json the product name should be unique and in the PR please attach the proof that the product name does'nt exist and that it is newly added, check using ctrl + F(Windpws)/cmd + F(Mac) that the product name already exists or not✌️😄

Please remember that products name should be unique🙂✌️

#### Wrong Data Entry❌
![Screenshot (69)](https://user-images.githubusercontent.com/76695320/135745955-bd12752f-e163-43f6-abd0-298719816c4e.jpg)


#### Correct Data Entry✔️
![image](https://user-images.githubusercontent.com/76695320/135745982-8c40c663-5728-495c-a656-b43d7add924a.png)

#### Rules to add new data 

#### @poduct.json format: 


```http
  [
    {
        "product":"PRODUCT_NAME (string)",
        "category":"CATEGORY_TYPE (string)",
        "price":PRICE (number),
        "company":"COMPANY_NAME (string)"
    },
]
```


#### @customer.json format

```http
   {
        "customer":"CUSTOMER_NAME (string)",
        "purchased":{
            "CATEGORY_TYPE_1 (string)":[
                "PRODUCT_NAME_1 (string)","PRODUCT_NAME_2 (string)"
            ],
            "CATEGORY_TYPE_2 (string)":[
                "PRODUCT_NAME_1 (string)","PRODUCT_NAME_2 (string)"
            ]
        }
    }
```

# Thanks For Contributin😄 Your Data is Valuable✌️

![](https://i.pinimg.com/564x/9c/61/cd/9c61cdd044f757ce20a0aec9555102ee.jpg)





