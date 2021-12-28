# Clone Coding: YouTube UIs

This project is to design the same UIs that YouTube is currently using to practice HTML and CSS skills.

## Wireframe

The wireframe was designed of the mobile view first. Then, it was considered to be responsive by changing the layout with minimal changes.
<br>There are 4 sections as below:</br>

- Header
- Player
- Info
- Up Next

<img width="600" alt="wide-screen-view" src="https://user-images.githubusercontent.com/57608628/147300517-28825c85-89ad-4cb8-9351-74fee712b5ab.jpeg">

## Player

In Player section, `controls` is used in the video placeholder. Also, `position: sticky` is used to place the video on top while the screen is scrolling down.

## Info

Info section has 3 different containers; _metadata_ that has information about the video (title etc), _actions_ and _channel description_.
<br>In title, `clamp` is used to only show 2 lines and JavaScript is used to make the more button toggled.</br>

## Layout

The site was designed with the mobile view first. When the viewport size is growing up, there was a lot of unnecessary space on the right panel so that HTML markup was edited to have a big box level that contains both _info_ and _upNext_ sections. Then, `Flex Box` and `@media` query are used to make minimal changes.

## Small view

<img width="600" alt="small-view" src="https://user-images.githubusercontent.com/57608628/147301357-1bc7faef-d941-44ea-ab79-489d8ed28cbc.png">

## Large view

<img width="600" alt="large-view" src="https://user-images.githubusercontent.com/57608628/147301441-5a96e42a-8eee-477e-aa84-211174bff400.png">
