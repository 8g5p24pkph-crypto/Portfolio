# Sebastian Xue Estevez — Portfolio

Personal portfolio website built with pure HTML/CSS/JS. No frameworks, no dependencies — just one file.

## 🚀 Deploy to GitHub Pages (3 steps)

1. Create a new GitHub repo named `your-username.github.io` (or any name)
2. Upload `index.html` to the repo
3. Go to **Settings → Pages → Source → main branch** → Save

Your site will be live at `https://your-username.github.io` within a minute.

## 📹 Adding Your Intro Video

In `index.html`, find the `video-placeholder` div inside `#intro` and replace it with:

**YouTube embed:**
```html
<iframe width="100%" height="100%" style="position:absolute;inset:0;border-radius:18px;"
  src="https://www.youtube.com/embed/YOUR_VIDEO_ID"
  frameborder="0" allowfullscreen></iframe>
```

**Local video file:**
```html
<video width="100%" height="100%" controls style="border-radius:18px;object-fit:cover;">
  <source src="your-video.mp4" type="video/mp4">
</video>
```

## 🎨 Customization

- **Colors**: Edit CSS variables at the top of the `<style>` block (`:root { ... }`)
- **Accent color**: Change `--accent: #2997ff` to any color you like
- **Add/remove labs**: Edit the `labs` array in the `<script>` block at the bottom
- **Profile photo**: Add `<img src="your-photo.jpg">` inside the hero section

## 📁 File Structure

```
sebastian-portfolio/
└── index.html    ← entire site, self-contained
```
