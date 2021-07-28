# Strapi application

backend with Strapi

## graphql
http://localhost:1337/graphql

```graphql

query GetReviews {
  reviews {
    title,
    id,
    rating,
    body,
  }
}
`