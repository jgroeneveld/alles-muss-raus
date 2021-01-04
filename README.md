# Alles-muss-raus

Super simple static website creation.

Bash script in `script/build` takes html files in `layout` and executes mardown for pages in `pages` and puts everything in `public`. Also copies whole `images` folder. Deployment via vercel. Install dependencies by hand, its simple, who cares, done is better than perfect.

## Dependencies

```
brew install markdown
npm i -g vercel
```
## Commands

```
script/build # build into public
script/serve # run php as a local webserver for convenience
script/deploy # deploy via vercel
```