# CSUF ACM Webring

A webring for CSUF ACM friends. Share your personal sites, portfolios, and projects!

**Live:** [webring-1.vercel.app](https://webring-1.vercel.app)

## Join the webring

1) Add your website to [index.html](index.html) - add to both the `sites` array (in the head script) and the `<ol>` list:

```html
<!-- In the head script sites array -->
{ id: 'your-name', url: 'https://yoursite.com' }

<!-- In the <ol id="icons"> list -->
<li data-lang="en" id="your-name">
  <a href="https://yoursite.com">Your Name</a>
</li>
```

2) Submit a Pull Request!

3) Add prev/next navigation to your site footer (see [lyyeric.tech](https://lyyeric.tech) for example)

## Managed by

[@lyyeric](https://lyyeric.tech) | CSUF ACM
