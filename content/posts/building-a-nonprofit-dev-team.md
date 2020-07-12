---
title: "On Growing a Nonprofit Dev Team"
date: 2020-05-15T10:29:35-07:00
featured_image: "images/growing.jpg"
tags: ["management"]
description: "Steps you can take to add highly skilled people to your team"
draft: false
---

# The Challenges

I have spent much of my career working in nonprofit organizations such as libraries, museums, and universities. Working in these organizations gives me a great sense of purpose. I know that I am contributing to efforts to make the world a better place. Working specifically in the technology departments of these organizations offers its own set of rewards and frustrations. On one hand, the technology in these organizations is often dated. Thus, there is usually plenty of low hanging fruit that can be addressed fairly quickly by a newcomer which earns the gratitude of other members of the organization. However, once those quick wins are done and the organization wants to move into more advanced projects, that same newcomer may encounter difficulty in forming a tech team capable of achieving those more ambitious goals.
 
Usually, the skillset of a tech team matches the tech stack of the organization. Thus, if the technology is dated, so are the skills of the tech team. The organization cannot realistically expect such a team to suddenly take on ambitious projects using new methods and advanced technologies. First, the team must undergo a modernization. My [previous post](/posts/modernizing-a-dev-team/) describes such an effort.
 
Alternatively, the organization may commit resources to hiring new members of the tech team. This is a wonderful position to be in, but ironically it can also be even more frustrating. Convincing talented software engineers, sysadmins, and other tech workers to join a nonprofit is very difficult. Salaries offered by nonprofits are usually lower than those offered by commercial organizations such as banks and retail firms, and they are much lower than those offered by tech firms.
 
If you are in a large metropolitan area, such as Los Angeles, which has offices for all of the big tech giants (Google, Netflix, Amazon, and more), then the market is just too competitive. I have never had a senior level engineer with experience in one of these companies apply for jobs at any of the nonprofit organizations I have worked with in the past ten years. As an alternative, I will often reach out through listservs to the communities of techies that already work in nonprofits and try to convince the most advanced members to come join my team. I feel somewhat guilty about this, as it is almost like poaching from my colleagues, who I know are facing similar challenges. However, this tactic almost never works anyway. The cost of living in Los Angeles is very high, and it has been near impossible to convince these senior level developers to give up home ownership in the Midwest or East Coast for an apartment in LA, which is about all they can afford on a nonprofit salary.
 
So, if advanced engineers do not apply for jobs at your nonprofit, how can you build an advanced tech team? In a word, be ***proactive***. Below I discuss several actions you can take. I recommend doing all of them rather than just picking one or two.

# The Methods

Building or rebuilding a tech team is like reviving a garden. First you assess what is already in the garden and your goals, then you take actions to transform it into your vision. This can involve nurturing the existing plants, purchasing some full grown plants from a local nursery, and growing new plants by planting seeds. It can also mean making environmental changes to the garden itself. And for long term success you need to ensure you are allocating the right amount of your time and resources to its success. All of these actions apply to your team as well.

## 1. Training

The first thing to do is work with the team you already have. Instead of hoping for an advanced engineer to walk through your doors, transform your current mid-level engineers into advanced engineers. My [previous post](/posts/modernizing-a-dev-team/) described my efforts to modernize my current team. Much of that described changes for the team as a whole. The training I refer to here is at the individual level.

### Assessment & Assignment

First, map out what your desired future system architecture will look like. Then determine what skills your team will need to acquire in order to build and support such a portfolio. Talk to your team members and figure out who has the aptitude and desire to learn each of the necessary skills and tools. Then create learning and skill acquisition goals to their annual performance reviews to reinforce the idea that this is a real goal, not something you mentioned in passing and which will be forgotten or deprioritized. 

My team uses a “Learning Goals” Scrum board which has 3 month “sprints”. Each team member sets quarterly learning goals by creating tickets and we review the progress of those tickets on the board once a week.

### Time & Resource Allocation

Simply identifying the needed skill and assigning it as a goal is not sufficient. Assigning a goal without providing an environment or time to achieve it is a recipe for failure. Education is an investment. If you want the payoff of a highly skilled team, you must make an up front investment and reduce your team’s workload to accommodate the time needed for training. You must state and respect that X number of hours will be spent on learning, not development. So reduce the scope of your team’s goals for the upcoming sprint, quarter, and/or year. 

And you must provide the necessary resources to facilitate their learning. There are lots of learning platforms out there for software tools and concepts and many of them are reasonably priced. My team tried out [Coursera](https://www.coursera.org/), but did not make much use of it. The catalog of courses is strong in CS theory but not practical skills. Instead, my team has been very happy with [Frontend Masters](https://frontendmasters.com/) and [Vue Mastery](https://www.vuemastery.com/) for the developers, and [Linux Academy](https://linuxacademy.com/) for the sysadmins, and [O’Reilly Learning](https://learning.oreilly.com) for everyone.

### Undisturbed Learning Time

Telling an employee to spend X number of hours a week on learning is rarely effective. They know that the actual development work is how they will ultimately be evaluated, no matter what you record in their annual performance goals. And they are constantly bombarded with email and chat messages from their peers and stakeholders asking them to look at code, bugs, attend meetings, and so on. The learning hours will always be postponed. As the manager, it is your responsibility to shield them from that bombardment and give them time for undisturbed learning.

My team has adopted a culture of “Learning Fridays.” We forbid all meetings on Fridays, except for the 15 minute daily standup (in the afternoon) in which we only look at the “Learning Goals” Scrum board and quickly share what each team member learned that day. We communicate this policy to our colleagues/stakeholders in the organization as well, so that they also respect the “no meetings” policy and do not send interrupting messages to the team’s various Slack channels (hold those thoughts until Monday). This standardization of dedicated learning time ensures the team has the time and mental bandwidth to actively learn. It is also a pretty impactful signifier of just how serious you are about the professional development of your team. 

### Foster Experimentation

When allocating time and resources, be sure to accommodate your team’s variety of learning styles. Not everybody learns the same way. Some prefer books, some like to read through documentation, some like video lessons, and some like to learn by poking, tinkering, and building. When it comes to mastering new technology, that last modality of “learning by doing” is often the preferred method and often the most effective. So in addition to providing time and resources, be sure to foster a culture of experimentation as part of the learning time. The experimental projects can be solo or group-based. Those group projects can be a “force multiplier” as it adds the benefit of diversity that a team gets from pair programming on top of the focus of undisturbed learning time.

## 2. Active Recruiting

Now let’s take a look at a scenario in which you and your administrators have determined that your team is too small to achieve your organization’s goals, regardless of the skillset of your team, and you have been giving funding to add new members to the team. You still face the challenges outlined in the introduction regarding the recruitment of highly skilled tech workers. Your HR department probably has a set list of channels through which they advertise your open positions. Do not rely on this kind of passive recruitment. To get the kind of people you want to join your team, you have to go out to where those people are and show them how great it would be *for them* to join your team.

### Personalize the Postings

You know your position has been advertised to your peers. You know the language in the job description is formulaic and dull. Well, then do something about that. You may not be able to convince your HR staff to change the official job announcement, but you can certainly let your peers know there is a lot more to it. Post a personal note to your professional listservs, Slack channels, IRCs, and so on. Describe the new directions you are taking the team, your vision for the future, the cool projects, materials, and people that the new member will get to work with. Let people know they can contact you directly to discuss the team, the org, and the projects. By breathing some personality and life into that boring job description, you will increase your chances of catching the eye of talented people.

### Network

Personalized posts to your peers in nonprofits is beneficial, but it does not help you cast a wider net. If you want to attract tech talent from the industry, you need to get out and mingle with those people. Go to tech meetups and get to know your peers from outside the nonprofit domain. This is just a good thing to do in general, for your own professional development and to keep up to date on new techniques and tools. But it is also great for recruitment. The time you put into making connections here will pay off down the line when you have an opening. But you have to invest the time up front. You cannot show up as a stranger and expect people to show interest in working with you. But if you are a known and respected member of the group, people will pay attention when you announce you have a position available.

### Show and Tell

Attending meetups is one thing. It will at least make your face recognizable. But if you really want to get value out of your time spent at these meetups, you should present on the work your team is doing. This can be intimidating. As mentioned at the outset of this post, nonprofits usually make use of dated technology, the kind that nobody wants to hear about at meetups. Meetups are usually about the latest and greatest things. However, there are two ways out of that conundrum. 

One, is to focus on the resources or services that your organization is providing rather than the technology. You will find that people who work for ecommerce or tech firms are often extremely fascinated by the projects you tell them you are working on. Let’s face it, working with cultural heritage resources and providing services that make the world a better place are both far more interesting than delivering ads online. 

Second, you can frame the presentation around how you are transitioning your technology stack and making use of the tools and techniques that particular meetup group is so familiar with. This will enable you to give a presentation before you have anything to really brag about. That, combined with the intriguing domain of your organization, can spark interest in potential candidates who see an opportunity to be a leader on your team and do something of great intrinsic value. If nothing else, you will likely get plenty of advice from the audience members about antipatterns and gotchas to watch out for as you adopt that new tool.

## 3. Teaching

For this third method, imagine a scenario in which you have tried the previous method of active recruitment, but still cannot convince advanced engineers to join your team. This is not hard to imagine. I have found myself in this position multiple times. At some point I had the realization that if I could not convince experienced software engineers to join my team in the library, then I should try going in the other direction. That is, find people already interested in working in libraries and teach them to be software engineers. This is significantly different from the training method discussed above. That was about levelling up or shifting skills for experienced techies already on your team. What I am proposing here is teaching non-techies from scratch so that you can then recruit them when you have positions available.

### Become a Lecturer

There are a few ways you can go about this. One is to actually become an instructor (Professor, Lecturer, etc.) at a local university or college. That is the route I took. When I couldn’t recruit engineers to work at my library, I began teaching technology classes at UCLA’s [Department of Information Studies](https://is.gseis.ucla.edu/), where future librarians get their Master’s degrees. I knew the department was interested in adding technology courses to the curriculum, so I introduced myself to the department head and offered my services. My first offering was essentially a crash course in computer science topics along with an introduction to programming. I also taught courses on web development and databases. I imagine something similar could possibly be done in a department of social work, public policy, urban planning, etc.

Perhaps the academic route seems daunting or perhaps your local campus does not have a department related to your organization’s domain. If so, you could also look into lecturing for one of the “coding boot camps” that have recently grown in popularity. I am not familiar enough with these programs to offer an insight as to how to get involved. However, I have seen many of them host meetups, so that seems the easiest way to introduce yourself and meet the person who hires instructors.

Aside from official lecturing positions, you could also become an instructor for less formal instruction, such as the [Carpentries](https://carpentries.org/) or a course of your own design. You can host a meetup for beginners and offer to teach an introduction to programming for people in your domain. You could even offer it to people already in your organization that are interested in picking up technical skills. 

### Build a Recruitment Pathway

No matter where you end up offering your instruction, keep in mind the goal is to eventually recruit skilled people to your team. So, in addition to teaching the tools and techniques you are looking for in a candidate, be sure to build a path towards employment for your best students. 

#### Paid Internships

The first  step is to offer internships. This will likely work better for the academic setting rather than bootcamps or meetups, since full time students are more likely to have time for an internship. ***Do not ask your students to take an unpaid internship.*** I have been in that situation in the past, and I feel awful about it. I am very happy that my current organization has agreed to a policy mandating that all interns must be paid. Work with your administrators and HR reps to allocate resources for an official internship or a limited term, part-time employee.

#### Structure the Internship

The internship should be well structured to give the intern valuable work experience and to hone their skills. An internship lacking in structure and guidance, or consisting of just “busy-work”, is of no value. That is true for any internship, but is especially true in this scenario, in which you are attempting to groom a candidate for hire. Don’t waste your time training them to do clerical tasks. If you want a future engineer, then give them engineering assignments. 

Ideally, you would just add them to your regular team’s Scrum meetings and standups and have them contribute to your team’s “real” projects like everyone else. However, since students usually work just a few hours a week, you will have to get creative if you want them to contribute to your primary projects without becoming a bottleneck. It may be best to carve out a side project that is non-blocking but still uses the same toolset and is appropriate for a junior level employee. Have them pair up with an advanced member of the team at times. This will greatly facilitate their learning and can challenge your senior level members by forcing them to answer questions about things they take for granted.

Be sure that the project is achievable within the timeframe of the internship. In addition to gaining skills, you want the intern to leave with a feeling of accomplishment. This will be a great confidence booster. And confidence is key when it comes to the growth of a new developer. There is so much to learn in technology. It can be very daunting when you first start out. Many of us who have been doing this for a while have forgotten what that feels like to be a beginner. We gain confidence with every new skill we learn and project we complete. Eventually we get to a point where most new tools and skills just sound like variations on themes we have heard before. We have no doubt we could learn to use any new tool that comes along. And that’s exactly the kind of confidence you should engender in your interns.

#### Bring them Onboard

As an instructor you will very easily identify the smartest and hardest working students. These are the ones you ask to become interns. At that point, you will also get a view into their interpersonal skills as they interact with your team. Ideally, you would have a vacant position open up just as the student graduates, but that obviously cannot be counted on. 

If you have a really great student you want on your team but no vacancies, then get creative and find a way to “create” a new position. Getting a new permanent FTE can be near impossible, especially for a junior level position. You may be better off trying to get temporary funding for a limited term position. This is a stepping stone for your student towards a permanent position. Look for opportunities in newly funded projects, grants, and initiatives. See if you can carve out a 1, 2, or 3 year term position that addresses the needs of the project and is a suitable entry level position for your prize student. Alternatively, find stakeholders with budgets and talk to them about their pet projects. Offer to implement those enhancements they’ve been wishing for if they help fund a limited term position for this great student that is eager to work on their project. Once on board, try to find a way to extend their contract until a permanent position can be allocated.

If you cannot bring the students onboard, at least keep in contact with them. Offer to help them find jobs elsewhere by writing a letter of recommendation. Even if you do not benefit from the work you put into grooming them, you will at least grow your network of contacts at your peer institutions, which may also help you with future recruiting.

## 4. Changing Policies

The three methods described above involve going out and interacting with people who have potential to become an advanced developer on your team. The next two actions involve some inward interactions, either with your administrators and HR department, or perhaps just with yourself. Our organizations often limit their own candidate pools with bureaucratic policies that may seem sensible at first glance, but which are entirely unnecessary and which are in fact detrimental to your team, the organization, and to the candidates these policies overlook.

### Allow Remote Employees

Many organizations prohibit the recruitment of remote employees. If you are in a major metropolitan area, then limiting your recruitment to local candidates puts you at a major disadvantage. You are in competition with the tech firms and corporate giants that offer much higher salaries. You will find it difficult to convince colleagues to move to your big city if your offered salary is not sufficient to purchase a home in the area. But if you offered that same salary while allowing them to stay in their current town which has a lower cost of living, you will find that many more talented folks will be interested in your open position. 

The prohibition of remote employees is an outdated policy that needs to die. It stems from a lack of trust in employees to work without physical supervision. This is a terrible way to run an organization. If you cannot trust your employees to do the work you hired them to do, then either you hired the wrong people, or you have not properly structured the work to give the employees satisfaction in completing it, or your team is severely lacking in actual teamwork. 

There is no reason not to hire remote employees, especially when it comes to IT. I have heard colleagues argue that there are disadvantages. Perhaps there are, but they are far outweighed by the giant advantage of being able to recruit really good people to your team that would otherwise not be willing to join. Some argue that a culture of “us versus them” will sprout when you mix local and remote. I argue that only happens if you allow it to. One way to avoid that attitude is to allow (and encourage) the local people to work from home one or two days a week. This turns them into remote employees as well, and helps the team adopt a “remote first” culture. My current team consists of about 50% on-site and 50% remote employees, spanning 5 time zones. The team is highly effective despite the wide physical distribution of its members. 

My hope is that the current pandemic will help break these old prohibitions on remote employees now that pretty much everyone is a remote employee.

### Anti-racist & Anti-sexist Recruitment

Another detrimental policy which seems fine on the surface is the requirement that candidates possess a degree in computer science.  This policy gains nothing for the organization. Most software development at a nonprofit organization revolves around website and web application development, and possibly some mobile app development as well. None of this requires a degree in computer science. Tech firms that are pushing the boundaries of performance and devising new algorithms need engineers with that kind of education. But basic web development for a nonprofit involves composition of prebuilt components or building on top of a robust framework. These skills can (and are) picked up by people with no CS education. On the contrary, many fresh computer science graduates have no idea how to build a clean, reliable, and secure web application. An understanding of CS theories is no guarantee of practical skills.

Many of us promote the idea of diversity but do not take the right actions to back up our words. Eliminating the CS degree requirement is the first step we should all take. Black students and female students are vastly underrepresented in computer science departments. And if the CS degree adds nothing to our candidate pools, as I argued above, then by requiring it we are actively choosing to block black and female developers from the workforce. 

Another aspect to this topic is the hunt for advanced developers and the lack of entry-level offerings. Most HR departments allow managers to post a position with a variable classification, such as Software Developer I, II, or III depending on the selected candidate’s experience. However, I often put most of my effort into trying to recruit advanced engineers. Indeed, this whole blog post began with that premise. This is usually because I have been handed an ambitious project and one or two FTEs to go with it. Naturally, I want to find advanced engineers that can jump in right away and help guarantee a successful outcome for the project.

However, this preference for advanced recruits also plays into the systemic bias against black and female developers. Since they are underrepresented in the CS departments and therefore in the workforce, they usually pick up their skills on their own often while performing other duties in their current jobs. Thus, their resumes list little to no official developer titles in their work experience despite having actually learned the skills and built production applications. Many of these candidates would be very appealing as entry- or mid-level developers, but our insistence on finding advanced people blinds us to what is right in front of us: candidates that are self-motivated, team players, and capable of quickly learning new skills. Those are the three key attributes I look for in all software developer candidates. So I, and all you other engineering managers out there, need to stop focusing on the hunt for advanced engineers and instead provide opportunities for candidates without CS credentials or official development titles in their work histories. When doing this be sure to provide structure, mentorship, and training as described above. You can think of your team as a garden. 

## 5. Advocating for a Team

### Raises & Equity

On top changing hiring practices, there is more internal advocacy that you must take on if you intend to keep the high quality team you have spent so much effort in growing. As your team levels up their skills they are likely to become more sensitive to issues around salaries, either through sheer self-awareness of their new value, or through a bombardment of messages from recruiters. If you do not address the salary gap, you are likely to lose some of the best contributors on your team. You could just wait for those people to get job offers and hope that your institution will make a satisfactory counter-offer. But that is a dangerous game to play. You are much better off putting in the effort up front and advocating for salary increases before your best and brightest start looking for and listening to offers from elsewhere. 

This is not an easy task, but it is worth the effort if it means keeping your team. If you don’t do this work, then you will once again have to go through all the team building work described in the sections above to fill vacancies created by people leaving for higher salaries. Document the accomplishments of the individual and how those contributed to successes for the organization. Describe their value as a team player and their high potential for future contributions. Stress the difficulties and likely failures that will occur in their absence and the dearth of candidates qualified to replace them. You have spent time nurturing their growth into a star member of your team. It is impossible to simply replace them.

Also, be sure to call out salary inequity within the team to your director and you HR rep. As discussed above, there is a systemic bias against black and female candidates. And those that do get hired are often paid less than their teammates. Don’t be complacent about that. Call it out when you see it and advocate for fair pay. I discussed in an earlier section the reasons we should hire these candidates. Getting them at a discount compared to other candidates should not be one of your reasons. 

### Expansion

This action is probably the most difficult and the most out of your control as a team manager. But you should definitely advocate for a bigger team when it is obvious you need more hands on deck (and not just with limited term employees, which I discussed above). Despite the challenge, you should make your needs known. The squeaky wheel gets the grease. If you don’t make your needs known, and put some strong, convincing arguments behind your claims, then your director will never consider expanding your team. 

## 6. Handling Exceptions

Finally, we come to the topic of what to do when training fails. What do you do about people on your team that just cannot (or will not) level up? Your options here are essentially to change your plans for them or show them the door. Usually this choice will depend on many factors including: their personality, their work history, your portfolio, your team size, and more.

### Alternative Roles

Sometimes when you come in as a new manager you will encounter employees that are hard working and enthusiastic, but after a few months it becomes obvious that they have reached a ceiling in regards to the types of skills you hoped they would acquire. At this point it is best to rethink your options. it would be extremely unfair to the employee to continue pushing them to raise the bar. It will cause them undue stress, destroy their confidence, sink their job satisfaction, and likely turn them into a disgruntled employee. It will cause resentment from teammates when they notice someone that is not pulling their weight despite having the same official role. It will also cause you undue frustration and likely cause missed deadlines due to unrealistic expectations. 

And yet, the person has shown nothing but dedication, which should never be undervalued. Sometimes this situation occurs because someone has been incorrectly hired or moved into a particular job classification. Or perhaps the job classifications in your organization are too broad. For instance, someone with the skills of a systems analyst or application administrator has been put into the coarse grained bucket of “programmer/analyst” which you incorrectly interpreted as “software engineer” in the absence of such a job title in your organization. Thus, you expect someone with the ability to build a web app from scratch, and instead you have a person that can write a little code to transform some metadata but who has no knowledge of network protocols, databases, web frameworks, etc. If you cannot get the person to that level that you were expecting, but the employee is still dedicated to the organization, then you should alter your expectations and formally change that employee’s job title and job description to fit their abilities. Carve out a role for them as a Systems Librarian, Business Application Analyst, etc. in which they can succeed and provide value to the team. The employee, you, your team, and your organization will all benefit from this change. It will give the employee the right soil in which to thrive and gain respect from peers. It will prevent you from setting unrealistic expectations and help you better plan your team’s roadmap. And you avoid the stress of the next option.

A final note: be sure to talk to the employee about the option to change titles and job descriptions and why you think it is a good move. Do not just make this career decision for them.

### Encouraging Exits

So what happens when you have an employee that has reached their ceiling and they do not want to take the alternative role you offered? Or perhaps you have an employee that is just resistant to any change at all? Well, in the section above on training I mentioned putting learning goals into employee performance reviews. There were two reasons for that. The primary reason is to show that you are serious about the learning initiative and that you are supporting your employees’ professional development. The second reason is for this unfortunate scenario. If the employee fails to demonstrate the acquisition of the necessary skills, you now have that documented, and you can discuss it with the employee. You can make it clear that acquiring these skills is a mandatory part of the job. If they do not want a job with those requirements you can try to define a new job title and description, but only if it is appropriate and valuable to the team and organization. Otherwise, they should look for a different job elsewhere.

If it unfortunately gets to that awkward phase, discuss options with your HR department. It will likely take some time, but eventually you will be able to dismiss the employee. However, most people will see the writing on the wall and begin looking elsewhere. Fortunately, developers are in such high demand that even difficult ones can find another gig and relieve you of the burden of actually having to fire someone. 

# Conclusion

This was (another) long post, but I hope that it proves helpful to my colleagues working in nonprofits who are new to management or who have just taken on the leadership of a new team. Managing technology in a nonprofit is not easy when the organization’s ambitions are high but the resources are low and the tools are dated. But by taking the steps above (along with some of the actions described in my previous post on modernization), you should be able to make significant improvements.

And keep in mind at all times that you are working with people, not things. I chose the analogy of “growing a team” rather than the traditional phrase “building a team” precisely because growing a garden means working with living things that have their own needs. They’re not a stack of standard sized bricks that are made to fit together perfectly. They will not always conform to the idealistic vision in your head. So you need to adjust your plans accordingly. 

Of course, even the garden analogy falls short, as all analogies eventually do. Flowers and trees may have needs but they don’t have their own ambitions. The people on your team do. And they have feelings, families, and careers. No two are alike. You will have to adapt all the suggestions above to fit the needs of the people on your team and your organization. So it's OK to think of your team as a garden, but treat the individuals on that team like people.

---

> Banner image credit: UCLA Library Digital Collections
>
> https://digital.library.ucla.edu/catalog/bbxp2000zz-89112
