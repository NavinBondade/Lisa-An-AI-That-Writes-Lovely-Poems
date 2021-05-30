# Writing Creative Poems With Deep Learning And NLP
<p align="center">
<a href="https://nbviewer.jupyter.org/github/NavinBondade/Lisa-An-AI-That-Writes-Lovely-Poems/blob/main/Notebook/Poem_Writing_AI%20%282%29.ipynb" target="_blank">
  <img align="center"  src="https://github.com/NavinBondade/Distinguishing-Fake-And-Real-News-With-Deep-Learning/blob/main/Graphs/button_if-github-fails-to-load-the-notebook-click-here%20(4).png?raw=true"/>
</a>
</p>
<img src="https://assets.readitforward.com/wp-content/uploads/2017/10/poems_art-900x675.png" width="950" height="650">
<p>“There is no rule on how to write. Sometimes it comes easily and perfectly: sometimes it’s like drilling rock and then blasting it out with charges” — Ernest Hemingway</p></p>Following this notion, here in this project, I have created a system that uses natural language processing and a deep learning system for writing beautiful poems.</p>
<h2>Libraries Used</h2>
<ul>
  <li>Tensorflow</li>
  <li>Keras</li>
  <li>Numpy</li>
  <li>Pandas </li>
  <li>Matplotlib</li>
  <li>Seaborn</li>
  <li>Sklearn</li>
  <li>Spacy</li>
  <li>BeautifulSoup</li>
  <li>Wordcloud</li>
</ul>
<h2>Model Details</h2>
<p align="center">
<img src="https://github.com/NavinBondade/Lisa-An-AI-That-Writes-Lovely-Poems/blob/main/Graphs/Model.png" alt="model" >
</p> 
<p>For generating the poetry, I have created a deep learning model that uses two LSTM layers which help the model to remember long-term dependencies and learn the relationship between the poem sentence. The LSTM layers are get followed by two dense layers, one uses RELU as an activation function, and the last dense layer using softmax.</p>
<h2>Model Traning</h2>
<p>The model has trained for 170 epochs. During training, the model uses Adam as an optimizer and uses categorical cross-entropy as the loss function to penalize the model more when it makes a false prediction.</p>
<h2>Model Analysis</h2>
<p align="center">
<img src="https://github.com/NavinBondade/Lisa-An-AI-That-Writes-Lovely-Poems/blob/main/Graphs/Loss.png" alt="Loss" >
</p>
<p align="center">
<img src="https://github.com/NavinBondade/Lisa-An-AI-That-Writes-Lovely-Poems/blob/main/Graphs/Accuracy.png" alt="Accuracy" >
</p>
<p>After model training for 170 epochs, the model has achieved an impressive accuracy of 95% and a very low loss of 0.1782.</p>
<h2>Beautiful Poems (Model's Ouput)</h2>
<h3>Title: Friendship</h3>
<p>an worry as we send instead of my purpose an <br>
irish trunk tshirts when my hand back i found my <br>
cousin milton worked for a cable company the boy i <br>
have become the person who says darling who says sugarpie <br>
metaphor maybe nothing to do but brush back the tears</p>
<h3>Title: Love</h3>
<p>of us bear that have so near his message is <br>
anything central orchards flung out on the land urban forests <br>
or whose hollows was mean visited up there still sister <br>
and you are both let me be no one and <br>
yesterday something shattering happened not yesterday but several that is <br>
anything central orchards flung out on the land urban forests</p>
<h3>Title: Life</h3>
<p>passes through places pj duffy landscapes of south ulster patrick <br>
amount soul lady certainly for night give well historical the <br>
cat has the chance to make the sunlight beautiful to <br>
imagine the next weeping of the next ear you see <br>
everything looped spiraled circular thought but the labyrinths not a</p>
<h3>Title: Sadness</h3>
<p>i believe for love my own name love and warn <br>
of time and even whatever i know an grant you <br>
are running away from everyone who loves you from your <br>
husband is stretched out on the ground as if he <br>
brings me chocolate from the pentagon dark chocolates shaped like</p>
