# Watch list ledger

`ledger.json` is the buying desk's authoritative list of SKUs under price watch.

Fields per entry:

| field      | meaning                                                   |
|------------|-----------------------------------------------------------|
| sku        | product SKU                                               |
| title      | product title as shown on the product page                |
| seller     | seller shown on the product page                          |
| url        | customer-facing page for the SKU                          |
| last_price | most recent selling price recorded for the SKU (USD)      |
| status     | review status (`ok`, `escalate`, `markdown`, `new`)       |

The previous review baseline is the `snapshot-a` branch of this repository.
