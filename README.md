# FORTHEPEOPLE

FORTHEPEOPLE is a static web portal that helps people discover Indian government
schemes, understand eligibility and benefits, and find application guidance.
Information is grouped into areas such as agriculture, healthcare, housing,
employment, pensions, financial services, and social welfare.

## Run locally

No build step or package installation is required. Clone the repository and
serve it with any static web server:

```bash
git clone https://github.com/suryasekhar18/Elderly-Government-Scheme-Eligibility-Information-Portal.git
cd Elderly-Government-Scheme-Eligibility-Information-Portal
python -m http.server 8000
```

Open [http://localhost:8000/finalproject/images/front.html](http://localhost:8000/finalproject/images/front.html)
in a browser. Opening the HTML file directly also works, but a local server
avoids browser restrictions when loading external resources.

## Project layout

- `finalproject/images/front.html` - portal homepage
- `finalproject/images/*.html` - scheme categories, help, authentication, and legal pages
- `finalproject/images/*.css` - page styling
- `finalproject/images/*.js` - search and navigation interactions
- `finalproject/images/logos/` and image files - site artwork and scheme assets

This is a client-side project built with HTML5, CSS3, and vanilla JavaScript.
It uses Google Fonts, Font Awesome, Phosphor Icons, and Google Translate from
their hosted services.

## Important

The portal is for information and navigation only. Always confirm current
eligibility rules, deadlines, and application requirements on the relevant
official government website before applying.

For the fuller feature and scheme overview, see
[`finalproject/README.md`](finalproject/README.md).
