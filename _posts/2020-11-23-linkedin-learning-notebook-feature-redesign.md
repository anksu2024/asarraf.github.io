---
<!-- Date in UTC -->
date: 2020-11-23T10:00:00.000Z
layout: post
title: "Unsolicited Redesign: <br/>LinkedIn Learning Notebooks"
subtitle: "Let's make note-taking more effective"
description: >-
  My views after using the LinkedIn Learning Note taking feature
image: >-
  https://res.cloudinary.com/dm7h7e8xj/image/upload/v1559821647/theme6_qeeojf.jpg
optimized_image: >-
  assets/img/uploads/profile.png
category: blog
tags:
  - linkedin
  - learning
  - notetaking
  - notes
  - welcome
author: Ankit Sarraf
paginate: false
---
As of Nov 26, 2020, <a href="https://www.linkedin.com/learning/">LinkedIn Learning</a> is a melting pot for curious minds to explore over 15K Courses in its content library. It is surely an exceptional platform to start the scholarly journey for a plethora of topics offered in multiple languages.

Many organizations have realized the criticality of the professional growth of their workforce. Sponsoring unlimited access to a premium subscription of various Open Online course websites to their employees becomes imperative in such a scenario.

## My User Experience 10K ft. View:
For the past couple of weeks, I have been pursuing a few courses on LinkedIn Learning, and I have a positive review on the platform. This article in itself is the manifestation of my learnings from the courses I enrolled in.

> Before movinbg any further, please note that this article documents my opinions to make LinkedIn Learning a better self-development platform. Ideally, organizations give deep thought to the features to implement in order to facilitate the best possible User Experience. Nevertheless, in the real world, multiple technical, business, and financial constraints need to be respected leading to the prioritization of features that go live.

## Scope of this article:
For the purpose of this UX case study, I will limit the scope to Note-taking functionality.
I will be providing some suggestions on how it can be improved further.
Also, we confine ourselves only to textual notes taking that LinkedIn Learning currently provides.
## My motivation behind the case study:
1. #GoGreen: Lesser physical notes means lesser deforestation, reduced industrial water usage, and reduced plastic waste (pens).
2. #Inclusion: Economically struggling learners, don't need to spend money on Stationery.
3. #Digitization: Improved accessibility to notes stored online vs. physical notes.

## UX Case Study Process:
Before we dive into "why's" and "what's" of the case study, let's get the "how's" out of the way:

#### Define Persona
![Persona Image](assets/img/uploads/20201123/persona.png)
#### Exploratory Testing
I tried out 3 courses (References) on UX Designs to determine the usefulness and utility of the note-taking functionality.
#### Diary Study
I recorded my Qualitative and Behavioral Responses while Note-Taking.
#### Figma Designing:
![Figma](https://www.figma.com/file/qoAwkrOjUAIRxGBZzQNWUZ/Unsolicited-Redesign-LinkedIn-Learning-Notebooks)

## My Experiences in Details:
### Experience 1: Format preservation
<strong>Current Behavior:</strong><br/>
The text formatting for the notes isn't reserved.<br/>
<strong>Severity:</strong> Medium<br/>
<strong>Outcome of the above behavior:</strong>
* Hampered Readability of Notes.
* The user could switch to an alternate tool for formatted documentation.

<strong>Heuristic Principles to achieve:</strong> Retaining the structure will improve readability of the user's notes.<br/>
<strong>Utility of resolution: </strong>Medium

![Final_exp_1](assets/img/uploads/20201123/final_screenshots/final_exp_1.png)

### Experience 2: Auto-saving notes
<strong>Current Behavior:</strong><br/>
Unexpected loss of unsaved notes on the completion of video right before the Chapter Quiz.<br/>
<strong>Severity:</strong> High<br/>
<strong>Outcome of the above behavior:</strong>
* Frustrating to lose all the unsaved notes from multiple previous chapters and might have to revisit all those chapters.
* Hampers the progress of the course because the user has to revisit all the chapter.

<strong>Heuristic Principles to achieve:</strong> <strong>Heuristic Principles to achieve:</strong> Users can focus on the learning while reliably offloading information on notes.<br/>
<strong>Utility of resolution: </strong>High

![Final_exp_2](assets/img/uploads/20201123/final_screenshots/final_exp_2.png)

### Experience 3: Correct Reference to the point in time
<strong>Current Behavior:</strong><br/>
The reference link points to the time and lesson at which the note got saved.<br/>
```
Eg.
1. User starts taking note at 00:10 of the a video.
2. Submits at 00:05 of the second chapter.
3. The reference link points to the latter point in time.
```
<strong>Severity:</strong> Low<br/>
<strong>Outcome of the above behavior:</strong>
* User has to remember the part of lesson corresponding to the note to revisit.
* Inconsistency between the point when note-taking started, and the reference to the point in time depicted once note got submitted.

<strong>Heuristic Principles to achieve:</strong> This will ensure that the navigation to the correct part of lesson is intuitive and consistent.<br/>
<strong>Suggested Solutions:</strong>
* Auto-saving before beginning of the next lesson (At the end of 10 sec buffer).
* Record the time, and the lesson when the User enters the first letter in the text box.
* Note that this feature would require exhaustive A/B Testing.

<strong>Utility of resolution: </strong>Low

![Final_exp_3](assets/img/uploads/20201123/final_screenshots/final_exp_3.png)

### Experience 4: Press Enter to Save
<strong>Current Behavior:</strong><br/>
* There is only one option to save the note that by pressing 'Enter' to save.
<strong>Severity:</strong> Low<br/>
<strong>Outcome of the above behavior:</strong>
* Difficult editing of Multi-paragraph notes by using "Shift" + "Enter" for new line/paragraph.
* Users who are used to "Click Send" feature on LinkedIn messaging might not find this intuitive.

<strong>Heuristic Principles to achieve:</strong> Saving notes should mirror the Send button on LinkedIn Messaging.<br/>
<strong>Utility of resolution: </strong>Medium

![Final_exp_4](assets/img/uploads/20201123/final_screenshots/final_exp_4.png)

### Experience 5: Exporting Notes
<strong>Current Behavior:</strong><br/>
* Users can export consolidated notes at a click of button.

<strong>Outcome of the above behavior:</strong>
* This is a fabulous feature that could enhable downloading note for saving offline.
* Downloaded note can be edited offline (Text Format).

<strong>Heuristic Principles achieved:</strong> Exported notes are readily available even during an internet outage.<br/>
<strong>Why am I including this:</strong><br/>
* This is a great feature, and hence, deserves recognition.
* I missed observing this feature in the first 2 courses.

![Final_exp_5](assets/img/uploads/20201123/final_screenshots/final_exp_5.png)

## References:
1. <a href="https://medium.com/swlh/the-problem-with-unsolicited-redesigns-5c6d230354ed">Problems with Unsolicited Redesigns</a>
2. Courses enrolled in for this UX Case Study:
* <a href="https://www.linkedin.com/learning/ux-foundations-interaction-design/welcome">UX Foundations: Interaction Design</a> by <a href="https://www.linkedin.com/in/dhogue">David M. Hogue, Ph.D.</a>
* <a href="https://www.linkedin.com/learning/ux-design-1-overview-2/welcome">UX Design: 1 Overview</a> by <a href="https://www.linkedin.com/in/chrisnodder">Chris Nodder</a>
* <a href="https://www.linkedin.com/learning/ux-foundations-research/welcome">UX Foundations: Research</a> by <a href="https://www.linkedin.com/in/amandastockwell">Amanda Stockwell</a>
