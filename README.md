<h2>Info</h2>
<ul>
<li>This lab consists of two parts</li>
<li>In this iteration you will be doing most of the logic/coding</li>
<li>You will also get started on the graphical appearance
<ul>
<li>The code will display the results in the developer console</li>
<li>The HTML is just a test placeholder for part 2 of this lab</li>
</ul></li>
</ul>
<h2>Objectives</h2>
<ul>
<li>Create an array called <code>friends</code>. It will hold five of your friends' names.</li>
<li>For every friend in the friend array, you will want to <code>console.log</code> the descending chorus of this brand-new, never before seen song 100 times. The lyric must include your friend's name, and must be grammatically correct when we get down to 1. See the example output for more information.</li>
<li>In the HTML, set the page title to 99 Lines of Code In The File</li>
<li>Put an <code>h1</code> element in the html body that says My Singing Friends</li>
<li>Put a <code>div</code> element in the html body with a class of <code>friend</code>.
<ul>
<li>Inside the <code>div</code> element, put an <code>h3</code> element that contains the word "Friend"</li>
<li>Inside the <code>div</code> element, put 5 <code>p</code> elements.</li>
<li>Inside the <code>p</code> elements, put "Test1", "Test2", ..., "Test5"</li>
</ul></li>
<li>Style the page
<ul>
<li>Set a background color on the page.</li>
<li>Change the text color of the h1.</li>
<li>Set a background color for class <code>friend</code>.</li>
<li>Target the <code>h3</code> element inside the <code>friend</code> class div and make it uppercase using only CSS.</li>
<li>You have stylistic freedom to make the page look good</li>
</ul></li>
</ul>
<h2>Hints</h2>
<ul>
<li>You will need to use two loops to accomplish this task
<ul>
<li>One loop is nested inside the other</li>
<li>The outer loop is picking the friend. For each friend, the inner loop runs for every line of the song.</li>
</ul></li>
</ul>
<h2>Submission</h2>
<ul>
<li>As usual, make sure you save and then commit and push your work to GitHub.</li>
</ul>
<h2>Example Output</h2>
<pre><code class="language-markdown">JOHN:
99 lines of code in the file, 99 lines of code; John strikes one out, clears it all out, 98 lines of code in the file
98 lines of code in the file, 98 lines of code; John strikes one out, clears it all out, 97 lines of code in the file
.......
.......
1 line of code in the file, 1 line of code; John strikes one out, clears it all out, no more lines of code in the file
JANE:
99 lines of code in the file, 99 lines of code; Jane strikes one out, clears it all out, 98 lines of code in the file
98 lines of code in the file, 98 lines of code; Jane strikes one out, clears it all out, 97 lines of code in the file
.......
.......
1 line of code in the file, 1 line of code; Jane strikes one out, clears it all out, no more lines of code in the file
</code></pre>