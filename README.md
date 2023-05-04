Download Link: https://assignmentchef.com/product/solved-cse-461-programming-languages-conceptshomework-2
<br>
<ol>

 <li>(8 points) Consider the C program given below. You will be asked to determine which variables are visible in a number of different situations. In each case, identify each variable by its name and the line number of its declaration.

  <ul>

   <li>int h, i;</li>

   <li>void B(int w) {</li>

   <li>int j, k;</li>

   <li>i = 2*w;</li>

   <li>w = w+1;</li>

   <li>…</li>

   <li>}</li>

   <li>void A (int x, int y) {</li>

   <li>float i, j;</li>

   <li>B(h);</li>

   <li>i = 3;</li>

   <li>…</li>

   <li>}</li>

   <li>void main() {</li>

   <li>int a, b;</li>

   <li>h = 5; a = 3; b = 2;</li>

   <li>A(a, b);</li>

   <li>B(h);</li>

   <li>…</li>

   <li>}</li>

   <li>C uses static scoping. Say which identifiers (including variablesand function names) are visible in the bodies of each of the functions: main, A, B.</li>

  </ul></li>

</ol>

1

<ul>

 <li>If C used dynamic scoping and the calling sequence is main callsB. Say which identifiers would be visible in B.</li>

 <li>If C used dynamic scoping and the calling sequence is main callsA. Say which identifiers would be visible in A.</li>

 <li>If C used dynamic scoping and the calling sequence is main callsA; A calls B. Say which identifiers would be visible in B.</li>

</ul>

<ol start="2">

 <li>(3 points) Find some online material to learn C++’s namespace mechanism. Explain briefly how it works and its benefits.</li>

 <li>(3 points) During the execution of a Java program, can a variable be visible but not allocated? Can a variable be allocated but not visible? Explain your answers.</li>

</ol>


