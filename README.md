# OSINT-Tools-Hungary
<img src="https://flagcdn.com/w320/hu.png" alt="Hungary_FLAG"/>
A list of OSINT resources and tools that may be useful to you when conducting investigations related to Hungary. Most of the resources and tools has versions in Hungarian and English. Many Hungarian government portals are Hungarian-only JavaScript applications, and some (e.g. the annual reports portal) block access through anonymous proxy networks. The beneficial ownership register (Tényleges Tulajdonosi Nyilvántartás, kept by the tax authority NAV) has no open online search: since the CJEU ruling of 22 November 2022 (C-37/20, C-601/20), secondary sources disagree on whether the general public can still get fee-based extracts or whether access is limited to authorities and obliged entities, so check the current rules with NAV. Land registry extracts (tulajdoni lap) are fee-based and are not listed here.

**Last Updated:** 2026-10-12

## Contributions
Feel free to join this project — [OSINT For Countries V2.0](https://github.com/Provereno-Media/OSINT-for-countries-V2.0)

## Table of contents:
 - [Open Data portals](#open-data-portals)
 - [Legal Entities](#legal-entities)
 - [Cadastral and other Maps](#maps)
 - [Vehicles](#vehicles)
 - [People, phones, social etc.](#people)
 - [Public procurements](#public-procurement)
 - [WHOIS](#whois)

## Open Data portals
(Country Open Data, Stock Exchange, Courts)
- [Nemzeti Közadatportál (National Public Data Portal)](https://kozadatportal.hu/) — national portal for open datasets and the public data inventory (Közadatkataszter), grouped by government function; providers include KSH and NAV; keyword search. *Lang: HU.* 
- [Közadatkereső (Public Data Search)](https://kozadattar.hu) — single search across public-interest data published by public bodies (metadata from 5,000+ institutions); advanced search. *Lang: HU.* 
- [KSH STADAT (Central Statistical Office summary tables)](https://www.ksh.hu/stadat) — official statistics tables; the KSH site also has a dissemination database, the 2022 census database, a regional atlas and public microdata files. *Lang: HU, EN.* 
- [Magyar Közlöny (Hungarian Official Gazette)](https://magyarkozlony.hu) — gazette issues from 1998 as PDF (digitally signed since May 2013); keyword search with wildcards and lookup by issue number. *Lang: HU.* 
- [Nemzeti Jogszabálytár (National Legislation Repository)](https://njt.jog.gov.hu/) — consolidated texts of Hungarian laws and decrees, with dated versions. *Lang: HU.* 
- [Anonimizált bírósági határozatok – ÜIR (Anonymised Court Decisions)](https://eakta.birosag.hu/anonimizalt-hatarozatok) — anonymised decisions of the Kúria and of the appeal, regional and district courts; full-text and legal-principle search; filters by court, year, legal area, case number and statute. *Lang: HU.* 
- [MNB Közzétételek (Central Bank Disclosure System)](https://kozzetetelek.mnb.hu) — mandatory disclosures of public and private securities issuers, supervised capital-market institutions and pension/health funds; short-selling data query. *Lang: HU, EN.* 
- [Budapesti Értéktőzsde (Budapest Stock Exchange)](https://bet.hu) — issuer list, archive of issuer news and extraordinary disclosures, exchange notices, 15-minute delayed market data. *Lang: HU, EN.*

## Legal Entities
- [e-Cégjegyzék – Ingyenes Céginformáció (Free Company Information)](https://www.e-cegjegyzek.hu/?ceginformacio) — Ministry of Justice service with free company register data from all Hungarian registration courts, including deleted companies and bankruptcy/liquidation status; search by name, registration number or tax number. Not a certified extract; certified extracts are paid. *Lang: HU.* 
- [Elektronikus Beszámoló Portál (Annual Financial Reports Portal)](https://e-beszamolo.im.gov.hu/oldal/beszamolo_kereses) — annual reports and balance sheets filed by companies; search by registration number, first 8 digits of the tax number, or name (min. 4 characters); captcha; anonymous proxies blocked. *Lang: HU.* 
- [Cégközlöny (Company Gazette)](https://cegportal.im.gov.hu/frontend/cegkozlony) — official gazette of company registration notices and Kft./Zrt. articles of association, published daily (JavaScript portal). *Lang: HU.* 
- [NAV Adóalanyok lekérdezése (Tax Authority taxpayer lookups)](https://nav.gov.hu/adatbazisok/adatbleker) — NAV public databases: VAT and group VAT registrants, other organisations, activity lookup, companies owning real estate; the same Adatbázisok menu lists suspended and sanction-deleted tax numbers. *Lang: HU, EN.* 
- [Civil Szervezetek Országos Névjegyzéke (National Register of Civil Organisations)](https://birosag.hu/en/kozzetetel-kereso) — associations, foundations and other NGOs; search by name (min. 6 characters, `%` as wildcard). *Lang: HU.* 
- [MNB Intézménykereső (Central Bank Institution Search)](https://intezmenykereso.mnb.hu/en/Home/Index) — licensed or registered financial institutions, insurance intermediaries (including individuals), crypto-asset and crowdfunding providers, MNB and foreign regulators' warnings; search by name, ID/registration number or ISIN. *Lang: EN, HU.* 
- [Törzskönyvi nyilvántartás (State Treasury Register of Budgetary Institutions)](https://www.allamkincstar.gov.hu/Koltsegvetes/Torzskonyvi_nyilvantartas/ktorzs) — lookup of budgetary institutions registered since 2004, including founding and termination documents. *Lang: HU.* 
- [Nemzeti Cégtár (National Company Directory)](https://www.nemzeticegtar.hu) — free basic data on ~600,000 Hungarian companies by name, tax number or registration number, plus interactive company statistics (Corvinus University and OPTEN). *Lang: HU.*

## Maps
(Cadastral Maps if available, GIS etc.)
- [Helyrajziszám-kereső (Lot Number Finder)](https://lechnerkozpont.hu/oldal/helyrajziszam-kereso) — Lechner Centre app built on the official land registry map (updated monthly): find a parcel's lot number (hrsz) by address or on the map; parcel boundaries, registered building outlines, orthophoto layer; free, no login. *Lang: HU.* 
- [e-építés – Nyilvántartások együttes lekérdezése (Joint Register Query by Lot Number)](https://www.e-epites.hu/altlek8x76y/) — queries construction-related registers by settlement and lot number; results are for information only. *Lang: HU.* 
- [Nemzeti Térinformatikai Alaptérkép – NTA (National GIS Base Map)](https://nta.lechnerkozpont.hu/) — 400+ layers (borders, buildings, transport, water network, land cover, relief, place names), served as WMTS; updated roughly yearly. *Lang: HU.*  ⚠️
- [Copernicus böngésző (Copernicus Browser)](https://copernicusbongeszo.hu/) — Lechner Centre web app for browsing Copernicus (EU Earth observation) data (JavaScript app). *Lang: HU.* 
- [MAPIRE (Historical Maps Online)](https://mapire.eu/en/) — georeferenced historical maps, including Habsburg military surveys (e.g. the First Military Survey, 1763–1785). *Lang: EN.*

## Vehicles
### Land
- [Közútijármű körözések (Wanted Road Vehicles – Police)](https://www.police.hu/hu/koral/kozutijarmu-korozesek) — public police notices for wanted (stolen) vehicles; search by plate, chassis number (VIN), vehicle type, make, colour, country of registration. *Lang: HU.* 
- [Forgalmi rendszám körözések (Wanted Licence Plates – Police)](https://www.police.hu/hu/koral/forgalmi-rendszam-korozesek) — wanted (stolen or lost) licence plates; search by plate number and issuing country. *Lang: HU.* 
- [Jármű Szolgáltatási Platform – JSZP (Vehicle Services Platform)](https://magyarorszag.hu/jszp_szuf) — government vehicle-services platform on the magyarorszag.hu e-government portal; which vehicle data is free and whether login is needed were not verified. *Lang: HU.* 

### Maritime
- [Vízijármű körözések (Wanted Watercraft – Police)](https://www.police.hu/hu/koral/vizijarmu-korozesek) — wanted boats, yachts, jet skis etc.; search by external ID, registration number, hull ID, serial number, vessel type, country. *Lang: HU.* 
- [Kishajóvezetői okmánylekérdezés (Boat Operator Certificate Check)](https://kozlekedesihatosag.kormany.hu/hu/web/hajozasi-hatosagi-foosztaly/kishajovezetoi-okmanylekerdezes) — Transport Authority check of International Certificates for Operators of Pleasure Craft by the 8-character certificate number; captcha. *Lang: HU.* 
- [VesselFinder](https://www.vesselfinder.com) — AIS vessel tracking map; coverage of Danube inland traffic not verified. *Lang: EN.* 💲 Freemium: live map, route planner and fleet explorer free; real-time and historical AIS data paid

### Aviation
- [Légijármű körözések (Wanted Aircraft – Police)](https://www.police.hu/hu/koral/legijarmu-korozesek) — wanted aircraft; search by aircraft type, ICAO identifier, make, serial number, country of registration. *Lang: HU.* 
- [HungaroControl AIS (Aeronautical Information Service)](https://ais.hungarocontrol.hu/) — AIP Hungary with amendments and supplements, VFR Manual (aerodrome data), daily airspace usage plan, free Netbriefing. *Lang: HU, EN.* 
- [Flightradar24](https://www.flightradar24.com) — live flight tracking map. *Lang: EN.* 💲 Freemium: live map free with a free account; email alerts and other premium features need a subscription (7-day trial)

## People
(Names, Addresses, Yellow Pages, White Pages etc.)
- [Közérdekből nyilvános körözések (Police Public Wanted & Missing Notices)](https://www.police.hu/hu/koral) — persons wanted on arrest warrants (search by name, place of birth, offence), missing persons, unidentified bodies; also wanted objects. *Lang: HU.* 
- [Választások – Nemzeti Választási Iroda (National Election Office Elections Portal)](https://vtr.valasztas.hu) — official elections portal (JavaScript app); candidate and results search not verified in this check. *Lang: HU.* 
- [NAV Egyéni vállalkozók nyilvántartása (Register of Sole Traders)](https://nav.gov.hu/adatbazisok/adatbleker/egyeni-vallalkozok-nyilvantartasa) — NAV public register of sole traders (egyéni vállalkozók); search fields not verified. *Lang: HU.* 
- [MBVK Végrehajtó kereső (Register of Court Bailiffs)](https://mbvk.hu/nevjegyzek/) — Hungarian Chamber of Judicial Officers register: find bailiffs by name, badge number, court district, postcode or settlement; office address list as Excel. *Lang: HU.*
- [MÉK Országos névjegyzék (National Register of Architects)](https://eugyintezes.mekon.hu/index.php?u=nevjegyzek) — Chamber of Architects register (~11,000 records): search by name, address, membership number, regional chamber, status; shows authorisations with expiry dates and contact address. *Lang: HU.*
- Try [OSINT Industries](https://app.osint.industries) and don't forget about the [Digital Profiler's Toolkit](https://github.com/paulpogoda/Digital-Profiler-s-Toolkit)

## Public procurement
- [Elektronikus Közbeszerzési Rendszer – EKR (Electronic Public Procurement System)](https://ekr.gov.hu) — official national e-procurement system (JavaScript portal); public access to procedures without login not verified. *Lang: HU.* 
- [Központi Információs Közadat-nyilvántartás – KIF (Central Register of Public Fund Transactions)](https://kif.gov.hu) — register of grants, contracts, asset uses and other payments from Hungarian or EU public funds above HUF 5 million (JavaScript app). *Lang: HU.* 
- [Közpénzügyi Portál (Public Finance Portal – State Treasury)](https://www.allamkincstar.gov.hu/Koltsegvetes/kozpenzugyi-portal) — Treasury reports and data on public finances; the Költségvetés section links central budget execution, municipal time series and government accounting (KGR-K11) data. *Lang: HU, EN.* 
- [Állami Számvevőszék – ÁSZ (State Audit Office)](https://www.asz.hu) — audit reports on public bodies, state-owned companies, political parties and party foundations; weekly report lists and audit plan. *Lang: HU, EN.* 
- [CRCB – Corruption Research Center Budapest](https://www.crcb.eu) — downloadable contract-level datasets of Hungarian public procurement (1998–2025) with corruption-risk indicators, and lists of high-risk contracts (2011–2026). *Lang: EN, HU.*

## WHOIS
- [domain.hu – Domain keresés (.hu Domain Search)](https://www.domain.hu/domain-kereses/) — official .hu registry (ISZT Nonprofit Kft.): availability check, then public data of registered domains after a captcha; private holders shown only as "Természetes személy" (natural person); contact form to holder or admin contact. *Lang: HU, EN.*
- [domain.hu – Meghirdetés (Published Domain Lists)](https://www.domain.hu/meghirdetes/) — newly applied-for .hu domains (8-day objection period), domains in 30-day pre-deletion parking, and domains of deceased users; private holders' personal data not published. *Lang: HU, EN.*
- [domain.hu – Technikai ellenőrzés (DNS Technical Check)](https://info.domain.hu/webregcheck/) — DNS and nameserver configuration check for a .hu domain, optional DNSSEC test. *Lang: HU.*
- [domain.hu – Regisztrátorok (.hu Registrars)](https://www.domain.hu/regisztratorok/) — list of ~120 .hu registrars with profile pages. *Lang: HU, EN.*
- [ViewDNS.info](https://viewdns.info) — free DNS and IP tools: reverse IP, reverse WHOIS, IP history, subdomain discovery, DNS records, reverse NS/MX. *Lang: EN.*

---

## Contributing

To contribute to this repository:
1. Verify all links are working and accessible
2. Provide accurate descriptions of database contents
3. Follow the 7-category structure
4. Include official government sources when available
5. Submit pull requests with detailed change descriptions

## Legal Disclaimer

This repository is for educational and legitimate investigative purposes only. Users are responsible for:
- Complying with all applicable laws and regulations
- Respecting terms of service for all databases and tools
- Using information ethically and responsibly
- Obtaining proper authorization when required

The information provided is for informational purposes only and should not be considered legal advice.

---

**Repository maintained by the [OSINT-for-Countries-V2.0 community](https://github.com/Provereno-Media/OSINT-for-countries-V2.0)**
