# Resources Hub

Resources Hub is a single-page web app that replaces the paper compliance trail for a truck fleet. Drivers log on with a number and PIN to do their daily declaration, prestart, hazard and fault reports from a phone. Office staff manage allocations (with WhatsApp dispatch), fleet details, service sheets, HSEQ forms and registers, and service scheduling with overdue and due-soon flags. A Compliance tab builds a per-vehicle audit zip for the NHVR. The servicing mechanic has their own login for fault reports, service sheets and scheduling.

Next steps are a hosted backend with real logins and Australian data residency, Geotab telematics, and automatic WhatsApp dispatch.

## What's here

- `index.html`: the whole app in one file. Open it in a browser, no build step.
- `docs/`: HSEQ policies and procedures, linked from the HSEQ page.
- `forms/`: the blank paper Form 20 Service Scheduling Register.

## This is a public copy

People's surnames in this copy are replaced with a letter and "Doe" (for example "Steven S Doe"), so the records read realistically without identifying anyone. The working hub keeps the real names.

Not in this repo, because they hold personal or financial details: service invoices (`invoices/`), scanned service sheets (`scans/`), the HSEQ register exports (RNSWF series, including Induction and NCR) and the Compliance Manual (RNSWM001). They stay in the hub's own file store, so links to them won't open from a copy of this repo.

## Data and logins

Until the backend exists, everything people enter is saved in the browser of the device they use (localStorage, plus IndexedDB for uploaded files). Logins are prototype accounts only. Ask the office for test logins.
