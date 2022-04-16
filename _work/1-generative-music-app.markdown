---
layout: page
title: 'Generative Music App'
description: 'An overview of my third year dissertation project, a generative music application. Written and devloped in Processing3 & Java. Evaluated qualitatively. Documented up in a formal report and video presentation.'
banner:
    src: '/images/generative-app-screenshot.png'
    alt: 'A screenshot of my generative music app'
    caption: 'A screenshot of the code and the app running side-by-side'
---

### Project Overview

Generative music describes an indirect form of music creation, wherein the composer sets parameters by which the music will generate itself. I made a video presentation as an overview of the development process, I hope it does a good job of getting across how I went about making the app and the thought processes behind the approach.

<iframe width="100%" height="400" src="https://www.youtube.com/embed/0WWOrIHrOho" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

If you have the time I would recommend checking out the report I wrote which goes into a **lot** more detail. Please [read or download](/assets/documents/generative_music_report.pdf) it, and possibly, enjoy it.


### Project Goals

The main goal of this project was to create an application that would allow a user to make generative music in real time, without overwhelming them with complex terminology, intimidating them with alienating interfaces, or confusing them with excessive detail.

The secondary goal was to fully leverage the language and IDE the application was built in, Processing (specifically Processing 3), by utilising as few external libraries as possible. This was decided so as to demonstrate the level of functionality that can be created ‘from scratch’ to new developers using Processing, and to reduce the complexity in sharing the project with others.

Overall, as this project was rooted in a human computer interaction student’s perspective, the focus was on creating a set of user experience outcomes; for app users, and potential  Processing developers, rather than a radical technological exercise.

### Development Process
The best overview of the development decisions within the project can be found in the video screencast which was presented as part of the final project presentation.

Throughout the development, multiple different UI designs & app functions were tested with different users. Through both formal and informal questioning and interviews, the design of the app was improved and refined, with a focus on rapid iterations to incorporate as many ideas as possible.

### Evaluation

A series of participants were asked questions in a semi-structured intervew formation, in order to elicit themes around their experience of using the application. The questions were designed to conform to a qualitative approach, and an attempt was made to interview users with a range of experience levels.

After the interview process, themes were identified and, quotes were pulled in order to explain the strengths and weaknesses that user's had identified. The wide range of **user experiences** really interested me, and being able to understand the relationship between my design decisions and their eventual feelings towards what I had made was a really interesting process. I would like to do more of this kind of work in the future, as I felt the ability to tease out information from conversation is a really important skill to develop and employ.

For more on the evaluation process, I again recommend [reading or downloading](/assets/documents/generative_music_report.pdf) the project report, which contains links so you can see the relevant sections, as well as transcripts of the interviews.

### Improvements

In the future I would like to do a few more things with this project. Namely to vastly improve the **accessibility** of the application by implementing better options for contrasting colours, as well as user selectable colour schemes for colour blindness. I would also make it possible for the user to resize the elements of the application, as well as the app window itself - although this would require a more thorough understanding of Processing's draw() loop.

Another larger scale change would be to port the project to use Processing's JavaScript language. In doing so it would help to both solidfy my JS skills, and also make the application itself easier to access; as it would no longer require a user to download it & ensure they have the correct version of Java.

### Conclusion

I believe this project demonstrates a few key things.

- An ability to see something through to completion

- To develop with a final user in mind

- To quickly learn new skills & technologies

Although the end functionality of the app is specific to the domain of music generation, the process of making it taught me a far wider range of skills, generalisable to more than just this topic!


### Your Turn!

You can download and unzip this exported project as a Java app in a few flavours:

- [Intel macOS app](/assets/files/mac/app_apple_intel.zip)

- [Apple Silcon macOS app](/assets/files/mac/app_apple_silicon.zip)

- [Windows exe](/assets/files/windows/app_windows.zip)

- [64-bit linux](/assets/files/linux/app_linux.zip)

- [32-bit Raspberry Pi](/assets/files/linux/app_32_bit_pi.zip) / [64-bit Raspberry Pi](/assets/files/linux/app_64_bit_pi.zip)

Or [browse the app's source](https://github.com/TrueHeresy/Portfolio/blob/main/Generative%20Music%20App/macOS/source/v1.java) to see how it all works under the hood. 

*A couple things to note*:

- If you don't have a **Version 17 Java JDK** installed already, you will need to [download and install](https://adoptium.net/temurin/releases) that for your system.

- You will most likely need to override some security warnings. That might be worrying, but I *promise* I'm not trying to mess up your computer.