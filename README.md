# [PyTexas 2023](https://www.pytexas.org/)

PyTexas is an annually held gathering for the Python community in Texas and is organized and run by community volunteers. The two day event consists of talks about software development, data science, and community, centered on Python. Following is a summary of attending PyTexas 2023.

This was a single track conference held at the Austin Public Library from April 1-2. There were about ~120 attendees from all over the world, from professionals in varying fields in industry and education. Most talks were thirty minutes long, with limited Q&A if time allowed. For more details on the presentations, see the Notes section below. Due to the state of the economy, there were no booths set up with sponsors, and networking was limited to speaking with attendees during breaks between speakers.

Shreya had the opportunity to give a lightening talk in which she discussed Azure Functions use cases and introduced the v2 programming model for Python. Speaking to the audience, she found that of the attendees, approximately thirty individuals had experience using serverless technologies, less than ten had experience using Azure Functions, and fewer had used Azure Functions in Python.

Overall, PyTexas shined a light on the character of the Python community. Though there were presumably over 100 people in the main conference room, it felt more intimate as attendees voiced their questions casually. Known qualities of the Python developer persona were evident, through the shared frustration of the language within the room and amazement at the solutions that were presented which significantly simplified development. For many attendees, it was their 5+ year attending the event, but there were also a fair share of attendees attending for the first time.

PyTexas would be a good conference for Microsoft to have a presence at in the future as the reach for a presentation would be to 100+ attendees, and there was space for education on Serverless technologies. Limited data showed that not a lot of Python developers at this event were Azure Functions users, but that they would be open to education. I hypothesize that smaller communities of language focused developers would be interested to learn more about Azure and due to presence from smaller organizations, it is possible that potential customers have a straightforward path to including Azure in their infrastructures.

# Notes

### _Walking the Line_ by Brandon Rhodes

This keynote was centered on how errors in code make Python developers feel. Brandon demonstrated how too much going right can lead to insecurity and doubt, if the code I am writing is really being tested. In contrast, too much red was made to impact developers to feel that the file was being read and so on. It was also pointed out that many times the errors that came up are not conceptual but regarding smaller things, such as which file is being read.

Brandon also empahsized how the goal is to ensure that you don't make changes that lead to a plethora of more changes - rather that developers should find the root cause and go from there. Furthermore, he pointed out a classic mistake that people think simplifying code doesn't always optimize it. Brandon, as well as many speakers through the conference also discussed Test Driven Development as a key principle to shipping better code.

### _Tale of Two Typings_ by Thomas Stephens

This was a talk about new processes that helped the team improve their practices. Thomas shared that "Legacy code is just code without tests", and went in depth regarding Type & Test driven development.

### _Hidden Gems in ML Flow that improve Model Credibility_ by Krishi Sharma

Krishi described the three gems that have changed her Machine Learning team's way of developing. Her tips were to:
1. back up your data
2. commit frequently
3. version your data

### _Exploring Sociotechnical Security Concerns in Critical Open Source Python Repositories_ by Jessy Ayala

During this talk, Jessy wanted to emphasize how many open source repoitories are lacking when it comes to security, and the importance of leveraging free GitHub extensions such as CodeQL to protect these repositories. He demonstrated some key issues by walking us through security risks on the vast number of open source reposiories for 3D printers, and the attacks that can be easily sent on these. Jessy pointed out that 99% of phishing attachs have human involvement and there is reason to be hesitant about secuirty vulnerabilities for open source repositories. 

### _A Build Engineer in a Buildless Lang_ by Joshua Cannon

Joshua gave this talk from the perspective of caring about the developer team's experience when it comes to following eingeering processes. He emphasized a case for having a mono repository, with the pros being easy collaboration and auto refactoring when required. Sophisticated tools are generally required when having a mono repository due to the amount of code that is in one place. He also shared his preference for Poetry and Black. 

The idea of the talk was that Python development is a social thing. if it wasn’t, we would always write assembly. part of the reason we use Python is so it can be easy for humans to read.

### _Build Your Own Chat GPT_ by Lizzie Siegle

Lizzie demonstrated how to use Flask to make a Web App using the Chat GPT API. This is something Gavin and I were brainstorming to do with Functions as well.

### _Unlocking the Power of Health Data: An Introduction to FHIR and Python_ by Aly Sivji

Aly shared some key issues with health care and technology that exists currently. He explained that getting health data across facilities is not very straightforward.

HL7 was formed in 1987. It was the first attempt to create a common data interface standards for rapidly growing EHR and health information technologies.
EHR adoption increased but does it mean better outcomes?
system to create more documentation for patients and easily share with members of the medical team

### _Duck Typing, Metaclasses, & Recursion: Building a Generalized Deep Collection Type_ by Joseph Nix

In this talk, Joseph demonstrated how to build a deep collection that could handle a myriad of scenarios.

### How to Build and Ship More Secure Python Apps with Sigstore by Lisa Tagliaferri

Lisa started the talk explaining how at the Gum wall, lots of people stick their gum there but not many people take gum off to chew it, and this same thinking should apply to the packages developers choose to use. Many packages have dependencies and issues that should be considered and though through - public packages should not be blindly trusted.

Note that PyPi and npm are both working on adding more security features, such as artifact signing through Sigstore.

### _HoloViz: Visualization and Interactive Dashboards in Python_ by Sophia Yang

Sophia discussed [Panel](https://panel.holoviz.org/) which is 'an open-source Python library that lets you create custom interactive web apps and dashboards by connecting user-defined widgets to plots, images, tables, or text'.

Sophia also hosts a book club for AI/ML books that is held virtually on Discord. Join the book club by signing up [here](book club http://dsbookclub.github.io/).

### _Using Python for Digital Investigations_ by Tristan Lee

Tristan works at Bellingcat, a non-profit independent research collective that was founded in 2014. THe organization participates in open source research.

what is a digital investigation

open-source research
research that uses information open to the public
investigator and consumer have equal access toinformation sources
increases transparency, accountability, reproductibility
many sources were previously only available to governments
there’s a lot of information on the internet
most common open source materials
google maps
CNN
YouTube
Google ebooks
geospatial, media, user-generated, databases& archived materials
Python tool: Social media scraping framework
Analyze the ecosystem of QAnon and adjacent online conspiracy communities in Europe
Collected lots of data
