# Rita's Italian Ice (ritas-italian-ice)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Rita's Italian Ice is a Philadelphia-area founded franchise chain of frozen treat shops known for Italian Ice, Frozen Custard, Gelati, and Misto, operating approximately 550-590 locations across the United States under the tagline "Ice Custard Happiness." The brand is privately held under MTY Food Group (acquired 2021). Rita's maintains a consumer-facing loyalty mobile app and a franchise development site, but exposes no public developer API, OpenAPI specification, SDK, webhooks, status page, or developer portal at this time. The loyalty program runs on the third-party Punchh customer engagement platform, and the mobile app was developed with Relevant Mobile; the only network-facing endpoint (api.ritasice.com) is a private backend for the consumer app and returns HTTP 403 to unauthenticated requests.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/ritas-italian-ice/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags

- Restaurants, Food and Beverage, Frozen Desserts, Franchise, Quick Service Restaurant

## Timestamps

- **Modified:** 2026-06-03

## APIs

No APIs have been documented yet. Rita's Italian Ice does not publish a public developer API, OpenAPI specification, SDK, or developer portal. Check back for updates.

## Common Properties

- [Website](https://www.ritasice.com)
- [ContactUs](https://www.ritasice.com/contact/)
- [Careers](https://www.ritasice.com/careers/)
- [Franchise](https://ownaritasfranchise.com/)
- [Rewards](https://www.ritasice.com/rewards/)
- [GiftCards](https://www.ritasice.com/gift-cards)
- [Press](https://www.ritasice.com/press-contact/)
- [Login - Rewards Account Login](https://api.ritasice.com/login)
- [TermsOfService - Loyalty Terms and Conditions](https://www.ritasice.com/loyalty-terms-and-conditions/)
- [Facebook](https://www.facebook.com/RitasItalianIceCompany)
- [Instagram](https://www.instagram.com/ritasice)
- [Twitter](https://twitter.com/ritasitalianice)

## Features

| Name | Description |
|------|-------------|
| Rita's Rewards Loyalty | Consumer loyalty program where guests earn credit per visit and unlock a free treat reward, accessible via the Rita's Ice mobile app, phone number, or email at the point of sale. |
| Mobile App | Native iOS and Android app providing a store locator, rewards tracking, mobile check-in, and personalized offers. |
| Store Locator | Find Rita's locations across the United States, surfaced in the mobile app and on the public website. |

## Use Cases

| Name | Description |
|------|-------------|
| Earn and Redeem Rewards | Guests present the mobile app, phone number, or email at checkout to earn visit credit and redeem a free Italian Ice, Frozen Custard, or Gelati reward. |
| Find a Location | Customers locate nearby Rita's shops using the in-app and website store locator. |
| Own a Franchise | Prospective franchisees research and apply to operate a Rita's Italian Ice location through the franchise development site. |

## Integrations

| Name | Description |
|------|-------------|
| Punchh | Cloud-based customer loyalty and engagement platform powering the Rita's Rewards program and its point-of-sale integration. Third-party vendor; Rita's exposes no public API for this integration. |
| Relevant Mobile | Mobile app development partner behind the revamped Rita's Ice app, including beacon-based targeting and social check-in features. |
| Apple App Store | Distribution channel for the Rita's Ice iOS app (apps.apple.com/us/app/ritas-ice/id532627057). |
| Google Play | Distribution channel for the Rita's Ice Android app (play.google.com/store/apps/details?id=com.app.ritas). |

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
