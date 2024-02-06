---
title: Val Town Newsletter 15
description: TODO
pubDate: February 06, 2024
author: Steven Krouse
---

TODO description

You all have made hundreds of really cool vals (links below). [Come join us in Discord!](https://discord.gg/dHv45uN5RY) 👋

### Custom domains

We released a heavily requested feature - custom domains. Custom domains allow you to use your own domain names to access the HTTP vals you created. This feature enables a more branded and professional experience for users visiting your vals. This is a feature for [Pro subscribers](https://www.val.town/pricing) only.

![A custom domain configured to direct HTTP requests to "amazingVal"](./val-town-newsletter-15/custom-domains.png)

You can add your domain or subdomain in the [custom domain settings](https://www.val.town/settings/domains). For more info take a look at our [documentation page](https://docs.val.town/reference/custom-domains/).

Big thanks to [SaaS Custom Domains](https://saascustomdomains.com/) for making the implementation much easier.

### Logs – larger, faster, streamed, and scalable

TODO description and photo

clickhouse

- TODO link & close: https://github.com/val-town/val-town-product/discussions/30

### Early Return HTTP Responses

- (TODO fix this title)
- link to the discussion
- and the discord announcement? https://discord.com/channels/1020432421243592714/1020432421243592717/1201996373013319690

### HTTP vals faster by 100ms ⚡️

- Tom could make a chart about this

### Suggest & vote on feature requests

on GitHub Discussions

The description of the discussions for feature-requests on GitHub [Discussions](https://github.com/val-town/val-town-product/discussions)

https://x.com/stevekrouse/status/1744721315024802285?s=20

### Val Town status page

https://x.com/Andre_Terron/status/1750578181600649312?s=20

- was this requested on discord or in a discussion?

### TypeScript-driven autocompletion

https://github.com/val-town/val.town/pull/3645

### CodeMirror Continue for comments

https://x.com/tmcw/status/1745147192656957771?s=20

### Improved Feedback button

https://x.com/stevekrouse/status/1749800319217700990?s=20

### Add code folding

- TODO ensure we closed this github discussion and link to it here

### Misc updates

- Fixed the big, old, annoying flicker on page load
- Redesigned our scheduled val & cron UI
- "Run Now" button on scheduled and cron vals
- Tabs on the bottom of vals for viewing logs and previewing HTTP vals
- Fix flicker bug with our AI autocomplete
- New comments on a val notify anyone who commented on that val
- HTTP responses can return up to 10Mb now (40x more than before)
- Val readmes can be edited via API
- Add URL ?search data to HTTP logs
- Updated Deno to 1.40.2 (there's now [an API for getting this version data](https://www.val.town/v/std/deno_version)!)
- Fix [val.town/brand](https://val.town/brand) assets
- Defer loading dprint to speed up page loading times
- Fix scheduled val bugs
- Include val readmes in val pull requests
- Add `VALTOWN_API_URL` environment variable to enable std library usage locally
- Deprecate showing output in favor of console logs
- Forked vals default to the name of the original val
- Renamed "Secrets" to "Environment Variables"
- Improved error message to when users try to preview a private HTTP val
- Speed up querying for the latest evaluation of a val (4 seconds to 40ms)
- [Halved our database size](https://x.com/tmcw/status/1742559580255658462?s=20) by removing stale data
- iframe previews of other peoples' HTTP vals are closed by default
- Disable grammarly correction in the editor
- [Improved Google indexing by adding pagination and noindex on vals without readmes](https://x.com/tmcw/status/1753458573764337783?s=20) (thanks [@tomcritchlow](https://www.val.town/u/tomcritchlow))
- Limit the number of versions a val can have to 14,400 (10 days in minutes)
- Fix bugs with our homepage buttons

### Roadmap

#### Feburary

- AI autocomplete improvements
- Improved val run scalability and pricing
- Improved workflows for POST-request HTTP vals
- Improved /trending ranking
- Button to request someone to publish a val
- Job posting & careers page
- New intro video
- Better onboarding for new users
- Drop "untitled\_" from new val names

### Soon-ish

- Speed up val execution
- Improved val organization in sidebar (TODO link to feature request)
- Val Town Projects (for more complex projects, branching and pull requests as groups of vals)
- TODO pull more from feature requests

## Kind words

- https://x.com/meekaale/status/1740818276152996271?s=20
- https://x.com/spences10/status/1741090256852586689?s=20
- https://x.com/ibuildthecloud/status/1742565036944740660?s=20
- https://x.com/arsalanbashir/status/1742830957374144658?s=20
- https://x.com/GrantSlatton/status/1743441341030486256?s=20
- https://x.com/alexzirbel/status/1744595109101101346?s=20
- https://x.com/rossSpeak/status/1744864326727737363?s=20
- https://x.com/CompuIves/status/1745400326654706144?s=20
- https://x.com/rossSpeak/status/1747310275773296841?s=20
- https://x.com/zeke/status/1748107363419332698?s=20
- https://x.com/IrvinZhan/status/1748079715515339074?s=20
- https://x.com/whelan_boyd/status/1722299311608807710?s=20
- https://x.com/glcst/status/1742554321965691324?s=20
- https://x.com/webtwozero/status/1750528451059368408?s=20
- https://x.com/okpasquale/status/1750653517629473014?s=20
- https://x.com/albfresco/status/1740955772144738738?s=20
- https://x.com/nerdymomocat/status/1743041429331689901?s=20

### Cool vals

- [@pomdtr](https://www.val.town/u/pomdtr) made a val that [serves VSCode](https://www.val.town/v/pomdtr/vscode)
- [@saolsen](https://www.val.town/u/saolsen) created a val for [tracing with OpenTelemetry](https://www.val.town/v/saolsen/tracing)
- [@pomdtr](https://www.val.town/u/pomdtr) kept updating his [Val Town VSCode extension](https://marketplace.visualstudio.com/items?itemName=pomdtr.valtown) so that now it allows to manage/edit blobs, query SQLite tables, edit readmes and a lot more
- [@saolsen](https://www.val.town/u/saolsen) explored the idea of [writing vals in Rust with WASM](https://gist.github.com/saolsen/d273bb1baba5e912e4dc2b187511affa)
- [@todepond](https://www.val.town/u/todepond) wrote about [making his supported dashboard using Val Town](https://todepond.com/wikiblogarden/tadi-web/fame/facts/)
- [@pomdtr](https://www.val.town/u/pomdtr) created a val that [creates screenshots from another val](https://www.val.town/v/pomdtr/val2img)
- [@saolsen](https://www.val.town/u/saolsen) created a [val version diff viewer](https://www.val.town/v/saolsen/changes)
- [@saolsen](https://www.val.town/u/saolsen) implemented [val analytics with Plausible](https://www.val.town/v/saolsen/plausible)
- [@pomdtr](https://www.val.town/u/pomdtr) created a [Chrome extension for Val Town](https://github.com/pomdtr/val-town-web-extension)
- [@pomdtr](https://www.val.town/u/pomdtr) implemented [JWT authentication utility](https://www.val.town/v/pomdtr/auth_middleware) to protect your APIs
- [@xkonti](https://www.val.town/u/xkonti) created a [GPT Action Framework](https://www.val.town/v/xkonti/gptApiFramework) for simplifying creation of APIs compatible with OpenAI GPTs
- [@saolsen](https://www.val.town/u/saolsen) created a Deno script that will [sync your vals to GitHub](https://www.val.town/v/saolsen/git_sync)
- [@pomdtr](https://www.val.town/u/pomdtr) ported [blakeembrey/sql-template-tag](https://github.com/blakeembrey/sql-template-tag) to Val Town to simplify [building safe SQL queries](https://www.val.town/v/pomdtr/sql)
- [@saolsen](https://www.val.town/u/saolsen) experimented with [writing tests with Jest ](https://www.val.town/v/saolsen/tiny_jest_example)
- [@pomdtr](https://www.val.town/u/pomdtr) found a way to [serve static content by using val's readme]()https://www.val.town/v/pomdtr/notebook
- [@stevekrouse](https://www.val.town/u/stevekrouse) wrote a whole fullstack (sqlite, backend js, frontend js, html) app in a [single val](https://www.val.town/v/stevekrouse/backend_in_a_file)
- [@saolsen](https://www.val.town/u/saolsen) wrote a useful [val that can automatically prune multiple versions of other vals](https://www.val.town/v/saolsen/prune_val)
- [@nbbaier](https://www.val.town/u/nbbaier) created a [val that can generate SQL](https://www.val.town/v/nbbaier/sqliteWriter) using [prisma-gpt](https://github.com/aliyeysides/prisma-gpt)
- [@nbbaier](https://www.val.town/u/nbbaier) made a val that [generates readme for vals automatically](https://www.val.town/v/nbbaier/readmeGPT) using GPT
- [@nbbaier](https://www.val.town/u/nbbaier) wrote a [Perplexity AI API wrapper val](https://www.val.town/v/nbbaier/perplextiyAPI)

---

To organize:

- https://x.com/deepfates/status/1751015063912399126?s=20
- https://x.com/tmcw/status/1744406760301920559?s=20
- https://x.com/stevedylandev/status/1745667977393910096?s=200
- https://x.com/stevekrouse/status/1747365282547478828?s=20
- https://x.com/nbbaier/status/1748564488029147417?s=20
- https://x.com/nbbaier/status/1748564489375502417?s=20
- https://x.com/glcst/status/1749888541612544292?s=20
- https://x.com/stevekrouse/status/1737173486047481887?s=20
- https://x.com/stevekrouse/status/1738651539458171255?s=20
- https://x.com/nbbaier/status/1744847782484070400?s=20
- https://discord.com/channels/1020432421243592714/1020432421243592717/1201507447425208442
- https://discord.com/channels/1020432421243592714/1020432421243592717/1201259951742521496
- https://discord.com/channels/1020432421243592714/1020432421243592717/1199745917293703228
- https://www.val.town/v/tomcritchlow/tom_og
-
