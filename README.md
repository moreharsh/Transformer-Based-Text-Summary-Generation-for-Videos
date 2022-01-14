# Video Summary Generation (Transformer Based Approach)

<h2> Abstract </h2>
<p>  With advancements in the multimedia sector, abundant videos are being generated for several applications. Video summarization has gained impetus as it can extract important parts of videos thus conserving the information. Moreover, understanding video content and generating a summary of the events can be useful for automating the process of video description which is being used in several online platforms. In this project, a Transformer-based Video to Text generator is proposed that can generate a concise summary for videos containing several scene changes. The proposed pipeline involves identification of keyframes from the input videos, extraction of image features and caption generation and finally summarisation of the concatenated captions. Evaluation is done on a custom dataset, and the average BLEU 4 and ROGUE-f-measures obtained are 50.69% and 37.78% respectively. </p>

<h2> Implementation </h2>
<p> Implementation is divided into main 3 components: </p>
* Identification and extraction of keyframes from the input videos.
* Generation of captions from the extracted images. 
* Concatenating captions and summarizing them.  

<p> The entire flow of the methodology has been illustrated in Figure given below. </p>
<img src="images/image1.png" alt="Project Flow Diagram"/>

<h2> Results </h2>
<img src="images/image2.png" alt="Generated summary for the video Input1 containing Olympic games."/>
<img src="images/image3.png" alt="Generated summary for the video Input4 containing several dog activities."/>

<br />

<h2>Navigation</h2>
Following are the navigations for:

* / - colab code file
* videos/ - contains the video dataset used for testing
* images/ - conatins project flow diagram and result images


<h3>GitHub Link: </h3> <a href="https://github.com/moreharsh/Video-Summary-Generation"> https://github.com/moreharsh/Video-Summary-Generation </a>

<h2>About the Team</h2>
All the members of Team Inferno are students of Second Year Information Technology Department of Vishwakarma Institute of Technology, Pune.


* Harsh More
* Juhi Rajani
* Nirvisha Soni
* Dhruva Khanwelkar

<br />
