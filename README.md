# Fractional CIO Executive Command Center

A complete, static executive technology assessment for **Northstar Manufacturing Group**, a fictional manufacturing enterprise. Built for **Stefen St. Jules**, Principal Enterprise IT & Cybersecurity Consultant, ZenTechnology LLC.

## Overview

This public portfolio demonstrates how a Fractional CIO translates a complex technology environment into executive decisions: business risk, control maturity, investment priorities, and a phased modernization roadmap. The premium responsive dashboard includes 12 navigable views, local filters, accessible charts, expandable recommendations, and an interactive roadmap.

## Capabilities Demonstrated

- Enterprise technology strategy and Fractional CIO / CTO advisory
- Cybersecurity assessment and risk prioritization
- Identity and access governance
- Microsoft cloud architecture and modernization
- IT operations, endpoint management, and resilience
- Vendor governance and technology financial management
- Application rationalization
- Governance and compliance readiness
- AI strategy, responsible adoption, and automation
- Executive reporting and technology roadmaps

## Demo Data

**Every organization, account, device, application, financial figure, vendor, incident, and operational metric is fictional and synthetic.** Northstar Manufacturing Group is not a real customer. The named consultant and consulting business identify the portfolio author; application owners are fictional role labels.

The dataset includes 750 employees, 835 endpoints, 96 individually listed applications, 18 business locations, 14 fictional vendors, and a simulated $2.4M annual budget. Five findings include one Critical, three High, and one Medium risk; the overview's four priority risks combine Critical and High findings. Framework percentages describe illustrative readiness or alignment, never certification. Vendor spending includes pass-through costs and must not be added to budget allocations. Savings are illustrative estimates.

## Architecture

Plain HTML5, CSS, and JavaScript. No framework, build, installation, server-side runtime, authentication, or external dependency is required. Classic scripts load local data before presentation logic, so `file://` opening also works.

```text
index.html
assets/
  css/main.css
  js/app.js
  data/
    organization.js
    risks.js
    applications.js
    vendors.js
    roadmap.js
  favicon.svg
  social-preview.svg
README.md
LICENSE
.gitignore
```

Charts use responsive HTML/CSS with descriptive accessible labels. Data tables have semantic column headers and scrollable containers. Hash navigation supports direct links and browser history. All calculations and filters run in the browser. Data is not persisted or submitted anywhere.

## Run Locally

Open `index.html` directly, or run:

```sh
python3 -m http.server 8080
```

Then visit `http://localhost:8080`. No package installation is needed.

## Deployment

### Hostinger

Deploy the repository contents as static files. The document root must contain `index.html` and the complete `assets` directory.

1. Push the project to a GitHub repository named `fractional-cio-command-center`.
2. If your Hostinger plan exposes a Git repository deployment option for web hosting, connect the repository and select its branch. Use the repository root as the source and your domain's public document root (typically `public_html`) as the destination. No build command is needed.
3. Alternatively, upload `index.html` and `assets/` using Hostinger File Manager or SFTP into `public_html`. Preserve directory names and case.
4. Open the domain and check navigation, filters, charts, and mobile layout. Enable HTTPS through your hosting controls.

Hostinger product interfaces and Git integration availability depend on the hosting plan. This project needs ordinary static web hosting; it does not need Node.js hosting or a backend deployment workflow. Connecting a repository must copy the files to the served document root.

See [Hostinger’s Git deployment guide](https://www.hostinger.com/support/1583302-how-to-deploy-a-git-repository-in-hostinger/) for the current hosting controls.

All asset paths are relative. The application works at a domain root or a subdirectory without route rewrites. Optional: replace the SVG social preview with a hosted PNG for broader social-network preview compatibility, and add a canonical URL after a public domain is assigned.

## Security

- No secrets are required.
- No database is required.
- No API keys are used.
- No environment variables are required.
- No production systems, customers, tenants, identity providers, or APIs are connected.
- All operational data is synthetic.
- No remote fonts, analytics, third-party scripts, cookies, or contact submissions are used.

The engagement CTA opens a local discussion agenda and directs visitors to the professional contact channel where the portfolio was shared. It deliberately contains no invented contact address.

## Accessibility & Performance

Semantic landmarks, skip navigation, keyboard focus indicators, labeled filters, live result counts, accessible tables, native disclosure controls, native modal dialogs, reduced-motion support, and keyboard-operable roadmap tabs are included. Local system fonts and CSS charts keep the site lightweight.

## Verification

Verified in headless Chromium with all 12 views at 1440, 1024, 768, and 390 pixel viewport widths. No page-level horizontal overflow. Risk, application, and vendor filters, empty results, roadmap arrow-key navigation, expandable recommendations, detail dialogs, mobile navigation, and consulting CTAs passed interaction checks. Direct-file opening and HTTP domain-root serving both passed. Browser checks recorded zero JavaScript console errors and zero external requests. All runtime assets loaded locally. Public hosting deployment remains the repository owner’s final step.

## Author

**Stefen St. Jules**<br>
Principal Enterprise IT & Cybersecurity Consultant<br>
**ZenTechnology LLC**

## License

MIT. See [LICENSE](LICENSE).
