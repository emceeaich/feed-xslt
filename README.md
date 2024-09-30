How to use this:

In your site's Atom feed, add the following to the top, before the opening `<feed ...>`element.

```xml
<?xml-stylesheet href="/blog/atom.xsl" type="text/xsl"?>
```
Change the `/blog/atom.xsl` path to where you will serve this file from.

Because of browser content security models, you will need to serve both your feed and this xslt file from the same domain, under HTTPS.

If you're `mae-the-space-cat.neocities.org` and your feed is at `mae-the-space-cat.neocities.org/feed.xml` then put this file at `mae-the-space-cat.neocities.org/atom.xsl`.

RSS and combined versions of this are forthcoming.

[![animated gif of eggbug with text 'i was on cohost'](/i-was-on-cohost.gif)](https://cohost.org/emmah)

[![88x31px link to maintainer's website](https://emmas.site/public/images/88x31.png)](https://emmas.site)
