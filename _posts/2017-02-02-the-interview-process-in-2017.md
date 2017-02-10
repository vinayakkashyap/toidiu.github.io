---
title: "The Technical Interview in 2017"
categories:
  - Technical Interview
tags:
  - HR
---

At the beginning of 2017, I was interviewing for a junior back-end Scala position during which I had the privilege to interview with various types of companies including consultancy, startups seed/A/B and mature companies with startup ideals. The overall experience was pleasant and even fun, but there were also a lot more mishaps that I expected and a few that left a bad taste. However, I don't think the bad experiences were intentional but rather rooted in a lack of perspective from the other party.

I spent a major part of 2016 working my startup Wilfred (a Slack based Chatbot), which was trying to solve the problem of bad workplace culture. I therefore spent a lot of time learning about the different components that make up a company's culture and worked on trying to optimize them. So as someone who has experience being the interviewing candidate, while also having insight into a company's motivation, I hope to provide a unique perspective into the interviewing process as it currently is.

Finally, the goal of this post is to help both the candidates as well as companies improve the process of Technical interviewing and hiring. Despite it being 2017, I think the technical interview is still very lacking and can only be changed once expectations are set and mutually understood.

### The Interview Process
Most companies, with the exception of a few, had a very similar hiring process. I will expand further on each step from the perspective of a candidate as well as the company.

- Application
    + Hiring service (Hired/recruiter)
    + Custom application on company site
- HR Screen
    + Questions for the candidate
    + Questions for the company representative
- Technical Screen
    + Live coding exercise (screen share)
    + Home coding challenge
- On-site
- Offer
    + Mutual understanding
- Rejection


### Application
The important task at this stage is for the company to give a timely response.

###### Company
Getting a timely response back to the candidate is key. A delay of one or two weeks could mean the candidate might be nearing the end of the interview process with other companies. 

Tools like Hired.com can help make the process seamless because they explicitly communicate the role/salary/location preferences; which are important but static aspects and therefore less interesting when determining the ideal candidate.

If a candidate is applying via the careers page on your site, then this is usually a good indicator of their interest. A timely response in key to attracting the applicant and also a way to make your company stand out (from personal experience, it usually takes over 1 week to get a response). 

Regardless of the application platform, it helps to have a designated person assigned to each candidate throughout the hiring process.

###### Candidate
From personal experience, the most effectiveness ways for finding companies are:

- use a hiring platform such as hired
- companies which are involved/host relevant meetups
- find a recruiter who specializes in your area of interest


### HR Screen
Communication and mindset is the core skill that should be vetted at this stage. 

###### Company
The candidate should be able to speak about his past experiences with clarity. Asking the candidate questions about challenges, conflicts and mistakes in past projects shows how involved they were, how they approach problems/work woth others, and if they can communicate ideas.

###### Candidate
Since companies are generally testing your communication skills, the secret is to think about potential questions and write down the answers beforehand. The cool thing is that by doing this for a few sample questions, you will generally be able to answers a broader range of questions and speak about your projects in a more coherent manner.

> Note: Try to sound excited ('fake it' if necessary). Show that it will be a pleasure to speak and work with you. (I say 'fake it' because it's difficult to know what to be excited about if you don't know much the company.)

Here are some questions to expect and prepare:

- Tell me about a project you worked on and challenges you faced?
- Tell me about a mistake you made and what you learned from it.
- Tell me about a tough bug and how you solved it.
- Tell me about when you had an conflict with a coworker and how you dealt with it.
- What is your ideal position?

This is also a good time to get insight into a company's values and role. Here are some sample questions:

- What would be your ideal candidate?
- What is the % of time spent coding vs in meeting?
- What is the approx. size of the engineering team?
- What specific product would I be working on?
- What is the stack you are working with?


### Technical Screen
From the name, the goal at this stage is to vet the technical capabilities of the candidate. Two methods available are either `live coding (screen share)` or a `home challenge`.

###### Company
`Live coding` tests the candidates ability to **1)**write code from scratch (no IDE), **2)**understanding of Computer Science, **3)**approach to problem solving, and **4)**communication. 

Because we are focusing on basic CS knowledge and working with limited time, the problems should generally be domain-independent. A general rule should be to ask about things that don't require internet access. This code will probably not be production ready.

`Home challenge` tests the candidates ability to **1)**come up with a working solution, **2)**ability to organize code, **3)**write maintainable code, **4)**write tests. 

The coding assignment should ask the candidate to include design considerations, assumptions and ideas on future improvements to gain further insight into their thought process. This is the place to ask domain specific questions and test aspects that might be critical for the role. 

A time limit is a great way to access the candidate's eagerness. However, the limit should be at least 3-7 days because a robust solution takes time to formulate, code, revise, test, and explain.

###### Candidate
Approach to a `live coding` technical screen:

- list/confirm assumptions
- list out possible approaches
- analyze their runtime
- pick the best/appropriate solution
- write pseudo-code
- write actual code
- test the code (sample input, most critical logic)

Approach to a `home challenge`:

- formulate a solution
- architect a design
- write code
- write tests!
- write maintainable code (revise design as needed)
- explain design considerations, assumptions and future improvements
- code should aim to be production ready


### On-site
This process will often vary based on a company's priorities. While the company is the one dictating the schedule, I want to stress that this should not a on-sided operation. A candidate should try to imagine the average work environment.

###### Company
The vetting criteria could include technical, behavioral, communication, culture fit, and problem solving. The exact structure of this stage will depend on the priorities of the company so I won't go into this much more.

Since the company is dictating the schedule for the on-site, it is responsible for considering and giving value to the candidate. Two things to consider are 

1. Communicating the schedule in detail
2. Addressing other things the candidate needs to help make their decision

**1)** Below is a template of one of the most impressive schedules I received.

    Details:
    - Date: Wednesday October 21, 2015 7:28AM EST
    - Address: 100 Here St, NY
    - Please arrive by 9:50AM
    - Bring valid ID
    - Ask for Person 7 upon arrival

    Interview Roster:
    - 10:00am-11:00am EST: Person 1 (Senior Software Engineer)
    - 11:00am-12:00pm EST: Person 2 (Lead Engineer)
    - 12:00pm-1:00pm EST: Lunch w/ Person 3 (Software Engineer), Person 4 (Product)
    - 1:00pm-2:00pm EST: Person 5 (Director, Software Engineering)
    - 3:45pm-4:00pm EST: Person 6 (Recruiter)

    [Credit to iHeartRadio]

**2)** More impressively, it was followed by a call to explain the different people and ask what else I needed to help make a decision. In my case, I wanted to see a sample of the production code.


###### Candidate
There are two aspects to an on-site interview from the perspective of the candidate; technical assessment and company evaluation.

The `technical assessment` usually involves solving problems on a white-board, which can be difficult if not practiced. Specially difficult is organizing code and thoughts when solving a problem on a white-board. Try to follow a process for each process: 1)note input/output 2)note assumptions 3)write pseudo-code 4)write code 5)test via sample input.

The `company evaluations` is often overlooked because its less concrete but I believe it is more important of the two. The task is to image working at the company, along side your potential co-workers. Here are a few things to help paint that picture:

- Ask people why they joined the company and why they stay. Here you should be be listening for similar morals and sentiments.
- Ask to look at sample production code. It should look coherent, well tested, and something you would want to work on.
- Ask to meet with the people you will report to. Try to judge if they show integrity and if they are someone you can trust.
- Ask what you can expect to work on in the next year.
- Ask about how decisions are made. Are they made top-down, bottom-up, random, merit-based.. this give a lot of insight into the company and its values.
- Assess the technical capabilities of your potential co-workers. Will you learn from them? 
- Assess the work space/environment.
- Assess the commute time.


### Offer

###### Company
I don't feel equipped to make general statements about this section because compensation and benefits will vary from company to company.

###### Candidate
Congrats! During the interview process you should have built up trust and understanding with the company. This means that if there is something you think is unfair with the final offer, reach out communicate it. We tend to call this negotiating but I think that word has come to take on a negative connotation. I view it as reaching mutual understanding and finding a reasonable middle ground.

When deciding between different offers, simply list your priorities and choose the best fit. Some factors include compensation, perks, learning potential...


### Rejection
It is vital to communicate the decision in a timely and respectful manner. In my opinion, ignoring to do this step is absolutely unacceptable, rude and indicates bad character/culture of the candidate/company. As both parties should be aware, a lot of time and money are spent and to simply ignore or lead the other party on is bad practice.

Lastly, regardless of the outcome, both parties should view the interview process as building a new relation/network. Even if the other party is not currently a good fit, this can change in the future. A respectful and timely rejection is less likely to offend and keep the door ajar. If nothing else realize that the tech world can be a small place and people talk. 

