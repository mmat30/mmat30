<div align="center">

# Mateo Martinez

### AWS Solutions Architect · Cloud Engineer · Software Engineer

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=16&duration=3000&pause=1200&color=93A1A1&center=true&vCenter=true&width=600&lines=Building+on+AWS+%E2%80%94+OIDC%2C+DynamoDB%2C+Lambda;Next.js+%2B+TypeScript+on+the+frontend;Rust+for+anything+that+needs+to+be+fast;Currently+writing+at+mem.codes" alt="Typing SVG" />

</div>

<br />

## About Me

Cloud-focused software engineer at AWS, based in Austin, TX. I gravitate toward systems that are boring in the right places — OIDC over static keys, passkeys over passwords, schema validation at every boundary — and write about that (and everything else) at [mem.codes](https://mem.codes).

Outside of the day job I split time between low-level systems and ML: LLMs and neural nets from scratch, a modular inference runtime, a Rust implementation of the Matrix protocol, mesh networking, and more custom keyboard firmware than is strictly reasonable.

<br />

## Skills

**Cloud & Infra**

![AWS](https://img.shields.io/badge/AWS-CB4B16?style=for-the-badge&logo=amazonaws&logoColor=FDF6E3)
![DynamoDB](https://img.shields.io/badge/DynamoDB-268BD2?style=for-the-badge&logo=amazondynamodb&logoColor=FDF6E3)
![Vercel](https://img.shields.io/badge/Vercel-6C71C4?style=for-the-badge&logo=vercel&logoColor=FDF6E3)
![Docker](https://img.shields.io/badge/Docker-2AA198?style=for-the-badge&logo=docker&logoColor=002B36)
![Kubernetes](https://img.shields.io/badge/Kubernetes-859900?style=for-the-badge&logo=kubernetes&logoColor=002B36)
![Terraform](https://img.shields.io/badge/Terraform-DC322F?style=for-the-badge&logo=terraform&logoColor=FDF6E3)

**Languages & Frameworks**

![TypeScript](https://img.shields.io/badge/TypeScript-268BD2?style=for-the-badge&logo=typescript&logoColor=FDF6E3)
![Next.js](https://img.shields.io/badge/Next.js-2AA198?style=for-the-badge&logo=nextdotjs&logoColor=002B36)
![Rust](https://img.shields.io/badge/Rust-CB4B16?style=for-the-badge&logo=rust&logoColor=FDF6E3)
![Python](https://img.shields.io/badge/Python-B58900?style=for-the-badge&logo=python&logoColor=002B36)
![Go](https://img.shields.io/badge/Go-859900?style=for-the-badge&logo=go&logoColor=002B36)
![Swift](https://img.shields.io/badge/Swift-DC322F?style=for-the-badge&logo=swift&logoColor=FDF6E3)

<br />

## GitHub Stats

<table align="center">
<tr>
<td><img height="165em" src="https://github-readme-stats.vercel.app/api?username=mmat30&show_icons=true&hide_border=true&bg_color=002B36&title_color=268BD2&text_color=839496&icon_color=2AA198" /></td>
<td><img height="165em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=mmat30&layout=compact&hide_border=true&bg_color=002B36&title_color=268BD2&text_color=839496" /></td>
</tr>
</table>

<div align="center">
<img src="https://github-readme-streak-stats.demolab.com?user=mmat30&background=002B36&border=073642&stroke=073642&ring=268BD2&fire=CB4B16&currStreakNum=EEE8D5&sideNums=839496&currStreakLabel=93A1A1&sideLabels=839496&dates=586E75&hide_border=false" alt="GitHub Streak" />
</div>

<br />

## Projects

### 🪶 [mem.codes](https://mem.codes)

Personal blog with a DynamoDB-backed admin portal, built on Next.js. *(Repo is private — the site isn't.)*

- **Zero static AWS keys** — DynamoDB access is provisioned through Vercel's AWS Marketplace integration over OIDC federation, not IAM access keys
- **Passwordless admin** — WebAuthn/passkey login only; no password is ever stored or checked
- **Validated at the boundary** — every mutation (posts, auth, the view counter) is checked against a Zod schema before it touches the database
- **Actually tested** — a full Playwright e2e suite (CRUD, autosave, image upload, auth/security) runs in CI on every push
- **The unglamorous SEO stuff, done right** — ISR, sitemap, RSS, JSON-LD, and EXIF/GPS stripping on every uploaded image

### 🌱 [verde](https://github.com/mmat30/verde) — *for the plot*

A small Rust CLI (`cargo install verde`) that scripts a git repo's commit history through `libgit2` — backdated, randomized commits, built to answer "what is a contribution graph actually made of?" A weekend `libgit2` exercise, not a claim about real work.

![Rust](https://img.shields.io/badge/Rust-CB4B16?style=flat-square&logo=rust&logoColor=FDF6E3)
![License](https://img.shields.io/badge/License-GPL--3.0-268BD2?style=flat-square)

<br />

## Heatmap

<div align="center">
<img src="https://github-readme-activity-graph.vercel.app/graph?username=mmat30&bg_color=002B36&color=839496&line=268BD2&point=2AA198&area=true&area_color=268BD2&title_color=268BD2&hide_border=true" alt="Contribution activity graph" width="100%" />
</div>

<br />

## Connect

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-268BD2?style=for-the-badge&logo=linkedin&logoColor=FDF6E3)](https://www.linkedin.com/in/mmat30/)
[![mem.codes](https://img.shields.io/badge/mem.codes-2AA198?style=for-the-badge&logo=rss&logoColor=002B36)](https://mem.codes)
![Austin, TX](https://img.shields.io/badge/Austin,_TX-586E75?style=for-the-badge&logo=googlemaps&logoColor=FDF6E3)

</div>

<br />

---

<div align="center">
<sub>Palette borrowed from <a href="https://mem.codes">mem.codes</a> — Solarized Dark, Ethan Schoonover's original values.</sub>
<br /><br />

![base03](https://img.shields.io/badge/base03-002B36-002B36?style=flat-square)
![blue](https://img.shields.io/badge/blue-268BD2-268BD2?style=flat-square)
![cyan](https://img.shields.io/badge/cyan-2AA198-2AA198?style=flat-square)
![green](https://img.shields.io/badge/green-859900-859900?style=flat-square)
![yellow](https://img.shields.io/badge/yellow-B58900-B58900?style=flat-square)
![orange](https://img.shields.io/badge/orange-CB4B16-CB4B16?style=flat-square)
![red](https://img.shields.io/badge/red-DC322F-DC322F?style=flat-square)
![magenta](https://img.shields.io/badge/magenta-D33682-D33682?style=flat-square)
![violet](https://img.shields.io/badge/violet-6C71C4-6C71C4?style=flat-square)

</div>
