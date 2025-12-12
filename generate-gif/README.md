# Commands to terminal recording and convert to gif

This is usefull to create examples to create documentations in markdown format

# Requirements

```$ brew install asciinema```

```$ brew install agg```

# Usage

```asciinema rec demo.cast```

After that, the recording starts, and all that you digited on terminal will be record. After you finished, press CRTL+d. This stop the recording. 

![find example](../images/demo.gif)

Now, you need to convert the cast file to gif

```$ agg demo.cast demo.gif```
