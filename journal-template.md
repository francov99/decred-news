# {DRAFT} Decred Journal – {month} {year}

![{alt text}](../img/{file.jpg} "{hover tooltip text}")

_Image: {"$title by $author. $optional-description" for artwork, "$description" for photos}_

{ introduction, major news of the month ordered by impact, don't put any links here }

## Development

Unless otherwise noted, the work reported here has the "merged to master" status. It means that the work is completed, reviewed, and integrated into the source code that advanced users can build and run, but is not yet available in release binaries for regular users.

{ hint: add below overview of activity for each project. add any other project that warrants a paragraph, drop projects without notable updates. for each project the order of reporting is: changes released > merged to master > started work > discussions and future plans }

[dcrd](https://github.com/decred/dcrd): {}

[dcrwallet](https://github.com/decred/dcrwallet): {}

[dcrctl](https://github.com/decred/dcrctl): {}

[Decrediton](https://github.com/decred/decrediton): {}

[Politeia](https://github.com/decred/politeia): {}

[vspd](https://github.com/decred/vspd): {}

[dcrstakepool](https://github.com/decred/dcrstakepool): {}

[dcrpool](https://github.com/decred/dcrpool): {}

[dcrlnd](https://github.com/decred/dcrlnd): {}

[cspp](https://github.com/decred/cspp): {}

[dcrdex](https://github.com/decred/dcrdex): {}

[dcrandroid](https://github.com/planetdecred/dcrandroid): {}

{ also check the base library https://github.com/planetdecred/dcrlibwallet }

[dcrios](https://github.com/planetdecred/dcrios): {}

[godcr](https://github.com/planetdecred/godcr): {}

[dcrdata](https://github.com/decred/dcrdata): {}

[tinydecred](https://github.com/decred/tinydecred): {}

[docs](https://github.com/decred/dcrdocs): {}

[decred.org](https://github.com/decred/dcrweb): {}

Other:

- { smaller items go here }

Dev activity stats for {month}: {n} active PRs, {n} master commits, {n}K added and {n}K deleted lines spread across {n} repositories. Contributions came from {n}-{n} developers per repository.

## People

{ hint: list people who made meaningful commits merged in master branches, in alphabetical order }

Welcome to new first time contributors with code merged to master: {@handle} ([{repo}]({link to user's commits})), ...

Congratulations to new contractors granted the Decred Contractor Clearance (DCC): [{@handle}]({link to most relevant account}). { hint: check the CMS }

{ welcome new corporate contractors with short intros, if any }

{ updates from existing contractors }

{ interviews about people }

Community stats as of {date}:

- Politeia users: {} (+{})
- Twitter followers: {} (+{})
- Reddit subscribers: {} (+{})
- Matrix #general users: {} (+{})
- Discord users: {}, verified to post: {}
- Telegram users: {} (+{})
- YouTube subscribers: {} (+{}), views: {} (+{})
- LinkedIn followers: {} (+{})
- GitHub dcrd stars: {} (+{}), forks: {} (+{})

## Governance

In {month} the [Treasury](https://explorer.dcrdata.org/address/Dcur2mcGjmENx4DhNqDctW5wJCVyT3Qeqkx) received {n} DCR and spent {n} DCR. Using {month}'s daily average DCR/USD rate of ${n.nn}, this is ${n}K received and ${n}K spent. At {prev month}'s average daily rate of ${n.nn}, the USD figure billed for work completed in that month is ${n}K. As of {date}, Treasury balance is {n} DCR ({n.nn} million USD at ${n.nn}).

{ high level recap of decision-making activity and most important events. link to Politeia Digest for higher detail }

## Network

{ section hint:

- check dcrdata.org (preferred), dcrstats.com and charts.dcr.farm to get the numbers
- use the same `zoom` parameter for all dcrdata links }

Hashrate: {month}'s [hashrate](https://explorer.dcrdata.org/charts?chart=hashrate&zoom=t1-t2&scale=linear&bin=block&axis=time) {set zoom to show the month} opened at ~{n} Ph/s and closed ~{n} Ph/s, bottoming at {n} Ph/s and peaking at {n} Ph/s throughout the month. Pool hashrate [distribution](https://miningpoolstats.stream/decred) as of {date}: {pool name n%, ...}.

{ hint: fallback link for pool distribution: https://dcrstats.com/pow }

Staking: [30-day average](https://dcrstats.com/) ticket price was {n.n, try to snapshot it on 1st} DCR (+{n.n}). The [price](https://explorer.dcrdata.org/charts?chart=ticket-price&zoom=t1-t2&bin=window&axis=time&visibility=true-false&mode=stepped) {set zoom to show the month} varied between {n.n}-{n.n} DCR. [Locked amount](https://explorer.dcrdata.org/charts?chart=ticket-pool-value&zoom=t1-t2&scale=linear&bin=block&axis=time) was {n.nn}-{n.nn} million DCR, which corresponded to {n.n}-{n.n}% of the available supply [participating](https://explorer.dcrdata.org/charts?chart=stake-participation&zoom=t1-t2&scale=linear&bin=block&axis=time) in PoS.

{ hint: fallback link for locked %: https://charts.dcr.farm/d/000000003/proof-of-stake?orgId=1&from=now-40d&to=now }

{ recap of ticket price action if it was interesting }

{ hint: consider keeping Block size and Transactions sections every 2nd or 3rd month, unless there is something interesting to report }

Block size: This month, the blockchain size grew by {n} MB. [Block size](https://explorer.dcrdata.org/charts?chart=block-size&bin=block&axis=time) {set zoom to show the month} varied between {n.n}-{n.n} with an average of {n.n} KB. {any interesting fact about this month's blocks}

Transactions: In {month}, Decred users made {n} regular transactions and bought {n} tickets. {n} tickets were rewarded for voting and {n} were revoked. On average, there were {n} regular DCR transactions and {n} new tickets per day.

{ hint: for dcr.farm set the zoom to show exactly UTC month 1st 00:00:00 - next month 1st 00:00:00 }

Nodes: Throughout [{month}](https://charts.dcr.farm/d/000000014/nodes?orgId=1&from=1583020800000&to=1585699200000) {set zoom to show the month} there was an average of {} public listening nodes and {} total nodes per dcr.farm. Version distribution: {vx.y.z: n% (+n%), ...}.

{ any interesting analysis or events in the network }

## Integrations

{ hint: new pieces of infrastructure or updates from existing: VSPs, exchanges, wallets, OTC desks, payment processors. use bullets or paragraphs, whatever looks best in a given month's compilation }

{ check https://github.com/decred/dcrwebapi/commits/master for changes to the VSP list }

Warning: the authors of the Decred Journal have no idea about the trustworthiness of any of the services above. Please do your own research before trusting your personal information or assets to any entity.

## Adoption

{ new merchants }

{ applications of Decred blockchain and related projects: Politeia, dcrtime, atomicswap }

{ investment adoption }

## Outreach

{ overview of outreach/communications/marketing/PR activity for past month and any short-term plans }

## Events

Attended:

- {dates} - [{title}]({event link}) - {city}, {country}. {recap}

Upcoming:

- {dates} - [{title}]({event link}) - {city}, {country}. {info}

{announcements in Events domain}

## Media

{ notable community efforts }

{ ratings news }

{ hint: use the following format: (title in Sentence case) by (author) ([domain](link)) - (optional comment) }

Selected articles:

- {}

Translations:

- {}

Videos:

- {}

Audio:

- {}

## Community Discussions

Comm systems news:

- {}

{ selected discussed topics, as bullet list or one paragraph per topic }

Selected Reddit posts:

- {}

Selected Twitter discussions:

- {}

## Markets

In {month} DCR was trading between USD {n.nn}-{n.nn} / BTC {}-{}. The average daily rate was ${n.nn}.

{ markets overview: USD and BTC prices, highs and lows, interesting events, interesting analysis }

## Relevant External

{ cc tech: PoW, ASIC resistance, full nodes, cc network security, etc }

{ governance, funding, chain forks, community splits }

{ DEX }

{ relevant exchanges and websites }

{ other: regulations, privacy, security, fun }

## About This Issue

This is issue {number} of Decred Journal. Index of all issues, mirrors, and translations is available [here](https://xaur.github.io/decred-news/).

Most information from third parties is relayed directly from source after a minimal sanity check. The authors of the Decred Journal have no ability to verify all claims. Please beware of scams and do your own research.

You can submit a story [here](https://github.com/xaur/decred-news/labels/next%20release) to be considered for the next release. [Feedback](https://github.com/xaur/decred-news/blob/docs/contributing.md#feedback) and [contributions](https://github.com/xaur/decred-news/blob/docs/contributing.md) are always welcome.

Credits (alphabetical order):

- writing and editing: {}
- reviews and feedback: {}
- title image: {}