# CSUF ACM Webring

A webring for CSUF ACM friends. Share your personal sites, portfolios, and projects!

**Live:** [webring-1.vercel.app](https://webring-1.vercel.app)

## Join the webring

### Step 1: Add your site to index.html

Add to both the `sites` array (in the head script) AND the `<ol>` list:

```html
<!-- In the head script sites array -->
{ id: 'your-name', url: 'https://yoursite.com' }

<!-- In the <ol id="icons"> list -->
<li data-lang="en" id="your-name">
  <a href="https://yoursite.com">Your Name</a>
</li>
```

### Step 2: Add webring navigation to YOUR site (required!)

Add these links to your site's footer so visitors can navigate the ring:

```html
<a href="https://webring-1.vercel.app/?from=your-name&dir=prev">←</a>
<a href="https://webring-1.vercel.app/?from=your-name&dir=next">→</a>
```

Replace `your-name` with your id from Step 1.

See [lyyeric.tech](https://lyyeric.tech) for a live example (scroll to footer).

### Step 3: Submit a Pull Request!

## Managed by

[@lyyeric](https://lyyeric.tech) | CSUF ACM
