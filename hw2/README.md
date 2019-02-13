# Homework #2 Solution
#### Adeeb Rahman
#### NetID: qz6928

<style>
    #Q1::first-letter {color: blue;}
    #Q2::first-letter {color: blue;}
    #Q3::first-letter {color: blue;}
    #Q4::first-letter {color: blue;}
    #Q5::first-letter {color: blue;}
    .content-style {background-color: Linen;}
    .answer {border: solid black; background-color: DarkSlateGrey;}
    h2:hover {background-color: LightGreen; color: SlateBlue;}
</style>

<ul class="content-style">

<li><a href="#Q1">Question 1.</a></li>
<ul>
<li><a href="#Q1a">(a)</a></li>
<li><a href="#Q1b">(b)</a></li>
<li><a href="#Q1c">(c)</a></li>
<li><a href="#Q1d">(d)</a></li>
</ul>

<li><a href="#Q2">Question 2.</a></li>
<ul>
<li><a href="#Q2a">(a)</a></li>
<li><a href="#Q2b">(b)</a></li>
</ul>

<li><a href="#Q3">Question 3.</a></li>
<ul>
<li><a href="#Q3a">(a)</a></li>
<li><a href="#Q3b">(b)</a></li>
<li><a href="#Q3c">(c)</a></li>
<li><a href="#Q3d">(d)</a></li>
</ul>

<li><a href="#Q4">Question 4.</a></li>
<ul>
<li><a href="#Q4a">(a)</a></li>
<li><a href="#Q4b">(b)</a></li>
<li><a href="#Q4c">(c)</a></li>
<li><a href="#Q4d">(d)</a></li>
<li><a href="#Q4e">(e)</a></li>

</ul>

<li><a href="#Q4">Question 5.</a></li>

<ul>
<li><a href="#Q5a">(a)</a></li>
<li><a href="#Q5b">(b)</a></li>
<li><a href="#Q5c">(c)</a></li>
<li><a href="#Q5d">(d)</a></li>
</ul>

</ul>
<h2 id="Q1"> Question 1. </h2>
<h3 id="Q1a">(a)</h3>

<section class="answer">

* ### Attributes
	* ##### class
	* ##### href
	* ##### alt
	* ##### src
	* ##### style

* ### Tags
	* ##### nav
	* ##### a
	* ##### img

</section>

<h3 id="Q1b">(b)</h3>

<section class="answer">

    No, you cannot use the same _id_ attribute on more than one element in an **HTML** document. This is because of the fact that we use _id_ attributes as targets for links since one attribute cannot refer to more than one link within the same **HTML** document. On the other hand, you can use the same _class_ on multiple elements in a document. This can be helpful for styling since the same styles can be reused and if needed can be overridden with a new class to make further modifications.

</section>

<h3 id="Q1c">(c)</h3>
<section class="answer"></section>
<h3 id="Q1d">(d)</h3>
<section class="answer"></section>

<h2 id="Q2"> Question 2. </h2>
<h3 id="Q2a">(a)</h3>

<section class="answer">


	 The CSS selectors are ' #RelatedItems ' and ' .graphDrawing '. #RelatedItems is of type _id_ and .graphDrawing is of type _class_.
* #### CSS Properties
	* ##### padding-top
	* ##### max-height
	* ##### overflow-y
	* ##### border
	* ##### border-radius
	* ##### width
	* ##### margin
	* ##### margin-bottom

* #### CSS Values	
	* ##### 50px
	* ##### 70vh
	* ##### auto
	* ##### solid thin #808080
	* ##### 5px
	* ##### 100%
	* ##### 0
	* ##### 15px
</section>

<h3 id="Q2b">(b)</h3>
<section class="answer">

     In the CSS fragment there are two descendant combinators **'article figcaption'** and 'a.navbar-brand img'. The article and figcaption elements is creating a self-contained reusable composition of a figure with a caption having a font-size of 18px and text-align to center. The anchor element a is using the _class_ navbar-brand and combined with the img element having all the properties and values specified in order to style a certain branding logo within a navigation bar.

</section>

<h2 id="Q3"> Question 3. </h2>
  
<h3 id="Q3a">(a)</h3>

<section class="answer">
	
	#Q1::first-letter {color: blue;}
    #Q2::first-letter {color: blue;}
    #Q3::first-letter {color: blue;}
    #Q4::first-letter {color: blue;}
    #Q5::first-letter {color: blue;}

![](https://github.com/secludedGrace/webdev101/blob/hw2/hw2/ss/3a_1.png)

![](https://github.com/secludedGrace/webdev101/blob/hw2/hw2/ss/3a_2.png)

![](https://github.com/secludedGrace/webdev101/blob/hw2/hw2/ss/3a_3.png)

![](https://github.com/secludedGrace/webdev101/blob/hw2/hw2/ss/3a_4.png)

![](https://github.com/secludedGrace/webdev101/blob/hw2/hw2/ss/3a_5.png)

</section>

<h3 id="Q3b">(b)</h3>
  <section class="answer">

    .content-style {background-color:PaleGreen;}

![](https://github.com/secludedGrace/webdev101/blob/hw2/hw2/ss/3b.png)

  </section>
<h3 id="Q3c">(c)</h3>

<section class="answer">

    .answer {border: solid black; background-color: DarkSlateGrey;}

![](https://github.com/secludedGrace/webdev101/blob/hw2/hw2/ss/3c.png)

</section>
  
<h3 id="Q3d">(d)</h3>

<section class="answer">
    
    h2:hover {background-color: LightGreen; color: SlateBlue;} 

</section>

<h2 id="Q4"> Question 4. </h2>

<h3 id="Q4a">(a)</h3>

<section class="answer">

![](https://github.com/secludedGrace/webdev101/blob/hw2/hw2/ss/4a.png)


	(i) Because the parseInt() function parses a string argument and returns an integer of the specified radix which in this case is not specified so it spills out NaN.

	Syntax: parseInt(string, radix);

	NaN stands for 'Not a Number'. If the first character of the string cannot be converted into a number, NaN is returned

	(ii) In this case, the radix is not defined and the first character is a number, so by convention/default JavaScript assumes the radix is 10(decimal).Also, if parseInt encounters a character that is not a numeral in the specified radix, it ignores it and all succeeding characters and returns the integer value parsed up to that point. That's why 12 is returned here.

	(iii) In this case, the string is specified as '1010' and the radix is 2. As a result, parseInt() returns the integer value of '1010' in base 2.

	(iv) This is not the same as (ii) because in (ii) the first character of the string can be converted into a number, but here in 'hi5' it's not the case, so it returns NaN.

	(v) parseInt('3.145Adeeb) - returns upto the character that is numeral in the specified radix.

	(vi) parseFloat('Adeeb2112') - returns NaN since first character is not a numeral.

</section>

<h3 id="Q4b">(b)</h3>

<section class="answer">

![](https://github.com/secludedGrace/webdev101/blob/hw2/hw2/ss/4b.png)


</section>

<h3 id="Q4c">(c)</h3>

<section class="answer">

![](https://github.com/secludedGrace/webdev101/blob/hw2/hw2/ss/4c.png)

	We bother using two string delimiters so that we don't have to use backslash(\) all the time and we can combine both delimiters within the same sentence according to the needs.

	(i) The first test output works.
	(ii) The second test output (test2) doesn't work because there is an uneven number of single quote(') that leaves one open ' and causes error.
	(iii) test3 works due to the usage of escape character (\) that identifies the second ' as an apostrophe.

</section>
  

<h3 id="Q4d">(d)</h3>

<section class="answer">

![](https://github.com/secludedGrace/webdev101/blob/hw2/hw2/ss/4d.png)

	(i) toUpperCase() function converts the name into all uppercase

	(ii) toLowerCase() function converts the name into all lowercase

	The last two lines uses the include() function to check if the name includes any uppercase 'A' or lowercase 'i' and returns true or false accordingly.
</section>

<h3 id="Q4e">(e)</h3>

<section class="answer">

![](https://github.com/secludedGrace/webdev101/blob/hw2/hw2/ss/4e.png)

</section>

<h2 id="Q5"> Question 5. </h2>



<h3 id="Q5a">(a)</h3>

<section class="answer">

![](https://github.com/secludedGrace/webdev101/blob/hw2/hw2/ss/5a.png)

	(i) the split() function splits the sentence into array of strings based on the argument as seperator which is a whitespace " " in this case.

	(ii) Each of these calls pushes the given arguments which are strings to the myArray basically adding words to the sentence.

	(iii) Join replaced all the whitespaces with the given argument, in this case an underscore(_).

	(iv) the tempIndex variable stores the index of the string entered as an argument from myArray using the indexOf() function.

	(v) Using the index from previous tempIndex variable the string value of the index is changed to 'college'.

	(vi) The pop() function removes the last element from the array.

</section>

<h3 id="Q5b">(b)</h3>

<section class="answer">

![](https://github.com/secludedGrace/webdev101/blob/hw2/hw2/ss/5b.png)

	(i) The upper(xString) function takes a string as an argument and returns the string in all uppercase.

	(ii) The map basically taking all the split strings from the previous array, switching it to uppercase and putting it in another array myArray3.

	(iii) returns -1 if lowercase x is alphabetically lower than lowecase y and returns 1 otherwise. If they're the same returns 0. This is just to compare two elements in the array and determine whether they're ordered.

	(iv) The reason for passing this function is because the sort() function uses the return value of noCaseSort() function and sorts them in alphabetical order.

</section>

<h3 id="Q5c">(c)</h3>

<section class="answer">

![](https://github.com/secludedGrace/webdev101/blob/hw2/hw2/ss/5c.png)

</section>

<h3 id="Q5d">(d)</h3>

<section class="answer">

	function max2secCompare(x, y) {
		if (x.max2sec < y.max2sec) {
			return -1;
		} else {
			return 1;
		}
		return 0;
	}

![](https://github.com/secludedGrace/webdev101/blob/hw2/hw2/ss/5d_1.png)

	function distanceCompare(x, y) {
		if (x.distance < y.distance) {
			return -1;
		} else {
			return 1;
		}
  		return 0;
}

![](https://github.com/secludedGrace/webdev101/blob/hw2/hw2/ss/5d_2.png)

</section>