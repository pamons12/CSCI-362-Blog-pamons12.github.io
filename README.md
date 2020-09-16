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
<span style="margin-left:2em">The readings this week seemed to focus on the importance of incorporating Test-Driven Development and establishing non-functional and functional requirements before the development phase even starts. Establishing non-functional and functional requirements before the development begins is essential to project organization and possible issues down the road. If a developer does not have a clear understanding of both the non-functional and functional requirements they could forget about a feature that could result in catastrophic errors and a delayed release date. I think the "Magical Number Seven" page ties in well here, this article states that the human brain can only store 7 (+-2) objects in their short term memory. The point is if all the functional and non-functional requirements are not laid out in an organized fashion the user could very easily forget to implement a feature, especially in big projects. After all, it is much easier to add features before development begins, instead of adding features mid-development or even worse at the end of development. With regard to incorporating test-driven development, all engineers should develop tests throughout the development process to ensure their software is behaving as intended.
4.5) Using the technique suggested here, where natural language descriptions are presented in a standard format, write plausible user requirements for the following functions: 
a) An unattended gas pump system that includes a credit card reader. The customer swipes the card through the reader, then specifies the amount of fuel required. The fuel is delivered and the customer's account is debited. 
Function: Issues gas
Description: Issue gas by charging the user for the amount of gas pumped
Input: pin/zipcode for debit or credit card, the grade of fuel
Source: Charging the credit card for the amount pumped based off of grade
Outputs: The gas the user pumps
Destination: Selection of fuel grade
Action: The gas filling system is at zero when no transaction is being made. When the card, card details, and the grade of fuel is selected, the user can begin pumping gas. 
Requires: Requires a valid card with details and the grade of fuel
Precondition: User must have a valid credit/debit card with details to use it
Post Condition: The gas is issued
Side Effects: None
b) The cash-dispensing function in a bank ATM. 
Function: Dispense money from ATM
Description: Given the amount of money is dispensed to the user if they have a valid debit card and pin
Input: Amount of cashback, debit card, and pin
Source: Keypad to get the amount of cash wanted and pin. Card reader to insert a debit card
Outputs: The cash the user requests
Destination: Amount deducted from users card
Action: The ATM  is in 0 state when no transaction is happening. When the user inserts a card the ATM asks for a pin. Once a valid card and the pin is given the user can select the amount of cash they want. Once the amount of cash is inputted the ATM makes sure the card has enough money for that. If it does the card is given back and the money is dispensed.
Requires: Requires the user's card and pin, the amount of money the user wishes to take out
Precondition: User must have enough money on the card for the withdraw and a valid debit card with pin
Postcondition: The cash is dispensed to the user
Side Effects: None
c) In an internet banking system, a facility that allows customers to transfer funds from one account held with the bank to another account with the same bank.
Function: Transfer money
Description: The given transferred amount is deducted from the sender's account and added to the receiver's account. 
Input: Account number of receiver and amount to be transferred
Source: Transfer money from source account to receivers account for a given amount
Outputs: The given amount of money arrives at the destination account
Destination: Selection of how much to send from the sender's account
Action: The system is in 0 state when no transaction is happening. When a user wants to transfer money, the system asks for the amount to be transferred and the destination account details. After this information is given the funds are transferred to the destination
Requires: Requires amount to be transferred and details for both source and destination accounts
Precondition: Enough funds to supply the transfer and the details for both source and destination accounts
Postcondition: The funds are transferred from the source to the destination account
Side effects: None
4.6) Suggest how an engineer responsible for drawing up a system requirements specification might keep track of the relationships between functional and non-functional requirements.
Functional Requirements
Describe what the system should do, requirements of individual system features
Non-functional Requirments
Describe the expectations of the system
An engineer could keep track of these by writing down all of the non-functional requirements and underneath each one write what functional requirements will be needed to satisfy this non-functional requirement.
4.7) Using your knowledge of how an ATM is used, develop a set of use cases the could serve as a basis for understanding the requirements for an ATM system.
The user does not have a valid card or forgets the pin so no transaction occurs
The user wishes to make a deposit. The user inserts their debit card and pin. The user selects the deposit option and asks for the user to insert their cash. The user inserts cash and once the machine is done counting the user verifies the amount. ATM deposits funds to the account and returns the card to the user, the transaction is complete.
The user wishes to make a withdraw. The user inserts their debit card and pin. The user selects the withdraw option and inputs the amount of cash they would like to withdraw. The ATM verifies the inputs and returns the card to the user. Once the card is returned the cash is dispensed, the transaction is complete.

*** HW6: Chapter 2
2.1) Suggest the most appropriate generic software process model that might be used as a basis for managing the development of the following systems. Explain your answer according to the type of system being developed: 
1. A system to control antilock braking in a car
I think the most appropriate generic software process model for this example would be the waterfall model. I choose this model because it is focused on making sure there are no flaws before deployment and the antilock braking is a critical system in ensuring the driver's safety.
2. A virtual reality system to support software maintenance
I think the most appropriate generic software process model for this example would be incremental development. I choose this model because it would allow the developers to easily make changes or maintenance to the software based on the feedback of the users. It is also not a critical system
3. A university accounting system that replaces an existing system
I think the most appropriate generic software process model for this example would be integration and configuration. I choose this model because an existing system is being replaced and some of that data will be reused. 
4. An interactive travel planning system that helps users plan journeys with the lowest environmental impact
I think the most appropriate generic software process model for this example would be incremental development. I choose this model because it is likely developers may want to update the systems algorithm that figures out how large an environmental impact a trip is. 


