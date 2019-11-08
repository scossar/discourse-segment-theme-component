# Discourse Segment Tracking Theme Component

Allows you to send page view and event data from your Discourse
site to Segment.

### Installation

See [How do I install a Theme or Theme Component?](https://meta.discourse.org/t/how-do-i-install-a-theme-or-theme-component/63682).

### Use

Add your Segment Write Key to the component's settings page, then select what you would like to
track. The component supports calling `segment.identify` when a user first logs on to the site. It allows for tracking views of the
Discourse latest, categories, category, tag, and topic pages. It allows you to track topic and post creation, likes, flags, and bookmarks.