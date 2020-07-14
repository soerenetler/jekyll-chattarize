---
layout: blocks
title: Chattarize
date: 2020-07-07T23:00:00.000+00:00
page_sections:
- template: navigation-header-w-button
  block: header-2
  logo: "/uploads/Chattarize.svg"
  navigation:
  - link: "/"
    link_text: Home
  - link: "#features"
    link_text: First steps
  - link: "#team"
    link_text: Team
  cta:
    url: https://github.com/soerenetler/ZoomViz/releases/latest
    button_text: Download

- template: hero-banner-w-image
  block: hero-2
  headline: <strong>Chattarize</strong>
  content: A free open source tool to visualize your Zoom chat. <br> <br> Chattarize can help you with stunning visualizations of the Zoom chat and make the participants of your online workshop part of your presentation without forcing them to leave the Zoom environment (and potentially get lost on the Internet).
  cta:
    enabled: true
    url: https://github.com/soerenetler/ZoomViz/releases/latest
    button_text: 'Download '
  image:
    image: "/uploads/chattarize.PNG"
    alt_text: Chattarize in action
  background_image: "/uploads/hero-2-bg.png"

- template: content-feature
  block: feature-1
  media_alignment: Left
  id: features
  headline: <strong>Save</strong><span class="light">&nbsp;Zoom chat</span>
  content: Save the chat from the Zoom meeting. This can be done in the chat panel above the input field. Click "..." and "Save Chat".
  media:
    image: "/uploads/save_chat.gif"
    alt_text: Save Zoom chat

- template: content-feature
  block: feature-1
  media_alignment: Right
  headline: <strong>Choose</strong><span class="light">&nbsp;Zoom folder and meeting</span>
  content: Zoom saves the chats & recordings in the Zoom folder normally located in the Documents folder. If it is not automaticallly detected, please select it. Afterwards, choose the meeting you want to visualize. The current / most recent meeting is pre-selected.
  media:
    image: "/uploads/folder_meeting.png"
    alt_text: Customize Blocks

- template: content-feature
  block: feature-1
  media_alignment: Left
  headline: <strong>Choose</strong><span class="light">&nbsp;chat marker</span>
  content: Only messages with the chat marker in the beginning are visualized in the Chattarize wordcloud. You can define one chat marker per question you pose to your audience.
  media:
    image: "/uploads/method.png"
    alt_text: Customize Blocks

- template: content-feature
  block: feature-1
  media_alignment: Right
  headline: <strong>Enjoy</strong><span class="light">&nbsp;the visualization</span>
  content: You can simply refresh the wordcloud by saving the chat again.
  media:
    image: "/uploads/wordcloud.gif"
    alt_text: Customize Blocks

- template: signup-bar
  block: cta-bar
  content: <p><strong>Stay connected!</strong></p><br><p>We will keep you infonformed about new features and everything around Chattarize!</p>
  email_recipient: xyynnnrd

- template: content-feature
  block: feature-1
  media_alignment: Left
  headline: <strong>That's me</strong><span class="light">&nbsp; - Sören</span>
  content: "I develop Chattarize as a side project. If you have any ideas for improvements, let me know: Either create a github issue or send an e-mail to hello@soeren101.de"
  id: team
  media:
    image: "/uploads/me.jpg"
    alt_text: Customize Blocks

- template: simple-footer
  block: footer-1
  content: Built with ❤︎ in Golm <br/> <a href="/imprint">Imprint</a>

---
foo bar