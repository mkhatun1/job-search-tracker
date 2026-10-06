# Job Search Tracker

A lightweight, privacy-friendly web app that helps you run a focused job search: track every application in one place and turn any job description into ready-to-use AI prompts for tailoring your materials.

**Live demo:** https://mkhatun1.github.io/job-search-tracker/

> Built with AI coding assistance as a practical project to streamline my own job search.

## Why I built it

Job searching involves repetitive work: logging applications, remembering follow-ups, and rewriting resumes and cover letters for each role. This tool organizes the pipeline and standardizes the AI prompts so tailoring each application takes minutes instead of an hour.

It deliberately does **not** auto-apply to jobs. Mass auto-apply produces generic applications, so this tool keeps a human in the loop for the final review and submission.

## Features

### Application tracker
- Log each job with company, role, and link
- Move jobs through **Saved → Applied → Interview → Offer → Rejected**
- Automatic follow-up date set 7 days after you mark a job as Applied, with an "overdue" flag
- Dashboard counts per stage and a daily application goal counter

### Prompt kit
- Save your resume or background once (stored locally)
- Paste any job description and generate a structured prompt for:
  - Match analysis (strengths, gaps, keywords, fit score)
  - Tailored resume bullets
  - Cover letter
  - Recruiter outreach message
  - Interview preparation
  - Follow-up email
- One-click copy, then paste into your AI assistant of choice

## How to use

1. Open `index.html` in a browser, or visit the live demo.
2. Paste your resume into the **Prompt Kit** tab (one-time).
3. Add jobs you find on LinkedIn, Indeed, or company career pages to the **Tracker**.
4. For each job, paste the description, choose a task, and copy the generated prompt into your AI assistant.
5. Review and edit the output so it is accurate and sounds like you, then apply.
6. Update the job's status as it progresses and act on follow-up reminders.

## Privacy

Everything runs in your browser. Your resume and job data are stored in your browser's local storage and are never sent to a server. Clearing your browser data will erase them.

## Tech

- Single-file app: HTML, CSS, and vanilla JavaScript
- No dependencies, no build step, no backend
- Light and dark theme support
- Responsive layout for desktop and mobile

## Limitations

- Data is stored per browser and device, with no sync or export yet
- Jobs are entered manually, with no job-board integration
- Prompts are generated for you to paste into an AI tool; the app does not call an AI service itself

## Roadmap

- [ ] Export and import data (CSV or JSON)
- [ ] Notes and contact fields per job
- [ ] Saved search links for common job boards
- [ ] Weekly stats on application-to-interview rate

## Run locally

```bash
git clone https://github.com/mkhatun1/job-search-tracker.git
cd job-search-tracker
# open index.html in your browser
```

## Author

**Mahfuza Khatun**: Solutions Engineer (IoT, cloud, and LPWAN)
[LinkedIn](https://www.linkedin.com/in/mahfuza-khatun/) · [GitHub](https://github.com/mkhatun1)

## License

MIT
