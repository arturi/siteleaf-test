---
title: It’s my page
date: 2016-06-21 19:59:00 Z
blocks:
- type: free-content
  fields:
  - type: markdown
    content: Hello, *this* is it!
  - type: text
    content: My fav title
- type: place
  fields:
  - id: title
    type: text
    content: Cherny coop
  - id: location
    type: text
    content: Pokrovka
  - id: description
    type: markdown
    text: |-
      We'll ignore the state stuff for now, since it's not important for this simple plugin. The rest should be fairly straightforward.

      The next thing this method does is create an instance of the CompositeDisposable class so it can register all the commands that can be called from the plugin so other plugins could subscribe to these events.

      Yes.
- type: wide-img
  fields:
  - id: img
    type: img
    content: http://ya.ru
---

# Right.

![IMG_9078.jpg](/uploads/IMG_9078.jpg)
