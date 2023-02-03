                                                                  Software Engineering (IT-314)

                                                                            Lab - 1

**Name : Kalp Pandya**  
**Id : 202001466**  
**Date : 03-02-2023**  

<h1 align = "center">
Question 1. Identify FRs and NFRs: 
</h1>
<ul>
<li><h3>Identification of Functional requirements</h3></li>
<ol>
<li> <b>Registration of new User :</b> Any institute member who wishes to use the library's services must sign up for access to its resources in the system. Once the person had successfully registered, they would be given a user ID and password. (S) He must use these identities for any upcoming Library Information System transactions.</li> 
<li> <b>Searching of Books :</b> A user of the Library Information System who has registered can log in by entering his employee ID and password. After successfully logging in, the user is directed to the "Home" page, where they can access the several LIS functions, including book search, book issue, book return, and book reissue. Any employee ID that isn't registered with LIS will see the login prompt return with a login failure notice. When a registered user enters their password incorrectly, the same thing happens. However, the security question that the user set during registration is displayed together with an input field for answering it if an incorrect password is entered three times in a row. If the security question is correctly answered, a new password will be issued to the user's email address. If the user didn't respond to the security question correctly, his LIS account would be suspended. He must speak with the administrator to make it active once more. </li> 
<li> <b>Issuing a Book :</b> Any member of the Library Information System may add books to his account so long as:  
<ol>
<li> The book is in the library, so you can find it by searching for it in Library Information System.</li>
<li> No other member has issued the book at this time.</li>
<li> The current user has not issued the maximum number of books that can be issued.</li>
</ol>
The book is provided to the member if the aforementioned conditions are satisfied. Remember that this FR would be lacking if the phrase "limit books authorised to be supplied to a member" were used. This number is presumably fixed at ten for academics and four for research scholars and students.
The successful issue of a book is reflected in the user account update.</li> 
<li> <b>Returning a Book :</b> We shall suppose that a book is available for a period of time of fourteen days. In other words, the book must be returned by the appropriate LIS member within the next 14 days of its issuance. This return day period may vary depending on the category of the book, such as fiction, business, or academic. The successful return of a book is reflected in the user account. If the book is not returned within the allotted time, the library policy will apply and a fine will be assessed.</li> 
<li> <b>Reissuing a Book :</b> Any member who has issued a book could find out that his deadline has passed by just fourteen days. If so, he might opt to reprint the book and ask for permission to keep it for an extra 14 days. A member can renew a book only three times before needing to return it. Once a book is successfully reissued, the data in the user account is updated.
<li> <b>Add/Drop Books :</b> Only the administrator of the Library Information System would have access to this feature. When necessary, the administrator might add new books to the system as well as remove existing ones.</li> 
</ol>

<li>Identification of Non-Functional requirements</li>   
</ul>
<ol>
<li> <b>Performance Requirements :</b> The server for the Library Information System would be able to do tasks as requested in a fair amount of time. The total number of users who can simultaneously access the system should be at least 200. This system ought to be available always.</li>
<li> <b>Security Requirements :</b> The system would only be accessible to authorised users. This system should only be accessible over the institute's LAN. In the LIS database, passwords cannot be kept in plain text; instead, a hashed value must be kept.</li>
<li> <b>Different Roles and Features :</b> Administrators will have no trouble keeping track of clients' log-in times with our proposed system.</li>
<li> <b>Design Constraints :</b> The LIS must be created as a web application that works with the most recent iterations of the aforementioned web browsers, including Google Chrome 10, Firefox 4, Internet Explorer 7, and Opera 9.</li>
<li> <b>Accessibility and Ease-of-use :</b> The suggested system would be user-friendly and provide a Graphical User Interface (GUI). The suggested system would consist of a desktop GUI application placed on a server that serves as the program's compute root node.</li>
<li> <b>Reliability :</b> As expected, the Server would carry out the desired operations. The system performs its functions with greater precision, including user registration, user validation and authorization, book search and issue operation, return status, and database updates by synchronizing between application and database.</li>
<li> <b>Maintainability :</b> Maintaining and expanding the proposed system would not be difficult. The running application would not be harmed by even the smallest system modification.</li>

</ol>

<h1 align = "center">
Question 2. : Identify Scope, Features and Non-functional aspects
</h1>

<ul>

<li><b>Scope :</b> The primary objective of the project is to provide an application for those who have hearing loss. Their daily needs for communication and safe travel will mostly benefit from it. This software would have a massive user base and receive government funding because it will be for the benefit of society. They make up about 5% of the world's population. Being a real-time system and a medium for user and environment interaction, it will be a very effective solution. </li>
<li><b>Features :</b> Artificial intelligence (Al) will be used by our smartphone application to identify important sound occurrences of importance to this community, such as car horns and newborns. These will mostly consist of the continuous logging and immediate alerts that are essential to the user. The system will employ several colour schemes for urgent notifications, monitor behaviour and alarms, and convey them to any members of its family or colleagues so they may take the appropriate action. The network of the government will be directly connected to the system, allowing it to execute safety-related policies.</li>
<li><b>Non Functional Aspects :</b> The application should be optimized in Android. The application should have low latency so that it works in real time.</li>

</ul>
