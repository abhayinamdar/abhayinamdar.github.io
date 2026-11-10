# abhayinamdar-site

Personal website of Abhay Inamdar: a profile page and a blog of his articles.
Built with [Eleventy](https://www.11ty.dev/). Every article is one Markdown file.

## Add a new article (no coding needed)

1. Open the `src/articles` folder on GitHub.
2. Click **Add file → Create new file**.
3. Name the file like this: `2026-11-10-short-title.md`
   (the date, then a few words of the title joined with dashes).
4. Copy everything from `NEW-POST-TEMPLATE.md` into it, then change the
   title, date, summary and the text.
5. Click **Commit changes**. The site updates by itself in about 1–2 minutes.

To add a picture: upload it to `src/images`, then write
`![What the picture shows](/images/picture-name.jpg)` in the article.

## Change the profile

Profile text (jobs, projects, skills, education, awards) lives in
`src/_data/profile.json`. Contact links live in `src/_data/site.json`.

## Run it on your computer

```bash
npm install
npm start
```

Then open http://localhost:8080.
