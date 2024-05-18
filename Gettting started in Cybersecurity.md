# Getting Started In Cybersecurity

## Foreword

It's fairly common for beginners to become interested in Cybersecurity and think, "Wow, I'd really like to do that!" The beginner then starts searching Google and Youtube for things like "How to become a hacker" or "hacking tutorials", etc. often to no avail due to the staggering amount of information presented to them, typically with varying opinions. 

The next logical step they take is to seek out communities where hackers and other Cybersecurity professionals congregate, in an attempt at finding some sort of mentorship or guidance. These days forums are mostly seen as antiquated and with beginners wanting a more real-time discussion, Discord tends to be a beginner's next stop.

It seems like not a day goes by on the Church of the SubHackers Discord that a new member will join and ask some form of this question:

> I'm trying to find out the best way to get into hacking and cybersecurity

Although this is a perfectly normal question, beginners often fail to realize that what they have just asked is a fairly deep question with no real clear cut answer.

This document aims to break that question down a bit and provide prospective Cybersecurity enthusiasts with some rough guidance in understanding the industry, determining their area of interest, and some helpful resources for the long journey ahead of them.

## First Steps

Here are the first steps towards becoming knowledgeable in Cybersecurity and hopefully landing a gig.

First we will start with Frequently Asked Questions. These are questions that come up time and time again in the Church of the SubHackers Discord server.

After the FAQs is a small questionnaire for readers to answer in order to transform the nebulous concept of Cybersecurity into a more concrete definition of what it is they intend to learn.

### FAQs
- **Q: How do I get started in Cybersecurity? How do I become a pentester/ethical hacker/red teamer?**
> A: There is no definitive right or wrong way to get into this industry. It is the intention of this document to prove a rough framework for a budding  Cybersecurity enthusiast to get an understanding of the industry and determine which course of action will benefit themself.

- **Q: Do I need to learn to code in order to get a job in Cybersecurity?**
> A: No, not necessarily. In many of the roles outlined below a focus is put on understanding tooling and methodologies; that is, knowing how to use Tool X to do Thing Y, regardless of your ability to manually do what Tool X does. 
> 
> On the other hand, while being able to code may not necessarily be a hard requirement it is in fact an incredibly useful skillset to have as it allows you to differentiate yourself from other people in your industry by showcasing a portfolio of your work via Github/Gitlab/Bitbucket/etc., and enables you to quickly adapt to situations where there is currently no tool which does X but X is exactly what you need done so you code your own tool.

- **Q: Do I need to go to college/university in order to get a job in Cybersecurity?**
> A: No, not necessarily.
>
>While it is becoming more and more popular for Universities to offer a degree in Cybersecurity, these programs tend to be restricted to graduate students looking to obtain a Master's degree.
> 
> This means that after spending 4 years to gain a Bachelor's degree in a field like IT or Computer Science, a student must then spend another 1.5-2 years in order to earn their degree. In these approximately 6 years someone looking to learn about Cybersecurity could have learned many of the core competencies and potentially even landed their first job.
>
>With all that said, the biggest value in persuing a degree in Cybersecurity is in internships. Universities are often partnered with various businesses to provide the business with college interns. Interships allow a student to build their resume by giving them actual work experience at some of the biggest companies in the world.
>
>This experience is useful when applying for jobs as you have more experience in the industry than someone who self-studied and never worked in a large company. Additionally, many interns find themselves with job offers waiting for them after they finish their degree because they impressed the company that they interned for.
>
>The choice is yours but a degree is definitely not needed.

> It is worth mentioning that while in the United States a degree may not be necessary, other countries such as India place a heavy emphasis on a degree as a stipulation for employment.
{.is-warning}


- **Q: If I don't get a degree, how can I get a job? Recruiters want experience but without a degree I can't get experience...**
> A: There are many ways for a Cybersecurity enthusiast to showcase their skills outside of a traditional work environment and prove that while they may not have documented work experience, they are more than capable to perform expected job duties for that role.
>
> Platforms such as Github allow you to build a portfolio of work showing various Cybersecurity-specific tools which they have created, open-source projects they have contributed to, etc.
>
> Github also allows easy creation of a blog where you can show off the latest research you've conducted, create articles about certain attacks, techniques, tools, tutorials, etc. that show competency in an area. 
>
> Capture The Flag (CTF) competitions allow you to put practical usage to the skills you have learned and give a hands-on example of your capabilities to prospective employers. Additionally, if you are able to solve a challenge, posting a detailed write-up onto your blog shows that you can not only tackle the technical aspects but are capable of distilling the information down and communicate it to others in an effective manner —something that is extremely important when dealing with non-security saavy people such as developers and project managers.
>
>Finally, we live in a world which has embraced independent security research and now rewards independent research. With many companies now running Bug Bounties it is easier than ever to pick a company you'd love to audit, find bugs in their code/infrastructure, report the finding and gain both recognition and oftentimes a cash reward. Bug Bounties demonstrate your ability to audit real-world targets and build a name for yourself at the same time.

- **Q: What's the easiest way to get a job in Cybersecurity?**
> A: While there is no one role that is easier to learn than others, there are some roles which are generally more in-demand from employers. 
>
>Candiates with experience in Vulnerability Management, Web Application Security (both offensive and defensive), Mobile Application Security (both offensive and defensive),and Security Analysis will generally have a much easier time getting hired at a company due to the ubiquitous need for those skillsets across all industries.

### Cybersecurity Beginner Questionnaire 

1. What Area of Expertise excites you the most? Reference the section titled "Areas of Expertise" if you are unsure.
2. What is your overarching goal in learning Cybersecurity? To gain employment in the industry? As a hobbyist? World domination?
3. If your goal is to get a job in this industry, what would your ideal job entail? What would make you happy to get out of bed in the morning and excited to get to work?

## Areas of Expertise

Cybersecurity is a multi-faceted discipline and is made up of multiple areas of expertise. While being a jack-of-all-trades is enticing to many beginners, it is important to understand that specializing in a specific area of Cybersecurity will be more beneficial for securing your first job.

The following list of typical roles within any Cybersecurity organization have been broken down into two major sections: Defensive, and Offensive. This list is in no way a definitive or exhaustive list of roles and only serves as a way to introduce beginners to the various fields of Cybersecurity. 

**Defensive** roles aim to proactively mitigate security concerns before they become full fledged security issues, but also include roles which both proactively secure an application or environment as well as reactively deal with security incidents.

**Offensive** roles aim to regularly test the security of an application or environment via various means in an attempt to discover flaws before legitimate attackers do. Despite being offensive in nature, the goal of any successful Offensive Security organization is to enable Defensive roles to mature by ensure the policies and procedures surrounding Cybersecurity are both effective and streamlined.

It is a common misconception that Defensive roles (often called "Blue team") are boring or otherwise do not require knowledge of Offensive roles (often mistakenly called "Red team"). In fact, while an Offensive role is typically a simulation or emulation of an attacker, Defensive roles often require the same attacker-oriented mindset as Offensive roles in order to predict how a threat actor might attack a target and thus how they will prevent or detect such behavior.

> **Red team is not better than Blue team. Both sides of the fence maintain the same core goal: elevating the security posture of an environment or product in order to minimize security incidents. A proper, mature Cybersecurity Organization will have a "Purple team" mindset in which both Red and Blue teams cooperate with each other to create a more secure environment.**
{.is-info}


### Defensive Roles

Some Cybersecurity job titles and roles which focus on defense.

- Detection & Response
- DevSecOps
- Security Analyst
- Malware Analyst
- Vulnerability Management
- Application/Product Security Engineer
- Reverse Engineer
- Security Researcher
- Network Security Engineer
- Cloud Security Engineer

### Offensive Roles

Some Cybersecurity job titles and roles which focus on offense.

- Penetration Tester
- Application/Product Security Tester
- "Red team"
- Mobile Application Security Tester
- Vulnerability Researcher & Exploit Developer
- Security Researcher

Google some of these titles and roles and get a feel for the different type of work they do. This will help you get an understanding of where you may want to focus your learning, at least initially.

## Now what?

Now that you've gotten a basic understanding for the various roles and skillsets that make up Cybersecurity it is time to pick a focus area. Focusing and specializing in one area is extremely important early on in your progression because it will allow you to steadily grow without being bogged down by other skills which may not necessarily be important towards your goal.

For example if your goal is to become an Offensive Web Application Tester:

Skills which are important include: 

- Understanding the OWASP Top 10
- Familiarity with various web technologies and protocols such as HTTP/HTTPS, Websockets, WebASM, SSL/TLS, etc.
- Familiarity with commonly used infrastructure
- Ideally familiarity with languages such as Javascript and frameworks like React, Vue, etc. which are used to build web applications
- Familiarity intercepting proxies like Burp
- Familiarity with commonly used tools such as Sqlmap, Acunetix, Postman, etc.

Skills which are not important include:

- Reverse Engineering
- Malware Analysis
- System internals
- Kernel Exploitation
- Network exploitation

This is not to say that you should not study skills which are not directly related to your desired job function. You should study whatever interests you. Keeping focused on a specific area is just a way to ensure you first learn the skills required for a specific role and gain a deep understanding of them before being distracted by other things.

At the end of the day, if a company is looking to hire a Web Application Security Tester they are going to be assess your resume based on those skills. Being mediocre at Web Application security as well as being a mediocre Reverse Engineer just makes you seem mediocre. Being a badass at Web Application security but a mediocre Reverse Engineer just means you're a badass and should the need arise you can also take on basic Reverse Engineering tasks.

## Closing

By now you should have an understanding of why "How can I get started in Cybersecurity" is a difficult question to answer. You should also be equipped with enough information to formulate a more specific question such as "I want to learn how to hack mobile applications but I don't know where to start. Can anyone help me?".

Feel free to join us on [Discord](https://discord.gg/bsuTrTjFte) where you can ask any questions you may have.
