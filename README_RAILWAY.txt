README — Railway (Fixed, English Alerts)

1) Upload this repo to GitHub.
2) In Railway → New Project → Deploy from GitHub.
3) Once deployed:
   - Go to 'Schedules' → Add Schedule
   - Command: python scan_bot.py
   - Cron: 0 * * * * (every hour)
   - Enabled: ON
4) Check Deployments → Logs and Telegram for messages.
