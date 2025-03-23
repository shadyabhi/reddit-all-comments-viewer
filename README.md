# Reddit All Comments Viewer

> [!info]- This only works with https://old.reddit.com as that's the only UI I
> use, even today!

This extention started with a need where I wanted to search for a comment on a
very popular Reddit post, but I had only seen that comment a few hours ago that
day.
To optimize server workloads, Reddit only loads popular comments "on-load" of a
post, and rest of the lesser popular ones are hidden behind `load more comments`
link. That means, I've no way to search for that comment via `CMD+F` shortcut in
browser.

To solve this, I created this extension which can expand all those hidden
comments, so I can search for my comment via text easily.

<img width="1306" alt="image" src="https://github.com/user-attachments/assets/774cb3bc-6eea-4f29-9a2e-d3e44d2b0f66" />

# Dev

This extension is also published on the Chrome Web Store: [Click Here](https://chromewebstore.google.com/detail/reddit-all-comments-viewe/djifpbcmaphjihhelcdeannijfelfnbh)

## Publishing

- [ ] Ensure that we've updated the new version in `manifest.json`
- [ ] Run: `make zip`, which creates the new zip file. This file is what's
  uploaded on Web Store.
- [ ] Upload on Chrome developer console.
- [ ] Press `Publish` when you've made all the modifications.
