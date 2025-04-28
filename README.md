# csci112-lab-3--infix-calculator-solved
**TO GET THIS SOLUTION VISIT:** [CSCI112  Lab 3- Infix Calculator Solved](https://www.ankitcodinghub.com/product/csci112-infix-calculator-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;117361&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSCI112 &nbsp;Lab 3- Infix Calculator Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
            5/5 - (2 votes)    </div>
    </div>
File names: Names of files, functions, and variables, when specified, must be EXACTLY as specified. This includes simple mistakes such as capitalization.

Documentation: Each file should begin with a docstring that includes your name, the class number and name, the lab number, and a short description of the lab, as well as documentation pertinent to that particular file.

Calculator: Finish the following two problems from the text:

1. Implement a direct infix evaluator that combines the functionality of infix-to-postfix conversion and the postfix evaluation algorithm. Your evaluator should process infix tokens from left to right and use two stacks, one for operators and one for operands, to perform the evaluation.

Follow the textbook’s style. Try to use as much of the code from the textbook as possible. You should be able to simply modify the infixToPostfix function using the doMath function. Every time the function would output an operator, apply this operator to the top two items on the stack. Think about the order of operands and the order of stacking!

2. Turn your direct infix evaluator from the previous problem into a calculator. This will simply print a prompt, read the input, evaluate the arithmetic expression, print the result, and loop. Here’s mine in action:

&gt;&gt;&gt; repl()

Geoff’s Amazing Calculator! &gt;&gt;&gt; 2 + 2

4

Geoff’s Amazing Calculator! &gt;&gt;&gt; 3 + 4 * 5

23

Geoff’s Amazing Calculator! &gt;&gt;&gt; 3 * 4 + 5

17

Geoff’s Amazing Calculator! &gt;&gt;&gt; quit

&gt;&gt;&gt;

repl stands for “read, evaluate, print, loop”

Tokenizing: Instead of using single-character numbers, as in the text, use my tokenizing function found in tokens.py. This allows the use of floats, too. It uses split() to separate tokens, so all tokens must be separated by spaces, including operators and parentheses. For example:

&gt;&gt;&gt; tokenize(’( 44 + -33.3 ) * 2 – 4’)

[’(’, 44, ’+’, -33.3, ’)’, ’*’, 2, ’-’, 4]

1

2

Operators: You must support addition, subtraction, multiplication and division. Multiplication and division have higher precedence than addition and subtraction. Otherwise everything is left associative.

Turn in: A file named calculator.py, with a function called evaluate with the following behavior, which does infix evaluation, for example:

1

evaluate(‘2 + 2’) =&gt; 4

1

and a function called repl which starts a read-eval-print loop.

A unit test module called calc_test.py, that tests the major functionality of your calculator functions.

Zip these functions, together with tokens.py and any other modules you built, in a folder called csci112lab03yourname zip and submit to canvas.

Optional additions:

• Write a better tokenizer so that spaces are not required where they are not needed, for example,

(2+2)

3 + ) , 4 + * 5 , and ( 3 ( 4 + 5 ))

• Add error checking to the tokenizer, so that the user gets meaningful feedback from expressions like these:, and the calculator continues to work, rather than stopping with an error.

• Add some unary operators, such as sin and cos and exp

• Add the ** operator. Note that this has higher precedence than all the others, and is also right associative. You will need to think through how to handle the operator stack for this one, and make the necessary additions to the algorithm outlined in §4.9.2.

2
