---
layout: project
urltitle:  "Self-supervision for reinforcement learning (SSL-RL)"
title: "Self-supervision for reinforcement learning (SSL-RL)"
categories: workshop, iclr, self-supervised learning, reinforcement learning, deep learning, 2021
permalink: /
bibtex: true
paper: true
acknowledgements: ""
---
<br/>
<div class="row reverse">
  <div class="col-xs-12 col-md-7">
    <h1>Self-supervision for Reinforcement Learning (SSL-RL)</h1>
    <br>
    <h4>May 7, 2021 // ICLR Workshop</h4>
    <br>
    <br>
    <p>
        Reinforcement learning (RL) entails letting an agent learn through interaction with an environment. The formalism is powerful in it’s generality, and presents us with a hard open-ended problem: how can we design agents that learn efficiently, and generalize well, given only sensory information and a scalar reward signal? The goal of this workshop is to explore the role of self-supervised learning within reinforcement learning agents, to make progress towards this goal. 
    </p>

    <font color="c31"><b>Update:</b></font> We are releasing a Q&A form where every workshop participant can ask a question to invited speakers: <a href="https://docs.google.com/forms/d/1KaF4omXVoXvZ8I3CxHK7AE7sRHsd-BfoYF372hR5Tdg/viewform?ts=6091a10c">Link to form</a>. 
    <br>
    There will also be a 5 to 10 minute period at the end of each talk where live questions can be asked.
  </div>
  <div class="col-md-1 hidden-xs">
  </div>
  <div class="col-xs-12 col-md-4">
    <img class="cover" src="/static/img/cover.jpg">
  </div>
</div>

<br/>

<div class="row">
    <div class="col-xs-8">
        
    </div>

</div>


<br />

<div class="row" id="dates">
  <div class="col-xs-12">
    <h2>Important Dates</h2>
  </div>
</div>

<br>
<div class="row">
  <div class="col-xs-12">
    <table class="table table-striped">
      <tbody>
        <tr>
          <td>Paper Submission Deadline</td>
          <td><s>February 26, 2021</s> March 7, 2021 AoE</td>
        </tr>
        <tr>
          <td><s>Decision Notifications</s></td>
          <td>March 26, 2021 </td>
        </tr>
        <tr>
          <td><s>Camera Ready Paper Deadline</s></td>
          <td>April 25, 2021 AoE</td>
        </tr>
        <tr>
          <td>Workshop</td>
          <td>Friday, May 7, 2021</td>
        </tr>
      </tbody>
    </table>
  </div>
</div>

<br />

<div class="row" id="cfp">
  <div class="col-xs-12">
    <h2>Call for Papers</h2>
  </div>
</div>






<div class="row">
  <div class="col-xs-12">
    <p>
      We invite both short (4 page) and long (8 page) anonymized submissions in the <a href="https://github.com/ICLR/Master-Template/raw/master/archive/iclr2021.zip">ICLR LaTeX format</a> that develop algorithms, benchmarks, and ideas to allow reinforcement learning agents to learn more effectively by making self-supervised predictions about their environment. More concretely, we welcome submissions around, but not necessarily limited to, the following broad questions: 
    </p>
    <p>
          <ul>
              <li>How can we leverage large amounts of unlabelled sensory data from diverse sources to bootstrap learning for reinforcement learning tasks?</li>
              <li>Can we use auxiliary targets --- generated in an unsupervised manner --- to accelerate learning?</li>
              <li>Can we meta-learn auxiliary targets that accelerate learning for a wide range of tasks?</li>
              <li>Can we build benchmarks and protocols for systematically comparing existing self-supervision methods? </li>
              <li>Do agents that learn multiple auxiliary predictions generalize better to new environments than those that learn purely by maximizing the reward?</li>
              <li>Can we learn predictive state representations to accelerate learning and generalization?  </li>
              <li>Can we benefit from insights gained from cognitive and neuroscience to build better self-supervisory objectives? </li>
          </ul>
      </p>
      <p>We welcome review and positional papers that may foster discussions. We also encourage published papers from <i>*non-ML*</i> conferences, e.g. epistemology, cognitive science, psychology, neuroscience, that are within the scope of the workshop.
       Note that as per ICLR guidelines, we don't accept works previously published in other conferences on machine learning, but are open to works that are currently under submission to a conference (such as ICML 2021).</p>
      
      <p>
        Submissions should be uploaded on OpenReview: <a class="red" href="https://openreview.net/group?id=ICLR.cc/2021/Workshop/SSL-RL">SSL-RL submission link</a>
      </p>
      <p>
        In case of any issues or questions, feel free to email the workshop organizers at: <a href="mailto:sslrl.ws.iclr2021@gmail.com" class="red">sslrl.ws.iclr2021@gmail.com</a>.
      </p>

  </div>
</div>


<br />


<hr />

<div class="row" id="speakers">
  <div class="col-xs-12">
    <h2>Speakers</h2>
  </div>
</div>

<div class="row">
  <div class="col-xs-6 col-lg-3 people">
    <a href="http://www.pyoudeyer.com/">
      <img class="people-pic" src="{{ "/static/img/people/py_oudeyer.jpg" | prepend:site.baseurl }}">
    </a>
    <div class="people-name">
      <a href="http://www.pyoudeyer.com/">Pierre-Yves Oudeyer</a>
      <h6>INRIA/ Flowers team</h6>
    </div>
  </div>
  <div class="col-xs-6 col-lg-3 people">
    <a href="https://scholar.google.com/citations?user=YWVuCKUAAAAJ&hl=en">
      <img class="people-pic" src="{{ "/static/img/people/irina_higgins.png" | prepend:site.baseurl }}">
    </a>
    <div class="people-name">
      <a href="https://scholar.google.com/citations?user=YWVuCKUAAAAJ&hl=en">Irina Higgins</a>
      <h6>DeepMind</h6>
    </div>
  </div>
  <div class="col-xs-6 col-lg-3 people">
    <a href="https://danijar.com/">
      <img class="people-pic" src="{{ "/static/img/people/danijar_hafner.jpg" | prepend:site.baseurl }}">
    </a>
    <div class="people-name">
      <a href="https://danijar.com/">Danijar Hafner</a>
      <h6>University of Toronto</h6>
    </div>
  </div>
  <div class="col-xs-6 col-lg-3 people">
    <a href="http://www.elisevanderpol.nl/">
      <img class="people-pic" src="{{ "/static/img/people/elise_van_der_pol.jpg" | prepend:site.baseurl }}">
    </a>
    <div class="people-name">
      <a href="http://www.elisevanderpol.nl/">Elise van der Pol</a>
      <h6>University of Amsterdam</h6>
    </div>
  </div>
  <div class="col-xs-6 col-lg-3 people">
    
  </div>
  <div class="col-xs-6 col-lg-3 people">
    <a href="https://www.microsoft.com/en-us/research/people/jcl/">
      <img class="people-pic" src="{{ "/static/img/people/john_langford.jpg" | prepend:site.baseurl }}">
    </a>
    <div class="people-name">
      <a href="https://www.microsoft.com/en-us/research/people/jcl/">John Langford</a>
      <h6>Microsoft Research, New York</h6>
    </div>
  </div>
  <div class="col-xs-6 col-lg-3 people">
    <a href="http://www.princeton.edu/~yael/">
      <img class="people-pic" src="{{ "/static/img/people/yael_niv.jpg" | prepend:site.baseurl }}">
    </a>
    <div class="people-name">
      <a href="http://www.princeton.edu/~yael/">Yael Niv</a>
      <h6>Princeton</h6>
    </div>
  </div>
</div>

<hr />

<div class="row" id="intro">
    <div class="col-xs-12">
        <h2>Introduction</h2>
        <p>Self-Supervised Learning for a RL agent involves the agent learning (and possibly discovering) many predictions about it’s world. For example, a natural self-supervised prediction task within an agent is to learn the transition dynamics of the environment [1-4]. But given the rich sequential and interactive nature of RL environments, many other prediction tasks could be used as well [5-9]. Self-supervised learning has several possible benefits. First, the agent can directly use its learned primitives to facilitate future learning, by endowing itself with learned priors instead of starting tabula-rasa [10-12]. Second, the agent can indirectly benefit from the learned predictions, by learning a representation that is useful for many different predictions [13]. Such a representation should also facilitate efficient learning [14-15] and exhibit better generalization [16-17]</p>. 

        <p> The aims of this workshop are to explore the potential benefits of self-supervision, how to specify self-supervised tasks, and to bring together people from different areas, including Cognitive Science, Reinforcement Learning, and Computer Vision, with a common interest in building better learning agents. The specific research questions we hope to tackle include:</p>
        <ul>
        <li>How can we leverage unsupervised data to bootstrap learning in an MDP, and what primitives should we learn: dynamics, representation, skills or something else?</li>
        <li>How can we measure progress in development of self-supervised, general purpose agents? Do we need to create a GLUE like benchmark for RL?</li>
        <li>What kind of structure in an MDP can an agent exploit to learn a task faster?</li>
        <li>How can we design self-supervised objectives that encourage an agent to generalize well out of its training distribution?</li>
        <li>Can we leverage insights from cognitive science on how humans acquire knowledge to build better self-supervised objectives?</li>
        </ul>
    </div>
</div>

<hr />

<div class="row" id="mindmatch">
    <div class="col-xs-12">
        <h2>Mind Match Program</h2>
        <p> The Mind Match event is aimed as a catalyst for discussion between researchers with shared interests,
         similar to the <a href="https://neuromatch.io/instructions/how-to-register">Neuromatch</a> and <a href="https://baicsworkshop.github.io/format.html">BAICS</a> events.
         Participants will be split into small groups according to topics of interest,
         and will have a chance to informally chat, discuss together and potentially setup collaborations. 
         </p> 
         <p>
         Sing up 
         <a href="https://docs.google.com/forms/d/1yJAQnIRLRaUd3Zxn6pAmSLxNY8OBseO5Jw4EZxHQG9s" class="red">here</a>, 
         and we will notify you of your groups and the meeting link prior to the event. 
        </p>. 

    </div>
</div>

<hr />

<div class="row" id="organizers">
  <div class="col-xs-12">
    <h2>Organizers</h2>
  </div>
</div>
<div class="row">
  <div class="col-xs-6 col-lg-3 people">
    <a href="https://amyzhang.github.io/">
      <img class="people-pic" src="{{ "/static/img/people/amy_zhang.png" | prepend:site.baseurl }}">
    </a>
    <div class="people-name">
      <a href="https://amyzhang.github.io/">Amy Zhang</a>
      <h6>McGill University / Mila / Facebook</h6>
    </div>
  </div>
  <div class="col-xs-6 col-lg-3 people">
    <a href="https://ankeshanand.com/">
      <img class="people-pic" src="{{ "/static/img/people/ankesh_anand.jpg" | prepend:site.baseurl }}">
    </a>
    <div class="people-name">
      <a href="https://ankeshanand.com/">Ankesh Anand</a>
      <h6>University of Montreal / Mila</h6>
    </div>
  </div>
  <div class="col-xs-6 col-lg-3 people">
    <a href="https://bmazoure.github.io/">
      <img class="people-pic" src="{{ "/static/img/people/bogdan_mazoure.jpg" | prepend:site.baseurl }}">
    </a>
    <div class="people-name">
      <a href="https://bmazoure.github.io/">Bogdan Mazoure</a>
      <h6>McGill University / Mila</h6>
    </div>
  </div>
  <div class="col-xs-6 col-lg-3 people">
    <a href="https://rdevon.github.io/">
      <img class="people-pic" src="{{ "/static/img/people/devon_hjelm.jpg" | prepend:site.baseurl }}">
    </a>
    <div class="people-name people">
      <a href="https://rdevon.github.io/">Devon Hjelm</a>
      <h6>Microsoft Research / University of Montreal</h6>
    </div>
  </div>
  <div class="col-xs-6 col-lg-3 people">
    <a href="https://sites.ualberta.ca/~kjaved/">
      <img class="people-pic" src="{{ "/static/img/people/khurram_javed.jpg" | prepend:site.baseurl }}">
    </a>
    <div class="people-name">
      <a href="https://sites.ualberta.ca/~kjaved/">Khurram Javed</a>
      <h6>University of Alberta / AMII</h6>
    </div>
  </div>
  <div class="col-xs-6 col-lg-3 people">
    <a href="http://webdocs.cs.ualberta.ca/~whitem/">
      <img class="people-pic" src="{{ "/static/img/people/martha_white.jpg" | prepend:site.baseurl }}">
    </a>
    <div class="people-name">
      <a href="http://webdocs.cs.ualberta.ca/~whitem/">Martha White</a>
      <h6>University of Alberta / AMII</h6>
    </div>
  </div>
  <div class="col-xs-6 col-lg-3 people">
    <a href="https://tldoan.github.io/">
      <img class="people-pic" src="{{ "/static/img/people/thang_doan.jpg" | prepend:site.baseurl }}">
    </a>
    <div class="people-name">
      <a href="https://tldoan.github.io/">Thang Doan</a>
      <h6>McGill University / Mila</h6>
    </div>
  </div>
</div>

<hr />


<div class="row" id="accepted">
  <div class="col-xs-12">
    <h2>Accepted papers</h2>
  </div>
</div>
<div class="row">
  <div class="col-md-12">
    <ol>
<li><b>[Oral]</b> <i>Learning One Representation to Optimize All Rewards</i>. Ahmed Touati, Yann Ollivier.</li>
<li><b>[Oral]</b> <i>Learning Generalizable Robotic Reward Functions from "In-The-Wild" Human Videos</i>. Annie S Chen, Suraj Nair, Chelsea Finn.</li>

<li><b>[Spotlight]</b> <i>Reinforcement Learning with Prototypical Representations</i>. Denis Yarats, Rob Fergus, Alessandro Lazaric, Lerrel Pinto.</li>
<li><b>[Spotlight]</b> <i>Causal Inference Q-Network: Toward Resilient Reinforcement Learning</i>. Chao-Han Huck Yang, Danny I-Te Hung, Yi Ouyang, Pin-Yu Chen.</li>
<li><b>[Spotlight]</b> <i>Augmented World Models Facilitate Zero-Shot Dynamics Generalization From a Single Offline Environment</i>. Philip Ball, Cong Lu, Jack Parker-Holder, Stephen Roberts.</li>

<li><b>[Poster]</b> <i>COMBO: Conservative Offline Model-Based Policy Optimization</i>. Tianhe Yu, Aviral Kumar, Rafael Rafailov, Aravind Rajeswaran, Sergey Levine, Chelsea Finn.</li>
<li><b>[Poster]</b> <i>Demonstration-Guided Reinforcement Learning with Learned Skills</i>. Karl Pertsch, Youngwoon Lee, Yue Wu, Joseph J Lim.</li>
<li><b>[Poster]</b> <i>Generalizable Representations for Reinforcement Learning</i>. Rutav Shah, Vikash Kumar.</li>
<li><b>[Poster]</b> <i>Goal Reaching via Recursive Reweighting of Offline Data</i>. Scott Emmons, Benjamin Eysenbach, Sergey Levine.</li>
<li><b>[Poster]</b> <i>Learning State Representations via Temporal Cycle-Consistency Constraint in Model-Based Reinforcement Learning</i>. Changmin Yu, Dong Li, Hangyu Mao, Jianye Hao, Neil Burgess.</li>
<li><b>[Poster]</b> <i>Learning Task Informed Abstractions</i>. Xiang Fu, Ge Yang, Pulkit Agrawal, Tommi S. Jaakkola.</li>
<li><b>[Poster]</b> <i>Learning to Explore a Class of Multiple Reward-Free Environments</i>. Mirco Mutti, Mattia Mancassola, Marcello Restelli.</li>
<li><b>[Poster]</b> <i>Learning to Infer Unseen Contexts in Causal Contextual Reinforcement Learning</i>. Hamid Eghbal-zadeh, Florian Henkel, Gerhard Widmer.</li>
<li><b>[Poster]</b> <i>Less Suboptimal Learning and Control in Variational POMDPs</i>. Baris Kayalibay, Atanas Mirchev, Patrick van der Smagt, Justin Bayer.</li>
<li><b>[Poster]</b> <i>LOCO: Adaptive exploration in reinforcement learning via local estimation of contraction coefficients</i>. Manfred Diaz, Liam Paull, Pablo Samuel Castro.</li>
<li><b>[Poster]</b> <i>Minimum Description Length Skills for Accelerated Reinforcement Learning</i>. Jesse Zhang, Karl Pertsch, Jiefan Yang, Joseph J Lim.</li>
<li><b>[Poster]</b> <i>Model-Invariant State Abstractions for Model-Based Reinforcement Learning</i>. Manan Tomar, Amy Zhang, Roberto Calandra, Matthew E. Taylor, Joelle Pineau.</li>
<li><b>[Poster]</b> <i>Offline Reinforcement Learning with Pseudometric Learning</i>.  Robert Dadashi, shideh rezaeifar, Nino Vieillard, Leonard Hussenot, Olivier Pietquin, Matthieu Geist.</li>
<li><b>[Poster]</b> <i>Optimism is All You Need: Model-Based Imitation Learning From Observation Alone</i>.  Rahul Kidambi, Jonathan Daniel Chang, Wen Sun.</li>
<li><b>[Poster]</b> <i>Out-of-distribution generalization of internal models is correlated with reward</i>.  Khushdeep Singh Mann, Steffen Schneider, Alberto Chiappa, Jin Hwa Lee, Matthias Bethge, Alexander Mathis, Mackenzie W Mathis.</li>
<li><b>[Poster]</b> <i>Pretraining Reward-Free Representations for Data-Efficient Reinforcement Learning</i>. Max Schwarzer, Nitarshan Rajkumar, Michael Noukhovitch, Ankesh Anand, Laurent Charlin, R Devon Hjelm, Philip Bachman, Aaron Courville.</li>
<li><b>[Poster]</b> <i>PsiPhi-Learning: Reinforcement Learning with Demonstrations using Successor Features and Inverse Temporal Difference Learning</i>. Angelos Filos, Clare Lyle, Yarin Gal, Sergey Levine, Natasha Jaques, Gregory Farquhar.</li>
<li><b>[Poster]</b> <i>Relevant Action Matters : Motivating agent with action usefulness</i>. Mathieu Seurin, Florian Strub, Philippe Preux, Olivier Pietquin.</li>
<li><b>[Poster]</b> <i>Representation Matters: Offline Pretraining for Sequential Decision Making</i>. Mengjiao Yang, Ofir Nachum.</li>
<li><b>[Poster]</b> <i>Resolving Causal Confusion in Reinforcement Learning via Robust Exploration</i>. Clare Lyle, Amy Zhang, Minqi Jiang, Joelle Pineau, Yarin Gal.</li>
<li><b>[Poster]</b> <i>Self-Supervised Exploration via Latent Bayesian Surprise</i>. Pietro Mazzaglia, Ozan Catal, Tim Verbelen, Bart Dhoedt.</li>
<li><b>[Poster]</b> <i>Solipsistic Reinforcement Learning</i>. Mingtian Zhang, Peter Noel Hayes, Tim Z. Xiao, Andi Zhang, David Barber.</li>
<li><b>[Poster]</b> <i>State Entropy Maximization with Random Encoders for Efficient Exploration</i>. Younggyo Seo, Lili Chen, Jinwoo Shin, Honglak Lee, Pieter Abbeel, Kimin Lee.</li>
<li><b>[Poster]</b> <i>Unsupervised Feature Learning for Manipulation with Contrastive Domain Randomization</i>. Carmel Rabinovitz, Niko Grupen, Aviv Tamar.</li>
<li><b>[Poster]</b> <i>Variational Model-Based Imitation Learning in High-Dimensional Observation Spaces</i>. Rafael Rafailov, Tianhe Yu, Aravind Rajeswaran, Chelsea Finn.</li>






</ol>
  </div>
</div>



<div class="row">
  <div class="col-xs-12">
    <h2>References</h2>
  </div>
</div>
<div class="row">
  <div class="col-md-12">
    <ol>
<li>Finn, Chelsea, Ian Goodfellow, and Sergey Levine. "Unsupervised learning for physical interaction through video prediction." NeurIPS (2016).</li>   
<li>Ha, David, and Jürgen Schmidhuber. "Recurrent world models facilitate policy evolution." NeurIPS (2018). </li>
<li>Hafner, Danijar, et al. "Learning latent dynamics for planning from pixels." ICML (2019).  </li>
<li>Kipf, Thomas, Elise van der Pol, and Max Welling. "Contrastive learning of structured world models." arXiv.  (2019). </li>
<li>Schmidhuber, Jürgen. "A possibility for implementing curiosity and boredom in model-building neural controllers." Proc. of the international conference on simulation of adaptive behavior: From animals to animals.  (1991). </li>
<li>Klyubin, Alexander S., Daniel Polani, and Chrystopher L. Nehaniv. "Empowerment: A universal agent-centric measure of control." IEEE Congress on Evolutionary Computation.  (2005). </li>
<li>Sutton, Richard S., et al. "Horde: A scalable real-time architecture for learning knowledge from unsupervised sensorimotor interaction." The 10th International Conference on Autonomous Agents and Multiagent Systems-Volume 2. 2011. </li>
<li>Mohamed, Shakir, and Danilo Jimenez Rezende. "Variational information maximisation for intrinsically motivated reinforcement learning." NeurIPS (2015). </li>
<li>Pathak, Deepak, et al. "Curiosity-driven exploration by self-supervised prediction." Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition Workshops.  (2017). </li>
<li>Ebert, Frederik, et al. "Visual foresight: Model-based deep reinforcement learning for vision-based robotic control." arXiv.  (2018). </li>
<li>Sekar, Ramanan, et al. "Planning to Explore via Self-Supervised World Models." arXiv.  (2020). </li>
<li>Lynch, Corey, et al. "Learning latent plans from play." CoRL. (2020). </li>
<li>Jaderberg, Max, et al. "Reinforcement learning with unsupervised auxiliary tasks." arXiv.(2016). </li>
<li>Eslami, SM Ali, et al. "Neural scene representation and rendering." Science. (2018). </li>
<li>Anand, Ankesh, et al. "Unsupervised state representation learning in atari." NeurIPS (2019). </li>
<li>Srinivas, Aravind et al. "CURL: Contrastive Unsupervised Representations for Reinforcement Learning" ICML (2020). </li>
<li>Zhang, Amy, et al. "Learning invariant representations for reinforcement learning without reconstruction." arXiv (2020).  </li>
<li>Mazoure, Bogdan, et al. "Deep reinforcement and infomax learning." NeurIPS (2020). </li>
<li> Stooke, Adam, et al. "Decoupling representation learning from reinforcement learning." arXiv preprint arXiv:2009.08319 (2020). </li>
<li>Hansen, Nicklas, et al. "Self-Supervised Policy Adaptation during Deployment." arXiv (2020). </li>
<li> Agarwal, Rishab, et al. "Contrastive Behavioral Similarity Embeddings for Generalization in Reinforcement Learning" ICLR (2021). </li>
<li>Schwarzer, Max, et al. "Data-Efficient Reinforcement Learning with Self-Predictive Representations." ICLR (2021) </li>

</ol>
  </div>
</div>

<div class="text-center p-3" style="background-color: rgba(0, 0, 0, 0)">
    <h6>Website theme inspired from the <a href="https://github.com/vigilworkshop/vigilworkshop.github.io">VIGIL workshop</a>. Cover art by <a href="https://www.mattdixon.co.uk">Matt Dixon</a></h6>
  </div>
