# comp3506-project-solved
**TO GET THIS SOLUTION VISIT:** [COMP3506 Project Solved](https://www.ankitcodinghub.com/product/comp3506-7505-project-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;116288&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;COMP3506 Project Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
Task

This project will require you to implement algorithms efficiently in order to solve desired tasks. In particular, you will be required to:

1. Complete programming tasks in reference to a given algorithm or desired efficiency.

2. Write a report explaining the efficiency of your implementation.

The specific details required for each of these two points are outlined in the questions below.

Submission Details

• Autograder: You must submit the programming part of your assignment to the autograder portal. You should only submit either the Java or Python code according to the language you have used. You must not submit your report PDF here. If you do so and fail to submit the project PDF to the Report Portal (see below), penalties will apply.

You should submit only the following files:

For Python: hospital 1.py, hospital 2.py, hospital 3.py, patient.py, login system.py tree of symptoms.py, alert system.py .

For Java: Hospital1.java, Hospital2.java, Hospital3.java, Patient.java, LoginSystem.java TreeOfSymptoms.java, AlertSystem.java1.

Do NOT modify and do NOT submit the interface files (ending with *Base.java/ * base.py)

• Report: You must submit a PDF export of your report to the report portal. You must use the template provided for your report. If you do not use the template or you modify the template in anyway, with the exemption of adding your answers in the box provided, you will incur a penalty.

Programming Details

Java Instructions

• Remove the main() method and any System.out.print() calls before submitting to the autograder.

Python Instructions

• You must use Python version 3.7 or higher.

• You should NOT use Python built-in sort methods, such as list.sort() or sorted(). You should NOT use Python built-in list methods, such as append, clear, count, copy, extend, index, insert, pop, remove, reverse, sort, or built-in methods min or max. If you wish to utilise similar functionality, you should implement the needed methods yourself.

• You should NOT use dictionary dict nor {}.

• Remove main method and print functions before submitting to the autograder.

Academic Misconduct

1 Hospital Appointment System

In this question, you need to implement an appointment system for three different hospitals, that would allow patients to book appointments according to their desired time. In particular, you need to complete the following functionality:

• iterator/ iter – iterates through the patients in the correct order according to their time

• addPatient/add patient – adds a new patient to the system. Returns True if the patient is successfully added, returns False otherwise.

It is known that all three hospitals work from 08:00 to 18:00 with a lunch break from 12:00 to 13:00. Additionally, each hospital has different time complexity requirements for each function. Based on these requirements, you have to chose the best data structure to represent the appointment system, as well as the best algorithm to order the patients by their times. The requirements are the following:

addPatient/add patient; iterator/ iter – as quickly as possible.

• Hospital 2: addPatient/add patient in O(n); iterator/ iter – as quickly as possible. If two patients requested the same time, give a priority to the patient that is already in the system.

• Hospital 3: addPatient/add patient in O(1); iterator/ iter – as quickly as possible. If two patients requested the same time, give a priority to the patient that is already in the system.

1.1 Programming

In the files Hospital1.java/hospital 1.py, Hospital2.java/hospital 2,py and Hospital3.java/hospital 3.py, you should implement the methods in the interface HospitalBase.

1.2 Report

Using the Gradescope document template provided, you must complete a report which analyses your code and the algorithms you have implemented. In the report, for each of the three hospitals you should:

1. State the data structure used to store patients and explain why this data structure is the best for the task in hand.

2. Describe the algorithm used to order the patients. Briefly explain how it works, from where it is called (from iterator/ iter or from addPatient/add patient) and why it is the best algorithm in comparison with the other known algorithms.

3. Assuming n to be the number of patients, state the best-case (Ω) and worst-case (O) time complexity of iterator/ iter and addPatient/add patient with respect to n.

PROJECT CONTINUES ON NEXT PAGE

2 Login System

Aside from keeping track of appointments throughout the day, hospitals are also required to store a secure collection of users who have signed up to the hospital appointment system. To accomplish this, you are required to implement a login system whereby users can sign up by providing their email address and password. Users must also be able to be removed from the system and change their password.

The login system should be implemented in the form of a hash table, with the following characteristics:

• Size: The hash table should be initialised to a static size M = 101. If the number of users exceeds the current size, resize the hash table using a tripling strategy: triple the size of the hash table.

• Hash Function: You should implement a hash function that consists of a custom hash code and a compression function.

– Hash Code: For the hash codes use the following function. Assume that the key represents a string s : s1,s2,s3,…,sn; and An represents an ASCII value for the letter sn, and c = 31 is a constant. Then the hash codes should be calculated as follows:

– Compression Function: For the compression function, use a division by a hash table size:

h2(y) = y mod M

• Collision Handling: Use linear probing to handle collisions.

2.1 Programming

In the files LoginSystem.java/login system.py, you should implement the methods in the interface LoginSystemBase.

2.2 Report

1. What is the advantage of storing a hash code of the password instead of the plain text password?

2. Do we need to store the email in the hash table? If your answer is yes, explain why it is necessary. If your answer is no, explain how you use the email (if you use it at all)?

3. Which of the following is an example of a collision? Explain your answer for both cases

(a) Two users have the same email hash

(b) Two users have the same password hash

4. What is the type of hash code function being used? Explain why it is suitable for use in this hash table.

PROJECT CONTINUES ON NEXT PAGE

3 Tree of Symptoms

Figure 1: Tree of symptoms

Recently graduated doctors get nervous interviewing patients for the first time, so the hospital made a simple cheat-sheet of symptoms they need to enquire about. The cheat-sheet is in the form of a tree, where each node represents a symptom and its severity level, and a higher severity number indicates a more severe symptom. Following the tree of symptoms helps the new doctors to select the questions to ask and to eventually diagnose a patient with the correct disease.

An experienced doctor noticed that the current version of a cheat-sheet is not very efficient and proposed to improve it by arranging mild symptoms on one side of the tree, and severe symptoms on the other side. Additionally, he proposed to start an enquiry with the symptom of a particular severity, so that new doctors can quickly identify if the disease is serious and call for back-up if necessary.

You are asked to perform this upgrade of the cheat-sheet. In particular, you need to restructure a tree of symptoms in the following way:

1. The new root symptom must be the symptom with the smallest severity that satisfies severity &gt;= threshold. If no such symptom exists, use the most severe symptom among existing as a new root node.

2. For all the nodes, the left sub-tree must contain more mild symptoms, and the right sub-tree must contain more severe symptoms.

For simplicity, we further introduce the following assumptions about the tree:

• There is at least one symptom in a tree.

• Each symptom has a unique severity level (no duplicates).

3.1 Programming

In the file TreeOfSymptoms.java/tree of symptoms.py, you should implement the methods in the base class

TreeOfSymptomsBase.

3.2 Report

1. What is the type of the restructured tree?

2. For any given binary tree, is the reconstructed tree balanced? If so, explain why. If not, give a counter-example. 3. For any given binary tree, is the reconstructed tree unique? If so, explain why. If not, give a counter-example.

PROJECT CONTINUES ON NEXT PAGE

4 Alert System (COMP7505 Students Only)

Figure 2: Graph of patients. Red node is the person with the infection, yellow and green nodes are their contacts of different degrees.

In this question, you need to implement an alert system that is capable of keeping track of people contracting some virus. The alert system should be organised in the form of a graph, where a node represents a person, and an edge between two nodes represents the fact that those two people were in contact with each other. If the virus is not contagious, only the person with the virus is marked as infected in the system (degree 0). However, if the virus is contagious, their contacts (degree 1) and the contacts of their contacts (degree 2) might be infected as well. Depending on how contagious the virus is, the neighbors of different degrees must be marked as infected.

Programming In the files AlertSystem.java/alert system.py, you should implement the methods in the abstract class AlertBase.
