### Tips

Try experimenting with the comparison operators (`<`, `>`, `===`, etc.) in the node REPL, which you can launch using the `node` command in Vagrant.

Work on your code iteratively – that means in small pieces. 

To help you figure out how to use `hungry` and `availableTime` inside your function, try outputting their values to the Terminal as follows.

```
// simple function to decide what to do for lunch
function whatToDoForLunch(hungry, availableTime) {
  if (!hungry) {
    console.log("Then get back to work!");
  } else {
    if (availableTime < 20) {
      console.log("Pick up something and eat in the lab");
    } else if (availableTime >= 20 && availableTime < 30) {
      console.log("Eat at a place nearby");
    } else if (availableTime > 30) {
      console.log("Remember you are at LHL and are here to learn");
    }
  }
}
```