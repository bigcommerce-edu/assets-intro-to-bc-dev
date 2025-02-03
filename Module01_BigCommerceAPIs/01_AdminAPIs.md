# Admin APIs

## REST Admin APIs

**Request with token:**

```
GET https://api.bigcommerce.com/stores/<store_hash>/v3/catalog/products
X-Auth-Token: <access_token>
Accept: application/json
```

## Payments API

**Request with PAT:**

```
POST https://payments.bigcommerce.com/stores/<store-hash>/payments
X-Auth-Token: <access_token>
Authorization: PAT <payment_access_token>
Accept: application/vnd.bc.v1+json
Content-Type: application/json
```

## GraphQL Admin API

**Request with token:**

```
POST https://api.bigcommerce.com/stores/<store_hash>/graphql
X-Auth-Token: <access_token>
Accept: application/json
Content-Type: application/json
```

## B2B REST Management API

**Request with token:**

```
GET https://api-b2b.bigcommerce.com/api/v3/io/companies
authToken: <access-token>
Accept: application/json
```

[Next](./02_StorefrontAPIs.md)
