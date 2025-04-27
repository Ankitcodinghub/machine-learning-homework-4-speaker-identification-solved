# machine-learning-homework-4-speaker-identification-solved
**TO GET THIS SOLUTION VISIT:** [Machine Learning Homework 4-Speaker Identification Solved](https://www.ankitcodinghub.com/product/machine-learning-solved-5/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;121234&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;3&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (3 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;Machine Learning Homework 4-Speaker Identification Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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

<div class="kksr-stars-active" style="width: 138px;">
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
            5/5 - (3 votes)    </div>
    </div>
Machine Learning HW4 Speaker Identification

Outline

● Task Description

● Dataset

● Data Segmentation ● Model Architecture

● Baselines

● Report

● Guidelines

Task Introduction

● Self-attention

○ Proposed in GOOGLE’s work, Attention is all you need. It combines the strengths of RNN (consider the whole sequence) and CNN (processing parallelly).

● Goal: Learn how to use Transformer.

Ref. Prof. Hung-Yi Lee

[2021Spring ML] Transformer (1), (2)

Speaker Identification

Task: Multiclass Classification

Predict speaker class from given speech.

Dataset – VoxCeleb2

● Training: 56666 processed audio features with labels.

● Testing: 4000 processed audio features (public &amp; private) without labels. ● Label: 600 classes in total, each class represents a speaker.

VoxCeleb2: Link

Data Preprocessing

Ref. Prof. Hung-Yi Lee

[2020Spring DLHLP] Speech

Recognition

Data Format

● Data Directory

○ metadata.json

○ testdata.json

○ mapping.json ○ uttr-{random string}.pt

● The information in metadata

○ “n_mels”: The dimention of mel-spectrogram. ○ “speakers”: A dictionary.

■ Key: speaker ids

■ Value: “feature_path” and “mel_len”

Data Segmentation During Training

Different length:

Data Segmentation During Training

Different length:

Segment during training

Segment = 2

Sample Code

● Link

● Baseline Methods

○ Simple: Run sample code &amp; know how to use Transformer.

○ Medium: Know how to adjust parameters of Transformer.

○ Strong: Construct Conformer, which is a variety of Transformer.

○ Boss: Implement Self-Attention Pooling &amp; Additive Margin Softmax to further boost the performance.

Requirements – Simple

● Build a self-attention network to classify speakers with sample code.

● Simple public baseline: 0.60824

● Estimate training time: 30~40 mins on Colab.

Requirements – Medium

● Modify the parameters of the transformer modules in the sample code.

● Medium public baseline: 0.70375

Requirements – Strong

● Construct Conformer, which is a variety of Transformer. ● Strong public baseline: 0.77750

Requirements – Boss

● Implement Self-Attention Pooling &amp; Additive Margin Softmax to further boost the performance.

● Public boss baseline: 0.86500

● Estimate training time: about 2~2.5 hours on Kaggle.

Hints

● Self-Attention Pooling

Hints ● Additive Margin Softmax

Grading

● Evalute Metric: @1 Accuracy

● Simple Baseline (Public / Private) +0.5 pt / 0.5 pt

● Medium Baseline (Public / Private) +0.5 pt / 0.5 pt

● Strong Baseline (Public / Private) +0.5 pt / 0.5 pt

● Boss Baseline (Public / Private) +0.5 pt / 0.5 pt

● Code Submission +2 pts

● Report +4 pts

Submission Format

● “Id, Category” split by ‘,’ in the first row.

● Followed by 8000 lines of “filename, speaker name” split by ‘,’.

Code Submission

● Submit your code to NTU COOL (2 pts).

○ We can only see your last submission.

○ Do NOT submit the model or dataset.

○ If your codes are not reasonable, your final grade will be x 0.9 ○ You should compress your code into a single zip file:

■ ex. b08902126_hw4.zip

&lt;Student ID&gt;_hw4.zip

Report (4 pts)

1. Make a brief introduction about a variant of Transformer. (2 pts)

2. Briefly explain why adding convolutional layers to Transformer can boost performance. (2 pts)

Links

● Kaggle: link

● Colab: link

● Data: link (請參照 sample code 之下載方式)

● Dataset: link

Regulation

● You should NOT plagiarize, if you use any other resource, you should cite it in the reference. (＊)

● You should NOT modify your prediction files manually.

● Do NOT share codes or prediction files with any living creatures.

● Do NOT use any approaches to submit your results more than 5 times a day.

● Do NOT search or use additional data or pre-trained models.

● Your final grade x 0.9 if you violate any of the above rules.

● Prof. Lee &amp; TAs preserve the rights to change the rules &amp; grades.

(＊) Academic Ethics Guidelines for

Researchers by the Ministry of Science and

Technology (MOST)

If any questions, you can ask us via…

● NTU COOL (Recommended)

○ https://cool.ntu.edu.tw/courses/11666

● Email

○ The title should begin with “[hw4]”

Appendix

● Colab 縮排問題

○ 工具 -&gt; 設定：
