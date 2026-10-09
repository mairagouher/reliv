<div align="center">

# RELiV

### Healthcare, now closer to you.

**A smart preventive healthcare kiosk for accessible screening, digital wellness insights, reports, and essential medicine dispensing.**

<br/>

[![Status](https://img.shields.io/badge/status-deployment--ready-success?style=for-the-badge)](https://github.com/Vaibhavcool4805/Reliv)
[![Platform](https://img.shields.io/badge/platform-Raspberry%20Pi%20%2B%20ESP32-black?style=for-the-badge)](https://github.com/Vaibhavcool4805/Reliv)
[![HealthTech](https://img.shields.io/badge/domain-HealthTech-orange?style=for-the-badge)](https://github.com/Vaibhavcool4805/Reliv)
[![SIH](https://img.shields.io/badge/Smart%20India%20Hackathon-2026-black?style=for-the-badge)](https://sih.gov.in/)

<br/>

<a href="https://relivkiosk.vercel.app/"><strong>Explore RELiV</strong></a>
&nbsp;&nbsp;•&nbsp;&nbsp;
<a href="#product-demo"><strong>Watch Demo</strong></a>
&nbsp;&nbsp;•&nbsp;&nbsp;
<a href="#documentation"><strong>Documentation</strong></a>

<br/><br/>

<img src="assets/gallery/Machine.jpeg" alt="RELiV preventive healthcare kiosk" width="850">

<br/>

*Physical RELiV kiosk — deployment-ready prototype.*

</div>

---

## The idea

Healthcare should be available where people already are.

**RELiV** is a preventive healthcare kiosk designed to make routine health screening and essential healthcare services more accessible in campuses, workplaces, gyms, and community spaces.

It combines a physical kiosk, local computing, sensor integration, a touch interface, wellness-report generation, digital payments, and a medicine-dispensing workflow into one guided experience.

> **You matter. RELiV cares.**

## Submission checklist

- [x] Team details
- [x] College/Incubator information
- [x] Project Title
- [x] Problem Statement
- [x] Healthcare Use Case
- [x] Technical Stack
- [x] AI/ML Model or Framework Details
- [x] 15–20 minute Demo Video is uploaded as an Unlisted YouTube video and the link is added to the README
- [x] Open-source License Details
- [x] Architecture Diagram in PDF/PPT format
- [x] Presentation in PDF/PPT format covering project details and outcomes
- [x] All files and links are publicly accessible without additional permissions

## Project snapshot

**Project title:** RELiV Smart Health Kiosk

**Problem statement:** Preventive healthcare remains difficult to access in everyday spaces such as campuses, workplaces, gyms, and community hubs. RELiV addresses this with a self-service kiosk that completes non-invasive health screening in around 3 minutes and produces an instant digital wellness summary.

**Healthcare use case:** Autonomous vitals checking for blood pressure, SpO₂, temperature, body metrics, and wellness guidance, available in English, Hindi, and Bengali.

**Team & institution:** RELiV Care Technologies, with the kiosk being developed and demonstrated from the IEM Gurukul Sector V Hub, Kolkata. The platform is recognized through Startup India, DPIIT, and Smart India Hackathon 2026 ecosystem visibility.

**Technical stack:** Raspberry Pi, ESP32/ESP32-S3, React, Node.js + Express, Python, SQLite, BLE/UART/MQTT, and a verified payment + dispensing flow.

**AI/ML and framework details:** See the project documentation and the public AI/ML framework details PDF in this repository: [AI/ML Framework Details](./open%20source%20and%20aiml%20frame%20work%20details.pdf).

## Public submission links

| Asset | Link |
|---|---|
| Live website | https://relivkiosk.vercel.app/ | Smart Preventive Health Screening India](https://relivkiosk.vercel.app/) |
| Demo video | [Public demo video](https://drive.google.com/file/d/1pCtbxVz6lWboECqmcMG6Bz_8ShGW6iFj/view?usp=sharing) |
| Architecture / presentation PDF | [Public PDF asset](https://drive.google.com/file/d/1ZPd1Oe96mEcPlWhB_8Kcii7WlnUrwtxs/view?usp=sharing) |
| License | [LICENSE](./LICENSE) |
| AI/ML framework details | [Open source and AI/ML framework details PDF](./open%20source%20and%20aiml%20frame%20work%20details.pdf) |
| Sample health report | [Sample Health Report](docs/reports/Sample-Health-Report.pdf) |
| Sample receipt | [Sample Receipt](docs/reports/Reliv-Receipt.pdf) |

## Website-derived details

The public RELiV website describes the product as a smart, autonomous preventive-health kiosk that can:

- complete a 3-minute check-up with body metrics, blood pressure, SpO₂, and temperature
- offer multilingual interaction in English, Hindi, and Bengali
- generate a digital wellness summary with a secure QR code
- provide a kiosk experience suitable for campuses, workplaces, gyms, and institutional hubs
- operate in a supervised public-health setting with free assisted screenings at the current Kolkata kiosk location

## Why RELiV?

| Accessible | Local-first | Digital | Modular |
|---|---|---|---|
| Designed for everyday locations where basic screening is convenient | Core kiosk workflows are built around local operation | Reports and receipts support digital delivery | Hardware, firmware, backend and intelligence can evolve independently |

## Product Demo

The physical machine is the clearest way to understand RELiV.

**[Watch the full RELiV machine demonstration →](https://drive.google.com/file/d/1P1BW-T57UvRlH1Z3W7Fd4589EpWNdnWm/view?usp=drive_link)**

A copy of the demo video is also available in [`assets/demo/`](assets/demo/).

> If the Google Drive video does not open, set its sharing permission to **Anyone with the link → Viewer**.

## What RELiV brings together

| Health Screening | Wellness Intelligence | Digital Reports | Essential Dispensing |
|---|---|---|---|
| BP, pulse, SpO₂, temperature and body metrics workflow | Plain-language wellness insights and summaries | QR/email-ready digital report experience | Payment-verified purchase and dispensing workflow |

### The patient journey

```text
Patient
   │
   ▼
┌──────────────────┐
│   RELiV KIOSK    │
│  Guided Touch UI │
└────────┬─────────┘
         │
    ┌────┴─────┐
    ▼          ▼
 Health Scan  Purchase
    │          │
    ▼          ▼
 Wellness    Payment
  Report    Verification
    │          │
    ▼          ▼
 QR / Digital  Dispense
 Delivery      + Receipt
```

## See the product

### Live Website

**[Open the RELiV web experience →](https://relivkiosk.vercel.app/)**

### Product Poster

![RELiV — Now Live](assets/gallery/reliv-now-live.jpeg)

## Product Gallery

The repository uses real RELiV prototype and product assets.

| Physical Prototype | Health Report | Digital Receipt |
|---|---|---|
| [View machine](assets/gallery/Machine.jpeg) | [View report](docs/reports/health-report.md) | [View receipt](docs/reports/receipt.md) |

## Health report experience

RELiV turns a screening session into a structured digital wellness report containing:

- Vital signs overview
- Body-composition metrics
- Wellness analysis and summary cards
- Progress-oriented insights
- 7-day wellness journey
- QR-based report access

**[Explore the sample health report →](docs/reports/health-report.md)**

## Payment & dispensing

The dispensing workflow is designed around verified payment before fulfillment:

```text
Select item → Online payment → Server verification
       → Signed authorization → Kiosk verification
       → Dispense + Receipt
```

The product workflow includes session binding, expiry validation, one-use authorization and replay protection.

**[Explore the product workflow →](docs/architecture/product-workflow.md)**

## Technical Architecture

RELiV follows an **offline-first kiosk + phone bridge** concept.

```text
                         RELiV KIOSK
┌──────────────────────────────────────────────────────────────┐
│                                                              │
│   Touch UI          Raspberry Pi 5           SQLite          │
│   React       ───►  Local API / Logic  ───►  Local Data     │
│                          │                                   │
│             ┌────────────┴────────────┐                      │
│             ▼                         ▼                      │
│       ESP32-S3 / Sensors        ESP32 / Dispenser           │
│       BLE • UART                MQTT / Local messaging      │
│                                                              │
└──────────────────────────┬───────────────────────────────────┘
                           │ Local Wi-Fi
                           ▼
                    CUSTOMER PHONE
                           │
                  Mobile Internet Bridge
                           │
             ┌─────────────┴─────────────┐
             ▼                           ▼
       Payment Verification        Deferred Delivery
             │                           │
             ▼                           ▼
          Razorpay                  Report / QR flow
```

### Technology Stack

| Layer | Technology |
|---|---|
| Kiosk controller | Raspberry Pi 5 (4 GB) |
| Microcontrollers | ESP32 / ESP32-S3 |
| Frontend | React |
| Backend | Node.js + Express |
| Device processing | Python |
| Database | SQLite |
| Communication | BLE · UART · MQTT |
| Payments | Razorpay verification flow |
| Deployment model | Local kiosk + web/cloud components |

**Core technologies:**

![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Raspberry Pi](https://img.shields.io/badge/Raspberry%20Pi-A22846?style=flat-square&logo=raspberrypi&logoColor=white)
![ESP32](https://img.shields.io/badge/ESP32-E7352C?style=flat-square&logo=espressif&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)

## Security & reliability

RELiV is designed with failure-aware fulfillment and local resilience in mind.

- Session-bound authorization
- Signed payment responses
- One-use authorization consumption
- Expiry validation and replay protection
- Durable local logs
- Retry-safe fulfillment
- No secrets committed to the repository
- Local operation for core kiosk functions

## Deployment-ready prototype

The RELiV prototype is **fully assembled and ready for deployment in suitable supervised environments**.

| Area | Status |
|---|---|
| Physical kiosk | Ready |
| Touch UI | Ready |
| Local backend | Ready |
| Health screening workflow | Ready |
| Digital health report | Ready |
| Inventory/admin workflow | Ready |
| Payment + dispensing flow | Ready |
| Device communication | Ready |
| Deployment | Ready |

Field-specific validation, calibration, operational monitoring, and regulatory or permission requirements can continue alongside deployment.

## Deployment opportunities

**Campuses** — routine wellness checks for students and staff.

**Workplaces** — accessible wellness stations in offices and institutions.

**Gyms & fitness spaces** — convenient measurements alongside regular fitness activity.

**Community locations** — a modular platform for broader preventive-health access.

## Recognition

**1st Runner-Up — Investopia, Bengal E-Summit 2026**

Recognized at IEM Gurukul, Kolkata, on 29–30 August 2026.

RELiV is also being developed under the **Student Innovation / Hardware** framing for Smart India Hackathon 2026.

## Documentation

| Resource | Description |
|---|---|
| [Submission Summary](docs/submission/README.md) | Public project checklist and links |
| [SIH Presentation Hub](docs/presentation/README.md) | Project presentation and context |
| [Sample Health Report](docs/reports/health-report.md) | Demonstration wellness report |
| [Sample Receipt](docs/reports/receipt.md) | Demonstration digital purchase receipt |
| [System Architecture](docs/architecture/system-architecture.md) | Architecture and data-flow notes |
| [Product Workflow](docs/architecture/product-workflow.md) | Patient and dispensing journeys |

## Repository Structure

```text
Reliv/
├── README.md
├── LICENSE
├── SECURITY.md
├── CONTRIBUTING.md
├── CHANGELOG.md
│
├── assets/
│   ├── demo/
│   ├── gallery/
│   └── screenshots/
│
├── docs/
│   ├── architecture/
│   ├── presentation/
│   ├── reports/
│   └── submission/
│
└── .github/
    └── ISSUE_TEMPLATE/
```

Application source modules can be added under their respective frontend, backend, hardware, AI, and firmware directories as the implementation is published.

## Roadmap

### Next stage

- [ ] Supervised field deployment
- [ ] Reference-device comparison and calibration documentation
- [ ] Pilot usability measurements
- [ ] Operational monitoring and maintenance workflow
- [ ] Broader institutional deployment

## Responsible Use

RELiV is a preventive-health and wellness platform. Screening outputs and generated summaries are not a substitute for professional medical diagnosis, treatment, or emergency care.

Clinical validation, calibration, applicable regulatory or permission requirements, privacy controls, safe medicine-handling procedures, and supervised operational practices should be maintained for real-world deployment.

Sample documents should use anonymized or synthetic information before public distribution.

## Contributing

Technical improvements, hardware integration work, UX feedback, testing strategies and documentation improvements are welcome.

See [CONTRIBUTING.md](CONTRIBUTING.md) for the contribution workflow.

## License

See [LICENSE](LICENSE).

---

<div align="center">

## RELiV

### Preventive healthcare, closer to everyday life.

[Explore RELiV](https://relivkiosk.vercel.app/) · [Watch the Demo](https://drive.google.com/file/d/1P1BW-T57UvRlH1Z3W7Fd4589EpWNdnWm/view?usp=drive_link) · [View Repository](https://github.com/Vaibhavcool4805/Reliv)

**You matter. RELiV cares.**

</div>
