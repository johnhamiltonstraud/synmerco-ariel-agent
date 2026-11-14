# NC, SC, TN acute hospitals: CMS general information matched to complications by ID, ranked, two pulls

Escrow: esc_d6e50da927ba44118a71a65d | Bid 4071: $6.30 (630 cents), net to seller $6.10 | Seller: did:pkh:eip155:8453:0xE69158fc6bCE070903e2960D195282BD086cE131
Awarded: 2026-11-13T00:49:11Z | Deliver by / hard stop: 2026-11-16T00:49:11Z | Earliest submit: 2026-11-14T00:49:11Z
Sources: data.cms.gov, Hospital General Information (xubh-q36u) and Complications and Deaths - Hospital (ynj2-r877). Public sources only; no contact with anyone.

Revision 1 (2026-11-14): PROOF now shows each response's count field as an exact body slice; PULL 1 times/URLs/Date headers now match the filed PULL 1 note window (2026-11-13T01:00:56Z-01:01:23Z). Only the PROOF sections and the A2/A5 answers changed.

## Counts per state per dataset (as the source returned them)

| Dataset | State | PULL 1 source count | PULL 1 rows read | PULL 2 source count | PULL 2 rows read |
|---|---|---|---|---|---|
| Hospital General Information (xubh-q36u), hospital_type = Acute Care Hospitals | NC | 80 | 80 | 80 | 80 |
| Hospital General Information (xubh-q36u), hospital_type = Acute Care Hospitals | SC | 51 | 51 | 51 | 51 |
| Hospital General Information (xubh-q36u), hospital_type = Acute Care Hospitals | TN | 78 | 78 | 78 | 78 |
| Complications and Deaths - Hospital (ynj2-r877) | NC | 2120 | 2120 | 2120 | 2120 |
| Complications and Deaths - Hospital (ynj2-r877) | SC | 1160 | 1160 | 1160 | 1160 |
| Complications and Deaths - Hospital (ynj2-r877) | TN | 2020 | 2020 | 2020 | 2020 |

PULL 1 totals: acute hospitals 209 (NC 80, SC 51, TN 78); complications rows 5300 (NC 2120, SC 1160, TN 2020).
PULL 2 totals: acute hospitals 209 (NC 80, SC 51, TN 78); complications rows 5300 (NC 2120, SC 1160, TN 2020).
Both pulls read every row the source count reported (rows == count for all six series in both pulls).

## One-dataset-only list

### Acute-pull hospitals with no complications rows: none

Every one of the 209 acute hospitals from the general-information pull has at least one complications row in both pulls (acute_only = 0 in pull 1 and in pull 2).

### Complications facility_ids not in the acute pull: 56

Each facility below was found in the Complications and Deaths - Hospital pull (ynj2-r877) and its facility_id is not in the Hospital General Information acute pull (xubh-q36u, hospital_type = Acute Care Hospitals). These include non-acute hospitals such as Critical Access Hospitals and federal (VA / military) facilities, by facility name. State and facility_name come from the complications row.

| facility_id | state | facility_name | how found |
|---|---|---|---|
| 34011F | NC | NMC Camp Lejeune | ynj2-r877 complications pull only; facility_id not in xubh-q36u acute pull |
| 34012F | NC | DURHAM VA MEDICAL CENTER | ynj2-r877 complications pull only; facility_id not in xubh-q36u acute pull |
| 34013F | NC | FAYETTEVILLE NC VA MEDICAL CENTER | ynj2-r877 complications pull only; facility_id not in xubh-q36u acute pull |
| 34014F | NC | Womack AMC (FT Bragg) | ynj2-r877 complications pull only; facility_id not in xubh-q36u acute pull |
| 34017F | NC | W.G. (BILL) HEFNER SALISBURY VA MEDICAL CENTER (SALSBURY) | ynj2-r877 complications pull only; facility_id not in xubh-q36u acute pull |
| 34036F | NC | ASHEVILLE-OTEEN VA MEDICAL CENTER | ynj2-r877 complications pull only; facility_id not in xubh-q36u acute pull |
| 341303 | NC | FIRSTHEALTH MONTGOMERY MEMORIAL HOSP | ynj2-r877 complications pull only; facility_id not in xubh-q36u acute pull |
| 341304 | NC | ECU HEALTH BERTIE HOSPITAL | ynj2-r877 complications pull only; facility_id not in xubh-q36u acute pull |
| 341305 | NC | DLP SWAIN COUNTY HOSPITAL LLC | ynj2-r877 complications pull only; facility_id not in xubh-q36u acute pull |
| 341307 | NC | PENDER MEMORIAL HOSPITAL | ynj2-r877 complications pull only; facility_id not in xubh-q36u acute pull |
| 341311 | NC | CHATHAM HOSPITAL INC | ynj2-r877 complications pull only; facility_id not in xubh-q36u acute pull |
| 341314 | NC | WASHINGTON COUNTY HOSP INC | ynj2-r877 complications pull only; facility_id not in xubh-q36u acute pull |
| 341315 | NC | CAPE FEAR VALLEY-BLADEN COUNTY HOSPITAL | ynj2-r877 complications pull only; facility_id not in xubh-q36u acute pull |
| 341316 | NC | HIGHLANDS CASHIERS HOSPITAL | ynj2-r877 complications pull only; facility_id not in xubh-q36u acute pull |
| 341317 | NC | LIFEBRITE COMMUNITY HOSPITAL OF STOKES | ynj2-r877 complications pull only; facility_id not in xubh-q36u acute pull |
| 341318 | NC | VIDANT CHOWAN HOSPITAL | ynj2-r877 complications pull only; facility_id not in xubh-q36u acute pull |
| 341319 | NC | TRANSYLVANIA REGIONAL HOSPITAL, INC | ynj2-r877 complications pull only; facility_id not in xubh-q36u acute pull |
| 341320 | NC | ALLEGHANY  MEMORIAL HOSPITAL | ynj2-r877 complications pull only; facility_id not in xubh-q36u acute pull |
| 341322 | NC | ADVENT HEALTH POLK | ynj2-r877 complications pull only; facility_id not in xubh-q36u acute pull |
| 341323 | NC | CHARLES A CANNON JR MEMORIAL HOSPITAL | ynj2-r877 complications pull only; facility_id not in xubh-q36u acute pull |
| 341324 | NC | THE OUTER BANKS HOSPITAL, INC | ynj2-r877 complications pull only; facility_id not in xubh-q36u acute pull |
| 341325 | NC | ASHE MEMORIAL HOSPITAL | ynj2-r877 complications pull only; facility_id not in xubh-q36u acute pull |
| 341326 | NC | ANGEL MEDICAL CENTER | ynj2-r877 complications pull only; facility_id not in xubh-q36u acute pull |
| 341327 | NC | J ARTHUR DOSHER MEMORIAL HOSPITAL | ynj2-r877 complications pull only; facility_id not in xubh-q36u acute pull |
| 341328 | NC | ERLANGER MURPHY MEDICAL CENTER | ynj2-r877 complications pull only; facility_id not in xubh-q36u acute pull |
| 341329 | NC | BLUE RIDGE REGIONAL HOSPITAL | ynj2-r877 complications pull only; facility_id not in xubh-q36u acute pull |
| 42009F | SC | NH Beaufort | ynj2-r877 complications pull only; facility_id not in xubh-q36u acute pull |
| 42011F | SC | COLUMBIA SC VA MEDICAL CENTER | ynj2-r877 complications pull only; facility_id not in xubh-q36u acute pull |
| 42029F | SC | CHARLESTON VA MEDICAL CENTER | ynj2-r877 complications pull only; facility_id not in xubh-q36u acute pull |
| 421300 | SC | ALLENDALE COUNTY HOSPITAL | ynj2-r877 complications pull only; facility_id not in xubh-q36u acute pull |
| 421301 | SC | ABBEVILLE AREA MEDICAL CENTER | ynj2-r877 complications pull only; facility_id not in xubh-q36u acute pull |
| 421304 | SC | EDGEFIELD COUNTY HEALTHCARE AN AFFILIATE OF SELF R | ynj2-r877 complications pull only; facility_id not in xubh-q36u acute pull |
| 423300 | SC | SHRINERS HOSPITALS FOR CHILDREN | ynj2-r877 complications pull only; facility_id not in xubh-q36u acute pull |
| 44013F | TN | MEMPHIS VA MEDICAL CENTER | ynj2-r877 complications pull only; facility_id not in xubh-q36u acute pull |
| 44016F | TN | MOUNTAIN HOME VA MEDICAL CENTER | ynj2-r877 complications pull only; facility_id not in xubh-q36u acute pull |
| 44017F | TN | VA MIDDLE TENNESSEE HEALTHCARE SYSTEM - MURFREESBORO | ynj2-r877 complications pull only; facility_id not in xubh-q36u acute pull |
| 44018F | TN | VA MIDDLE TENNESSEE HEALTHCARE SYSTEM | ynj2-r877 complications pull only; facility_id not in xubh-q36u acute pull |
| 440779 | TN | TRISTAR ASHLAND CITY MEDICAL CENTER | ynj2-r877 complications pull only; facility_id not in xubh-q36u acute pull |
| 440780 | TN | WAYNE MEDICAL CENTER | ynj2-r877 complications pull only; facility_id not in xubh-q36u acute pull |
| 441300 | TN | SAINT THOMAS HICKMAN HOSPITAL | ynj2-r877 complications pull only; facility_id not in xubh-q36u acute pull |
| 441301 | TN | HIGHPOINT HEALTH-TROUSDALE WITH ASCENSION SAINT | ynj2-r877 complications pull only; facility_id not in xubh-q36u acute pull |
| 441303 | TN | ASCENSION SAINT THOMAS THREE RIVERS | ynj2-r877 complications pull only; facility_id not in xubh-q36u acute pull |
| 441304 | TN | JOHNSON COUNTY COMMUNITY HOSPITAL | ynj2-r877 complications pull only; facility_id not in xubh-q36u acute pull |
| 441305 | TN | MACON COMMUNITY HOSPITAL | ynj2-r877 complications pull only; facility_id not in xubh-q36u acute pull |
| 441306 | TN | ERLANGER BLEDSOE HOSPITAL | ynj2-r877 complications pull only; facility_id not in xubh-q36u acute pull |
| 441307 | TN | HIGHPOINT HEALTH-RIVERVIEW WITH ASCENSION SAINT TH | ynj2-r877 complications pull only; facility_id not in xubh-q36u acute pull |
| 441309 | TN | MARSHALL MEDICAL CENTER | ynj2-r877 complications pull only; facility_id not in xubh-q36u acute pull |
| 441310 | TN | RHEA MEDICAL CENTER | ynj2-r877 complications pull only; facility_id not in xubh-q36u acute pull |
| 441313 | TN | HANCOCK COUNTY HOSPITAL | ynj2-r877 complications pull only; facility_id not in xubh-q36u acute pull |
| 441314 | TN | LAUDERDALE COMMUNITY HOSPITAL | ynj2-r877 complications pull only; facility_id not in xubh-q36u acute pull |
| 441316 | TN | WEST TENNESSEE HEALTHCARE CAMDEN HOSPITAL | ynj2-r877 complications pull only; facility_id not in xubh-q36u acute pull |
| 441320 | TN | WEST TENNESSEE HEALTHCARE BOLIVAR HOSPITAL | ynj2-r877 complications pull only; facility_id not in xubh-q36u acute pull |
| 441322 | TN | HOUSTON COUNTY COMMUNITY HOSPITAL | ynj2-r877 complications pull only; facility_id not in xubh-q36u acute pull |
| 441323 | TN | BIG SOUTH FORK MEDICAL CENTER | ynj2-r877 complications pull only; facility_id not in xubh-q36u acute pull |
| 443302 | TN | ST JUDE CHILDRENS RESEARCH HOSPITAL | ynj2-r877 complications pull only; facility_id not in xubh-q36u acute pull |
| 443303 | TN | EAST TENNESSEE CHILDRENS HOSPITAL | ynj2-r877 complications pull only; facility_id not in xubh-q36u acute pull |

Complications-only by state: NC 26, SC 7, TN 23 (total 56).

## Top 20 ranked (hospital-recon-pull2.csv)

Rank rule: matched hospitals (in both datasets) with a numeric hospital_overall_rating, higher rating first, then fewer worse_measures, then facility_id ascending as text. Rank is empty for rows that are not matched or have no numeric rating. 188 of 209 matched hospitals are ranked in both pulls.

| rank | facility_id | facility_name | state | hospital_overall_rating | worse_measures | complication_rows |
|---|---|---|---|---|---|---|
| 1 | 340017 | PARDEE HOSPITAL HENDERSON COUNTY | NC | 5 | 0 | 20 |
| 2 | 340023 | ADVENTHEALTH HENDERSONVILLE | NC | 5 | 0 | 20 |
| 3 | 340053 | NOVANT HEALTH PRESBYTERIAN MEDICAL CENTER | NC | 5 | 0 | 20 |
| 4 | 340061 | UNC HOSPITALS | NC | 5 | 0 | 20 |
| 5 | 340114 | REX HOSPITAL | NC | 5 | 0 | 20 |
| 6 | 340148 | NOVANT HEALTH MEDICAL PARK HOSPITAL | NC | 5 | 0 | 20 |
| 7 | 340155 | DUKE REGIONAL HOSPITAL | NC | 5 | 0 | 20 |
| 8 | 340171 | NOVANT HEALTH MATTHEWS MEDICAL CENTER | NC | 5 | 0 | 20 |
| 9 | 340173 | WAKEMED, CARY HOSPITAL | NC | 5 | 0 | 20 |
| 10 | 340190 | NOVANT HEALTH MINT HILL MEDICAL CENTER | NC | 5 | 0 | 20 |
| 11 | 420033 | PRISMA HEALTH GREER MEMORIAL HOSPITAL | SC | 5 | 0 | 20 |
| 12 | 420102 | PRISMA HEALTH  PATEWOOD HOSPITAL | SC | 5 | 0 | 20 |
| 13 | 420103 | PELHAM MEDICAL CENTER | SC | 5 | 0 | 20 |
| 14 | 420104 | MOUNT PLEASANT HOSPITAL | SC | 5 | 0 | 20 |
| 15 | 420110 | ROPER ST FRANCIS HOSPITAL-BERKELEY INC | SC | 5 | 0 | 20 |
| 16 | 440029 | WILLIAMSON MEDICAL CENTER | TN | 5 | 0 | 20 |
| 17 | 440081 | LECONTE MEDICAL CENTER | TN | 5 | 0 | 20 |
| 18 | 440091 | MEMORIAL HEALTHCARE SYSTEM, INC | TN | 5 | 0 | 20 |
| 19 | 440193 | VANDERBILT WILSON COUNTY HOSPITAL | TN | 5 | 0 | 20 |
| 20 | 440039 | VANDERBILT UNIVERSITY MEDICAL CENTER | TN | 5 | 1 | 20 |

## Measure table for the top 20 (values from pull 2 complications rows)

One row per measure per hospital: every measure_id with compared_to_national, score, start_date, end_date, exactly as published (MM/DD/YYYY dates; an empty cell means the source left it empty). 400 rows in total (20 measures per hospital).

| rank | facility_id | facility_name | measure_id | compared_to_national | score | start_date | end_date |
|---|---|---|---|---|---|---|---|
| 1 | 340017 | PARDEE HOSPITAL HENDERSON COUNTY | COMP_HIP_KNEE | Not Available | 4 | 04/01/2023 | 03/31/2025 |
| 1 | 340017 | PARDEE HOSPITAL HENDERSON COUNTY | Hybrid_HWM | Not Available | 3.5 | 07/01/2024 | 06/30/2025 |
| 1 | 340017 | PARDEE HOSPITAL HENDERSON COUNTY | ISCMR | No Different Than the National Rate | 56.95 | 07/01/2023 | 06/30/2025 |
| 1 | 340017 | PARDEE HOSPITAL HENDERSON COUNTY | MORT_30_AMI | Not Available | 12.7 | 07/01/2022 | 06/30/2025 |
| 1 | 340017 | PARDEE HOSPITAL HENDERSON COUNTY | MORT_30_CABG | Not Available | Not Available | 07/01/2022 | 06/30/2025 |
| 1 | 340017 | PARDEE HOSPITAL HENDERSON COUNTY | MORT_30_COPD | Not Available | 9.5 | 07/01/2022 | 06/30/2025 |
| 1 | 340017 | PARDEE HOSPITAL HENDERSON COUNTY | MORT_30_HF | Not Available | 13.1 | 07/01/2022 | 06/30/2025 |
| 1 | 340017 | PARDEE HOSPITAL HENDERSON COUNTY | MORT_30_PN | Not Available | 12.6 | 07/01/2022 | 06/30/2025 |
| 1 | 340017 | PARDEE HOSPITAL HENDERSON COUNTY | MORT_30_STK | Not Available | 7.6 | 07/01/2023 | 06/30/2025 |
| 1 | 340017 | PARDEE HOSPITAL HENDERSON COUNTY | PSI_03 | No Different Than the National Rate | 0.21 | 07/01/2023 | 06/30/2025 |
| 1 | 340017 | PARDEE HOSPITAL HENDERSON COUNTY | PSI_06 | No Different Than the National Rate | 0.15 | 07/01/2023 | 06/30/2025 |
| 1 | 340017 | PARDEE HOSPITAL HENDERSON COUNTY | PSI_08 | No Different Than the National Rate | 0.20 | 07/01/2023 | 06/30/2025 |
| 1 | 340017 | PARDEE HOSPITAL HENDERSON COUNTY | PSI_09 | No Different Than the National Rate | 2.42 | 07/01/2023 | 06/30/2025 |
| 1 | 340017 | PARDEE HOSPITAL HENDERSON COUNTY | PSI_10 | No Different Than the National Rate | 1.36 | 07/01/2023 | 06/30/2025 |
| 1 | 340017 | PARDEE HOSPITAL HENDERSON COUNTY | PSI_11 | No Different Than the National Rate | 5.92 | 07/01/2023 | 06/30/2025 |
| 1 | 340017 | PARDEE HOSPITAL HENDERSON COUNTY | PSI_12 | No Different Than the National Rate | 3.76 | 07/01/2023 | 06/30/2025 |
| 1 | 340017 | PARDEE HOSPITAL HENDERSON COUNTY | PSI_13 | No Different Than the National Rate | 4.94 | 07/01/2023 | 06/30/2025 |
| 1 | 340017 | PARDEE HOSPITAL HENDERSON COUNTY | PSI_14 | No Different Than the National Rate | 1.56 | 07/01/2023 | 06/30/2025 |
| 1 | 340017 | PARDEE HOSPITAL HENDERSON COUNTY | PSI_15 | No Different Than the National Rate | 1.07 | 07/01/2023 | 06/30/2025 |
| 1 | 340017 | PARDEE HOSPITAL HENDERSON COUNTY | PSI_90 | No Different Than the National Value | 0.83 | 07/01/2023 | 06/30/2025 |
| 2 | 340023 | ADVENTHEALTH HENDERSONVILLE | COMP_HIP_KNEE | Not Available | 5.9 | 04/01/2023 | 03/31/2025 |
| 2 | 340023 | ADVENTHEALTH HENDERSONVILLE | Hybrid_HWM | Not Available | 3.6 | 07/01/2024 | 06/30/2025 |
| 2 | 340023 | ADVENTHEALTH HENDERSONVILLE | ISCMR | No Different Than the National Rate | 44.95 | 07/01/2023 | 06/30/2025 |
| 2 | 340023 | ADVENTHEALTH HENDERSONVILLE | MORT_30_AMI | Not Available | Not Available | 07/01/2022 | 06/30/2025 |
| 2 | 340023 | ADVENTHEALTH HENDERSONVILLE | MORT_30_CABG | Not Available | Not Available | 07/01/2022 | 06/30/2025 |
| 2 | 340023 | ADVENTHEALTH HENDERSONVILLE | MORT_30_COPD | Not Available | 6.7 | 07/01/2022 | 06/30/2025 |
| 2 | 340023 | ADVENTHEALTH HENDERSONVILLE | MORT_30_HF | Not Available | 9.8 | 07/01/2022 | 06/30/2025 |
| 2 | 340023 | ADVENTHEALTH HENDERSONVILLE | MORT_30_PN | Not Available | 13.4 | 07/01/2022 | 06/30/2025 |
| 2 | 340023 | ADVENTHEALTH HENDERSONVILLE | MORT_30_STK | Not Available | 9.6 | 07/01/2023 | 06/30/2025 |
| 2 | 340023 | ADVENTHEALTH HENDERSONVILLE | PSI_03 | No Different Than the National Rate | 0.30 | 07/01/2023 | 06/30/2025 |
| 2 | 340023 | ADVENTHEALTH HENDERSONVILLE | PSI_06 | No Different Than the National Rate | 0.28 | 07/01/2023 | 06/30/2025 |
| 2 | 340023 | ADVENTHEALTH HENDERSONVILLE | PSI_08 | No Different Than the National Rate | 0.22 | 07/01/2023 | 06/30/2025 |
| 2 | 340023 | ADVENTHEALTH HENDERSONVILLE | PSI_09 | No Different Than the National Rate | 2.07 | 07/01/2023 | 06/30/2025 |
| 2 | 340023 | ADVENTHEALTH HENDERSONVILLE | PSI_10 | No Different Than the National Rate | 1.51 | 07/01/2023 | 06/30/2025 |
| 2 | 340023 | ADVENTHEALTH HENDERSONVILLE | PSI_11 | No Different Than the National Rate | 6.65 | 07/01/2023 | 06/30/2025 |
| 2 | 340023 | ADVENTHEALTH HENDERSONVILLE | PSI_12 | No Different Than the National Rate | 3.52 | 07/01/2023 | 06/30/2025 |
| 2 | 340023 | ADVENTHEALTH HENDERSONVILLE | PSI_13 | No Different Than the National Rate | 4.12 | 07/01/2023 | 06/30/2025 |
| 2 | 340023 | ADVENTHEALTH HENDERSONVILLE | PSI_14 | No Different Than the National Rate | 1.65 | 07/01/2023 | 06/30/2025 |
| 2 | 340023 | ADVENTHEALTH HENDERSONVILLE | PSI_15 | No Different Than the National Rate | 0.91 | 07/01/2023 | 06/30/2025 |
| 2 | 340023 | ADVENTHEALTH HENDERSONVILLE | PSI_90 | No Different Than the National Value | 0.86 | 07/01/2023 | 06/30/2025 |
| 3 | 340053 | NOVANT HEALTH PRESBYTERIAN MEDICAL CENTER | COMP_HIP_KNEE | Not Available | 3.6 | 04/01/2023 | 03/31/2025 |
| 3 | 340053 | NOVANT HEALTH PRESBYTERIAN MEDICAL CENTER | Hybrid_HWM | Not Available | 3.9 | 07/01/2024 | 06/30/2025 |
| 3 | 340053 | NOVANT HEALTH PRESBYTERIAN MEDICAL CENTER | ISCMR | No Different Than the National Rate | 52.81 | 07/01/2023 | 06/30/2025 |
| 3 | 340053 | NOVANT HEALTH PRESBYTERIAN MEDICAL CENTER | MORT_30_AMI | Not Available | 10.6 | 07/01/2022 | 06/30/2025 |
| 3 | 340053 | NOVANT HEALTH PRESBYTERIAN MEDICAL CENTER | MORT_30_CABG | Not Available | 3 | 07/01/2022 | 06/30/2025 |
| 3 | 340053 | NOVANT HEALTH PRESBYTERIAN MEDICAL CENTER | MORT_30_COPD | Not Available | 9.3 | 07/01/2022 | 06/30/2025 |
| 3 | 340053 | NOVANT HEALTH PRESBYTERIAN MEDICAL CENTER | MORT_30_HF | Not Available | 9.3 | 07/01/2022 | 06/30/2025 |
| 3 | 340053 | NOVANT HEALTH PRESBYTERIAN MEDICAL CENTER | MORT_30_PN | Not Available | 14.3 | 07/01/2022 | 06/30/2025 |
| 3 | 340053 | NOVANT HEALTH PRESBYTERIAN MEDICAL CENTER | MORT_30_STK | Not Available | 10.9 | 07/01/2023 | 06/30/2025 |
| 3 | 340053 | NOVANT HEALTH PRESBYTERIAN MEDICAL CENTER | PSI_03 | No Different Than the National Rate | 0.09 | 07/01/2023 | 06/30/2025 |
| 3 | 340053 | NOVANT HEALTH PRESBYTERIAN MEDICAL CENTER | PSI_06 | No Different Than the National Rate | 0.15 | 07/01/2023 | 06/30/2025 |
| 3 | 340053 | NOVANT HEALTH PRESBYTERIAN MEDICAL CENTER | PSI_08 | No Different Than the National Rate | 0.21 | 07/01/2023 | 06/30/2025 |
| 3 | 340053 | NOVANT HEALTH PRESBYTERIAN MEDICAL CENTER | PSI_09 | No Different Than the National Rate | 2.35 | 07/01/2023 | 06/30/2025 |
| 3 | 340053 | NOVANT HEALTH PRESBYTERIAN MEDICAL CENTER | PSI_10 | No Different Than the National Rate | 1.20 | 07/01/2023 | 06/30/2025 |
| 3 | 340053 | NOVANT HEALTH PRESBYTERIAN MEDICAL CENTER | PSI_11 | Better Than the National Rate | 3.74 | 07/01/2023 | 06/30/2025 |
| 3 | 340053 | NOVANT HEALTH PRESBYTERIAN MEDICAL CENTER | PSI_12 | No Different Than the National Rate | 3.93 | 07/01/2023 | 06/30/2025 |
| 3 | 340053 | NOVANT HEALTH PRESBYTERIAN MEDICAL CENTER | PSI_13 | No Different Than the National Rate | 2.92 | 07/01/2023 | 06/30/2025 |
| 3 | 340053 | NOVANT HEALTH PRESBYTERIAN MEDICAL CENTER | PSI_14 | No Different Than the National Rate | 1.46 | 07/01/2023 | 06/30/2025 |
| 3 | 340053 | NOVANT HEALTH PRESBYTERIAN MEDICAL CENTER | PSI_15 | No Different Than the National Rate | 0.89 | 07/01/2023 | 06/30/2025 |
| 3 | 340053 | NOVANT HEALTH PRESBYTERIAN MEDICAL CENTER | PSI_90 | Better Than the National Value | 0.64 | 07/01/2023 | 06/30/2025 |
| 4 | 340061 | UNC HOSPITALS | COMP_HIP_KNEE | Not Available | 3.4 | 04/01/2023 | 03/31/2025 |
| 4 | 340061 | UNC HOSPITALS | Hybrid_HWM | Not Available | 3 | 07/01/2024 | 06/30/2025 |
| 4 | 340061 | UNC HOSPITALS | ISCMR | No Different Than the National Rate | 56.54 | 07/01/2023 | 06/30/2025 |
| 4 | 340061 | UNC HOSPITALS | MORT_30_AMI | Not Available | 11.4 | 07/01/2022 | 06/30/2025 |
| 4 | 340061 | UNC HOSPITALS | MORT_30_CABG | Not Available | 2.8 | 07/01/2022 | 06/30/2025 |
| 4 | 340061 | UNC HOSPITALS | MORT_30_COPD | Not Available | 7.2 | 07/01/2022 | 06/30/2025 |
| 4 | 340061 | UNC HOSPITALS | MORT_30_HF | Not Available | 10.6 | 07/01/2022 | 06/30/2025 |
| 4 | 340061 | UNC HOSPITALS | MORT_30_PN | Not Available | 12.1 | 07/01/2022 | 06/30/2025 |
| 4 | 340061 | UNC HOSPITALS | MORT_30_STK | Not Available | 12 | 07/01/2023 | 06/30/2025 |
| 4 | 340061 | UNC HOSPITALS | PSI_03 | No Different Than the National Rate | 0.54 | 07/01/2023 | 06/30/2025 |
| 4 | 340061 | UNC HOSPITALS | PSI_06 | No Different Than the National Rate | 0.21 | 07/01/2023 | 06/30/2025 |
| 4 | 340061 | UNC HOSPITALS | PSI_08 | No Different Than the National Rate | 0.21 | 07/01/2023 | 06/30/2025 |
| 4 | 340061 | UNC HOSPITALS | PSI_09 | No Different Than the National Rate | 2.77 | 07/01/2023 | 06/30/2025 |
| 4 | 340061 | UNC HOSPITALS | PSI_10 | No Different Than the National Rate | 1.90 | 07/01/2023 | 06/30/2025 |
| 4 | 340061 | UNC HOSPITALS | PSI_11 | No Different Than the National Rate | 9.56 | 07/01/2023 | 06/30/2025 |
| 4 | 340061 | UNC HOSPITALS | PSI_12 | No Different Than the National Rate | 3.67 | 07/01/2023 | 06/30/2025 |
| 4 | 340061 | UNC HOSPITALS | PSI_13 | No Different Than the National Rate | 3.81 | 07/01/2023 | 06/30/2025 |
| 4 | 340061 | UNC HOSPITALS | PSI_14 | No Different Than the National Rate | 1.21 | 07/01/2023 | 06/30/2025 |
| 4 | 340061 | UNC HOSPITALS | PSI_15 | No Different Than the National Rate | 1.09 | 07/01/2023 | 06/30/2025 |
| 4 | 340061 | UNC HOSPITALS | PSI_90 | No Different Than the National Value | 1.03 | 07/01/2023 | 06/30/2025 |
| 5 | 340114 | REX HOSPITAL | COMP_HIP_KNEE | Not Available | 3.6 | 04/01/2023 | 03/31/2025 |
| 5 | 340114 | REX HOSPITAL | Hybrid_HWM | Not Available | 3 | 07/01/2024 | 06/30/2025 |
| 5 | 340114 | REX HOSPITAL | ISCMR | No Different Than the National Rate | 43.46 | 07/01/2023 | 06/30/2025 |
| 5 | 340114 | REX HOSPITAL | MORT_30_AMI | Not Available | 10.5 | 07/01/2022 | 06/30/2025 |
| 5 | 340114 | REX HOSPITAL | MORT_30_CABG | Not Available | 1.2 | 07/01/2022 | 06/30/2025 |
| 5 | 340114 | REX HOSPITAL | MORT_30_COPD | Not Available | 8.7 | 07/01/2022 | 06/30/2025 |
| 5 | 340114 | REX HOSPITAL | MORT_30_HF | Not Available | 8.2 | 07/01/2022 | 06/30/2025 |
| 5 | 340114 | REX HOSPITAL | MORT_30_PN | Not Available | 13.9 | 07/01/2022 | 06/30/2025 |
| 5 | 340114 | REX HOSPITAL | MORT_30_STK | Not Available | 10.1 | 07/01/2023 | 06/30/2025 |
| 5 | 340114 | REX HOSPITAL | PSI_03 | No Different Than the National Rate | 0.30 | 07/01/2023 | 06/30/2025 |
| 5 | 340114 | REX HOSPITAL | PSI_06 | No Different Than the National Rate | 0.24 | 07/01/2023 | 06/30/2025 |
| 5 | 340114 | REX HOSPITAL | PSI_08 | No Different Than the National Rate | 0.23 | 07/01/2023 | 06/30/2025 |
| 5 | 340114 | REX HOSPITAL | PSI_09 | No Different Than the National Rate | 1.92 | 07/01/2023 | 06/30/2025 |
| 5 | 340114 | REX HOSPITAL | PSI_10 | No Different Than the National Rate | 1.08 | 07/01/2023 | 06/30/2025 |
| 5 | 340114 | REX HOSPITAL | PSI_11 | No Different Than the National Rate | 5.17 | 07/01/2023 | 06/30/2025 |
| 5 | 340114 | REX HOSPITAL | PSI_12 | No Different Than the National Rate | 2.27 | 07/01/2023 | 06/30/2025 |
| 5 | 340114 | REX HOSPITAL | PSI_13 | No Different Than the National Rate | 3.64 | 07/01/2023 | 06/30/2025 |
| 5 | 340114 | REX HOSPITAL | PSI_14 | No Different Than the National Rate | 1.25 | 07/01/2023 | 06/30/2025 |
| 5 | 340114 | REX HOSPITAL | PSI_15 | No Different Than the National Rate | 0.61 | 07/01/2023 | 06/30/2025 |
| 5 | 340114 | REX HOSPITAL | PSI_90 | Better Than the National Value | 0.70 | 07/01/2023 | 06/30/2025 |
| 6 | 340148 | NOVANT HEALTH MEDICAL PARK HOSPITAL | COMP_HIP_KNEE | Not Available | Not Available | 04/01/2023 | 03/31/2025 |
| 6 | 340148 | NOVANT HEALTH MEDICAL PARK HOSPITAL | Hybrid_HWM | Not Available | 4.2 | 07/01/2024 | 06/30/2025 |
| 6 | 340148 | NOVANT HEALTH MEDICAL PARK HOSPITAL | ISCMR | No Different Than the National Rate | 50.75 | 07/01/2023 | 06/30/2025 |
| 6 | 340148 | NOVANT HEALTH MEDICAL PARK HOSPITAL | MORT_30_AMI | Not Available | Not Available | 07/01/2022 | 06/30/2025 |
| 6 | 340148 | NOVANT HEALTH MEDICAL PARK HOSPITAL | MORT_30_CABG | Not Available | Not Available | 07/01/2022 | 06/30/2025 |
| 6 | 340148 | NOVANT HEALTH MEDICAL PARK HOSPITAL | MORT_30_COPD | Not Available | Not Available | 07/01/2022 | 06/30/2025 |
| 6 | 340148 | NOVANT HEALTH MEDICAL PARK HOSPITAL | MORT_30_HF | Not Available | Not Available | 07/01/2022 | 06/30/2025 |
| 6 | 340148 | NOVANT HEALTH MEDICAL PARK HOSPITAL | MORT_30_PN | Not Available | Not Available | 07/01/2022 | 06/30/2025 |
| 6 | 340148 | NOVANT HEALTH MEDICAL PARK HOSPITAL | MORT_30_STK | Not Available | Not Available | 07/01/2023 | 06/30/2025 |
| 6 | 340148 | NOVANT HEALTH MEDICAL PARK HOSPITAL | PSI_03 | No Different Than the National Rate | 0.52 | 07/01/2023 | 06/30/2025 |
| 6 | 340148 | NOVANT HEALTH MEDICAL PARK HOSPITAL | PSI_06 | No Different Than the National Rate | 0.18 | 07/01/2023 | 06/30/2025 |
| 6 | 340148 | NOVANT HEALTH MEDICAL PARK HOSPITAL | PSI_08 | No Different Than the National Rate | 0.24 | 07/01/2023 | 06/30/2025 |
| 6 | 340148 | NOVANT HEALTH MEDICAL PARK HOSPITAL | PSI_09 | No Different Than the National Rate | 2.13 | 07/01/2023 | 06/30/2025 |
| 6 | 340148 | NOVANT HEALTH MEDICAL PARK HOSPITAL | PSI_10 | No Different Than the National Rate | 1.49 | 07/01/2023 | 06/30/2025 |
| 6 | 340148 | NOVANT HEALTH MEDICAL PARK HOSPITAL | PSI_11 | No Different Than the National Rate | 6.57 | 07/01/2023 | 06/30/2025 |
| 6 | 340148 | NOVANT HEALTH MEDICAL PARK HOSPITAL | PSI_12 | No Different Than the National Rate | 3.05 | 07/01/2023 | 06/30/2025 |
| 6 | 340148 | NOVANT HEALTH MEDICAL PARK HOSPITAL | PSI_13 | No Different Than the National Rate | 4.01 | 07/01/2023 | 06/30/2025 |
| 6 | 340148 | NOVANT HEALTH MEDICAL PARK HOSPITAL | PSI_14 | No Different Than the National Rate | 1.65 | 07/01/2023 | 06/30/2025 |
| 6 | 340148 | NOVANT HEALTH MEDICAL PARK HOSPITAL | PSI_15 | No Different Than the National Rate | 0.96 | 07/01/2023 | 06/30/2025 |
| 6 | 340148 | NOVANT HEALTH MEDICAL PARK HOSPITAL | PSI_90 | No Different Than the National Value | 0.89 | 07/01/2023 | 06/30/2025 |
| 7 | 340155 | DUKE REGIONAL HOSPITAL | COMP_HIP_KNEE | Not Available | 3.5 | 04/01/2023 | 03/31/2025 |
| 7 | 340155 | DUKE REGIONAL HOSPITAL | Hybrid_HWM | Not Available | 2.5 | 07/01/2024 | 06/30/2025 |
| 7 | 340155 | DUKE REGIONAL HOSPITAL | ISCMR | No Different Than the National Rate | 37.77 | 07/01/2023 | 06/30/2025 |
| 7 | 340155 | DUKE REGIONAL HOSPITAL | MORT_30_AMI | Not Available | 11.5 | 07/01/2022 | 06/30/2025 |
| 7 | 340155 | DUKE REGIONAL HOSPITAL | MORT_30_CABG | Not Available | Not Available | 07/01/2022 | 06/30/2025 |
| 7 | 340155 | DUKE REGIONAL HOSPITAL | MORT_30_COPD | Not Available | 7.3 | 07/01/2022 | 06/30/2025 |
| 7 | 340155 | DUKE REGIONAL HOSPITAL | MORT_30_HF | Not Available | 11.7 | 07/01/2022 | 06/30/2025 |
| 7 | 340155 | DUKE REGIONAL HOSPITAL | MORT_30_PN | Not Available | 13.4 | 07/01/2022 | 06/30/2025 |
| 7 | 340155 | DUKE REGIONAL HOSPITAL | MORT_30_STK | Not Available | 9.5 | 07/01/2023 | 06/30/2025 |
| 7 | 340155 | DUKE REGIONAL HOSPITAL | PSI_03 | No Different Than the National Rate | 0.64 | 07/01/2023 | 06/30/2025 |
| 7 | 340155 | DUKE REGIONAL HOSPITAL | PSI_06 | No Different Than the National Rate | 0.20 | 07/01/2023 | 06/30/2025 |
| 7 | 340155 | DUKE REGIONAL HOSPITAL | PSI_08 | No Different Than the National Rate | 0.23 | 07/01/2023 | 06/30/2025 |
| 7 | 340155 | DUKE REGIONAL HOSPITAL | PSI_09 | No Different Than the National Rate | 2.11 | 07/01/2023 | 06/30/2025 |
| 7 | 340155 | DUKE REGIONAL HOSPITAL | PSI_10 | No Different Than the National Rate | 1.83 | 07/01/2023 | 06/30/2025 |
| 7 | 340155 | DUKE REGIONAL HOSPITAL | PSI_11 | No Different Than the National Rate | 4.89 | 07/01/2023 | 06/30/2025 |
| 7 | 340155 | DUKE REGIONAL HOSPITAL | PSI_12 | No Different Than the National Rate | 4.14 | 07/01/2023 | 06/30/2025 |
| 7 | 340155 | DUKE REGIONAL HOSPITAL | PSI_13 | No Different Than the National Rate | 2.99 | 07/01/2023 | 06/30/2025 |
| 7 | 340155 | DUKE REGIONAL HOSPITAL | PSI_14 | No Different Than the National Rate | 1.57 | 07/01/2023 | 06/30/2025 |
| 7 | 340155 | DUKE REGIONAL HOSPITAL | PSI_15 | No Different Than the National Rate | 1.12 | 07/01/2023 | 06/30/2025 |
| 7 | 340155 | DUKE REGIONAL HOSPITAL | PSI_90 | No Different Than the National Value | 0.91 | 07/01/2023 | 06/30/2025 |
| 8 | 340171 | NOVANT HEALTH MATTHEWS MEDICAL CENTER | COMP_HIP_KNEE | Not Available | 3.6 | 04/01/2023 | 03/31/2025 |
| 8 | 340171 | NOVANT HEALTH MATTHEWS MEDICAL CENTER | Hybrid_HWM | Not Available | 3.5 | 07/01/2024 | 06/30/2025 |
| 8 | 340171 | NOVANT HEALTH MATTHEWS MEDICAL CENTER | ISCMR | No Different Than the National Rate | 47.68 | 07/01/2023 | 06/30/2025 |
| 8 | 340171 | NOVANT HEALTH MATTHEWS MEDICAL CENTER | MORT_30_AMI | Not Available | 10.3 | 07/01/2022 | 06/30/2025 |
| 8 | 340171 | NOVANT HEALTH MATTHEWS MEDICAL CENTER | MORT_30_CABG | Not Available | Not Available | 07/01/2022 | 06/30/2025 |
| 8 | 340171 | NOVANT HEALTH MATTHEWS MEDICAL CENTER | MORT_30_COPD | Not Available | 8 | 07/01/2022 | 06/30/2025 |
| 8 | 340171 | NOVANT HEALTH MATTHEWS MEDICAL CENTER | MORT_30_HF | Not Available | 7.1 | 07/01/2022 | 06/30/2025 |
| 8 | 340171 | NOVANT HEALTH MATTHEWS MEDICAL CENTER | MORT_30_PN | Not Available | 11.4 | 07/01/2022 | 06/30/2025 |
| 8 | 340171 | NOVANT HEALTH MATTHEWS MEDICAL CENTER | MORT_30_STK | Not Available | 11.3 | 07/01/2023 | 06/30/2025 |
| 8 | 340171 | NOVANT HEALTH MATTHEWS MEDICAL CENTER | PSI_03 | No Different Than the National Rate | 0.48 | 07/01/2023 | 06/30/2025 |
| 8 | 340171 | NOVANT HEALTH MATTHEWS MEDICAL CENTER | PSI_06 | No Different Than the National Rate | 0.16 | 07/01/2023 | 06/30/2025 |
| 8 | 340171 | NOVANT HEALTH MATTHEWS MEDICAL CENTER | PSI_08 | No Different Than the National Rate | 0.24 | 07/01/2023 | 06/30/2025 |
| 8 | 340171 | NOVANT HEALTH MATTHEWS MEDICAL CENTER | PSI_09 | No Different Than the National Rate | 2.02 | 07/01/2023 | 06/30/2025 |
| 8 | 340171 | NOVANT HEALTH MATTHEWS MEDICAL CENTER | PSI_10 | No Different Than the National Rate | 1.48 | 07/01/2023 | 06/30/2025 |
| 8 | 340171 | NOVANT HEALTH MATTHEWS MEDICAL CENTER | PSI_11 | No Different Than the National Rate | 5.88 | 07/01/2023 | 06/30/2025 |
| 8 | 340171 | NOVANT HEALTH MATTHEWS MEDICAL CENTER | PSI_12 | No Different Than the National Rate | 5.05 | 07/01/2023 | 06/30/2025 |
| 8 | 340171 | NOVANT HEALTH MATTHEWS MEDICAL CENTER | PSI_13 | No Different Than the National Rate | 3.70 | 07/01/2023 | 06/30/2025 |
| 8 | 340171 | NOVANT HEALTH MATTHEWS MEDICAL CENTER | PSI_14 | No Different Than the National Rate | 1.54 | 07/01/2023 | 06/30/2025 |
| 8 | 340171 | NOVANT HEALTH MATTHEWS MEDICAL CENTER | PSI_15 | No Different Than the National Rate | 0.79 | 07/01/2023 | 06/30/2025 |
| 8 | 340171 | NOVANT HEALTH MATTHEWS MEDICAL CENTER | PSI_90 | No Different Than the National Value | 0.93 | 07/01/2023 | 06/30/2025 |
| 9 | 340173 | WAKEMED, CARY HOSPITAL | COMP_HIP_KNEE | Not Available | 4.1 | 04/01/2023 | 03/31/2025 |
| 9 | 340173 | WAKEMED, CARY HOSPITAL | Hybrid_HWM | Not Available | 2.7 | 07/01/2024 | 06/30/2025 |
| 9 | 340173 | WAKEMED, CARY HOSPITAL | ISCMR | No Different Than the National Rate | 50.24 | 07/01/2023 | 06/30/2025 |
| 9 | 340173 | WAKEMED, CARY HOSPITAL | MORT_30_AMI | Not Available | 14 | 07/01/2022 | 06/30/2025 |
| 9 | 340173 | WAKEMED, CARY HOSPITAL | MORT_30_CABG | Not Available | Not Available | 07/01/2022 | 06/30/2025 |
| 9 | 340173 | WAKEMED, CARY HOSPITAL | MORT_30_COPD | Not Available | 7.4 | 07/01/2022 | 06/30/2025 |
| 9 | 340173 | WAKEMED, CARY HOSPITAL | MORT_30_HF | Not Available | 11.3 | 07/01/2022 | 06/30/2025 |
| 9 | 340173 | WAKEMED, CARY HOSPITAL | MORT_30_PN | Not Available | 13.9 | 07/01/2022 | 06/30/2025 |
| 9 | 340173 | WAKEMED, CARY HOSPITAL | MORT_30_STK | Not Available | 10.5 | 07/01/2023 | 06/30/2025 |
| 9 | 340173 | WAKEMED, CARY HOSPITAL | PSI_03 | No Different Than the National Rate | 1.04 | 07/01/2023 | 06/30/2025 |
| 9 | 340173 | WAKEMED, CARY HOSPITAL | PSI_06 | No Different Than the National Rate | 0.14 | 07/01/2023 | 06/30/2025 |
| 9 | 340173 | WAKEMED, CARY HOSPITAL | PSI_08 | No Different Than the National Rate | 0.23 | 07/01/2023 | 06/30/2025 |
| 9 | 340173 | WAKEMED, CARY HOSPITAL | PSI_09 | No Different Than the National Rate | 2.16 | 07/01/2023 | 06/30/2025 |
| 9 | 340173 | WAKEMED, CARY HOSPITAL | PSI_10 | No Different Than the National Rate | 1.40 | 07/01/2023 | 06/30/2025 |
| 9 | 340173 | WAKEMED, CARY HOSPITAL | PSI_11 | No Different Than the National Rate | 6.72 | 07/01/2023 | 06/30/2025 |
| 9 | 340173 | WAKEMED, CARY HOSPITAL | PSI_12 | No Different Than the National Rate | 4.74 | 07/01/2023 | 06/30/2025 |
| 9 | 340173 | WAKEMED, CARY HOSPITAL | PSI_13 | No Different Than the National Rate | 3.38 | 07/01/2023 | 06/30/2025 |
| 9 | 340173 | WAKEMED, CARY HOSPITAL | PSI_14 | No Different Than the National Rate | 2.00 | 07/01/2023 | 06/30/2025 |
| 9 | 340173 | WAKEMED, CARY HOSPITAL | PSI_15 | No Different Than the National Rate | 0.74 | 07/01/2023 | 06/30/2025 |
| 9 | 340173 | WAKEMED, CARY HOSPITAL | PSI_90 | No Different Than the National Value | 1.10 | 07/01/2023 | 06/30/2025 |
| 10 | 340190 | NOVANT HEALTH MINT HILL MEDICAL CENTER | COMP_HIP_KNEE | Not Available | Not Available | 04/01/2023 | 03/31/2025 |
| 10 | 340190 | NOVANT HEALTH MINT HILL MEDICAL CENTER | Hybrid_HWM | Not Available | 3.5 | 07/01/2024 | 06/30/2025 |
| 10 | 340190 | NOVANT HEALTH MINT HILL MEDICAL CENTER | ISCMR | Number of Cases Too Small | Not Available | 07/01/2023 | 06/30/2025 |
| 10 | 340190 | NOVANT HEALTH MINT HILL MEDICAL CENTER | MORT_30_AMI | Not Available | Not Available | 07/01/2022 | 06/30/2025 |
| 10 | 340190 | NOVANT HEALTH MINT HILL MEDICAL CENTER | MORT_30_CABG | Not Available | Not Available | 07/01/2022 | 06/30/2025 |
| 10 | 340190 | NOVANT HEALTH MINT HILL MEDICAL CENTER | MORT_30_COPD | Not Available | 9.7 | 07/01/2022 | 06/30/2025 |
| 10 | 340190 | NOVANT HEALTH MINT HILL MEDICAL CENTER | MORT_30_HF | Not Available | 9.7 | 07/01/2022 | 06/30/2025 |
| 10 | 340190 | NOVANT HEALTH MINT HILL MEDICAL CENTER | MORT_30_PN | Not Available | 11.2 | 07/01/2022 | 06/30/2025 |
| 10 | 340190 | NOVANT HEALTH MINT HILL MEDICAL CENTER | MORT_30_STK | Not Available | 8.8 | 07/01/2023 | 06/30/2025 |
| 10 | 340190 | NOVANT HEALTH MINT HILL MEDICAL CENTER | PSI_03 | No Different Than the National Rate | 0.45 | 07/01/2023 | 06/30/2025 |
| 10 | 340190 | NOVANT HEALTH MINT HILL MEDICAL CENTER | PSI_06 | No Different Than the National Rate | 0.18 | 07/01/2023 | 06/30/2025 |
| 10 | 340190 | NOVANT HEALTH MINT HILL MEDICAL CENTER | PSI_08 | No Different Than the National Rate | 0.26 | 07/01/2023 | 06/30/2025 |
| 10 | 340190 | NOVANT HEALTH MINT HILL MEDICAL CENTER | PSI_09 | No Different Than the National Rate | 2.24 | 07/01/2023 | 06/30/2025 |
| 10 | 340190 | NOVANT HEALTH MINT HILL MEDICAL CENTER | PSI_10 | No Different Than the National Rate | 1.55 | 07/01/2023 | 06/30/2025 |
| 10 | 340190 | NOVANT HEALTH MINT HILL MEDICAL CENTER | PSI_11 | No Different Than the National Rate | 7.79 | 07/01/2023 | 06/30/2025 |
| 10 | 340190 | NOVANT HEALTH MINT HILL MEDICAL CENTER | PSI_12 | No Different Than the National Rate | 3.23 | 07/01/2023 | 06/30/2025 |
| 10 | 340190 | NOVANT HEALTH MINT HILL MEDICAL CENTER | PSI_13 | No Different Than the National Rate | 4.81 | 07/01/2023 | 06/30/2025 |
| 10 | 340190 | NOVANT HEALTH MINT HILL MEDICAL CENTER | PSI_14 | Number of Cases Too Small | Not Available | 07/01/2023 | 06/30/2025 |
| 10 | 340190 | NOVANT HEALTH MINT HILL MEDICAL CENTER | PSI_15 | No Different Than the National Rate | 1.02 | 07/01/2023 | 06/30/2025 |
| 10 | 340190 | NOVANT HEALTH MINT HILL MEDICAL CENTER | PSI_90 | No Different Than the National Value | 0.95 | 07/01/2023 | 06/30/2025 |
| 11 | 420033 | PRISMA HEALTH GREER MEMORIAL HOSPITAL | COMP_HIP_KNEE | Not Available | Not Available | 04/01/2023 | 03/31/2025 |
| 11 | 420033 | PRISMA HEALTH GREER MEMORIAL HOSPITAL | Hybrid_HWM | Not Available | 3.2 | 07/01/2024 | 06/30/2025 |
| 11 | 420033 | PRISMA HEALTH GREER MEMORIAL HOSPITAL | ISCMR | No Different Than the National Rate | 47.48 | 07/01/2023 | 06/30/2025 |
| 11 | 420033 | PRISMA HEALTH GREER MEMORIAL HOSPITAL | MORT_30_AMI | Not Available | Not Available | 07/01/2022 | 06/30/2025 |
| 11 | 420033 | PRISMA HEALTH GREER MEMORIAL HOSPITAL | MORT_30_CABG | Not Available | Not Available | 07/01/2022 | 06/30/2025 |
| 11 | 420033 | PRISMA HEALTH GREER MEMORIAL HOSPITAL | MORT_30_COPD | Not Available | 9 | 07/01/2022 | 06/30/2025 |
| 11 | 420033 | PRISMA HEALTH GREER MEMORIAL HOSPITAL | MORT_30_HF | Not Available | 8.9 | 07/01/2022 | 06/30/2025 |
| 11 | 420033 | PRISMA HEALTH GREER MEMORIAL HOSPITAL | MORT_30_PN | Not Available | 14.2 | 07/01/2022 | 06/30/2025 |
| 11 | 420033 | PRISMA HEALTH GREER MEMORIAL HOSPITAL | MORT_30_STK | Not Available | 9.1 | 07/01/2023 | 06/30/2025 |
| 11 | 420033 | PRISMA HEALTH GREER MEMORIAL HOSPITAL | PSI_03 | No Different Than the National Rate | 0.32 | 07/01/2023 | 06/30/2025 |
| 11 | 420033 | PRISMA HEALTH GREER MEMORIAL HOSPITAL | PSI_06 | No Different Than the National Rate | 0.17 | 07/01/2023 | 06/30/2025 |
| 11 | 420033 | PRISMA HEALTH GREER MEMORIAL HOSPITAL | PSI_08 | No Different Than the National Rate | 0.29 | 07/01/2023 | 06/30/2025 |
| 11 | 420033 | PRISMA HEALTH GREER MEMORIAL HOSPITAL | PSI_09 | No Different Than the National Rate | 2.16 | 07/01/2023 | 06/30/2025 |
| 11 | 420033 | PRISMA HEALTH GREER MEMORIAL HOSPITAL | PSI_10 | No Different Than the National Rate | 1.54 | 07/01/2023 | 06/30/2025 |
| 11 | 420033 | PRISMA HEALTH GREER MEMORIAL HOSPITAL | PSI_11 | No Different Than the National Rate | 9.80 | 07/01/2023 | 06/30/2025 |
| 11 | 420033 | PRISMA HEALTH GREER MEMORIAL HOSPITAL | PSI_12 | No Different Than the National Rate | 3.54 | 07/01/2023 | 06/30/2025 |
| 11 | 420033 | PRISMA HEALTH GREER MEMORIAL HOSPITAL | PSI_13 | No Different Than the National Rate | 4.64 | 07/01/2023 | 06/30/2025 |
| 11 | 420033 | PRISMA HEALTH GREER MEMORIAL HOSPITAL | PSI_14 | No Different Than the National Rate | 1.66 | 07/01/2023 | 06/30/2025 |
| 11 | 420033 | PRISMA HEALTH GREER MEMORIAL HOSPITAL | PSI_15 | No Different Than the National Rate | 1.30 | 07/01/2023 | 06/30/2025 |
| 11 | 420033 | PRISMA HEALTH GREER MEMORIAL HOSPITAL | PSI_90 | No Different Than the National Value | 0.99 | 07/01/2023 | 06/30/2025 |
| 12 | 420102 | PRISMA HEALTH  PATEWOOD HOSPITAL | COMP_HIP_KNEE | Not Available | 3.8 | 04/01/2023 | 03/31/2025 |
| 12 | 420102 | PRISMA HEALTH  PATEWOOD HOSPITAL | Hybrid_HWM | Not Available | 4 | 07/01/2024 | 06/30/2025 |
| 12 | 420102 | PRISMA HEALTH  PATEWOOD HOSPITAL | ISCMR | No Different Than the National Rate | 44.86 | 07/01/2023 | 06/30/2025 |
| 12 | 420102 | PRISMA HEALTH  PATEWOOD HOSPITAL | MORT_30_AMI | Not Available | Not Available | 07/01/2022 | 06/30/2025 |
| 12 | 420102 | PRISMA HEALTH  PATEWOOD HOSPITAL | MORT_30_CABG | Not Available | Not Available | 07/01/2022 | 06/30/2025 |
| 12 | 420102 | PRISMA HEALTH  PATEWOOD HOSPITAL | MORT_30_COPD | Not Available | Not Available | 07/01/2022 | 06/30/2025 |
| 12 | 420102 | PRISMA HEALTH  PATEWOOD HOSPITAL | MORT_30_HF | Not Available | Not Available | 07/01/2022 | 06/30/2025 |
| 12 | 420102 | PRISMA HEALTH  PATEWOOD HOSPITAL | MORT_30_PN | Not Available | Not Available | 07/01/2022 | 06/30/2025 |
| 12 | 420102 | PRISMA HEALTH  PATEWOOD HOSPITAL | MORT_30_STK | Not Available | Not Available | 07/01/2023 | 06/30/2025 |
| 12 | 420102 | PRISMA HEALTH  PATEWOOD HOSPITAL | PSI_03 | No Different Than the National Rate | 0.51 | 07/01/2023 | 06/30/2025 |
| 12 | 420102 | PRISMA HEALTH  PATEWOOD HOSPITAL | PSI_06 | No Different Than the National Rate | 0.18 | 07/01/2023 | 06/30/2025 |
| 12 | 420102 | PRISMA HEALTH  PATEWOOD HOSPITAL | PSI_08 | No Different Than the National Rate | 0.23 | 07/01/2023 | 06/30/2025 |
| 12 | 420102 | PRISMA HEALTH  PATEWOOD HOSPITAL | PSI_09 | No Different Than the National Rate | 2.19 | 07/01/2023 | 06/30/2025 |
| 12 | 420102 | PRISMA HEALTH  PATEWOOD HOSPITAL | PSI_10 | No Different Than the National Rate | 1.53 | 07/01/2023 | 06/30/2025 |
| 12 | 420102 | PRISMA HEALTH  PATEWOOD HOSPITAL | PSI_11 | No Different Than the National Rate | 6.99 | 07/01/2023 | 06/30/2025 |
| 12 | 420102 | PRISMA HEALTH  PATEWOOD HOSPITAL | PSI_12 | No Different Than the National Rate | 3.03 | 07/01/2023 | 06/30/2025 |
| 12 | 420102 | PRISMA HEALTH  PATEWOOD HOSPITAL | PSI_13 | No Different Than the National Rate | 4.52 | 07/01/2023 | 06/30/2025 |
| 12 | 420102 | PRISMA HEALTH  PATEWOOD HOSPITAL | PSI_14 | Number of Cases Too Small | Not Available | 07/01/2023 | 06/30/2025 |
| 12 | 420102 | PRISMA HEALTH  PATEWOOD HOSPITAL | PSI_15 | Number of Cases Too Small | Not Available | 07/01/2023 | 06/30/2025 |
| 12 | 420102 | PRISMA HEALTH  PATEWOOD HOSPITAL | PSI_90 | No Different Than the National Value | 0.92 | 07/01/2023 | 06/30/2025 |
| 13 | 420103 | PELHAM MEDICAL CENTER | COMP_HIP_KNEE | Not Available | Not Available | 04/01/2023 | 03/31/2025 |
| 13 | 420103 | PELHAM MEDICAL CENTER | Hybrid_HWM | Not Available | 3.7 | 07/01/2024 | 06/30/2025 |
| 13 | 420103 | PELHAM MEDICAL CENTER | ISCMR | No Different Than the National Rate | 47.25 | 07/01/2023 | 06/30/2025 |
| 13 | 420103 | PELHAM MEDICAL CENTER | MORT_30_AMI | Not Available | Not Available | 07/01/2022 | 06/30/2025 |
| 13 | 420103 | PELHAM MEDICAL CENTER | MORT_30_CABG | Not Available | Not Available | 07/01/2022 | 06/30/2025 |
| 13 | 420103 | PELHAM MEDICAL CENTER | MORT_30_COPD | Not Available | 7.4 | 07/01/2022 | 06/30/2025 |
| 13 | 420103 | PELHAM MEDICAL CENTER | MORT_30_HF | Not Available | 9.2 | 07/01/2022 | 06/30/2025 |
| 13 | 420103 | PELHAM MEDICAL CENTER | MORT_30_PN | Not Available | 13 | 07/01/2022 | 06/30/2025 |
| 13 | 420103 | PELHAM MEDICAL CENTER | MORT_30_STK | Not Available | 17.3 | 07/01/2023 | 06/30/2025 |
| 13 | 420103 | PELHAM MEDICAL CENTER | PSI_03 | No Different Than the National Rate | 0.35 | 07/01/2023 | 06/30/2025 |
| 13 | 420103 | PELHAM MEDICAL CENTER | PSI_06 | No Different Than the National Rate | 0.17 | 07/01/2023 | 06/30/2025 |
| 13 | 420103 | PELHAM MEDICAL CENTER | PSI_08 | No Different Than the National Rate | 0.26 | 07/01/2023 | 06/30/2025 |
| 13 | 420103 | PELHAM MEDICAL CENTER | PSI_09 | No Different Than the National Rate | 2.05 | 07/01/2023 | 06/30/2025 |
| 13 | 420103 | PELHAM MEDICAL CENTER | PSI_10 | No Different Than the National Rate | 1.52 | 07/01/2023 | 06/30/2025 |
| 13 | 420103 | PELHAM MEDICAL CENTER | PSI_11 | No Different Than the National Rate | 7.66 | 07/01/2023 | 06/30/2025 |
| 13 | 420103 | PELHAM MEDICAL CENTER | PSI_12 | No Different Than the National Rate | 3.07 | 07/01/2023 | 06/30/2025 |
| 13 | 420103 | PELHAM MEDICAL CENTER | PSI_13 | No Different Than the National Rate | 3.67 | 07/01/2023 | 06/30/2025 |
| 13 | 420103 | PELHAM MEDICAL CENTER | PSI_14 | No Different Than the National Rate | 1.64 | 07/01/2023 | 06/30/2025 |
| 13 | 420103 | PELHAM MEDICAL CENTER | PSI_15 | No Different Than the National Rate | 0.95 | 07/01/2023 | 06/30/2025 |
| 13 | 420103 | PELHAM MEDICAL CENTER | PSI_90 | No Different Than the National Value | 0.85 | 07/01/2023 | 06/30/2025 |
| 14 | 420104 | MOUNT PLEASANT HOSPITAL | COMP_HIP_KNEE | Not Available | 3.1 | 04/01/2023 | 03/31/2025 |
| 14 | 420104 | MOUNT PLEASANT HOSPITAL | Hybrid_HWM | Not Available | 3.3 | 07/01/2024 | 06/30/2025 |
| 14 | 420104 | MOUNT PLEASANT HOSPITAL | ISCMR | No Different Than the National Rate | 40.11 | 07/01/2023 | 06/30/2025 |
| 14 | 420104 | MOUNT PLEASANT HOSPITAL | MORT_30_AMI | Not Available | Not Available | 07/01/2022 | 06/30/2025 |
| 14 | 420104 | MOUNT PLEASANT HOSPITAL | MORT_30_CABG | Not Available | Not Available | 07/01/2022 | 06/30/2025 |
| 14 | 420104 | MOUNT PLEASANT HOSPITAL | MORT_30_COPD | Not Available | 6.8 | 07/01/2022 | 06/30/2025 |
| 14 | 420104 | MOUNT PLEASANT HOSPITAL | MORT_30_HF | Not Available | 9.8 | 07/01/2022 | 06/30/2025 |
| 14 | 420104 | MOUNT PLEASANT HOSPITAL | MORT_30_PN | Not Available | 13.1 | 07/01/2022 | 06/30/2025 |
| 14 | 420104 | MOUNT PLEASANT HOSPITAL | MORT_30_STK | Not Available | 9 | 07/01/2023 | 06/30/2025 |
| 14 | 420104 | MOUNT PLEASANT HOSPITAL | PSI_03 | No Different Than the National Rate | 0.31 | 07/01/2023 | 06/30/2025 |
| 14 | 420104 | MOUNT PLEASANT HOSPITAL | PSI_06 | No Different Than the National Rate | 0.17 | 07/01/2023 | 06/30/2025 |
| 14 | 420104 | MOUNT PLEASANT HOSPITAL | PSI_08 | No Different Than the National Rate | 0.25 | 07/01/2023 | 06/30/2025 |
| 14 | 420104 | MOUNT PLEASANT HOSPITAL | PSI_09 | No Different Than the National Rate | 2.39 | 07/01/2023 | 06/30/2025 |
| 14 | 420104 | MOUNT PLEASANT HOSPITAL | PSI_10 | No Different Than the National Rate | 1.50 | 07/01/2023 | 06/30/2025 |
| 14 | 420104 | MOUNT PLEASANT HOSPITAL | PSI_11 | No Different Than the National Rate | 7.75 | 07/01/2023 | 06/30/2025 |
| 14 | 420104 | MOUNT PLEASANT HOSPITAL | PSI_12 | No Different Than the National Rate | 2.95 | 07/01/2023 | 06/30/2025 |
| 14 | 420104 | MOUNT PLEASANT HOSPITAL | PSI_13 | No Different Than the National Rate | 3.96 | 07/01/2023 | 06/30/2025 |
| 14 | 420104 | MOUNT PLEASANT HOSPITAL | PSI_14 | No Different Than the National Rate | 1.62 | 07/01/2023 | 06/30/2025 |
| 14 | 420104 | MOUNT PLEASANT HOSPITAL | PSI_15 | No Different Than the National Rate | 0.87 | 07/01/2023 | 06/30/2025 |
| 14 | 420104 | MOUNT PLEASANT HOSPITAL | PSI_90 | No Different Than the National Value | 0.85 | 07/01/2023 | 06/30/2025 |
| 15 | 420110 | ROPER ST FRANCIS HOSPITAL-BERKELEY INC | COMP_HIP_KNEE | Not Available | 3.3 | 04/01/2023 | 03/31/2025 |
| 15 | 420110 | ROPER ST FRANCIS HOSPITAL-BERKELEY INC | Hybrid_HWM | Not Available | 3.7 | 07/01/2024 | 06/30/2025 |
| 15 | 420110 | ROPER ST FRANCIS HOSPITAL-BERKELEY INC | ISCMR | No Different Than the National Rate | 46.36 | 07/01/2023 | 06/30/2025 |
| 15 | 420110 | ROPER ST FRANCIS HOSPITAL-BERKELEY INC | MORT_30_AMI | Not Available | Not Available | 07/01/2022 | 06/30/2025 |
| 15 | 420110 | ROPER ST FRANCIS HOSPITAL-BERKELEY INC | MORT_30_CABG | Not Available | Not Available | 07/01/2022 | 06/30/2025 |
| 15 | 420110 | ROPER ST FRANCIS HOSPITAL-BERKELEY INC | MORT_30_COPD | Not Available | 8.6 | 07/01/2022 | 06/30/2025 |
| 15 | 420110 | ROPER ST FRANCIS HOSPITAL-BERKELEY INC | MORT_30_HF | Not Available | 11.6 | 07/01/2022 | 06/30/2025 |
| 15 | 420110 | ROPER ST FRANCIS HOSPITAL-BERKELEY INC | MORT_30_PN | Not Available | 14.1 | 07/01/2022 | 06/30/2025 |
| 15 | 420110 | ROPER ST FRANCIS HOSPITAL-BERKELEY INC | MORT_30_STK | Not Available | 9.9 | 07/01/2023 | 06/30/2025 |
| 15 | 420110 | ROPER ST FRANCIS HOSPITAL-BERKELEY INC | PSI_03 | No Different Than the National Rate | 0.34 | 07/01/2023 | 06/30/2025 |
| 15 | 420110 | ROPER ST FRANCIS HOSPITAL-BERKELEY INC | PSI_06 | No Different Than the National Rate | 0.17 | 07/01/2023 | 06/30/2025 |
| 15 | 420110 | ROPER ST FRANCIS HOSPITAL-BERKELEY INC | PSI_08 | No Different Than the National Rate | 0.23 | 07/01/2023 | 06/30/2025 |
| 15 | 420110 | ROPER ST FRANCIS HOSPITAL-BERKELEY INC | PSI_09 | No Different Than the National Rate | 2.17 | 07/01/2023 | 06/30/2025 |
| 15 | 420110 | ROPER ST FRANCIS HOSPITAL-BERKELEY INC | PSI_10 | No Different Than the National Rate | 1.54 | 07/01/2023 | 06/30/2025 |
| 15 | 420110 | ROPER ST FRANCIS HOSPITAL-BERKELEY INC | PSI_11 | No Different Than the National Rate | 7.40 | 07/01/2023 | 06/30/2025 |
| 15 | 420110 | ROPER ST FRANCIS HOSPITAL-BERKELEY INC | PSI_12 | No Different Than the National Rate | 3.32 | 07/01/2023 | 06/30/2025 |
| 15 | 420110 | ROPER ST FRANCIS HOSPITAL-BERKELEY INC | PSI_13 | No Different Than the National Rate | 4.49 | 07/01/2023 | 06/30/2025 |
| 15 | 420110 | ROPER ST FRANCIS HOSPITAL-BERKELEY INC | PSI_14 | No Different Than the National Rate | 2.12 | 07/01/2023 | 06/30/2025 |
| 15 | 420110 | ROPER ST FRANCIS HOSPITAL-BERKELEY INC | PSI_15 | No Different Than the National Rate | 0.96 | 07/01/2023 | 06/30/2025 |
| 15 | 420110 | ROPER ST FRANCIS HOSPITAL-BERKELEY INC | PSI_90 | No Different Than the National Value | 0.89 | 07/01/2023 | 06/30/2025 |
| 16 | 440029 | WILLIAMSON MEDICAL CENTER | COMP_HIP_KNEE | Not Available | 6 | 04/01/2023 | 03/31/2025 |
| 16 | 440029 | WILLIAMSON MEDICAL CENTER | Hybrid_HWM | Not Available | 4.5 | 07/01/2024 | 06/30/2025 |
| 16 | 440029 | WILLIAMSON MEDICAL CENTER | ISCMR | No Different Than the National Rate | 65.44 | 07/01/2023 | 06/30/2025 |
| 16 | 440029 | WILLIAMSON MEDICAL CENTER | MORT_30_AMI | Not Available | 11 | 07/01/2022 | 06/30/2025 |
| 16 | 440029 | WILLIAMSON MEDICAL CENTER | MORT_30_CABG | Not Available | Not Available | 07/01/2022 | 06/30/2025 |
| 16 | 440029 | WILLIAMSON MEDICAL CENTER | MORT_30_COPD | Not Available | 8.1 | 07/01/2022 | 06/30/2025 |
| 16 | 440029 | WILLIAMSON MEDICAL CENTER | MORT_30_HF | Not Available | 14 | 07/01/2022 | 06/30/2025 |
| 16 | 440029 | WILLIAMSON MEDICAL CENTER | MORT_30_PN | Not Available | 14.3 | 07/01/2022 | 06/30/2025 |
| 16 | 440029 | WILLIAMSON MEDICAL CENTER | MORT_30_STK | Not Available | 11.3 | 07/01/2023 | 06/30/2025 |
| 16 | 440029 | WILLIAMSON MEDICAL CENTER | PSI_03 | No Different Than the National Rate | 0.23 | 07/01/2023 | 06/30/2025 |
| 16 | 440029 | WILLIAMSON MEDICAL CENTER | PSI_06 | No Different Than the National Rate | 0.24 | 07/01/2023 | 06/30/2025 |
| 16 | 440029 | WILLIAMSON MEDICAL CENTER | PSI_08 | No Different Than the National Rate | 0.27 | 07/01/2023 | 06/30/2025 |
| 16 | 440029 | WILLIAMSON MEDICAL CENTER | PSI_09 | No Different Than the National Rate | 2.38 | 07/01/2023 | 06/30/2025 |
| 16 | 440029 | WILLIAMSON MEDICAL CENTER | PSI_10 | No Different Than the National Rate | 1.43 | 07/01/2023 | 06/30/2025 |
| 16 | 440029 | WILLIAMSON MEDICAL CENTER | PSI_11 | No Different Than the National Rate | 9.15 | 07/01/2023 | 06/30/2025 |
| 16 | 440029 | WILLIAMSON MEDICAL CENTER | PSI_12 | No Different Than the National Rate | 2.52 | 07/01/2023 | 06/30/2025 |
| 16 | 440029 | WILLIAMSON MEDICAL CENTER | PSI_13 | No Different Than the National Rate | 4.69 | 07/01/2023 | 06/30/2025 |
| 16 | 440029 | WILLIAMSON MEDICAL CENTER | PSI_14 | No Different Than the National Rate | 1.60 | 07/01/2023 | 06/30/2025 |
| 16 | 440029 | WILLIAMSON MEDICAL CENTER | PSI_15 | No Different Than the National Rate | 1.44 | 07/01/2023 | 06/30/2025 |
| 16 | 440029 | WILLIAMSON MEDICAL CENTER | PSI_90 | No Different Than the National Value | 0.90 | 07/01/2023 | 06/30/2025 |
| 17 | 440081 | LECONTE MEDICAL CENTER | COMP_HIP_KNEE | Not Available | Not Available | 04/01/2023 | 03/31/2025 |
| 17 | 440081 | LECONTE MEDICAL CENTER | Hybrid_HWM | Not Available | 3.9 | 07/01/2024 | 06/30/2025 |
| 17 | 440081 | LECONTE MEDICAL CENTER | ISCMR | No Different Than the National Rate | 36.08 | 07/01/2023 | 06/30/2025 |
| 17 | 440081 | LECONTE MEDICAL CENTER | MORT_30_AMI | Not Available | Not Available | 07/01/2022 | 06/30/2025 |
| 17 | 440081 | LECONTE MEDICAL CENTER | MORT_30_CABG | Not Available | Not Available | 07/01/2022 | 06/30/2025 |
| 17 | 440081 | LECONTE MEDICAL CENTER | MORT_30_COPD | Not Available | 8 | 07/01/2022 | 06/30/2025 |
| 17 | 440081 | LECONTE MEDICAL CENTER | MORT_30_HF | Not Available | 12.7 | 07/01/2022 | 06/30/2025 |
| 17 | 440081 | LECONTE MEDICAL CENTER | MORT_30_PN | Not Available | 13.9 | 07/01/2022 | 06/30/2025 |
| 17 | 440081 | LECONTE MEDICAL CENTER | MORT_30_STK | Not Available | 9.6 | 07/01/2023 | 06/30/2025 |
| 17 | 440081 | LECONTE MEDICAL CENTER | PSI_03 | No Different Than the National Rate | 0.35 | 07/01/2023 | 06/30/2025 |
| 17 | 440081 | LECONTE MEDICAL CENTER | PSI_06 | No Different Than the National Rate | 0.18 | 07/01/2023 | 06/30/2025 |
| 17 | 440081 | LECONTE MEDICAL CENTER | PSI_08 | No Different Than the National Rate | 0.26 | 07/01/2023 | 06/30/2025 |
| 17 | 440081 | LECONTE MEDICAL CENTER | PSI_09 | No Different Than the National Rate | 2.21 | 07/01/2023 | 06/30/2025 |
| 17 | 440081 | LECONTE MEDICAL CENTER | PSI_10 | Number of Cases Too Small | Not Available | 07/01/2023 | 06/30/2025 |
| 17 | 440081 | LECONTE MEDICAL CENTER | PSI_11 | Number of Cases Too Small | Not Available | 07/01/2023 | 06/30/2025 |
| 17 | 440081 | LECONTE MEDICAL CENTER | PSI_12 | No Different Than the National Rate | 2.93 | 07/01/2023 | 06/30/2025 |
| 17 | 440081 | LECONTE MEDICAL CENTER | PSI_13 | Number of Cases Too Small | Not Available | 07/01/2023 | 06/30/2025 |
| 17 | 440081 | LECONTE MEDICAL CENTER | PSI_14 | No Different Than the National Rate | 1.66 | 07/01/2023 | 06/30/2025 |
| 17 | 440081 | LECONTE MEDICAL CENTER | PSI_15 | No Different Than the National Rate | 1.00 | 07/01/2023 | 06/30/2025 |
| 17 | 440081 | LECONTE MEDICAL CENTER | PSI_90 | No Different Than the National Value | 0.90 | 07/01/2023 | 06/30/2025 |
| 18 | 440091 | MEMORIAL HEALTHCARE SYSTEM, INC | COMP_HIP_KNEE | Not Available | 3.4 | 04/01/2023 | 03/31/2025 |
| 18 | 440091 | MEMORIAL HEALTHCARE SYSTEM, INC | Hybrid_HWM | Not Available | 3.8 | 07/01/2024 | 06/30/2025 |
| 18 | 440091 | MEMORIAL HEALTHCARE SYSTEM, INC | ISCMR | No Different Than the National Rate | 49.87 | 07/01/2023 | 06/30/2025 |
| 18 | 440091 | MEMORIAL HEALTHCARE SYSTEM, INC | MORT_30_AMI | Not Available | 10 | 07/01/2022 | 06/30/2025 |
| 18 | 440091 | MEMORIAL HEALTHCARE SYSTEM, INC | MORT_30_CABG | Not Available | 1.5 | 07/01/2022 | 06/30/2025 |
| 18 | 440091 | MEMORIAL HEALTHCARE SYSTEM, INC | MORT_30_COPD | Not Available | 10.6 | 07/01/2022 | 06/30/2025 |
| 18 | 440091 | MEMORIAL HEALTHCARE SYSTEM, INC | MORT_30_HF | Not Available | 12.9 | 07/01/2022 | 06/30/2025 |
| 18 | 440091 | MEMORIAL HEALTHCARE SYSTEM, INC | MORT_30_PN | Not Available | 13.4 | 07/01/2022 | 06/30/2025 |
| 18 | 440091 | MEMORIAL HEALTHCARE SYSTEM, INC | MORT_30_STK | Not Available | 10.7 | 07/01/2023 | 06/30/2025 |
| 18 | 440091 | MEMORIAL HEALTHCARE SYSTEM, INC | PSI_03 | No Different Than the National Rate | 0.66 | 07/01/2023 | 06/30/2025 |
| 18 | 440091 | MEMORIAL HEALTHCARE SYSTEM, INC | PSI_06 | No Different Than the National Rate | 0.14 | 07/01/2023 | 06/30/2025 |
| 18 | 440091 | MEMORIAL HEALTHCARE SYSTEM, INC | PSI_08 | No Different Than the National Rate | 0.28 | 07/01/2023 | 06/30/2025 |
| 18 | 440091 | MEMORIAL HEALTHCARE SYSTEM, INC | PSI_09 | No Different Than the National Rate | 2.07 | 07/01/2023 | 06/30/2025 |
| 18 | 440091 | MEMORIAL HEALTHCARE SYSTEM, INC | PSI_10 | No Different Than the National Rate | 1.10 | 07/01/2023 | 06/30/2025 |
| 18 | 440091 | MEMORIAL HEALTHCARE SYSTEM, INC | PSI_11 | No Different Than the National Rate | 7.63 | 07/01/2023 | 06/30/2025 |
| 18 | 440091 | MEMORIAL HEALTHCARE SYSTEM, INC | PSI_12 | No Different Than the National Rate | 2.19 | 07/01/2023 | 06/30/2025 |
| 18 | 440091 | MEMORIAL HEALTHCARE SYSTEM, INC | PSI_13 | No Different Than the National Rate | 4.72 | 07/01/2023 | 06/30/2025 |
| 18 | 440091 | MEMORIAL HEALTHCARE SYSTEM, INC | PSI_14 | No Different Than the National Rate | 1.30 | 07/01/2023 | 06/30/2025 |
| 18 | 440091 | MEMORIAL HEALTHCARE SYSTEM, INC | PSI_15 | No Different Than the National Rate | 0.56 | 07/01/2023 | 06/30/2025 |
| 18 | 440091 | MEMORIAL HEALTHCARE SYSTEM, INC | PSI_90 | No Different Than the National Value | 0.92 | 07/01/2023 | 06/30/2025 |
| 19 | 440193 | VANDERBILT WILSON COUNTY HOSPITAL | COMP_HIP_KNEE | Not Available | 3.9 | 04/01/2023 | 03/31/2025 |
| 19 | 440193 | VANDERBILT WILSON COUNTY HOSPITAL | Hybrid_HWM | Not Available | 3.5 | 07/01/2024 | 06/30/2025 |
| 19 | 440193 | VANDERBILT WILSON COUNTY HOSPITAL | ISCMR | No Different Than the National Rate | 47.68 | 07/01/2023 | 06/30/2025 |
| 19 | 440193 | VANDERBILT WILSON COUNTY HOSPITAL | MORT_30_AMI | Not Available | 10.9 | 07/01/2022 | 06/30/2025 |
| 19 | 440193 | VANDERBILT WILSON COUNTY HOSPITAL | MORT_30_CABG | Not Available | Not Available | 07/01/2022 | 06/30/2025 |
| 19 | 440193 | VANDERBILT WILSON COUNTY HOSPITAL | MORT_30_COPD | Not Available | 6.7 | 07/01/2022 | 06/30/2025 |
| 19 | 440193 | VANDERBILT WILSON COUNTY HOSPITAL | MORT_30_HF | Not Available | 10.5 | 07/01/2022 | 06/30/2025 |
| 19 | 440193 | VANDERBILT WILSON COUNTY HOSPITAL | MORT_30_PN | Not Available | 15.1 | 07/01/2022 | 06/30/2025 |
| 19 | 440193 | VANDERBILT WILSON COUNTY HOSPITAL | MORT_30_STK | Not Available | 11.8 | 07/01/2023 | 06/30/2025 |
| 19 | 440193 | VANDERBILT WILSON COUNTY HOSPITAL | PSI_03 | No Different Than the National Rate | 0.52 | 07/01/2023 | 06/30/2025 |
| 19 | 440193 | VANDERBILT WILSON COUNTY HOSPITAL | PSI_06 | No Different Than the National Rate | 0.16 | 07/01/2023 | 06/30/2025 |
| 19 | 440193 | VANDERBILT WILSON COUNTY HOSPITAL | PSI_08 | No Different Than the National Rate | 0.22 | 07/01/2023 | 06/30/2025 |
| 19 | 440193 | VANDERBILT WILSON COUNTY HOSPITAL | PSI_09 | No Different Than the National Rate | 2.09 | 07/01/2023 | 06/30/2025 |
| 19 | 440193 | VANDERBILT WILSON COUNTY HOSPITAL | PSI_10 | No Different Than the National Rate | 1.52 | 07/01/2023 | 06/30/2025 |
| 19 | 440193 | VANDERBILT WILSON COUNTY HOSPITAL | PSI_11 | No Different Than the National Rate | 9.14 | 07/01/2023 | 06/30/2025 |
| 19 | 440193 | VANDERBILT WILSON COUNTY HOSPITAL | PSI_12 | No Different Than the National Rate | 2.66 | 07/01/2023 | 06/30/2025 |
| 19 | 440193 | VANDERBILT WILSON COUNTY HOSPITAL | PSI_13 | No Different Than the National Rate | 5.71 | 07/01/2023 | 06/30/2025 |
| 19 | 440193 | VANDERBILT WILSON COUNTY HOSPITAL | PSI_14 | No Different Than the National Rate | 1.63 | 07/01/2023 | 06/30/2025 |
| 19 | 440193 | VANDERBILT WILSON COUNTY HOSPITAL | PSI_15 | No Different Than the National Rate | 0.97 | 07/01/2023 | 06/30/2025 |
| 19 | 440193 | VANDERBILT WILSON COUNTY HOSPITAL | PSI_90 | No Different Than the National Value | 1.01 | 07/01/2023 | 06/30/2025 |
| 20 | 440039 | VANDERBILT UNIVERSITY MEDICAL CENTER | COMP_HIP_KNEE | Not Available | 4.5 | 04/01/2023 | 03/31/2025 |
| 20 | 440039 | VANDERBILT UNIVERSITY MEDICAL CENTER | Hybrid_HWM | Not Available | 2.9 | 07/01/2024 | 06/30/2025 |
| 20 | 440039 | VANDERBILT UNIVERSITY MEDICAL CENTER | ISCMR | No Different Than the National Rate | 50.92 | 07/01/2023 | 06/30/2025 |
| 20 | 440039 | VANDERBILT UNIVERSITY MEDICAL CENTER | MORT_30_AMI | Not Available | 12.1 | 07/01/2022 | 06/30/2025 |
| 20 | 440039 | VANDERBILT UNIVERSITY MEDICAL CENTER | MORT_30_CABG | Not Available | 1.8 | 07/01/2022 | 06/30/2025 |
| 20 | 440039 | VANDERBILT UNIVERSITY MEDICAL CENTER | MORT_30_COPD | Not Available | 9.6 | 07/01/2022 | 06/30/2025 |
| 20 | 440039 | VANDERBILT UNIVERSITY MEDICAL CENTER | MORT_30_HF | Not Available | 9.2 | 07/01/2022 | 06/30/2025 |
| 20 | 440039 | VANDERBILT UNIVERSITY MEDICAL CENTER | MORT_30_PN | Not Available | 11.7 | 07/01/2022 | 06/30/2025 |
| 20 | 440039 | VANDERBILT UNIVERSITY MEDICAL CENTER | MORT_30_STK | Not Available | 10.1 | 07/01/2023 | 06/30/2025 |
| 20 | 440039 | VANDERBILT UNIVERSITY MEDICAL CENTER | PSI_03 | Worse Than the National Rate | 1.13 | 07/01/2023 | 06/30/2025 |
| 20 | 440039 | VANDERBILT UNIVERSITY MEDICAL CENTER | PSI_06 | No Different Than the National Rate | 0.24 | 07/01/2023 | 06/30/2025 |
| 20 | 440039 | VANDERBILT UNIVERSITY MEDICAL CENTER | PSI_08 | No Different Than the National Rate | 0.18 | 07/01/2023 | 06/30/2025 |
| 20 | 440039 | VANDERBILT UNIVERSITY MEDICAL CENTER | PSI_09 | No Different Than the National Rate | 2.87 | 07/01/2023 | 06/30/2025 |
| 20 | 440039 | VANDERBILT UNIVERSITY MEDICAL CENTER | PSI_10 | No Different Than the National Rate | 0.93 | 07/01/2023 | 06/30/2025 |
| 20 | 440039 | VANDERBILT UNIVERSITY MEDICAL CENTER | PSI_11 | No Different Than the National Rate | 7.15 | 07/01/2023 | 06/30/2025 |
| 20 | 440039 | VANDERBILT UNIVERSITY MEDICAL CENTER | PSI_12 | No Different Than the National Rate | 4.29 | 07/01/2023 | 06/30/2025 |
| 20 | 440039 | VANDERBILT UNIVERSITY MEDICAL CENTER | PSI_13 | No Different Than the National Rate | 5.63 | 07/01/2023 | 06/30/2025 |
| 20 | 440039 | VANDERBILT UNIVERSITY MEDICAL CENTER | PSI_14 | No Different Than the National Rate | 1.47 | 07/01/2023 | 06/30/2025 |
| 20 | 440039 | VANDERBILT UNIVERSITY MEDICAL CENTER | PSI_15 | No Different Than the National Rate | 0.84 | 07/01/2023 | 06/30/2025 |
| 20 | 440039 | VANDERBILT UNIVERSITY MEDICAL CENTER | PSI_90 | Worse Than the National Value | 1.21 | 07/01/2023 | 06/30/2025 |

## Raw excerpt: rank 1 facility

Request: GET https://data.cms.gov/provider-data/api/1/datastore/query/ynj2-r877/0?conditions%5B0%5D%5Bproperty%5D=facility_id&conditions%5B0%5D%5Bvalue%5D=340017&conditions%5B0%5D%5Boperator%5D=%3D&limit=1500&offset=0
Retrieved: 2026-11-14T01:46:21Z (UTC). Response Date header: Sat, 14 Nov 2026 01:46:21 GMT. Count returned: 20, rows returned: 20. The 20 rows below are the returned rows, one compact row per line (jq -c style), exactly as returned; they are identical to the pull 2 complications rows for this facility_id.

```
{"facility_id":"340017","facility_name":"PARDEE HOSPITAL HENDERSON COUNTY","address":"800 N JUSTICE ST","citytown":"HENDERSONVILLE","state":"NC","zip_code":"28791","countyparish":"HENDERSON","telephone_number":"(828) 696-1000","measure_id":"COMP_HIP_KNEE","measure_name":"Rate of complications for hip/knee replacement patients","compared_to_national":"Not Available","denominator":"229","score":"4","lower_estimate":"Not Available","higher_estimate":"Not Available","footnote":"","start_date":"04/01/2023","end_date":"03/31/2025"}
{"facility_id":"340017","facility_name":"PARDEE HOSPITAL HENDERSON COUNTY","address":"800 N JUSTICE ST","citytown":"HENDERSONVILLE","state":"NC","zip_code":"28791","countyparish":"HENDERSON","telephone_number":"(828) 696-1000","measure_id":"Hybrid_HWM","measure_name":"Hybrid Hospital-Wide All-Cause Risk Standardized Mortality Rate","compared_to_national":"Not Available","denominator":"2383","score":"3.5","lower_estimate":"Not Available","higher_estimate":"Not Available","footnote":"","start_date":"07/01/2024","end_date":"06/30/2025"}
{"facility_id":"340017","facility_name":"PARDEE HOSPITAL HENDERSON COUNTY","address":"800 N JUSTICE ST","citytown":"HENDERSONVILLE","state":"NC","zip_code":"28791","countyparish":"HENDERSON","telephone_number":"(828) 696-1000","measure_id":"ISCMR","measure_name":"Inpatient Surgical Complications Mortality Rate","compared_to_national":"No Different Than the National Rate","denominator":"345","score":"56.95","lower_estimate":"38.29","higher_estimate":"75.62","footnote":"","start_date":"07/01/2023","end_date":"06/30/2025"}
{"facility_id":"340017","facility_name":"PARDEE HOSPITAL HENDERSON COUNTY","address":"800 N JUSTICE ST","citytown":"HENDERSONVILLE","state":"NC","zip_code":"28791","countyparish":"HENDERSON","telephone_number":"(828) 696-1000","measure_id":"MORT_30_AMI","measure_name":"Death rate for heart attack patients","compared_to_national":"Not Available","denominator":"215","score":"12.7","lower_estimate":"Not Available","higher_estimate":"Not Available","footnote":"","start_date":"07/01/2022","end_date":"06/30/2025"}
{"facility_id":"340017","facility_name":"PARDEE HOSPITAL HENDERSON COUNTY","address":"800 N JUSTICE ST","citytown":"HENDERSONVILLE","state":"NC","zip_code":"28791","countyparish":"HENDERSON","telephone_number":"(828) 696-1000","measure_id":"MORT_30_CABG","measure_name":"Death rate for CABG surgery patients","compared_to_national":"Not Available","denominator":"Not Available","score":"Not Available","lower_estimate":"Not Available","higher_estimate":"Not Available","footnote":"5","start_date":"07/01/2022","end_date":"06/30/2025"}
{"facility_id":"340017","facility_name":"PARDEE HOSPITAL HENDERSON COUNTY","address":"800 N JUSTICE ST","citytown":"HENDERSONVILLE","state":"NC","zip_code":"28791","countyparish":"HENDERSON","telephone_number":"(828) 696-1000","measure_id":"MORT_30_COPD","measure_name":"Death rate for COPD patients","compared_to_national":"Not Available","denominator":"113","score":"9.5","lower_estimate":"Not Available","higher_estimate":"Not Available","footnote":"","start_date":"07/01/2022","end_date":"06/30/2025"}
{"facility_id":"340017","facility_name":"PARDEE HOSPITAL HENDERSON COUNTY","address":"800 N JUSTICE ST","citytown":"HENDERSONVILLE","state":"NC","zip_code":"28791","countyparish":"HENDERSON","telephone_number":"(828) 696-1000","measure_id":"MORT_30_HF","measure_name":"Death rate for heart failure patients","compared_to_national":"Not Available","denominator":"319","score":"13.1","lower_estimate":"Not Available","higher_estimate":"Not Available","footnote":"","start_date":"07/01/2022","end_date":"06/30/2025"}
{"facility_id":"340017","facility_name":"PARDEE HOSPITAL HENDERSON COUNTY","address":"800 N JUSTICE ST","citytown":"HENDERSONVILLE","state":"NC","zip_code":"28791","countyparish":"HENDERSON","telephone_number":"(828) 696-1000","measure_id":"MORT_30_PN","measure_name":"Death rate for pneumonia patients","compared_to_national":"Not Available","denominator":"319","score":"12.6","lower_estimate":"Not Available","higher_estimate":"Not Available","footnote":"","start_date":"07/01/2022","end_date":"06/30/2025"}
{"facility_id":"340017","facility_name":"PARDEE HOSPITAL HENDERSON COUNTY","address":"800 N JUSTICE ST","citytown":"HENDERSONVILLE","state":"NC","zip_code":"28791","countyparish":"HENDERSON","telephone_number":"(828) 696-1000","measure_id":"MORT_30_STK","measure_name":"Death rate for stroke patients","compared_to_national":"Not Available","denominator":"213","score":"7.6","lower_estimate":"Not Available","higher_estimate":"Not Available","footnote":"","start_date":"07/01/2023","end_date":"06/30/2025"}
{"facility_id":"340017","facility_name":"PARDEE HOSPITAL HENDERSON COUNTY","address":"800 N JUSTICE ST","citytown":"HENDERSONVILLE","state":"NC","zip_code":"28791","countyparish":"HENDERSON","telephone_number":"(828) 696-1000","measure_id":"PSI_03","measure_name":"Pressure ulcer rate","compared_to_national":"No Different Than the National Rate","denominator":"3634","score":"0.21","lower_estimate":"0","higher_estimate":"0.98","footnote":"","start_date":"07/01/2023","end_date":"06/30/2025"}
{"facility_id":"340017","facility_name":"PARDEE HOSPITAL HENDERSON COUNTY","address":"800 N JUSTICE ST","citytown":"HENDERSONVILLE","state":"NC","zip_code":"28791","countyparish":"HENDERSON","telephone_number":"(828) 696-1000","measure_id":"PSI_06","measure_name":"Iatrogenic pneumothorax rate","compared_to_national":"No Different Than the National Rate","denominator":"4823","score":"0.15","lower_estimate":"0","higher_estimate":"0.33","footnote":"","start_date":"07/01/2023","end_date":"06/30/2025"}
{"facility_id":"340017","facility_name":"PARDEE HOSPITAL HENDERSON COUNTY","address":"800 N JUSTICE ST","citytown":"HENDERSONVILLE","state":"NC","zip_code":"28791","countyparish":"HENDERSON","telephone_number":"(828) 696-1000","measure_id":"PSI_08","measure_name":"In-hospital fall-associated fracture rate","compared_to_national":"No Different Than the National Rate","denominator":"4787","score":"0.20","lower_estimate":"0.04","higher_estimate":"0.37","footnote":"","start_date":"07/01/2023","end_date":"06/30/2025"}
{"facility_id":"340017","facility_name":"PARDEE HOSPITAL HENDERSON COUNTY","address":"800 N JUSTICE ST","citytown":"HENDERSONVILLE","state":"NC","zip_code":"28791","countyparish":"HENDERSON","telephone_number":"(828) 696-1000","measure_id":"PSI_09","measure_name":"Postoperative hemorrhage or hematoma rate","compared_to_national":"No Different Than the National Rate","denominator":"996","score":"2.42","lower_estimate":"0.88","higher_estimate":"3.96","footnote":"","start_date":"07/01/2023","end_date":"06/30/2025"}
{"facility_id":"340017","facility_name":"PARDEE HOSPITAL HENDERSON COUNTY","address":"800 N JUSTICE ST","citytown":"HENDERSONVILLE","state":"NC","zip_code":"28791","countyparish":"HENDERSON","telephone_number":"(828) 696-1000","measure_id":"PSI_10","measure_name":"Postoperative acute kidney injury requiring dialysis rate","compared_to_national":"No Different Than the National Rate","denominator":"692","score":"1.36","lower_estimate":"0","higher_estimate":"2.9","footnote":"","start_date":"07/01/2023","end_date":"06/30/2025"}
{"facility_id":"340017","facility_name":"PARDEE HOSPITAL HENDERSON COUNTY","address":"800 N JUSTICE ST","citytown":"HENDERSONVILLE","state":"NC","zip_code":"28791","countyparish":"HENDERSON","telephone_number":"(828) 696-1000","measure_id":"PSI_11","measure_name":"Postoperative respiratory failure rate","compared_to_national":"No Different Than the National Rate","denominator":"688","score":"5.92","lower_estimate":"0","higher_estimate":"12.31","footnote":"","start_date":"07/01/2023","end_date":"06/30/2025"}
{"facility_id":"340017","facility_name":"PARDEE HOSPITAL HENDERSON COUNTY","address":"800 N JUSTICE ST","citytown":"HENDERSONVILLE","state":"NC","zip_code":"28791","countyparish":"HENDERSON","telephone_number":"(828) 696-1000","measure_id":"PSI_12","measure_name":"Perioperative pulmonary embolism or deep vein thrombosis rate","compared_to_national":"No Different Than the National Rate","denominator":"1298","score":"3.76","lower_estimate":"1.70","higher_estimate":"5.82","footnote":"","start_date":"07/01/2023","end_date":"06/30/2025"}
{"facility_id":"340017","facility_name":"PARDEE HOSPITAL HENDERSON COUNTY","address":"800 N JUSTICE ST","citytown":"HENDERSONVILLE","state":"NC","zip_code":"28791","countyparish":"HENDERSON","telephone_number":"(828) 696-1000","measure_id":"PSI_13","measure_name":"Postoperative sepsis rate","compared_to_national":"No Different Than the National Rate","denominator":"640","score":"4.94","lower_estimate":"0.92","higher_estimate":"8.96","footnote":"","start_date":"07/01/2023","end_date":"06/30/2025"}
{"facility_id":"340017","facility_name":"PARDEE HOSPITAL HENDERSON COUNTY","address":"800 N JUSTICE ST","citytown":"HENDERSONVILLE","state":"NC","zip_code":"28791","countyparish":"HENDERSON","telephone_number":"(828) 696-1000","measure_id":"PSI_14","measure_name":"Postoperative wound dehiscence rate","compared_to_national":"No Different Than the National Rate","denominator":"322","score":"1.56","lower_estimate":"0","higher_estimate":"3.25","footnote":"","start_date":"07/01/2023","end_date":"06/30/2025"}
{"facility_id":"340017","facility_name":"PARDEE HOSPITAL HENDERSON COUNTY","address":"800 N JUSTICE ST","citytown":"HENDERSONVILLE","state":"NC","zip_code":"28791","countyparish":"HENDERSON","telephone_number":"(828) 696-1000","measure_id":"PSI_15","measure_name":"Abdominopelvic accidental puncture or laceration rate","compared_to_national":"No Different Than the National Rate","denominator":"873","score":"1.07","lower_estimate":"0.02","higher_estimate":"2.13","footnote":"","start_date":"07/01/2023","end_date":"06/30/2025"}
{"facility_id":"340017","facility_name":"PARDEE HOSPITAL HENDERSON COUNTY","address":"800 N JUSTICE ST","citytown":"HENDERSONVILLE","state":"NC","zip_code":"28791","countyparish":"HENDERSON","telephone_number":"(828) 696-1000","measure_id":"PSI_90","measure_name":"CMS Medicare PSI 90: Patient safety and adverse events composite","compared_to_national":"No Different Than the National Value","denominator":"Not Applicable","score":"0.83","lower_estimate":"0.45","higher_estimate":"1.2","footnote":"","start_date":"07/01/2023","end_date":"06/30/2025"}
```

## Changes: pull 1 vs pull 2 (matched by facility_id)

| | count |
|---|---|
| pull 1 CSV rows | 265 |
| pull 2 CSV rows | 265 |
| new (only in pull 2) | 0 |
| gone (only in pull 1) | 0 |
| changed (same facility_id, different value in a named column) | 0 |

Check: pull 2 rows = pull 1 rows + new - gone = 265 + 0 - 0 = 265. The two pulls returned identical data: same counts from the source, same 265 facility_ids, and no value changed in any of the 13 columns for any facility_id.

## PROOF — PULL 1

Pull window: 2026-11-13T01:00:56Z to 2026-11-13T01:01:23Z (UTC). Host for every request: data.cms.gov.

This PROOF documents the cms_pull.py pull recorded in the filed PULL 1 progress note (same window); requests below are in retrieval order.

### PULL 1 request 1

- URL: https://data.cms.gov/provider-data/api/1/datastore/query/xubh-q36u/0?conditions%5B0%5D%5Bproperty%5D=state&conditions%5B0%5D%5Bvalue%5D=NC&conditions%5B0%5D%5Boperator%5D=%3D&conditions%5B1%5D%5Bproperty%5D=hospital_type&conditions%5B1%5D%5Bvalue%5D=Acute+Care+Hospitals&conditions%5B1%5D%5Boperator%5D=%3D&limit=1500&offset=0
- Retrieved (UTC): 2026-11-13T01:00:56Z
- Response Date header: Fri, 13 Nov 2026 01:01:00 GMT
- count field: 80; rows in page: 80
- Response body SHA-256: b1d8f2660817602f53cc071a60fc7c959cc32e000a8502e593a532f1c33e0b3c
- Raw excerpt (first 320 characters of the body, exactly as returned):
```
{"results":[{"facility_id":"340001","facility_name":"CAROLINAS MEDICAL CENTER-NORTHEAST","address":"920 CHURCH ST N","citytown":"CONCORD","state":"NC","zip_code":"28025","countyparish":"CABARRUS","telephone_number":"(704) 783-3000","hospital_type":"Acute Care Hospitals","hospital_ownership":"Government - Hospital Distr
```

- Count excerpt (characters 103716 to 103929 of the body, counting from 0, exactly as returned):
```
15","pt_exp_group_footnote":"","te_group_measure_count":"10","count_of_facility_te_measures":"7","te_group_footnote":""}],"count":80,"schema":{"af9369a8-f9c7-53d6-8d77-dbd4bdfef5ab":{"fields":{"facility_id":{"type
```


### PULL 1 request 2

- URL: https://data.cms.gov/provider-data/api/1/datastore/query/xubh-q36u/0?conditions%5B0%5D%5Bproperty%5D=state&conditions%5B0%5D%5Bvalue%5D=SC&conditions%5B0%5D%5Boperator%5D=%3D&conditions%5B1%5D%5Bproperty%5D=hospital_type&conditions%5B1%5D%5Bvalue%5D=Acute+Care+Hospitals&conditions%5B1%5D%5Boperator%5D=%3D&limit=1500&offset=0
- Retrieved (UTC): 2026-11-13T01:00:59Z
- Response Date header: Fri, 13 Nov 2026 01:01:03 GMT
- count field: 51; rows in page: 51
- Response body SHA-256: 984991fc1e8ac981c8a6e47f65a72bcf1712b34456937c20e65e224c4c27739c
- Raw excerpt (first 320 characters of the body, exactly as returned):
```
{"results":[{"facility_id":"420002","facility_name":"ROCK HILL HOSPITAL-PIEDMONT MEDICAL CENTER","address":"222 S HERLONG AVE","citytown":"ROCK HILL","state":"SC","zip_code":"29730","countyparish":"YORK","telephone_number":"(803) 329-1234","hospital_type":"Acute Care Hospitals","hospital_ownership":"Proprietary","emerg
```

- Count excerpt (characters 66054 to 66267 of the body, counting from 0, exactly as returned):
```
15","pt_exp_group_footnote":"","te_group_measure_count":"10","count_of_facility_te_measures":"9","te_group_footnote":""}],"count":51,"schema":{"af9369a8-f9c7-53d6-8d77-dbd4bdfef5ab":{"fields":{"facility_id":{"type
```


### PULL 1 request 3

- URL: https://data.cms.gov/provider-data/api/1/datastore/query/xubh-q36u/0?conditions%5B0%5D%5Bproperty%5D=state&conditions%5B0%5D%5Bvalue%5D=TN&conditions%5B0%5D%5Boperator%5D=%3D&conditions%5B1%5D%5Bproperty%5D=hospital_type&conditions%5B1%5D%5Bvalue%5D=Acute+Care+Hospitals&conditions%5B1%5D%5Boperator%5D=%3D&limit=1500&offset=0
- Retrieved (UTC): 2026-11-13T01:01:03Z
- Response Date header: Fri, 13 Nov 2026 01:01:06 GMT
- count field: 78; rows in page: 78
- Response body SHA-256: 119334e701c52aed63143511f4200bb90552cd426872e3a389084e16faf2fc6a
- Raw excerpt (first 320 characters of the body, exactly as returned):
```
{"results":[{"facility_id":"440002","facility_name":"JACKSON-MADISON COUNTY GENERAL HOSPITAL","address":"620 SKYLINE DRIVE","citytown":"JACKSON","state":"TN","zip_code":"38301","countyparish":"MADISON","telephone_number":"(731) 541-5000","hospital_type":"Acute Care Hospitals","hospital_ownership":"Government - Hospital
```

- Count excerpt (characters 101681 to 101894 of the body, counting from 0, exactly as returned):
```
e","pt_exp_group_footnote":"5","te_group_measure_count":"10","count_of_facility_te_measures":"4","te_group_footnote":""}],"count":78,"schema":{"af9369a8-f9c7-53d6-8d77-dbd4bdfef5ab":{"fields":{"facility_id":{"type
```


### PULL 1 request 4

- URL: https://data.cms.gov/provider-data/api/1/datastore/query/ynj2-r877/0?conditions%5B0%5D%5Bproperty%5D=state&conditions%5B0%5D%5Bvalue%5D=NC&conditions%5B0%5D%5Boperator%5D=%3D&limit=1500&offset=0
- Retrieved (UTC): 2026-11-13T01:01:06Z
- Response Date header: Fri, 13 Nov 2026 01:01:09 GMT
- count field: 2120; rows in page: 1500
- Response body SHA-256: 39e61b82b059bcc82cde779a2329fa6df527f34ac698ec927f64b138c9cb69db
- Raw excerpt (first 320 characters of the body, exactly as returned):
```
{"results":[{"facility_id":"340001","facility_name":"CAROLINAS MEDICAL CENTER-NORTHEAST","address":"920 CHURCH ST N","citytown":"CONCORD","state":"NC","zip_code":"28025","countyparish":"CABARRUS","telephone_number":"(704) 783-3000","measure_id":"COMP_HIP_KNEE","measure_name":"Rate of complications for hip\/knee replace
```

- Count excerpt (characters 776144 to 776359 of the body, counting from 0, exactly as returned):
```
98","lower_estimate":"0.45","higher_estimate":"1.5","footnote":"","start_date":"07\/01\/2023","end_date":"06\/30\/2025"}],"count":2120,"schema":{"5dcebce4-6940-5efa-a05f-0871bfb6445f":{"fields":{"facility_id":{"type
```


### PULL 1 request 5

- URL: https://data.cms.gov/provider-data/api/1/datastore/query/ynj2-r877/0?conditions%5B0%5D%5Bproperty%5D=state&conditions%5B0%5D%5Bvalue%5D=NC&conditions%5B0%5D%5Boperator%5D=%3D&limit=1500&offset=1500
- Retrieved (UTC): 2026-11-13T01:01:09Z
- Response Date header: Fri, 13 Nov 2026 01:01:13 GMT
- count field: 2120; rows in page: 620
- Response body SHA-256: 14006f35adbfc36b547e116b9703dd17bb944d1373686108bff5fbf7cbf9cc81
- Raw excerpt (first 320 characters of the body, exactly as returned):
```
{"results":[{"facility_id":"340166","facility_name":"ATRIUM HEALTH UNIVERSITY CITY","address":"8800 NORTH TYRON STREET","citytown":"CHARLOTTE","state":"NC","zip_code":"28262","countyparish":"MECKLENBURG","telephone_number":"(704) 548-6000","measure_id":"COMP_HIP_KNEE","measure_name":"Rate of complications for hip\/knee
```

- Count excerpt (characters 328733 to 328948 of the body, counting from 0, exactly as returned):
```
"Not Available","higher_estimate":"Not Available","footnote":"13","start_date":"07\/01\/2023","end_date":"06\/30\/2025"}],"count":2120,"schema":{"5dcebce4-6940-5efa-a05f-0871bfb6445f":{"fields":{"facility_id":{"type
```


### PULL 1 request 6

- URL: https://data.cms.gov/provider-data/api/1/datastore/query/ynj2-r877/0?conditions%5B0%5D%5Bproperty%5D=state&conditions%5B0%5D%5Bvalue%5D=SC&conditions%5B0%5D%5Boperator%5D=%3D&limit=1500&offset=0
- Retrieved (UTC): 2026-11-13T01:01:13Z
- Response Date header: Fri, 13 Nov 2026 01:01:17 GMT
- count field: 1160; rows in page: 1160
- Response body SHA-256: e6366c9b9073669476dac7a57a7bf613ad426286cf171593bbc59570d11d89d3
- Raw excerpt (first 320 characters of the body, exactly as returned):
```
{"results":[{"facility_id":"420002","facility_name":"ROCK HILL HOSPITAL-PIEDMONT MEDICAL CENTER","address":"222 S HERLONG AVE","citytown":"ROCK HILL","state":"SC","zip_code":"29730","countyparish":"YORK","telephone_number":"(803) 329-1234","measure_id":"COMP_HIP_KNEE","measure_name":"Rate of complications for hip\/knee
```

- Count excerpt (characters 607293 to 607508 of the body, counting from 0, exactly as returned):
```
"Not Available","higher_estimate":"Not Available","footnote":"19","start_date":"07\/01\/2023","end_date":"06\/30\/2025"}],"count":1160,"schema":{"5dcebce4-6940-5efa-a05f-0871bfb6445f":{"fields":{"facility_id":{"type
```


### PULL 1 request 7

- URL: https://data.cms.gov/provider-data/api/1/datastore/query/ynj2-r877/0?conditions%5B0%5D%5Bproperty%5D=state&conditions%5B0%5D%5Bvalue%5D=TN&conditions%5B0%5D%5Boperator%5D=%3D&limit=1500&offset=0
- Retrieved (UTC): 2026-11-13T01:01:17Z
- Response Date header: Fri, 13 Nov 2026 01:01:20 GMT
- count field: 2020; rows in page: 1500
- Response body SHA-256: eac5cd011804e0fda0cff128363703da57355585b18a174b5b361ce10e29babe
- Raw excerpt (first 320 characters of the body, exactly as returned):
```
{"results":[{"facility_id":"440002","facility_name":"JACKSON-MADISON COUNTY GENERAL HOSPITAL","address":"620 SKYLINE DRIVE","citytown":"JACKSON","state":"TN","zip_code":"38301","countyparish":"MADISON","telephone_number":"(731) 541-5000","measure_id":"COMP_HIP_KNEE","measure_name":"Rate of complications for hip\/knee r
```

- Count excerpt (characters 787753 to 787968 of the body, counting from 0, exactly as returned):
```
9","lower_estimate":"0.67","higher_estimate":"1.52","footnote":"","start_date":"07\/01\/2023","end_date":"06\/30\/2025"}],"count":2020,"schema":{"5dcebce4-6940-5efa-a05f-0871bfb6445f":{"fields":{"facility_id":{"type
```


### PULL 1 request 8

- URL: https://data.cms.gov/provider-data/api/1/datastore/query/ynj2-r877/0?conditions%5B0%5D%5Bproperty%5D=state&conditions%5B0%5D%5Bvalue%5D=TN&conditions%5B0%5D%5Boperator%5D=%3D&limit=1500&offset=1500
- Retrieved (UTC): 2026-11-13T01:01:20Z
- Response Date header: Fri, 13 Nov 2026 01:01:23 GMT
- count field: 2020; rows in page: 520
- Response body SHA-256: d0621a45ec0863e5f5b207930000ff83e29c3f73f1fc6b7f96ed9ba8412f7c8e
- Raw excerpt (first 320 characters of the body, exactly as returned):
```
{"results":[{"facility_id":"440197","facility_name":"TRISTAR SOUTHERN HILLS MEDICAL CENTER","address":"391 WALLACE RD","citytown":"NASHVILLE","state":"TN","zip_code":"37211","countyparish":"DAVIDSON","telephone_number":"(615) 781-4000","measure_id":"COMP_HIP_KNEE","measure_name":"Rate of complications for hip\/knee rep
```

- Count excerpt (characters 277385 to 277600 of the body, counting from 0, exactly as returned):
```
"Not Available","higher_estimate":"Not Available","footnote":"19","start_date":"07\/01\/2023","end_date":"06\/30\/2025"}],"count":2020,"schema":{"5dcebce4-6940-5efa-a05f-0871bfb6445f":{"fields":{"facility_id":{"type
```


### PULL 1 response headers (one request, general information NC, including Date)

```
HTTP/1.1 200 Connection Established

HTTP/1.1 200 OK
Content-Language: en
Content-Security-Policy: frame-ancestors https://*.cms.gov; upgrade-insecure-requests;
Content-Type: application/json
ETag: "1794531658-gzip"
Last-Modified: Fri, 13 Nov 2026 01:00:58 GMT
X-Age: 0
X-AH-Environment: prod
X-Content-Type-Options: nosniff
X-Drupal-Cache: MISS
X-Frame-Options: SAMEORIGIN
X-Generator: Drupal 11 (https://www.drupal.org)
X-Request-ID: v-afcb9862-defd-11f1-a21c-232be2058dd2
Vary: cookie
Vary: origin
Expires: Fri, 13 Nov 2026 01:01:00 GMT
Cache-Control: max-age=0, no-cache, no-store
Pragma: no-cache
Date: Fri, 13 Nov 2026 01:01:00 GMT
Akamai-GRN: 0.49c90b17.1794531658.4e44b7d
X-XSS-Protection: 1; mode=block
Strict-Transport-Security: max-age=31536000 ; includeSubDomains ; preload
Transfer-Encoding: chunked
```

## PROOF — PULL 2

Pull window: 2026-11-14T01:44:37Z to 2026-11-14T01:45:01Z (UTC). Host for every request: data.cms.gov.

### PULL 2 request: general information, NC

- URL: https://data.cms.gov/provider-data/api/1/datastore/query/xubh-q36u/0?conditions%5B0%5D%5Bproperty%5D=state&conditions%5B0%5D%5Bvalue%5D=NC&conditions%5B0%5D%5Boperator%5D=%3D&conditions%5B1%5D%5Bproperty%5D=hospital_type&conditions%5B1%5D%5Bvalue%5D=Acute+Care+Hospitals&conditions%5B1%5D%5Boperator%5D=%3D&limit=1500&offset=0
- Retrieved (UTC): 2026-11-14T01:44:37Z
- Response Date header: Sat, 14 Nov 2026 01:44:41 GMT
- count field: 80; rows returned: 80
- Response body SHA-256: c960d65507efc03c735629eea5043d5bbdefc57b114a9f616d15a13068f6fcd0
- Raw excerpt (first 320 characters of the body, exactly as returned):
```
{"results":[{"facility_id":"340001","facility_name":"CAROLINAS MEDICAL CENTER-NORTHEAST","address":"920 CHURCH ST N","citytown":"CONCORD","state":"NC","zip_code":"28025","countyparish":"CABARRUS","telephone_number":"(704) 783-3000","hospital_type":"Acute Care Hospitals","hospital_ownership":"Government - Hospital Distr
```

- Count excerpt (characters 103716 to 103929 of the body, counting from 0, exactly as returned):
```
15","pt_exp_group_footnote":"","te_group_measure_count":"10","count_of_facility_te_measures":"7","te_group_footnote":""}],"count":80,"schema":{"af9369a8-f9c7-53d6-8d77-dbd4bdfef5ab":{"fields":{"facility_id":{"type
```


### PULL 2 request: general information, SC

- URL: https://data.cms.gov/provider-data/api/1/datastore/query/xubh-q36u/0?conditions%5B0%5D%5Bproperty%5D=state&conditions%5B0%5D%5Bvalue%5D=SC&conditions%5B0%5D%5Boperator%5D=%3D&conditions%5B1%5D%5Bproperty%5D=hospital_type&conditions%5B1%5D%5Bvalue%5D=Acute+Care+Hospitals&conditions%5B1%5D%5Boperator%5D=%3D&limit=1500&offset=0
- Retrieved (UTC): 2026-11-14T01:44:41Z
- Response Date header: Sat, 14 Nov 2026 01:44:44 GMT
- count field: 51; rows returned: 51
- Response body SHA-256: 99aa0c1b21c7128836cabf5f1e267d28629d3962d68133c03b4d8c2aca812aa5
- Raw excerpt (first 320 characters of the body, exactly as returned):
```
{"results":[{"facility_id":"420002","facility_name":"ROCK HILL HOSPITAL-PIEDMONT MEDICAL CENTER","address":"222 S HERLONG AVE","citytown":"ROCK HILL","state":"SC","zip_code":"29730","countyparish":"YORK","telephone_number":"(803) 329-1234","hospital_type":"Acute Care Hospitals","hospital_ownership":"Proprietary","emerg
```

- Count excerpt (characters 66054 to 66267 of the body, counting from 0, exactly as returned):
```
15","pt_exp_group_footnote":"","te_group_measure_count":"10","count_of_facility_te_measures":"9","te_group_footnote":""}],"count":51,"schema":{"af9369a8-f9c7-53d6-8d77-dbd4bdfef5ab":{"fields":{"facility_id":{"type
```


### PULL 2 request: general information, TN

- URL: https://data.cms.gov/provider-data/api/1/datastore/query/xubh-q36u/0?conditions%5B0%5D%5Bproperty%5D=state&conditions%5B0%5D%5Bvalue%5D=TN&conditions%5B0%5D%5Boperator%5D=%3D&conditions%5B1%5D%5Bproperty%5D=hospital_type&conditions%5B1%5D%5Bvalue%5D=Acute+Care+Hospitals&conditions%5B1%5D%5Boperator%5D=%3D&limit=1500&offset=0
- Retrieved (UTC): 2026-11-14T01:44:43Z
- Response Date header: Sat, 14 Nov 2026 01:44:46 GMT
- count field: 78; rows returned: 78
- Response body SHA-256: 708ad21dfc93714daa37b489cb1b360eb7a70dc1ad0ef87282f1d5943b15a751
- Raw excerpt (first 320 characters of the body, exactly as returned):
```
{"results":[{"facility_id":"440002","facility_name":"JACKSON-MADISON COUNTY GENERAL HOSPITAL","address":"620 SKYLINE DRIVE","citytown":"JACKSON","state":"TN","zip_code":"38301","countyparish":"MADISON","telephone_number":"(731) 541-5000","hospital_type":"Acute Care Hospitals","hospital_ownership":"Government - Hospital
```

- Count excerpt (characters 101681 to 101894 of the body, counting from 0, exactly as returned):
```
e","pt_exp_group_footnote":"5","te_group_measure_count":"10","count_of_facility_te_measures":"4","te_group_footnote":""}],"count":78,"schema":{"af9369a8-f9c7-53d6-8d77-dbd4bdfef5ab":{"fields":{"facility_id":{"type
```


### PULL 2 request: complications, NC

- URL: https://data.cms.gov/provider-data/api/1/datastore/query/ynj2-r877/0?conditions%5B0%5D%5Bproperty%5D=state&conditions%5B0%5D%5Bvalue%5D=NC&conditions%5B0%5D%5Boperator%5D=%3D&limit=1500&offset=0
- Retrieved (UTC): 2026-11-14T01:44:46Z
- Response Date header: Sat, 14 Nov 2026 01:44:49 GMT
- count field: 2120; rows returned: 1500
- Response body SHA-256: 55050c71bd86c0ac8d167b599a89896463f78fcfb69b710deb97c01fddeeed42
- Raw excerpt (first 320 characters of the body, exactly as returned):
```
{"results":[{"facility_id":"340001","facility_name":"CAROLINAS MEDICAL CENTER-NORTHEAST","address":"920 CHURCH ST N","citytown":"CONCORD","state":"NC","zip_code":"28025","countyparish":"CABARRUS","telephone_number":"(704) 783-3000","measure_id":"COMP_HIP_KNEE","measure_name":"Rate of complications for hip\/knee replace
```

- Count excerpt (characters 776144 to 776359 of the body, counting from 0, exactly as returned):
```
98","lower_estimate":"0.45","higher_estimate":"1.5","footnote":"","start_date":"07\/01\/2023","end_date":"06\/30\/2025"}],"count":2120,"schema":{"5dcebce4-6940-5efa-a05f-0871bfb6445f":{"fields":{"facility_id":{"type
```


### PULL 2 request: complications, NC, offset 1500

- URL: https://data.cms.gov/provider-data/api/1/datastore/query/ynj2-r877/0?conditions%5B0%5D%5Bproperty%5D=state&conditions%5B0%5D%5Bvalue%5D=NC&conditions%5B0%5D%5Boperator%5D=%3D&limit=1500&offset=1500
- Retrieved (UTC): 2026-11-14T01:44:49Z
- Response Date header: Sat, 14 Nov 2026 01:44:52 GMT
- count field: 2120; rows returned: 620
- Response body SHA-256: 5a9af9732e885017401221911c35dc8f32b2962b2bdb7535a7efe70f306f332c
- Raw excerpt (first 320 characters of the body, exactly as returned):
```
{"results":[{"facility_id":"340166","facility_name":"ATRIUM HEALTH UNIVERSITY CITY","address":"8800 NORTH TYRON STREET","citytown":"CHARLOTTE","state":"NC","zip_code":"28262","countyparish":"MECKLENBURG","telephone_number":"(704) 548-6000","measure_id":"COMP_HIP_KNEE","measure_name":"Rate of complications for hip\/knee
```

- Count excerpt (characters 328733 to 328948 of the body, counting from 0, exactly as returned):
```
"Not Available","higher_estimate":"Not Available","footnote":"13","start_date":"07\/01\/2023","end_date":"06\/30\/2025"}],"count":2120,"schema":{"5dcebce4-6940-5efa-a05f-0871bfb6445f":{"fields":{"facility_id":{"type
```


### PULL 2 request: complications, SC

- URL: https://data.cms.gov/provider-data/api/1/datastore/query/ynj2-r877/0?conditions%5B0%5D%5Bproperty%5D=state&conditions%5B0%5D%5Bvalue%5D=SC&conditions%5B0%5D%5Boperator%5D=%3D&limit=1500&offset=0
- Retrieved (UTC): 2026-11-14T01:44:52Z
- Response Date header: Sat, 14 Nov 2026 01:44:55 GMT
- count field: 1160; rows returned: 1160
- Response body SHA-256: 46ad92715c4614c3728e4cb1398f6dd12b1f017bf02b93920c5d77f23f3da0be
- Raw excerpt (first 320 characters of the body, exactly as returned):
```
{"results":[{"facility_id":"420002","facility_name":"ROCK HILL HOSPITAL-PIEDMONT MEDICAL CENTER","address":"222 S HERLONG AVE","citytown":"ROCK HILL","state":"SC","zip_code":"29730","countyparish":"YORK","telephone_number":"(803) 329-1234","measure_id":"COMP_HIP_KNEE","measure_name":"Rate of complications for hip\/knee
```

- Count excerpt (characters 607293 to 607508 of the body, counting from 0, exactly as returned):
```
"Not Available","higher_estimate":"Not Available","footnote":"19","start_date":"07\/01\/2023","end_date":"06\/30\/2025"}],"count":1160,"schema":{"5dcebce4-6940-5efa-a05f-0871bfb6445f":{"fields":{"facility_id":{"type
```


### PULL 2 request: complications, TN

- URL: https://data.cms.gov/provider-data/api/1/datastore/query/ynj2-r877/0?conditions%5B0%5D%5Bproperty%5D=state&conditions%5B0%5D%5Bvalue%5D=TN&conditions%5B0%5D%5Boperator%5D=%3D&limit=1500&offset=0
- Retrieved (UTC): 2026-11-14T01:44:55Z
- Response Date header: Sat, 14 Nov 2026 01:44:58 GMT
- count field: 2020; rows returned: 1500
- Response body SHA-256: 4b01ce4b94b33f8567e245a234d53989cedd554085f9afb6971edc90540b8837
- Raw excerpt (first 320 characters of the body, exactly as returned):
```
{"results":[{"facility_id":"440002","facility_name":"JACKSON-MADISON COUNTY GENERAL HOSPITAL","address":"620 SKYLINE DRIVE","citytown":"JACKSON","state":"TN","zip_code":"38301","countyparish":"MADISON","telephone_number":"(731) 541-5000","measure_id":"COMP_HIP_KNEE","measure_name":"Rate of complications for hip\/knee r
```

- Count excerpt (characters 787753 to 787968 of the body, counting from 0, exactly as returned):
```
9","lower_estimate":"0.67","higher_estimate":"1.52","footnote":"","start_date":"07\/01\/2023","end_date":"06\/30\/2025"}],"count":2020,"schema":{"5dcebce4-6940-5efa-a05f-0871bfb6445f":{"fields":{"facility_id":{"type
```


### PULL 2 request: complications, TN, offset 1500

- URL: https://data.cms.gov/provider-data/api/1/datastore/query/ynj2-r877/0?conditions%5B0%5D%5Bproperty%5D=state&conditions%5B0%5D%5Bvalue%5D=TN&conditions%5B0%5D%5Boperator%5D=%3D&limit=1500&offset=1500
- Retrieved (UTC): 2026-11-14T01:44:58Z
- Response Date header: Sat, 14 Nov 2026 01:45:02 GMT
- count field: 2020; rows returned: 520
- Response body SHA-256: c7c9f1538a673302e4ff9f7ca4a1d5b2374a4c800f624db415511d4cdc5a96a7
- Raw excerpt (first 320 characters of the body, exactly as returned):
```
{"results":[{"facility_id":"440197","facility_name":"TRISTAR SOUTHERN HILLS MEDICAL CENTER","address":"391 WALLACE RD","citytown":"NASHVILLE","state":"TN","zip_code":"37211","countyparish":"DAVIDSON","telephone_number":"(615) 781-4000","measure_id":"COMP_HIP_KNEE","measure_name":"Rate of complications for hip\/knee rep
```

- Count excerpt (characters 277385 to 277600 of the body, counting from 0, exactly as returned):
```
"Not Available","higher_estimate":"Not Available","footnote":"19","start_date":"07\/01\/2023","end_date":"06\/30\/2025"}],"count":2020,"schema":{"5dcebce4-6940-5efa-a05f-0871bfb6445f":{"fields":{"facility_id":{"type
```


### PULL 2 response headers (one request, general information NC, including Date)

```
HTTP/1.1 200 Connection Established

HTTP/1.1 200 OK
Content-Language: en
Content-Security-Policy: frame-ancestors https://*.cms.gov; upgrade-insecure-requests;
Content-Type: application/json
ETag: "1794620679-gzip"
Last-Modified: Sat, 14 Nov 2026 01:44:39 GMT
X-Age: 0
X-AH-Environment: prod
X-Content-Type-Options: nosniff
X-Drupal-Cache: MISS
X-Frame-Options: SAMEORIGIN
X-Generator: Drupal 11 (https://www.drupal.org)
X-Request-ID: v-f4d2ea62-dfcc-11f1-a045-3330167b9d5b
Vary: cookie
Vary: origin
Expires: Sat, 14 Nov 2026 01:44:41 GMT
Cache-Control: max-age=0, no-cache, no-store
Pragma: no-cache
Date: Sat, 14 Nov 2026 01:44:41 GMT
Akamai-GRN: 0.0f933617.1794620679.2f40ebd
X-XSS-Protection: 1; mode=block
Strict-Transport-Security: max-age=31536000 ; includeSubDomains ; preload
Transfer-Encoding: chunked
```

## DATA FILES

```synmerco-data
c34fb6dcb9a2a93b5c05273b8c958e88b6a9ed17bed51cab134e279fb57a3aaa hospital-recon-pull1.csv
9ae6a6cf7a267ce31a16c81472b5da7577a470547f3efb436855465d4d04a8a5 hospital-recon-pull2.csv
```

hospital-recon-pull1.csv: 265 rows, 18,239 bytes. hospital-recon-pull2.csv: 265 rows, 17,973 bytes. Same 13 columns in this order in both files: facility_id, facility_name, state, in_general_information, in_complications, hospital_overall_rating, hospital_overall_rating_footnote, count_of_mort_measures_worse, count_of_safety_measures_worse, count_of_readm_measures_worse, complication_rows, worse_measures, rank. One row per facility_id, no duplicate keys. The rating, footnote and three count_of_ columns are copied as published from general information. A value the source leaves empty stays an empty cell; rank is empty for rows that are not matched or have no numeric rating.

## PLATFORM RECORD

Progress notes filed on the escrow (GET /v1/escrows/esc_d6e50da927ba44118a71a65d/progress):

PULL 1 note, recordedAt 2026-11-13 01:02:58.371897+00:

> PULL 1: hospital-recon-pull1.csv, 265 rows, SHA-256 c34fb6dcb9a2a93b5c05273b8c958e88b6a9ed17bed51cab134e279fb57a3aaa. General information (acute): NC 80, SC 51, TN 78. Complications: NC 2120, SC 1160, TN 2020. Pulled 2026-11-13 01:00:56-01:01:23 UTC from data.cms.gov (xubh-q36u, ynj2-r877). PULL 2 in 24h.

PULL 1 note (second, same file), recordedAt 2026-11-13 01:04:54.837208+00:

> PULL 1: hospital-recon-pull1.csv, 265 rows, SHA-256 c34fb6dcb9a2a93b5c05273b8c958e88b6a9ed17bed51cab134e279fb57a3aaa. Acute hospitals from CMS general information: NC 80, SC 51, TN 78 (209 total, source counts match). Complications rows: NC 2120, SC 1160, TN 2020 (5300 total). Matched 209, ranked 188, complications-only facility_ids 56. Source Date header 2026-11-13 01:00 UTC approx (see pull1-proof.json). PULL 2 re-check due 24h after this note.

PULL 2 note, recordedAt 2026-11-14 01:45:35.969356+00 (24 hours 40 minutes after the later PULL 1 note):

> PULL 2: hospital-recon-pull2.csv, 265 rows, SHA-256 9ae6a6cf7a267ce31a16c81472b5da7577a470547f3efb436855465d4d04a8a5. General information (acute): NC 80, SC 51, TN 78. Complications: NC 2120, SC 1160, TN 2020. Pulled 2026-11-14 01:44:37-01:45:01 UTC from data.cms.gov (xubh-q36u, ynj2-r877). No changes vs PULL 1 (0 new, 0 gone, 0 changed).

## ACCEPTANCE

1. Each CSV has exactly the named columns in order, one row per facility_id with no duplicate keys, and the row counts in the report equal the files. — YES. Both files have exactly the 13 named columns in the stated order; pull 1 has 265 rows and pull 2 has 265 rows, each with 265 unique facility_ids (0 duplicates); the row counts in this report (265 and 265) equal the files.

2. The report gives the acute hospital count and complications row count per state as the source returned them, each matching its PROOF excerpt. — YES. Acute: NC 80, SC 51, TN 78 in both pulls; complications: NC 2120, SC 1160, TN 2020 in both pulls; every count is shown in its request's PROOF count excerpt, an exact slice of the response body containing the count field (for example PULL 1 request 1 shows "count":80, PULL 2 complications NC offset 0 shows "count":2120).

3. The one-dataset-only list is present (or states none) and every entry shows state, name and how found. — YES. Acute-only: none (stated above, 0 in both pulls). Complications-only: all 56 entries listed with state, facility_name and how found (ynj2-r877 complications pull only; facility_id not in the xubh-q36u acute pull).

4. Ranked rows follow the stated rule, rank is empty for unmatched or unrated rows, and the top 20 table and its measure table are present. — YES. Ranking verified: rating descending, then fewer worse_measures, then facility_id ascending as text; 188 matched hospitals ranked in each pull; rank is empty for the 77 unranked rows (56 complications-only plus 21 matched without a numeric rating); the top 20 table and the 400-row measure table for those 20 are present above.

5. Each pull's PROOF shows a source-written time (Date header), and the changes table is present as described. — YES. PULL 1 PROOF lists a Date header for all 8 requests (e.g. Fri, 13 Nov 2026 01:01:00 GMT) and the full response headers for one request; PULL 2 PROOF lists a Date header for all 8 requests (e.g. Sat, 14 Nov 2026 01:44:41 GMT) and the full response headers for one request; the changes table is present above (0 new, 0 gone, 0 changed; 265 = 265 + 0 - 0).

6. The PLATFORM RECORD shows a PULL 1: note and a PULL 2: note at least 24 hours later, each with its CSV's row count and SHA-256 as under DATA FILES; pull 2's source time is later than pull 1's; the change counts agree with both CSV files (or pull 2 failed as the TASK allows). — YES. PULL 1 note recordedAt 2026-11-13 01:02:58Z (second PULL 1 note 01:04:54Z), PULL 2 note recordedAt 2026-11-14 01:45:35Z — more than 24 hours later; each note gives its CSV's row count (265) and SHA-256 matching the DATA FILES block; pull 2's source Date headers (14 Nov 2026 01:44-01:45 UTC) are later than pull 1's (13 Nov 2026 01:00-01:01 UTC); change counts (0 new, 0 gone, 0 changed) agree with both CSV files (265 = 265 + 0 - 0). Pull 2 did not fail.
