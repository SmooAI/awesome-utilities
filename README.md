# awesome-utilities
A list of utilities I don't want to forget.

## [cli53](https://github.com/barnybug/cli53)
`cli53` is a command-line tool for managing Amazon Route 53 DNS, making it easy to import and export zones in BIND format, create and manage hosted zones, and add, update, or delete DNS records—including advanced types like failover, latency-based, weighted, geolocation, and ALIAS records. It also supports reusable delegation sets and integrates with AWS profiles and role-based authentication, enabling streamlined automation, migration, and reliable DNS management directly from the terminal.

## [@alcyone-labs/zod-to-json-schema](https://www.npmjs.com/package/@alcyone-labs/zod-to-json-schema)
`@alcyone-labs/zod-to-json-schema` is a fork of [`zod-to-json-schema`](https://www.npmjs.com/package/zod-to-json-schema) that supports zod v4. This may not be necessary once/if [this issue](https://github.com/StefanTerdell/zod-to-json-schema/issues/173) is resolved. Zod v4 [supports JSON Schema](https://zod.dev/json-schema) by default, but it is much more stringent than [`zod-to-json-schema`](https://www.npmjs.com/package/zod-to-json-schema) was on what it supports. It does not support z.date(), anything with z.transform(), or z.custom() for instance.
