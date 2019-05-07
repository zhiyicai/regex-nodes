# Regex Nodes

This is the elm rewrite of the [regex-nodes prototype](https://github.com/johannesvollmer/regex-nodes-js).
Currently barely usable.

# Build
Run `elm make src/Main.elm --output=html/elm.js`.
Also, see [compiling elm with optimization enabled](https://elm-lang.org/0.19.0/optimize).

Alternatively, use [modd](https://github.com/cortesi/modd) to run elm-make on every file save.

# To Do
- [ ] Example text for feedback
- [ ] Implement all node types
- [ ] Automatic node width calculation
- [ ] Middle mouse button view movement
- [ ] Reconnect replaced connections 
- [ ] Instantiate Nodes centered to the screen
      when reverting connection prototype
- [ ] Rewrite Css to Sass
- [ ] Build to Github Pages
- [ ] Node Groups!