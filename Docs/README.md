# E-commerce-RESTful-API

> Version 1.0.0

## Path Table

| Method | Path | Description |
| --- | --- | --- |
| GET | [/api/v1/categories](#getapiv1categories) | getCategories |
| GET | [/api/v1/categories/66f03101c1b7a8fdee9be66b](#getapiv1categories66f03101c1b7a8fdee9be66b) | getCategory |
| PUT | [/api/v1/categories/66f03101c1b7a8fdee9be66b](#putapiv1categories66f03101c1b7a8fdee9be66b) | updateCategory |
| POST | [/api/v1/categories/](#postapiv1categories) | createCategory |
| DELETE | [/api/v1/categories/66d5fd2de8b79539a190a0c8](#deleteapiv1categories66d5fd2de8b79539a190a0c8) | deleteCategory |
| GET | [/api/v1/brands](#getapiv1brands) | Get List of Brands |
| GET | [/api/v1/brands/66e71e127014e2b579119b45](#getapiv1brands66e71e127014e2b579119b45) | Get Specific Brand |
| POST | [/api/v1/brands/](#postapiv1brands) | Create Brand |
| PUT | [/api/v1/brands/66f036671fffd0f6d65a1d58](#putapiv1brands66f036671fffd0f6d65a1d58) | Update Specific Brand |
| DELETE | [/api/v1/brands/66d9ac36a323087d7bbcd62f](#deleteapiv1brands66d9ac36a323087d7bbcd62f) | deleteCategory |
| GET | [/api/v1/users](#getapiv1users) | Get List of Users |
| POST | [/api/v1/users](#postapiv1users) | Create User |
| GET | [/api/v1/users/67019d515d4d3d07e28038ac](#getapiv1users67019d515d4d3d07e28038ac) | Get Specific User |
| PUT | [/api/v1/users/670c1a59cdd70e7d355568c1](#putapiv1users670c1a59cdd70e7d355568c1) | Update Specific User |
| PUT | [/api/v1/users/changepassword/67088847a05699adc4dd3b8c](#putapiv1userschangepassword67088847a05699adc4dd3b8c) | Change User Password |
| DELETE | [/api/v1/users/67019e715d4d3d07e28038bf](#deleteapiv1users67019e715d4d3d07e28038bf) | Delete User |
| GET | [/api/v1/products](#getapiv1products) | Get List of products |
| POST | [/api/v1/products](#postapiv1products) | Create Product |
| GET | [/api/v1/subcategories/66d8725f23e31ad45a0e1bfd](#getapiv1subcategories66d8725f23e31ad45a0e1bfd) | getSubcategory |
| POST | [/api/v1/subcategories/](#postapiv1subcategories) | createSubcategory |
| PUT | [/api/v1/subcategories/66d86c9760a8d7068425759b](#putapiv1subcategories66d86c9760a8d7068425759b) | updateSubcategory |
| DELETE | [/api/v1/subcategories/66d86c9760a8d7068425759b](#deleteapiv1subcategories66d86c9760a8d7068425759b) | deleteSubcategory |
| GET | [/api/v1/categories/66d5f29ce3cf1164e4c193ce/subcategories](#getapiv1categories66d5f29ce3cf1164e4c193cesubcategories) | Get List of SubCatgories For Category |
| POST | [/api/v1/categories/66d5f29ce3cf1164e4c193ce/subcategories](#postapiv1categories66d5f29ce3cf1164e4c193cesubcategories) | Create subcategory on Category |
| GET | [/api/v1/products/66def32151e816be5bdbea26](#getapiv1products66def32151e816be5bdbea26) | Get Specific Product |
| PUT | [/api/v1/products/66daecf4b3001f5b6099e042](#putapiv1products66daecf4b3001f5b6099e042) | Update Specific Product |
| DELETE | [/api/v1/products/66daecd8b3001f5b6099e03d](#deleteapiv1products66daecd8b3001f5b6099e03d) | delete Product |
| POST | [/api/v1/auth/signup](#postapiv1authsignup) | SignUp |
| POST | [/api/v1/auth/login](#postapiv1authlogin) | login |
| POST | [/api/v1/auth/forgetpassword](#postapiv1authforgetpassword) | Forgot Password |
| POST | [/api/v1/auth/verifyResetCode](#postapiv1authverifyresetcode) | Verify Reset Password Code |
| PUT | [/api/v1/auth/resetpassword](#putapiv1authresetpassword) | Reset Password |
| GET | [/api/v1/users/getMe](#getapiv1usersgetme) | Get Logged User Data |
| PUT | [/api/v1/users/changemypassword](#putapiv1userschangemypassword) | Update Logged User Password |
| PUT | [/api/v1/users/updateme](#putapiv1usersupdateme) | Update Logged User Data |
| PUT | [/api/v1/users/deleteme](#putapiv1usersdeleteme) | Update Logged User Data Copy |
| GET | [/api/v1/reviews](#getapiv1reviews) | Get List of reviews |
| POST | [/api/v1/reviews](#postapiv1reviews) | Create  Review |
| GET | [/api/v1/reviews/670c0dbac6f89173cda0ef5b](#getapiv1reviews670c0dbac6f89173cda0ef5b) | Get Specific  Review |
| PUT | [/api/v1/reviews/670ffbe62681d0e5d503db54](#putapiv1reviews670ffbe62681d0e5d503db54) | Update Specific Review |
| DELETE | [/api/v1/reviews/671006f4bdd3fd0c6ca068e7](#deleteapiv1reviews671006f4bdd3fd0c6ca068e7) | delete Review |
| GET | [/api/v1/wishlist](#getapiv1wishlist) | Get Loggeduser WishList |
| POST | [/api/v1/wishlist](#postapiv1wishlist) | Add Product To wishList |
| DELETE | [/api/v1/wishlist/66def32151e816be5bdbea2a](#deleteapiv1wishlist66def32151e816be5bdbea2a) | Delete Product From WishList |
| GET | [/api/v1/address](#getapiv1address) | Get Loggeduser Addresses |
| POST | [/api/v1/address](#postapiv1address) | Add Address |
| DELETE | [/api/v1/address/6713353ddfd443a9e3195d4b](#deleteapiv1address6713353ddfd443a9e3195d4b) | Delete addresss |
| GET | [/api/v1/coupons](#getapiv1coupons) | Get List of Coupons |
| GET | [/api/v1/coupons/67134ed7afc4854866e35c3c](#getapiv1coupons67134ed7afc4854866e35c3c) | Get Specific Coupon |
| PUT | [/api/v1/coupons/67134ed7afc4854866e35c3c](#putapiv1coupons67134ed7afc4854866e35c3c) | Update Specific Brand |
| DELETE | [/api/v1/coupons/67134ed7afc4854866e35c3c](#deleteapiv1coupons67134ed7afc4854866e35c3c) | deleteCategory |
| POST | [/api/v1/coupons/](#postapiv1coupons) | Create Coupon |
| GET | [/api/v1/products/66def32151e816be5bdbea2a/reviews](#getapiv1products66def32151e816be5bdbea2areviews) | Get List of reviews on specific Products |
| GET | [/api/v1/products/66def32151e816be5bdbea2a/reviews/670c2cf6511faf33168948bc](#getapiv1products66def32151e816be5bdbea2areviews670c2cf6511faf33168948bc) | Get A specific Review on specific Product |
| POST | [/api/v1/products/66e820de422c2b84a2a742d4/reviews](#postapiv1products66e820de422c2b84a2a742d4reviews) | Create Review in specific product |
| POST | [/api/v1/cart](#postapiv1cart) | Add Product to Cart |
| GET | [/api/v1/cart](#getapiv1cart) | Get Logged in User Cart |
| DELETE | [/api/v1/cart/](#deleteapiv1cart) | Remove Specifc Cart Item |
| DELETE | [/api/v1/cart/66def32151e816be5bdbea26](#deleteapiv1cart66def32151e816be5bdbea26) | Clear User Cart |
| PUT | [/api/v1/cart/applycoupon](#putapiv1cartapplycoupon) | Aply Coupon To user Cart |
| PUT | [/api/v1/cart/6714fc6119228ca73e6b3f3f](#putapiv1cart6714fc6119228ca73e6b3f3f) | Update Cart Item Quantity |
| POST | [/api/v1/orders/67168b6ec979d4f8028d87b5](#postapiv1orders67168b6ec979d4f8028d87b5) | Create Cash Order |
| GET | [/api/v1/orders/67168acb305eee14769692f8](#getapiv1orders67168acb305eee14769692f8) | Get Specific Order |
| GET | [/api/v1/orders/](#getapiv1orders) | Get All Orders |
| PUT | [/api/v1/orders/67168acb305eee14769692f8/pay](#putapiv1orders67168acb305eee14769692f8pay) | Update Order Status to Paid |
| PUT | [/api/v1/orders/67168acb305eee14769692f8/deliver](#putapiv1orders67168acb305eee14769692f8deliver) | Update Order Status to Deliverd |
| GET | [/api/v1/orders/checkout-session/6716a507ace4dc490f2fb4b0](#getapiv1orderscheckout-session6716a507ace4dc490f2fb4b0) | Get Checkout Session |

## Reference Table

| Name | Path | Description |
| --- | --- | --- |
| noauthAuth | [#/components/securitySchemes/noauthAuth](#componentssecurityschemesnoauthauth) |  |
| bearerAuth | [#/components/securitySchemes/bearerAuth](#componentssecurityschemesbearerauth) |  |

## Path Details

***

### [GET]/api/v1/categories

- Summary  
getCategories

#### Responses

- 200 Successful response

`application/json`

***

### [GET]/api/v1/categories/66f03101c1b7a8fdee9be66b

- Summary  
getCategory

- Security  
noauthAuth  

#### Responses

- 200 Successful response

`application/json`

***

### [PUT]/api/v1/categories/66f03101c1b7a8fdee9be66b

- Summary  
updateCategory

#### RequestBody

- multipart/form-data

```ts
{
  name?: string
}
```

#### Responses

- 200 Successful response

`application/json`

***

### [POST]/api/v1/categories/

- Summary  
createCategory

- Security  
bearerAuth  

#### RequestBody

- multipart/form-data

```ts
{
  name?: string
  image?: string
}
```

#### Responses

- 200 Successful response

`application/json`

***

### [DELETE]/api/v1/categories/66d5fd2de8b79539a190a0c8

- Summary  
deleteCategory

#### Responses

- 200 Successful response

`application/json`

***

### [GET]/api/v1/brands

- Summary  
Get List of Brands

#### Responses

- 200 Successful response

`application/json`

***

### [GET]/api/v1/brands/66e71e127014e2b579119b45

- Summary  
Get Specific Brand

#### Responses

- 200 Successful response

`application/json`

***

### [POST]/api/v1/brands/

- Summary  
Create Brand

#### RequestBody

- multipart/form-data

```ts
{
  name?: string
  image?: string
}
```

#### Responses

- 200 Successful response

`application/json`

***

### [PUT]/api/v1/brands/66f036671fffd0f6d65a1d58

- Summary  
Update Specific Brand

#### RequestBody

- multipart/form-data

```ts
{
  name?: string
  image?: string
}
```

#### Responses

- 200 Successful response

`application/json`

***

### [DELETE]/api/v1/brands/66d9ac36a323087d7bbcd62f

- Summary  
deleteCategory

#### Responses

- 200 Successful response

`application/json`

***

### [GET]/api/v1/users

- Summary  
Get List of Users

- Security  
bearerAuth  

#### Responses

- 200 Successful response

`application/json`

***

### [POST]/api/v1/users

- Summary  
Create User

- Security  
bearerAuth  

#### RequestBody

- multipart/form-data

```ts
{
  name?: string
  email?: string
  password?: string
  phone?: integer
  role?: string
  profileImg?: string
  confirmPassword?: string
}
```

#### Responses

- 200 Successful response

`application/json`

***

### [GET]/api/v1/users/67019d515d4d3d07e28038ac

- Summary  
Get Specific User

#### Responses

- 200 Successful response

`application/json`

***

### [PUT]/api/v1/users/670c1a59cdd70e7d355568c1

- Summary  
Update Specific User

- Security  
bearerAuth  

#### RequestBody

- multipart/form-data

```ts
{
  name?: string
  email?: string
  profileImg?: string
  role?: string
}
```

#### Responses

- 200 Successful response

`application/json`

***

### [PUT]/api/v1/users/changepassword/67088847a05699adc4dd3b8c

- Summary  
Change User Password

#### RequestBody

- application/json

```ts
{
}
```

#### Responses

- 200 Successful response

`application/json`

***

### [DELETE]/api/v1/users/67019e715d4d3d07e28038bf

- Summary  
Delete User

- Security  
bearerAuth  

#### Responses

- 200 Successful response

`application/json`

***

### [GET]/api/v1/products

- Summary  
Get List of products

- Security  
noauthAuth  

#### Parameters(Query)

```ts
limit?: integer
```

#### Headers

```ts
Authorization?: string
```

#### Responses

- 200 Successful response

`application/json`

***

### [POST]/api/v1/products

- Summary  
Create Product

#### RequestBody

- multipart/form-data

```ts
{
  title?: string
  price?: integer
  quantity?: integer
  category?: string
  description?: string
  imageCover?: string
  images?: string
}
```

#### Responses

- 200 Successful response

`application/json`

***

### [GET]/api/v1/subcategories/66d8725f23e31ad45a0e1bfd

- Summary  
getSubcategory

#### Responses

- 200 Successful response

`application/json`

***

### [POST]/api/v1/subcategories/

- Summary  
createSubcategory

#### RequestBody

- application/json

```ts
{
}
```

#### Responses

- 200 Successful response

`application/json`

***

### [PUT]/api/v1/subcategories/66d86c9760a8d7068425759b

- Summary  
updateSubcategory

#### RequestBody

- application/json

```ts
{
}
```

#### Responses

- 200 Successful response

`application/json`

***

### [DELETE]/api/v1/subcategories/66d86c9760a8d7068425759b

- Summary  
deleteSubcategory

#### Responses

- 200 Successful response

`application/json`

***

### [GET]/api/v1/categories/66d5f29ce3cf1164e4c193ce/subcategories

- Summary  
Get List of SubCatgories For Category

#### Responses

- 200 Successful response

`application/json`

***

### [POST]/api/v1/categories/66d5f29ce3cf1164e4c193ce/subcategories

- Summary  
Create subcategory on Category

#### RequestBody

- application/json

```ts
{
}
```

#### Responses

- 200 Successful response

`application/json`

***

### [GET]/api/v1/products/66def32151e816be5bdbea26

- Summary  
Get Specific Product

#### Responses

- 200 Successful response

`application/json`

***

### [PUT]/api/v1/products/66daecf4b3001f5b6099e042

- Summary  
Update Specific Product

#### RequestBody

- application/json

```ts
{
}
```

#### Responses

- 200 Successful response

`application/json`

***

### [DELETE]/api/v1/products/66daecd8b3001f5b6099e03d

- Summary  
delete Product

#### Responses

- 200 Successful response

`application/json`

***

### [POST]/api/v1/auth/signup

- Summary  
SignUp

#### RequestBody

- application/json

```ts
{
}
```

#### Responses

- 200 Successful response

`application/json`

***

### [POST]/api/v1/auth/login

- Summary  
login

#### RequestBody

- application/json

```ts
{
}
```

#### Responses

- 200 Successful response

`application/json`

***

### [POST]/api/v1/auth/forgetpassword

- Summary  
Forgot Password

#### RequestBody

- application/json

```ts
{
}
```

#### Responses

- 200 Successful response

`application/json`

***

### [POST]/api/v1/auth/verifyResetCode

- Summary  
Verify Reset Password Code

#### RequestBody

- application/json

```ts
{
}
```

#### Responses

- 200 Successful response

`application/json`

***

### [PUT]/api/v1/auth/resetpassword

- Summary  
Reset Password

#### RequestBody

- application/json

```ts
{
}
```

#### Responses

- 200 Successful response

`application/json`

***

### [GET]/api/v1/users/getMe

- Summary  
Get Logged User Data

- Security  
bearerAuth  

#### Responses

- 200 Successful response

`application/json`

***

### [PUT]/api/v1/users/changemypassword

- Summary  
Update Logged User Password

- Security  
bearerAuth  

#### RequestBody

- application/json

```ts
{
}
```

#### Responses

- 200 Successful response

`application/json`

***

### [PUT]/api/v1/users/updateme

- Summary  
Update Logged User Data

- Security  
bearerAuth  

#### RequestBody

- application/json

```ts
{
}
```

#### Responses

- 200 Successful response

`application/json`

***

### [PUT]/api/v1/users/deleteme

- Summary  
Update Logged User Data Copy

- Security  
bearerAuth  

#### RequestBody

- application/json

```ts
{
}
```

#### Responses

- 200 Successful response

`application/json`

***

### [GET]/api/v1/reviews

- Summary  
Get List of reviews

#### Responses

- 200 Successful response

`application/json`

***

### [POST]/api/v1/reviews

- Summary  
Create  Review

- Security  
bearerAuth  

#### RequestBody

- application/json

```ts
{
}
```

#### Responses

- 200 Successful response

`application/json`

***

### [GET]/api/v1/reviews/670c0dbac6f89173cda0ef5b

- Summary  
Get Specific  Review

#### Responses

- 200 Successful response

`application/json`

***

### [PUT]/api/v1/reviews/670ffbe62681d0e5d503db54

- Summary  
Update Specific Review

- Security  
bearerAuth  

#### RequestBody

- application/json

```ts
{
}
```

#### Responses

- 200 Successful response

`application/json`

***

### [DELETE]/api/v1/reviews/671006f4bdd3fd0c6ca068e7

- Summary  
delete Review

- Security  
bearerAuth  

#### Responses

- 200 Successful response

`application/json`

***

### [GET]/api/v1/wishlist

- Summary  
Get Loggeduser WishList

- Security  
bearerAuth  

#### Responses

- 200 Successful response

`application/json`

***

### [POST]/api/v1/wishlist

- Summary  
Add Product To wishList

- Security  
bearerAuth  

#### RequestBody

- application/json

```ts
{
}
```

#### Responses

- 200 Successful response

`application/json`

***

### [DELETE]/api/v1/wishlist/66def32151e816be5bdbea2a

- Summary  
Delete Product From WishList

- Security  
bearerAuth  

#### Responses

- 200 Successful response

`application/json`

***

### [GET]/api/v1/address

- Summary  
Get Loggeduser Addresses

- Security  
bearerAuth  

#### Responses

- 200 Successful response

`application/json`

***

### [POST]/api/v1/address

- Summary  
Add Address

- Security  
bearerAuth  

#### RequestBody

- application/json

```ts
{
}
```

#### Responses

- 200 Successful response

`application/json`

***

### [DELETE]/api/v1/address/6713353ddfd443a9e3195d4b

- Summary  
Delete addresss

- Security  
bearerAuth  

#### Responses

- 200 Successful response

`application/json`

***

### [GET]/api/v1/coupons

- Summary  
Get List of Coupons

- Security  
bearerAuth  

#### Responses

- 200 Successful response

`application/json`

***

### [GET]/api/v1/coupons/67134ed7afc4854866e35c3c

- Summary  
Get Specific Coupon

#### Responses

- 200 Successful response

`application/json`

***

### [PUT]/api/v1/coupons/67134ed7afc4854866e35c3c

- Summary  
Update Specific Brand

- Security  
bearerAuth  

#### RequestBody

- application/json

```ts
{
}
```

#### Responses

- 200 Successful response

`application/json`

***

### [DELETE]/api/v1/coupons/67134ed7afc4854866e35c3c

- Summary  
deleteCategory

- Security  
bearerAuth  

#### Responses

- 200 Successful response

`application/json`

***

### [POST]/api/v1/coupons/

- Summary  
Create Coupon

- Security  
bearerAuth  

#### RequestBody

- application/json

```ts
{
}
```

#### Responses

- 200 Successful response

`application/json`

***

### [GET]/api/v1/products/66def32151e816be5bdbea2a/reviews

- Summary  
Get List of reviews on specific Products

#### Responses

- 200 Successful response

`application/json`

***

### [GET]/api/v1/products/66def32151e816be5bdbea2a/reviews/670c2cf6511faf33168948bc

- Summary  
Get A specific Review on specific Product

#### Responses

- 200 Successful response

`application/json`

***

### [POST]/api/v1/products/66e820de422c2b84a2a742d4/reviews

- Summary  
Create Review in specific product

- Security  
bearerAuth  

#### RequestBody

- application/json

```ts
{
}
```

#### Responses

- 200 Successful response

`application/json`

***

### [POST]/api/v1/cart

- Summary  
Add Product to Cart

- Security  
bearerAuth  

#### RequestBody

- application/json

```ts
{
}
```

#### Responses

- 200 Successful response

`application/json`

***

### [GET]/api/v1/cart

- Summary  
Get Logged in User Cart

- Security  
bearerAuth  

#### Responses

- 200 Successful response

`application/json`

***

### [DELETE]/api/v1/cart/

- Summary  
Remove Specifc Cart Item

- Security  
bearerAuth  

#### Responses

- 200 Successful response

`application/json`

***

### [DELETE]/api/v1/cart/66def32151e816be5bdbea26

- Summary  
Clear User Cart

- Security  
bearerAuth  

#### Responses

- 200 Successful response

`application/json`

***

### [PUT]/api/v1/cart/applycoupon

- Summary  
Aply Coupon To user Cart

- Security  
bearerAuth  

#### RequestBody

- application/json

```ts
{
}
```

#### Responses

- 200 Successful response

`application/json`

***

### [PUT]/api/v1/cart/6714fc6119228ca73e6b3f3f

- Summary  
Update Cart Item Quantity

- Security  
bearerAuth  

#### RequestBody

- application/json

```ts
{
}
```

#### Responses

- 200 Successful response

`application/json`

***

### [POST]/api/v1/orders/67168b6ec979d4f8028d87b5

- Summary  
Create Cash Order

- Security  
bearerAuth  

#### RequestBody

- application/json

```ts
{
}
```

#### Responses

- 200 Successful response

`application/json`

***

### [GET]/api/v1/orders/67168acb305eee14769692f8

- Summary  
Get Specific Order

- Security  
bearerAuth  

#### Responses

- 200 Successful response

`application/json`

***

### [GET]/api/v1/orders/

- Summary  
Get All Orders

- Security  
bearerAuth  

#### Responses

- 200 Successful response

`application/json`

***

### [PUT]/api/v1/orders/67168acb305eee14769692f8/pay

- Summary  
Update Order Status to Paid

- Security  
bearerAuth  

#### RequestBody

- application/json

```ts
{
}
```

#### Responses

- 200 Successful response

`application/json`

***

### [PUT]/api/v1/orders/67168acb305eee14769692f8/deliver

- Summary  
Update Order Status to Deliverd

- Security  
bearerAuth  

#### RequestBody

- application/json

```ts
{
}
```

#### Responses

- 200 Successful response

`application/json`

***

### [GET]/api/v1/orders/checkout-session/6716a507ace4dc490f2fb4b0

- Summary  
Get Checkout Session

- Security  
bearerAuth  

#### Responses

- 200 Successful response

`application/json`

## References

### #/components/securitySchemes/noauthAuth

```ts
{
  "type": "http",
  "scheme": "noauth"
}
```

### #/components/securitySchemes/bearerAuth

```ts
{
  "type": "http",
  "scheme": "bearer"
}
```
