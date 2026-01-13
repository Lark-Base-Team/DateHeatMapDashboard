# Date HeatMap Dashboard (日期热力图插件)

A dashboard component for visualizing date-based data density using a heatmap, designed for Lark/Feishu Bitable (Base).

## Tech Stack

- **Framework**: React 18
- **Build Tool**: Vite
- **UI Component Library**: [Semi UI](https://semi.design/)
- **SDK**: @lark-base-open/js-sdk (Lark Base Open JS SDK)
- **Language**: TypeScript
- **Styling**: SCSS / CSS
- **Internationalization**: i18next

## Features

- Visualize data records frequency over time (Daily/Monthly/Yearly).
- Customizable heat map colors and ranges.
- Drag and drop configuration for color ranges.
- Integrated with Lark/Feishu Bitable data sources.

## Project Structure

```
src/
  components/
    Dashboard/       # Main container and logic
    DashboardConfig/ # Configuration panel implementation
    DashboardView/   # The heatmap visualization view
    BaseSelector/    # Component for selecting Base/Table
  hooks.ts           # Custom hooks (useTheme, useConfig)
  locales/           # i18n resources
```

## Getting Started

### Prerequisites

- Node.js (v16+)
- npm or pnpm

### Installation

```bash
npm install
# or
pnpm install
```

### Development

```bash
npm run dev
```

### Build

```bash
npm run build
```

## Troubleshooting

- If you encounter build errors related to SASS, ensure your environment supports the latest SASS version.
- For `TypeError: Cannot read properties of undefined` in Config, ensure your configuration object matches the expected schema. (Fixed in latest update).
