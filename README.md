<!-- readme-sync:repo:start -->
# og\-image

Open Graph Image as a Service \- generate cards for Twitter, Facebook, Slack, etc
<!-- readme-sync:repo:end -->

<!-- readme-sync:header:start -->
<p>
  <a href="https://kitze.io/?ref=kitze%2Fog-image"><img src="https://unavatar.io/x/thekitze" align="left" hspace="12" width="64" height="64" alt="Kitze"></a>
  <strong>Made by <a href="https://kitze.io/?ref=kitze%2Fog-image">Kitze</a></strong><br>
  <a href="https://kitze.io/?ref=kitze%2Fog-image">kitze.io</a> · <a href="https://x.com/thekitze?ref=kitze%2Fog-image">X</a> · <a href="https://youtube.com/kitze?ref=kitze%2Fog-image">YouTube</a>
</p>
<br clear="all">


<h3>More projects by Kitze</h3>
<table>
  <tr>
    <td width="50%" valign="top">
      <a href="https://zerotoshipped.com/?ref=kitze%2Fog-image"><img src="https://zerotoshipped.com/ship.png" width="72" alt="Zero To Shipped logo"></a><br>
      <strong><a href="https://zerotoshipped.com/?ref=kitze%2Fog-image">Zero To Shipped</a></strong><br>
      A full-stack starter kit for web and mobile apps.
    </td>
    <td width="50%" valign="top">
      <a href="https://sotto.to/?ref=kitze%2Fog-image"><img src="https://sotto.to/apple-touch-icon.png" width="48" alt="Sotto logo"></a><br>
      <strong><a href="https://sotto.to/?ref=kitze%2Fog-image">Sotto</a></strong><br>
      Voice-to-text for macOS. Local AI, one-time purchase.
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <a href="https://tinkerer.club/?ref=kitze%2Fog-image"><img src="https://app.tinkerer.club/brand/tinkerer-logo-128.png" width="48" alt="Tinkerer Club logo"></a><br>
      <strong><a href="https://tinkerer.club/?ref=kitze%2Fog-image">Tinkerer Club</a></strong><br>
      A private community for builders, self-hosters, and AI tinkerers.
    </td>
    <td width="50%" valign="top">
      <a href="https://sizzy.co/?ref=kitze%2Fog-image"><img src="https://sizzy.co/apple-touch-icon.png" width="48" alt="Sizzy logo"></a><br>
      <strong><a href="https://sizzy.co/?ref=kitze%2Fog-image">Sizzy</a></strong><br>
      The browser for web developers.
    </td>
  </tr>
</table>

<h3>Sponsors</h3>
<table>
  <tr>
    <td width="50%" valign="top">
      <a href="https://postiz.com/?ref=kitze%2Fog-image"><img src="https://media.gifs.so/sponsors/50b4a915f9c47b5328b97281/b08730d86b240100fd72d42b828923856d14d82d50eb5698b99cf8e2ca125288.webp" width="40" alt="Postiz logo"></a><br>
      <strong><a href="https://postiz.com/?ref=kitze%2Fog-image">Postiz</a></strong><br>
      Schedule social posts with AI agents.
    </td>
    <td width="50%" valign="top">
      <a href="https://www.founderstack.pro/?ref=kitze%2Fog-image"><img src="https://media.gifs.so/sponsors/bc182e02573bf0e14da0cb0c/f164ca56c7b1d7869e589917f716e58355536eef30854f62c49f711c07a7de96.webp" width="40" alt="FounderStack logo"></a><br>
      <strong><a href="https://www.founderstack.pro/?ref=kitze%2Fog-image">FounderStack</a></strong><br>
      A SaaS stack for your business, without subscriptions.
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <a href="https://matte.app/?ref=kitze%2Fog-image"><img src="https://media.gifs.so/sponsors/4193d8ef8f8b0660107703fe/66b20a60c4d9e1da3d999efe862e86f600ebb5a4ffa3a8b63f40a507fef91f66.webp" width="40" alt="Matte logo"></a><br>
      <strong><a href="https://matte.app/?ref=kitze%2Fog-image">Matte</a></strong><br>
      3D mockups, screen recordings, and video editing.
    </td>
    <td width="50%" valign="top">
      <a href="https://htmlcsstoimage.com/?ref=kitze%2Fog-image"><img src="https://media.gifs.so/sponsors/f4c20d84da68764c3f7a4f67/167bf23cf98b11e2d55ea9aa69f83052daceb881bdea7b76925ffa185ed66d2b.webp" width="40" alt="HTML/CSS to Image logo"></a><br>
      <strong><a href="https://htmlcsstoimage.com/?ref=kitze%2Fog-image">HTML/CSS to Image</a></strong><br>
      Turn HTML/CSS into images, PDFs, and screenshots.
    </td>
  </tr>
  <tr>
    <td colspan="2" valign="top">
      <a href="https://namemyventi.com/?ref=kitze%2Fog-image"><img src="https://media.gifs.so/sponsors/da87180867c3c7451bd30d7b/43ce5be2540cf23d3d7d7104ba829a455a9608861a780e0ec2b35b189695f7ea.webp" width="40" alt="NameMyVenti logo"></a><br>
      <strong><a href="https://namemyventi.com/?ref=kitze%2Fog-image">NameMyVenti</a></strong><br>
      Get your brand shouted out at Starbucks.
    </td>
  </tr>
</table>

<br>

<hr>

<br>
<!-- readme-sync:header:end -->

# [Open Graph Image as a Service](https://og-image.now.sh)

<a href="https://twitter.com/zeithq/status/1092587111985881088">
    <img align="right" src="https://raw.githubusercontent.com/zeit/og-image/master/public/tweet.png" height="300" />
</a>

Serverless service that generates dynamic Open Graph images that you can embed in your `<meta>` tags.

For each keystroke, headless chromium is used to render an HTML page and take a screenshot of the result which gets cached.

See the image embedded in the tweet for a real use case.


## What is an Open Graph Image?

Have you ever posted a hyperlink to Twitter, Facebook, or Slack and seen an image popup?
How did your social network know how to "unfurl" the URL and get an image?
The answer is in your `<head>`.

The [Open Graph protocol](http://ogp.me) says you can put a `<meta>` tag in the `<head>` of a webpage to define this image.

It looks like the following:

```html
<head>
  <title>Title</title>
  <meta property="og:image" content="http://example.com/logo.jpg" />
</head>
```

## Why use this service?

Read the [blog post](https://zeit.co/blog/social-og-image-cards-as-a-service) for more info on the "Why" part.

The short answer is that it would take a long time to painstakingly design an image for every single blog post. And we don't want the exact same image for every blog post because that wouldn't make the article stand out when it was shared to Twitter. 

That's where `og-image.now.sh` comes in. We can simply pass the title of our blog post to our generator service and it will generate the image for us on the fly!

It looks like the following:

```html
<head>
  <title>Hello World</title>
  <meta property="og:image" content="https://og-image.now.sh/Hello%20World.png" />
</head>
```

Now try changing the text `Hello%20World` to the title of your choosing and watch the magic happen ✨

## Deploy your own

You'll want to fork this repository and deploy your own image generator.

1. Click the fork button at the top right of GitHub
2. Clone the repo to your local machine with `git clone URL_OF_FORKED_REPO_HERE`
3. Change directory with `cd og-image`
4. Make changes by swapping out images, changing colors, etc (see [contributing](https://github.com/zeit/og-image/blob/master/CONTRIBUTING.md) for more info)
5. Run locally with `now dev` and visit [localhost:3000](http://localhost:3000)  (if nothing happens, run `npm install -g now`)
6. Deploy to the cloud by running `now` and you'll get a unique URL
7. Setup [GitHub](https://zeit.co/github) to autodeply on push and set an `alias` in [now.json](https://zeit.co/github) to customize your URL.

Alternatively, you can do a one-click to deploy with the button below.

[![Deploy to now](https://deploy.now.sh/static/button.svg)](https://zeit.co/new/project?template=zeit/og-image)

Once you have an image generator that sparks joy, you can setup [automatic Now + GitHub](https://zeit.co/github) deployments so that pushing to master is also deploying to production! 🚀

## Authors

- Steven ([@styfle](https://twitter.com/styfle)) - [ZEIT](https://zeit.co)
- Evil Rabbit ([@evilrabbit](https://twitter.com/evilrabbit_)) - [ZEIT](https://zeit.co)


<!-- readme-sync:footer:start -->
<hr>
<h3>More projects by Kitze</h3>
<h4>Apps &amp; tools</h4>
<table>
  <tr>
    <td width="50%" valign="top">
      <strong><a href="https://gifs.so/?ref=kitze%2Fog-image">gifs.so</a></strong><br>
      Search, copy, and download reaction GIFs.
    </td>
    <td width="50%" valign="top">
      <strong><a href="https://glink.so/?ref=kitze%2Fog-image">Glink</a></strong><br>
      Feedback, roadmaps, changelogs, and discussions.
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <strong><a href="https://benji.so/?ref=kitze%2Fog-image">Benji</a></strong><br>
      Tasks, habits, calendar, health, and routines in one place.
    </td>
    <td width="50%" valign="top">
      <strong><a href="https://dmx.to/?ref=kitze%2Fog-image">DMX</a></strong><br>
      A focused desktop client for X.
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <strong><a href="https://glink.so/kitze/mindy?ref=kitze%2Fog-image">Mindy</a></strong><br>
      An AI browser that keeps your work organized.
    </td>
    <td width="50%" valign="top">
      <strong><a href="https://glink.so/kitze/supermac?ref=kitze%2Fog-image">Supermac</a></strong><br>
      A macOS command center for everyday workflows.
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <strong><a href="https://glink.so/kitze/k67-1787136958277?ref=kitze%2Fog-image">K67</a></strong><br>
      A fork of T3 Code for working with coding agents.
    </td>
    <td width="50%" valign="top">
      <strong><a href="https://perkz.to/?ref=kitze%2Fog-image">Perkz</a></strong><br>
      Sell and manage access to private GitHub repositories.
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <strong><a href="https://glink.so/kitze/labz?ref=kitze%2Fog-image">Labz</a></strong><br>
      A platform for teaching workshops and courses.
    </td>
    <td width="50%" valign="top">
      <strong><a href="https://glink.so/kitze/popcorner-1762890546557?ref=kitze%2Fog-image">Popcorner</a></strong><br>
      Organize your movies and TV shows.
    </td>
  </tr>
  <tr>
    <td colspan="2" valign="top">
      <strong><a href="https://glink.so/kitze/champions?ref=kitze%2Fog-image">Champions Online</a></strong><br>
      A free multiplayer card-game platform.
    </td>
  </tr>
</table>

<h4>Open source</h4>
<table>
  <tr>
    <td width="50%" valign="top">
      <strong><a href="https://github.com/kitze/skillbox?ref=kitze%2Fog-image">Skillbox</a></strong><br>
      A self-hosted, versioned skills library for AI agents.
    </td>
    <td width="50%" valign="top">
      <strong><a href="https://github.com/kitze/unclutter?ref=kitze%2Fog-image">Unclutter</a></strong><br>
      Remove page clutter with AI-powered, reusable browser rules.
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <strong><a href="https://github.com/kitze/pagegrade?ref=kitze%2Fog-image">PageGrade</a></strong><br>
      Grade page clarity, writing, and on-page SEO.
    </td>
    <td width="50%" valign="top">
      <strong><a href="https://github.com/kitze/council?ref=kitze%2Fog-image">Council</a></strong><br>
      Let your coding agents deliberate together before making a plan.
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <strong><a href="https://github.com/kitze/codexmaxx?ref=kitze%2Fog-image">CodexMaxx</a></strong><br>
      Manage Codex accounts, usage, and active sessions on macOS.
    </td>
    <td width="50%" valign="top">
      <strong><a href="https://github.com/kitze/react-hanger?ref=kitze%2Fog-image">React Hanger</a></strong><br>
      A collection of useful React hooks.
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <strong><a href="https://github.com/kitze/react-genie?ref=kitze%2Fog-image">React Genie</a></strong><br>
      Animate React elements as they enter the viewport.
    </td>
    <td width="50%" valign="top">
      <strong><a href="https://github.com/kitze/mobx-router?ref=kitze%2Fog-image">MobX Router</a></strong><br>
      A simple router for MobX and React apps.
    </td>
  </tr>
</table>

<p><a href="https://kitze.io/projects?ref=kitze%2Fog-image">All projects</a> · <a href="https://github.com/kitze?ref=kitze%2Fog-image">GitHub</a> · <a href="https://x.com/thekitze?ref=kitze%2Fog-image">Follow on X</a> · <a href="https://youtube.com/kitze?ref=kitze%2Fog-image">YouTube</a></p>
<!-- readme-sync:footer:end -->
