## alltheseas

open source contributor buidling:

🐞 **[bugstr](https://github.com/alltheseas/bugstr)** - zero-infrastructure bug reporting \
🟣 **[damus](https://github.com/damus-io/damus)** - iOS short note app with zaps \
🎥 **[Lumina Video](https://github.com/lumina-video/lumina-video)** - zero-copy native A/V streaming rust SDK + MoQ \
👀 **[nostrability](https://github.com/nostrability)** - left curve nostr interoperability tracker & JSON schema validation \
🐰 **[notedeck](https://github.com/damus-io/notedeck)** - nostr egui browser \
👨🏻‍🏭 **[telemoq](https://github.com/alltheseas/telemoq)** - MoQ for robot teleops — priority scheduling in field conditions \
⚡️ **[zapstore](https://github.com/zapstore/zapstore)** - the social app store built for app devs

---

### upstream merged PRs (Oct 2025 – Mar 2026)

105 PRs merged across 24 repos in 19 organizations · +59,605 lines

#### [lumina-video/lumina-video](https://github.com/lumina-video/lumina-video) — 20 merged · +24.7k lines
- iOS Foundation: core extraction + C FFI bridge
- Flutter plugin for cross-platform embedding
- MoQ web live streaming with Opus audio decode + A/V sync + drift correction
- Android zero-copy video rendering + VideoPlayer API
- Fix frozen video + choppy audio on late join
- Replace rodio with cpal for low-latency audio
- CI: Android APK + macOS DMG release workflows

#### [nostrability/outbox](https://github.com/nostrability/outbox) — 16 merged · +15.1k lines
- Outbox model analysis framework + benchmark suite (120+ runs)
- NIP-66 relay filter + Thompson Sampling algorithm
- Filter Decomposition + Hybrid outbox enrichment
- Latency-aware Thompson Sampling with EOSE-race + TTFE benchmarks

#### [nostrability/schemata](https://github.com/nostrability/schemata) — 20 merged · +2.9k lines
- JSON schema validation for 20+ NIPs: NIP-04, 05, 09, 10, 17, 18, 23, 25, 32, 34, 36, 38, 42, 52, 53, 56, 57, 59, 61, 68, 69, 78, 84, 88, 89, 99, B7
- MIP-00 schemas for Marmot protocol
- Sample-based vitest test suite with real Nostr events

#### [damus-io/damus](https://github.com/damus-io/damus) — 13 merged · +2.6k lines
- Consume NIP-19 relay hints for event fetching (+1.5k lines)
- Add NIP-89 client tag support
- Highlight search terms in note search results
- Fix Lightning invoice parsing and fetching
- Fix missing profile names/pictures due to stream timing
- Fix auto-translate regression, blank notifications, shifty cursor, chat overlays, mention rendering

#### [damus-io/notecrumbs](https://github.com/damus-io/notecrumbs) — 4 merged · +4.3k lines
- Longform article rendering pipeline (+1.5k lines)
- SEO: sitemap.xml + robots.txt generation (+2.6k lines)
- Skip blocking profile feed fetch when notes are cached (perf)

#### [damus-io/notedeck](https://github.com/damus-io/notedeck) — 6 merged · +660 lines
- Rebuild timeline filter on contact list changes
- Configurable hashtag limit filter
- Filter out future-dated notes
- Collapsible follow pack members in onboarding
- Switch Copy Note ID to nevent format
- Windows Media Foundation video decoder with D3D11 hardware acceleration

#### [marmot-protocol/*](https://github.com/marmot-protocol) — 3 merged · +3.9k lines
- marmot-ts: MIP compliance gaps — retries, NIP-70, welcome failures, key rotation (+3.5k)
- mdk: self-update tracking fields for Group struct
- marmot: MIP-00 64-char Nostr pubkey format fix

#### [hzrd149/applesauce](https://github.com/hzrd149/applesauce) — 2 merged · +1.8k lines
- Validate kind-0/1 events against nostrability JSON blob verification schemas
- Enable default signature verification of profiles

#### NIP-17 compliance fixes — 9 merged across 5 apps + nips spec
- [0xchat-app/nostr-dart](https://github.com/0xchat-app/nostr-dart): seal verification + relay hints (2 PRs)
- [VectorPrivacy/Vector](https://github.com/VectorPrivacy/Vector): relay confirmation + NIP-17 inbox routing (2 PRs, +1.1k lines)
- [lumehq/coop](https://github.com/lumehq/coop): gift wrap validation + DM relay hints (3 PRs)
- [psic4t/nospeak](https://github.com/psic4t/nospeak): comprehensive NIP-17 compliance
- [formstr-hq/nostr-polls](https://github.com/formstr-hq/nostr-polls): publish inbox relays
- [nostr-protocol/nips](https://github.com/nostr-protocol/nips): NIP-17 + NIP-59 spec clarifications (2 PRs)

#### other upstream
- [zapstore/zapstore](https://github.com/zapstore/zapstore): error messages + AGENTS.md (2 PRs)
- [purplebase/models](https://github.com/purplebase/models): NIP-88 poll models
- [moq-dev/moq](https://github.com/moq-dev/moq): native client integration guide
- [v0l/zap-stream-core](https://github.com/v0l/zap-stream-core): MoQ catalog + SPS/PPS fix
- [hoytech/strfry](https://github.com/hoytech/strfry): subscription ID cap bugfix
- [greenart7c3/Amber](https://github.com/greenart7c3/Amber): bunker encryption serialization fix
- [AustinKelsay/snstr](https://github.com/AustinKelsay/snstr): docs + crypto test fix
- [sledtools/pika](https://github.com/sledtools/pika): relay confirmation + README
