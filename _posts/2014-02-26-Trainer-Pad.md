---
layout: post
title: "Trainer Pad"
quote: The definitive tool for trainers and athletes, fine-tuned and personalized for different sports and activities through specialized tasks modules.
image: /media/2014-02-26-Trainer-Pad/pankration3.jpg
video: false
---

#Trainer Pad 1.0, codename "[Milon](/)"

{% include image.html url="/media/2014-02-26-Trainer-Pad/allenamento-nano.jpg" width="100%" description="Most historians agree that Milo remains to this day the greatest wrestler and fighter (from any combat sport) the world has ever known. Milo of Croton became an Olympic champion several times during his nearly thirty-year career. His size and physique were intimidating, and his strength and technique perfect—and many people accordingly believed that he was  the son of Zeus. He was said to eat more than eight kilograms of meat every day. Some say that he even once carried an adult bull on his shoulders, all the way to the Olympic stadium, where he slaughtered and devoured it. Yet Milo was not merely a hulking wrestler; he was also a musician and a poet, as well as a student of the mathematician and philosopher Pythagoras.The greatest wrestler of the twentieth century, Alexander Karelin, was often called the modern-day Milo of Croton—but he himself acknowledged that he would not stand a good chance against the real Milo." %}

{% include image.html url="/media/2014-02-26-Trainer-Pad/run_2.jpg" width="100%" description="Olympics games: London 2012." %}


## Features
Modular system for the complete mamnagement of sporting activities. 

<table>
  <thead>
    <tr>
      <th>Module</th>
      <th>Description</th>
      <th>Sport</th>
      <th>Release date</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Timers</td>
      <td>Taking times, scores, running timers, rates.</td>
      <td>All</td>
      <td>June 2014</td>
    </tr>
    <tr>
      <td>Training</td>
      <td>Training routines</td>
      <td>All</td>
      <td>July 2014</td>
    </tr>
    <tr>
      <td>Imaging</td>
      <td>Shooting films and photos, movement analisys. Image and film annotations.</td>
      <td>All</td>
      <td>August 2014</td>
    </tr>
    <tr>
      <td>Calendars</td>
      <td>Scheduling, activity calendars.</td>
      <td>All</td>
      <td>September 2014</td>
    </tr>
    <tr>
      <td>Team and athlets management</td>
      <td>Keeping track of teams and athletes data.</td>
      <td>All</td>
      <td>September 2014</td>
    </tr>
    <tr>
      <td>Calendars</td>
      <td>Scheduling training sessions and events, organizing tounaments, activity calendars, tracking game fields, lanes, tracks.</td>
      <td>All</td>
      <td>September 2014</td>
    </tr>
    <tr>
      <td>Notes</td>
      <td>Typed or hand written note taking and sketching, game fields annotations</td>
      <td>All</td>
      <td>September 2014</td>
    </tr>
    <tr>
      <td>Rules</td>
      <td>Game rule books and regulations.</td>
      <td>All</td>
      <td>September 2014</td>
    </tr>
    <tr>
      <td>Mapping</td>
      <td>Tracking distances, field and road conditions, terrain satellite images.</td>
      <td>All</td>
      <td>September 2014</td>
    </tr>
    <tr>
      <td>Safety</td>
      <td>Warning for proximity or dangerous situations.</td>
      <td>Sculling</td>
      <td>September 2014</td>
    </tr>
    <tr>
      <td>Communications</td>
      <td>Text and voice communication. GPS, Wi-Fi, BlueTooth tracking of networked devices.</td>
      <td>All</td>
      <td>September 2014</td>
    </tr>
    <tr>
      <td>Weather</td>
      <td>Hourly weather reports for local conditions with detailed satellite imaginery.</td>
      <td>All</td>
      <td>September 2014</td>
    </tr>
    <tr>
      <td>Nutrition</td>
      <td>Keeping track of nutrition facts, diets, calories ingest.</td>
      <td>All</td>
      <td>September 2014</td>
    </tr>
    <tr>
      <td>Medical</td>
      <td>Medical records, bio stats.</td>
      <td>All</td>
      <td>September 2014</td>
    </tr>
  </tbody>
</table> 

## Usage

{% include image.html url="/media/2014-02-26-Trainer-Pad/rowing_3.jpg" width="100%" description="Olympics games: London 2012." %}

### Main variables

The global variables are set on the `_config.yml` file.

To start, you need to change at least the variable `url` on the file.

#### Social links

{% include image.html url="/media/2014-02-26-Trainer-Pad/bike_1.jpg" width="100%" description="Olympics games: London 2012." %}

To add a social link you just need to add the following code inside the variable `social`:

```
  - icon:	[the genericon name for the social network]
    url:	[the url to follow]
    desc:	[a small description for the link (e.g. "Follow me on twitter")]
```

#### Menu

To add a menu item you just need to add the following code inside the variable `menu`:

```
  - title:	[title of the menu item]
    url:	[the url to follow]
```

#### Others

{% include image.html url="/media/2014-02-26-Trainer-Pad/swim_2.jpg" width="100%" description="Olympics games: London 2012." %}

You'll find a lot of other variables inside the file, e.g.:

- the site `title`, `description`, `icon` and default `cover` image.
- text of the `copyright` message.
- the number of posts per page (`paginate`).
- the `permalink`'s structure (see [the docs](http://jekyllrb.com/docs/pagination/)).


### Default YAML tags

- `layout:`<i>`post, page`</i> `or `<i>`fullscreen`</i>: defines the layout of the page.
- `title: [string]`: title of the post.
- `quote: [string]`: a small description of the post to be shown above the title.
- `dark:`<i>`true`</i> `or `<i>`false`</i>: use black font (instead of white) for the header (default value is false).
- `image: [url] or `<i>`false`</i>: a cover image for the post (default value is _false_).
- `video:`<i>`true`</i> `or `<i>`false`</i>: add a cover video for the post (default value is _false_).
- `video_mp4: [url]`: the URL for the mp4 video.
- `video_webm: [url]`: the URL for the webm video.
- `video_ogv: [url]`: the URL for the ogv video.


## Download

> Thinny 2.1 is already [available for download on GitHub](https://github.com/camporez/Thinny/releases).

-----
Want to see something else added or report a bug? [Open an issue](https://github.com/camporez/camporez.github.io/issues/new).
