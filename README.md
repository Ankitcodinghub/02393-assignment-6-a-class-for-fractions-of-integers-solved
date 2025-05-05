# 02393-assignment-6-a-class-for-fractions-of-integers-solved
**TO GET THIS SOLUTION VISIT:** [02393 Assignment 6-A class for fractions of integers Solved](https://www.ankitcodinghub.com/product/02393-assignment-6-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;101443&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;02393 Assignment 6-A class for fractions of integers Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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

<div class="kksr-stars-active" style="width: 0px;">
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
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
A class for fractions of integers

The goal of the exercise of this week is to implement a class of fractions of integers supporting some basic operations like addition and multiplication. You can use the following interface for the class as a starting point and modify it at will:

<pre>class fraction {
</pre>
<pre>private:
    // Internal representation of a fraction as two integers
    int numerator;
    int denominator;
</pre>
<pre>public:
    // Class constructor
    fraction(int n, int d);
</pre>
<pre>    // Methods to update the fraction
    void add(fraction f);
    void mult(fraction f);
    void div(fraction f);
</pre>
<pre>    // Display method
    void display(void);
</pre>
};

The main idea above is that a fraction ab is represented by two integers (the numerator a and the denominator b) and several methods are provided to support arithmetic operations on fractions. For example:

fraction(int n, int m) constructs the fraction mn ;

void add(fraction f) updates a fraction by adding fraction f to it.

void mult(fraction f) updates a fraction by multiplying it by fraction f. void div(fraction f) updates a fraction by dividing it by fraction f.

Your program should read sequences of simple expressions from cin of the form: a/b+c/d,a/b*c/dora/bdivc/dandprovidethe result as a simplified fraction. For example, if the input is

1/4+1/2

your program should provide the following output to cout

3/4

which results from 1·2+1·4 = 6 which after simplification is 3 . 4·2 8 4

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
Challenge The suggested internal representation poses some limits on the ac-

tual domain of integral numbers that the fraction class can cover. For example,

</div>
</div>
<div class="layoutArea">
<div class="column">
the largest number would be INT MAX and the smallest positive fraction would be 1

</div>
</div>
<div class="layoutArea">
<div class="column">
1 . A possible remedy to mitigate this would be to exploit the fact that every INT MAX

</div>
</div>
<div class="layoutArea">
<div class="column">
integer can be represented by a product of prime numbers (see e.g. https:// en.wikipedia.org/wiki/Fundamental_theorem_of_arithmetic). This was indeed what we exploited in assignment 2. For example

137200 = 2 · 2 · 2 · 2 · 5 · 5 · 7 · 7 · 7

To avoid repeating the same prime number many times, we could equivalently

represent 137200 with exponentiation of prime numbers: 137200 = 24 ·52 ·73

We could thus represent all the exponents in an array of exponents, where the i-th element of the array represents how many times the i-th prime number occurs.1 So the representation of 137200 would be

</div>
</div>
<div class="layoutArea">
<div class="column">
arrayindex

array

corresponding prime number

</div>
<div class="column">
01234 5 … 40230 0 … 2 3 5 7 11 13 . . .

</div>
</div>
<div class="layoutArea">
<div class="column">
Arithmetic operations can also exploit such representation. For instance, the multiplication of two numbers in such representation can be obtained by adding the corresponding exponents. For instance, multiplying the factorizations of 12 and 10 would be done as follows

primes 2 3 5

12 210

10 101 Adding exponents gives: 120 311

Division can be obtained in a similar manner, by substracting the exponents. Addition may be more involved.

The challenge is to implement the class of fractions with this representation technique.

1Formally, the factorization of a natural number n &gt; 0 consists of the (uniquely determined) exponentsk1,k2,…suchthatn=pk1 ·pk2 ·…wherep1,p2,…aretheprimenumbers.

12

2

</div>
</div>
</div>
