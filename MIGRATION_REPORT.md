# LIBERTY ENTERPRISES — Product migration report

Generated: 2026-10-30T12:52:46.950Z
Source: https://www.libertyenterprises.online (DotPe longtail storefront, store 5659143)
Method: public `sitemap_products.xml` → public product pages → SSR product payload (`__NEXT_DATA__`).
The source website was only read; nothing was changed or disrupted.

## Coverage

| Metric | Count |
| --- | ---: |
| Published product URLs discovered | 678 |
| Products migrated | 678 |
| Failed pages | 0 |
| Duplicate URLs / slugs | 0 |
| Products missing images | 0 |
| Products missing prices | 4 |
| Products missing descriptions | 444 |
| Products out of stock at source | 83 |
| Products with variants | 4 |
| Legacy categories referenced | 62 |
| Products requiring manual review | 492 |

All 678 published products were migrated. Nothing was silently discarded.
Legacy category `More Items` (cid=0) contains no products and is therefore not used.

## Department mapping

| Department | Products |
| --- | ---: |
| Soft Toys & Dolls | 293 |
| Feeding & Baby Care | 80 |
| Baby Mobility & Carriers | 96 |
| Baby Bedding & Sleeping | 96 |
| Kids Toys & Ride-ons | 37 |
| Kids Lifestyle & Play | 26 |
| Baby Clothing & Accessories | 50 |

## Legacy categories preserved as subcategories

| Legacy category | Products |
| --- | ---: |
| CARTOON CHARACTER | 65 |
| ANIMAL SOFT TOYS | 59 |
| TEDDY BEAR | 34 |
| DOLLS | 32 |
| BABY BED | 26 |
| BABY RIDER | 23 |
| BABY CYCLE | 21 |
| MIX CHARACTERS | 21 |
| INTEX TUBS AND PUMP | 20 |
| FEEDING BOTTLE | 18 |
| BABY WALKER | 18 |
| BABY GIFT SET | 17 |
| 55rs LOT ITEMS | 16 |
| BABY CRADLE | 14 |
| Kids Battery Bikes & Cars | 14 |
| UNICORN | 14 |
| BONDA TEDDY BEARS | 13 |
| BABY PILLOW | 13 |
| BABY SHOE, SOCKS, CAP AND GLOUSE | 12 |
| ADJUSTABLE BABY WALKER | 11 |
| BABY DRY SHEET AND RUBBER SHEET | 11 |
| BABY POTTY | 10 |
| More Items | 10 |
| PILLOWS | 9 |
| MOSQUITO NET UMBRELLA | 8 |
| BIRDS SOFT TOY | 8 |
| KIDS TENT HOUSE | 8 |
| CLASSIC INDIAN COVER TEDDY | 7 |
| BABY SWING | 7 |
| SKATING SCOOTERS | 7 |
| BABY FEEDING NIPPLE | 7 |
| BABY BATH TOWEL | 6 |
| BABY CHAIR | 6 |
| BABY BRUSH | 6 |
| BABY NAIL CLIPPERS | 6 |
| CAP TEDDY | 6 |
| SPRING | 6 |
| COAT TEDDY BEAR | 6 |
| PACKET TEDDY | 5 |
| SOFT BALLS | 5 |
| bags | 5 |
| BABY SIPPER | 5 |
| BABY WIPES | 5 |
| AVENGERS | 5 |
| Rangeela bonda | 5 |
| CAP TOWEL | 4 |
| BABY SWEATER | 4 |
| MOSQUITO NET AND TENT | 4 |
| BABY NADA VANDI | 4 |
| Heart Ring Cap Teddy | 4 |
| THOTTIL KATTAI | 4 |
| BABY ADJUSTABLE DIAPERS AND BIPS | 3 |
| BABY CARRIER | 3 |
| BABY HANGARS | 3 |
| Rocking Chairs | 3 |
| GOLU HEART TEDDY | 3 |
| STUDY TABLES | 3 |
| BABY POWDER PUF | 2 |
| BABY BUDDS | 1 |
| BABY PALADAI | 1 |
| PLASTIC SPEAKING DOLL | 1 |
| BABY HELMET | 1 |

## Data-quality flags

### Products without a description (444)
The legacy storefront left these descriptions blank. They are migrated as-is and flagged
`needsReview`; marketing copy must be written by the owner, not invented.

- 0 SIZE TEDDY (`LE-30968263`)
- 000 COVER TEDDY (`LE-28791303`)
- 12 PCS TEDDY FOR 180 (`LE-30964571`)
- 12 PCS TEDDY SMALL (`LE-30964329`)
- 12PCS TEDDY (S) (`LE-30103981`)
- 150 ML WIDE MOUTH PREMIUM MORISON (`LE-30955020`)
- 2 In 1 Potty Chair (`LE-31987666`)
- 250ML WIDE MOUTH PREMIUM MORISON (`LE-30955025`)
- 3D booster XXL bed printed (`LE-32594182`)
- 4 RIB MOSQUITO UMBRELLA NYLON THICK (`null`)
- 40CM BONDA TEDDY (`LE-30681598`)
- 55rs LOT ITEMS (More Variety) (`null`)
- 6 PACK SPECIAL CARTOON CHARACTER Rs 85(Each Piece) (`LE-29387602`)
- 6 PCK SOFT BALLS (`LE-29166677`)
- 6 PCS PACK FUR TEDDY (`LE-30964592`)
- 6 PCS PACK TEDDY (`LE-30964598`)
- 6 RIB NYLON THICK (`null`)
- 6PKT SMILY TEDDY (EACH PIECE 72) (`null`)
- 8 WHEEL GRIP WALKER PLAIN (`LE-30955058`)
- 8 WHEEL PVC WALKER MUSIC (`LE-27576653`)
- adjestable 3 in 1 walker (`LE-33138306`)
- adjestable 3in 1 walker (`LE-33138310`)
- ADJUSTABLE DIAPPER PLAIN (`LE-27589443`)
- AMERICAN TEDDY NO1 (`LE-30378237`)
- AMERICAN TEDDY NO2 (`LE-30378239`)
- AMERICAN TEDDY NO3 (`LE-30296293`)
- ANGRY BIRD CYCLE (`null`)
- ANIMAL TIGER 90cm (`LE-30305335`)
- APPLE FUR DOLL (`null`)
- APPLE TOP GOLD (`LE-31230323`)

…and 414 more (see `data/migration/products.json` → description === "").

### Products without a price (4)
- INTEX BATH TUB 56441 (`null`) — https://www.libertyenterprises.online/product/27661269/INTEX-BATH-TUB-56441
- INTEX BATH TUB 56451 (`null`) — https://www.libertyenterprises.online/product/27661323/INTEX-BATH-TUB-56451
- INTEX BATH TUB 56490 (`null`) — https://www.libertyenterprises.online/product/27661438/INTEX-BATH-TUB-56490
- INTEX BATH TUB 57412 (`null`) — https://www.libertyenterprises.online/product/27661569/INTEX-BATH-TUB-57412

### Categories that needed a judgement call (10)
These legacy category names are not explicit about their department. Products are still
migrated and the owner should confirm the department in the admin.

- More Items

### Duplicate product names (0)
Same display name, different SKU/source ID — these are distinct listings at source.

None.

## Price handling

* `historicalListPrice` = legacy selling price.
* `historicalDiscountedPrice` = legacy struck-through price where present.
* Migrated wholesale price uses the lower of the two **as a historical starting point**.
  The owner must review pricing in Admin → Products before launch.
* Quantity tiers seeded: MOQ–9 (base), 10–49 (−5%), 50–99 (−8%), 100+ (custom quote).
  All tiers are editable in the admin.

## Image handling

* 812 image URLs preserved, still served from the legacy CDN (`cdn.dotpe.in`).
* Only publicly listed product images are referenced. The owner must confirm image rights
  before commercial launch and can replace any image in Admin → Products.
* Every image keeps its original alt text where available.

## Review queue (first 40)

| Product | SKU | Price (₹) | Legacy category | Source |
| --- | --- | ---: | --- | --- |
| 0 SIZE TEDDY | `LE-30968263` | 60 | TEDDY BEAR | https://www.libertyenterprises.online/product/30968263/0-SIZE-TEDDY |
| 000 COVER TEDDY | `LE-28791303` | 36 | CLASSIC INDIAN COVER TEDDY | https://www.libertyenterprises.online/product/28791303/000-COVER-TEDDY |
| 12 PCS TEDDY FOR 180 | `LE-30964571` | 156 | PACKET TEDDY | https://www.libertyenterprises.online/product/30964571/12-PCS-TEDDY-FOR-180 |
| 12 PCS TEDDY SMALL | `LE-30964329` | 240 | PACKET TEDDY | https://www.libertyenterprises.online/product/30964329/12-PCS-TEDDY-SMALL |
| 12PCS TEDDY (S) | `LE-30103981` | 180 | TEDDY BEAR | https://www.libertyenterprises.online/product/30103981/12PCS-TEDDY--S- |
| 150 ML WIDE MOUTH PREMIUM MORISON | `LE-30955020` | 105 | FEEDING BOTTLE | https://www.libertyenterprises.online/product/30955020/150-ML-WIDE-MOUTH-PREMIUM-MORISON |
| 2 In 1 Potty Chair | `LE-31987666` | 320 | BABY POTTY | https://www.libertyenterprises.online/product/31987666/2-In-1-Potty-Chair |
| 250ML WIDE MOUTH PREMIUM MORISON | `LE-30955025` | 119 | FEEDING BOTTLE | https://www.libertyenterprises.online/product/30955025/250ML-WIDE-MOUTH-PREMIUM-MORISON |
| 3D booster XXL bed printed | `LE-32594182` | 480 | BABY BED | https://www.libertyenterprises.online/product/32594182/3D-booster-XXL-bed-printed |
| 4 RIB MOSQUITO NET DOLPHIN | `null` | 140 | MOSQUITO NET UMBRELLA | https://www.libertyenterprises.online/product/28631907/4-RIB-MOSQUITO-NET-DOLPHIN |
| 4 RIB MOSQUITO NET PHOTO | `null` | 145 | MOSQUITO NET UMBRELLA | https://www.libertyenterprises.online/product/28631830/4-RIB-MOSQUITO-NET-PHOTO |
| 4 RIB MOSQUITO NET SILKY | `null` | 165 | MOSQUITO NET UMBRELLA | https://www.libertyenterprises.online/product/28631944/4-RIB-MOSQUITO-NET-SILKY |
| 4 RIB MOSQUITO UMBRELLA NYLON THICK | `null` | 90 | MOSQUITO NET UMBRELLA | https://www.libertyenterprises.online/product/27577674/4-RIB-MOSQUITO-UMBRELLA-NYLON-THICK |
| 40CM BONDA TEDDY | `LE-30681598` | 165 | BONDA TEDDY BEARS | https://www.libertyenterprises.online/product/30681598/40CM-BONDA-TEDDY |
| 55rs LOT ITEMS (More Variety) | `null` | 55 | 55rs LOT ITEMS | https://www.libertyenterprises.online/product/29472823/55rs-LOT-ITEMS--More-Variety- |
| 6 PACK SPECIAL CARTOON CHARACTER Rs 85(Each Piece) | `LE-29387602` | 85 | CARTOON CHARACTER | https://www.libertyenterprises.online/product/29387602/6-PACK-SPECIAL-CARTOON-CHARACTER-Rs-85-Each-Piece- |
| 6 PCK SOFT BALLS | `LE-29166677` | 270 | SOFT BALLS | https://www.libertyenterprises.online/product/29166677/6-PCK-SOFT-BALLS |
| 6 PCS PACK FUR TEDDY | `LE-30964592` | 216 | PACKET TEDDY | https://www.libertyenterprises.online/product/30964592/6-PCS-PACK-FUR-TEDDY |
| 6 PCS PACK TEDDY | `LE-30964598` | 360 | PACKET TEDDY | https://www.libertyenterprises.online/product/30964598/6-PCS-PACK-TEDDY |
| 6 RIB MOSQUITO NET COTTON PRINT | `null` | 120 | MOSQUITO NET UMBRELLA | https://www.libertyenterprises.online/product/27577669/6-RIB-MOSQUITO-NET-COTTON-PRINT |
| 6 RIB MOSQUITO NET PHOTO | `null` | 160 | MOSQUITO NET UMBRELLA | https://www.libertyenterprises.online/product/28631998/6-RIB-MOSQUITO-NET-PHOTO |
| 6 RIB MOSQUITO NET SILKY | `null` | 175 | MOSQUITO NET UMBRELLA | https://www.libertyenterprises.online/product/28632020/6-RIB-MOSQUITO-NET-SILKY |
| 6 RIB NYLON THICK | `null` | 100 | MOSQUITO NET UMBRELLA | https://www.libertyenterprises.online/product/27560545/6-RIB-NYLON-THICK |
| 6PKT SMILY TEDDY (EACH PIECE 72) | `null` | 72 | TEDDY BEAR | https://www.libertyenterprises.online/product/29558036/6PKT-SMILY-TEDDY--EACH-PIECE-72- |
| 8 WHEEL GRIP WALKER PLAIN | `LE-30955058` | 440 | BABY WALKER | https://www.libertyenterprises.online/product/30955058/8-WHEEL-GRIP-WALKER-PLAIN |
| 8 WHEEL PVC WALKER MUSIC | `LE-27576653` | 560 | BABY WALKER | https://www.libertyenterprises.online/product/27576653/8-WHEEL-PVC-WALKER-MUSIC |
| adjestable 3 in 1 walker | `LE-33138306` | 1650 | More Items | https://www.libertyenterprises.online/product/33138306/adjestable-3-in-1-walker |
| adjestable 3in 1 walker | `LE-33138310` | 1500 | ADJUSTABLE BABY WALKER | https://www.libertyenterprises.online/product/33138310/adjestable-3in-1-walker |
| ADJUSTABLE DIAPPER PLAIN | `LE-27589443` | 95 | BABY ADJUSTABLE DIAPERS AND BIPS | https://www.libertyenterprises.online/product/27589443/ADJUSTABLE-DIAPPER-PLAIN |
| AIR PILLOW | `null` | 90 | INTEX TUBS AND PUMP | https://www.libertyenterprises.online/product/28628206/AIR-PILLOW |
| AMERICAN TEDDY NO1 | `LE-30378237` | 180 | TEDDY BEAR | https://www.libertyenterprises.online/product/30378237/AMERICAN-TEDDY-NO1 |
| AMERICAN TEDDY NO2 | `LE-30378239` | 220 | TEDDY BEAR | https://www.libertyenterprises.online/product/30378239/AMERICAN-TEDDY-NO2 |
| AMERICAN TEDDY NO3 | `LE-30296293` | 340 | TEDDY BEAR | https://www.libertyenterprises.online/product/30296293/AMERICAN-TEDDY-NO3 |
| ANGRY BIRD CYCLE | `null` | 780 | BABY CYCLE | https://www.libertyenterprises.online/product/27628255/ANGRY-BIRD-CYCLE |
| ANIMAL TIGER 90cm | `LE-30305335` | 820 | ANIMAL SOFT TOYS | https://www.libertyenterprises.online/product/30305335/ANIMAL-TIGER-90cm |
| APPLE FUR DOLL | `null` | 80 | DOLLS | https://www.libertyenterprises.online/product/29392280/APPLE-FUR-DOLL |
| APPLE TOP GOLD | `LE-31230323` | 420 | More Items | https://www.libertyenterprises.online/product/31230323/APPLE-TOP-GOLD |
| Apple Top With Spring | `LE-27589433` | 600 | BABY BED | https://www.libertyenterprises.online/product/27589433/Apple-Top-With-Spring |
| Apple Top Without Spring | `LE-27589430` | 450 | BABY BED | https://www.libertyenterprises.online/product/27589430/Apple-Top-Without-Spring |
| AROGYA COW IMPORTED | `LE-29615353` | 260 | ANIMAL SOFT TOYS | https://www.libertyenterprises.online/product/29615353/AROGYA-COW-IMPORTED |
