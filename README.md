# Alles-muss-raus

Super simple static website creation.

Bash script in `script/build` takes html files in `layout` and executes mardown for pages in `pages` and puts everthing in `out`. Also copies whole `images` folder.

## Dependencies

```
brew install markdown
npm i -g vercel
```
## Commands

```
script/build # build into out
script/serve # run php as a local webserver for convenience
script/deploy # deploy via vercel (but it also is linked as github repo hook)
```