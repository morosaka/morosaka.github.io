---
layout: post
title: "Action Cam"
quote: Camera module specialized in action review, movement analisys, and image annotation.
image: /media/2014-01-22-View-Camera/Pompejanischer-Maler-2.jpg
video: false
---

Record both stroke rate frequencies and lap, cumulative piece time events.
Recall all current events on the fly, right on the main screen.
Email current events to anybody. Review the saved data on your computer at home.

The whole events display area accepts taps, making it easier to input commands.
Buttons can have a audible feedback. All functions are clearly marked and labeled for easy usage.
It is possible to take rate frequency over 2, 3, 4, or 5 cycles.

Rates are displayed both as cycles per minute (cpm) and seconds per cycle (spc), piece times measure Laps and Cumulative times, all shown on one screen.

#Thinny 2.0, codename "[Bianca](http://memoriaglobo.globo.com/programas/entretenimento/novelas/caras-bocas/caras-bocas-bianca-isabelle-drummond.htm)"

This new version of Thinny goes deeper with the [initial idea](http://ghost-camporez.rhcloud.com/making-applications-icon-smaller-on-gnome-shells-top-panel/) of a big image before the post. As the saying goes, <cite>a picture is worth a thousand words</cite>, so we expanded the concept. I mean, literally. The post image (or video!) is now full width and full height, and can be easily add with the use of a variable.
##Features

### Lists and text formatting

You can use various HTML tags:

- **To bold text**, use `<strong>`.
- *To italicize text*, use `<em>`.
- Abbreviations, like <abbr title="HyperText Markup Langage">HTML</abbr> should use `<abbr>`, with an optional `title` attribute for the full phrase.

1. Citations, like <cite>&mdash; {{ site.title }}</cite>, should use `<cite>`.
2. <del>Deleted</del> text should use `<del>` and <ins>inserted</ins> text should use `<ins>`.
3. Superscript <sup>text</sup> uses `<sup>` and subscript <sub>text</sub> uses `<sub>`.

###Messages, code and images

<div class="message">This is a <strong>warning</strong> message. Now, you can keep falling in love with this theme...</div>

You can add `code elements` with highlight support:
<div class="highlight"><pre><code class="ruby"><span class="p">{</span><span class="o">%</span> <span class="kp">include</span> <span class="n">image</span><span class="o">.</span><span class="n">html</span> <span class="n">url</span><span class="o">=</span><span class="s2">&quot;/media/2014-01-22-thinny-2/bianca.jpg&quot;</span> <span class="n">width</span><span class="o">=</span><span class="s2">&quot;100&#37;&quot;</span> <span class="n">description</span><span class="o">=</span><span class="s2">&quot;Image captions are supported out of the box. Brilliant!&quot;</span> <span class="o">%</span><span class="p">}</span></code></pre></div>

Will output this:

{% include image.html url="/media/2014-01-22-thinny-2/bianca.jpg" width="100%" description="Image captions are supported out of the box. Brilliant!" %}

### Table

Thinny also support html tag `<table>`:
<table>
  <thead>
    <tr>
      <th>Version</th>
      <th>Codename</th>
      <th>Platform</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>[0.3](https://github.com/camporez/Thinny/releases/tag/v0.3-alexandra)</td>
      <td>[Alexandra](http://nikita2010.wikia.com/wiki/Alexandra_Udinov)</td>
      <td>Ghost 0.3.x</td>
    </tr>
    <tr>
      <td>[2.0](https://github.com/camporez/Thinny/releases/tag/v2.0-bianca)</td>
      <td>[Bianca](http://memoriaglobo.globo.com/programas/entretenimento/novelas/caras-bocas/caras-bocas-bianca-isabelle-drummond.htm)</td>
      <td>Jekyll</td>
    </tr>
    <tr>
      <td>2.1</td>
      <td>[Cosette](http://lesmiserables.wikia.com/wiki/Cosette)</td>
      <td>Jekyll</td>
    </tr>
  </tbody>
</table>

### Mobile version

<strong>Coming soon...</strong>

### Quote

> Did you liked it? You can [download Thinny on GitHub](https://github.com/camporez/Thinny/releases).

-----
Want to see something else added? [Open an issue](https://github.com/camporez/camporez.github.io/issues/new).
