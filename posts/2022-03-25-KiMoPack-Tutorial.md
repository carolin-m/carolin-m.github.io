---
layout: postpage
readtime: '5 min'
title:  "Tutorial: KiMoPack"
date:   2022-03-25
image: KiMoPack_logo.png
---

The tutorial will take place on 25/03/2022 between 8:30 and 16:30 *via* Zoom. 
Here you will find the presentation slides, exercises as well as the *Jupyter notebooks* that are used 
in the hands-on sessions.
Moreover you can download the group challenges here.

_____
<h4>01) Preparation/Installation</h4>

The hands-on session of the Python tutorial will be performed using *Jupyter Notebooks*. During the course we work with the [KiMoPack](https://pypi.org/project/KiMoPack/) tool. Please make sure that you have installed [Python](https://www.python.org/), the Classical [Jupyter Notebook](https://jupyter.org/install) and [KiMoPack](https://pypi.org/project/KiMoPack/).
<br>

I recommend to install [Anaconda](https://www.anaconda.com/products/individual). If you use anaconda you need to install additional packages by opening a command line (*e.g.* using “cmd” in windows) and executing the following commands:

{%- highlight bash -%}
conda create -n kimopack
conda activate kimopack

conda install -c erdzeichen kimopack
conda install -c anaconda qt
conda install -c conda-forge lmfit
conda install -c conda-forge python-pptx
{%- endhighlight -%}

Please make sure that you can open a specific *Jupyter Notebook* (*e.g.*, see [here](https://docs.jupyter.org/en/latest/running.html)). 

You can use [this *Jupyter Notebook* (test.ipynb)](./docs/KiMoPack/test.ipynb) to verify that the installation was successful. Therefore, open *test.ipynb* and run the first cell (*e.g.* hit SHIFT + ENTER). If the installation was successful, the path to *plot_func.py* and your current working directory will be printed. If there are any problems, feel free to contact me.

_____
<h4>02) Tutorial </h4>

<p>
<ul>
  <li><a class="btn btn-lg btn-success" href="../docs/KiMoPack/Presentation-Slides_Exercises.pdf"> Presentation Slides and Exercises</a></li>
  <br>
  <li><a class="btn btn-lg btn-success" href="../docs/KiMoPack/00_hands-on_session.zip"> Hands-on Session 00 - Introduction to Python</a></li>
  <br>
  <li><a class="btn btn-lg btn-success" href="../docs/KiMoPack/01_hands-on_session.zip"> Hands-on Session 01 - Analysis Workflow with KiMoPack</a></li>
  <br>
  <li><a class="btn btn-lg btn-success" href="../docs/KiMoPack/02_hands-on_session.zip"> Hands-on Session 02 - Defining and Optimizing Kinetic Models</a></li>
</ul>
</p>

<img width=600 src='https://raw.githubusercontent.com/carolin-m/carolin-m.github.io/main/img/pub/TOC_KiMoPack.png'> 

_____
<h4>03) Group Challenges </h4> 

<p>
<ul class="list-inline">
  <li><a class="btn btn-lg btn-success" href="../docs/KiMoPack/Group01.zip"> Group 01</a></li>
  <li><a class="btn btn-lg btn-success" href="../docs/KiMoPack/Group02.zip"> Group 02</a></li>
  <li><a class="btn btn-lg btn-success" href="../docs/KiMoPack/Group03.zip"> Group 03</a></li>
  <li><a class="btn btn-lg btn-success" href="../docs/KiMoPack/Group04.zip"> Group 04</a></li>
</ul>
</p>

_____
<h4>04) Follow-up</h4>

<p>
<ul class="list-inline">
  <li><a class="btn btn-lg btn-success" href=""> Hands-on Session - Solutions</a></li>
  <li><a class="btn btn-lg btn-success" href="../docs/KiMoPack/Solutions_Group-Challenges.zip"> Group Challenge - Solutions</a></li>
</ul>
</p>
