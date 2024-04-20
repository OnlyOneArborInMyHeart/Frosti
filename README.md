# 🧊 Frosti

**A clean, elegant, and fast static blog template! Developed using [Astro](https://astro.build/)！**

[**🖥️ Frosti Demo**](https://forsti.saroprock.com)&nbsp;&nbsp;&nbsp;/&nbsp;&nbsp;&nbsp;[**🌏 中文 README**](https://github.com/EveSunMaple/Frosti/blob/main/README.zh-CN.md)&nbsp;&nbsp;&nbsp;/&nbsp;&nbsp;&nbsp;[**❤️My Blog**](https://www.saroprock.com)

> [!NOTE]
> For a better reading experience, visit ->

## 🖥️ Preview

![view](./view.png)

## ✨ Features

- ✅ Page sub-routing
- ✅ Excellent loading speed
- ✅ **Light** / **Dark** modes available
- ✅ Various components for enriching article content
- ✅ Various components for enriching page content
- ✅ Comment system built with [Waline](https://waline.js.org/)
- ✅ Beautiful pages built with [Tailwind CSS](https://tailwindcss.com/) and [daisyUI](https://daisyui.com/)

## 🚀 Project Structure

```bash
\Frosti
├── astro.config.mjs
├── categories.txt
├── index.png
├── package-lock.json
├── package.json
├── pnpm-lock.yaml
├── public
|  ├── favicon.svg
|  ├── fonts
|  |  └── CascadiaCode.woff2
|  ├── home.webp
|  └── profile.webp
├── README.md
├── README.zh-CN.md
├── src
|  ├── components
|  |  ├── BaseCard.astro
|  |  ├── BaseHead.astro
|  |  ├── blog
|  |  |  ├── error.astro
|  |  |  ├── info.astro
|  |  |  ├── success.astro
|  |  |  └── warning.astro
|  |  ├── Comment.astro
|  |  ├── CopyBtn.astro
|  |  ├── EnvelopeCard.astro
|  |  ├── Footer.astro
|  |  ├── FormattedDate.astro
|  |  ├── Header.astro
|  |  ├── HeaderLink.astro
|  |  ├── License.astro
|  |  ├── ProfileCard.astro
|  |  ├── ProfileCardFooter.astro
|  |  ├── ProfileCardMenu.astro
|  |  └── ThemeIcon.astro
|  ├── consts.ts
|  ├── content
|  |  ├── blog
|  |  |  ├── markdown-style-guide.md
|  |  |  └── using-mdx.mdx
|  |  └── config.ts
|  ├── env.d.ts
|  ├── layouts
|  |  └── BaseLayout.astro
|  ├── pages
|  |  ├── about.astro
|  |  ├── blog
|  |  |  ├── tag
|  |  |  ├── [...page].astro
|  |  |  └── [...slug].astro
|  |  ├── friend.astro
|  |  ├── index.astro
|  |  ├── project.astro
|  |  └── rss.xml.js
|  ├── scripts
|  |  └── copybutton.mjs
|  └── styles
|     └── global.css
├── tailwind.config.js
└── tsconfig.json
```

## ✒️ Article Information

| Name | Meaning | Mandatory |
| :---: | :---: | :---: |
| title | Article title | Yes |
| description | Article description | Yes |
| pubDate | Article date | Yes |
| image | Article cover | No |
| tags | Article tags | No |
| badge | Article badge | No |

## ⬇️ Usage

Use Frosti by passing the `--template` parameter to the `create astro` command!

```bash
npm create astro@latest -- --template EveSunMaple/Frosti
```

## 🎯 Plans

- [] Add table of contents (done but CSS not written)
- [] Add timeline component
- [] Add friends link component

## 👀 Issues

- [] `global.css` is too messy
- [] **Light** / **Dark** mode transition is currently not implemented
- [] Website score has not reached 400 yet

## 🎉 Acknowledgments

@[Saicaca](https://github.com/saicaca) His inspiration is the main reason for me to create this theme
@[WRXinYue](https://github.com/WRXinYue) Helped me a lot in my early learning phase