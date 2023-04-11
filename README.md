# Awesome Middleware [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

Curated list of middleware resources.

## Middleware

| Name                                                                                         | Description                                        | Target                                                                                                                                                       |
| -------------------------------------------------------------------------------------------- | -------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| [etag-middleware](https://github.com/httpland/etag-middleware)                               | HTTP ETag middleware                               | [ETag](https://www.rfc-editor.org/rfc/rfc9110.html#section-8.8.3)                                                                                            |
| [hsts-middleware](https://github.com/httpland/hsts-middleware)                               | HTTP Strict Transport Security(HSTS) middleware    | [Strict-Transport-Security](https://www.rfc-editor.org/rfc/rfc6797)                                                                                          |
| [compression-middleware](https://github.com/httpland/compression-middleware)                 | HTTP compression middleware                        | <ul><li>HTTP Content</li><li> Content-Encoding</li><li>Vary</li><li>Content-Length</li></ul>                                                                 |
| [range-request-middleware](https://github.com/httpland/range-request-middleware)             | HTTP range request middleware                      | <ul><li>HTTP Content </li><li>Accept-Ranges</li><li>Content-Range</li> <li>Content-Type</li><li>Status 206</li><li>Status 416</li> </ul>                     |
| [conditional-request-middleware](https://github.com/httpland/conditional-request-middleware) | HTTP conditional request middleware                | <ul><li>HTTP Content</li><li> [Representaion headers](https://www.rfc-editor.org/rfc/rfc9110.html#section-8)</li><li>Status 206</li><li>Status 412</li></ul> |
| [xcto-middleware](https://github.com/httpland/xcto-middleware)                               | HTTP XCTO(X-Content-Type-Options) middleware       | X-Content-Type-Options                                                                                                                                       |
| [corp-middleware](https://github.com/httpland/corp-middleware)                               | HTTP cross-origin resource policy(CORP) middleware | Cross-Origin-Resource-Policy                                                                                                                                 |
| [referrer-policy-middleware](https://github.com/httpland/referrer-policy-middleware)         | HTTP referrer policy middleware                    | Referrer-Policy                                                                                                                                              |
| [coep-middleware](https://github.com/httpland/coep-middleware)                               | HTTP cross-origin embedder policy(COEP) middleware | <ul><li>Cross-Origin-Embedder-Policy</li><li>Cross-Origin-Embedder-Policy-Report-Only</li></ul>                                                              |
| [coop-middleware](https://github.com/httpland/coop-middleware)                               | HTTP cross-origin opener policy(COOP) middleware   | <ul><li>Cross-Origin-Opener-Policy</li><li>Cross-Origin-Opener-Policy-Report-Only</li></ul>                                                                  |
| [csp-middleware](https://github.com/httpland/csp-middleware)                                 | HTTP content security policy(CSP) middleware       | <ul><li>Content-Security-Policy</li><li>Content-Security-Policy-Report-Only</li></ul>                                                                        |

## License

Copyright © 2023-present [httpland](https://github.com/httpland).

Released under the [MIT](./LICENSE) license
