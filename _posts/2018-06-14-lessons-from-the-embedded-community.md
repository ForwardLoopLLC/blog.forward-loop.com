---
title: How Do You Prototype Embedded Applications? Lessons from the Community
---

When we started building [floop cli tool](https://docs.forward-loop.com/floopcli/master/index.html), we reached out the our fellow developers through cold emails and LinkedIn messages. Over the past few months, we have spoken with hundreds of embedded developers across North America, Europe, and Asia. To start, we asked each developer one simple question, “How do you prototype embedded applications?” We did this to learn how other developers build new applications quickly and effectively. Along the way, we were amazed by how many developers responded with detailed feedback and best practice suggestions.

We distilled these conversations down to three major points that you can put into practice in your own embedded development today. Here they are:

(1) Be careful when you choose a microcontroller. You need to understand how the hardware, IDE, and toolchain can lock you in while you build your application. If you have the choice, go with the most affordable open-source hardware that you can buy at the scale of the number of devices you intend to deploy.

(2) Simulation can only test so much of your application. While simulations can help test application logic, developers should also spend considerable time testing on real hardware and infrastructure. These tests should range from coping with spotty network coverage to addressing hardware failures, to everything in between. Running your code on real devices in real-world scenarios is the only complete test suite.

(3) Portability is the holy grail. If you can write code one time and run that same code across all different types of microcontrollers, operating systems, and architectures then you can prototype faster. This means you should put considerable effort into making your drivers, libraries, and applications as modular, simple, and standard as possible. An ounce of API design at the start is worth a pound of reusability in the end.

Each of these three points from the embedded community influenced what we wanted to build and how we created floop. With floop cli tool, embedded developers can standardize how they push, test, run code on different devices while using their preferred tools and languages. We would love to hear more input from you on the best practices you use for prototyping embedded applications. Please comment below, or feel free to email us directly here.

Try floop on [Forward Loop Zero](https://forward-loop.com/product.html), hardware and sensors that make application development faster.