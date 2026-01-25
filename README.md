# SCALE AI Maturity Assessment Tool

A comprehensive, interactive assessment tool that helps organizations evaluate their AI transformation readiness using the proven **SCALE framework** for GTM (Go-To-Market) AI implementation.

![SCALE Framework](https://img.shields.io/badge/Framework-SCALE-blue)
![License](https://img.shields.io/badge/License-MIT-green)
![Deployment](https://img.shields.io/badge/Deploy-Vercel-black)

## What is SCALE?

**S.C.A.L.E.** is a systematic framework for enterprise AI implementation:

| Letter | Dimension | Focus |
|--------|-----------|-------|
| **S** | Strategic Outcomes | Define measurable business goals AI will achieve |
| **C** | Chart Friction & Foundations | Map workflow bottlenecks and assess data readiness |
| **A** | Align Capabilities & Readiness | Match AI solutions to problems and ensure organizational readiness |
| **L** | Launch with Control | Execute structured pilots with clear metrics and feedback loops |
| **E** | Evolve & Expand | Scale what works with governance and continuous measurement |

## Key Statistics

- **73%** of AI initiatives fail to scale beyond pilot stage
- **4.3x** higher success rate with structured frameworks like SCALE
- **$4.4+ trillion** projected global value from Gen AI (McKinsey)

## Features

- **25 Assessment Questions** across 5 dimensions (5 per dimension)
- **5-Level Maturity Scoring** from Experimenting to Scaling
- **Interactive UI** with real-time progress tracking
- **Personalized Recommendations** based on your scores
- **30-Day Action Plan** prioritized by your weakest areas
- **Print/Download Report** functionality
- **Mobile Responsive** design
- **No Backend Required** - runs entirely in the browser

## Maturity Levels

| Level | Name | Description |
|-------|------|-------------|
| 1 | **Experimenting** | Ad-hoc AI exploration without strategic direction |
| 2 | **Exploring** | Beginning to identify AI opportunities with emerging structure |
| 3 | **Establishing** | Structured approach emerging with defined processes |
| 4 | **Executing** | Systematic implementation with measurable outcomes |
| 5 | **Scaling** | Enterprise-wide AI integration with continuous improvement |

## Quick Start

### Option 1: Open Locally
Simply open `index.html` in any modern web browser.

### Option 2: Deploy to Vercel
1. Fork this repository
2. Connect to Vercel
3. Deploy automatically

### Option 3: Deploy to GitHub Pages
1. Go to repository Settings
2. Navigate to Pages
3. Select "Deploy from a branch" → main → / (root)
4. Your site will be live at `https://[username].github.io/scale-ai-assessment`

## Project Structure

```
scale-ai-assessment/
├── index.html      # Complete assessment tool (self-contained)
├── README.md       # This file
├── LICENSE         # MIT License
└── CONTRIBUTING.md # Contribution guidelines
```

## Technology

This is a single-page application built with:
- **HTML5** - Semantic markup
- **CSS3** - Custom properties, Flexbox, Grid, animations
- **Vanilla JavaScript** - No frameworks or dependencies
- **Google Fonts** - Inter font family

## Customization

The assessment can be customized by modifying the `assessmentData` object in `index.html`:

- **Questions**: Edit the `questions` array in each dimension
- **Scoring**: Modify the `getMaturityLevel()` function
- **Recommendations**: Update the `getRecommendations()` function
- **Styling**: Adjust CSS custom properties in `:root`

## Based On

This tool is based on the **SCALE AI Transformation Framework** developed for GTM AI implementation, which emphasizes:

> "Don't deploy AI. S.C.A.L.E. it. Business outcomes first, technology second."

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contributing

Contributions are welcome! Please read [CONTRIBUTING.md](CONTRIBUTING.md) for details on how to submit pull requests.

## Acknowledgments

- SCALE Framework methodology
- GTM AI Academy concepts
- Industry research from McKinsey, Gartner, and others

---

**Ready to assess your AI maturity?** [Try the live demo →](https://scale-ai-assessment.vercel.app)
