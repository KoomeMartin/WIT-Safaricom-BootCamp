# WIT-Safaricom-BootCamp
I will outline practical skills acquired in the WIT AI/ML  Boot Camp 2024

<h3>EDA Training </h3>

<p>We don't do EDA as a 'ritual" but rather with intent to unearth patterns in data.</p>
Consider working with a bike sharing company (our dataset).
<p>Lets assume we own the bike sharing company and we want to get insights that can drive value for our company. We can ask ourselves a couple of questions that we may need to answer from the data like:</p>
<p>
<li>Which are the most common routes used?</li>
<li>Can we allocate more bikes in stations along this route Which are the most popular start stations?</li>
<li>Do we need more bikes here Is there a difference in trip duration/length for different types of members?</li>
<li>Is there a difference in trip duration/length by members based on rideable_type?</li>
<li>Which hour of the day do people often take trips?</li>
</p>

<p>I have tried to bring out answers to these few questions in this EDA section</p>

<h3>Recommender Systems</h3>

<p>In this project, we will analyze the interactions that users have with articles on the IBM Watson Studio platform, and make recommendations to them about new articles we think they will like.</p>

<ol>i. EDA</ol>
<p>Before making recommendations of any kind, we will need to explore the data we are working with for the project. Dive in to see what we can find. These are some of the questions answered in this section:</p>
<ul>
<li>The number of unique articles that have an interaction with a user.</li>
<li>The number of unique articles in the dataset (whether they have any interactions or not).</li>
<li>The number of unique users in the dataset. (excluding null values)</li>
<li>The number of user-article interactions in the dataset.</li>
</ul>

<ol>i. Rank Based Recommendations</ol>
<p>To get started in building recommendations, we will first find the most popular articles simply based on the most interactions. Since there are no ratings for any of the articles, it is easy to assume the articles with the most interactions are the most popular. These are then the articles we might recommend to new users (or anyone depending on what we know about them).</p>
<ol>iii. Neighborhood Based Collaborative Filtering (User-User Based)</ol>
<p>In order to build better recommendations for the users of IBM's platform, we could look at users that are similar in terms of the items they have interacted with. These items could then be recommended to the similar users; if user a and user b are similar users it means both have interacted with similar articles at a certain point, so we can recommend user a an article that user b has interacted with but a have not and vice versa.</p>


<h4>Resources and Credits</h4>
<a href='https://github.com/louisteo9/recommendations-with-IBM'>Git Repo</a>
