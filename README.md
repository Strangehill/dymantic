
I'm not sure how I set this project up but my goal was with this, at some point in the development of this, to use both react and styled components.
There are curious bits and pieces here that confuse me a bit and having not documented the setup process I can't say for sure whether all was intentional or accidentally succesful.
After all, the react button in js/app.js seems to work fine even though it appears I don't have an import statement for React in that file.
Yes, I've limited experience with javascript.

In order to compile styled components into browser code I use the following command:

`npx babel --watch js --out-dir build --presets react-app/prod js/app.`
which produces the following output in the terminal immediately (given that I'm writing code in app.js inside the 'js' directory whichis getting compiled to a file of the same name in the 'build' directory.
`js -> build/app.js`

I'm using a Python server:
`python -m SimpleHTTPServer 8000`

Deployment is as straightforward as `git push origin`

