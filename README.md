# Horizon Releases

**Horizon** – Your Databricks Consumption Planning Tool

This repository contains release builds of Horizon. The source code is maintained in a private repository.

## Installation

### Option 1: Direct Download

Download the latest wheel from the [Releases page](https://github.com/hourdays/horizon-releases/releases).

### Option 2: pip install from GitHub

```bash
# Install latest release
pip install https://github.com/hourdays/horizon-releases/releases/latest/download/horizon-py3-none-any.whl

# Install specific version
pip install https://github.com/hourdays/horizon-releases/releases/download/v1.5.1/horizon-1.5.1-py3-none-any.whl
```

### Option 3: Databricks Apps

1. Download the wheel file
2. Upload to your Databricks workspace
3. Create a `requirements.txt` pointing to the wheel:
   ```
   horizon-1.5.1-py3-none-any.whl
   ```
4. Deploy using Databricks Apps

## Requirements

- Python 3.10+
- Databricks workspace with Unity Catalog (or use Manual Baseline mode)
- SQL Warehouse for data queries

## Versions

| Version | Date | Notes |
|---------|------|-------|
| v1.5.1 | 2025-12-10 | Mobile UX: expandable cards, toggle checkbox |
| v1.5.0 | 2025-12-10 | Manual baseline, CSV export/import, mobile responsive |
| v1.4.0 | 2025-12-04 | Multi-account, sidebar navigation |
| v1.3.4 | 2025-12-03 | Multi-user support, delete use cases |

## Features

- 📊 **Consumption Dashboard** - Track DBU usage with KPIs and trends
- 📈 **Use Case Planning** - Project future consumption with onboarding patterns
- 📱 **Mobile Responsive** - Fully functional on mobile devices
- 💾 **CSV Export/Import** - Backup and restore use cases
- ➖ **Negative DBU** - Model optimizations and cost reductions
- 🔐 **Multi-User** - Per-user and per-account isolation

## Links

- **Author:** [Hugues Journeau](https://www.linkedin.com/in/hourdays/)
- **App URL:** [horizon.databricksapps.com](https://horizon-416411475796958.gcp.databricksapps.com)

## License

Proprietary - Contact author for licensing information.
