# cse230-assignment-6-solved
**TO GET THIS SOLUTION VISIT:** [CSE230 Assignment 6 Solved](https://www.ankitcodinghub.com/product/cse230-assignment-6-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;96172&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSE230 Assignment 6 Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
<div class="section">
<div class="section">
<div class="layoutArea">
<div class="column">
You are required to turn in the following source file: assignment6.s

Objecves:

-write assembly language programs to:

-define procedures/functions and call them.

-create loops

</div>
</div>
</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="section">
<div class="section">
<div class="section">
<div class="layoutArea">
<div class="column">
-use syscall operations to display integers and strings on the console window

-use syscall operations to read integers from the keyboard.

Assignment Description:

Implement a MIPS assembly language program that defines main, readArray, printArray, and changeArrayContent procedures/functions.

The readArray takes an array of integers as its parameter, asks a user how many numbers will be entered, then reads in integers from a user to fill the array.

The printArray takes an array of integers as its parameter, prints each integer of the array.

The changeArrayContent procedure/function takes parameters of arrays of integers, an integer that specify how many integers were entered by a user, a maximum array size, and also asks a user to enter an integer. Then it goes through each element of the array, and check if it is divisible by the entered integer, it multiplies it by the entered integer. Then it calls printArray to print out the changed content. (Please see the C program below).

The main procedure/function calls readArray function to populate the array, calls printArray to print out its original content, then it asks a user to enter how many times the operation should be repeated, then calls changeArrayContent to change it content,

Please see the following C program to understand how it should work.

If your program causes an infinite loop, press Control and ‘C’ keys at the same time to stop it.

Name your source code file assignment6.s.

You can create an array in the following way:

<pre>numbers:     .word 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0
</pre>
The following shows how it looks like in a C program:

</div>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
<pre>int readArray(int array[], int arraysize)
{</pre>
</div>
</div>
</div>
</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="section">
<div class="section">
<div class="layoutArea">
<div class="column">
<pre>    int num, i = 0;
    int length;
</pre>
<pre>    printf("Specify how many numbers should be stored in the array (at most 1
1):\n");
</pre>
<pre>    scanf("%d", &amp;length);
</pre>
<pre>    while (i &lt; arraysize &amp;&amp; i &lt; length)
    {
</pre>
<pre>        printf("Enter an integer: \n");
</pre>
<pre>        //read an integer from a user input and store it in num1
        scanf("%d", &amp;num);
        array[i] = num;
</pre>
i++; }

<pre>    return length;
}
</pre>
<pre>//The printArray function prints integers of the array
void printArray(int array[], int arraysize, int length)
{
</pre>
int i;

<pre>    i = 0;
    while (i &lt; arraysize &amp;&amp; i &lt; length)
    {
</pre>
<pre>        printf("%d\n", array[i]);
</pre>
i++; }

return; }

<pre>//The changeArrayContent reads in an integer
//Then it goes through the parameter array, and if an element
//is divisible by the entered integer, then it multiplies the element
//by the entered integer.
void changeArrayContent(int numbers[], int arraysize, int length)
</pre>
{

int i;

<pre>     int num1;
     printf("Enter an integer:\n");
</pre>
<pre>     //read an integer from a user input
     scanf("%d", &amp;num1);
</pre>
<pre>     //It goes through each element of array
     //and change their values if the condition holds
</pre>
</div>
</div>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
mb

</div>
</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="section">
<div class="section">
<div class="layoutArea">
<div class="column">
The following is a sample output (user input is in bold):

</div>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
<pre>     i = 0;
     while (i &lt; arraysize &amp;&amp; i &lt; length)
</pre>
<pre>      {
          if (numbers[i]%num1 == 0)
</pre>
<pre>            numbers[i] = numbers[i]*num1;
</pre>
i++; }

<pre>     printf("\nResult Array Content:\n");
     printArray(numbers, arraysize, length);
</pre>
return; }

<pre>//The main reads in an array content,
//then it prints it,
//then it asks a user how many time to repeat
//the changeArrayContent operation.
void main()
{
</pre>
<pre>    int arraysize = 12, length;
    int numbers[arraysize];
    int howMany;
    int i;
</pre>
<pre>    length = readArray(numbers, arraysize);
    printf("\nOriginal Array Content:\n");
    printArray(numbers, arraysize, length);
</pre>
<pre>    printf("Specify how many times to repeat:\n");
    scanf("%d", &amp;howMany);
</pre>
<pre>    i=0;
    while (i &lt; howMany)
    {
</pre>
<pre>        changeArrayContent(numbers, arraysize, length);
</pre>
i++; }

return; }

</div>
</div>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
mb

</div>
</div>
</div>
</div>
<div class="page" title="Page 5">
<div class="section">
<div class="section">
<div class="layoutArea">
<div class="column">
Specify how many numbers should be stored in the array (at most 11):

9

Enter an integer:

1

Enter an integer:

-12

Enter an integer:

53

Enter an integer:

-4

Enter an integer:

5

Enter an integer:

32

Enter an integer:

1

Enter an integer:

7

Enter an integer:

-5

Original Array Content: 1

-12

53

-4

5

32

1

7

-5

Specify how many times to repeat: 3

Enter an integer:

4

Result Array Content: 1

-48

53

</div>
</div>
</div>
</div>
</div>
<div class="page" title="Page 6">
<div class="section">
<div class="section">
<div class="layoutArea">
<div class="column">
-16 5 128 1

7

-5

Enter an integer:

2

Result Array Content: 1

-96

53

-32 5 256 1

7

-5

Enter an integer:

5

Result Array Content: 1

-96

53

-32 25 256 1

7 -25

————————————————–

</div>
</div>
</div>
</div>
</div>
