# CS-370: Emerging Trends in Computer Science

## The Treasure Hunt Project

### Introduction
The treasure hunt game is a game where the human player needs to find the treasure before the non-player character (NPC), which represents the pirate. In this instance, I, as the developer, was tasked with designing the NPC as an intelligent agent to represent the pirate. The goal of the pirate is to find the treasure before the human player. 

### Game Framework
Some starter code and a sample environment were provided. The starter code consisted of a convolutional neural network with several layers. What needed to be developed, was the intelligent agent and training algorithm to optimize the intelligent agent's performance i.e get through the game in an optimal time and find the treasure before the human player.   

### Game Development
I coded the training algorithm to train the intelligent agent. That consisted of submitting multiple epochs to the game. The agent would then start out playing at a high exploration rate, which I would decay over time and replace with exploitation, using saved episodes from previous games. To optimize performance, the agent would only use successful episodes. Through this combination of exploration and exploitation, and over many epochs, the model would then optimize the agent's performance by getting it to the treasure in an optimal way and in the shortest amount of time.

### Reflection

#### What computer scientists do and why it matters
Computer scientists design, analyze, and implement computational systems to solve real-world problems efficiently, securely, and ethically. They:
- do problem formalization by translating ambiguous real-world needs into precise computational problems
- design and analyze algorithms, creating procedures that are correct, efficient, and scalable
- build secure, reliable, and maintainable software and hardware systems
- extract insights from data, build models, and enable automation
- ensure that systems can resist attacks, failures, and misuse
- design systems that are user-friendly and that people can use safe and effectivlely

What a computer scientist does matters because:
- society is increasingly dependent on computational solutions for problem-solving
- a single algorithmic decision can affect millions of users
- poorly designed systems can introduce vulnerabilities, bias, privacy violations, and safety concerns; this would violate the principle of doing no harm and breaks fown trust in the system
- computer science drives innovation across all sectors of society

#### How I approach a problem as a computer scientist
As a computer scientist, I approach a program systematically by:
- Defining the problem precisely: identifying stakeholders, constraints, success criteria and failure modes, and converting the ambiguous requirements into measurable objectives.
- Decomposing the problem by breaking it up into modules, data flows, and decision points, and identifying what can be solved programatically and what would require human intervention.
- Model the problem with graphs, statemachines, data structures, or optimization models, then determining computational complexity and feasibility.
- Designing the solution by selecting or designing the algorithms, architecting the system, taking performanace, scalability, and maintainability into consideration.
- Iterating and improving the implemented system through optimization based on metrics, user feedback, and real-world behavior.
  
### My ethical responsibilities to the end user and organization
My ethical responsibilities to the user are:
- to ensure privacy protection by collecting only the necessary data, minimizing data retention, and transparent policies about data use.
- to ensure system security by implementing least privilige access, secure defaults, encryption, continuous monitoring, and preventing vulnerabilities that could compromise the system
- to ensure fairness and bias mitigation by identifying and reducing algorithmic bias, validating models accross all demographic groups, and avoiding opaque black box decisions that might impact the rights or opportunities of users.
- to respect user autonomy by avoiding manipulative design patters (dark patterns) and providing the user with meaningful consent and control.

My ethical responsibilities to the organization are:
- to act with integrity and professionalism through honest reporting of risks and not falsifying or hiding vulnerabilities.
- to conform to security and compliance protocols by following legal requirements (GDPR, HIPAA).
- to innovate responsibly by evaluating the societal impact of new techmologies before deploying them.
- to manage risks through early detection of threats and by recommending mitigations grounded in evidence and best practices.




