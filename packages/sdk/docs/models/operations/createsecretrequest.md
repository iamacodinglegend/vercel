# CreateSecretRequest

## Example Usage

```typescript
import { CreateSecretRequest } from "@vercel/sdk/models/operations/createsecret.js";

let value: CreateSecretRequest = {
  name: "my-api-key",
  requestBody: {
    name: "my-api-key",
    value: "some secret value",
    decryptable: true,
  },
};
```

## Fields

| Field                                                                                    | Type                                                                                     | Required                                                                                 | Description                                                                              | Example                                                                                  |
| ---------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------- |
| `teamId`                                                                                 | *string*                                                                                 | :heavy_minus_sign:                                                                       | The Team identifier to perform the request on behalf of.                                 |                                                                                          |
| `slug`                                                                                   | *string*                                                                                 | :heavy_minus_sign:                                                                       | The Team slug to perform the request on behalf of.                                       |                                                                                          |
| `name`                                                                                   | *string*                                                                                 | :heavy_check_mark:                                                                       | The name of the secret.                                                                  | my-api-key                                                                               |
| `requestBody`                                                                            | [operations.CreateSecretRequestBody](../../models/operations/createsecretrequestbody.md) | :heavy_minus_sign:                                                                       | N/A                                                                                      |                                                                                          |