---
layout: default
---

# My Raspberry Pi + NodeJS Journey

You may have read some of my blogs on Salesforce development and architecture, but this year I decided to embark on a new hobby: Robotics! So this blog will be a bit different than the ones you regularly read from me.

To start learning about this fantastic new world, I decided to purchase a few things on Christmas 2020 from Amazon. If you want to start learning about this beautiful world, I recommend you get a hold of these items:

- Raspberry Pi 4 starter kit comes with everything you need to get started (the actual computer, the micro SD card, and power supply). I got the 4GB RAM version. [Amazon.ca](https://www.amazon.ca/gp/product/B07XLMVYJJ/ref=ppx_yo_dt_b_asin_title_o05_s00?ie=UTF8&psc=1)
- Freenove kit has a ton of components and a book to guide you through. [Amazon.ca](https://www.amazon.ca/gp/product/B06W54L7B5/ref=ppx_yo_dt_b_asin_title_o00_s00?ie=UTF8&psc=1)
- My sight is not what it used to be, so I also had to get a 10X magnifier to see the tiny pieces. [Amazon.ca](https://www.amazon.ca/gp/product/B074C4D9TG/ref=ppx_yo_dt_b_asin_title_o01_s00?ie=UTF8&psc=1)
- [optional] An oscilloscope is indispensable to “see” the electrons flowing through the wires, but those things are expensive. A good one is at least a few hundred dollars. I was able to find this little device which is doing an excellent job for what I need. [Amazon.ca](https://www.amazon.ca/gp/product/B0892KBP7P/ref=ppx_yo_dt_b_asin_title_o09_s01?ie=UTF8&psc=1)

Once I had acquired these items, I was ready to start my journey and, let me tell you, it has been an incredible ride!

The Freenove kit that I acquired has a great set of components, and the projects are simple and work quite well. The concepts are incremental, starting with a simple LED and evolving to add switches and more advanced components.

I decided that if I wanted to learn, I would have to challenge myself, so I came up with a great idea: I will build the circuits they have in the book, but I will write the code using JavaScript (NodeJS). The kit comes with code samples in C++ and Python, and I can use those samples as guides.

This was a great idea because I have to fully understand the sample code they provide to rewrite it using JavaScript. The book has some essential explanations of how things work. But it does not go into a lot of depth. Sometimes they do oversimplify things, but having to translate the code to another language requires me to go into a lot of depth on the information provided and learn not only how it’s done but why it’s done. So the book, together with Google, has been a great educational experience!

But it was easier said than done, especially at the beginning of my journey. After a lot of research (trial and error and plenty of googling), I found a couple of good npm libraries named [RPIO](https://www.npmjs.com/package/rpio) and [PIGPIO](https://www.npmjs.com/package/pigpio) that work pretty well with Raspberry Pi and Javascript. So far, they have everything I need.

If I had to choose just one of those libraries, I would use PIGPIO because it has more features. For example, I have noticed that RPIO does hardware-based PWM, but PIGPIO does software-based PWM. Why is this important? It allows me to use more pins on the Raspberry Pi. That will be a topic for another post ;-)

There are other npm libraries. For example, [Johny-Five](https://www.npmjs.com/package/johnny-five) allows you to write simpler NodeJS code because it has one more abstraction layer. But this is precisely the reason I have stayed away from that library: it does too much hand-holding. I feel this would not help me learn as much, but it could help me later in some projects.

I will start the new series of blogs, sharing some of the knowledge I have acquired while working on some projects. So stay tuned, and join me in the discovery of this new fascinating world.
