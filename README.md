# Lee-Bella's No Place Like Home CDC — Website Files
## How to Upload to GitHub Pages

Your website is made up of these files — keep them ALL in the same folder:

| File | Page |
|------|------|
| index.html | Home page |
| about.html | About Tanika & the Center |
| services.html | Services & Pricing |
| contact.html | Contact page |
| interest.html | Family Interest Form |
| support.html | GoFundMe / Support Us |
| logo.png | Your logo (used on every page) |

---

## How to Upload to Your GitHub Site (pynkshouse.github.io)

1. Go to https://github.com and sign in
2. Open your repository: **pynkshouse/lee-bellas-NPLH**
3. For EACH file above, click **"Add file" → "Upload files"**
4. Drag and drop all the files at once
5. Scroll down and click **"Commit changes"**
6. Your site will update at: https://pynkshouse.github.io/lee-bellas-NPLH/

> ⚠️ Make sure `logo.png` is uploaded — every page needs it!

---

## Making the Interest Form Actually Send Emails (Optional)

Right now the interest form shows a "thank you" message but doesn't email you.
To receive emails from the form, sign up FREE at **https://formspree.io**:

1. Create a free account using your LeeBellas-NPLH@outlook.com
2. Create a new form — Formspree will give you a form endpoint URL like:
   `https://formspree.io/f/xxxxxxxx`
3. Open `interest.html` and find the `submitForm()` function
4. Replace the comment with a fetch call to your Formspree endpoint

Or simply direct people to email you at LeeBellas-NPLH@outlook.com for now!

---

## Colors Used (from your logo)
- Sage Green: #7A9E7E
- Dusty Blue: #7BA7BC
- Blush Pink: #E8A0B4
- Sunshine Yellow: #F5C842
- Cream: #FDF8F3
