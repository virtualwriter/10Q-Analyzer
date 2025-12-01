# 📊 10-K/10-Q SEC Filing Analyzer

A browser-based tool to analyze and compare SEC 10-K and 10-Q financial filings side-by-side.

## 🚀 Live Demo

[https://10q-analyzer.vercel.app](https://10q-analyzer.vercel.app)

## Features

- **Direct SEC EDGAR Integration** - Paste URLs from SEC EDGAR and analyze HTML filings directly
- **File Upload Support** - Upload downloaded HTML files for offline analysis
- **Side-by-Side Comparison** - Compare up to 3 companies at once
- **Comprehensive Metrics**:
  - Income Statement (Revenue, Net Income, Operating Income, Margins)
  - Balance Sheet (Assets, Liabilities, Equity, Cash Position)
  - Cash Flow (Operating, Investing, Financing, Free Cash Flow)
  - Key Ratios (Current Ratio, Debt-to-Assets, Net Cash)
- **Red Flag Detection** - Automatically identifies financial concerns
- **Export Options** - Download as Markdown, JSON, or CSV

## Usage

### Option 1: URL-Based Analysis (index.html)
1. Go to [SEC EDGAR](https://www.sec.gov/edgar/searchedgar/companysearch.html)
2. Search for a company and find their 10-Q filing
3. Copy the URL of the HTML filing (e.g., `https://www.sec.gov/Archives/edgar/data/1652044/000165204424000091/goog-20240930.htm`)
4. Paste 3 URLs into the analyzer
5. Click "Fetch & Analyze"

### Option 2: File Upload (10q_analyzer.html)
1. Download HTML files from SEC EDGAR
2. Upload 3 files to compare
3. Click "Analyze & Compare"

## Tech Stack

- Pure HTML/CSS/JavaScript
- No backend required
- CORS proxy for SEC EDGAR access
- Runs entirely in your browser

## Local Development

Simply open `index.html` in your browser - no build step required!

```bash
# Clone the repo
git clone https://github.com/YOUR_USERNAME/10Q-Analyzer.git

# Open in browser
open index.html
```

## Deployment

This is a static site that can be deployed to any hosting platform:

- **Vercel**: Just connect your GitHub repo
- **Netlify**: Drag and drop the folder
- **GitHub Pages**: Enable in repo settings

## License

MIT

