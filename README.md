# Paperline — CV, Resume & Cover Letter Builder

A professional CV and cover letter builder in **one HTML file**. No server, no sign-up. Your data stays in your browser.

## Features

### Templates
There are 8 templates:
- **Professional**
- **Modern**
- **Corporate**
- **Infographic**
- **Classic**
- **Elegant**
- **Minimal**
- **Executive**

### Design options
- 11 colors, plus a custom color.
- 7 fonts and 3 text sizes.
- A4 or US Letter paper.
- Styles for skills: grey tags, color tags, level bars, level dots, a two-column list, or a comma list.
- Styles for languages: proficiency text, one per line, level dots, level bars, rings, or a comma list.

### Photo
Upload a photo or drag one in. Choose a circle, rounded or square shape.

### Personal details
Name, job title, email, phone and location. Optional extras:
- Website
- LinkedIn
- Visa status
- Driving license
- Date of birth
- Nationality

### Sections
- Profile
- Work experience, with an optional line about the employer and a reference contact
- Education, with grade, key courses and thesis
- Projects
- Organizations
- Training & courses
- Certificates
- Achievements
- Volunteering
- Publications
- References
- Additional information (a custom section)
- Declaration
- Skills
- Languages
- Interests

You can switch any section on or off, rename it, and reorder it. You can also move sections between the left and right columns.

### Cover letter
The cover letter uses the same design as your CV, so the two match.

### Auto-save and saved CVs
- Every change saves automatically in your browser. The top bar shows "Saved" with the time.
- Turn auto-save off in the Menu if you want to save manually. Then save with the Save button or **Ctrl+S**.
- **My saved CVs** keeps several versions. You can open, rename, duplicate and delete them.
- Save a backup file (.json) to move your CVs to another device.

### Export
- **Download PDF**: an exact copy of the preview.
- **Download Word (.docx)**: editable in Microsoft Word and Google Docs.
- **Print or Save as PDF**: text stays selectable, which is best for online job portals.
- **Print-ready HTML**: one web page file you can print anywhere.

### Optional AI help
Uses Claude with your own Anthropic API key:
- Improve your summary.
- Write achievement bullets.
- Write or polish a cover letter.
- Get a recruiter-style review of your CV.

## Publish on GitHub Pages

1. Create a repository and upload `index.html` and `README.md`.
2. Go to **Settings → Pages**.
3. Choose **Deploy from a branch**, then `main` and `/ (root)`, and click **Save**.
4. After about a minute, your site is at `https://<username>.github.io/<repo>/`.

> ⚠️ **Do not upload personal backup files (.json) to a public repository.** They contain your phone number, email and photo. Keep them on your own computer and open them from **Menu → Open backup file**.

## Notes

- PDF and Word export load small libraries from jsdelivr the first time you use them, so you need an internet connection.
- The Word file uses a clean single-column layout. This is the safest format for applicant tracking systems (ATS).

## License

MIT
