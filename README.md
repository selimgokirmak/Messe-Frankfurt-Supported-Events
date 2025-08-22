## 🤖 [Messe Frankfurt Exhibitor List Scraper](https://apify.com/skython/messe-frankfurt-exhibitor-list-scraper)

Simple web scraper for extracting exhibitor data from **Messe Frankfurt** trade show exhibitor lists. 

Easily scrape company profiles including **company details, websites, social media links, contact persons, product groups, brands, and more**. 

Ideal for **B2B lead generation, market research, event networking, and competitive analysis**. 

Supports multiple Messe Frankfurt trade fair websites with a consistent HTML structure.


## 🎯 Supported Website Structure

This scraper is designed to extract data from exhibitor directories with the same HTML structure as the supported Messe Frankfurt exhibitor lists.

### ❓ How to identify a supported website:

✅ Exhibitor listing page URL usually ends with `/exhibitor-search.html` or a similar format.

✅ There could be an `Exhibitors & Products` or `Exhibitor List` or a similar option under one of the menus (like in the image).

✅ Exhibitor listing page format should be the same as the sample websites below.

💡 **If you are unsure whether your target event website is supported,** you can run a test with the exhibitor listing page URL — if no results are returned, the website is not compatible.

<img src="exhibitor-list.png" alt="exhibitor search" width="100%" style="border: 2px solid #000; border-radius: 8px;"/>


## 🌐 Supported Messe Frankfurt Events (Exhibitor Lists)
**Note:** *The following list includes Messe Frankfurt exhibitor directory URLs that have been tested so far. Other Messe Frankfurt or different events with the same website structure may also be supported.*

- [Ambiente 2025 Exhibitor List](https://ambiente.messefrankfurt.com/frankfurt/en/exhibitor-search.html)

- [Apparel Sourcing 2025 Exhibitor List](https://texworld-paris.fr.messefrankfurt.com/paris/en/exhibitor-search/exhibitor-search-apps.html)

- [Arminera 2025 Exhibitor List](https://arminera.ar.messefrankfurt.com/buenosaires/en/exhibitor-search.html)

- [Automechanika Birmingham 2025 Exhibitor List](https://automechanika-birmingham.uk.messefrankfurt.com/birmingham/en/exhibitors-products1.html)

- [CAPAS Chengdu 2025 Exhibitor List](https://capas-chengdu.hk.messefrankfurt.com/chengdu/en/exhibitor-search.html)

- [Christmasworld 2025 Exhibitor List](https://christmasworld.messefrankfurt.com/frankfurt/en/exhibitor-search.html)

- [Creativeworld 2025 Exhibitor List](https://creativeworld.messefrankfurt.com/frankfurt/en/exhibitor-search.html)

- [Eurobike 2025 Exhibitor List](https://eurobike.com/frankfurt/en/exhibitor-search.html)

- [Heimtextil 2025 Exhibitor List](https://heimtextil.messefrankfurt.com/frankfurt/en/exhibitor-search.html)

- [IFFA 2025 Exhibitor List](https://iffa.messefrankfurt.com/frankfurt/en/exhibitor-search.html)

- [Interpets Osaka 2026 Exhibitor List](https://interpets-osaka.jp.messefrankfurt.com/osaka/en/exhibitor-search.html)

- [Intertextile Shenzhen 2025 Exhibitor List](https://intertextile-shenzhen.hk.messefrankfurt.com/shenzhen/en/exhibitor-search.html)

- [ISH 2025 Exhibitor List](https://ish.messefrankfurt.com/frankfurt/en/exhibitor-search.html)

- [Nordstil 2025 Exhibitor List](https://nordstil.messefrankfurt.com/hamburg/en/exhibitor-search.html)

- [Parken 2025 Exhibitor List](https://parken.mesago.com/wiesbaden/en/exhibitor-search.html)

- [PCIM Expo 2025 Exhibitor List](https://pcim.mesago.com/nuernberg/en/exhibitor-search.html)

- [Prolight + Sound 2025 Exhibitor List](https://pls.messefrankfurt.com/frankfurt/en/exhibitor-search.html)

- [SPS Guangzhou 2025 Exhibitor List](https://spsinchina.cn.messefrankfurt.com/guangzhou/en/exhibitor-search.html)

- [Texworld 2025 Exhibitor List](https://texworld-paris.fr.messefrankfurt.com/paris/en/exhibitor-search.html)

- [VIATT 2025 Exhibitor List](https://viatt.hk.messefrankfurt.com/hochiminhcity/en/exhibitor-search.html)

- [Automechanika Frankfurt 2024 Exhibitor List](https://automechanika.messefrankfurt.com/frankfurt/en/exhibitor-search.html)

- [Prolight + Sound Guangzhou 2025 Exhibitor List](https://prolight-sound-guangzhou.hk.messefrankfurt.com/guangzhou/en/exhibitor-search.html)

- [Guangzhou International Lighting 2025 Exhibitor List](https://guangzhou-international-lighting-exhibition.hk.messefrankfurt.com/guangzhou/en/exhibitor-search.html)

- [Interior Lifestyle Tokyo 2026 Exhibitor List](https://interiorlifestyle-tokyo.jp.messefrankfurt.com/tokyo/en/exhibitor-search.html)

- [Automechanika Ho Chi Minh City 2025 Exhibitor List](https://automechanika-hcmc.hk.messefrankfurt.com/hochiminhcity/en/exhibitor-search.html)

- [Beautyworld Japan Nagoya 2025 Exhibitor List](https://beautyworld-japan-nagoya.jp.messefrankfurt.com/nagoya/en/exhibitor-search.html)

- [Child Edu & Care Japan West 2024 Exhibitor List](https://hoikuhaku-west.jp.messefrankfurt.com/osaka/en/exhibitor-search.html)

- [INA PAACE Automechanika Mexico City 2025 Exhibitor List](https://ina-paace-automechanika-mexico-city.us.messefrankfurt.com/mexico-city/en/ExhibitorInformation/ExhibitorSearch.html)

- [Formnext Asia Shenzhen 2025 Exhibitor List](https://formnext-sz.hk.messefrankfurt.com/shenzhen/en/exhibitor-search.html)

- [PCIM Asia Shanghai 2025 Exhibitor List](https://pcimasia-shanghai.cn.messefrankfurt.com/shanghai/en/exhibitor-search.html)

- [Formnext Asia Tokyo Forum 2025 Exhibitor List](https://formnextforum.jp.messefrankfurt.com/tokyo/en/exhibitor-search.html)

- [Light + Building 2024 Exhibitor List](https://light-building.messefrankfurt.com/frankfurt/en/exhibitor-search.html)

- [Motobike Istanbul 2025 Exhibitor List](https://motobike-istanbul.tr.messefrankfurt.com/istanbul/en/exhibitors-products.html)

- [Automechanika Dubai 2024 Exhibitor List](https://automechanika-dubai.ae.messefrankfurt.com/dubai/en/exhibitor-search/exhibitor-list.html)

- [Automechanika Riyadh 2025 Exhibitor List](https://automechanika-riyadh.ae.messefrankfurt.com/riyadh/en/exhibitor-list.html)

- [Automechanika Kuala Lumpur 2025 Exhibitor List](https://automechanika-kualalumpur.hk.messefrankfurt.com/kualalumpur/en/exhibitor-search.html)

- [Automechanika Johannesburg 2025 Exhibitor List](https://automechanika.za.messefrankfurt.com/johannesburg/en/Exhibitors/2025_Exhibitors.html)

- [Automechanika Shanghai 2025 Exhibitor List](https://automechanika-shanghai.hk.messefrankfurt.com/shanghai/en/exhibitor-search.html)

- [Beautyworld Saudi Arabia 2025 Exhibitor List](https://beautyworld-saudi-arabia.ae.messefrankfurt.com/ksa/en/exhibitor-search.html)

- [Paperworld Middle East 2024 Exhibitor List](https://paperworld-middle-east.ae.messefrankfurt.com/dubai/en/exhibitor-search.html)

- [Gifts & Lifestyle Middle East 2024 Exhibitor List](https://gifts-lifestyle-middle-east.ae.messefrankfurt.com/dubai/en/exhibitor-search.html)

- [Intertextile Shanghai Apparel Fabrics Spring 2025 Exhibitor List](https://intertextile-shanghai-apparel-fabrics-spring.hk.messefrankfurt.com/shanghai/en/exhibitor-search.html)

- [Intertextile Shanghai Apparel Fabrics Autumn 2025 Exhibitor List](https://intertextile-shanghai-apparel-fabrics-autumn.hk.messefrankfurt.com/shanghai/en/exhibitor-search.html)

- [Techtextil 2024 Exhibitor List](https://techtextil.messefrankfurt.com/frankfurt/en/exhibitor-search.html)

- [Texprocess 2024 Exhibitor List](https://texprocess.messefrankfurt.com/frankfurt/en/exhibitor-search.html)

- [Light + Intelligent Building Middle East 2025 Exhibitor List](https://light-middle-east.ae.messefrankfurt.com/dubai/en/exhibitor-search.html)

- [Light + Intelligent Building Istanbul 2025 Exhibitor List](https://light-building-istanbul.tr.messefrankfurt.com/istanbul/en/exhibitors-products.html)

- [Intersec 2025 Exhibitor List](https://intersec.ae.messefrankfurt.com/dubai/en/exhibitor-search/exhibitor-search.html)

- [Intersec Saudi Arabia 2025 Exhibitor List](https://intersec-ksa.ae.messefrankfurt.com/ksa/en/exhibitor-search.html)

- [EMV 2025 Exhibitor List](https://emv.mesago.com/koeln/en/exhibitor-search.html)

- [SPS 2025 Exhibitor List](https://sps.mesago.com/nuernberg/en/exhibitor-search.html)

- [Formnext 2025 Exhibitor List](https://formnext.mesago.com/frankfurt/en/exhibitor-search.html)

- [Tecno Fidta 2024 Exhibitor List](https://tecnofidta.ar.messefrankfurt.com/buenos-aires/en/exhibitor-search.html)

- [Texcare France 2025 Exhibitor List](https://texcare-france.fr.messefrankfurt.com/paris/en/exhibitor-search.html)

- [Texcare International 2024 Exhibitor List](https://texcare.messefrankfurt.com/frankfurt/en/exhibitor-search.html)

- [ExpoFerretera 2025 Exhibitor List](https://expoferretera.ar.messefrankfurt.com/buenosaires/en/exhibitor-search.html)

- [Traffic Infratech Expo 2025 Exhibitor List](https://trafficinfratechexpo.in.messefrankfurt.com/newdelhi/en/exhibitor-search.html)

- [Media Expo New Delhi 2025 Exhibitor List](https://media-expo-newdelhi.in.messefrankfurt.com/newdelhi/en/exhibitor-search.html)

- [BIEL Light + Building Buenos Aires 2025 Exhibitor List](https://biel-light-building.ar.messefrankfurt.com/buenosaires/en/exhibitor-search.html)

- [Techtextil India 2025 Exhibitor List](https://techtextil-india.in.messefrankfurt.com/mumbai/en/exhibitor-search.html)