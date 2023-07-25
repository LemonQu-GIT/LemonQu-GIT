What happens every day:
``` cpp
// Daily situations
if (self.studying.status == true){
    studying.interrupt();
    studying.status = false;
    self.encourage(event.play_computer);
} else {
    self.encourage(event.play_computer);
}

if (parent.angry.status == true){
    self.sad(parent.angry);
    self.studying.status = true;
}
```

![Metrics](/github-metrics.svg)
