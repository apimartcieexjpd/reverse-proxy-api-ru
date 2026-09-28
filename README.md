# reverse-proxy-api-ru — API шлюз (Русский)

> **One OpenAI-compatible key, 300+ models** · image2.5 **$0.0085/image** · Seedance 2.0 Mini **$0.01056/sec** · LLM from **$0.0228 / M tokens** · $1 minimum top-up.

**[Смотреть цены](https://go.apimart.ai/k-7bf10d)** · **[Получить API-ключ](https://go.apimart.ai/k-9b7359)**

reverse-proxy-api-ru — один `base_url` и один ключ ко более чем 300 моделям. Расчёты в USD, оплата по факту, минимальный платёж $1.

### реверс-инжиниринг / reverse-engineered routes

reverse-proxy-api-ru объединяет маршруты **реверс-инжиниринг** и официальные: ID с суффиксом `-ext` — это обратный маршрут, остальные модели идут официально по сниженной цене. Один ключ на всё.

## Published unit prices (snapshot 2026-09-28)

| Unit | Price |
| --- | --- |
| `GPT Image 2.5 (1K)` | $0.0085 |
| `Seedance 2.0 Mini (480P/sec)` | $0.01056 |
| `Qwen3.7 Flash (per M input)` | $0.0228568 |

## Quickstart

```bash
curl -X POST https://api.apimart.ai/v1/images/generations \
  -H 'Authorization: Bearer $APIMART_KEY' \
  -H 'Content-Type: application/json' \
  -d '{"model":"gpt-image-2.5-ext","prompt":"cozy reading nook, warm lamp, cinematic","size":"1:1","resolution":"1K","n":1}'
```

Async: submit → get `task_id` → poll `GET https://api.apimart.ai/v1/tasks/<task_id>` → read `cost` / `credits_cost` from the result. Parameter tables, `version`/`resolution`/`size` options and idempotency headers are documented on the model page reachable from the pricing link above.

## Keywords

`реверс-инжиниринг` · `reverse-engineered` · `API шлюз` · `API релей` · `nano banana 2 api` · `gpt-image-2.5 api` · `ai api pricing` · `pay-as-you-go`

## Platform facts

- USD settlement, pay-as-you-go, **$1 minimum top-up**, no subscription.
- Operating since last year; ~100,000 registered users, mostly enterprise accounts.
- International invoices available on request.
- 307 models online (live `/v1/models`) as of 2026-09-28.

## Disclosure

This repository documents **APIMart**, a third-party API aggregator/gateway. It is **not affiliated with, endorsed by, or sponsored by** OpenAI, Google, Anthropic, xAI, ByteDance or any model vendor. Model names and trademarks belong to their owners. Prices are a point-in-time snapshot and may change; the vendor's console billing is authoritative.

