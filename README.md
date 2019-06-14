# Hiring Process

This process is centered around having an open conversation with someone who is interested in workin with you and finding someone who shares your culture and believes in the way you and your team looks at engineering.

## Nomenclature

For the sake of understanding and binding this into some sort of a process, I am using these terms through my explanation which could mean different things for different people and positions -
* *Hiring Manager* - A person who initiates and decides on the the hiring process. This is usually an engineering manager or a director who is hiring. This could also be a developer looking for another developer to work with. This could be product, business, marketing - any role that will decide which engineer they want to work with.
* *Senior Developer* - When I say senior I do not mean someone who has the title of a senior developer or has been around longer. Someone whose seniority comes from a hiring perspective. Someone who can judge where lapses in knowledge might lie, where training on the current stack might be required, someone who will handle onboarding for this soon-to-be hired engineer and will teach her / him the ropes.
* *Technical Recruiter* - Someone who is non-tech and is a good judge of soft skills. This could be the founder of the company who is a Product person or the Business head who wants to help hiring engineers in a small startup.

If you have these three roles, sometimes could be played by two people as well, hiring could move ahead smoothly. Also, to note, that I usually dont like the idea of one person hiring if there are more people who will be working with the person being hired.

## Prerequisites

I usually maintain a board to track candidate statuses and upcoming interviews. The swim lanes denote the statuses or rounds of interview. We also have statuses in between like Waiting to Send coding challenge if there is a delay between these two or if someone else is supposed to pick it up and send it from this column. Each card / entity on this swim lane is a candidate name - using something like Trello or Asana or Notion lets you add details to the card so that the next person looking at this card knows what the process so far has been.

[Candidate tracking board](./Candidate-tracking-board.md)

## Screening

Screening starts from the time a profile is available as a potential hire. This could be a LinkedIn link, an email forward with a resume (referral or recruiter) or someone applying via our website. All the resumes land up on this Trello board

From here we discard the ones we don’t really want to move ahead with and put them in the rejected column. This column right now serves as reference for candidates who have applied in the past and want to apply again.

All the candidates we choose to move ahead with, we move them to the Get-To-Know column and usually HR or someone from the team emails them to arrange for a phone call. This process is automated by setting workflows on these columns or adding watchers for statuses.

## Get to know the candidate

This is mostly a casual chat, we pair up one senior hiring manager and someone who is new to hiring to sort of get a balance. This part of the process is to build a relationship with the candidate. The HR usually is part of this but in the absence of a technical recruiter, a developer can pick up the baton.

This part of the interview is not about putting the candidate under pressure but finding out more about what they do; how their work life looks like, what motivates them, what excites them about work, what kind of problems do they like solving, what tech stack do they work on, how does day-to-day tooling look like, open source projects or hobby projects they work on etc: some of the questions for this round of interviews could be found [here](./questions/get-to-know.md)


## Coding exercise

In this part of the process, a candidate interviewing for an engineering position gets to show us some of their coding skills. There is a growing list of coding challenges I have documented [here](./questions/coding-exercises/). These are divided into multiple categories and skill levels - however, this is highly subjective and sometimes I mix and match questions based on what I want to find out or attest. Hence, it is very important to have one senior developer / architect in the first round of interviews to be able to select the right coding challenge to send.

The list of coding challenges is in no way meant to serve as a guide. It is a collection of resources and hence is amenable. Please feel free to send custom challenges if you think so and add them to the collection for others to use. Also try and explain the persona the challenge is supposed to test and what the reviewers should be looking for when evaluating the challenge.

When sending a coding challenge, there are a few guiding principles I use:

- always ask the candidate to use a git repository and share **a private repository** with us. They can choose to make it public after the interviews are done
- do not try to sound smart or belittle the candidate (even when hiring freshers or junior engineers) when sending coding exercise
- be truly cross functional and encourage the use of languages, techniques, frameworks a candidate is comfortable with. There are cases when one needs to hire for specific frameworks and language requirements, but in all other cases we should try and be flexible when hiring (diversity is strength 🙂 )
- give enough time for the candidate to take this exercise. Usually I ask the candidate when they would have 24 - 40 hours available to take this challenge at home and mostly the answer has been Friday evening (😕 developers). Send the email then. You can find a sample email [here](./communication/invite-to-coding-exercise.md)

## Coding challenge

This is the part where a candidate gets to explain the exercise and defend it against questions of scale and architecture. There are many ways you could approach this particular part in the process based on the talent you are hiring and the position you are looking to fill. The coding challenge could be engineers pouring over the codebase and coming up with questions to ask or managers and architects going through the code and looking for parts where an engineer should have been more methodical.

I prefer to always have this part of the process as a face to face. It could be a video call if the candidate could not be physically present in the office or if you are looking for remote positions only. If you are looking to hire for a physical office then this part of the process is a great time to invite the engineer and let them soak in the culture at work. They get to talk to fellow engineers about code they have written and face questions, they can get a coffee in the office pantry area and also get into small chats with product management and UI/UX (in case of QA, front end engineers etc:)

Please keep this civil and do not try to humiliate the candidate. If the coding exercise was really bad, reject the candidate before the coding challenge.

Coding exercise and challenge are supposed to flow into each other, try not to have a long gap between the two since you and the candidate can both lose grip on the context. Also, a coding exercise is only as good as the problem definition. Be explicit if there are patterns you want to test in your exercise, if you want candidates to not work with a framework or create their own event bus or an observable pattern, please mention in the exercise sent. An open ended vague exercise often ends in a generic implementation.

Also, I prefer this to having someone code with their screen shared. If I want to test how good a developer is under pressure, I would employ better simulations (hint: swordfish)

## Technical skills / soft skills interview

This part of the process depends on the preceding parts. Usually, you are left with further questions about technical skills or soft skills that a candidate brings to the table. More often than nought, you want other teams to talk to the candidate and get a perspective on how working with them would be. This is the right time to have a face to face conversation with the candidate and ask about how they interact with other engineers in the team etc: Also a good time to talk to managers about other operational stuff they take care of. Good time to ask devops about development and developers about operations and what the definition of done is for them and how they look at quality and testing.

Again, have an honest chat with the individual. Take questions between the interview and not at the end; it helps it make more like a conversation than an interview. Set the tone of a friendly work environment. The candidate will get this feeling when he/she joins the company and becomes a part of this culture when they talk to people about you.

This round could also be skipped if you are really sure about the candidate and want to move ahead to make them an offer.

## Making an offer

I prefer to give a timeline for the offer on the table. This could be extended depending on what the notice period is for the candidate and how they have fared in the last few rounds. A deadline with an offer shows some urgency but for some senior positions could also be off-putting. The hiring manager should decide this. As a general rule of thumb, if both you and the candidate have enjoyed this process, this should be a no-brainer and after making an offer, the candidate should accept it within a stipulated amount of time. I usually extend it to cover one weekend so you could think it over in peace.

Some general pointers -

- always send feedback within 48 hours. Its unprofessional to have the candidate waiting for a response from you for over 48 hours. The only exception to this is the first communication that goes out after you have received the profile