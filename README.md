# Bechuana

I build and maintain the systems that run businesses. 

Most of my day-to-day involves untangling complex workflows, migrating legacy systems without breaking production, and making sure the API doesn't fall over when traffic spikes. I specialize in **Odoo ERP implementations** and **Laravel backend architecture**. 

I don't chase the newest frameworks. I use boring, reliable technology to solve actual business problems. Good code is quiet—it handles edge cases gracefully, doesn't wake me up at 3 AM, and lets the business focus on making money.

### What I'm working on right now

- **The Big Migration:** Moving a massive, multi-vendor e-commerce platform from Laravel 8 to Laravel 12 (PHP 8.5). 1,500+ files, 15 payment gateways, and a strict mandate of zero breaking changes to public API contracts. 
- **Odoo at Scale:** Partner-level ERP deployments (v16 through v19). Currently building custom Python modules for logistics and automating 3-way matching for procure-to-pay workflows.
- **API Hygiene:** Refactoring legacy payment integrations (M-Pesa, Stripe, direct bank APIs) into a unified adapter pattern so the core application doesn't care which gateway is actually processing the money.

### The Stack

I use the right tool for the job, but these are my daily drivers:

* **ERP & Business Logic:** Odoo (Python, XML, Studio), SAP B1 integrations.
* **Backend & APIs:** PHP 8.x (Laravel), RESTful API design, GraphQL, Webhooks.
* **Data:** PostgreSQL, MySQL, Redis. I care deeply about schema design and indexing.
* **Frontend:** Vue.js, Alpine.js, Tailwind. I prefer keeping the frontend as thin as possible.
* **Infrastructure:** Linux (Ubuntu), Nginx, Docker, GitHub Actions (CI/CD), Cron.

### My Engineering Principles

1. **Code is a liability.** Every line written is a line that must be read, tested, and maintained. The best code is the code you didn't have to write.
2. **Readability over cleverness.** If a junior developer can't understand your function at 4 PM on a Friday, it's not clever; it's a bug waiting to happen.
3. **The database is the source of truth.** ORMs are great, but they don't excuse a bad schema. Understand your indexes and your locks.
4. **Talk to the users.** An elegant technical solution to the wrong business problem is still a failure. 
5. **Contracts are sacred.** Never break a public interface. Use adapters, version your APIs, and deprecate gracefully.

### Notable Work

* **[Odoo Logistics Automation]** - Custom Odoo module handling multi-warehouse routing, stock replenishment triggers, and landed cost calculations.
* **[Laravel M-Pesa Package]** - A clean, heavily tested wrapper for the Safaricom Daraja API. Handles STK pushes, C2B, and B2C with proper queueing and retry mechanisms.
* **[Agri-Supply Chain Platform]** - Built a low-bandwidth Laravel/Vue application connecting smallholder farmers to buyers, featuring SMS fallbacks for offline users.

### Let's talk

If you're dealing with a messy legacy migration, need an ERP that actually fits your operations, or just want to argue about database normalization, I'm always open to a chat.

📫 **Email:** [mykbechuana@gmail.com](mailto:mykbechuana@gmail.com)  
💼 **LinkedIn:** [linkedin.com/in/bechuana1](https://linkedin.com/in/bechuana1)  
