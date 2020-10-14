---
layout: post
title:  "HW5: Chapter 4 and Reflections"
date:   2020-009-10
categories: Software Engineering Homework
---

4.5) 	Using the technique suggested here, where natural language descriptions are presented in a standard format, write plausible user requirements for the following functions:

An unattended gas pump system that includes a credit card reader. The customer swipes the card through the reader, then specifies the amount of fuel required. The fuel is delivered and the customer's account debited.

The cash-dispensing function in a bank ATM.

 In an internet banking system, a facility that allows customers to transfer funds from one account held with the bank to another account with the same bank.


Gas pump user requirements:

The system shall present a choice of debit or credit

The system shall process card choice and give prompt accordingly

The system shall ask debit users for their pin numbers

The system shall ask credit users for their zip codes

The system shall prompt user to select fuel grade

The system shall dispense fuel according to user selection

The system shall charge the account


Cash-dispensing function in a bank ATM user requirements:

***Assuming this is referring specifically, and only, to the cash-dispensing function, the preceding requirements to this function are omitted, such as authentication, and account selection. As well as requirements that would follow withdrawal, such as further user action, or card ejection prompt.***

The system shall get user input of withdrawal amount

The system shall alert the user if they are going to overdraw their account

The system shall ask user to confirm selection

The system shall dispense the inputted selection of money

The system shall ask user of receipt selection




Transferring funds between accounts within the same bank user requirements:

***Again, assuming this is referring to the specific action of transferring funds, where authentication and authorization have already been addressed.***

The system shall get account information of receiving account

The system shall verify information

The system shall prompt user for amount

The system shall send process request




4.6) 	Suggest how an engineer responsible for drawing up a system requirements specification might keep track of the relationships between functional and non-functional requirements.

Constructing the system requirements and maintaining clear relationships between functional and non-functional requirements is an involved process. Decisions have to be made regarding the importance of each non-functional requirement, and how it might be related/integrated with functional requirements. When drawing up the system requirements specification, the engineer should be careful to either clearly distinguish between the functional and non-functional requirements via separating them, or having some way of indicating the non-functional portions of the system. A lot of critical non-functional requirements, like reliability or ease of use, can be expressed in terms of functional requirements as well. For example, a functional requirement could be that a system must have a user log in. The non-functional requirement associated with this is that the system must be secure via set levels of authentication. Thus, in the system requirements specification, the types of non-functional requirements that are related to functional requirements can be presented together such that some non-functional requirement has a set of related functional requirements or vice versa.

 4.7) 	Using your knowledge of how an ATM is used, develop a set of use cases that could serve as a basis for understanding the requirements for an ATM system.

Users of an ATM:
Person with an ATM/Debit card

Use Case 1: User wants to make a withdrawal

User puts in card associated with relevant account, and their pin number

User selects withdrawal option, and selects amount to withdraw

User receives dispensed money

User is prompted to remove their card

User is given a receipt of the transaction


Use Case 2: User wants to make a deposit

User puts in card associated with relevant account, and their pin number

User selects deposit option, and selects amount to deposit

User insert money

User removes their card

User receives a receipt of the transaction


Use Case 3: User wants to make a withdrawal but changes their mind

User puts in card associated with relevant account, and their pin number

User selects withdrawal option, and selects amount to withdraw

User exits selection

User removes their card


Use Case 4: User is not authenticated

User puts in card associated with relevant account, and their pin number; invalid

User is prompted to re-enter pin

User re-enters pin; invalid

User is prompted to re-enter pin

User re-enters pin; invalid

User is informed account is locked

User is asked to remove card
