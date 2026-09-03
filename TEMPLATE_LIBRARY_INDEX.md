# 30-Workflow n8n Template Library — Master Index

> **Library truth:** 30 configurable n8n template repositories. They are **not** thirty verified production deployments. Every repository contains a `TEMPLATE_STATUS.md` verification/security control.

## Sales / lead operations

- [lead-scoring-automation](https://github.com/oyekola-ololade/lead-scoring-automation)
- [email-lead-openai-airtable](https://github.com/oyekola-ololade/email-lead-openai-airtable)
- [multi-source-lead-aggregator](https://github.com/oyekola-ololade/multi-source-lead-aggregator)
- [sms-lead-qualification-email](https://github.com/oyekola-ololade/sms-lead-qualification-email)
- [whatsapp-lead-ai-scoring-slack](https://github.com/oyekola-ololade/whatsapp-lead-ai-scoring-slack)
- [website-form-qualification-calendar](https://github.com/oyekola-ololade/website-form-qualification-calendar)
- [linkedin-autoreply-crm](https://github.com/oyekola-ololade/linkedin-autoreply-crm)

## Email / support / inquiry workflows

- [email-segmentation-automation](https://github.com/oyekola-ololade/email-segmentation-automation) — **known branching repair required**
- [email-sentiment-ai-response](https://github.com/oyekola-ololade/email-sentiment-ai-response)
- [email-ticket-autorouter](https://github.com/oyekola-ololade/email-ticket-autorouter)
- [multi-channel-inquiry-unifier](https://github.com/oyekola-ololade/multi-channel-inquiry-unifier)
- [whatsapp-support-bot](https://github.com/oyekola-ololade/whatsapp-support-bot)
- [chat-transcript-summary](https://github.com/oyekola-ololade/chat-transcript-summary)

## Ecommerce / customer operations

- [cart-abandonment-sequence](https://github.com/oyekola-ololade/cart-abandonment-sequence)
- [csv-product-upload-shopify](https://github.com/oyekola-ololade/csv-product-upload-shopify)
- [inventory-alert-system](https://github.com/oyekola-ololade/inventory-alert-system)
- [order-status-whatsapp](https://github.com/oyekola-ololade/order-status-whatsapp)
- [returns-refunds-processor](https://github.com/oyekola-ololade/returns-refunds-processor)
- [shopify-invoice-email-whatsapp](https://github.com/oyekola-ololade/shopify-invoice-email-whatsapp)

## Content / publishing / social

- [content-calendar-organizer](https://github.com/oyekola-ololade/content-calendar-organizer)
- [linkedin-auto-publisher](https://github.com/oyekola-ololade/linkedin-auto-publisher) — **legacy LinkedIn API + pseudo-wait compatibility issue documented**
- [subscriber-social-sync](https://github.com/oyekola-ololade/subscriber-social-sync)
- [tweet-scheduler-engagement](https://github.com/oyekola-ololade/tweet-scheduler-engagement)

## Data / reporting / internal operations

- [data-validation-cleanup](https://github.com/oyekola-ololade/data-validation-cleanup)
- [db-query-slack-report](https://github.com/oyekola-ololade/db-query-slack-report)
- [feedback-sentiment-dashboard](https://github.com/oyekola-ololade/feedback-sentiment-dashboard)
- [googleforms-ai-notion](https://github.com/oyekola-ololade/googleforms-ai-notion)
- [googlesheets-ai-report](https://github.com/oyekola-ololade/googlesheets-ai-report)
- [multi-source-data-aggregator](https://github.com/oyekola-ololade/multi-source-data-aggregator)
- [slack-command-task-creation](https://github.com/oyekola-ololade/slack-command-task-creation)

## Standard repository contract

Each template repository should expose:

```text
README.md
INDEX.md
TEMPLATE_STATUS.md
workflow/<template>.json
evidence/
├── demo/README.md
└── screenshots/README.md
```

`INDEX.md` is navigation. `TEMPLATE_STATUS.md` is the verification/security authority. The evidence folders remain visible placeholders until genuine configured evidence exists.

## Verification gate before stronger claims

A template is not promoted from `CONFIGURABLE TEMPLATE` to `VERIFIED CONFIGURED BUILD` until:

1. JSON imports into the target n8n version;
2. graph/connections are valid;
3. expressions evaluate correctly;
4. third-party API versions/permissions are current;
5. credentials/placeholders are configured safely;
6. a success case executes;
7. a malformed/failure case behaves safely;
8. side effects are checked for duplication/idempotency where relevant;
9. evidence is added to demo/screenshots folders with date/environment.

## Known library-wide evidence boundary

The underlying 30 workflow JSONs are structurally meaningful template assets, but fresh configured-live-run evidence is not available for all thirty. Older provider/model assumptions should not be silently modernized without tests.