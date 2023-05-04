Download Link: https://assignmentchef.com/product/solved-cs5225-project-2-monte-carlo-prediction-and-control
<br>
In this project, you will be asked to implement two model-free algorithms. The first one is Monte-Carlo(MC), including the first visit of on-policy MC prediction and on-policy MC control for <a href="https://gym.openai.com/envs/Blackjack-v0/" rel="nofollow">blackjack</a>. The second one is Temporal-Difference(TD), including Sarsa(on-policy) and Q-Learning(off-policy) for <a href="https://github.com/openai/gym/blob/master/gym/envs/toy_text/cliffwalking.py">cliffwalking</a>.

<a href="https://i0.wp.com/github.com/huiminren/DS595CS525-RL-HW/blob/master/project2/img/project2-1.png?ssl=1" target="_blank" rel="noopener noreferrer"><img decoding="async" data-recalc-dims="1" data-src="https://i0.wp.com/github.com/huiminren/DS595CS525-RL-HW/raw/master/project2/img/project2-1.png?w=980&amp;ssl=1" class="lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

  <noscript>

   <img decoding="async" src="https://i0.wp.com/github.com/huiminren/DS595CS525-RL-HW/raw/master/project2/img/project2-1.png?w=980&amp;ssl=1" data-recalc-dims="1">

  </noscript></a>

<a href="https://i0.wp.com/github.com/huiminren/DS595CS525-RL-HW/blob/master/project2/img/project2-2.png?ssl=1" target="_blank" rel="noopener noreferrer"><img decoding="async" data-recalc-dims="1" data-src="https://i0.wp.com/github.com/huiminren/DS595CS525-RL-HW/raw/master/project2/img/project2-2.png?w=980&amp;ssl=1" class="lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

  <noscript>

   <img decoding="async" src="https://i0.wp.com/github.com/huiminren/DS595CS525-RL-HW/raw/master/project2/img/project2-2.png?w=980&amp;ssl=1" data-recalc-dims="1">

  </noscript></a>

<strong>TA will run your code twice. You will get full credits if one of the tests passes.</strong>

<h2><a id="user-content-hints" class="anchor" href="https://github.com/bucky1995/CS_525_RL/tree/master/Project-2#hints" aria-hidden="true"></a>Hints</h2>

<ul>

 <li>On-policy first visit Monte-Carlo prediction</li>

</ul>

<a href="https://i0.wp.com/github.com/huiminren/DS595CS525-RL-HW/blob/master/project2/img/mc_predict.png?ssl=1" target="_blank" rel="noopener noreferrer"><img decoding="async" data-recalc-dims="1" data-src="https://i0.wp.com/github.com/huiminren/DS595CS525-RL-HW/raw/master/project2/img/mc_predict.png?w=980&amp;ssl=1" class="lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

  <noscript>

   <img decoding="async" src="https://i0.wp.com/github.com/huiminren/DS595CS525-RL-HW/raw/master/project2/img/mc_predict.png?w=980&amp;ssl=1" data-recalc-dims="1">

  </noscript></a>

<ul>

 <li>On-policy first visit Monte-Carlo control</li>

</ul>

<a href="https://i0.wp.com/github.com/huiminren/DS595CS525-RL-HW/blob/master/project2/img/mc.png?ssl=1" target="_blank" rel="noopener noreferrer"><img decoding="async" data-recalc-dims="1" data-src="https://i0.wp.com/github.com/huiminren/DS595CS525-RL-HW/raw/master/project2/img/mc.png?w=980&amp;ssl=1" class="lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

  <noscript>

   <img decoding="async" src="https://i0.wp.com/github.com/huiminren/DS595CS525-RL-HW/raw/master/project2/img/mc.png?w=980&amp;ssl=1" data-recalc-dims="1">

  </noscript></a>

<ul>

 <li>Sarsa (on-policy TD control)</li>

</ul>

<a href="https://i0.wp.com/github.com/huiminren/DS595CS525-RL-HW/blob/master/project2/img/sarsa.png?ssl=1" target="_blank" rel="noopener noreferrer"><img decoding="async" data-recalc-dims="1" data-src="https://i0.wp.com/github.com/huiminren/DS595CS525-RL-HW/raw/master/project2/img/sarsa.png?w=980&amp;ssl=1" class="lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

  <noscript>

   <img decoding="async" src="https://i0.wp.com/github.com/huiminren/DS595CS525-RL-HW/raw/master/project2/img/sarsa.png?w=980&amp;ssl=1" data-recalc-dims="1">

  </noscript></a>

<ul>

 <li>Q-learing (off-policy TD control)</li>

</ul>

<a href="https://i0.wp.com/github.com/huiminren/DS595CS525-RL-HW/blob/master/project2/img/q-learning.png?ssl=1" target="_blank" rel="noopener noreferrer"><img decoding="async" data-recalc-dims="1" data-src="https://i0.wp.com/github.com/huiminren/DS595CS525-RL-HW/raw/master/project2/img/q-learning.png?w=980&amp;ssl=1" class="lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

  <noscript>

   <img decoding="async" src="https://i0.wp.com/github.com/huiminren/DS595CS525-RL-HW/raw/master/project2/img/q-learning.png?w=980&amp;ssl=1" data-recalc-dims="1">

  </noscript></a>