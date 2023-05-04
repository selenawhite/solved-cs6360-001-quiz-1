Download Link: https://assignmentchef.com/product/solved-cs6360-001-quiz-1
<br>
<strong> </strong>

<strong> Database Design </strong>

<strong> </strong>

<ol>

 <li>Draw an ER diagram for the following case: Assume there are two entities, Student and Room, which is a part of dorm. A student can share a room with his/her friends. At least two students share a room. There is no vacant room. A student can stay in his/her house, which is not room of the dorm. (20 points)</li>

</ol>

<strong> </strong>

<ol start="2">

 <li>Consider an ONLINE_AUCTION database system in which members (buyers and sellers) participate in the sale of items. The data requirements for this system are summarized as follows:</li>

</ol>




<ul>

 <li>The online site has members, each of whom is identified by a unique member number and is described by an e-mail address, name, password, home address, and phone number.</li>

 <li>A member may be a buyer or a seller. A buyer has a shipping address recorded in the database. A seller has a bank account number and routing number recorded in the database.</li>

 <li>Items are placed by a seller for sale and are identified by a unique item number assigned by the system. Items are also described by an item title, a description, starting bid price, bidding increment, the start date of the auction, and the end date of the auction. Items are assigned to different categories.</li>

 <li>Buyers make bids for items they are interested in. Bid price and time of bid is recorded. The bidder at the end of the auction with the highest bid price is declared the winner and a transaction between buyer and seller may then proceed.</li>

 <li>The buyer and seller may record feedback regarding their completed transactions. Feedback contains a rating of the other party participating in the transaction (1–10) and a comment.</li>

</ul>

<strong> </strong>

Draw the Enhanced Entity-Relationship diagram for the ONLINE_AUCTION database. (40 points)

<strong> </strong>

<ol start="3">

 <li>Design an ER schema for keeping track of information about votes taken in the U.S. House of Representatives during the current two-year congressional session.</li>

</ol>




<ul>

 <li>The database needs to keep track of each U.S. STATE’s Name (e.g., ‘Texas’, ‘New York’, ‘California’) and include the Region of the state (whose domain is {‘Northeast’, ‘Midwest’, ‘Southeast’, ‘Southwest’, ‘West’}).</li>

</ul>




<ul>

 <li>Each CONGRESS_PERSON in the House of Representatives is described by his or her Name, plus the District represented, the Start_date when the congressperson was first elected, and the political Party to which he or she belongs (whose domain is {‘Republican’, ‘Democrat’, ‘Independent’, ‘Other’}).</li>

</ul>




<ul>

 <li>The database keeps track of each BILL (i.e., proposed law), including the Bill_name, the Date_of_vote on the bill, whether the bill Passed_or_failed (whose domain is {‘Yes’, ‘No’}), and the Sponsor (the congressperson(s) who sponsored—that is, proposed—the bill).</li>

</ul>




<ul>

 <li>The database also keeps track of how each congressperson voted on each bill (domain of Vote attribute is {‘Yes’, ‘No’, ‘Abstain’, ‘Absent’}). Draw an ER schema diagram for this application. State clearly any assumptions you make.</li>

</ul>







(40 points)