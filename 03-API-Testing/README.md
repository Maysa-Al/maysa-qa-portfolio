# API Testing

This section demonstrates my approach to API testing using Postman, including positive, negative, validation, and boundary testing.

## API Testing Coverage

- Request validation
- Response validation
- HTTP status code validation
- Request body validation
- Response body validation
- Required field validation
- Data type validation
- Positive testing
- Negative testing
- Boundary testing
- Authentication and authorization
- Error handling
- Business rule validation

## Example API

### Create Order

**Method:** POST

**Endpoint:**

`/api/orders`

### Sample Request

```json
{
  "customerId": "CUST-1001",
  "productId": "PROD-2001",
  "quantity": 2
}
