## This is the transcript for Episode 18 of the Sustaining open Source Design podcast

This episode Eriol and Guest host Kelsey from [Superbloom, formely Simply Secure](https://superbloom.design/) are Joined by Saide and Lucie of [I2P](https://geti2p.net/) and [Saptak](https://saptaks.website/) to talk about how designers and developers collaborate in OSS project communities.

You'll find URL links at the bottom of the transcript document under the next heading.


**Richard L  0:00**

Let's go.

Hello, and welcome to sustain open source design this to sustain our design? No, it's the same open source design. Yes sustain open source design SOS.

**Eriol  0:30**

Hello, and welcome to the sustaining open source design podcast. This is where we talk about everything to do with open source software and design and sustaining it for the long haul. And all of the different complexities about being a designer on open source and being a developer in open source. And how do these two entities collaborate and work together? 

That's the focus of the conversation we will be having today. A really exciting one that isn't often talked about. How these two functions interact with each other in open source. Today, we have two hosts myself. I am Eriol Fox, hello. And a second host that we've not had before on the podcast is Kelsey. Say hello, Kelsey. 

**Kelsey  1:18**

Hello, I'm Kelsey UX designer, Simply Secure. 

**Eriol  1:22**

And we actually have a slightly different format to the podcast today. So instead of just having one or two guests from a particular project, we have a few guests from different projects, to talk about the topic of collaboration between designers and developers in open source software. Our first panelist that I'm going to ask to introduce themselves is Lucie. 

**Lucie  1:45**  

Hi, I'm Lucie, and currently working on the I2P project (https://geti2p.net/en/), which stands for the invisible Internet Project. And I'm a UX designer and researcher on the team. 

**Eriol  1:57** 

And the second person I'm going to invite to introduce themselves is Saptak. 

**Saptak  2:02**

Hey, my name is Saptak. I'm a Human Rights Centered web developer, I am currently contracting with freedom of the press foundation, I have been actively contributing and maintaining various different open source projects like our Onion share, accessibility project, Wagtail and open source design to name a few. 

**Eriol  2:18** 

And our last panelist for today is Sadie. 

**Sadie  2:21**  

Hi, everyone, my name is Sadie, I work on I2P, the invisible Internet Project. I've been working on putting together something called the usability lab. And my focus of my work right now is on UX and design in open source tools. 

**Eriol  2:39**  

So this is a topic which we have almost too many questions and too many kinds of topics to discuss around the ideas and processes and things that happen when designers and developers collaborate or do what is kind of often more traditionally called the handoff process within building software. 

So the first question that we have on our agenda today is how does design and developer handoff or collaboration work in your teams and your projects? And how did it get to be that way in your projects? So I'd like to invite Sadie to respond for us. 

**Sadie  3:18**  

Hi. So in our project, we have first of all, something that starts off more as a developer designer handoff. So design came a little bit later. And so we're a development, heavy project and free open source. And right now, Lucie and I are working on putting together wireframes. And we are handing this off to one person on our team who is the most comfortable with CSS and has the best sort of knowledge of the legacy code base. And so in that case, it's our website, specifically that we're working on. 

**Lucie  3:57**  

Yeah, so I joined the invisible Internet Project back around June or July, or summer. And when I first joined, I learned that I2P is such a technical project, it really helps to have a little bit of knowledge of the technical aspects in order to design effectively. And when I started out, I really didn't know much. One example of how this played out is we wanted to redesign the download page. And on the download page. There's not just a simple download button, there are a lot of other little buttons that went along with it. So it's very confusing as to what you're supposed to click on on what each one meant. And I didn't understand what those other buttons did. Because there was the signature key button and license key button. I mean, I still technically we don't, I guess understand them fully. But at the time he had no idea. And I had to ask Sadie, who I work with closely, and the developer on our team what these mean? And then what they're used for in order to create the most effective design that made the most sense. 

But I learned that we couldn't remove these tiny buttons, so we had to keep them. So how do you design no way where the download button is pretty obvious, that's the main thing you are supposed to focus on. And this small buttons don't detract away from the download button when that they are necessary and serve a purpose. So on team specifically, Sadie has served as a bridge between design and development, she kind of links me and our developer on our team together since we come from vastly different perspectives, and different skill sets. And Sadie she's been on the project long enough that she does have some technical understanding. Yeah, at the same time, she really understands the usability and design aspect of the project. 

**Eriol  5:52**  

So I really want to hear more about this bridge between design and development from Sadie's point of view. And also, I want to hear how you described a process, which was more developer to designer collaboration handoff, and then we'll follow up with some of Saptak's thoughts. So Sadie, can you tell us a little bit more about what it's like to be this bridge between design and development and how it is a little bit more developer led at the moment.

**Sadie  6:22**  

So the bridge building aspect of this comes from my background with I2P. And working with very closely with the developers doing PR originally, and having to understand how the protocol works, the software works the network, obviously, function. Also part of that learning is learning about code bases, legacy code bases, and also having very good information about the resources, the an open source, which I think are oftentimes very small and very strained to work with. So my kind of job between designers and developers is to accommodate the designers and to ensure that the work that's being done, can actually be implemented. Understanding, also, from a management perspective, what kind of time the very few people who can implement the design work on the team have, because we're often competing for resources in a team, our go between right now, the developer on the team, who's taking on the work that Lucie and I are doing, is also working on the protocol is also maintaining all sorts of things within the software itself. 

So I have to understand his time. And I have to balance expectations from a design perspective. With regards to the developer designer handoff, this, I think comes from the fact that the code came first, the product, the software came first. And so in my role with I2P, I was asked to do PR and to talk about I2P at conferences. And this kind of led me on this journey towards with usability and UX and UI considerations, especially for our new user onboarding, and adoption and sustainability. So I felt like I was dealing kind of with design in retro actively in a way. So we had very good looking software. But there were some improvements that needed to be made, specifically with new user onboarding, and taking into account things like accessibility. So that's what I am talking about when we refer to the developer designer handoff. That's the context. 

**Eriol  8:49**  

Yeah, that makes total sense to me. A lot of it's really familiar to me as a product manager in open source, like I'm both a designer and a product manager. And there are sometimes these amorphous roles within open source that kind of are like this facilitator translator roles between different functions. And they're quite difficult spaces to operate. And I find it particularly quite difficult because you have to know enough about the technical aspects as well as the design needs, and those kinds of things to be able to play this bridging role. And I do think that, personally, is a critical role within open source that needs to happen, either needs to be able to be done by multiple people, that either identifies developers that can be that bridge, or designers or product managers that will serve that bridge. So yeah, I think what you say, really shines a light on how important it is communication and understanding each other's roles. 

I want to give Saptak a chance to talk about whether anything that Sadie and Lucie said, any of those familiar to you and the projects that you work in And do you have anything else to add about how designer developer, handoff and collaboration works in the projects that you are part of?

**Saptak  10:08**  

Yeah, definitely. So like I said, one of the things that I liked was that since development came first and the designers had to learn a lot from how the actual software in itself works. So I have been in projects where there have been both kind of scenarios where we are starting from scratch, we already have a designer on board. And then it's really good, we can all start with the design process, and then go into the development thing. But also, it often happens that there is a proof of concept software already. And then we come to the design work. And often that one thing I have found, which is helpful, then we already have the software, it's always helpful to do some kind of user testing, before going into the designing part, because then you get to know the user stories that are behind and also like, okay, the things are there, the features are there, but why is the user not really able to find the things. So I think that really helps. So often, when I already have a proof of concept, and I want some designer to work with, we will both sit together, do some user testing. So we have an idea that, okay, these are the things or these are the features that are not very discoverable, or these are the user experiences that need a lot of improvement, and then we can start working from there. And yeah, that's why I feel like it's more of a collaboration than a handoff per se, because, again, it doesn't really end where like the designer finishes the design and hands it over to the developer. 

And then I feel there's always this yet another step when the development is finished that to do the user testing again, and to see whether the new designs really did improve the experience. And if not, then we go back to the design process again. So I think it's always in a bit of a collaboration way rather than, okay, I have done the design, my part is done. And then the developer is like, Okay, I just found out the designer, and this is what we get, I don't know if it works better or not. So I feel it's always good to have a collaborative kind of mindset where we do go through user testing, because I feel at the end of the day, the user is very important when we are making an user facing tool. So involving the user in the flow always really helps.

**Kelsey  12:22**  

It's so great to hear these perspectives, because this is resonating with me. And confirming all of these experiences that I've had recently, I was just on a very technical project like Lucie was talking about. And it's interesting to hear Lucie talk about this as well about how actually, the way to move forward in a project that requires a lot of learning was to really collaborate with the developer team. And so a lot of this work that Lucie is talking about, I have also done as well, asking, you know, what does this mean? I've asked like, can you explain how this works in the background, like what's actually happening here? What's the most important thing, just to get their perspective as well. 

And so having this, I found that using this developer knowledge is one way to gain this domain expertise that is so required when these projects are so technical, and furthermore, what Saptak is saying about how, you know, it's not just about handing over the designs, because there's other things that happened afterwards, like user testing. So handoff is not this event. But you know, this long collaboration that and Lucie is talking about starts from the kickoff meeting, or even before to get that background knowledge and Saptak is saying have continues through user testing. And it's important to close that circle. So it's not just a handoff point, but like a longer collaboration. 

**Eriol  14:04** 

I sometimes wonder if like one of the things that designers really bring to usually not just an open source space, but particularly in open source space, because of the more of the absence of designers within that space is this 'questioning' role. 

So why is that like that? So why is this 'code proof of concept' built in this way? Because I think we have this conversation a lot on this podcast about like, how does open source get built? And is there a way that it can be built more inclusively, more user focused, more, kind of more able to respond to the challenges that often come up in a lot of open source projects when they do kind of have a code first process or just a natural kind of way of growing? But it's almost like what kind of place are we in as an open source software culture at the moment where I don't think we're quite anywhere close actually to a process, which is more like design lead or user lead. And I do think at the moment, it is this challenge for designers and developers that are really interested in actually working together and collaborating and planning, doing, like the ways that work at the moment to do better collaboration. 

So hearing Saptak talk about doing user testing and design isn't just like this handoff process that I often kind of it is understood as, there's this kind of phrase of throwing design 'over the wall' that the developers and then that there is this wall. And I love that there are projects out there demonstrated by the guests that are doing more of this work together. Are there other challenges that you will have faced in trying to do this collaboration work? I'd love to understand whether there's any intricacies or particularly hard conversations are particularly difficult, or maybe even really easy parts of the process. When you're doing collaboration? Is it easier to have certain conversations rather than other conversations? Is it easier to have conversations when you show visuals? Is it harder to do research? Yeah, has anybody got any examples of good, easy processes or not so good, not so easy processes.

**Saptak  16:17**

So some of the not so easy processes, I guess I'll start with and then there are a few easy processes, obviously, there are different kinds of tools. The user facing tool can either be a website, or it can be, let's say, a desktop application, it can be a Android app, it can be an iPhone app, it can even be a command line tool, because let's face it, it's still being used by users. So command line tools also do need some kind of user experience and user interfaces. And I feel the some of the challenges that comes is often the restrictions that the developer faces, where the designer is often not very accustomed with the restrictions that they will face while coding up the things. 

So like, for example, when I'm using a website, I'm making and website, it's often very easy. And most of the tools these days are websites. So often, many designers will start from a mindset of designing a website, but let's say I'm making a desktop application, and I don't really have CSS that I can use, because of the tools I have chose to use, then a lot of the designs become maybe difficult to integrate. And that's something I feel that often comes up between the designer and the developer and I have had both happy stories and sad stories related to that. Like there needs to be some kind of compromise, because often we say when in web development and desktop application, it's said that always try to give the native design, like whether it be the native designs by the website, if it's not horrible, or even by the desktop application itself, because then most of the times the native designs always tend to be usable, accessible, and all the other human rights centered focuses that a design should have. But sometimes there is that gap. 

I feel that and I have had conversations when I'm working on a desktop application that, Hey, see, this design is very easy to implement if I was making a website, but maybe not so easy to implement, since it's a desktop application. And I have chose a particular tech stack because I have certain considerations based on the users, let's say they are very security focused. So I don't want to make my desktop application on some react heavy stack. So will want to use something very underlying like, Python or C++ or something like that. And in that case, it doesn't really have the same flexibility of CSS that we can use in a website. So those kinds of issues do happen. Sometimes similar issues also happened with websites in itself. Also, like, if I'm making a security focus project, or like a privacy focus project, rather often, the privacy focus projects will be used in a tool like Tor browser. And if they're using the safest security in Tor browser, then both JavaScript and SVG is disabled. 

So we always need to provide a design such that even if JavaScript is disabled, low feature is completely blocked, so that it doesn't affect the user experience completely. So if since it's a privacy focused tool, and if the user really wants to use it, without JavaScript, they should still have a way to do that. So those kind of I feel it's more like not a trouble, but more like a communication that needs to happen. And it's always good to have that communication at a very early stage rather than and that's again, why collaboration is important. Because if the developer sees at the very end when all the design has been made, and then you're like, hey, no, none of this will work because we want to support non JavaScript users as well. That's really not a good way to approach it.

**Eriol  20:02**  

This is super important. And I'm really curious to know, from Lucie's point of view, what kinds of things did you need to know? Or what kinds of conversations did you need to have with developers, possibly facilitated by Sadie in order to design solutions or responses to some of the problems that you had in I2P? And how do you work with that kind of set of I don't want to say restrictions, but like it is sort of restrictions, but it's like being able to work within those guidelines, maybe is the better way to say can you describe like your process of doing design around like something which might have interesting, complicated, or unknown parts of the process that you might need to discover through conversation with the developers or the technical teams? 

**Lucie  20:51**  

Yeah. Early on in the project, especially, I had a lot of questions, especially about the technical information, because that does affect that design. There are times where I would ask one or two questions to the developer on our messaging platform discord, hoping or expecting to get just like a short answer that kind of like sums it up very nicely, or, okay, got it. But our developer, he's very patient, and very thorough, some of those language can be academic in a sense. And I would get these long, winding answers that just went completely over my head, or would put me in a state of more confusion than I started out with. 

But it was really great that our developer was being so thorough, and obviously shared a passion for the topic, or the issues that I brought up. So one of the things that Sadie you had mentioned to me was that I'm good at asking the questions in multiple different ways. So I would ask a question, I get a long answer, still not understanding what it meant. And then I'd ask it slightly differently, hoping to get like a straightforward response. So that has been a part of the process of just really constantly reframing the question and drilling down to what you really want to know, in order to do the design. Because I don't need to know all the extraneous information that goes on the technical and developer side, I just need to know enough to do the design. And yeah, just understand it's part of the process to go developer has that style of giving a very thorough answer. 

So how to pick and choose what is pertinent to the design, but how to fill in your knowledge gaps as much as possible. 

**Eriol  22:51** 

I think at this point, I'd really like to invite Sadie to respond as that process is happening for Lucie. And she's because that is design work is asking those questions and refining where the intervention for designers, this is part of the design process. And I'm really curious because of what you said earlier Sadie about being this bridge between design and development and knowing enough and about the different areas to be able to balance things. Well, I'd love to have you fill in that kind of part of where you come in to facilitate. Do you facilitate conversations? Do you help the developers? Or have you helped the developers be able to communicate their technical aspects or the technical aspects more in a more accessible way? What part of this conversational process? Are you parallel Sadie,

**Sadie  23:43**  

I do facilitate the conversations between design and developer. And where I get involved, is when I can see that a developer is talking more about how the thing works, rather than how it's going to be used. And that is a very important thing to be able to narrow in on. And at that point, I can say, Okay, we're going over here now, we can stop. And in that process, I learned to facilitate better communication. We can only do it's good work from a design perspective, understanding security. So yes, CSS, we can't say use JavaScript. If somebody is using no script. We can't use SVG in our console in our software. We need to have security built into our design. We need to understand what's important to our existing user base, as well as trying to incorporate different UX considerations. 

And so most of the conversations that I end up having with Lucie are with our developer And then I kind of go back and I say, okay, see this and this and this, these are the things that we can focus on. And in doing that, it's helping everybody communicate better. And to make the best use of our time together. Because our resources are, as I've mentioned, a bit smaller, our time together is not as long as we might like it to be. Just knowing when things are going a little bit more into watching somebody describe a whole protocol and how it works. And I say, oh, no, we just need to understand where I interact with it as an end user. 

**Kelsey  25:33**  

So jumping off of what we've just been talking about. I'm curious now, with in this specific space, of security, privacy and Human Rights Center design practices, I guess, I'll speak directly to Saptak now, what would you like designers to know about the death processes, specifically in this space, versus other spaces, and then we'll move on to Lucie and Sadie well, and talk about what developers can learn and experience from design practices that encompasses human rights concerns.

**Saptak  26:13**  

One of the things that Sadie actually said that I really liked is that we developers often focus on saying more about how we are making the code, what is the protocol behind it, rather than focusing on the interaction with the end users. And I think this comes back towards something Eriol said, as well that, why does the OSS often not have the same kind of usability? In open source projects? That is mostly because many times the developer comes up with an idea they don't really think about? They do want to build it for the users, but they don't really focus on how the user is going to interacted with it. 

They always think it from their perspective, and they're often like, yeah, it's very obvious to me that I have to click this button, Why can the user understand I have to click this button. And when you ask them questions, it's always like, they will start describing the technical jargon behind it, rather than saying the user interaction. So I guess that's very important. And I have also been trying, like, talk a lot with designers to understand what kind of things we need to discuss with them. That's why I often try to be the facilitator as well. And I have been lucky enough to be in projects where the developers do care about the design and the user interaction. So it's often helpful. When they are showing us the design, we can obviously go and say, like, Hey, see, this is something that we need to do. 

Like I was saying some of the things that often comes up in security projects or privacy based projects is, we don't want to use JavaScript, or at least we want to provide a fallback if someone is not using a JavaScript. So that is often not the consideration that a lot of designers will take if they have not worked in a project like this. But if they have worked in a project like this, it comes very obvious with them as well. So it's again, I guess, more of a collaboration, the more you collaborate, both of the people learn another thing that I have seen. 

And I feel this is not just designer, but this is an issue with good designer and developer is like a lot of the projects don't really focus on accessibility and usability but more on making things look really good. Like, hey, it looks really slick. But did you really check if someone who has other kind of needs? Or who is using an assistive technology can actually use your tool or website? No? Or is it actually being usable by the user that you're wanting to target? No. So I think accessibility is another thing, or even just the entire usability, trying to test it with as many users as you can, including the people who are using assistive technologies. 

And in some projects, what I've done is I will go to the designs and I have come across this very interesting thing recently called Accessibility blue lines. So I found that really helpful. And this is a tool I feel which both developers and designers can use, what it helps to do is, let's say we have a figma design. And then it's more like a designer and the developer will sit together and use the accessibility blue lines to decide what are the different kinds of interactions that will happen by the accessibility. For example, if I'm doing a tab navigation, which are the points in the website that should have a tab navigation, what are the things that should come one after the another? Or let's say for example, where the focus should be going or if there is a color contrast issue, why is there a color contrast issue and other kind of all defining all the interactions if there is an input field on a form fill? How do they use it each there? So accessibility blue line I have found is very helpful for that. 

So I feel like there needs to be definitely like Eriol said there should not a world where you throw the design off, and then also the developer throws to laughs to another wall to the user. And then the user is like, I have no idea what anyone did. So it's obviously always very important that all these three parties collaborate a lot. Do user testings and understand each other's needs and know how to talk to each other I guess, and which is like designers always know how to talk to users. And for user testing, I feel often developers lack that part. And I think it really helps to often be part of the design process and see how designers actually design so that you can better communicate, see, this is the reason I can't be using this. Or let's say, it can be as simple as say, this is a filter, and this filter looks good. But because we have JavaScript, we can probably use this kind of filter in this place. And the user probably doesn't need it so we can do something other. So I think those kinds of conversations need to happen a lot more between the designer and the developer,

**Eriol  31:04**  

I hear what you're saying about design being understood as something that is limited. This idea of slick design, or good looking design isn't the entirety of what design is and it's sometimes hard to one talk to designers about saying that open source actually, especially open source security projects, actually require a different kind of design consideration. Versus like typical design projects, these kinds of ones, there are a lot more on aesthetics and things like that. It's the hard cultural thing to bridge. 

But I'd love to hear from Lucie and Sadie and see whether they have anything that they would like to talk about around design practices that encompass good security and human rights concerns. And then we're going to move on to a question about how open source is compared to private software projects. So if you Sadie or Lucie, if you'd like to respond to anything to do with design practices in security and human rights, and then we'll move on to the next question. 

**Sadie  32:05**  

In our experience with this security, specifically, with open source, our download process looks very different than perhaps other download processes. And so we have something on our download page where we have a signature, and mirrors and things of that sort, which I think can be very confusing to people who do not have dev knowledge, or do not perhaps understand that open source has built in trust mechanisms for the user, that they may be confusing. So you may not understand if you should I click the mirror? What does a signature mean? Where is this going to go? where's this going to take me. And so adding more definition, and having better processes within the new user onboarding to encompass some of those philosophies behind open source. And why we have those things in place is very important. 

Additionally, assumed dev knowledge within documentation is something that I am trying to address right now. Because this can become overwhelming. For many people, we often do our best to educate people, perhaps a little too much. Rather than simplifying the process, and making their journey to using the software, just the best and the simplest and most secure path for them. You can't overwhelm that's a problem with accessibility. 

And so we have done so much work over the last six months to make better steps towards accessibility, or people in that way. Additionally, when we simplify our language around those processes, one of the things that is very important to me is that language becomes more simple, more easy to understand. And then it can help our translators for localization efforts. In the end. This is one of the most important processes that I have worked on with I2P. And I think, will add to our ability to sustain the project for longer and obviously help our users help people who need us most and help with adoption. 

**Eriol  34:27**  

I love to hear that I love the simplicity is not seen as like a bug simplicity as a feature to use that kind of language. So simplicity means good for everyone and more accessible for everyone, including people that are reading in their second or third language or even doing that process of translation or even like coming to a tool like I2P from very much like a non developer non technical background previously like I need this tool to be able to do some important work or I need to be able to access this to do important work. And like, the focus should be on being able to use this and understand this versus user led way rather than a deeply, we keep using the word technical. 

And I have a personal problem with the word technical not being associated with design, because design is technical. But we have this like idea that technical work is the code or like the building of servers or something like that, that I guess when we talk about technical we mean, the stuff that requires implicit knowledge or learned knowledge of a certain sector or a certain practice, essentially. But yeah, I'd love to ask Lucie to talk about the differences that they have noticed within the collaboration process for developers and designers within open source compared to private software projects. And then we're going to wrap up because we're running out of time on this really important topic.

**Lucie  35:58**  

So the majority of my career early on, I've been in the private space, parents offer space. And this is my first time really collaborating on open source projects. And before one of the companies I was at was IBM. And two things really stand out to me on the differences between open source and private, and they are capacity and hierarchy. 

And what I mean by that is, at IBM, for example, on my chain, we had the capacity to bring someone in that were just specialize in a project management role. They set the deadlines, they delegated all the tasks and made sure the project was implemented and shipped, they had a bottom line to consider since there's a money making aspect, whereas on I2P, open source project, we don't have that kind of role. And part of it is of course, funding. And there isn't that money making aspect. And a lot of the people that work on the project, are hobbyists and volunteers. So this really affects the speed at which the project can be implemented. 

There's people on teams like IBM, where their job is to push the project forward. So there's just entirely different cultures, environments and motivations that affect collaboration and execution of the project. Also, in the past several years at IBM specifically, they really prioritize design, almost as much as engineering. They made a huge effort to hire many more designers and recognising the importance of it. And they have people at the top, which again, is that hierarchy, who can make the decision to prioritize that. 

So yeah, one thing that's great about working I2P is that there is less of a hierarchy. Everyone has a voice and has a say. But that does slow down the project unfortunately.

**Eriol  37:58**  

There's so much more that I would love to talk about. We haven't managed to talk about tooling, which is really a huge topic within the collaboration between designers and developers in open source. We haven't got time to cover that. Sadly, I would love to hear Saptak's response to any differences that they've seen or been part of between maybe private software projects and open source projects, we'll have to save it for maybe a part two of an episode at some point or a further discussion on this topic, because we need to wrap up, sadly, but I think this just goes to show how much there is to talk about how designers and developers work together on open source projects. 

So what I'd really like to invite each panelist to do now is to say where you can be found on the Internet, whether that's a website, whether that's a social media profile, and any final comments on this collaboration aspect between designers and developers. Can I invite Saptak to tell us where people can find you on the internet? And any last comments?

**Saptak  39:02**  

Yeah, sure, people can find me on the internet, I guess on my website, which is SaptakS.website. So it should be pretty easy. And I also am kind of active on Twitter, which is Saptak013. So that's where you can find me. And I just want to reiterate on the fact that developers and designers do need to work a lot more on collaboration. Like Ariel said, there should not be a world which you throw the design and development across. Rather, you always collaborate from the very beginning. That should make all the processes much more smoother.

**Eriol  39:35**  

And Sadie, where can people find you on the internet or about your project? So any last thoughts? 

**Sadie  39:40**  

People can find me on Twitter I'm just Sadie. And my handle is yrb1rd. I also manage the Twitter accounts and Mastodon accounts for I2P and the website is getI2P.net and right now we're working on launching the I2P usability lab. So this will hopefully provide a place for more discussion around how we can better facilitate conversations between developers and designers going forward, and also make some tools available for other people to make use of in their journey. 

**Eriol  40:20**  

And Lucie, where can people find you on the internet? And any last thoughts? 

**Lucie  40:23**  

People can find me? Live my website where luwuxu.com and thanks for having me on the podcast. It's been super fun to do this. It's my first time. And yeah, really, it was really great to learn about everyone's experiences, then relate to each other. 

**Eriol  40:46**  

We are so happy to have you. And we definitely need to have everyone back on another episode. Kelsey, where can people find you on the internet? And what you up to and any last thoughts? 

**Kelsey  40:56**  

Well, I want to take a moment to talk about the project that we're working on together, Eriol and myself. Were working on the USABLE project with the goal of creating resources for open source developer tool teams. And so we're especially interested in collaborating with developers on that and using design making resources that could help developers and designers work together. So look out for our current resources, which are out right now and future resources, which coming.

**Eriol  41:33**  

Amazing. Thank you all so much for spending time with us and recording this podcast. And we'll see you around on the internet on the next episode of sustaining open source design. See you all bye bye


## Links

[Open Source Design Twitter](https://twitter.com/opensrcdesign)

[Open Source Design](https://opensourcedesign.net/)

[Sustain Design & UX working group](https://discourse.sustainoss.org/t/design-ux-working-group/348)

[Sustain Open Source Twitter](https://twitter.com/sustainoss)

[Richard Littauer Twitter](https://twitter.com/richlitt)

[Eriol Fox Twitter](https://twitter.com/EriolDoesDesign)

[Eriol Fox-Simply Secure](https://superbloom.design/about/people/eriol/)

[Kelsey Smith-Simply Secure](https://simplysecure.org/who-we-are/kelsey/) - Link no longer active

[Saptak Sengupta Website](https://saptaks.website/)

[Saptak Sengupta Twitter](https://twitter.com/Saptak013)

[Sadie Twitter](https://twitter.com/yrb1rd) - Link no longer active

[Sadie GitHub](https://github.com/Shoalsteed)

[I2P](https://geti2p.net/en/)

[I2P Mastodon](https://mastodon.social/@i2p)

[I2P Twitter](https://twitter.com/i2p)

[Lucie Wu Website](https://luwuxu.com/)

[USABLE Tools](https://usable.tools/)

[Accessibility Bluelines](https://dribbble.com/shots/6269661-Accessibility-Bluelines)

### Credits
Produced by [Richard Littauer](https://www.burntfen.com/)

Edited by Paul M. Bahr at [Peachtree Sound](https://www.peachtreesound.com/)

Show notes by DeAnn Bahr [Peachtree Sound](https://www.peachtreesound.com/)
