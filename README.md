![Banner](assets/banner.svg)

# Awesome-Business-Banking-Platform

## 🚀 Similar Projects to Business Banking Platforms

**Business Banking Platforms** (also called startup banks or neobanks for business) provide modern checking accounts, corporate cards, cash management, payments, and financial tooling tailored for startups, SMBs, and freelancers. Leading platforms include Mercury, Brex, Rho, Relay Financial, Bluevine, Found, Novo, NorthOne, Grasshopper, and Meow.

Below is a **curated list** of notable platforms and their open-source equivalents. Fully equivalent open-source business banking products do not exist in the traditional sense because real banking requires banking licenses, sponsor banks, and regulatory compliance. Open-source strength lies in core banking engines, ledgers, and fintech infrastructure that organizations (or licensed partners) can use to build similar experiences.

## 🏦 SaaS / Hosted Platforms

| Platform | Description | Pricing | Free Tier Limit | Valuation |
| :--- | :--- | :--- | :--- | :--- |
| **[Brex](https://www.brex.com/)** | Corporate card and business banking platform widely used by venture-backed companies. | Free (Premium tiers exist) | No monthly fees or minimums | $12.3B |
| **[Mercury](https://mercury.com/)** | Popular business banking platform for startups, offering checking accounts, cards, wires, and financial tools with a strong developer focus. | Free | No monthly fees, free domestic/USD international wires | $1.6B |
| **[Bluevine](https://www.bluevine.com/)** | Digital business banking and cash-management solutions serving startups, small businesses, and freelancers. | Free (Premier is $95/mo) | Unlimited transactions, no minimum balance | $1.0B |
| **[Novo](https://www.novo.co/)** | Digital business banking and cash-management solutions serving startups, small businesses, and freelancers. | Free | No monthly fees, free ACH transfers | $700M |
| **[Rho](https://www.rho.co/)** | All-in-one finance platform combining banking, cards, bill pay, expenses, and treasury for startups and scale-ups. | Free | No monthly fees or minimums, free wires | $150M |
| **[Relay Financial](https://relayfi.com/)** | Business banking focused on multi-account cash management and team spending controls. | Free (Pro is $30/mo) | Up to 20 checking accounts, 50 virtual cards | $140M |
| **[Found](https://found.com/)** | Digital business banking and cash-management solutions serving startups, small businesses, and freelancers. | Free (Plus is $19.99/mo) | Unlimited invoicing, standard transactions | $130M |
| **[NorthOne](https://www.northone.com/)** | Digital business banking and cash-management solutions serving startups, small businesses, and freelancers. | $10/month | No free tier | $120M |
| **[Grasshopper](https://www.grasshopper.bank/)** | Digital business banking and cash-management solutions serving startups, small businesses, and freelancers. | Free | Unlimited transactions, cash back on debit | $110M |
| **[Meow](https://www.meow.com/)** | Digital business banking and cash-management solutions serving startups, small businesses, and freelancers. | Custom | N/A | $100M |

## 🔓 Open-Source Software

### Open-Source Core Banking & Neobank Infrastructure
- **[Apache Fineract] <a href="https://github.com/apache/fineract/stargazers"><img src="https://img.shields.io/github/stars/apache/fineract?style=social&color=white" alt="stars"></a>(https://fineract.apache.org/)** — The most established open-source core banking platform. Provides accounts, loans, savings, transactions, and portfolio management. Widely used as the foundation for digital financial services and can power business banking products when paired with a licensed bank or BaaS partner.
- **[FinAegis] <a href="https://github.com/finaegis/finaegis/stargazers"><img src="https://img.shields.io/github/stars/finaegis/finaegis?style=social&color=white" alt="stars"></a>(https://finaegis.org/)** — Modern open-source core banking infrastructure built with domain-driven design, event sourcing, and CQRS. Includes modules for accounts, payments, compliance, multi-asset support, and Banking-as-a-Service patterns.
- Emerging open-source neobank and ledger projects (search GitHub for production-grade double-entry ledgers and microservices-based banking platforms) that demonstrate full account, wallet, and transaction systems.

### Supporting Open-Source Fintech Building Blocks
- Open-source double-entry ledger and accounting engines that form the system of record for any banking product.
- Identity, KYC/KYB orchestration tools (some with open-source cores) for customer onboarding.
- Payment orchestration and open banking API frameworks.
- Self-hosted finance dashboards and cash-management tools that businesses can run alongside traditional bank accounts.

### Related Open-Source Tools
- Personal and small-business finance managers (e.g., Firefly III) that offer strong multi-account tracking, though they are not full banking platforms.
- Open-source CRM and expense tools that complement business banking workflows.

### 💡 Reality Check & Typical Approach
True FDIC-insured business checking, debit/credit cards, and payment rails cannot be fully replicated in pure open source without a banking charter or sponsor-bank partnership. Most teams that want an “open” stack currently:

1. Use a commercial business banking platform (Mercury, Rho, Relay, etc.) for the regulated account and cards.
2. Layer open-source core banking, ledger, or analytics tools for internal control, custom products, or multi-entity reporting.
3. Or partner with Banking-as-a-Service providers while running open-source components for the customer-facing experience and ledger.

Open-source core banking projects remain the closest foundation for anyone building a new digital bank or embedded finance product.

---

**How to contribute**  
Fork this repository, add a new project (with link + short description + category), and open a pull request.  
Prefer actively maintained open-source projects related to core banking, neobank infrastructure, business finance ledgers, or Banking-as-a-Service components.

**License**  
This list is public domain / CC0. Feel free to copy into your own awesome list or README.

Star the projects you find useful — open banking infrastructure helps more teams build transparent and customizable financial products! 🏦
