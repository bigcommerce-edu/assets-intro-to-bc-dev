# Storefront APIs

## GraphQL Storefront API

**Request with token:**

```
POST https://mystore.com/graphql
Authorization: Bearer <storefront_token>
Accept: application/json
Content-Type: application/json
```

**Request with customer context:**

```
POST https://mystore.com/graphql
Authorization: Bearer <storefront_token>
X-Customer-Access-Token: <access_token>
Accept: application/json
Content-Type: application/json
```

**Canonical URL endpoint:**

```
https://store-<store_hash>-<channel_id>.mybigcommerce.com/graphql
```

## B2B GraphQL Storefront API

**Request with token:**

```
POST https://api-b2b.bigcommerce.com/graphql
Authorization: Bearer <user_token>
Accept: application/json
Content-Type: application/json
```

## Storefront and Authentication APIs for Stencil

**REST Storefront API:**

```
GET https://mystore.com/api/storefront/carts
Accept: application/json
Content-Type: application/json
```
