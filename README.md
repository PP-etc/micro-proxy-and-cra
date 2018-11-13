# micro-proxy and static website issue

in order to test it, run:
1. 1st terminal
```
npm start
```
2. 2nd terminal
```
npx micro-proxy -r rules.json -p 9000
```
3. open `http://localhost:3000/` - react app works
4. open `http://localhost:9000/static-website` - resources can not be loaded


how to make it work?

Here is the actual issue I have with `now`:
https://spectrum.chat/zeit/general?thread=7d017c0f-090a-4231-9380-72d28d584586