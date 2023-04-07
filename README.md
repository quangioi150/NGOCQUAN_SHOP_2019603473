## Database: MySQLAdmin

# Tạo config thư viện:

``
# install Java JDK 13
# install MySQL 
```

# Setup database trong file settings.py

```
DATABASES = {
    'default': {
        'ENGINE': 'django.db.backends.postgresql',
        'NAME': 'luxury_shop',
        'USER': 'admin',
        'PASSWORD': '123456',
        'HOST': 'localhost',
        'PORT': '5432',
    }
}
```

## Import file postman.json vào postman, test các API

## Name

NGOCQUAN_SHOP_2019603473

## Description
Project NGOCQUAN_SHOP_2019603473 là website bán hàng nội thất code bằng Java Spring, có sử dụng luật khai phá để  
để hiện thị những sản phẩm đi kèm.




