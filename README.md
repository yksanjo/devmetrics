# DevMetrics - Developer Analytics Dashboard

<p align="center">
  <img src="https://img.shields.io/badge/Python-FastAPI-00d4aa?style=for-the-badge&logo=python" alt="Python">
  <img src="https://img.shields.io/badge/Analytics-Dashboard-7c3aed?style=for-the-badge&logo=chartjs" alt="Analytics">
</p>

Developer analytics dashboard with GitHub activity tracking, productivity metrics, and team insights.

## 🌟 Features

- **GitHub Activity Tracking** - Monitor commits, PRs, issues
- **Productivity Metrics** - Code velocity, review time, deployment frequency
- **Team Insights** - Compare team member contributions
- **Goal Tracking** - Set and track development goals
- **Custom Dashboards** - Build your own metric views
- **Export Reports** - PDF/CSV exports for stakeholders

## 🚀 Quick Start

```bash
cd backend
pip install -r requirements.txt
python -m uvicorn app.main:app --reload

cd ../frontend
python -m http.server 8080
```

## 🔌 API Endpoints

- `GET /api/metrics` - Get developer metrics
- `GET /api/activity` - Get activity timeline
- `POST /api/goals` - Set development goals

---

Built with ⚡ for data-driven development teams
