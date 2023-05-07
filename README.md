Download Link: https://assignmentchef.com/product/solved-eso207-data-structures-and-algorithms-theory-assignment-3
<br>
<h1>Part 1</h1>

<strong>Problem1</strong>.  Electric cars are gaining popularity. This creates the need for charging stations (CS). A single CS is composed of multiple charging points (CP). One CP can charge one car at a time. So the total number of vehicles a CS can handle depends on the number of CPs present in it.

Assume you want to construct a new CS at IITK. There are <em>n </em>electric cars arriving at the CS each day and you are provided with the arrival time (an integer array arr of size <em>n</em>) and the charging time (an integer array time of size <em>n</em>) of all <em>n </em>cars (for simplicity, assume data is identical throughout the year). Concerning the above scenario, please perform the following tasks.

<ol>

 <li>Design an <em>O</em>(<em>n</em>log<em>n</em>) time greedy algorithm to find the minimum number of CPs required by the CS so that no car waits in a queue for charging.</li>

 <li>Explain the designed algorithm.</li>

 <li>Provide proof of correctness of your proposed algorithm.</li>

</ol>

<strong>Problem2</strong>. Suppose a Binary Search Tree (BST) is used to store students’ names enrolled in the ESO207 course using the format {<em>FamilyName </em>: <em>MiddleName </em>: <em>FirstName</em>}. [Hint: Please note that a single node of the BST contains three elements i.e. Family name, Middle name and First name separated by ‘:’ (colon).]

Page 1 of 2

<ol>

 <li>Design an algorithm that allows user to enter a FamilyName and prints the First and Middle names of all students with the given FamilyName present in the course in <em>O</em>(<em>k </em>+ log<sub>2 </sub><em>n</em>) time. (where <em>k </em>is the number of students whose family name matches the FamilyName inputted by the user).</li>

 <li>Mention assumptions taken for designing this algorithm.</li>

 <li>Also prove the correctness of your algorithm.</li>

</ol>

<h1>Part 2</h1>

<strong>Problem3</strong>. (There are <em>n </em>bags in a sequence and each bag has a certain number of candies. You are given an array <em>B </em>of length <em>n</em>, such that <em>B</em>[<em>i</em>] is the number of candies in the <em>i</em>th bag of the sequence, and a number <em>k</em>. For a contiguous subsequence (say <em>σ</em>) of length <em>k </em>(where 1 ≤ <em>k </em>≤ <em>n</em>) of <em>B</em>, cost of equalization of <em>σ</em>, is the minimum sum of candies that must be added or removed from the bags of <em>σ </em>so that all bags in <em>σ </em>have equal number of candies. The optimal cost of <em>B </em>is the minimum cost of equalization over all the (<em>n</em>−<em>k</em>+1) many contiguous subsequences of <em>B</em>. Given an array <em>B </em>and a number <em>k</em>, design an <em>O</em>(<em>n</em>log<em>n</em>) time algorithm to compute the optimal cost of <em>B</em>. Prove the correctness of your algorithm.

For example, if <em>B </em>= [4<em>,</em>8<em>,</em>7<em>,</em>6<em>,</em>9] and <em>k </em>= 3, then the three subsequences are (4<em>,</em>8<em>,</em>7), (8<em>,</em>7<em>,</em>6) and (7<em>,</em>6<em>,</em>9). The cost of equalizing (4<em>,</em>8<em>,</em>7) is 4, the cost of equalizing (8<em>,</em>7<em>,</em>6) is 2 and the cost of equalizing (7<em>,</em>6<em>,</em>9) is 3. Hence the optimal cost of <em>B </em>is 2.

<strong>Problem4</strong>. ( Given two sequences <em>S </em>and <em>S</em><sup>0 </sup>of length <em>n </em>and <em>m</em>, respectively, design an <em>O</em>(<em>m</em>(<em>n </em>+ <em>m</em>)) time algorithm to find out the minimum number of elements that you need to add in the beginning and end of <em>S </em>so that <em>S</em><sup>0 </sup>becomes a subsequence of <em>S</em>. Prove the correctness of your algorithm.

For example, if <em>S </em>= {4<em>,</em>8<em>,</em>9<em>,</em>3<em>,</em>2} and <em>S</em><sup>0 </sup>= {5<em>,</em>8<em>,</em>3<em>,</em>1}, then the answer is 2 because you only need to add a 5 in the beginning and a 1 in the end of <em>S </em>in order to make <em>S</em><sup>0 </sup>a subsequence of <em>S</em>.


