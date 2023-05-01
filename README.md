Download Link: https://assignmentchef.com/product/solved-cinf362-week-3-html-part-ii
<br>
<h1></h1>

<strong>Agenda</strong>

<ul>

 <li>More HTML

  <ul>

   <li>Semantic markup</li>

   <li>Validating our documents</li>

   <li>HTML Exercise 2</li>

   <li>Validation Exercise</li>

   <li>HTML Research Initial Post &amp; Response</li>

  </ul></li>

 <li>Next Week</li>

</ul>

<h2>Hypertext Markup Language</h2>

<strong>Semantic Markup</strong>

For web pages, the browser interprets the tags used in the .html file and displays them as it comes across them. We can do things like create headings, paragraphs, images, etc. using specific tags intended for those purposes. If we choose to use tags for purposes they weren’t intended for, it could have consequences for users. Of course, we can use things like CSS/JS to cover up poor HTML structure but that only works for entirely visual users. If we want our page to be as accessible/usable for as many users as possible, it is important to use semantic markup correctly. Any tags we use should help define the document structure in a clear manner and separate content from styles. This will allow users that utilize tools like screen readers to access our content and create a better experience overall.

<u>Additional Reading</u>

<ul>

 <li><a href="https://html.com/semantic-markup/">https://html.com/semantic-markup/</a></li>

 <li><a href="https://www.lifewire.com/why-use-semantic-html-3468271">https://www.lifewire.com/why-use-semantic-html-3468271</a></li>

 <li><a href="https://internetingishard.com/html-and-css/semantic-html/">https://internetingishard.com/html-and-css/semantic-html/</a></li>

</ul>




<strong>Validating our documents</strong>

For our pages to present themselves correctly and behave in expected ways, it is important to validate our documents. A document’s code is considered valid when the tags are nested correctly, and everything is placed according to W3C specifications. An example would be a &lt;ul&gt; tag containing only &lt;li&gt; elements inside of it. One rule that trips up students a lot is that &lt;ul&gt; cannot be a direct child of another &lt;ul&gt;. The sample code below demonstrates good and bad structures for lists.

<table>

 <tbody>

  <tr>

   <td width="312"><strong>Good List Structure</strong></td>

   <td width="312"><strong>Bad List Structure</strong></td>

  </tr>

  <tr>

   <td width="312">&lt;ul&gt;&lt;li&gt;Item 1&lt;/li&gt;&lt;li&gt;Item 2&lt;ul&gt;&lt;li&gt;Sub Item 1&lt;/li&gt;&lt;/ul&gt;&lt;/li&gt;&lt;li&gt;Item 3&lt;/li&gt;&lt;/ul&gt; </td>

   <td width="312">&lt;ul&gt;&lt;li&gt;Item 1&lt;/li&gt;&lt;li&gt;Item 2&lt;/li&gt;&lt;ul&gt;&lt;li&gt;Sub Item 1&lt;/li&gt; &lt;/ul&gt;&lt;li&gt;Item 3&lt;/li&gt;&lt;/ul&gt; </td>

  </tr>

 </tbody>

</table>




In the example above, the left side has the 2<sup>nd</sup> &lt;ul&gt; tag nested <strong>inside</strong> of the 2<sup>nd</sup> &lt;li&gt; tag. The &lt;/li&gt; tag is closed <strong>after</strong> the 2<sup>nd</sup> &lt;ul&gt; set is closed. In the bad list portion, the 2<sup>nd</sup> &lt;ul&gt; is a direct child of the 1<sup>st</sup> &lt;ul&gt; and therefore not valid. This is just a rule that is a standard in HTML and there are many others like it. Look at the example below for an explanation of list nesting:

<a href="https://iinf362.000webhostapp.com/examples/nesting-example.html">https://iinf362.000webhostapp.com/examples/nesting-example.html</a>

I don’t expect you all to memorize all rules which is why you place your content in a validator. It will tell you what lines of code are wrong so you can fix them and improve your document’s markup. To check your code, copy all of it and paste it directly into the validator. You can also upload files or provide a link, but copy/pasting code is quicker. Use the website below to validate your code in the assignments mentioned below. I would recommend bookmarking it in your favorite browser (ideally Chrome for its web developer tools) for the semester.

<a href="https://validator.w3.org/#validate_by_input">https://validator.w3.org/#validate_by_input</a>




<strong><u>Before completing the assignments for this week, please read the “Creating and Viewing our Web Pages.docx” file on Blackboard. You will not be able to submit anything for the assignment without completing that portion first. </u></strong>

<strong><u> </u></strong>

<strong>HTML Exercise 2</strong>

Download the html-exercise-2.zip folder from Blackboard under today’s lecture notes or the assignments folder. Using the html files, create two web pages based on the images provided in parts 1 and 2. Your pages should validate entirely (green bar on the validator website) and contain the content <strong>exactly</strong> as I have it. This means all text should be bolded/italicized or linked as depicted on the pages. You can also use your own HTML file if you prefer to do it that way. Just make sure it validates by the time you finish.

The list below contains the tags that should be used for this assignment:




<ul>

 <li>title</li>

 <li>p</li>

 <li>h1-h3</li>

 <li>ul</li>

 <li>li</li>

 <li>ol</li>

 <li>hr</li>

 <li>em</li>

 <li>strong</li>

 <li>table</li>

 <li>tr</li>

 <li>td</li>

 <li>th</li>

 <li>form</li>

 <li>input/button</li>

 <li>textarea</li>

 <li>br</li>

 <li>html</li>

 <li>body</li>

 <li>a</li>

</ul>

<strong> </strong>

<strong> </strong>

<strong> </strong>

<strong> </strong>

To receive credit, you should submit TWO links to your pages. You can name the files whatever you’d like but part1.html and part2.html are straightforward and easy for me to grade. The most important thing is that you submit two live links to Blackboard and that both pages validate.




<strong>Validation Exercise</strong>

Download the validation-exercise.zip folder from Blackboard under today’s lecture notes folder. Your task is to fix the HTML in the document which contain numerous errors. To see what your page should look like, there are images inside of the assignment folder. No text content should be removed from the page, but you will need to add, delete, or move around tags. Once your page is validated, place it on your web hosting account. To earn credit for this assignment, you will need to submit a link to a validated page to Blackboard. You will know the page is validated when you use the validator link and it displays a green bar with the text: <strong>Document checking completed. No errors or warnings to show.</strong>

<u>Tips</u>

<ul>

 <li>Make sure tags are nested correctly</li>

 <li>Some tags require the presence of another tag</li>

 <li>Some tags may be misspelled</li>

 <li>Submit a live link from your web host (000webhost)</li>

</ul>

<strong>HTML Research Initial Post &amp; Response</strong>

Visit two websites and write a post about the HTML content you are seeing. Is the code easy to read? What are some of the most prevalent tags on the page? What are some tags you’re seeing that you weren’t expecting? Does the website use semantic markup? How would you alter the HTML so that it is more user-friendly/semantic? Does the page’s code validate? This initial post is due by Saturday, February 8<sup>th</sup>, at midnight.




In your response post, look at the websites reviewed by other students and provide your take on what you are seeing. Do you agree with their assessment? Can the code be improved, or does it have good, semantic markup? The response post doesn’t need to be elaborate; I want to see that you are opening up code from various websites and checking it out mostly. This response post is due by Tuesday, February 11<sup>th</sup>, at midnight.