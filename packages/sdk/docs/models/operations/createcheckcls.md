# CreateCheckCLS

## Example Usage

```typescript
import { CreateCheckCLS } from "@vercel/sdk/models/operations/createcheck.js";

let value: CreateCheckCLS = {
  value: 1103.75,
  source: "web-vitals",
};
```

## Fields

| Field                                                                                                    | Type                                                                                                     | Required                                                                                                 | Description                                                                                              |
| -------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------- |
| `value`                                                                                                  | *number*                                                                                                 | :heavy_check_mark:                                                                                       | N/A                                                                                                      |
| `previousValue`                                                                                          | *number*                                                                                                 | :heavy_minus_sign:                                                                                       | N/A                                                                                                      |
| `source`                                                                                                 | [operations.CreateCheckChecksResponseSource](../../models/operations/createcheckchecksresponsesource.md) | :heavy_check_mark:                                                                                       | N/A                                                                                                      |