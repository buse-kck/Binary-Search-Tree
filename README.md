# Binary-Search-Tree

1- Binary Search Tree Aşamaları

Root 7'dir. Eğer okuduğumuz sayı 7'den büyükse sağına, 7'den küçükse soluna yazılr.

<pre><code>1.Aşama <br/>
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; 7 <br/>
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp;  /  <br/>
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; 5 </code></pre>

<pre><code>2.Aşama <br/>
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; 7 <br/>
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp;  /  <br/>
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; 5 <br/>
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp;/ <br/>
&nbsp; &nbsp; &nbsp; &nbsp; 1
</code></pre>


<pre><code>3.Aşama <br/>
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; 7 <br/>
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp;  / \ <br/>
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; 5 &nbsp; 8 <br/> 
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp;/ <br/>
&nbsp; &nbsp; &nbsp; &nbsp; 1 </code></pre>

<pre><code>4.Aşama <br/>
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; 7 <br/>
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp;  / \ <br/>
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; 5 &nbsp; 8 <br/> 
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp;/ <br/>
&nbsp; &nbsp; &nbsp; &nbsp; 1 <br/>
&nbsp; &nbsp; &nbsp;    \ <br/>
&nbsp; &nbsp;       3
</code></pre>

<pre><code>5.Aşama <br/>
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; 7 <br/>
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp;  / \ <br/>
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; 5 &nbsp; 8 <br/> 
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp;/ \ <br/>
&nbsp; &nbsp; &nbsp; &nbsp; 1   6 <br/>
&nbsp; &nbsp; &nbsp;    \ <br/>
&nbsp; &nbsp;       3
</code></pre>

<pre><code>6.Aşama <br/>
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; 7 <br/>
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp;  / \ <br/>
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; 5 &nbsp; 8 <br/> 
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp;/ \ <br/>
&nbsp; &nbsp; &nbsp; &nbsp; 1   6<br/>
&nbsp; &nbsp; &nbsp;  / \ <br/>
&nbsp; &nbsp;   0   3
</code></pre>

<pre><code>7.Aşama <br/>
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; 7 <br/>
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp;  / \ <br/>
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; 5 &nbsp; 8 <br/> 
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp;/ \   \<br/>
&nbsp; &nbsp; &nbsp; &nbsp; 1   6   9<br/>
&nbsp; &nbsp; &nbsp;  / \ <br/>
&nbsp; &nbsp;   0   3
</code></pre>

<pre><code>8.Aşama <br/>
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; 7 <br/>
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp;  / \ <br/>
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; 5 &nbsp; 8 <br/> 
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp;/ \   \<br/>
&nbsp; &nbsp; &nbsp; &nbsp; 1   6   9<br/>
&nbsp; &nbsp; &nbsp;  / \ <br/>
&nbsp; &nbsp;   0   3 <br/>
&nbsp; &nbsp;        \ <br/>
&nbsp; &nbsp;         4

<pre><code>9.Aşama <br/>
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; 7 <br/>
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp;  / \ <br/>
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; 5 &nbsp; 8 <br/> 
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp;/ \   \<br/>
&nbsp; &nbsp; &nbsp; &nbsp; 1   6   9<br/>
&nbsp; &nbsp; &nbsp;  / \ <br/>
&nbsp; &nbsp;   0   3 <br/>
&nbsp; &nbsp;      / \ <br/>
&nbsp; &nbsp;     2   4</code></pre>


## 2- Big O Gösterimi

Worst Case: O(n)
Best Case: O(logn)

[Patika](app.patika.dev/courses/veri-yapilari-ve-algoritmalar/insertion-sort-proje)
