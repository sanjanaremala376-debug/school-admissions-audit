# Admissions Website Audit: 21 International and Boarding Schools

A manual audit of how clearly 21 school websites in India present admissions information, with an Excel workbook (formulas, dashboard) and a written report. Completed in June 2026 as a case assignment for an internship application. It is a portfolio exercise, not work for a real client.

## What is in this repository
- `School_Admissions_Audit.xlsx`: the dataset and analysis. Sheets: README, Dashboard, Summary, Pivot, Data, Issue Log, Case Studies. The Data sheet keeps the full audit notes for every school. Counts use COUNTIFS formulas, the Pivot sheet is a PivotTable of guide tier against fee disclosure, inputs use data validation, and the Dashboard has charts.
- `Admissions_Audit_Report.pdf`: the written report, with six ranked recommendations.

## Method
- Schools were found through a Google search and each website was reviewed by hand.
- Each site was recorded on six checks: fee structure, admission guide (rated 1 to 5 stars, where 5 is a clear guide that is easy to follow), deadlines, enquiry form, phone number and WhatsApp support, with notes on operational gaps and points of confusion.
- A simple 0 to 6 tally adds one point for each of: full fees, a clear guide (4 or 5 stars), deadlines, enquiry form, phone number and WhatsApp.
- Two schools could not be fully assessed (one unreachable, one with admissions closed), so findings use n = 19.
- The Case Studies sheet maps the route to the enquiry form at two schools.

## Findings
- **No school shows both full fees and admission deadlines.** The 9 schools with full fees all omit deadlines, and the 3 that state deadlines all hide fees. Another 7 show neither.
- **Fees:** 9 show them in full, 1 partly and 9 not at all.
- **Contact options exist at most schools but are often hard to use:** 15 of 19 have an enquiry form and 15 of 19 a phone number, but only 6 offer WhatsApp. At 6 schools the form is missing or hard to find, and at 6 the contact channel has a gap or friction.
- **A clear guide does not mean transparent fees:** of the 9 schools rated 4 or 5 stars for their guide, only 3 show fees in full, and both 5-star schools hide them. All 6 three-star schools show fees.
- **Most schools have only some of the basics:** the average tally is 3 of 6, 12 of 19 score three or fewer, and the highest is 5.
- **The audit notes also record friction in how information is presented:** six themes each appear at 6 or 7 schools, led by missing or non-admission FAQs and missing or buried eligibility criteria (7 each). The others are a vague process, a hidden or missing enquiry form, contact-channel gaps and confusing navigation (6 each).
- Six ranked recommendations are in the report, for example publishing deadlines and adding admission-specific FAQs.

## Limitations
- One reviewer and a snapshot taken in June 2026; websites change.
- The ratings and the grouping of notes into friction themes are judgement calls.
- Small sample chosen from a Google search, so it describes these 21 websites, not schools in general.
