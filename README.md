## 🤖 [Messe Frankfurt Exhibitor List Scraper](https://apify.com/skython/messe-frankfurt-exhibitor-list-scraper)

Simple web scraper for extracting exhibitor data from trade show exhibitor lists provided by **Messe Frankfurt**. Easily scrape company profiles including **company details, websites, social media links, contact persons, product groups, brands, and more**. 

Ideal for **B2B lead generation, market research, event networking, and competitive analysis**. Supports multiple **Messe Frankfurt** exhibition websites with a consistent HTML structure.

> [Apify](https://apify.com/) is a cloud platform and marketplace for web scraping and automation tools.

---

## Contents

- [Features](#features)

- [Use Cases](#use-cases)

- [Supported Website Structure](#supported-website-structure)

- [Supported Messe Frankfurt Events (Exhibitor Lists)](#supported-messe-frankfurt-events-exhibitor-lists)

- [Testing Exhibitor List URLs](#testing-exhibitor-list-urls-for-free)

- [Exhibitor List Scraper - All-In-One Version](#exhibitor-list-scraper---all-in-one-version)

- [Data Fields](#data-fields)

- [Example Output](#example-output)

- [My Other Exhibitor List Scrapers](#my-other-exhibitor-list-scrapers)

---

## Features

- Scrape all exhibitor profiles from supported Messe Frankfurt event websites

- Extract detailed data from every exhibitor profile page

- Company primary information (address, email, phone, website)

- Social media links (LinkedIn, Facebook, Instagram, Twitter, YouTube)

- Contact person details

- Product groups with full hierarchical structure

- Two output formats (Single-Row & Multi-Row)

- Multi-Row format for Excel-friendly product group filtering

- Export to JSON, CSV, and Excel

---

## Use Cases

- **B2B Lead Generation:** Build targeted contact lists for marketing and sales outreach. 

- **Market Research:** Analyze exhibitors by product categories, brands, and sectors.  

- **Event Networking:** Familiarize yourself with exhibitors before attending trade fairs.  

- **Competitive Analysis:** Track competitor participation and product focus areas.

---

## Supported Website Structure

- This scraper is designed to extract data from exhibitor directories with the same HTML structure as the supported Messe Frankfurt exhibitor lists below.

- Take a look at some of the event websites from the below list. Your event website URL might be in that list.

- If you are not sure about if this actor is capable of scraping your event URL, test it with [**Exhibitor List Scrapers URL Tester**](https://apify.com/skython/exhibitor-list-scrapers-router) actor.

---

## Supported Messe Frankfurt Events (Exhibitor Lists)

> The following partial list includes Messe Frankfurt exhibitor directory URLs that have been tested so far. Other Messe Frankfurt events or different events with the same website structure may also be supported.

> Some event URLs may have been updated or canceled entirely; please check them before using.

- [Ambiente 2026 Exhibitor List – ambiente.messefrankfurt.com](https://ambiente.messefrankfurt.com/frankfurt/en/exhibitor-search.html)

- [Arminera 2025 Exhibitor List – arminera.ar.messefrankfurt.com](https://arminera.ar.messefrankfurt.com/buenosaires/en/exhibitor-search.html)

- [Automechanika Birmingham 2025 Exhibitor List – automechanika-birmingham.uk.messefrankfurt.com](https://automechanika-birmingham.uk.messefrankfurt.com/birmingham/en/exhibitors-products1.html)

- [Automechanika Ho Chi Minh City 2026 Exhibitor List – automechanika-hcmc.hk.messefrankfurt.com](https://automechanika-hcmc.hk.messefrankfurt.com/hochiminhcity/en/exhibitor-search.html)

- [Automechanika Kuala Lumpur 2026 Exhibitor List – automechanika-kualalumpur.hk.messefrankfurt.com](https://automechanika-kualalumpur.hk.messefrankfurt.com/kualalumpur/en/exhibitor-search.html)

- [Automechanika Frankfurt 2026 Exhibitor List – automechanika.messefrankfurt.com](https://automechanika.messefrankfurt.com/frankfurt/en/exhibitor-search.html)

- [Automechanika Johannesburg 2025 Exhibitor List – automechanika.za.messefrankfurt.com](https://automechanika.za.messefrankfurt.com/johannesburg/en/Exhibitors/2025_Exhibitors.html)

- [Beautyworld Japan Nagoya 2026 Exhibitor List – beautyworld-japan-nagoya.jp.messefrankfurt.com](https://beautyworld-japan-nagoya.jp.messefrankfurt.com/nagoya/en/exhibitor-search.html)

- [Beautyworld Saudi Arabia 2025 Exhibitor List – beautyworld-saudi-arabia.ae.messefrankfurt.com](https://beautyworld-riyadh.ksa.messefrankfurt.com/ksa/en/exhibitor-search.html)

- [BIEL Light + Building Buenos Aires 2025 Exhibitor List – biel-light-building.ar.messefrankfurt.com](https://biel-light-building.ar.messefrankfurt.com/buenosaires/en/exhibitor-search.html)

- [Christmasworld 2026 Exhibitor List – christmasworld.messefrankfurt.com](https://christmasworld.messefrankfurt.com/frankfurt/en/exhibitor-search.html)

- [Creativeworld 2026 Exhibitor List – creativeworld.messefrankfurt.com](https://creativeworld.messefrankfurt.com/frankfurt/en/exhibitor-search.html)

- [EMV Stuttgart 2026 Exhibitor List – emv.mesago.com/stuttgart](https://emv.mesago.com/stuttgart/en/exhibitor-search.html)

- [Eurobike 2026 Exhibitor List – eurobike.com](https://eurobike.com/frankfurt/en/exhibitor-search.html)

- [ExpoFerretera 2025 Exhibitor List – expoferretera.ar.messefrankfurt.com](https://expoferretera.ar.messefrankfurt.com/buenosaires/en/exhibitor-search.html)

- [Formnext Asia Shenzhen 2026 Exhibitor List – formnext-sz.hk.messefrankfurt.com](https://formnext-sz.hk.messefrankfurt.com/shenzhen/en/exhibitor-search.html)

- [Formnext 2025 Exhibitor List – formnext.mesago.com](https://formnext.mesago.com/frankfurt/en/exhibitor-search.html)

- [Guangzhou International Lighting 2026 Exhibitor List – guangzhou-international-lighting-exhibition.hk.messefrankfurt.com](https://guangzhou-international-lighting-exhibition.hk.messefrankfurt.com/guangzhou/en/exhibitor-search.html)

- [Heimtextil 2026 Exhibitor List – heimtextil.messefrankfurt.com](https://heimtextil.messefrankfurt.com/frankfurt/en/exhibitor-search.html)

- [IFFA 2025 Exhibitor List – iffa.messefrankfurt.com](https://iffa.messefrankfurt.com/frankfurt/en/exhibitor-search.html)

- [INA PAACE Automechanika Mexico City 2026 Exhibitor List – ina-paace-automechanika-mexico-city.us.messefrankfurt.com](https://ina-paace-automechanika-mexico-city.us.messefrankfurt.com/mexico-city/en/showschedule/exhibitorsearch.html)

- [Emitex, Simatex and Confemaq 2024 Exhibitor List – industriatextilexpo.ar.messefrankfurt.com](https://industriatextilexpo.ar.messefrankfurt.com/buenosaires/en/exhibitor-search.html)

- [Interior Lifestyle Tokyo 2026 Exhibitor List – interiorlifestyle-tokyo.jp.messefrankfurt.com](https://interiorlifestyle-tokyo.jp.messefrankfurt.com/tokyo/en/exhibitor-search.html)

- [Interpets Osaka 2026 Exhibitor List – interpets-osaka.jp.messefrankfurt.com](https://interpets-osaka.jp.messefrankfurt.com/osaka/en/exhibitor-search.html)

- [Intersec Saudi Arabia 2025 Exhibitor List – intersec-ksa.ae.messefrankfurt.com](https://intersec-saudiarabia.ksa.messefrankfurt.com/ksa/en/exhibitor-search.html)

- [Intersec Global 2026 Exhibitor List – intersec.ae.messefrankfurt.com](https://intersecglobal.ae.messefrankfurt.com/dubai/en/exhibitor-search/exhibitor-search.html)

- [Intertextile Shanghai Apparel Fabrics Autumn 2026 Exhibitor List – intertextile-shanghai-apparel-fabrics-autumn.hk.messefrankfurt.com](https://intertextile-shanghai-apparel-fabrics-autumn.hk.messefrankfurt.com/shanghai/en/exhibitor-search.html)

- [Intertextile Shanghai Apparel Fabrics Spring 2026 Exhibitor List – intertextile-shanghai-apparel-fabrics-spring.hk.messefrankfurt.com](https://intertextile-shanghai-apparel-fabrics-spring.hk.messefrankfurt.com/shanghai/en/exhibitor-search.html)

- [Intertextile Shenzhen 2026 Exhibitor List – intertextile-shenzhen.hk.messefrankfurt.com](https://intertextile-shenzhen.hk.messefrankfurt.com/shenzhen/en/exhibitor-search.html)

- [ISH 2025 Exhibitor List – ish.messefrankfurt.com](https://ish.messefrankfurt.com/frankfurt/en/exhibitor-search.html)

- [Light + Intelligent Building Istanbul 2026 Exhibitor List – light-building-istanbul.tr.messefrankfurt.com](https://light-building-istanbul.tr.messefrankfurt.com/istanbul/en/exhibitors-products.html)

- [Light + Building 2026 Exhibitor List – light-building.messefrankfurt.com](https://light-building.messefrankfurt.com/frankfurt/en/exhibitor-search.html)

- [Light + Intelligent Building Middle East 2026 Exhibitor List – light-middle-east.ae.messefrankfurt.com](https://light-middle-east.ae.messefrankfurt.com/dubai/en/exhibitor-search.html)

- [Motobike Istanbul 2026 Exhibitor List – motobike-istanbul.tr.messefrankfurt.com](https://motobike-istanbul.tr.messefrankfurt.com/istanbul/en/exhibitors-products.html)

- [Nordstil 2026 Exhibitor List – nordstil.messefrankfurt.com](https://nordstil.messefrankfurt.com/hamburg/en/exhibitor-search.html)

- [PCIM Expo 2026 Exhibitor List – pcim.mesago.com](https://pcim.mesago.com/nuernberg/en/exhibitor-search.html)

- [PCIM Asia Shanghai 2026 Exhibitor List – pcimasia-shanghai.cn.messefrankfurt.com](https://pcimasia-shanghai.cn.messefrankfurt.com/shanghai/en/exhibitor-search.html)

- [Prolight + Sound 2025 Exhibitor List – pls.messefrankfurt.com](https://pls.messefrankfurt.com/frankfurt/en/exhibitor-search.html)

- [SPS 2026 Exhibitor List – sps.mesago.com](https://sps.mesago.com/nuernberg/en/exhibitor-search.html)

- [SPS Guangzhou 2026 Exhibitor List – spsinchina.cn.messefrankfurt.com](https://spsinchina.cn.messefrankfurt.com/guangzhou/en/exhibitor-search.html)

- [Techtextil India 2025 Exhibitor List – techtextil-india.in.messefrankfurt.com](https://techtextil-india.in.messefrankfurt.com/mumbai/en/exhibitor-search.html)

- [Techtextil 2026 Exhibitor List – techtextil.messefrankfurt.com](https://techtextil.messefrankfurt.com/frankfurt/en/exhibitor-search.html)

- [Tecno Fidta 2026 Exhibitor List – tecnofidta.ar.messefrankfurt.com](https://tecnofidta.ar.messefrankfurt.com/buenos-aires/en/exhibitor-search.html)

- [Texcare International 2024 Exhibitor List – texcare.messefrankfurt.com](https://texcare.messefrankfurt.com/frankfurt/en/exhibitor-search.html)

- [Texprocess 2026 Exhibitor List – texprocess.messefrankfurt.com](https://texprocess.messefrankfurt.com/frankfurt/en/exhibitor-search.html)

- [VIATT 2026 Exhibitor List – viatt.hk.messefrankfurt.com](https://viatt.hk.messefrankfurt.com/hochiminhcity/en/exhibitor-search.html)

---

## Testing Exhibitor List URLs for FREE

- Since I have multiple exhibitor list scraper actors for different types of trade event websites, it might be hard to find the correct actor for your exhibitor list URL.

- Use [**Exhibitor List Scrapers URL Tester**](https://apify.com/skython/exhibitor-list-scrapers-router) actor to test your exhibitor list URLs **for FREE** and see which scraper can process them.

---

## Exhibitor List Scraper - All-In-One Version

- I also provide an **All-In-One** version that combines **my 30+ exhibitor list scrapers** into a single actor.

- Instead of searching for the correct scraper for each event URL, simply provide the event URL and the actor automatically selects the appropriate scraper.

- ➡️ [Exhibitor List Scraper - All-In-One](https://apify.com/skython/exhibitor-list-scraper)

---

## Data Fields

<table>
  <thead>
    <tr>
    <th><span style="font-size:14px;">Company</span></th>
    <th><span style="font-size:14px;">Social</span></th>
    <th><span style="font-size:14px;">Additional</span></th>
    </tr>
  </thead>
    <tbody>
        <tr>
            <td>Profile URL</td>
            <td>LinkedIn</td>
            <td>Hall Stands</td>
        </tr>
        <tr>
            <td>Company Name</td>
            <td>Facebook</td>
            <td>Product Groups</td>
        </tr>
        <tr>
            <td>Address</td>
            <td>Instagram</td>
            <td>Brands</td>
        </tr>
        <tr>
            <td>Website</td>
            <td>Twitter / X</td>
            <td>Keywords</td>
        </tr>
        <tr>
            <td>Email</td>
            <td>YouTube</td>
            <td>Contact Persons</td>
        </tr>
        <tr>
            <td>Phone</td>
            <td></td>
            <td></td>
        </tr>
    </tbody>
</table>

---

## Example Output

```json
{
  "___exhibitor_profile_url": "https://eurobike.com/frankfurt/en/exhibitor-search.detail.html/amazing-industries.html",
  "__company_name": "Amazing Industries",
  "_company_address": "Zafarwali, Sambrial 25-KM Wazirabad Road, Sialkot, 51310, Pakistan",
  "_company_country": "Pakistan",
  "_company_email": "info@amazingind.com",
  "_company_phone": "+92 301 8378700",
  "_company_website": "www.amazingind.com",
  "_hall_stands": "Hall 8.0 - F58",
  "_social_url_linkedin": ["https://www.linkedin.com/company/amazing-industries-sialkot-pakistan/"],
  "_social_url_facebook": ["https://www.facebook.com/amazinginds"],
  "keywords": "Gloves | Cycling Gloves | Bike Gloves | Handschuh | Apparels",
  "contact_persons": [
    {
      "_name": "Ahsan Ilahi",
      "department": "Sales",
      "position": "Head of Department"
    }
  ],
  "product_categories": [
    {
      "title": "Clothing",
      "subgroups": [
        {
          "title": "Jackets",
          "subgroups": [
            {
              "title": "Winter",
              "subgroups": null
            }
          ]
        },
        {
          "title": "Accessories",
          "subgroups": [
            {
              "title": "Gloves",
              "subgroups": null
            },
            {
              "title": "Arm Warmers",
              "subgroups": null
            }
          ]
        }
      ]
    }
  ]
}
```

---

## My Other Exhibitor List Scrapers

- [Exhibitor List Scraper - All-In-One](https://apify.com/skython/exhibitor-list-scraper)

- [Koelnmesse Exhibitor List Scraper](https://apify.com/skython/koelnmesse-exhibitor-list-scraper)

- [Map Your Show Exhibitor List Scraper](https://apify.com/skython/map-your-show-exhibitor-list-scraper)

- [Messe Düsseldorf Exhibitor List Scraper](https://apify.com/skython/messe-duesseldorf-exhibitor-list-scraper)

- [Xporience Exhibitor List Scraper](https://apify.com/skython/xporience-exhibitor-list-scraper)

- [Reed Expo Exhibitor List Scraper](https://apify.com/skython/reed-expo-exhibitor-list-scraper)

- [Messe München Exhibitor List Scraper](https://apify.com/skython/messe-muenchen-exhibitor-list-scraper)

- [Xporience Exhibitor List Scraper V2](https://apify.com/skython/xporience-exhibitor-list-scraper-2)

- [Nürnberg Messe Exhibitor List Scraper](https://apify.com/skython/nuernberg-messe-exhibitor-list-scraper)

- [GSMA MWC Exhibitor List Scraper](https://apify.com/skython/gsma-mwc-exhibitor-list-scraper)

- [Messe Berlin Exhibitor List Scraper](https://apify.com/skython/messe-berlin-exhibitor-list-scraper)

- [AFAG Messe Exhibitor List Scraper](https://apify.com/skython/afag-messe-exhibitor-list-scraper)

- [Messe Stuttgart Exhibitor List Scraper](https://apify.com/skython/messe-stuttgart-exhibitor-list-scraper)

- [Messe Essen Exhibitor List Scraper](https://apify.com/skython/messe-essen-exhibitor-list-scraper)

- [Informa Markets Exhibitor List Scraper](https://apify.com/skython/informa-markets-exhibitor-list-scraper)

- [Informa Markets Exhibitor List Scraper V2](https://apify.com/skython/informa-markets-exhibitor-list-scraper-2)

- [Ungerboeck Exhibitor List Scraper](https://apify.com/skython/ungerboeck-exhibitor-list-scraper)

- [A2Z Events Exhibitor List Scraper](https://apify.com/skython/a2z-events-exhibitor-list-scraper)

- [Deutsche Messe Exhibitor List Scraper](https://apify.com/skython/deutsche-messe-exhibitor-list-scraper)

- [Newfront Exhibitor List Scraper](https://apify.com/skython/newfront-exhibitor-list-scraper)

- [Goeshow Exhibitor List Scraper](https://apify.com/skython/goeshow-exhibitor-list-scraper)

- [EasyFairs Exhibitor List Scraper](https://apify.com/skython/easyfairs-exhibitor-list-scraper)

- [IEG Expo Exhibitor List Scraper](https://apify.com/skython/ieg-expo-exhibitor-list-scraper)

- [The Smarter E Exhibitor List Scraper](https://apify.com/skython/the-smarter-e-exhibitor-list-scraper)

- [Schall Messen Exhibitor List Scraper](https://apify.com/skython/schall-messen-exhibitor-list-scraper)

- [Messe München Exhibitor List Scraper V2](https://apify.com/skython/messe-muenchen-exhibitor-list-scraper-2)

- [Comexposium Exhibitor List Scraper](https://apify.com/skython/comexposium-exhibitor-list-scraper)

- [IME Events Exhibitor List Scraper](https://apify.com/skython/ime-events-exhibitor-list-scraper)

- [ANDMORE Exhibitor List Scraper](https://apify.com/skython/andmore-exhibitor-list-scraper)

- [Comexposium Exhibitor List Scraper V2](https://apify.com/skython/comexposium-exhibitor-list-scraper-2)

- [Informa Markets Exhibitor List Scraper V3](https://apify.com/skython/informa-markets-exhibitor-list-scraper-3)