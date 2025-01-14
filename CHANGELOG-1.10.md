# CHANGELOG FOR `1.10.X`

## v1.10.0-ALPHA.1 (2021-05-10)

#### TL;DR

- Added support for PHP 8.0 ([#12552](https://github.com/Sylius/Sylius/issues/12552))
- Allowed user password to be null ([#12441](https://github.com/Sylius/Sylius/issues/12441))
- Bumped PHP requirements to 7.4 ([#12297](https://github.com/Sylius/Sylius/issues/12297))
- Removed Admin API Bundle from the default Sylius installation ([#12547](https://github.com/Sylius/Sylius/issues/12547))
- Replaced codes and ids in API v2 with IRIs ([#12487](https://github.com/Sylius/Sylius/issues/12487))
- Replaced deprecated Zend libraries with Laminas replacements ([#12357](https://github.com/Sylius/Sylius/issues/12357))
- Switched to utf8mb4 database charset ([#12429](https://github.com/Sylius/Sylius/issues/12429))
- Unified serialization groups within API v2 ([#12532](https://github.com/Sylius/Sylius/issues/12532))
- Upgraded to API Platform ^2.6 ([#12510](https://github.com/Sylius/Sylius/issues/12510))

#### Details

- [#12048](https://github.com/Sylius/Sylius/issues/12048) [API] Explicitly exclude feature from API implementation ([@lchrusciel](https://github.com/lchrusciel))
- [#12092](https://github.com/Sylius/Sylius/issues/12092) Resource layer tip - English corrections ([@tuala](https://github.com/tuala))
- [#12297](https://github.com/Sylius/Sylius/issues/12297) Bump up requirements to PHP 7.4 ([@pamil](https://github.com/pamil))
- [#12303](https://github.com/Sylius/Sylius/issues/12303) Remove lock file from cache hashes in CI ([@szepeviktor](https://github.com/szepeviktor))
- [#12304](https://github.com/Sylius/Sylius/issues/12304) Update PHPStan configuration ([@szepeviktor](https://github.com/szepeviktor))
- [#12333](https://github.com/Sylius/Sylius/issues/12333) [API] remove promotion coupon ([@arti0090](https://github.com/arti0090))
- [#12347](https://github.com/Sylius/Sylius/issues/12347) Remove roadmap links for now ([@pjedrzejewski](https://github.com/pjedrzejewski))
- [#12357](https://github.com/Sylius/Sylius/issues/12357) Replace zendframework/zend-stdlib with laminas/laminas-stdlib ([@pamil](https://github.com/pamil))
- [#12360](https://github.com/Sylius/Sylius/issues/12360) [API] Password reset ([@arti0090](https://github.com/arti0090))
- [#12366](https://github.com/Sylius/Sylius/issues/12366) [API] change variants to iri + tests ([@SirDomin](https://github.com/SirDomin))
- [#12368](https://github.com/Sylius/Sylius/issues/12368) [API] Account verifying ([@AdamKasp](https://github.com/AdamKasp), [@arti0090](https://github.com/arti0090))
- [#12382](https://github.com/Sylius/Sylius/issues/12382) Filter product variants by product & option values ([@pamil](https://github.com/pamil), [@GSadee](https://github.com/GSadee))
- [#12385](https://github.com/Sylius/Sylius/issues/12385) Add contact email in channel fixture ([@maximehuran](https://github.com/maximehuran))
- [#12390](https://github.com/Sylius/Sylius/issues/12390) Shipping method change key cost to price ([@SirDomin](https://github.com/SirDomin), [@AdamKasp](https://github.com/AdamKasp))
- [#12391](https://github.com/Sylius/Sylius/issues/12391) [API] reseting password with validation ([@arti0090](https://github.com/arti0090))
- [#12395](https://github.com/Sylius/Sylius/issues/12395) [Docs] Add note about doctrine migrations ([@Tomanhez](https://github.com/Tomanhez))
- [#12402](https://github.com/Sylius/Sylius/issues/12402) Remove duplicated entry in composer file and add return type in setup trait ([@arti0090](https://github.com/arti0090))
- [#12405](https://github.com/Sylius/Sylius/issues/12405) Decouple translation used in emails from shopBundle to coreBundle ([@arti0090](https://github.com/arti0090))
- [#12408](https://github.com/Sylius/Sylius/issues/12408) [ApiBundle] Use one kernel in test application ([@GSadee](https://github.com/GSadee))
- [#12419](https://github.com/Sylius/Sylius/issues/12419) [API] Add missing specs and make fixes to reset password PR ([@arti0090](https://github.com/arti0090))
- [#12420](https://github.com/Sylius/Sylius/issues/12420) [API] Adjust reset password requests ([@lchrusciel](https://github.com/lchrusciel))
- [#12424](https://github.com/Sylius/Sylius/issues/12424) Doc: Fix Doctrine project url ([@n3wborn](https://github.com/n3wborn))
- [#12429](https://github.com/Sylius/Sylius/issues/12429) Use 4-Byte UTF-8 Unicode Encoding ([@jacquesbh](https://github.com/jacquesbh))
- [#12431](https://github.com/Sylius/Sylius/issues/12431) Bump elliptic from 6.5.3 to 6.5.4 ([@dependabot](https://github.com/dependabot)[[@bot](https://github.com/bot)])
- [#12441](https://github.com/Sylius/Sylius/issues/12441) [UserBundle] Allow user password to be null for SSO ([@loic425](https://github.com/loic425))
- [#12444](https://github.com/Sylius/Sylius/issues/12444) Create resource belongs to collectionOperation ([@kayue](https://github.com/kayue))
- [#12445](https://github.com/Sylius/Sylius/issues/12445) [Api] Subscribed to newsletter ([@Tomanhez](https://github.com/Tomanhez))
- [#12451](https://github.com/Sylius/Sylius/issues/12451) [Docs] How to add product variants by options to the cart in Sylius API? ([@AdamKasp](https://github.com/AdamKasp))
- [#12456](https://github.com/Sylius/Sylius/issues/12456) Update sspooky13/yaml-standards requirement from ^5.1 to ^5.1 || ^6.0 ([@dependabot-preview](https://github.com/dependabot-preview)[[@bot](https://github.com/bot)])
- [#12457](https://github.com/Sylius/Sylius/issues/12457) Drop sspooky13/yaml-standards ^5.1 in favour of ^6.0 ([@pamil](https://github.com/pamil))
- [#12460](https://github.com/Sylius/Sylius/issues/12460) Use egulias/email-validator ^3.0 ([@pamil](https://github.com/pamil))
- [#12470](https://github.com/Sylius/Sylius/issues/12470) [API] Remove untested route on ProductVariant ([@lchrusciel](https://github.com/lchrusciel))
- [#12472](https://github.com/Sylius/Sylius/issues/12472) [Api] Visitor and Customer add ProductReview ([@Tomanhez](https://github.com/Tomanhez))
- [#12474](https://github.com/Sylius/Sylius/issues/12474) [API] Resend Verification email ([@arti0090](https://github.com/arti0090))
- [#12476](https://github.com/Sylius/Sylius/issues/12476) [API] Subscribing to newsletter on account register ([@arti0090](https://github.com/arti0090))
- [#12477](https://github.com/Sylius/Sylius/issues/12477) [API] product review filters ([@SirDomin](https://github.com/SirDomin))
- [#12478](https://github.com/Sylius/Sylius/issues/12478) Remove unnecessary logic from handler ([@arti0090](https://github.com/arti0090))
- [#12479](https://github.com/Sylius/Sylius/issues/12479) Add few cosmetic improvements in ChangeShopUserPasswordHandler.php and xml files ([@Tomanhez](https://github.com/Tomanhez))
- [#12480](https://github.com/Sylius/Sylius/issues/12480) Change command constructor ([@arti0090](https://github.com/arti0090))
- [#12482](https://github.com/Sylius/Sylius/issues/12482) Remove duplicated service ([@Tomanhez](https://github.com/Tomanhez))
- [#12483](https://github.com/Sylius/Sylius/issues/12483) [Api] Product has last 3 reviews by default ([@SirDomin](https://github.com/SirDomin))
- [#12485](https://github.com/Sylius/Sylius/issues/12485) Use route name instead of a hardcoded '/' to redirect user on logout ([@rimas-kudelis](https://github.com/rimas-kudelis))
- [#12487](https://github.com/Sylius/Sylius/issues/12487) [Api][POC]Convert iri to code in command ([@Tomanhez](https://github.com/Tomanhez), [@arti0090](https://github.com/arti0090))
- [#12491](https://github.com/Sylius/Sylius/issues/12491) [API] Added product average rating ([@SirDomin](https://github.com/SirDomin))
- [#12496](https://github.com/Sylius/Sylius/issues/12496) fixed find files in yaml standards ([@sspooky13](https://github.com/sspooky13))
- [#12497](https://github.com/Sylius/Sylius/issues/12497) [API] Validating shipment that was shipped ([@arti0090](https://github.com/arti0090))
- [#12498](https://github.com/Sylius/Sylius/issues/12498) Convert iri to code in command AddProductReview ([@Tomanhez](https://github.com/Tomanhez))
- [#12499](https://github.com/Sylius/Sylius/issues/12499) [API][Shop] Add validation for adding a product review ([@GSadee](https://github.com/GSadee))
- [#12509](https://github.com/Sylius/Sylius/issues/12509) [API] Add admin and shop section resolvers ([@GSadee](https://github.com/GSadee))
- [#12510](https://github.com/Sylius/Sylius/issues/12510) Update to api platform v2.6 ([@Tomanhez](https://github.com/Tomanhez))
- [#12512](https://github.com/Sylius/Sylius/issues/12512) [API] Fix cart blaming ([@GSadee](https://github.com/GSadee), [@arti0090](https://github.com/arti0090))
- [#12518](https://github.com/Sylius/Sylius/issues/12518) fix: add unique index to token_value in order entity ([@pptasinski](https://github.com/pptasinski))
- [#12526](https://github.com/Sylius/Sylius/issues/12526) Remove unused api cart blamer method add missing spec ([@arti0090](https://github.com/arti0090))
- [#12528](https://github.com/Sylius/Sylius/issues/12528) Refactor cart blaming ([@arti0090](https://github.com/arti0090))
- [#12529](https://github.com/Sylius/Sylius/issues/12529) Cleanup resend verification email handler ([@arti0090](https://github.com/arti0090))
- [#12530](https://github.com/Sylius/Sylius/issues/12530) [API]Unify change quantity endpoint with other orders endpoints ([@arti0090](https://github.com/arti0090))
- [#12532](https://github.com/Sylius/Sylius/issues/12532) [API] Serialization groups unified ([@SirDomin](https://github.com/SirDomin))
- [#12533](https://github.com/Sylius/Sylius/issues/12533) Minor fixes for cart blaming command ([@arti0090](https://github.com/arti0090))
- [#12534](https://github.com/Sylius/Sylius/issues/12534) [Api] upgrade taxon filter on product ([@AdamKasp](https://github.com/AdamKasp), [@GSadee](https://github.com/GSadee), [@SirDomin](https://github.com/SirDomin))
- [#12542](https://github.com/Sylius/Sylius/issues/12542) Upgrade release cycle dates for 1.9 and 1.10 ([@pamil](https://github.com/pamil))
- [#12544](https://github.com/Sylius/Sylius/issues/12544) [API][Checkout] Add tag to promotion scenario ([@lchrusciel](https://github.com/lchrusciel))
- [#12545](https://github.com/Sylius/Sylius/issues/12545) [API][Promotion] Test applying promotion rules ([@lchrusciel](https://github.com/lchrusciel))
- [#12547](https://github.com/Sylius/Sylius/issues/12547) Remove Admin API Bundle from the default Sylius installation ([@pamil](https://github.com/pamil))
- [#12552](https://github.com/Sylius/Sylius/issues/12552) Add support for PHP 8.0 ([@pamil](https://github.com/pamil))
- [#12557](https://github.com/Sylius/Sylius/issues/12557) update Plus installation guide ([@AdamKasp](https://github.com/AdamKasp))
- [#12558](https://github.com/Sylius/Sylius/issues/12558) [Order] Fix race condition problem with multiple order recalculations ([@GSadee](https://github.com/GSadee))
- [#12562](https://github.com/Sylius/Sylius/issues/12562) [DOC] update theme structure documentation ([@Sylvain](https://github.com/Sylvain) [@Just](https://github.com/Just))
- [#12564](https://github.com/Sylius/Sylius/issues/12564) [Docs] add minor improvement to Plus installation guide ([@AdamKasp](https://github.com/AdamKasp))
- [#12565](https://github.com/Sylius/Sylius/issues/12565) [API][Order] Fix possibility to limit orders by refactoring from data provider to extension ([@GSadee](https://github.com/GSadee))
- [#12568](https://github.com/Sylius/Sylius/issues/12568) [API] channel based product collection ([@SirDomin](https://github.com/SirDomin))
- [#12569](https://github.com/Sylius/Sylius/issues/12569) Bugfix | Filter out not enabled products in API collection ([@stloyd](https://github.com/stloyd), [@arti0090](https://github.com/arti0090))
- [#12571](https://github.com/Sylius/Sylius/issues/12571) [API] remove productCode from addToCart ([@SirDomin](https://github.com/SirDomin))
- [#12574](https://github.com/Sylius/Sylius/issues/12574) Upgrade to GitHub-native Dependabot ([@dependabot-preview](https://github.com/dependabot-preview)[[@bot](https://github.com/bot)])
- [#12579](https://github.com/Sylius/Sylius/issues/12579) [API] Validate if product or variant is enabled ([@arti0090](https://github.com/arti0090))
- [#12581](https://github.com/Sylius/Sylius/issues/12581) [Api]Fix isAllowedProperty return type in ReflectionExtractor ([@Tomanhez](https://github.com/Tomanhez), [@pamil](https://github.com/pamil))
- [#12592](https://github.com/Sylius/Sylius/issues/12592) Include just one MySQL 5.7 build ([@pamil](https://github.com/pamil))
- [#12599](https://github.com/Sylius/Sylius/issues/12599) [Docs] Add and improve new api docs ([@AdamKasp](https://github.com/AdamKasp))
- [#12600](https://github.com/Sylius/Sylius/issues/12600) [Api]Add customers id next to token ([@Tomanhez](https://github.com/Tomanhez))
- [#12604](https://github.com/Sylius/Sylius/issues/12604) [API] Cherry pick commits on 1.9 branch for validating if product is enabled during adding to cart ([@arti0090](https://github.com/arti0090), [@GSadee](https://github.com/GSadee))
- [#12609](https://github.com/Sylius/Sylius/issues/12609) Adding product from another channel bugfix ([@arti0090](https://github.com/arti0090))
- [#12610](https://github.com/Sylius/Sylius/issues/12610) Fixes after upmerge ([@AdamKasp](https://github.com/AdamKasp))
- [#12612](https://github.com/Sylius/Sylius/issues/12612) [Documentation] Update cookbook about Facebook login ([@GSadee](https://github.com/GSadee))
- [#12613](https://github.com/Sylius/Sylius/issues/12613) [API] Adding inexistent variant ([@arti0090](https://github.com/arti0090), [@GSadee](https://github.com/GSadee))
- [#12617](https://github.com/Sylius/Sylius/issues/12617) [API][PHPSpec] Fix validator after upmerge ([@GSadee](https://github.com/GSadee))
