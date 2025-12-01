# 192.com Businesses Scraper

![Banner](https://i.ibb.co/1GXK9xRQ/Screenshot-2025-11-02-at-4-14-32-PM.png)

This Apify actor allows you to scrape business directory data from **192.com**, the UK's leading online directory. Extract comprehensive business information including contact details, locations, websites, opening hours, and market sectors — perfect for business intelligence, market research, and directory data collection.

<p align="center">
  <img src="https://apify-image-uploads-prod.s3.us-east-1.amazonaws.com/DevbkY3adMTBuoECt-actor-Cfp9stC9qcoKKFCZG-haThOgnN0i-295331757_473876728075220_6639252721489178882_n.jpg" alt="192.com Businesses Scraper" style="height: 60px; margin-right: 15px;" /><a href="https://apify.com/lexis-solutions/192-com-businesses-scraper" target="_blank">
    <img src="https://img.shields.io/badge/Try%20it%20on-Apify-0066FF?style=for-the-badge&logo=data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iNDA4IiBoZWlnaHQ9IjQwOCIgdmlld0JveD0iMCAwIDQwOCA0MDgiIGZpbGw9Im5vbmUiIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyI+CjxnIGNsaXAtcGF0aD0idXJsKCNjbGlwMF8zNDFfNDE1NykiPgo8cGF0aCBkPSJNMjE4LjY5NSAxMDRIMzAwLjk3QzMwMi42NDMgMTA0IDMwNCAxMDUuMzU3IDMwNCAxMDcuMDNWMjMyLjc2NkMzMDQgMjM1Ljc3OCAzMDAuMDgzIDIzNi45NDUgMjk4LjQzNCAyMzQuNDI1TDIxNi4xNTkgMTA4LjY5QzIxNC44NDEgMTA2LjY3NCAyMTYuMjg3IDEwNCAyMTguNjk1IDEwNFoiIGZpbGw9IndoaXRlIi8+CjxwYXRoIGQ9Ik0xODkuMzA1IDEwNEgxMDcuMDNDMTA1LjM1NyAxMDQgMTA0IDEwNS4zNTcgMTA0IDEwNy4wM1YyMzIuNzY2QzEwNCAyMzUuNzc4IDEwNy45MTcgMjM2Ljk0NSAxMDkuNTY2IDIzNC40MjVMMTkxLjg0IDEwOC42OUMxOTMuMTU5IDEwNi42NzQgMTkxLjcxMyAxMDQgMTg5LjMwNSAxMDRaIiBmaWxsPSJ3aGl0ZSIvPgo8cGF0aCBkPSJNMjAyLjU5MSAyMDQuNjY4TDEwOS4xMjcgMjk4LjgzNUMxMDcuMjI5IDMwMC43NDcgMTA4LjU4MyAzMDQgMTExLjI3OCAzMDRIMjk2LjhDMjk5LjQ4MyAzMDQgMzAwLjg0MiAzMDAuNzcgMjk4Ljk2NyAyOTguODUyTDIwNi45MDggMjA0LjY4NUMyMDUuNzI2IDIwMy40NzUgMjAzLjc4MiAyMDMuNDY4IDIwMi41OTEgMjA0LjY2OFoiIGZpbGw9IndoaXRlIi8+CjwvZz4KPGRlZnM+CjxjbGlwUGF0aCBpZD0iY2xpcDBfMzQxXzQxNTciPgo8cmVjdCB3aWR0aD0iMjAwIiBoZWlnaHQ9IjIwMCIgZmlsbD0id2hpdGUiIHRyYW5zZm9ybT0idHJhbnNsYXRlKDEwNCAxMDQpIi8+CjwvY2xpcFBhdGg+CjwvZGVmcz4KPC9zdmc+Cg==&logoColor=white" alt="Try it on Apify" style="border-radius: 12px; height: 60px;" />
  </a>
</p>


---


## 📊 Actor Stats

| Stat | Value |
|------|-------|
| **Version** | `1.0.1` |
| **Last Update** | Dec 1, 2025 |

---



## 💻 Integration Examples

This repository includes example code showing how to integrate the `192-com-businesses-scraper` actor into your projects.

You can find example implementations in the [`examples/`](./examples) folder:
- **TypeScript/JavaScript**: See [`examples/typescript/`](./examples/typescript) for a complete TypeScript example
- **Python**: See [`examples/python/`](./examples/python) for a complete Python example

Each example includes:
- Ready-to-use code templates
- Setup instructions
- Documentation links

---


## 🚀 Key Features

- 🔎 Search and extract business listings from **192.com**
- 🏢 Extract detailed business information (name, address, phone, website)
- 📍 Location-based filtering across the UK
- 🕒 Opening hours and operational status
- 📄 Structured business data extraction with 15+ fields
- 🌐 Proxy support for stable, anonymous scraping


---

## ❓ Why Use This Actor

- ✅ Automate business directory data collection
- ✅ Save hours of manual browsing and copying from **192.com**
- ✅ Build datasets for business intelligence and market research
- ✅ Monitor business presence and contact information
- ✅ Integrate data into CRM systems and business platforms
- ✅ Research local markets and competitor analysis

---

## 👥 Who Is This Actor Suitable For?

- 🏢 Business intelligence analysts and researchers
- 📊 Market research companies
- 🧠 Data scientists studying business landscapes
- 🧰 Developers building business directory platforms
- 📚 Academic researchers studying business markets
- 💼 Sales and marketing teams

---

## 📥 Input Schema

The actor accepts the following input parameters:

```json
{
  "who": "restaurant",
  "where": "London",
  "maxResults": 10,
  "proxyConfiguration": {
    "useApifyProxy": false
  }
}
```

### Input Parameters

- **who** (required): Business name or type to search for (e.g., 'plumber', 'Tesco', 'restaurant')
- **where** (optional): Location to search (e.g., 'London', 'SW6', 'Manchester')
- **maxResults** (optional): Maximum number of business results to extract.
- **proxyConfiguration** (optional): Proxy settings for anonymous scraping

---

## 📤 Output Schema

Each scraped business returns the following structured data:

```json
{
  "position": 1,
  "name": "The Ivy Market Grill",
  "marketSector": "Restaurant",
  "phone": "020 3146 7337",
  "address": "Market Building, Stoney Street, London SE1 9AA",
  "detailUrl": "https://www.192.com/businesses/details/london-se1/the-ivy-market-grill/123456789/",
  "searchType": "Businesses",
  "description": "Contemporary British restaurant in the heart of Borough Market...",
  "tags": ["British", "Contemporary", "Restaurant"],
  "website": "https://theivymarketgrill.co.uk",
  "logo": "https://www.192.com/logos/the-ivy-market-grill.png",
  "openingHours": "Mon-Sun: 12:00-22:30",
  "claimed": true,
  "isOpen": true,
  "fullAddress": {
    "street": "Market Building, Stoney Street",
    "city": "London",
    "postcode": "SE1 9AA"
  }
}
```

---

👀 p.s.

Got feedback or need an extension?

Lexis Solutions is a [certified Apify Partner](https://apify.com/partners/find). We can help you with custom solutions or data extraction projects.

Contact us over [Email](mailto:scraping@lexis.solutions) or [LinkedIn](https://www.linkedin.com/company/lexis-solutions)

## Support Our Work 💝

If you're happy with our work and scrapers, you're welcome to leave us a company review [here](https://apify.com/partners/find/lexis-solutions/review) and leave a review for the scrapers you're subscribed to. It will take you less than a minute but it will mean a lot to us!
