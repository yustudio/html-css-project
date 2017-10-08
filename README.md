# HTML & CSS sandbox

## Setup
To get started:
```
git clone https://github.com/matt-tingen/html-css-workshop.git
cd html-css-workshop
git checkout -b wiki

npm i
npm start
```
This will start a server which will auto-reload when changes are made.

## Images
Images used on the page are provided in the `public/images` folder. They are served automatically by the provided server. As such, they can be included with simply `<img src="/public/images/node.png">`

[Font Awesome](http://fontawesome.io/) is included for icons. Use them like so:
```html
<i class="fa fa-user"></i>
<i class="fa fa-external-link"></i>
<i class="fa fa-cog"></i>
<i class="fa fa-pencil"></i>
```
