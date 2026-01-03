# Local Marine Spatial Planning (LMSP) - Tanzania

[![GitHub Repository](https://img.shields.io/badge/GitHub-lugoga%2Flmsp-blue)](https://github.com/lugoga/lmsp)
[![Quarto](https://img.shields.io/badge/Built%20with-Quarto-brightgreen)](https://quarto.org)
[![Website](https://img.shields.io/badge/Website-Live-success)](https://lugoga.github.io/lmsp/)

## Overview

**Local Marine Spatial Planning (LMSP): Enhancing community stewardship in spatial planning**

This is the official repository for the LMSP-Tanzania website and initiative hub. We are an Ad Hoc Group of Experts dedicated to promoting evidence-based, community-centered marine spatial planning across Tanzania and the Western Indian Ocean region.

## Mission

To be the leading source and advocate for Local Marine Spatial Planning in Tanzania, strengthening community stewardship and sustainable ocean governance across the WIO region.

## Key Objectives

- **🌍 Raise Awareness & Visibility** - Increase awareness of local Marine Spatial Planning initiatives in Tanzania and showcase successful approaches
- **👥 Increase Team Visibility** - Highlight the expertise, research, and fieldwork of our team members working on MSP
- **🤝 Mobilize Support** - Draw partnerships and assignments from development partners interested in supporting LMSP efforts
- **📊 Share Knowledge & Data** - Be the key source for data, information, and best practices on MSP in Tanzania and the WIO region

## Website Structure

```
lmsp/
├── index.qmd              # Homepage
├── about.qmd              # About LMSP
├── blog.qmd               # Blog posts
├── contacts.qmd           # Contact information
├── team.qmd               # Team members
├── partners.qmd           # Partner organizations
├── faq.qmd                # Frequently Asked Questions
├── _quarto.yml            # Quarto configuration
├── admin/                 # Administrative pages
│   ├── data.qmd
│   ├── deliverables.qmd
│   ├── scope.qmd
│   ├── timeline.qmd
│   └── team.qmd
├── posts/                 # Blog posts and analyses
│   ├── finding_unique_land_cover_patterns/
│   ├── lulc_change/
│   ├── lulc_pattern/
│   └── ...
├── images/                # Logos, graphics, team photos
├── styles.css             # Custom styling
└── docs/                  # Rendered HTML output
```

## Key Pages

| Page | Description |
|------|-------------|
| **Home** | Overview of LMSP initiatives and objectives |
| **About** | Detailed information about the LMSP initiative |
| **LMSP Initiatives** | Ongoing, Planned, and Completed projects |
| **Blog** | Articles, case studies, and research insights |
| **Team** | Meet the team members and their expertise |
| **Partners** | Network of partner organizations |
| **FAQs** | Frequently asked questions |
| **Resources** | Implementation guides, publications, and tools |
| **Admin** | Administrative dashboard and project management |

## Featured Tools & Dashboards

The website provides quick access to interactive tools and dashboards:

- **BESA Dashboard** - https://semba.shinyapps.io/besa/
- **Digital Tool** - https://semba.shinyapps.io/digital/
- **Vizinga Dashboard** - https://semba.shinyapps.io/vizingaApp/

Access the QR code in the website footer for quick mobile access.

## Technology Stack

- **Framework**: [Quarto](https://quarto.org) - An open-source scientific publishing system
- **Language**: Markdown + HTML/CSS
- **Deployment**: GitHub Pages
- **Interactive Elements**: Leaflet (maps), ECharts (visualizations)
- **Styling**: Bootstrap + Custom CSS

## Getting Started

### Prerequisites
- Quarto (v1.3+)
- Git
- A text editor or IDE

### Installation & Local Development

1. **Clone the repository**
   ```bash
   git clone https://github.com/lugoga/lmsp.git
   cd lmsp
   ```

2. **Preview the website locally**
   ```bash
   quarto preview
   ```
   The website will be available at `http://localhost:3000`

3. **Build the website**
   ```bash
   quarto render
   ```
   This generates the static HTML files in the `docs/` directory.

## Contributing

We welcome contributions! To contribute:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/your-feature`)
3. Make your changes
4. Commit your changes (`git commit -m 'Add your feature'`)
5. Push to the branch (`git push origin feature/your-feature`)
6. Open a Pull Request

### Contribution Guidelines

- Follow the existing content structure and formatting
- Use clear, descriptive commit messages
- Include relevant documentation for new features
- Test changes locally before submitting

## Content Management

### Adding Blog Posts

Blog posts are located in the `posts/` directory. Each post should have its own folder:

```
posts/
├── your_post_name/
│   ├── index.qmd          # Post content
│   └── images/            # Post-specific images
```

### Updating Team Information

Team information can be updated in `team.qmd`. Follow the existing structure for consistency.

### Adding Partners

Update the partner list in `partners.qmd` with relevant partner information and logos.

## Website Features

- **Responsive Design** - Mobile-friendly layout using Bootstrap
- **Interactive Maps** - Location maps using Leaflet
- **Data Visualizations** - Charts and graphs with ECharts4r
- **Search Functionality** - Built-in search across all pages
- **Sidebar Navigation** - Easy access to key sections
- **Social Media Integration** - Links to GitHub, LinkedIn, YouTube
- **Contact Forms** - Interactive contact forms for inquiries

## Data Resources

The website includes shared data resources located in `data_shared/`:
- CSV files for datasets
- Spatial data files
- Reference materials

## Deployment

The website is automatically deployed to GitHub Pages when changes are pushed to the `main` branch. The compiled website is served from the `docs/` directory.

**Live Website**: https://lugoga.github.io/lmsp/

## Contact & Support

**Email**: [lugosemba@gmail.com](mailto:lugosemba@gmail.com)

**Location**: Kinondoni District, Dar es Salaam, Tanzania

**Office Hours**: Monday - Friday: 8:00 AM - 5:00 PM EAT

### Department Contacts

- **Marine Spatial Planning & Strategy**: Julius Francis
- **Data & Information**: Masumbuko Semba
- **Policy & Governance**: Siajali Pamba
- **Community Engagement**: Emmanuel Mpina
- **Research & Analysis**: Rushingisha George
- **Communications & Media**: John Komakoma

## Partners

The LMSP initiative is supported by:
- Government of Tanzania
- University of Dar es Salaam (UDSM)
- Nelson Mandela African Institution of Science and Technology (NM-AIST)
- The Nature Conservancy (TNC)
- Regional organizations

## License

© 2026 LMSP-Tanzania | Ad Hoc Group of Experts on Marine Spatial Planning

## Acknowledgments

This website represents the collaborative efforts of the LMSP team, partners, and contributors dedicated to advancing marine spatial planning in Tanzania and the Western Indian Ocean region.

## Additional Resources

- [Implementation Guide](./lmplementation_guide.qmd)
- [Publications](./pubs.qmd)
- [Case Studies](./case_studies.qmd)
- [Guidelines](./guidelines.qmd)

---

**Last Updated**: January 2026

For more information, visit our [website](https://lugoga.github.io/lmsp/) or contact us through the [Contact Form](./contacts.qmd).
