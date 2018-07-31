---
title: What Does It Mean To Build An Industrial IoT Product?
---

We’re at a point where we can reflect on the product development process for MoldMonitor. For product development, the first 3.5 months of Forward Loop included pushing out a set of 6 prototype IoT sensors, and going through live testing in a production facility in China. At this point, there are some conclusions to draw about prototyping and building IoT sensors for industrial applications.

(1) To build a new IoT application with open-source hardware and sensors, there is an a lot of specialization. A single person needs to know many obscure facts in order to make low-level hardware, sensors, software, and cloud infrastructure work as a well-oiled system. At any given moment, an IoT application running on hardware has dozens of components that rely on each other to keep the system online.

On each layer of development, there are a subset of realizations that came from our product development. 

(a) Ensuring synchronization and standardization of code across all devices is a constant effort. We wanted to have complete synchronization across devices for our live factory test, and ensuring that happened took a lot of time to verify.

(b) Community support for open-source hardware is great for individual set-up tasks, so we decided to integrate many of these ideas into a our system. 

 At this point, we know building IoT applications faster means more modular low-level requirements, more portable software deployment, and more cloud infrastructure integration support. For us to build a more flexible end-to-end system, we know we need more dev tools to automate different components of this process. If anyone is interested in talking to us and sharing notes on dev tools, we'd love to chat.

### **Want to chat about embedded dev tools? <br/>Get in touch at [info@forward-loop.com](mailto:info@forward-loop.com)**