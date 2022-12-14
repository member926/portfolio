# Instructions

## How to see changes on your machine

1. Add or change your content
1. Open terminal in VS Code (Terminal -> New Terminal) from the top menu
1. Make sure you're in the right directory (newport?)
1. Type `hugo server -D` and navigate to the url (probably `http://localhost:1313`)

## How to add your changes permanently

1. Navigate to project directory in the terminal
1. `git add -A`
1. `git commit -m "write your own message here"`
1. `git push`

Netlify should automatically pick up the changes and start the deployment process.

## How to add an image to a post

1. Put the image in your `static/img` directory
1. Place the image in your post with: `![self portrait](/img/metsfans.jpg)`.
   - **Make sure you leave off the `static` part of the path!**
