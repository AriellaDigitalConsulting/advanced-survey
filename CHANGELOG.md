# Changelog

## 0.5.0 (next)

### Features

- New “Survey Answered” options:
  - Collective Recap: view all participants’ answers
  - Personal Recap: view only your own answers
  - Thank You: show a customizable thank-you message
- In Collective Recap, include all submitted free-text answers
- Detailed export improvements

### No longer broken

- Automatic Google Drive export for Google users

## 0.4.0 (September 4th)

## Features

- Save the survey settings to our service (enabled by default)
  - Disable this if you do not want to send data to our own server
  - Disabling this feature implies that Surveys removed from a Space or a Community will not anymore be exportable
- Webhooks
  - Events (answer submitted) can be sent to a third party platform (such as Zapier)
- Debounced text fields
  - Improving the user experience when typing the title of a question, of a survey or a question choice label
- Full screen analytics
  - We've seen our widget on very small surfaces; instead of miniaturizing the survey analytics, let's use the entire screen to display them!
- Detailed Export: include the value of the choice selected by the user (choices questions)

## 0.3.0 (August 6th)

### Features

- Export the CSVs to Google Spreadsheets (for Google Users)
- More details in the detailed export (user first, last, question title)

## 0.2.0 (July 31st)

### Features

- option to ask one question at a time
- trivia questions
- include spaces and communities informations in the governance dashboard

## 0.1.2 (review asked on July 11th)

### Bugfixes

- improve the container ID detection on a community

## 0.1.1 (review asked on July 9th, published on July 11th)

### Bugfixes

- we are not considering anymore the aggregate answers to determine whether or not the user has answered the poll

## 0.1.0 (review asked on July 7th, published on July 9th)

### Features

- rework the pie/bar charts

### Bugfixes

- clarify labels
- fallback to English for survey questions labels (instead of displaying "Choice text missing")
- All Surveys: sort by number of answers

## 0.0.3 (June 24th, 2025)

## Features

- partial spaces and communities support

## Bugfixes

- deselect the current feed in the Survey Moderators
- licensing: use the right widget ID

## 0.0.2 (June 20th, 2025)

## Features

- Export to PDFs.

## 0.0.1 (June 11th, 2025)

The initial Survey Widget release including

- Multiple questions
- Expiration Date
- Display/hide results - and define a custom "Thank you message"
- Survey Moderators: define a group of users (not lumapps administrators) who will be allowed to check the survey analytics
- Export analytics (summary, to HTML, CSV and PDF; detailed: CSV).
- Import/Export Questions (for rapid prototyping)
- Governance: a centralized Dashboard where to find all the surveys
