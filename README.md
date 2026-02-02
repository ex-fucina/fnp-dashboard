# FNP Fundraising Dashboard

Public dashboard for tracking Fucina Nexus Foundation fundraising outreach.

**Live:** [fnp-dashboard.netlify.app](https://fnp-dashboard.netlify.app) *(after Netlify setup)*

## About

This dashboard displays the current status of foundation grant applications and outreach efforts. It's a static HTML file that gets updated manually from the main tracking system in `fnp-ops` (private repo).

## Updating

When the tracker changes:

```bash
# From fnp-ops repo
cp docs/fundraising/dashboard.html ../fnp-dashboard/index.html
cd ../fnp-dashboard
git add . && git commit -m "Update dashboard" && git push
```

Or run the sync script (if available).

## Structure

```
fnp-dashboard/
├── index.html    # The dashboard
└── README.md     # This file
```

## Links

- [Fucina Nexus Foundation](https://fucinanexus.foundation)
- [GitHub Organization](https://github.com/ex-fucina)

---

*Maintained by Copernico + DD*
