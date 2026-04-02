# My Personal Site

A clean, minimal personal blog and portfolio — built with plain HTML & CSS, no build tools required.

## File structure

```
my-site/
├── index.html       ← Homepage
├── blog.html        ← Blog listing
├── projects.html    ← Projects page
├── about.html       ← About page
├── style.css        ← All styles
└── posts/
    ├── post-1.html  ← Sample post (edit this as a template)
    ├── post-2.html
    └── post-3.html
```

## Deploying to GitHub Pages

1. Create a new repo named `yourusername.github.io` on GitHub
2. Upload all these files to the repo root
3. Go to **Settings → Pages → Source → Deploy from branch → main**
4. Your site will be live at `https://yourusername.github.io` in ~2 minutes

## Customising the site

**Change your name:** Find & replace "Your Name" across all .html files.

**Update links:** Replace `yourusername` with your actual GitHub/Twitter username, and `you@example.com` with your email.

**Add a new blog post:**
1. Duplicate `posts/post-1.html` and rename it (e.g. `posts/my-new-post.html`)
2. Update the `<title>`, the `.post-meta` date, and the `.post-header h1`
3. Replace the content inside `.post-body`
4. Add a new `.blog-item` entry in both `blog.html` and `index.html`

**Add a new project:**
1. Add a new `.project-card` block in `projects.html` and `index.html`
2. Update the emoji icon, name, description, tags, and `href` link

## Fonts used
- [Lora](https://fonts.google.com/specimen/Lora) — serif headings
- [DM Sans](https://fonts.google.com/specimen/DM+Sans) — body text
