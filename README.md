## Offensive Security 

### Red Team

You've been tasked with enumerating the target network from a "black box" position (minimal knowledge of the target environment) starting with a foothold on a single endpoint. One of your goals is discovering as many vulnerabilities as you can and documenting them in accordance with community resources such as CWE and CVSS. You'll also get to apply TTPs you've learned throughout this course and perform exploits as the opportunities present themselves. Document how you went about executing TTPs and whether they were successful or not.

#### Red Team Staging

You will be provided with multiple compromised endpoint instances as well as VPN access to its LAN to facilitate tool execution. For example, if you wanted to perform attacks from Kali Linux, you would activate an OpenVPN connection from Kali Linux to the target network.

#### Red Team Objectives (RTOs)

- RTO1. Enumerate the target network, gleaning as much information as possible about the various hosts and their configurations. Document in detail what tools were used and how much you were able to reveal.
- RTO1a. Create a professional network topology of the target environment for inclusion in your final report.
- RTO2. Discover vulnerabilities on targets hosts on the network. There will be at least one web application for you to discover and test against, in addition to several other instances running various operating systems with unknown configurations.
- RTO3. Build/customize and utilize at least one custom Python tool to aid in your team's offensive efforts.
- RTO4. Exploit and gain access to as many host instances as possible, and as deeply as possible.

While hacking is great fun, be sure to take plenty of screenshots and document what worked and didn't work in order to produce a high quality report deliverable. Remember the goal is to help your client understand their risks.

### Red Team RoE

- Do not attack or damage the hypervisor software on instances
- Read and abide by the [HackTheBox AUP](https://www.hackthebox.com/aup)
- Do not alter the firewall or port configurations on the instances
- Do not update the OS or existing software on the instances
- Do not attack tooling systems
  - OpenVPN server instance
  - SIEM instance
  - Threat hunter instance
- Do not damage the operability of the instances
- Do not delete data on the instances
- If you need a reboot on an instance, contact the white team


## Assignments & Deliverables

Keep an eye on Canvas for assignments due this week.

- Remember to complete nightly Project Report assignments. These assignments are easy to forget as you get swept up in interesting project subject matter.
- Necessities such as team agreement (conflict resolution, etc.) and project plan will be created in your Project Prep assignments. Instructor approval is required before progressing to the next Project Prep assignment.
- By demo day, you'll need these deliverables assembled:
  - Demo day slide deck.
  - Project report.
  - Project plan.
  - GitHub repo.
  - Google drive docs (if used).
- Track your individual contributions throughout the project so that you can easily submit your individual contributions writeup on demo day for grading.

## Standup

Every day, the instructional team with circulate to your group for a formal "Standup Meeting". Standup should take approximately 10 minutes per team. Some instructors will opt for a "retro" later in the day to review how things went.

> Standups give the instructional team insight into the current status of your project and the progress the team hopes to make each day.

During standup, each team member will address these three points:

  1. What you individually accomplished yesterday.
  1. What you individually plan to accomplish today.
  1. Anything that is blocking you from making progress.

## Presentation Prep

Practice your presentation prior to the final presentation day. This is typically scheduled by the instructional team. During the practice presentation, the instructional team will provide constructive feedback about the flow of the presentation and delivery of the subject matter.

Practice and prepare your technical demonstrations in advance of demo day to rule out any quirks/bugs.

General slide deck guidelines:
- The presentation slides must use the aesthetic formatting of the [template slide deck](https://docs.google.com/presentation/d/16LOH5KiIVGq3oJReWa2kVO_VgQZlYG9K4vNXJuJNJdE).
  - Remember to create your own copy of the template and do not edit the template itself.
- Ensure your timing is no more than 25 minutes long, including some time at the end for questions.
- Present from the final product, deployed site, or offical documentation that you produce.
- Each member should introduce themselves with their personal pitch.
  - The "About Us" page provides a great backdrop for this portion of the presentation.

It is okay to use presenter notes/outlines but remember to avoid reading notes verbatim and to present naturally as if speaking to a colleague.

### Demo Day Presentation Requirements

Components of the presentation must include:

- A. Team members individually introduce themselves using their own professional pitch. (3 min, explain why they are making the career change).
- B. Topical overview (2 min).
  - B1. As the "Problem Domain", describe the project scenario you were assigned and the overall client requirements.
    - B1a. Compliance requirements.
    - B1b. Security systems requirements.
- C. Technical demonstrations of solutions (12 min).
  - C1. Introduce the network topology of your environment.
  - C2. Demonstrate your solution(s) to the problem domain here.
- D. Final thoughts on how the project went (3 min).
  - D1. Each team member should share some final thoughts on the project. Some topics you could discuss here include:
    - D1a. The team's approach to planning and communication throughout the project.
    - D1b. A technical obstacle or two and how those obstacles were overcome.
    - D1c. A portion of the outcome you are particularly proud of achieving.
- E. Q&A (5 min).

The appropriate dress code is business casual - not too formal and not too casual. 

Be cognizant of the environment you're presenting from. A clean backdrop, good lighting, and quality mic and webcam go a long ways.

In addition to the scheduled practice session, you are encouraged to continue to practice on your own. Keep track of the time and adjust accordingly. Practice transitioning speaking segments.

Speak clearly and do not use slang or profanity. Take it seriously and be professional.

> Tip: Slides should be composed of talking points, not lines to be read verbatim! Avoid the "teleprompter" effect and aim for a natural, extemporaneous presentation on demo day.

## Grading

Grade is split between individual effort and the project's technical merit.

Individual effort is graded based on contributions to project deliverables, and professionalism in the presentation.

Technical merit of the project overall is evaluated according the requirements.

### Deliverables

Submit to instructor a single "Project Report" Google Doc. 

Encouraged to adopt an Agile mindset with regards to the development of their project deliverables and regularly solicit feedback from staff regarding their project report, slide deck, and other deliverables. The quality of your reporting will be evaluated and will directly impact the group submission grade. Remember to budget adequate time and attention for project deliverables to ensure a high quality of work is delivered. 

Here is a list of requirements your manager would like to see addressed in your final project report:

#### Red Team Deliverables (RTDs)

- RTD1: Completed [penetration test report](https://www.offensive-security.com/reports/sample-penetration-testing-report.pdf)
  - RTD1a: As you describe the TTPs employed and vulnerabilities discovered in the main body of your report, ensure that you associate them with reputable community resources (e.g. CWE, CVSS, etc.)
  - RTD1b: Replace Appendix B with a table listing all TTPs attempted mapped 1:1 to MITRE ATT&CK

### Resources

Reference the below resources for developing your penetration test report.

- [Writing or Receiving Your First Pentest Report](https://blog.zsec.uk/ltr101-pentest-reporting/)
- [Template OSCP Penetration Test Report](https://www.offensive-security.com/pwk-online/PWKv1-REPORT.doc)
- [Example OSCP Penetration Test Report](https://www.offensive-security.com/reports/sample-penetration-testing-report.pdf)
