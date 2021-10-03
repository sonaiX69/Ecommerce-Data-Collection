
# Ecommerce Data Collection

Welcome to this repo, this repo will be collectiong data on Ecommerce products and its customers.

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



