# Some-Every-Exercise
some / every practice lesson for UMass/Springboard bootcamp
Javascript, HTML

<div class="section" id="hasoddnumber">
<h3>hasOddNumber</h3>
<p>Write a function called hasOddNumber which accepts an array and returns true if the array contains at least one odd number, otherwise it returns false.</p>
<div class="highlight-js notranslate"><div class="highlight"><pre><span></span><span class="nx">hasOddNumber</span><span class="p">([</span><span class="mi">1</span><span class="p">,</span><span class="mi">2</span><span class="p">,</span><span class="mi">2</span><span class="p">,</span><span class="mi">2</span><span class="p">,</span><span class="mi">2</span><span class="p">,</span><span class="mi">2</span><span class="p">,</span><span class="mi">4</span><span class="p">])</span> <span class="c1">// true</span>
<span class="nx">hasOddNumber</span><span class="p">([</span><span class="mi">2</span><span class="p">,</span><span class="mi">2</span><span class="p">,</span><span class="mi">2</span><span class="p">,</span><span class="mi">2</span><span class="p">,</span><span class="mi">2</span><span class="p">,</span><span class="mi">4</span><span class="p">])</span> <span class="c1">// false</span>
</pre></div>
</div>
</div>
<div class="section" id="hasazero">
<h3>hasAZero</h3>
<p>Write a function called hasAZero which accepts a number and returns true if that number contains at least one zero. Otherwise, the function should return false</p>
<div class="highlight-js notranslate"><div class="highlight"><pre><span></span><span class="nx">hasAZero</span><span class="p">(</span><span class="mi">33321232131012</span><span class="p">)</span> <span class="c1">// true</span>
<span class="nx">hasAZero</span><span class="p">(</span><span class="mi">1212121</span><span class="p">)</span> <span class="c1">// false</span>
</pre></div>
</div>
</div>
<div class="section" id="hasonlyoddnumbers">
<h3>hasOnlyOddNumbers</h3>
<p>Write a function called hasOnlyOddNumbers which accepts an array and returns true if every single number in the array is odd. If any of the values in the array are not odd, the function should return false.</p>
<div class="highlight-js notranslate"><div class="highlight"><pre><span></span><span class="nx">hasOnlyOddNumbers</span><span class="p">([</span><span class="mi">1</span><span class="p">,</span><span class="mi">3</span><span class="p">,</span><span class="mi">5</span><span class="p">,</span><span class="mi">7</span><span class="p">])</span> <span class="c1">// true</span>
<span class="nx">hasOnlyOddNumbers</span><span class="p">([</span><span class="mi">1</span><span class="p">,</span><span class="mi">2</span><span class="p">,</span><span class="mi">3</span><span class="p">,</span><span class="mi">5</span><span class="p">,</span><span class="mi">7</span><span class="p">])</span> <span class="c1">// false</span>
</pre></div>
</div>
</div>
<div class="section" id="hasnoduplicates">
<h3>hasNoDuplicates</h3>
<p>Write a function called hasNoDuplicates which accepts an array and returns true if there are no duplicate values (more than one element in the array that has the same value as another). If there are any duplicates, the function should return false.</p>
<div class="highlight-js notranslate"><div class="highlight"><pre><span></span><span class="nx">hasNoDuplicates</span><span class="p">([</span><span class="mi">1</span><span class="p">,</span><span class="mi">2</span><span class="p">,</span><span class="mi">3</span><span class="p">,</span><span class="mi">1</span><span class="p">])</span> <span class="c1">// false</span>
<span class="nx">hasNoDuplicates</span><span class="p">([</span><span class="mi">1</span><span class="p">,</span><span class="mi">2</span><span class="p">,</span><span class="mi">3</span><span class="p">])</span> <span class="c1">// true</span>
</pre></div>
</div>
</div>
<div class="section" id="hascertainkey">
<h3>hasCertainKey</h3>
<p>Write a function called hasCertainKey which accepts an array of objects and a key, and returns true if every single object in the array contains that key. Otherwise it should return false.</p>
<div class="highlight-js notranslate"><div class="highlight"><pre><span></span><span class="kd">let</span> <span class="nx">arr</span> <span class="o">=</span> <span class="p">[</span>
    <span class="p">{</span><span class="nx">title</span><span class="o">:</span> <span class="s2">&quot;Instructor&quot;</span><span class="p">,</span> <span class="nx">first</span><span class="o">:</span> <span class="s1">&#39;Elie&#39;</span><span class="p">,</span> <span class="nx">last</span><span class="o">:</span><span class="s2">&quot;Schoppik&quot;</span><span class="p">},</span>
    <span class="p">{</span><span class="nx">title</span><span class="o">:</span> <span class="s2">&quot;Instructor&quot;</span><span class="p">,</span> <span class="nx">first</span><span class="o">:</span> <span class="s1">&#39;Tim&#39;</span><span class="p">,</span> <span class="nx">last</span><span class="o">:</span><span class="s2">&quot;Garcia&quot;</span><span class="p">,</span> <span class="nx">isCatOwner</span><span class="o">:</span> <span class="kc">true</span><span class="p">},</span>
    <span class="p">{</span><span class="nx">title</span><span class="o">:</span> <span class="s2">&quot;Instructor&quot;</span><span class="p">,</span> <span class="nx">first</span><span class="o">:</span> <span class="s1">&#39;Matt&#39;</span><span class="p">,</span> <span class="nx">last</span><span class="o">:</span><span class="s2">&quot;Lane&quot;</span><span class="p">},</span>
    <span class="p">{</span><span class="nx">title</span><span class="o">:</span> <span class="s2">&quot;Instructor&quot;</span><span class="p">,</span> <span class="nx">first</span><span class="o">:</span> <span class="s1">&#39;Colt&#39;</span><span class="p">,</span> <span class="nx">last</span><span class="o">:</span><span class="s2">&quot;Steele&quot;</span><span class="p">,</span> <span class="nx">isCatOwner</span><span class="o">:</span> <span class="kc">true</span><span class="p">}</span>
  <span class="p">]</span>

  <span class="nx">hasCertainKey</span><span class="p">(</span><span class="nx">arr</span><span class="p">,</span><span class="s1">&#39;first&#39;</span><span class="p">)</span> <span class="c1">// true</span>
  <span class="nx">hasCertainKey</span><span class="p">(</span><span class="nx">arr</span><span class="p">,</span><span class="s1">&#39;isCatOwner&#39;</span><span class="p">)</span> <span class="c1">// false</span>
</pre></div>
</div>
</div>
<div class="section" id="hascertainvalue">
<h3>hasCertainValue</h3>
<p>Write a function called hasCertainValue which accepts an array of objects and a key, and a value, and returns true if every single object in the array contains that value for the specific key. Otherwise it should return false.</p>
<div class="highlight-js notranslate"><div class="highlight"><pre><span></span><span class="kd">let</span> <span class="nx">arr</span> <span class="o">=</span> <span class="p">[</span>
    <span class="p">{</span><span class="nx">title</span><span class="o">:</span> <span class="s2">&quot;Instructor&quot;</span><span class="p">,</span> <span class="nx">first</span><span class="o">:</span> <span class="s1">&#39;Elie&#39;</span><span class="p">,</span> <span class="nx">last</span><span class="o">:</span><span class="s2">&quot;Schoppik&quot;</span><span class="p">},</span>
    <span class="p">{</span><span class="nx">title</span><span class="o">:</span> <span class="s2">&quot;Instructor&quot;</span><span class="p">,</span> <span class="nx">first</span><span class="o">:</span> <span class="s1">&#39;Tim&#39;</span><span class="p">,</span> <span class="nx">last</span><span class="o">:</span><span class="s2">&quot;Garcia&quot;</span><span class="p">,</span> <span class="nx">isCatOwner</span><span class="o">:</span> <span class="kc">true</span><span class="p">},</span>
    <span class="p">{</span><span class="nx">title</span><span class="o">:</span> <span class="s2">&quot;Instructor&quot;</span><span class="p">,</span> <span class="nx">first</span><span class="o">:</span> <span class="s1">&#39;Matt&#39;</span><span class="p">,</span> <span class="nx">last</span><span class="o">:</span><span class="s2">&quot;Lane&quot;</span><span class="p">},</span>
    <span class="p">{</span><span class="nx">title</span><span class="o">:</span> <span class="s2">&quot;Instructor&quot;</span><span class="p">,</span> <span class="nx">first</span><span class="o">:</span> <span class="s1">&#39;Colt&#39;</span><span class="p">,</span> <span class="nx">last</span><span class="o">:</span><span class="s2">&quot;Steele&quot;</span><span class="p">,</span> <span class="nx">isCatOwner</span><span class="o">:</span> <span class="kc">true</span><span class="p">}</span>
  <span class="p">]</span>

  <span class="nx">hasCertainValue</span><span class="p">(</span><span class="nx">arr</span><span class="p">,</span><span class="s1">&#39;title&#39;</span><span class="p">,</span><span class="s1">&#39;Instructor&#39;</span><span class="p">)</span> <span class="c1">// true</span>
  <span class="nx">hasCertainValue</span><span class="p">(</span><span class="nx">arr</span><span class="p">,</span><span class="s1">&#39;first&#39;</span><span class="p">,</span><span class="s1">&#39;Elie&#39;</span><span class="p">)</span> <span class="c1">// false</span>
</pre></div>
</div>
