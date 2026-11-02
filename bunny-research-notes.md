# Research log — the sleepy white rabbit figurine

All checks done **1 November 2026**. "Verified" = I opened the page and compared the photographs to the reference image.

## The item, identified

| Attribute | Detail |
|---|---|
| Sculpt | Chubby white rabbit, sitting, both back legs splayed out sideways, eyes closed (two curved lines), red-orange nose, pink cheeks, pink ear insides/paws |
| Material / finish | Glossy resin |
| Size | ~5 × 5 × 6.5 cm (1.9 × 1.9 × 2.5 in), ~240 g boxed weight |
| Family | One of 5 poses sold together by the factory (also: paws-together open eyes; winking standing; lying with eyes open; lying with eyes closed) |
| Amazon identity | brand `ihreesy`, colour/variant **White Rabbit #E**, MPN `BQTK37157`, ASIN `B0CDZYFMHC` |
| AliExpress identity | "Cute Rabbit Gift Box Small Decorative Resin Animal Micro Landscape Decoration Car Supplies Home Furnishings" (supplier store: *Wedo Life Store*) |
| Temu identity | goods ID `601099511750810` |
| Other names seen | "Cute Rabbit Desktop Ornaments / Funny Miniature Bunny Figurine / Car Dashboard Ornament"; Russian: «Подарочная коробка с милым Кроликом» |

## Status table

| # | Where | URL / ID | Status on 1 Nov 2026 | Match |
|---|---|---|---|---|
| 1 | Amazon US | https://www.amazon.com/dp/B0CDZYFMHC | **$16.49, listed In stock**, seller *Partong Store*, delivery Nov 12–20, returns to Jan 31 2027 | ✅ photo-verified exact |
| 2 | AliExpress | item `1005001333292108` | Mirror (imall.com) reports *"not available now"* + *"store does not ship to your country"* | ✅ exact, but dead |
| 3 | AliExpress | item `1005004884651516` — "2023 New Year Gift Figurine Miniature Cute Rabbit…" | Mirror shows $0.40, flagged *"store does not ship to your country"* | ✅ image set includes the identical 5-pose factory photo |
| 4 | AliExpress | item `1005005596719787` — "Figurines Miniature Cute White Rabbit Micro Landscape Ornaments…" | Not verifiable (bot wall) | ⚠️ same family, photos unverified |
| 5 | Temu | goods `601099511750810` (user's own link) | Sold out | ✅ exact (user-verified) |
| 6 | Joom | `676b7fc52986f901f8506004` — «Микропейзаж Мультфильм Милый Кролик…» | Page: **"Товар недоступен" — product unavailable** | was exact family |
| 7 | Alibaba | product `1600990901052` — "Micro Landscape Animal Figurine Cartoon Cute Little Rabbit…" (MOQ 2) | Product page **deleted** (redirects to invalid-items search) | was exact family |
| 8 | Ozon (RU) | `1342108765` «Статуя Мультяшный Кролик Пейзажный Орнамент» | Listed, RU delivery only | similar family |
| 9 | 21vek.by (BY) | ILikeGift "Sleepy bunny / FC191121" | Listed, Belarus delivery only; it is a **coin bank** version | ⚠️ different product type |
| 10 | Amazon UK / CA | same ASIN | 404 — ASIN doesn't exist on either marketplace | ❌ |
| 11 | eBay | searches: "resin rabbit car dashboard ornament", "sleeping bunny resin figurine" | Only unrelated, larger, vintage-style sleeping bunnies | ❌ |
| 12 | Etsy | searches + DashMasteer listings | Different sculpts (vase bunnies, butt-up winking bunny) | ❌ |
| 13 | Walmart | marketplace searches | Sets of 8/25/50 mini bunnies, lucky rabbits, dog figurines | ❌ |

## Lookalikes checked and rejected (with reason)

- **AliExpress `1005011911972602`** "Cute Panda & Bunny Car Dashboard Decor Relaxed Resin Animal Figurines" ($2.55, 2,000+ sold, 4.8–4.9). Photos show the bunny **reclining against a pink cushion wearing sunglasses, ears folded down**. Wrong sculpt — rejected.
- **Amazon `B0GTF6DQLS`** (ARTIBETTER, $14.99, seller *QingLL*) and **`B0GP677JT9`** (Toyvian, $13.39, seller *HLShan*): New-Year "wealth" bunnies with gold ingot + red 财 card. Rejected.
- **Amazon `B0BQBQSBLV`** (Chinese lucky rabbit figurines) and **`B0C3CC18ZN`** (CRASPIRE 18pcs). Rejected.
- **Etsy listing 4311943714** "Kawaii Animal Car Dashboard Figurine" — bunny lying on stomach, winking, pink bottom. Rejected.

## Search strings that actually surface this item

- AliExpress: `Cute Rabbit Gift Box Small Decorative Resin Animal Micro Landscape`; `Mini Simulation Rabbit Figurine Bunny Car Desktop Ornament Micro Landscape`; `Miniature Cute Rabbit Micro Landscape Ornaments`
- Amazon: `ihreesy rabbit dashboard ornament`; `Cute Rabbit Desktop Ornaments Funny Miniature Bunny Figurine`
- Chinese (for Taobao / 1688 / agent sites): `兔子摆件 微景观` · `车载兔子摆件` · `树脂兔子 摆件 睡觉`
- Temu: `1pc small white rabbit resin figure home garden decoration`

## Methods used

1. Reverse-image search (Yandex Smart Camera) on the Amazon main photo, the 5-pose gallery photo, and the original AliExpress factory photo — this is what surfaced the Russian/Belarusian resellers and the Alibaba wholesale listing.
2. AliExpress price-mirror (`imall.com`) to read listing status/photos without hitting AliExpress's anti-bot wall.
3. Direct page reads on Amazon US/UK/CA, Joom, Alibaba, eBay, Etsy, Walmart, Superbuy (Taobao search proxy).
4. Photo-by-photo comparison of every candidate against the reference image before recommending it.

## Not yet cracked

- No live, in-stock, US-shipping **AliExpress** listing confirmed by me (site blocks automation). Three candidate listing IDs are in the shopping card for you to open directly.
- No **Taobao/1688** source item found via the agent search proxy with the keyword sets above; a Chinese-language keyword or an image search inside the agent app would likely find it.

---

# Part 4 — 2 November 2026

Second pass, new session, new tools. Full narrative: `bunny-pass-4.html`.

## Tool reality of this session (differs from Parts 1–3)

| Capability | This session |
|---|---|
| `fetch_page` on Amazon product / seller-search / all-offers pages | ✅ works |
| `fetch_page` on AliExpress **wholesale/search** pages | ✅ **works** (was walled in Parts 1–3) |
| `fetch_page` on AliExpress **item** pages | ❌ "We need to check if you are a robot" |
| `fetch_page` on Temu | ❌ slide-puzzle verification |
| `fetch_page` on Ozon | ❌ HTTP 500 |
| Yandex reverse-image by URL | ✅ works, but returns only already-known hits |
| Yiwugo (yiwugo.com) search + product detail | ✅ **works, no login** |
| eBay search | ✅ works (renders, filter chrome heavy) |
| Viewing a **remote** product photo | ❌ not possible this session — image URLs 500, no shell network |
| `image_search` → saves to workspace → viewable | ✅ works (used for sculpt spot-checks) |
| Shell network (`curl`) to any marketplace | ❌ blocked; sandbox has no outbound web |

Consequence worth remembering: in this session **no candidate could be photo-verified**. Every "wrong sculpt" call in Part 4 rests on titles/categories, not on looking.

## Amazon B0CDZYFMHC — now proven a ghost

- $16.49, "In Stock", free delivery Nov 12–20, returnable to Jan 31 2027. Unchanged from Part 3.
- **All-offers panel (`/gp/product/ajax/aodAjaxMain`): exactly one offer, then "End of results".** Shipper = seller = Partong Store, ID `AT2IQ293SRQ0N`. → The Part 3 advice "click Other sellers" is **closed**; there is no alternate offer.
- Seller health: 4.5★ / 216 ratings / **82% positive over last 12 months**.
- **BSR #4,291,820 in Automotive**, #6,250 in Automotive Interior Mirrors → effectively no sales.
- Reading: page and price are real, stock is not; checkout cannot see that, hence order → refund loop. Not a stock cycle to wait out.
- Sibling found via the seller's own storefront search (`/s?me=AT2IQ293SRQ0N&k=rabbit`, 31 results): **`B0CDZZRHXC`** "ihreesy Rabbit Miniature Figurines … Resin Crafts Statues, **Pink**", $15.09, In Stock, same seller, but filed under Toys & Games → Non-Edible Cake Toppers. Seller runs a cluster of *ihreesy* rabbit SKUs across categories. Not the white #E; not a substitute.
- Sibling also seen: `B0CF11QS88` (bobblehead, Type B, $16.09), `B0CF12DQC9` (bobblehead Type A).
- Narrow check `/s?me=…&k=white+rabbit+figurine` → only 2 results: the target and the bobblehead. **No hidden white-#E twin under another ASIN.**

## eBay

`resin rabbit dashboard ornament white sleeping`, Buy-It-Now → **0 results**, literally. Corrects Part 3's "only unrelated hits".

## Yiwugo — the factory layer, open for the first time

Search terms that worked: `兔子摆件`, `睡觉兔子摆件`, `趴趴睡觉兔子`, `车载兔子摆件`.
Yiwugo product pages expose: stall address, boss name, mobile, item code, per-variant price **and live stock count**.

### 栎町工艺 / 义乌市栎町工艺品有限公司 — best lead
- Self-described **own-design + production + sales factory** (自主设计，生产，销售一体); resin ornaments, PVC figures, miniature props.
- Product **983810072** 微景观可爱趴趴睡觉猫狗猪兔子动物…; item code **LIT0320**; resin; PP bag; 6 variants 小猪/小兔/仓鼠/小熊/小狗/小猫.
- **小兔 ¥1.00, 库存 40,140, 3 件起购**, free shipping in China.
- Booth: 义乌国际商贸城一区东 6门 1楼 4街 101180B. Contact **李红群 13335959405** (phone = WeChat; shop notice says order via WeChat).
- Shop page https://www.yiwugo.com/hu/101180B01.html · product https://www.yiwugo.com/product/detail/983810072.html
- Runs a **1688** shop `2214100418246` (offers linked from the Yiwugo page: 730204153172, 788160165033, 747270965415, 744977591818, 690936544451, 824214125966).
- **Correction:** Part 3 eliminated 栎町 for its "兔子家族萌兔" set. That verdict covers that set only — `LIT0320` is a different line, never examined.

### Other live candidates
- 义乌永辉供应 (6 yrs): same 趴趴睡觉 series **¥1.32–1.56**, min 3 — product 971022812. Car console rabbit set **¥0.96–8.64**, min 1 — product 971031644. Tulip screen rabbit — product 971040542.
- 海淘优选日用百货 (15 yrs): 微景观 resin rabbit **¥0.70–1.46**, min 2 — product 965378567.
- 陈军工艺品三店 also carries 983225021 睡觉贴贴小兔 (fridge-magnet style) — still the wrong family.

### Not confirmed
None of the above is photo-verified as the exact sculpt. They are the correct *genre* (glossy resin, sprawled/sleeping, car-or-desk scale, ¥0.70–1.56) from contactable shops. Confirmation needs human eyes on 4 photos.

## Yandex reverse-image (run on `m.media-amazon.com/images/I/413PFxvpRsL.jpg`)

Returns only: Ozon `493654747` («Спящая зайка с розовым бантиком», 4×3×5 cm, polystone — and it is the real factory photo) and the deleted Alibaba `1600990901052`. Ozon page now 500s for me. **No new sellers.**

## Still open after Part 4

1. Photo-confirm the Yiwu candidates (user's job, 30 seconds, 4 links).
2. A working **AliExpress item-page** reader — search is open, items are not.
3. 1688 itself (login wall) — reachable only through an agent.
4. True stock status behind Partong Store — needs a seller reply, not a scrape.
