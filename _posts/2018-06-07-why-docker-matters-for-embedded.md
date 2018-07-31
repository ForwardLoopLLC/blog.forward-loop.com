---
title: Why Docker Matters for Embedded Development
---

Here at Forward Loop, we use Docker for building and running embedded applications. For development on Linux ARM devices, like Orange Pi or Raspberry Pi, Docker standardizes your build and run environments. So what does this mean and why does it matter?

Using embedded Docker images, developers can push and run the same code across all different types of devices. Docker images abstract away these differences. We show an example of this in action [here](https://www.youtube.com/watch?v=rT3D8THxBn4&t=1s) using our [floop cli tool](https://docs.forward-loop.com/floopcli/master/index.html).

In this video, Nick pushes and runs the same Hello World applications in different languages across different boards, operating systems, and ARM architectures. Instead of building applications for each specific operating systems, running on specific boards and architectures, using Docker images, you can generalize code so that it runs across types of devices in a way that is easy to understand.

You can try embedded Docker on [Forward Loop Zero](https://forward-loop.com/developer.html) using floop cli tool[floop cli tool](https://docs.forward-loop.com/floopcli/master/index.html).