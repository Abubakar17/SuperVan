# 🚐 SuperVan — Safe School Rides

![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)
![GitHub Pages](https://img.shields.io/badge/Deployed-GitHub%20Pages-222?logo=githubpages&logoColor=white)

> **"Aap ka Bacha, Hamari Imanat"**: *your child, our responsibility.*

Website for **SuperVan**, a startup concept that makes school transport something parents can trust. It pitches a service built around live tracking, in-van cameras and vetted, rated drivers, with a full landing page, blog and contact flow.

## The idea

Parents who send children to school in private vans usually have no idea where the van is, who is driving, or whether something went wrong. SuperVan answers each of those concerns:

| Concern | SuperVan feature |
|---|---|
| *Where is my child right now?* | 📍 Real-time GPS tracking of every van |
| *When will they arrive?* | 🔔 Pick-up and drop-off alerts over SMS and WhatsApp |
| *Is the ride safe?* | 🎥 In-vehicle cameras for live surveillance |
| *Who is the driver?* | ⭐ Driver ratings and parent reviews |
| *What if something happens?* | 🚨 One-tap emergency alerts |
| *How do I reach the driver?* | 💬 Direct driver–parent messaging |

## The site

- **Home:** hero, parent concerns, features, team, pricing call-to-action and FAQ
- **About:** the mission behind SuperVan
- **Blog:** listing page and post template for updates
- **Contact:** enquiry form with international phone-number input

Deployed automatically to GitHub Pages through a GitHub Actions workflow (`.github/workflows/static.yml`).

## Run locally

It's a static site, so there's no build step:

```bash
git clone https://github.com/Abubakar17/SuperVan.git
cd SuperVan
python -m http.server 8000   # then open http://localhost:8000
```

**Built with:** HTML, CSS, JavaScript and jQuery, designed in Nicepage, with intl-tel-input for the contact form.
