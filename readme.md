# 📄 Automated Job Application Bot (UiPath)

This project automates job applications using UiPath. Given a candidate's CV and a list of job offers in CSV format (with contact emails), the bot applies to matching offers automatically by generating and sending tailored emails.

## 🚀 Features

* ✅ Reads a CV and job offers from CSV
* ✅ Automatically generates and sends job application emails
* ✅ Tracks status (e.g., "sent", "failed") and logs to CSV
* ✅ 🔍 \[Planned] Web scraping workflow to collect fresh offers
* ✅ 📈 \[Planned] Monitoring system to track success/failure

## 📁 Project Structure

```
.
├── ApplyToOffers.xaml         # Main workflow (application logic)
├── ScrapeOffers.xaml          # (WIP) Web scraping of new offers
├── MonitorApplications.xaml   # (WIP) Monitoring/reporting logic
├── Input/
│   ├── cv.pdf                 # Candidate CV
│   └── job_offers.csv         # Offers (with at least email)
├── Output/
│   └── results.csv         # Application results log
└── README.md
```

## ⚙️ Requirements

* UiPath Studio (tested with version X.X.X)
* Outlook or SMTP configured
* CSV files formatted with expected fields (E-mail, SOCIETE, )

## 📌 Usage

1. Open `SequencePourPostuler.xaml` in UiPath
2. Place the candidate's CV in the `Input/` folder
3. Add or update `job_offers.csv` with new offers
4. Run the bot — it will:

   * Match and apply automatically
   * Log the results to `Output/results.csv`

## 🔠 Planned Additions

* 🔍 `ScrapeOffers.xaml`: Collect new offers from job boards
* 📈 `MonitorApplications.xaml`: Track performance, visualize stats

## 💡 Demo

*(You can add a link to your video or screenshots here)*

## 📬 Contact

For questions or contributions, feel free to reach out.
