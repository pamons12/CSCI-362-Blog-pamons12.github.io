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
<br/>-A system that can support fault tolerance has to be designed to use redundant and diverse hardware and software.

<br/> 11.7 It has been suggested that the control software for a radiation therapy machine, used
to treat patients with cancer should be implemented using N-version programming.
Comment on whether or not you think this is a good suggestion.
<br/>-I think using N-version programming for a radiation therapy machine is not only a good idea but should be required. Being that radiation therapy could be fatal or result in life long complications if used incorrectly. Essentially N-version programming runs the same task on separate identical machines and a fault manager will compare the outputs at the end. If all the answers line up then the fault manager knows there is a low chance of error, if the outputs don't line up the machine can be shut down safely without any harm to the patient. 

<br/> 11.9 Explain why you should explicitly handle all exceptions in a system that is intended to have a high level of availability.
<br/>-A system that has a high availability means that it needs to be running and operational as much as possible. This means if a problem does arise the system needs to correct it while maintaining a high level of availability. Problems need to be found and resolved as soon as possible to prevent a snowball effect of issues, later on, possibly compromising the availability of the system.

<br/>12.5 A train protection system automatically applies the brakes of a train if the speed limit for a segment of track is exceeded, or if the train enters a track segment that is currently signaled with a red light (i.e., the segment should not be entered). There are two critical-safety requirements for this train protection system: 
<br/>The train shall not enter a segment of track that is signaled with a red light. 
<br/>The train shall not exceed the specified speed limit for a section of track. 
<br/>Assuming that the signal status and the speed limit for the track segment are transmitted to on-board software on the train before it enters the track segment, propose five possible functional system requirements for the onboard software that may be generated from the system safety requirements.
<br/>1. If the current train speed exceeds the speed limit for that section of track the brakes will be applied until the speed of the train is at the speed limit.
<br/>2. If the train is approaching a segment of track that is signaled red, the train should alert the driver to look for a green signaled track.
<br/>3. If the train enters a segment of track that is signaled red, the brakes should be applied and the train should alert the driver of the situation.
<br/>4. If the train stops due to entering a segment of track signaled red, the driver will be allowed to accelerate the train at a safe speed to reach green signled track.
<br/>5. If the train detects another train coming straight at it regardless of track signal, both trains will immediatly apply brakes and an alarm will sound for the driver.

### HW4: Reflections on software failures
<br/>Upon reflecting on all the readings it was clear the common concern throughout all of them is the struggles of software failures and how costly they can become. Starting with the semi-failed FBI sentinel project, I say semi-failed not because it wasn't completed but because there were many issues along that way. Following the 9-11 attacks, the FBI wanted to develop a digital information and case management system, which would allow FBI agents to share information easily and securely. Alas, the project had some difficulties during development and the FBI decided to complete it in house, causing the project to way over budget and took 12 years to complete instead of the proposed 6 years. According to the Spectrum article, an update on the project two years after deployment, Sentinal still has some bugs resulting from rushing the development of it. 
<br/>The Sentinal project may have been costly in terms of currency but the failures of CT scans talked about in the New York Times article were costly in terms of human life. This is a prime example of why testing software before deployment, especially when lives are at risk, is critical. Although the extremely elevated levels of radiation could put blame on the technicians operating the equipment, the software should have a built-in failsafe to prevent this from happening. All in all, this seems to me like an attempt to minimize cost, rush development, or a lack of testing of the software, which is unacceptable especially when lives are at risk. 
<br/>Both of these incidents could have been prevented if development wasn't rushed. That brings up the question, how can we prevent software failures in the future? To address this we must look at the Entrepreneur article regarding why software projects fail.  First up is insufficient time, developing software can be a very lengthy process, so when companies try to set unrealistic deadlines for their developers this is setting up the project to fail before it even starts. This leads to the next point, inadequate planning. When planning to develop software both the developers and the company's management team needs to have a meeting to come to a deadline that works with both parties along with what the project requirements are. Just like a sturdy house cant be built on a weak foundation, good software cant be properly developed without a good plan. This next point ties the first two together, unclear project requirements. If a good plan isn't laid out or if the plan is changing midway through development this will risk having to redo entire sections of code causing the project to go over budget and over time. Next up is having too many people assigned to the same project, this is just like the saying of having too many hands in the cookie jar. Adding more developers to the project isn't always the answer as this can drive up costs and could result in communication issues if everyone isn't exercising good communication. After a project is completed, thorough testing is essential in order to make sure the project is functioning as intended. The Therac-25 accidents are a great example of this, a lack of testing caused machines to deliver elevated doses of Therac-25 causing radiation poising in patients. Last but not least, is the failure to find a good project manager. Without a good project manager, development could become disorganized and confusing real quick. 
<br/>In conclusion, addressing these six software project concerns will ensure the software development process to run more smoothly and will prevent software project failures in the future.

### HW5: Chapter 4 and Reflections
<span style="margin-left:3em">The readings this week seemed to focus on the importance of incorporating Test-Driven Development and establishing non-functional and functional requirements before the development phase even starts. Establishing non-functional and functional requirements before the development begins is essential to project organization and possible issues down the road. If a developer does not have a clear understanding of both the non-functional and functional requirements they could forget about a feature that could result in catastrophic errors and a delayed release date. I think the "Magical Number Seven" page ties in well here, this article states that the human brain can only store 7 (+-2) objects in their short term memory. The point is if all the functional and non-functional requirements are not laid out in an organized fashion the user could very easily forget to implement a feature, especially in big projects. After all, it is much easier to add features before development begins, instead of adding features mid-development or even worse at the end of development. With regard to incorporating test-driven development, all engineers should develop tests throughout the development process to ensure their software is behaving as intended.
<br/>
<br/>4.5) Using the technique suggested here, where natural language descriptions are presented in a standard format, write plausible user requirements for the following functions: 
<br/>a) An unattended gas pump system that includes a credit card reader. The customer swipes the card through the reader, then specifies the amount of fuel required. The fuel is delivered and the customer's account is debited. 
<br/><span style="margin-left:3em">-Function: Issues gas
<br/><span style="margin-left:3em">-Description: Issue gas by charging the user for the amount of gas pumped
<br/><span style="margin-left:3em">-Input: pin/zipcode for debit or credit card, the grade of fuel
<br/><span style="margin-left:3em">-Source: Charging the credit card for the amount pumped based off of grade
<br/><span style="margin-left:3em">-Outputs: The gas the user pumps
<br/><span style="margin-left:3em">-Destination: Selection of fuel grade
<br/><span style="margin-left:3em">-Action: The gas filling system is at zero when no transaction is being made. When the card, card details, and the grade of fuel is selected, the user can begin pumping gas. 
<br/><span style="margin-left:3em">-Requires: Requires a valid card with details and the grade of fuel
<br/><span style="margin-left:3em">-Precondition: User must have a valid credit/debit card with details to use it
<br/><span style="margin-left:3em">-Post Condition: The gas is issued
<br/><span style="margin-left:3em">-Side Effects: None
<br/>
<br/>b) The cash-dispensing function in a bank ATM. 
<br/><span style="margin-left:3em">-Function: Dispense money from ATM
<br/><span style="margin-left:3em">-Description: Given the amount of money is dispensed to the user if they have a valid debit card and pin
<br/><span style="margin-left:3em">-Input: Amount of cashback, debit card, and pin
<br/><span style="margin-left:3em">-Source: Keypad to get the amount of cash wanted and pin. Card reader to insert a debit card
<br/><span style="margin-left:3em">-Outputs: The cash the user requests
<br/><span style="margin-left:3em">-Destination: Amount deducted from users card
<br/><span style="margin-left:3em">-Action: The ATM  is in 0 state when no transaction is happening. When the user inserts a card the ATM asks for a pin. Once a valid card and the pin is given the user can select the amount of cash they want. Once the amount of cash is inputted the ATM makes sure the card has enough money for that. If it does the card is given back and the money is dispensed.
<br/><span style="margin-left:3em">-Requires: Requires the user's card and pin, the amount of money the user wishes to take out
<br/><span style="margin-left:3em">-Precondition: User must have enough money on the card for the withdraw and a valid debit card with pin
<br/><span style="margin-left:3em">-Postcondition: The cash is dispensed to the user
<br/><span style="margin-left:3em">-Side Effects: None
<br/>
<br/>c) In an internet banking system, a facility that allows customers to transfer funds from one account held with the bank to another account with the same bank.
<br/><span style="margin-left:3em">-Function: Transfer money
<br/><span style="margin-left:3em">-Description: The given transferred amount is deducted from the sender's account and added to the receiver's account. 
<br/><span style="margin-left:3em">-Input: Account number of receiver and amount to be transferred
<br/><span style="margin-left:3em">-Source: Transfer money from source account to receivers account for a given amount
<br/><span style="margin-left:3em">-Outputs: The given amount of money arrives at the destination account
<br/><span style="margin-left:3em">-Destination: Selection of how much to send from the sender's account
<br/><span style="margin-left:3em">-Action: The system is in 0 state when no transaction is happening. When a user wants to transfer money, the system asks for the amount to be transferred and the destination account details. After this information is given the funds are transferred to the destination
<br/><span style="margin-left:3em">-Requires: Requires amount to be transferred and details for both source and destination accounts
<br/><span style="margin-left:3em">-Precondition: Enough funds to supply the transfer and the details for both source and destination accounts
<br/><span style="margin-left:3em">-Postcondition: The funds are transferred from the source to the destination account
<br/><span style="margin-left:3em">-Side effects: None
<br/>
<br/>4.6) Suggest how an engineer responsible for drawing up a system requirements specification might keep track of the relationships between functional and non-functional requirements.
<br/><span style="margin-left:3em">Functional Requirements
<br/><span style="margin-left:4em">-Describe what the system should do, requirements of individual system features
<br/><span style="margin-left:3em">Non-functional Requirments
<br/><span style="margin-left:4em">-Describe the expectations of the system
<br/><span style="margin-left:3em">-An engineer could keep track of these by writing down all of the non-functional requirements and underneath each one write what functional requirements will be needed to satisfy this non-functional requirement.
<br/>
<br/>4.7) Using your knowledge of how an ATM is used, develop a set of use cases the could serve as a basis for understanding the requirements for an ATM system.
<br/><span style="margin-left:3em">-The user does not have a valid card or forgets the pin so no transaction occurs
<br/><span style="margin-left:3em">-The user wishes to make a deposit. The user inserts their debit card and pin. The user selects the deposit option and asks for the user to insert their cash. The user inserts cash and once the machine is done counting the user verifies the amount. ATM deposits funds to the account and returns the card to the user, the transaction is complete.
<br/><span style="margin-left:3em">-The user wishes to make a withdraw. The user inserts their debit card and pin. The user selects the withdraw option and inputs the amount of cash they would like to withdraw. The ATM verifies the inputs and returns the card to the user. Once the card is returned the cash is dispensed, the transaction is complete.
<br/>
### HW6: Chapter 2
2.1) Suggest the most appropriate generic software process model that might be used as a basis for managing the development of the following systems. Explain your answer according to the type of system being developed: 
<br/><span style="margin-left:3em">1. A system to control antilock braking in a car
<br/><span style="margin-left:4em">-I think the most appropriate generic software process model for this example would be the waterfall model. I choose this model because it is focused on making sure there are no flaws before deployment and the antilock braking is a critical system in ensuring the driver's safety.
<br/><span style="margin-left:3em">2. A virtual reality system to support software maintenance
<br/><span style="margin-left:4em">-I think the most appropriate generic software process model for this example would be incremental development. I choose this model because it would allow the developers to easily make changes or maintenance to the software based on the feedback of the users. It is also not a critical system
<br/><span style="margin-left:3em">3. A university accounting system that replaces an existing system
<br/><span style="margin-left:4em">-I think the most appropriate generic software process model for this example would be integration and configuration. I choose this model because an existing system is being replaced and some of that data will be reused. 
<br/><span style="margin-left:3em">4. An interactive travel planning system that helps users plan journeys with the lowest environmental impact
<br/><span style="margin-left:4em">-I think the most appropriate generic software process model for this example would be incremental development. I choose this model because it is likely developers may want to update the systems algorithm that figures out how large an environmental impact a trip is. 

### HW7: Chapter 5 and 6
  5.3) You have been asked to develop a system that will help with planning large-scale events and parties such as weddings, graduation celebrations, and birthday parties. Using an activity diagram, model the process context for such a system that shows the activities involved in planning a party (booking a venue, organizing invitations, etc.) and the system elements that might be used at each stage.
  ![5 3](https://user-images.githubusercontent.com/47860735/94605169-b87c3680-0266-11eb-941e-d1cf1bb8eff4.jpg)
  
  5.5) Develop a sequence diagram showing the interactions involved when a student registers for a course in a university. Courses may have limited enrollment, so the registration process must include checks that places are available. Assume that the student accesses an electronic course catalog to find out about available courses.
  ![5 5](https://user-images.githubusercontent.com/47860735/94605176-bade9080-0266-11eb-80f7-166d95395195.jpg)
  
  5.7) Based on your experience with a bank ATM, draw an activity diagram that models the data processing involved when a customer withdraws cash from the machine.
  ![5 7](https://user-images.githubusercontent.com/47860735/94605189-bf0aae00-0266-11eb-8f57-608fc3e911e9.jpg)
  
  5.8) Draw a sequence diagram for the same system. Explain why you might want to develop both activity and sequence diagrams when modeling the behavior of a system.
  ![5 8](https://user-images.githubusercontent.com/47860735/94605191-bf0aae00-0266-11eb-8150-55f3d34bde52.jpg)

  6.4) Draw diagrams showing a conceptual view and a process view of the architectures of the following systems:

   A ticket machine used by passengers at a railway station.
   ![6 4 1](https://user-images.githubusercontent.com/47860735/94605516-3d675000-0267-11eb-8402-1ae9c1c79db8.jpg)

   A computer-controlled video conferencing system that allows video, audio, and computer data to be visible to several participants at the same time.
   ![6 4 2](https://user-images.githubusercontent.com/47860735/94605515-3c362300-0267-11eb-8010-0778470191bb.jpg)

   A robot floor-cleaner that is intended to clean relatively clear spaces such as corridors. The cleaner must be able to sense walls and other obstructions.
   ![6 4 3](https://user-images.githubusercontent.com/47860735/94605193-bfa34480-0266-11eb-8b40-30f0ce1c51af.jpg)
   
### HW8: Mythical Man Month 
Upon reading the first four chapters of the Mythical Man-Month it became apparent that software engineering isn't always about the quantity of a workforce but instead the quality of the workforce. 
<br/><span style="margin-left:2em">The first chapter talks about the tarpit that is software engineering. I thought the analogy of calling software engineering a tar pit was intresting. When a large project is being developed it requires a massive amount of working hours and money to keep it alive, throwing all these resources into this "tar pit" is what the author is talking about. Developers might get stuck in this pit due to running out of resources causing the death of their project. On the other hand, developers might get stuck in the pit for a little bit they will ultimately concur the pit and complete the project. 
<br/><span style="margin-left:2em">The second chapter is all about the timing required for software engineering and reinforces my first point that the quantity of work isn't always as important as the quality of work. When working on a large project in a tight time frame many people might think adding more software engineers to the project will speed up the progress. Although this might make sense this is not always the case. To understand this better the author talks about two different types of tasks, partitionable and non-partitionable. Partitionable tasks are tasks that can have the workload easily divided, thus this type of task will benefit from an increase of developers. Take car manufacturing for example, sure one person could build a car by themselves but it is much more efficient and quicker to have multiple people working on the same car at the same time, this is the idea of an assembly line. On the other hand, non-partitionable tasks are tasks that can not have the workload easily divided, thus an increase of developers will not help with this type of task. For example, if someone wanted to have a baby, no matter how many pregnant women there are, the time it would take would always be nine months. The author then goes into detail on how the time should be divided up: 1/3 planning, 1/6 coding, 1/4 component test/early system test, 1/4 system test after development is completed. When reading this I was shocked at how little time is dedicated to coding and how much time is set aside for testing. 
<br/><span style="margin-left:2em">Chapter 3 talks about the importance of the quality of the team instead of the size of a team. The author uses a surgical team as an example, surgical teams are usually fairly small, usually only consisting of 5-7 people. Now imagine if there were 15-20 people on that surgical team, the room would be crowded and the increase in communication would complicate things. The sample idea can be applied to developing software, including large projects. When team sizes get large people could get a smaller amount of work, but in order to keep everyone on the same page, the amount of communication needs to be increased. This can be decremental as more time is being dedicated to communication thus making the project need more time to be completed. It is better to have a smaller workforce of great engineers than it is to have a large workforce of decent engineers. The other side of seeing this is if the workforce is too small, too few developers could cause the time needed to be extended. This is why the planning stage is so important, in the planning stage developers must find the sweet spot of the number of developers needed in order to prevent costly additions to the team later in development. 
<br/><span style="margin-left:2em">Lastly, chapter four talked about the importance of conceptual integrity. The basic idea behind this is everyone on the team should be working towards the same goal, not their individual goals. A developer working on a group project not only needs to make sure that his portion is completed on time and correctly, but needs to make sure that his work will be compatible with the rest of the group's work and have the user's requirements in mind. 
<br/><span style="margin-left:2em">All in all, I thought the article Mythical Man-Month was a fascinating read and brought up some good points that I have never thought of. The overarching message I took from this article is the importance of having a high-quality workforce instead of having just a large decent-quality workforce.
  
### HW9: Chapter 8 and reflections on testing

<br/>8.7) Write a scenario that could be used to help design tests for the wilderness weather station system. 
<br/><span style="margin-left:2em">John is doing a monthly inspection of all of the wilderness weather station systems. He logs into each one using a unique identifier given to each weather station. He first does a status check to make sure all the instruments are up and running correctly. Once he sees that all the instruments are up and running, he compares this station's readings with readings of other stations in the area to verify the instruments are working correctly. Once he confirms the station's correctness, he issues a reboot of all the instruments to recalibrate them. Once he sees the system is back online, and the instruments produce outputs, he signs off of this station and moves onto the next.

<br/>8.10) A common approach to system testing is to test the system until the testing budget is exhausted and then deliver the system to customers. Discuss the ethics of this approach for systems that are delivered to external customers. 
<br/><span style="margin-left:2em">There are many problems with this type of approach. If the system still has some errors when the budget runs out, the customer will be receiving a faulty piece of hardware and causing some significant issues down the road. It is better to alert the customer that the project went over budget than to give them a faulty product. Also, what if the testing budget is not enough to cover all the methods in the software. If only half of the methods can be tested, then there is a pretty big chance that the other half might have some error than could mess up the methods that have been tested, its like a domino effect. Lastly, suppose the system is deployed, and errors are discovered. In that case, it tarnishes the software company's reputation, but the cost to fix these errors will be a lot more than if they were just fixed before the system was deployed.
  
### HW10: Chapter 15
  
<br/>15.10) The reuse of software raises a number of copyright and intellectual property issues. If a customer pays a software contractor to develop a system, who has the right to reuse the developed code? Does the software contractor have the right to use that code as a basis for a generic component? What payment mechanisms might be used to reimburse providers of reusable components? Discuss these issues and other ethical issues associated with the reuse of software.

<br/><span style="margin-left:2em">What software is developed for a company by an outside developer, the company that requested for the software to be built is the one who owns it. This is because the company is the one who is paying for it, and if the company never requested the software to be developed than the code would have never existed. The software contractor would not have the right to reuse the code as a basis for a generic component because he does not own it. He would have to ask for permission if he would like to reuse it for something else. The first thing that comes to mind for reimbursement would be an upfront payment or a royalty system. The upfront payment would be a one-time payment that gives the owner of the code payment for a contractor to reuse the code. A royalty system would be a payment over a certain length of time or in perpetuity. For example, if a contractor reuses some code, and that code adds up to 20% of the total code, then the reused code owner would get 20% of the profit. Plagiarism is one thing that can occur when reusing code and can result in issues for both the contractor and client. Another problem with the reuse of code is the eventual lack of new ideas. If people keep reusing code, a better way of implementing that code may never be found.
  
### HW11: Chapter 9

<br/>9.8) Briefly describe the three main types of software maintenance. Why is it sometimes difficult to distinguish between them?
<br/><span style="margin-left:2em">1. Fault repairs to fix bugs and vulnerabilities
<br/><span style="margin-left:3em">-This type of maintenance is done when a coding error, design error, or requirement error occurs. Coding errors being the least expensive to fix and requirement errors being the most expensive.
<br/><span style="margin-left:2em">2. Environmental adaptation to adapt the software to new platforms and environments
<br/><span style="margin-left:3em">-This type of maintenance is done when some aspect of the systems environment changes. This can be anything from changing out hardware, changing operating systems, or changing supporting software. 
<br/><span style="margin-left:2em"> 3.Functionality addition to add new features and to support new requirements.
<br/><span style="margin-left:3em">-This type of maintenance is done when system requirements change in response to an organizational or business change. This type of maintenance results in a bigger scale of change than the other types of maintenance. This type is also done when new features are being added.
<br/><span style="margin-left:2em">-It is often difficult to distinguish between these maintenance types because they often overlap with each other. They also all try to accomplish the same goal by having software that runs correctly without issues.

<br/>9.10) Do software engineers have a professional responsibility to develop code that can be easily maintained even if their employer does not explicitly request it?
<br/><span style="margin-left:2em">-Software engineers have a professional responsibility to develop easily maintainable code, even if their employer does not request it. This would save money and time for both the company and client if an issue arose down the road. It is much easier to maintain code that is written with ease of maintenance in mind. Also, before the software is even deployed, testing and fixing bugs would be much easier if the software was written to be easily maintained.
  
### HW12: Chapter 16

16.9) Design the interface of components that might be used in a system for an emergency control room. You should design interfaces for a call logging component that records calls made, and a vehicle discovery component that, given a postcode (zip code) and an incident type, finds the nearest suitable vehicle to be dispatched to the incident.

![IMG_1254](https://user-images.githubusercontent.com/47860735/96297654-2f336680-0fbf-11eb-8f24-0e7083292815.jpg)

### HW13: Chapter 17

17.10) Your company wishes to move from using desktop applications to accessing the same functionality remotely as services. Identify three risks that might arise and suggest how these risks may be reduced.
<br/>1. Moving online will require more network bandwidth, causing latency and slow connection speeds, especially if the application deals with large files, such as video files. 
<br/><span style="margin-left:2em">-To reduce the risk of this problem, all of the company's offices would need to pay to have their network upgraded to suit their particular needs.
<br/>The transition to remote might take a while and result in a lot of downtime and issues.
<br/><span style="margin-left:2em">Before the transition is rolled out to the entire company, select a test group of a few people to use it daily and have them record any problems they encounter. It is better to have this small test group to have issues instead of the entire company.
<br/>Since the application is going online, there is always the concern of network security and how the employees are accessing the program.
<br/><span style="margin-left:2em">To reduce the risk of this problem, make sure employees are educated on being safe on the internet. Distribute employee laptops if they are allowed to work from home and only allow the laptops to connect to the internet if a company-issued VPN is running. Hire a cybersecurity expert team to monitor network traffic and ensure all security components are up to date.


