# database-homework-2-entity-relationship-model-conference-review-system-solved
**TO GET THIS SOLUTION VISIT:** [Database Homework 2-Entity-Relationship Model Conference Review System Solved](https://www.ankitcodinghub.com/product/database-homework-2-entity-relationship-model-conference-review-system-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;97085&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;Database Homework 2-Entity-Relationship Model Conference Review System Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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

<div class="kksr-stars-active" style="width: 0px;">
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
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
Entity-Relationship Model Conference Review System

With your homework team, create an ER model diagram for the scenario described below. Submit the diagram along with any assumptions or explanations.

Consider a system for managing conference paper reviews. Such systems are used to help administer the process of deciding which researchers’ papers can be presented/published at an academic conference. Researchers submit their papers for consideration for inclusion in the conference, and each paper is reviewed to see whether or not it is worthy of being included.

Assume this system manages a single conference, but the conference is held annually, and all records from each annual meeting must be saved in the database. These records are important for recruiting authors and reviewers, and for advertising how selective the conference is.

Researchers write papers about their research and can submit one or more papers to the conference each year. Researchers can also serve as reviewers during any year (whether or not they submit a paper). Each submitted paper requires at least 2 reviews. The system allows reviewers to record their comments about each paper, score the paper with respect to some categories, and recommend whether to accept or reject the paper. The detailed requirements are as follows:

<ul>
<li> &nbsp;Paper authors are uniquely identified by their email address. Their first and last names are also kept, as well as their affiliation(s).</li>
<li> &nbsp;Each paper is assigned a unique id, and has a title, an abstract, one or more topics, and the filename of the paper itself. Once the reviewing process is over, the final decision (which is either accept or reject) for the paper in the conference is stored. The final decision is made after all reviews are submitted, and is a human decision based on all the scores and comments in each review.</li>
<li> &nbsp;A paper may have multiple authors, but a single author is designated as the contact author. The contact author is the one who gets all the emails about the paper.</li>
<li> &nbsp;Reviewers are uniquely identified by email address. A reviewer’s first and last name, phone number, affiliation(s), and set of topics of expertise are kept. Also, the total number of papers that have been reviewed by this author is stored.</li>
<li> &nbsp;Each paper is assigned multiple (at least 2) reviewers. A reviewer rates a paper on a scale of 1- 10 in four categories: technical merit, readability, originality, and relevance (to the conference). They also give an overall recommendation, which is either accept or reject.</li>
<li> &nbsp;A review also includes two text comments: comments to the author, and private comments (to the committee who will make the final decisions about the papers).</li>
<li> &nbsp;Authors can also act as reviewers, but they cannot review papers written by themselves or any person who currently shares or has shared the same affiliation as them in the past.</li>
<li> &nbsp;An affiliation is a university or research lab where the person works or has worked in the past. It has a name, country code, and website address. A researcher may have one or more current affiliations, and any number of previous affiliations. A researcher’s current affiliations have a from-date but the to-date is empty. Previous affiliations have the from-date and to-date filled in.</li>
<li> &nbsp;Presumably, there is some software module that automates the matching of reviewers to papers, using the topics and affiliations.</li>
</ul>
</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
 A paper’s most current state in the review process (and the date-time the state was entered), per reviewer, must be stored for each paper. The review process is as follows:

o A paper is assigned to a reviewer.

o The reviewer either accepts or rejects the offer to review the paper. If the offer to

review is rejected, the reason for rejection is stored.

o The reviewer can work on the review and save their work without submitting the final

review. Finally, the review is submitted.

</div>
</div>
</div>
