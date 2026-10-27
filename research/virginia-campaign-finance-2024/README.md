God first. All glory to God through Jesus Christ.

# Virginia campaign finance: show the arithmetic

By Sherman G. Laing · Word.Quantum.Earth  
October 27, 2026 · Public-data research and teaching note

Word.Quantum.Earth places God's Word first. Truthfulness requires us to show how we reach a conclusion and to correct it when the evidence requires correction. This inquiry asks a narrow, answerable question: **How do the reported disbursements assigned to Virginia in the FEC's 2023–2024 House candidate table compare with other states?**

## Finding

The table lists **$65,513,529.02 across 67 Virginia records**. Dividing by Virginia's 11 House seats gives **$5,955,775.37 per seat**. That is **20.51% above** the weighted 50-state average for this measure.

Virginia ranks **9th in total disbursements and 14th per seat** among the 50 states in the unaltered table. The source contains flagged entries and repeated rows. The sensitivity checks below change Virginia's rankings to as high as 8th and 11th respectively, while leaving Virginia's own dollar total unchanged. These are descriptive comparisons of a published table, not proof of misconduct.

## What the numbers measure

The period is **January 1, 2023–December 31, 2024**. We use the FEC's [Congressional Candidate Table 7 workbook](https://www.fec.gov/resources/campaign-finance-statistics/2024/tables/congressional/ConCand7_2024_24m.xlsx), worksheet `CongressionalCandidate Table 7`, rows 6–1891, column J. Its [PDF companion](https://www.fec.gov/resources/campaign-finance-statistics/2024/tables/congressional/ConCand7_2024_24m.pdf) says it was generated March 17, 2025. The source files were retrieved October 27, 2026. This is that historical snapshot, not a reconstruction of subsequent amendments.

“Disbursements” means the total reported on Form 3, line 22, column A, under the FEC's [table definitions](https://www.fec.gov/campaign-finance-data/campaign-finance-statistics/formula-calculations-statistical-tables-election-cycles-after-2010/). It includes categories such as operating expenses, transfers, loan repayments and contribution refunds. It is broader than advertising purchases. See [Form 3](https://www.fec.gov/resources/cms-content/documents/fecfrm3.pdf), detailed disbursements page.

A state identifies the candidate's office, not necessarily the place a payment was spent. The comparison does not include all state or local elections, Senate or presidential campaigns, or separately reported outside spending. Adding PAC receipts or expenditures to these candidate totals would require checking transfers and overlap first.

The FEC includes special-election activity in this cycle, including Virginia's 4th District. Therefore, “per seat” does not mean “per distinct election contest.” [FEC cycle summary](https://www.fec.gov/updates/statistical-summary-of-24-month-campaign-activity-of-the-2023-2024-election-cycle/)

## The calculation, one step at a time

**1. Add the Virginia records.** Virginia occupies rows 1727–1793. There are 67 rows. Add their column-J amounts:

`SUM(J1727:J1793) = $65,513,529.02`

**2. Use a matching 50-state comparison.** The full table has 1,886 records. Of these, 22 concern DC or territories. Their combined disbursements are $6,487,076.97. Keep them in the national source reconciliation, but exclude them from a comparison using the 50 states' 435 voting House seats:

`$2,156,242,566.97 − $6,487,076.97 = $2,149,755,490.00`

This leaves **1,864 table records across 50 states**. Row counts are not asserted to be unique people; repeated names are documented below.

**3. Account for delegation size.** A state with more seats has more seats to finance. Divide by the [Census apportionment seat counts](https://www2.census.gov/programs-surveys/decennial/2020/data/apportionment/apportionment-2020-table01.pdf) applicable to this cycle:

`Virginia: $65,513,529.02 ÷ 11 = $5,955,775.37 per seat`

`50 states: $2,149,755,490.00 ÷ 435 = $4,941,966.64 per seat`

The second calculation is a **seat-weighted average**, not the simple average of 50 state averages. Seat normalization controls for delegation size only; it does not control for competitiveness, media prices, the number of candidates or special elections.

**4. Calculate the relative difference.** Keep full precision until the final displayed result:

`[(65,513,529.02 ÷ 11) ÷ (2,149,755,490.00 ÷ 435) − 1] × 100 = 20.51%`

This means Virginia's reported disbursements per seat are 20.51% higher than this benchmark. It does not mean each Virginia candidate spends that amount.

**5. Rank consistently.** For either total dollars or dollars per seat:

`Rank = 1 + number of states with a strictly larger value`

The same rule applies to all 50 states. Equal values would share a rank. All dollar sums use cents; division is rounded only for display.

## Virginia and its five neighboring states

The displayed neighbors are selected geographically. The full 50-state comparison follows, so the reader need not rely on this subset.

| State | House seats | Table disbursements | Dollars per seat | Per-seat rank / 50 |
|---|---:|---:|---:|---:|
| Virginia | 11 | $65,513,529.02 | $5,955,775.37 | 14 |
| Maryland | 8 | $91,688,218.91 | $11,461,027.36 | 3 |
| North Carolina | 14 | $62,485,468.52 | $4,463,247.75 | 26 |
| Kentucky | 6 | $17,666,522.06 | $2,944,420.34 | 36 |
| Tennessee | 9 | $14,836,996.11 | $1,648,555.12 | 46 |
| West Virginia | 2 | $5,570,824.44 | $2,785,412.22 | 38 |

Maryland's high baseline requires particular care: one FEC-flagged entry, David Trone, accounts for $64,032,401.51 of its $91,688,218.91. Excluding that entry changes Maryland's total to $27,655,817.40. We do not present the original Maryland total as a clean measure of House-race spending.

## Where Virginia's total is concentrated

| District | Table records | Disbursements | Table 7 source rows |
|---|---:|---:|---|
| VA-01 | 3 | $2,883,245.48 | 1727–1729 |
| VA-02 | 3 | $10,088,130.99 | 1730–1732 |
| VA-03 | 3 | $906,229.43 | 1733–1735 |
| VA-04 | 5 | $3,337,651.12 | 1736–1740 |
| VA-05 | 5 | $3,630,946.65 | 1741–1745 |
| VA-06 | 3 | $1,171,983.13 | 1746–1748 |
| VA-07 | 15 | $26,239,972.10 | 1749–1763 |
| VA-08 | 6 | $3,164,537.45 | 1764–1769 |
| VA-09 | 2 | $1,354,630.65 | 1770–1771 |
| VA-10 | 19 | $10,370,656.77 | 1772–1790 |
| VA-11 | 3 | $2,365,545.25 | 1791–1793 |

The three largest district totals are VA-07, VA-10 and VA-02:

`$26,239,972.10 + $10,370,656.77 + $10,088,130.99 = $46,698,759.86`

`$46,698,759.86 ÷ $65,513,529.02 × 100 = 71.28%`

Thus **three of Virginia's eleven districts account for 71.28%** of the table's Virginia disbursements. That describes concentration. It does not establish why the concentration occurred.

## What the source checks found

**FEC flags.** Fifteen entries carry an asterisk. The FEC's footnote identifies candidates who began the cycle for one office and later announced retirement, resignation or candidacy for another office. Their listed disbursements total **$217,144,092.94**. None are Virginia entries. Excluding all fifteen is a sensitivity test: it can also remove legitimate House campaign activity, so it is not an authoritative correction. [Flagged records](FLAGGED-RECORDS.csv) · [FEC footnote, final PDF page](https://www.fec.gov/resources/campaign-finance-statistics/2024/tables/congressional/ConCand7_2024_24m.pdf#page=43)

**Repeated records.** There are 21 groups with the same state, district and candidate name. Within those groups, 17 rows beyond the first occurrence repeat all 13 source cell values exactly, totaling **$10,392,108.73**. Other same-name rows differ in at least one field and are retained in the exact-repeat sensitivity. Table 7 does not expose committee identifiers sufficient to resolve every repeated name. None of these groups are in Virginia. [Repeated-name audit with row numbers](REPEATED-NAME-AUDIT.csv)

The baseline retains all published rows. A separate sensitivity removes only the 17 exact repeats beyond the first. This preserves the source while making the effect of that choice visible. The asterisk and exact-repeat exclusions do not overlap.

| Treatment | 50-state total | Weighted dollars per seat | Virginia above average | VA total rank | VA per-seat rank |
|---|---:|---:|---:|---:|---:|
| FEC table as published | $2,149,755,490.00 | $4,941,966.64 | 20.51% | 9 | 14 |
| Remove only the 17 exact repeated rows | $2,139,363,381.27 | $4,918,076.74 | 21.10% | 9 | 14 |
| Exclude only the 15 FEC-flagged entries | $1,932,611,397.06 | $4,442,784.82 | 34.06% | 8 | 11 |
| Apply both sensitivity exclusions | $1,922,219,288.33 | $4,418,894.92 | 34.78% | 8 | 11 |

Across these four explicitly defined treatments, Virginia remains above the comparison average. That stability supports this limited descriptive finding. It does not resolve every classification or filing issue in the source.

**Reporting dates.** Column M shows 103 records ending in 2023 and 1,783 ending in 2024. Virginia has 4 and 63 respectively. We retain them as the FEC lists them. We do not assume an early ending date is a missing report; establishing the reason requires examining individual filings.

**State labels.** Arizona, California, Colorado and Virginia have trailing spaces in the workbook. We trim whitespace in the calculation copy only. Original files remain unchanged.

**Precision.** Spreadsheet storage contains tiny binary-number tails on some values. The independent check reads the raw workbook numbers and rounds each monetary value to cents before summing. No substantive dollar amount is changed to make a control pass.

## Reproduce the result without specialized software

1. Download the linked Table 7 workbook and preserve it. Work in a separate copy.
2. On that copy, label N5 `Clean state`; enter `=TRIM(A6)` in N6 and fill through N1891.
3. Add the cents-rounded amount in O5/O6: label `Disbursements in cents precision`, formula `=ROUND(J6,2)`, filled through O1891.
4. Virginia's total is `=SUMIFS($O$6:$O$1891,$N$6:$N$1891,"Virginia")`.
5. For the asterisk sensitivity, label P5 `FEC asterisk`; enter `=IF(RIGHT(C6,1)="*",1,0)` in P6 and fill down. Add `$P$6:$P$1891,0` to the SUMIFS criteria to exclude those entries.
6. For the exact-repeat sensitivity, start with another preserved working copy of A5:M1891. Use the spreadsheet's Remove Duplicates feature with **all 13 columns selected**. It should remove 17 rows. Do not remove rows merely because a candidate name repeats. Rebuild the helper columns after that operation.
7. Use [the 50-state seat list](SEAT-DENOMINATORS.csv), sum each state's dollar amount, then divide by its seats. Sum those 50 state totals and divide by 435 for the weighted benchmark. Use the dollar amounts before display rounding.
8. Compare with [the state results](STATE-COMPARISON.csv) and [the 67 Virginia input records](VIRGINIA-CANDIDATE-ARITHMETIC.csv). The Virginia district totals are also [available separately](VIRGINIA-DISTRICTS.csv).

Every one of the seven financial-column sums from Table 7 matches the FEC's separate [Table 3 workbook](https://www.fec.gov/resources/campaign-finance-statistics/2024/tables/congressional/ConCand3_2024_24m.xlsx), worksheet `Congressional Candidate Table 3`, 2024 row 7, columns D–J, to the cent. The count matches C7 at 1,886. See [the control differences](CONTROL-CHECKS.csv). A second extraction directly from the workbook's stored XML independently reproduces all 50 state dollar totals at cents precision. These checks verify our extraction and arithmetic; two FEC tables can share an underlying source issue.

## What this establishes, and what remains open

The evidence establishes the table totals, comparative ranks, the effects of specified exclusions and the concentration within Virginia. It does **not**, by itself, establish racial discrimination, corruption, donor influence, the motives of a company or official, or a causal connection between campaign finance and the historical exclusions discussed in our earlier article.

Those questions require additional evidence: identified donors and recipients, transaction dates, comparable policy decisions or outcomes, and a defined test against alternative explanations. A separate state/local-election study would also need aligned election cycles and comparable reporting categories. This federal House comparison is not a substitute for that work.

The lesson is simple: define what is counted, use a matching denominator, expose the calculation and test whether reasonable source-handling choices change the conclusion. Anyone can check this arithmetic, learn it and teach it.

## All 50 states

Baseline as published. Per-seat rank is descending. Dollars per seat are displayed to cents.

| State | Seats | Table disbursements | Dollars per seat | Rank |
|---|---:|---:|---:|---:|
| Alabama | 7 | $23,842,073.30 | $3,406,010.47 | 32 |
| Alaska | 1 | $17,588,551.46 | $17,588,551.46 | 1 |
| Arizona | 9 | $134,286,038.25 | $14,920,670.92 | 2 |
| Arkansas | 4 | $9,029,486.86 | $2,257,371.72 | 43 |
| California | 52 | $341,228,286.62 | $6,562,082.44 | 11 |
| Colorado | 8 | $56,588,954.63 | $7,073,619.33 | 10 |
| Connecticut | 5 | $14,383,536.45 | $2,876,707.29 | 37 |
| Delaware | 1 | $6,154,182.49 | $6,154,182.49 | 13 |
| Florida | 28 | $84,894,130.21 | $3,031,933.22 | 34 |
| Georgia | 14 | $35,340,320.64 | $2,524,308.62 | 41 |
| Hawaii | 2 | $1,598,091.40 | $799,045.70 | 50 |
| Idaho | 2 | $2,611,523.53 | $1,305,761.77 | 48 |
| Illinois | 17 | $46,592,463.44 | $2,740,733.14 | 39 |
| Indiana | 9 | $46,535,840.48 | $5,170,648.94 | 21 |
| Iowa | 4 | $32,750,720.89 | $8,187,680.22 | 6 |
| Kansas | 4 | $14,502,954.35 | $3,625,738.59 | 30 |
| Kentucky | 6 | $17,666,522.06 | $2,944,420.34 | 36 |
| Louisiana | 6 | $43,155,332.22 | $7,192,555.37 | 8 |
| Maine | 2 | $12,556,536.25 | $6,278,268.13 | 12 |
| Maryland | 8 | $91,688,218.91 | $11,461,027.36 | 3 |
| Massachusetts | 9 | $16,580,313.82 | $1,842,257.09 | 44 |
| Michigan | 13 | $76,560,102.21 | $5,889,238.63 | 16 |
| Minnesota | 8 | $46,664,874.63 | $5,833,109.33 | 17 |
| Mississippi | 4 | $4,554,689.17 | $1,138,672.29 | 49 |
| Missouri | 8 | $26,860,418.38 | $3,357,552.30 | 33 |
| Montana | 2 | $22,298,048.63 | $11,149,024.32 | 4 |
| Nebraska | 3 | $17,740,844.07 | $5,913,614.69 | 15 |
| Nevada | 4 | $33,933,147.25 | $8,483,286.81 | 5 |
| New Hampshire | 2 | $15,959,156.52 | $7,979,578.26 | 7 |
| New Jersey | 12 | $56,005,046.19 | $4,667,087.18 | 25 |
| New Mexico | 3 | $14,862,488.51 | $4,954,162.84 | 24 |
| New York | 26 | $185,612,165.56 | $7,138,929.44 | 9 |
| North Carolina | 14 | $62,485,468.52 | $4,463,247.75 | 26 |
| North Dakota | 1 | $5,193,186.43 | $5,193,186.43 | 19 |
| Ohio | 15 | $63,691,557.66 | $4,246,103.84 | 28 |
| Oklahoma | 5 | $17,102,834.80 | $3,420,566.96 | 31 |
| Oregon | 6 | $30,887,659.80 | $5,147,943.30 | 22 |
| Pennsylvania | 17 | $75,804,156.27 | $4,459,068.02 | 27 |
| Rhode Island | 2 | $7,473,046.41 | $3,736,523.21 | 29 |
| South Carolina | 7 | $17,948,557.07 | $2,564,079.58 | 40 |
| South Dakota | 1 | $1,810,600.08 | $1,810,600.08 | 45 |
| Tennessee | 9 | $14,836,996.11 | $1,648,555.12 | 46 |
| Texas | 38 | $112,422,607.50 | $2,958,489.67 | 35 |
| Utah | 4 | $19,823,442.30 | $4,955,860.58 | 23 |
| Vermont | 1 | $1,458,229.74 | $1,458,229.74 | 47 |
| Virginia | 11 | $65,513,529.02 | $5,955,775.37 | 14 |
| Washington | 10 | $51,793,441.17 | $5,179,344.12 | 20 |
| West Virginia | 2 | $5,570,824.44 | $2,785,412.22 | 38 |
| Wisconsin | 8 | $42,836,226.89 | $5,354,528.36 | 18 |
| Wyoming | 1 | $2,478,066.41 | $2,478,066.41 | 42 |

## Source preservation

The official workbook downloads and PDF sources are identified by URL and SHA-256 in [SOURCE-RECEIPT.json](SOURCE-RECEIPT.json) and [CENSUS-SOURCE-RECEIPT.json](CENSUS-SOURCE-RECEIPT.json). A fingerprint identifies the bytes used; it does not certify the source's truth. The downloadable audit tables and this article are fingerprinted in [FILE-INTEGRITY.json](FILE-INTEGRITY.json).

This release contains public-data arithmetic and its explanation. The project's proprietary models, architecture and private research are outside its scope.
