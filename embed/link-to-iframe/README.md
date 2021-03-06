# Convert a Weblink into an iFrame
*by [Jack Dougherty](../introduction/who.md), last updated March 15, 2017*

After you publish your data visualization to the web, how do you convert its weblink (or URL) into an iFrame, to embed in your personal website?

The answer depends: did you publish your visualization as a code template on GitHub Pages? Or did you publish it using a drop-and-drag tool such as Google Sheets or Tableau Public?

## Published with a code template on GitHub Pages
If you published your visualization from a code template (such as Leaflet or Highcharts) with GitHub Pages, follow these easy steps:

1) Copy the URL of your published visualization on GitHub, which will be in this format:
```
https://USERNAME.github.io/REPOSITORY
```

2) Add ```iframe``` tags to the beginning and end, insert ```src=``` and enclose the URL inside quotation marks, like this:
```
<iframe src="https://USERNAME.github.io/RESPOSITORY"></iframe>
```

3) Optional: Insert preferred width and height (in pixels by default, or percentages), like this:
```
<iframe src="https://USERNAME.github.io/RESPOSITORY" width="90%" height="400"></iframe>
```

4) Go to the appropriate tutorial to embed your iframe in your personal website:
- [Embed an iframe in GitHub Pages](../iframe-github)
- [Embed an iframe in WordPress.org](../iframe-wordpress)

## Published with Google Sheets or Tableau Public
Or, if you published your visualization using a drop-and-drag tool, see these tutorials:
- [Copy an iframe code from a Google Sheets interactive chart](../iframe-google-sheets)
- [Embed Tableau Public on your Website](../tableau)

{% footer %}
{% endfooter %}
