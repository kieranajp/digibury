These are the slides for a talk at Digibury, Apr 10 2013.

## Script: 

Hello, I’m Kieran, I’m a web developer here in Canterbury, yes this presentation is being controlled with an Xbox controller, and I’m here to sort of ramble on a bit about how we interact with computers.

So hopefully I don’t sound too mad when I say everyone knows what this is right? Almost every computer made in the past few decades has had a keyboard and mouse, it’s really become the de facto way of using a computer. It’s part of the mental image that comes to people’s minds when you mention a PC. And of course that’s not always been the case. And what’s to say it will still be the case in a few years’ time?

So, that’s half the subject of this talk. I want to gush about where these things came from and where they seem to be going - how we’re going to be interacting with computers in a few years’ time - because I find that really fascinating. But then I was thinking more about what people use computers for the most these days and I realised there’s a huge elephant in the HCI room - and that’s where the Web fits in to all of this. So this talk is also about how these changes in HCI relate to the web and how, hopefully, the two aren’t going to hold each other back too much.

So, the keyboard and mouse. Right now, you feel one of three things: familiarity, nostalgia or just sheer horror. And yes I am old enough to remember Lotus 123. And going back even further, way, way before my time now, this is how people used to use computers. I know I’d be super interested to hear from some of the guys in here who have some experience with punch cards; to me this looks completely alien. At the same time, I look at stuff we see in sci-fi, like this shot from Minority Report, and that looks pretty foreign to me too. And I kind of want it.

And I looked at this stuff and I realised that authors and the like can dream up this sort of shit, but actually we’re still mostly using the keyboard and mouse setup we’ve used for decades. I can look back to 1870 and see a keyboard very similar to the one on my desk today, and I can look back to Douglas Englebart’s original mouse prototype from the late ‘60s and again, see very little difference between that and the one I use for playing Crysis with. Which is probably not something he foresaw his invention being used for. 

There’s been this incredible period of stagnation. And sure that’s partly because the technology hasn’t really been there for us to do things like touch screens or to make Tony Stark’s interface from Iron Man, but I find this timeline pretty amazing, to see that we’ve stuck with the same input methods for so long. I’m just glad the rest of the computer has come on such a long way.

And sure there have been some blips along the road. The first TV remote control - 1956. In 1958, a “game controller” of sorts was invented for the game Tennis for Two - it was just one dial and one red button. In 1984 the first ‘pointing stick’ - those little nipples in the middle of laptop keyboards - was invented (Ted Selker). In 1989 Psion shipped a laptop computer with a trackpad. The PlayStation Eye Toy came out in 2003 - that was hugely ahead of its time. The Wii is notable enough to deserve a mention. And of course there are graphics tablets.

But it’s only recently that we’re seeing a change here that’s actually becoming ubiquitous in the same way the mouse and keyboard is: and that’s the touchscreen. It’s not perfect and it’s not everyone’s cup of tea, but it’s certainly a step in the right direction. And that’s pushed trackpad manufacturers to finally pay attention and try something new. Really natural feeling gestures like your pinch to zoom and your left and right swiping. Again they’re really not perfect, but I’m starting to see change.

Which brings us to the web.

Devices that can’t access the web arbitrarily are the exception, not the rule. ??? But while most of the web is designed for input with a mouse, we can’t count on having a mouse to use it with these days. 

Put it this way: If something really cool came out tomorrow that allowed you to control your computer with your brain, how horrible would it be having to reach for that mouse whenever you needed to Google something? What if you didn’t have a mouse? 

This isn’t restricted to some dream of brain control. Cool input devices exist today. And the web really sucks with them. Even with touch - the web tends to assume that you only need touch-friendly controls on phones. But what if you were one of the poor souls who brought one of these? No matter how optimised the operating system is for touch, you’re still looking at the same old web.

These days you can browse the web on an Xbox. Obviously you can plug an Xbox controller into a Macbook, too, or you can browse the web with a Kinect. But while the Kinect is really awesome in some applications like in this swooshy medical case designed so surgeons don’t get intestines on computers, using the web with one is just sort of awkward. Supposedly Microsoft are working on a way of embedding Kinects into laptops too, which is going to bring awkward web browsing to even more people, which would be a great tagline for their ad campaign.

Another method of input we seem to be moving more towards is audio. We’re finally at a stage where computers can reliably pick up what we’re saying, with Google Glass on the way - for anyone who doesn’t know, voice controlled glasses that can search the web, take photographs etc. - but try telling a device to click on a specific link or something with your voice.

And the Leap Motion and the MYO armband, which I think have a huge amount of potential. The first projects a three foot area above it, and whatever gesture you make in that area is transmitted to an attached computer. I’m super excited about this thing. The second lets you use gesture control from anywhere within Bluetooth range by wearing an armband.

Now the thing is I say the web would suck if you were trying to solely use this stuff, but with recent HTML APIs, getting all of this integrated with a website is not only possible but really easy to do. There are three new ways we can use JavaScript to make the web more friendly for someone using something other than a mouse, and one old way which is keyboard input. Considering that the keyboard has existed for longer than the web, it amazes me that there aren’t many sites that let you use keyboard shortcuts.

As for the newer methods: touch events allow web developers to detect not just taps but swipes, pinches and the like. The gamepad API allows you to bind gamepad button presses and stick movements to do pretty much anything - hence how I’m controlling this slideshow. And getUserMedia() - well, here’s a really buggy demo of how that works.

So getUserMedia() is a way of capturing user input from a webcam and/or the microphone. Here I’m only using the video - though it would probably be possible to make a slideshow that advanced when you shouted at it, too. And same as keyboard, touch and gamepad events can be used to do pretty much anything, the input you get from getUserMedia() can work arbitrarily too.

Anyway as hilariously bad as that demo was, I spent less than an hour getting it working. The point is it’s not difficult. And if I can do that and the Xbox controller input in one evening with just what I already have lying around and a bit of JavaScript, then think of what could be done with a little more time and effort by someone much smarter than me. And why go to that effort? Because you’re creating an enviroment that’s works in the same way the rest of the device does. People don’t have to abandon their shiny gimmicks when they come to your website. And besides, it would easily be possible to use this stuff to increase accessibility of a website or web app. 

I’m not saying that everyone wants to be able to wave at their webcam today, but what happens when Microsoft do bring out laptops with Kinects at the top, everyone’s happily waving their way through Windows, but as soon as they open their browser the experience just ends? What if the Leap really takes off and all your favourite apps work beautifully with it, but you’re still reaching for the mouse to click on a tiny arrow to advance to the next page in a website? Can you imagine a world where the web and technology are holding each other back?

It’s up to us web developers to stay ahead of the curve and be ready to embrace and prepare for change like this. It’s up to people and businesses who own websites and web apps to look critically at how they can improve them for touch input, and to keep looking at what’s next. And its up to web users, particularly those using touchscreens, and early adopters of things like the Leap to demand more from the sites they visit on the web, even if that starts with something small and relatively primitive like keyboard shortcuts.

And if you’re still not convinced then: what’s wrong with doing something cool, simply because you can?
