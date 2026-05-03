# TradeStation

TradeStation is a financial brokerage and trading platform offering RESTful brokerage and market data services for building trading applications for stocks, options, futures, and cryptocurrency. The API supports account management, order execution, real-time and historical market data, option chains, and HTTP streaming.

**URL:** [apis.yml](https://raw.githubusercontent.com/api-evangelist/tradestation/refs/heads/main/apis.yml)

## Tags

- Brokerage
- Cryptocurrency
- Finance
- Futures
- Market Data
- Options
- Stocks
- Trading

## APIs

### TradeStation API

RESTful brokerage and market data API covering accounts, orders, quotes, bar charts, options, symbols, and reference data. Supports OAuth2 authentication with production and simulator environments.

**Human URL:** [https://api.tradestation.com/docs/](https://api.tradestation.com/docs/)

**Base URL:** https://api.tradestation.com

#### Tags

- Accounts
- Brokerage
- Cryptocurrency
- Market Data
- Options
- Order Execution
- Stocks
- Trading

#### Properties

| Type | URL |
|------|-----|
| Documentation | [https://api.tradestation.com/docs/](https://api.tradestation.com/docs/) |
| OpenAPI | [openapi/tradestation-api-openapi.yml](openapi/tradestation-api-openapi.yml) |
| AsyncAPI | [asyncapi/tradestation-streaming-asyncapi.yml](asyncapi/tradestation-streaming-asyncapi.yml) |
| JSON Schema | [json-schema/tradestation-order-schema.json](json-schema/tradestation-order-schema.json) |
| JSON Structure | [json-structure/tradestation-order-structure.json](json-structure/tradestation-order-structure.json) |
| JSON-LD | [json-ld/tradestation-context.jsonld](json-ld/tradestation-context.jsonld) |
| Spectral Rules | [rules/tradestation-rules.yml](rules/tradestation-rules.yml) |
| Vocabulary | [vocabulary/tradestation-vocabulary.yml](vocabulary/tradestation-vocabulary.yml) |
| GitHub | [https://github.com/tradestation](https://github.com/tradestation) |
| API Specification | [https://tradestation.github.io/api-docs/](https://tradestation.github.io/api-docs/) |

### TradeStation Streaming API

Real-time HTTP streaming for market data and brokerage events using chunked transfer encoding with newline-delimited JSON.

**Human URL:** [https://api.tradestation.com/docs/](https://api.tradestation.com/docs/)

#### Properties

| Type | URL |
|------|-----|
| AsyncAPI | [asyncapi/tradestation-streaming-asyncapi.yml](asyncapi/tradestation-streaming-asyncapi.yml) |

## Capabilities

### Trading and Market Data

Unified trading and market data workflow covering account management, order execution, real-time quotes, historical bar data, and options analysis.

| File | Description |
|------|-------------|
| [capabilities/trading-and-market-data.yaml](capabilities/trading-and-market-data.yaml) | Workflow capability: 17 MCP tools for trading and market data |
| [capabilities/shared/tradestation-api.yaml](capabilities/shared/tradestation-api.yaml) | Shared per-API consumed definition |

## Examples

| File | Description |
|------|-------------|
| [examples/tradestation-get-quotes-example.json](examples/tradestation-get-quotes-example.json) | Get Quotes request/response example |
| [examples/tradestation-place-order-example.json](examples/tradestation-place-order-example.json) | Place Order request/response example |

## Common Properties

| Type | URL |
|------|-----|
| Website | [https://www.tradestation.com](https://www.tradestation.com) |
| Developer | [https://developer.tradestation.com](https://developer.tradestation.com) |
| Documentation | [https://api.tradestation.com/docs/](https://api.tradestation.com/docs/) |
| Authentication | [https://api.tradestation.com/docs/fundamentals/authentication/](https://api.tradestation.com/docs/fundamentals/authentication/) |
| GitHub | [https://github.com/tradestation](https://github.com/tradestation) |
| Rate Limiting | [https://api.tradestation.com/docs/fundamentals/rate-limiting/](https://api.tradestation.com/docs/fundamentals/rate-limiting/) |
| Terms of Service | [https://www.tradestation.com/important-information/](https://www.tradestation.com/important-information/) |

---
*Maintained by Kin Lane (kin@apievangelist.com)*
