---
keywords: fastai
title: Conditionals and Boolean Expressions Blog
toc: true 
badges: true
comments: false
categories: [jupyter]
nb_path: _notebooks/2022-09-12-conditionals.ipynb
layout: notebook
---

<!--
#################################################
### THIS FILE WAS AUTOGENERATED! DO NOT EDIT! ###
#################################################
# file to edit: _notebooks/2022-09-12-conditionals.ipynb
-->

<div class="container" id="notebook-container">
        
<div class="cell border-box-sizing text_cell rendered"><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h1 id="If,-If-else,-If-elseif-else-statements">If, If else, If elseif else statements<a class="anchor-link" href="#If,-If-else,-If-elseif-else-statements"> </a></h1>
</div>
</div>
</div>
    {% raw %}
    
<div class="cell border-box-sizing code_cell rendered">
<div class="input">

<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-java"><pre><span></span><span class="k">if</span><span class="p">(</span><span class="mi">1</span><span class="o">==</span><span class="mi">1</span><span class="p">){</span> <span class="c1">//checking if 1 is equal to one</span>
    <span class="n">System</span><span class="p">.</span><span class="na">out</span><span class="p">.</span><span class="na">println</span><span class="p">(</span><span class="s">&quot;one is equal to one&quot;</span><span class="p">);</span> <span class="c1">//prints out the message if that is true</span>
<span class="p">}</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">

<div class="output_area">

<div class="output_subarea output_stream output_stdout output_text">
<pre>True code block
</pre>
</div>
</div>

</div>
</div>

</div>
    {% endraw %}

    {% raw %}
    
<div class="cell border-box-sizing code_cell rendered">
<div class="input">

<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-java"><pre><span></span><span class="kd">var</span> <span class="n">num</span> <span class="o">=</span> <span class="mi">2</span><span class="p">;</span> <span class="c1">//creating a random variable (num) and assigning a value to it</span>
<span class="k">if</span> <span class="p">(</span><span class="n">num</span> <span class="o">==</span> <span class="mi">1</span><span class="p">){</span> <span class="c1">//checking to see if that value of the variable is equal to one</span>
    <span class="n">System</span><span class="p">.</span><span class="na">out</span><span class="p">.</span><span class="na">println</span><span class="p">(</span><span class="s">&quot;num is equal to one&quot;</span><span class="p">);</span> <span class="c1">//if num is equal to one we want to print it out</span>
<span class="p">}</span>
<span class="k">else</span><span class="p">{</span> <span class="c1">//if the if statement is NOT true proceed with this</span>
    <span class="n">System</span><span class="p">.</span><span class="na">out</span><span class="p">.</span><span class="na">println</span><span class="p">(</span><span class="s">&quot;num is not equal to one&quot;</span><span class="p">);</span> <span class="c1">// if the value does not equal to one we want to also print that out</span>
<span class="p">}</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">

<div class="output_area">

<div class="output_subarea output_stream output_stdout output_text">
<pre>a is not equal to one
</pre>
</div>
</div>

</div>
</div>

</div>
    {% endraw %}

    {% raw %}
    
<div class="cell border-box-sizing code_cell rendered">
<div class="input">

<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-java"><pre><span></span><span class="kd">var</span> <span class="n">num</span> <span class="o">=</span> <span class="mi">15</span><span class="p">;</span> <span class="c1">//creating a random variable (num) and assigning a value to it</span>
<span class="k">if</span><span class="p">(</span><span class="n">num</span> <span class="o">&lt;</span> <span class="mi">10</span><span class="p">){</span> <span class="c1">//checking to see if num is less than 10</span>
    <span class="n">System</span><span class="p">.</span><span class="na">out</span><span class="p">.</span><span class="na">println</span><span class="p">(</span><span class="s">&quot;num is less than 10&quot;</span><span class="p">);</span> <span class="c1">//print result </span>
<span class="p">}</span>
<span class="k">else</span> <span class="k">if</span><span class="p">(</span><span class="n">num</span> <span class="o">&gt;</span> <span class="mi">10</span><span class="p">){</span> <span class="c1">//checking to see if num is greater than 10</span>
    <span class="n">System</span><span class="p">.</span><span class="na">out</span><span class="p">.</span><span class="na">println</span><span class="p">(</span><span class="s">&quot;num is greater than 10&quot;</span><span class="p">);</span> <span class="c1">//print result </span>
<span class="p">}</span>
<span class="k">else</span><span class="p">{</span> <span class="c1">//If both of the previous statements are false then the number has to equal to 10</span>
    <span class="n">System</span><span class="p">.</span><span class="na">out</span><span class="p">.</span><span class="na">println</span><span class="p">(</span><span class="s">&quot;num is equal to 10&quot;</span><span class="p">);</span> <span class="c1">//print result </span>
<span class="p">}</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">

<div class="output_area">

<div class="output_subarea output_stream output_stdout output_text">
<pre>num is greater than 10
</pre>
</div>
</div>

</div>
</div>

</div>
    {% endraw %}

<div class="cell border-box-sizing text_cell rendered"><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h1 id="switch-case">switch-case<a class="anchor-link" href="#switch-case"> </a></h1>
</div>
</div>
</div>
    {% raw %}
    
<div class="cell border-box-sizing code_cell rendered">
<div class="input">

<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-java"><pre><span></span><span class="kt">int</span> <span class="n">randomNum</span> <span class="o">=</span> <span class="p">(</span><span class="kt">int</span><span class="p">)(</span><span class="n">Math</span><span class="p">.</span><span class="na">random</span><span class="p">()</span> <span class="o">*</span> <span class="mi">6</span><span class="p">);</span>  <span class="c1">// random number between 0 to 5</span>
<span class="k">if</span><span class="p">(</span><span class="n">randomNum</span> <span class="o">==</span> <span class="mi">0</span><span class="p">){</span> <span class="c1">//Checking if the random number is 0</span>
    <span class="n">System</span><span class="p">.</span><span class="na">out</span><span class="p">.</span><span class="na">println</span><span class="p">(</span><span class="s">&quot;The number is: 0&quot;</span><span class="p">);</span> <span class="c1">//printing out the random number if its 0</span>
<span class="p">}</span>
<span class="k">else</span> <span class="k">if</span><span class="p">(</span><span class="n">randomNum</span> <span class="o">==</span> <span class="mi">1</span><span class="p">){</span> <span class="c1">//Checking if the random number is 1</span>
    <span class="n">System</span><span class="p">.</span><span class="na">out</span><span class="p">.</span><span class="na">println</span><span class="p">(</span><span class="s">&quot;The number is: 1&quot;</span><span class="p">);</span> <span class="c1">//printing out the random number if its 1</span>
<span class="p">}</span>
<span class="k">else</span> <span class="k">if</span><span class="p">(</span><span class="n">randomNum</span> <span class="o">==</span> <span class="mi">2</span><span class="p">){</span> <span class="c1">//Checking if the random number is 2</span>
    <span class="n">System</span><span class="p">.</span><span class="na">out</span><span class="p">.</span><span class="na">println</span><span class="p">(</span><span class="s">&quot;The number is: 2&quot;</span><span class="p">);</span> <span class="c1">//printing out the random number if its 2</span>
<span class="p">}</span>
<span class="k">else</span> <span class="k">if</span><span class="p">(</span><span class="n">randomNum</span> <span class="o">==</span> <span class="mi">3</span><span class="p">){</span> <span class="c1">//Checking if the random number is 3</span>
    <span class="n">System</span><span class="p">.</span><span class="na">out</span><span class="p">.</span><span class="na">println</span><span class="p">(</span><span class="s">&quot;The number is: 3&quot;</span><span class="p">);</span> <span class="c1">//printing out the random number if its 3</span>
<span class="p">}</span>
<span class="k">else</span> <span class="k">if</span><span class="p">(</span><span class="n">randomNum</span> <span class="o">==</span> <span class="mi">4</span><span class="p">){</span> <span class="c1">//Checking if the random number is 4</span>
    <span class="n">System</span><span class="p">.</span><span class="na">out</span><span class="p">.</span><span class="na">println</span><span class="p">(</span><span class="s">&quot;The number is: 4&quot;</span><span class="p">);</span> <span class="c1">//printing out the random number if its 4</span>
<span class="p">}</span>
<span class="k">else</span><span class="p">{</span> <span class="c1">//if everything else is false then the number is five</span>
    <span class="n">System</span><span class="p">.</span><span class="na">out</span><span class="p">.</span><span class="na">println</span><span class="p">(</span><span class="s">&quot;The number is: 5&quot;</span><span class="p">);</span> <span class="c1">//printing out the random number if its 5</span>
<span class="p">}</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">

<div class="output_area">

<div class="output_subarea output_stream output_stdout output_text">
<pre>The number is: 2
</pre>
</div>
</div>

</div>
</div>

</div>
    {% endraw %}

<div class="cell border-box-sizing text_cell rendered"><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h3 id="lets-put-this-into-a-different-form-called-switch-case-otherwise">lets put this into a different form called switch-case-otherwise<a class="anchor-link" href="#lets-put-this-into-a-different-form-called-switch-case-otherwise"> </a></h3>
</div>
</div>
</div>
    {% raw %}
    
<div class="cell border-box-sizing code_cell rendered">
<div class="input">

<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-java"><pre><span></span><span class="kt">int</span> <span class="n">randomNum</span> <span class="o">=</span> <span class="p">(</span><span class="kt">int</span><span class="p">)(</span><span class="n">Math</span><span class="p">.</span><span class="na">random</span><span class="p">()</span> <span class="o">*</span> <span class="mi">6</span><span class="p">);</span>  <span class="c1">// random number between 0 to 5</span>
<span class="k">switch</span> <span class="p">(</span><span class="n">randomNum</span><span class="p">)</span> <span class="p">{</span>
  <span class="k">case</span> <span class="mi">0</span><span class="p">:</span> <span class="c1">//Checks if randomNum is equal to zero</span>
    <span class="n">System</span><span class="p">.</span><span class="na">out</span><span class="p">.</span><span class="na">println</span><span class="p">(</span><span class="s">&quot;The number is: 0&quot;</span><span class="p">);</span> <span class="c1">//printing out the random number if its 0</span>
    <span class="k">break</span><span class="p">;</span> <span class="c1">//stops the code</span>
  <span class="k">case</span> <span class="mi">1</span><span class="p">:</span> <span class="c1">//Checks if randomNum is equal to one</span>
    <span class="n">System</span><span class="p">.</span><span class="na">out</span><span class="p">.</span><span class="na">println</span><span class="p">(</span><span class="s">&quot;The number is: 1&quot;</span><span class="p">);</span> <span class="c1">//printing out the random number if its 1</span>
    <span class="k">break</span><span class="p">;</span> <span class="c1">//stops the code</span>
  <span class="k">case</span> <span class="mi">2</span><span class="p">:</span> <span class="c1">//Checks if randomNum is equal to two</span>
    <span class="n">System</span><span class="p">.</span><span class="na">out</span><span class="p">.</span><span class="na">println</span><span class="p">(</span><span class="s">&quot;The number is: 2&quot;</span><span class="p">);</span> <span class="c1">//printing out the random number if its 2</span>
    <span class="k">break</span><span class="p">;</span> <span class="c1">//stops the code</span>
  <span class="k">case</span> <span class="mi">3</span><span class="p">:</span> <span class="c1">//Checks if randomNum is equal to three</span>
    <span class="n">System</span><span class="p">.</span><span class="na">out</span><span class="p">.</span><span class="na">println</span><span class="p">(</span><span class="s">&quot;The number is: 3&quot;</span><span class="p">);</span> <span class="c1">//printing out the random number if its 3</span>
    <span class="k">break</span><span class="p">;</span> <span class="c1">//stops the code</span>
  <span class="k">case</span> <span class="mi">4</span><span class="p">:</span> <span class="c1">//Checks if randomNum is equal to four</span>
    <span class="n">System</span><span class="p">.</span><span class="na">out</span><span class="p">.</span><span class="na">println</span><span class="p">(</span><span class="s">&quot;The number is: 4&quot;</span><span class="p">);</span> <span class="c1">//printing out the random number if its 3</span>
    <span class="k">break</span><span class="p">;</span> <span class="c1">//stops the code</span>
  <span class="k">default</span><span class="p">:</span> <span class="c1">//If none of them are true then proceed</span>
    <span class="n">System</span><span class="p">.</span><span class="na">out</span><span class="p">.</span><span class="na">println</span><span class="p">(</span><span class="s">&quot;The number is: 5&quot;</span><span class="p">);</span> <span class="c1">//printing out the random number if its 3</span>
    <span class="k">break</span><span class="p">;</span> <span class="c1">//stops the code</span>
<span class="p">}</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">

<div class="output_area">

<div class="output_subarea output_stream output_stdout output_text">
<pre>The number is: 4
</pre>
</div>
</div>

</div>
</div>

</div>
    {% endraw %}

<div class="cell border-box-sizing text_cell rendered"><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h1 id="De-Morgan's-law">De Morgan's law<a class="anchor-link" href="#De-Morgan's-law"> </a></h1><h2 id="Description:">Description:<a class="anchor-link" href="#Description:"> </a></h2><p>The complement of the union of the two sets A and B will be equal to the intersection of A' (complement of A) and B' (complement of B).</p>
<ul>
<li><img src="vscode-remote://wsl%2Bubuntu/home/reem57/blog_new/images/law.png" alt="image"></li>
</ul>

</div>
</div>
</div>
    {% raw %}
    
<div class="cell border-box-sizing code_cell rendered">
<div class="input">

<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-java"><pre><span></span><span class="kd">var</span> <span class="n">a</span> <span class="o">=</span> <span class="kc">true</span><span class="p">;</span> <span class="c1">//creating a variable with a value of true</span>
<span class="kd">var</span> <span class="n">b</span> <span class="o">=</span> <span class="kc">false</span><span class="p">;</span> <span class="c1">//creating a variable with a value of false</span>
<span class="k">if</span> <span class="p">(</span><span class="o">!</span><span class="p">(</span><span class="n">a</span><span class="o">&amp;</span><span class="n">b</span><span class="p">)</span> <span class="o">==</span> <span class="o">!</span><span class="n">a</span><span class="o">|!</span><span class="n">b</span><span class="p">){</span> <span class="c1">// checks if De Morgan&#39;s law is correct</span>
    <span class="n">System</span><span class="p">.</span><span class="na">out</span><span class="p">.</span><span class="na">println</span><span class="p">(</span><span class="s">&quot;De Morgan&#39;s law is true&quot;</span><span class="p">);</span> <span class="c1">//prints out the result</span>
<span class="p">}</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">

<div class="output_area">

<div class="output_subarea output_stream output_stdout output_text">
<pre>De Morgan&#39;s law is true
</pre>
</div>
</div>

</div>
</div>

</div>
    {% endraw %}

    {% raw %}
    
<div class="cell border-box-sizing code_cell rendered">
<div class="input">

<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-java"><pre><span></span><span class="kd">var</span> <span class="n">a</span> <span class="o">=</span> <span class="kc">true</span><span class="p">;</span> <span class="c1">//creating a variable with a value of true</span>
<span class="kd">var</span> <span class="n">b</span> <span class="o">=</span> <span class="kc">false</span><span class="p">;</span> <span class="c1">//creating a variable with a value of false</span>
<span class="k">if</span> <span class="p">(</span><span class="o">!</span><span class="p">(</span><span class="n">a</span><span class="o">|</span><span class="n">b</span><span class="p">)</span> <span class="o">==</span> <span class="o">!</span><span class="n">a</span><span class="o">&amp;!</span><span class="n">b</span><span class="p">){</span> <span class="c1">// checks if De Morgan&#39;s law is correct</span>
    <span class="n">System</span><span class="p">.</span><span class="na">out</span><span class="p">.</span><span class="na">println</span><span class="p">(</span><span class="s">&quot;De Morgan&#39;s law is true&quot;</span><span class="p">);</span> <span class="c1">//prints out the result</span>
<span class="p">}</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">

<div class="output_area">

<div class="output_subarea output_stream output_stdout output_text">
<pre>De Morgan&#39;s law is true
</pre>
</div>
</div>

</div>
</div>

</div>
    {% endraw %}

    {% raw %}
    
<div class="cell border-box-sizing code_cell rendered">
<div class="input">

<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-java"><pre><span></span><span class="kd">var</span> <span class="n">a</span> <span class="o">=</span> <span class="kc">true</span><span class="p">;</span> <span class="c1">//creating a variable with a value of true</span>
<span class="kd">var</span> <span class="n">b</span> <span class="o">=</span> <span class="kc">false</span><span class="p">;</span> <span class="c1">//creating a variable with a value of false</span>
<span class="k">if</span> <span class="p">(</span><span class="o">!</span><span class="p">(</span><span class="n">a</span><span class="o">&amp;</span><span class="n">b</span><span class="p">)</span> <span class="o">==</span> <span class="o">!</span><span class="n">a</span><span class="o">&amp;!</span><span class="n">b</span><span class="p">){</span> <span class="c1">// checks if De Morgan&#39;s law is correct</span>
    <span class="n">System</span><span class="p">.</span><span class="na">out</span><span class="p">.</span><span class="na">println</span><span class="p">(</span><span class="s">&quot;De Morgan&#39;s law is not true&quot;</span><span class="p">);</span> <span class="c1">//prints out the result</span>
<span class="p">}</span>
<span class="k">else</span><span class="p">{</span> <span class="c1">// if not true then proceed</span>
    <span class="n">System</span><span class="p">.</span><span class="na">out</span><span class="p">.</span><span class="na">println</span><span class="p">(</span><span class="s">&quot;De Morgan&#39;s law is true&quot;</span><span class="p">);</span> <span class="c1">//prints out the result</span>
<span class="p">}</span>
</pre></div>

    </div>
</div>
</div>

</div>
    {% endraw %}

</div>
 
