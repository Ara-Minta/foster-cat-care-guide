# Foster Cat Care Guide

A mobile-friendly web app that helps foster caregivers find care information for infants, kittens, adult cats, and nursing mothers. It includes a symptom checker, a feeding calculator, a weight tracker, a stool chart, an age estimator, and a vaccine and deworming planner.

**This is a test version.** The content is general guidance and has not yet been reviewed by a veterinarian. It does not replace a vet or your foster organization's protocols.

## Put it online with GitHub Pages

1. Create a new public repository on GitHub, for example `foster-cat-care-guide`.
2. Upload every file and folder in this package, including the `.github` folder, to the repository.
3. Go to **Settings → Pages**.
4. Under **Build and deployment**, set **Source** to **Deploy from a branch**, choose the **main** branch and the **/(root)** folder, then select **Save**.
5. After a minute or two, the site will be live at `https://YOUR-USERNAME.github.io/foster-cat-care-guide/`.

Share that link with your testers.

## Turn on the feedback link (optional)

1. Open `index.html` and find the line `const FEEDBACK_URL = "";` near the top of the script.
2. Paste in your repository's new-issue link:
   `https://github.com/YOUR-USERNAME/foster-cat-care-guide/issues/new?template=feedback.md`
3. Save. A **Send feedback** link will appear at the bottom of every page.

Testers need a free GitHub account to submit an issue. If your testers won't have accounts, use a Google Form instead and paste its link as `FEEDBACK_URL`.

## Files

- `index.html` is the complete app in one file.
- `TESTING.md` is the guide for testers: tasks to try and questions to answer.
- `.github/ISSUE_TEMPLATE/feedback.md` is the feedback form testers fill out on GitHub.

## Notes

- The app works on phones and desktops, in light and dark mode.
- The weight tracker saves entries only in the tester's own browser. Nothing is sent anywhere.
- Fonts load from Google Fonts. Everything else is contained in `index.html`.
- Sources for the medical content are listed on each topic page and on the "About the sources" page.
