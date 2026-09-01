# HepBVaccineTracker
Track Hep B Vaccine for ESRF with .ics &amp; pdf generator
# Hep B Vaccine Tracker — Multi-Patient

A simple, offline-friendly web tool for tracking full-dose Hepatitis B vaccine
schedules (default: 0, 1, 4, 6 months) across multiple patients at once.

## Live version

👉 [Open the tracker](https://yourusername.github.io/your-repo-name/)

## Features

- **Multi-patient tracking** — add as many patients as needed, each with their
  own Dose 1 date
- **Editable schedule intervals** — defaults to 0/1/4/6 months, adjustable for
  facilities using a different protocol
- **Status at a glance** — each dose is flagged as upcoming, due today, or
  past due
- **Google Calendar reminders** — one-click "Add to Google Calendar" per dose,
  no login or API key required
- **Bulk calendar export** — download a single `.ics` file with every
  patient's doses, importable into Google Calendar, Apple Calendar, or Outlook
- **PDF documentation log** — generate a clean, per-patient PDF report for
  facility records
- **Built-in import guide** — step-by-step instructions for adding the `.ics`
  file to common calendar apps

## How it works

1. Set the reminder time and schedule intervals (or leave the 0/1/4/6-month
   default).
2. Add each patient's name and Dose 1 date.
3. Click **Generate schedules** to see every patient's dose dates and
   statuses.
4. Add individual doses to Google Calendar, download all doses as an `.ics`
   file, or export a PDF log for documentation.

## Disclaimer

This tool is a scheduling and documentation aid only. It is **not** a
substitute for clinical judgment or your facility's approved immunization
protocol. Always confirm dosing intervals — especially for patients on
hemodialysis or who are immunocompromised, who may follow different
formulations or schedules — with a clinician.

## License

MIT — see [LICENSE](LICENSE) for details. Contributions and forks welcome.
