# audioviz-bars
Javascript audio visualization with frequency bar plot.

![Screenshot](https://i.imgur.com/l51Y6tq.png)

### Usage

```
<script src="audioviz-bars.min.js"></script>
<script>
audiovizBars({
  element: 'content',          // id of container html element
  audioPath: 'GroovyBaby.mp3', // local file path
  totalBars: 32,               // examples: 16, 32, 64, 128
  backgroundColor: "#231f20",  // hex, RGB or RGBA
  barsColor: "#f0ad00",        // hex, RGB or RGBA
  gapSize: 10,                 // pixels
});
</script>
```

### Notes

- Must use http protocol on live server.

[Demo](https://tomasantunes.com/audioviz/example/audioviz-bars.html)
