# snowflake_2025

Library to generate unique Snowflake IDs for distributed systems.

## Installation

```bash
npm install @theinternetfolks/snowflake
```

## Usage

```javascript
import { Snowflake } from "@theinternetfolks/snowflake";

// Simple generation
console.log(Snowflake.generate());
// 6917062538869867520

// With options
console.log(Snowflake.generate({ timestamp: 1649156222074, shard_id: 4 }));
// 6917065950617407488
```

## License

[MIT](https://choosealicense.com/licenses/mit/)
