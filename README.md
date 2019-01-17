# <img src="http://www.rice.edu/_images/rice-logo.jpg" width=180> Comp427, Spring 2018, Homework 1
## Rational Paranoia
The homework specifications, as well as the corresponding course slide decks,
can be found on the [Comp427 Piazza](https://piazza.com/class/jqifhp864b37ju).
This assignment is due **Thursday, January 17 at 6 p.m.**

You will do this homework by editing the _README.md_ file. It's in
[MarkDown format](https://guides.github.com/features/mastering-markdown/)
and will be rendered to beautiful HTML when you visit your GitHub repo.

## Student Information
_Student name_: Tian Lan

_If you contacted us in advance and we approved a late submission,
please cut-and-paste the text from that email here._

## Problem 1
- Scenario: Documents: As head of IT for an international law firm, you are responsible for a document management system; some documents stored there are about sensitive legal, financial, or political matters
- Assumptions:
  - The document management system refers to some sort of digital document system, not for papery docuemts.
  
- Assets:
  - Legal documents that are related to clients. These documents might contain commercial secrets, firm private information or personal identification information and etc. It is very important to protect such information.
  - Employee information. The firm stores and has access to its employees’ personal information, such as phone number, salary, address, date of birth and etc. We need to protect the privacy of the firm’s own employees.
  - The firm’s financial information. Contracts and many financial agreements could be critical for running the firm. It is important to keep them in a safe place.
  - The physical device on which the document management system is deployed. If the device is exposed to bad people, it could be damaged, or someone could install malware on it and intercept information.
  
- Threats:
  - Thieves that might break into the firm physically and steal information.  
  - Cyber thieves that break into the firm’s system from internet or malware and steal information.
  - Some employees download the documents on their desktop, while forget to lock their desktop after they leave. Bad people could potentially access these documents using their unlocked desktop.
  
- Countermeasures:
  - Keep the document system physical server in a safe place, such as a locked server room. Or alternatively, rent a third-party server with not physical security concern. Cost would be it’d increase cost for maintaining the server. Benefits would be it isolate the physical server from the public.
  - Encrypted all the documentary data if the document management system is deployed the on third-party server. Cost would be the time to encrypt and decrypt data everything upload or download documents. Benefits would be it’d make it harder to steal information from the server even if someone unauthorized has access to the server.
  - Enforce employees to review or edit all documents via the system (providing some kind of preview user interface) but save documents locally. Cost would be it’d make the documents less accessible or say inconvenient to access. Benefits would be it’d make the server more centralized, and thus documents also less accessible to bad people.

## Problem 2
- Scenario: Grading: You are grading homework submissions for a class of 200+ students. 
- Assumptions:
  - "Students" refers to college students.
  - "Homework" refers to hand-written/hand-typed problem sets or anyting that could be presented on paper or screen.
  
- Assets:
  - Homework submissions (content) of all students. Someone else might take away the submissions if they are submitted or returned in a public space. We don’t want other students that have not taken this class yet to access these submissions, and we don’t want students who submitted their work to have a missing grade.
  - Names, email address and student IDs. Most often, the information is printed on the homework. These are private personal information that we should protect.
  - Authorization/the ability to modify grades. We for sure don’t want students to do anything they want to their grades.
  - Grade information. Scores of a student should be private to himself/herself as it is privacy. 
  
- Threats:
  - Other people that want to take away the work of the current students. As mentioned, we don’t want other students that have not taken this class yet to access these submissions, and we don’t want students who submitted their work to have a missing grade.
  - Stalkers that steal personal information from homework submissions.
  - Bad-intentional students who want to enter or modify their grade, or modify submission after turning in.
  
- Countermeasures:
  - Ask students to upload soft copies instead of turning in hard copies. Cost: need to develop / use an online learning management system, which is extra work for instructors and students. Benefits: it makes it harder for others access a student’s submission, in case of submitting and returning. So personal information and content are protected. Since the grades will then also be maintained on the online system, it also makes it harder for bad-intentional students to modify scores or submissions without authorization. 
  - If hard copies need to be turned in, seal them in provided envelops when submitting and returning. Cost: cost of enveloping, time for sealing and unsealing. Benefits: sometimes turning hard copies is necessary for take-home exams. Sealing them in envelops also protects personal information and content, and prevents students from modifying after turning in. 


## Problem 3
- Scenario: You are a manager of a private sport physical therapy clinic who have tens of patients.
- Assumptions:
  - You are responsible for protecting the patients' information they give you.
  - Patients trust you.
  
- Assets:
  - Patient information, including their names, addresses and phone numbers. They are privacies that need to be protected.
  - Patients’ medical records. They are absolute privacies.
  - Patients’ payment information.
  - Internal documents of the clinic, including financial documents and human-resource documents.

- Threats:
  - Privacy invaders. For example, some patients could be celebrities as sport stars, and some reporters might try to obtain their medical record, which invades patients’ privacies. 
  - Credit card thieves. They could steal patient information and used it illegally.

- Countermeasures:
  - Do not save patients’ payment information. Cost: makes it inconvenient for regular patients as they need to fill in the same payment information every time.  Benefits: less chance to have liability of leaking payment information if you simply don’t record them.
  - Buy good safes to store patients’ medical records, and develop polices for accessing the documents, such as logging a time stamp, and requesting a signature every time an employee needs to access a document. 


