# Cold Email Fails at DNS, Not Copy

Your cold email is not failing because of bad copy.

It is failing because your DNS is a mess.

Here is what 2026 data from 31 million cold emails tells us: roughly 1 in 6 legitimate emails never reaches the inbox.

Not the spam folder. Not promotions. Just gone.

The culprit in most cases? A domain with no DMARC policy, a broken SPF record, or DKIM that was configured once and never checked again.

Your email copy could be Ogilvy level. Does not matter. No amount of clever copy can save a weak infrastructure.

## The non-negotiable technical floor

Before you send a single sequence:

- **SPF** tells inbox providers which servers are authorized to send for your domain.
- **DKIM** signs each message so providers know it was not tampered with in transit.
- **DMARC** tells them what to do when both checks fail (hint: `reject` is the answer).

## The warmup step most SDRs skip

New sending domains need 4-6 weeks of gradual warmup, starting at 5-10 emails per day.

Erratic volume:

- 500 Monday, zero Tuesday, 1000 Friday

...looks like a spam operation to every major ESP.

Google enforces a spam complaint threshold of 0.1%. Hit it, and your domain stops reaching Gmail inboxes entirely.

Your deliverability is not a marketing problem. It is a DNS record problem.

Fix the infrastructure first. Write the copy second.

## Discussion prompt

What is the dumbest deliverability mistake you have seen on a real campaign?

Drop it below. I will go first: a company using a Gmail address to cold email 2,000 prospects. No custom domain. No SPF. Just vibes.
