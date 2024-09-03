# Zine using modern CSS after 2024

I was not able to find a simple 1 page zine using CSS that didn't break when I went to go print it. Be sure to switch to **landscape** when printing.

I use:
* aspect ratio  8.5 / 11 to maintain zine pane size (useful for generating midjourney backgrounds with `--ar 17:22`
* grid layout
* img elements by default take up fill width of zine page
* zine page has overflow hidden
* zine uses *vw* font sizing for h1,h2,h3,p
* zine tries to emulate that 1 inch margin on most printers in screen media query

<img width="777" alt="Screenshot 2024-09-02 at 6 43 30 PM" src="https://github.com/user-attachments/assets/612accb8-75f9-4bf2-b740-8dc6a24fe52c">
