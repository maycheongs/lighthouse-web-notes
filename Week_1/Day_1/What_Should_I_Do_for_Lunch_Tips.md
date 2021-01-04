### Tips

Try experimenting with the comparison operators (`<`, `>`, `===`, etc.) in the node REPL, which you can launch using the `node` command in Vagrant.

Work on your code iteratively – that means in small pieces. 

To help you figure out how to use `hungry` and `availableTime` inside your function, try outputting their values to the Terminal as follows.

```javascript
const whatToDoForLunch = function(hungry, availableTime) {
  if (!hungry) {
    console.log('You\'re not hungry, wait a little!');
  } else {
    switch (true) {
    case (availableTime <= 20):
      console.log('Grab a quick bite in the kitchen!');
      break;
    case (availableTime <= 30):
      console.log('You deserve a break. Maybe try a place in Gastown?');
      break;
    case (availableTime > 30):
      console.log('You\'ve got plenty of time, maybe start on a stretch exercise? Its bootcamp after all.');
      break;
    }
  }
};
```


