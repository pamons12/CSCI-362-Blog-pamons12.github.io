### HW0: Introduction
Welcome to my blog.
<br/> I am a senior at the College of Charleston and am pursuing a BS in Computer Science.

### HW1: Chapter 1
<br/> 1.3: What are the four important attributes that all professional software should possess? Suggest four
other attributes that may sometimes be significant.
<br/>-Acceptability, Dependability and security, Efficiency, and Maintainability
<br/>-Some additional attributes might be: Ease of use, Reliability, Response time, and Backwards compatibility

<br/> 1.8: Discuss whether professional software engineers should be licensed in the same way as doctors or
lawyers.
<br/>-I believe software engineers should be licensed in the same way doctors and lawyers are. Just like doctors and lawyers, software engineers need to be able to produce quality work or else it could result in massive amounts of damage. Take doctors, for example, if they didn't have to be licensed they could dismiss something a patient brings up that could be an issue down the road. Software engineers also need this level of quality because if their work isn't up to par it could result in significant financial damage or loss of life depending on the application.

<br/> 1.9: For each of the clauses in the ACM/IEEE Code of Ethics shown in Figure 1.4, propose an appropriate example that illustrates that clause.
<br/>Public: Software engineers will work to better their software through feedback/criticism.
<br/>Client and Employer: Software engineers will abide by the 4 professional responsibilities when working for a client or employer. Them being Confidentiality, Competence, <br/>Intellectual property rights, and avoiding computer misuse
<br/>Product: As stated earlier Software engineers need to uphold a level of quality. They should run and show several tests of the software working as anticipated.
<br/>Judgment: Software engineers should use their professional judgment properly, ie not add extra features to raise the price or cause more bloat. They should be confident in the work they produce
<br/>Management: When bringing new software engineers onboard management should go over and make sure the new engineers understand good ethics.
<br/>Profession: Software engineers need to uphold a level of quality and trust with the client/employer for their organization to grow as a whole. 
<br/>Colleagues: Software engineers should accept and supply constructive criticism/feedback when coming from a fellow engineer or a client/employer.
<br/>Self: Software engineers should always be learning and improving themselves throughout their careers.

<br/> 1.10: To help counter terrorism, many countries are planning or have developed computer systems that track large numbers of their citizens and their actions. Clearly, this has privacy implications. Discuss the ethics of working on the development of this type of system.
<br/> -One one hand, having such large scale tracking violates the privacy of citizens and if this system was compromised could result in a catastrophic leak of private information. On the other hand, it does provide citizens with more protection when it comes to terrorism and could lead to the prevention of terrorist attacks on that country's soil. 

### HW2: Reflections on software engineering practices
<br/>When reading through the three articles No Silver Bullet, Kode Vicious, and Google Code Repo I thought to my self what common concerns do these articles bring up? After some thought, the most prominent concern is the challenges of software engineering, and what are some possible solutions to these challenges?

<br/>Unfortunately, there is no "silver bullet" that will solve all the challenges of software engineering, but they are a few changes that can be made to better the experience when developing software. First off, conformity of software. When working with a group of software engineers on a piece of software it is common for individuals in the group to have different ideas or different ways of working. Conformity is the idea that new software or changes to existing software must conform or work with older/existing software. Conformity is an important challenge to overcome especially when working in a team. An individual's different ways of working/thinking could result in a compatibility issue when everyone's work finally comes together at the end. This is why strong communication is vital when working with a group developing a piece of software. 
Next, is the organization and complexity of engineering software. When dealing with a large project getting lost in the code can be an easy thing that can happen to anyone. This is why the organization of ideas is crucial in software engineering. One possible solution suggested by the Kode Vicious article is to apply the scientific method. To put it simply the scientific method is developing a question and through research develop a hypothesis (an educated guess to the problem). When testing the hypothesis you either change the hypothesis using what you learned from the test or you eliminate that hypothesis and create a new one. Now how does the scientific method provide a possible solution to conformity? Well, when a software engineer stumbles upon a problem, let's say a bug in some piece of software, for example, you want to apply the scientific method to solve that problem. Develop a theory and from that theory develop a series of tests or hypothesis on how to solve this problem. When a test/hypothesis fails don't erase it, write down your results, and say why it failed. This will help keep software engineers organized because if the same bug happens a month or so later they can look back at their notes and see what they have already tried and see whether or not it worked out, that way they are not wasting time or resources testing things again.
Lastly, is the sharing of code and the importance of open source projects. Interestingly enough Google has a single repository that contains several billion lines of code. All this code in a single repository might sound immensely overwhelming but this allows for developers to have one place to search for a bit of code they would like to reuse that they know works and has been tested. This helps with the engineering process immensely especially when on a tight time frame and it allows engineers to solve issues that might arise in the development process much faster.
<br/>In conclusion, these three articles highlighted on the challenges of a softeware engineer and possible solutions to these challenges.

### HW3: Chapters 11 & 12

<br/> 11.4 What is the common characteristic of all architectural styles that are geared to
supporting software fault tolerance?
<br/>A system that can support fault tolerance has to be designed to use redundant and diverse hardware and software.

<br/> 11.7 It has been suggested that the control software for a radiation therapy machine, used
to treat patients with cancer should be implemented using N-version programming.
Comment on whether or not you think this is a good suggestion.
<br/>I think using N-version programming for a radiation therapy machine is not only a good idea but should be required. Being that radiation therapy could be fatal or result in life long complications if used incorrectly. Essentially N-version programming runs the same task on separate identical machines and a fault manager will compare the outputs at the end. If all the answers line up then the fault manager knows there is a low chance of error, if the outputs don't line up the machine can be shut down safely without any harm to the patient. 

<br/> 11.9 Explain why you should explicitly handle all exceptions in a system that is intended to have a high level of availability.
<br/> A system that has a high availability means that it needs to be running and operational as much as possible. This means if a problem does arise the system needs to correct it while maintaining a high level of availability. Problems need to be found and resolved as soon as possible to prevent a snowball effect of issues, later on, possibly compromising the availability of the system.

<br/>12.5 A train protection system automatically applies the brakes of a train if the speed limit for a segment of track is exceeded, or if the train enters a track segment that is currently signaled with a red light (i.e., the segment should not be entered). There are two critical-safety requirements for this train protection system: 
<br/>The train shall not enter a segment of track that is signaled with a red light. 
<br/>The train shall not exceed the specified speed limit for a section of track. 
<br/>Assuming that the signal status and the speed limit for the track segment are transmitted to on-board software on the train before it enters the track segment, propose five possible functional system requirements for the onboard software that may be generated from the system safety requirements.
<br/>1. If the current train speed exceeds the speed limit for that section of track the brakes will be applied until the speed of the train is at the speed limit.
<br/>2. If the train is approaching a segment of track that is signaled red, the train should alert the driver to look for a green signaled track.
<br/>3. If the train enters a segment of track that is signaled red, the brakes should be applied and the train should alert the driver of the situation.
<br/>4. If the train stops due to entering a segment of track signaled red, the driver will be allowed to accelerate the train at a safe speed to reach green signled track.
<br/>5. If the train detects another train coming straight at it regardless of track signal, both trains will immediatly apply brakes and an alarm will sound for the driver.
