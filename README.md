# UN-general-debates-text-analysis

Data Provided by UCSD Poli176/DSC161;

## Project Description

Members: Haihan Tian, Jeffrey Feng, Zhexu Li
Instructor: Professor Molly Roberts
POLI 176/DSC 161
05/23/2021

## Selected Corpus

UN General Debate Corpus, collected by Baturo, Dasandi, and Mikhaylov, containing all 8093 UNGD statements presented from 1970 to 2018, and their corresponding metadata.
This corpus is great for our research questions because the nature of UNGD could allow smaller states to raise issues that they believe are important while receiving less attention. While other states could use GD as a way to influence international perceptions of their states and other states. Thus, we can observe the fairly accurate policy preferences of Israel and Palestine.  

## Research Question

How did the policy preferences in UNGD of Israel change overtime? Is there a dramatic shift after Palestine was able to speak at UNGD in 1998? Could the General Debates reflect the conflicts between Israel and Palestine?

## Research Question Significance

About two weeks ago, a serious armed conflict involving airstrikes and missile attacks broke out between Israel and Palestine. The enduring Israeli-Palestinian conflict made our group wonder whether their hostility were already embedded in their General Debates at the United Nation, and how their policy preferences changed over time. If we can find patterns in their speeches, we may understand their conflicts from a more comprehensive perspective. 

## Related Study

Jeremy Pressman (2020) ‘History in conflict: Israeli–Palestinian speeches at the United Nations, 1998–2016’, Mediterranean Politics, 25:4, 476-498, DOI: 10.1080/13629395.2019.1589936

In this paper, Pressman studied the General Debate of both Israel and Palestine from 1998 to 2016, as the result Pressman found that the leaders of both countries covered similar issues. And both countries argued that they are the ones committing for peace, while accusing the other country of invasion. While this paper doesn’t use any topic modeling techniques and only include speeches until 2016, it still helped our research by providing background knowledge of the history of Israeli-Palestinian conflict, helping us interpret the results, and providing validation for our findings. 

## Topic modeling

###  1.	Run a topic model on your corpus: Why did you choose the number of topics?
a.	LDA vs. STM: we performed LDA as well as STM analysis, and we found that since STM can take in account of medata, which will be useful in further analysis with the help of representative documents, we choose to mainly use STM.
b.	To study the changes of Israeli statements, we used STM with two topics. It basically divide Iseaeli’s statements into two categories, which allows us to discover whether there was a significant change after Palestine’s first participation at the UN General Debate in 1998. 
c.	In the final model, to study the topics of statements of these two countries altogether we decided to use 5 topics. Because we evaluated the results qualitatively, we found that if we use 10 topics there would be overlapped topics. Thus, 5 topics were best to answer our research questions.

### 2.	Interpret and label the topics.
1	palestinian, peac, peopl, state, intern, will, israel	Calling attention to the Nakba and refugees, Palestine seeks right and justice, with commitment to peace, and calls out threats from Israel. 
2	israel, iran, will, peac, year, peopl, nation	Israel points out Iran’s military threats, calling for ending its nuclear program after 2012. 
3	peac, peopl, will, nation, new, can, palestinian	Post-cold-war Israel’s promise to spread democratic values, build friendship with neighboring states, and more importantly, resolve the Palestine issue.
4	israel, arab, peac, state, nation, unit, agreement	Israel was seeking agreement with Arab countries about peace and Jews refugees, wanted to work with UN and other members to solve world problems, 
5	israel, peac, nation, will, unit, state, countri	Pre-1998 Israel addressed its responsibility to secure regional and world peace. 

### 3.	Analyze the topic model by relating one or more topics to some metadata within your corpus in a way that answers your research question.
a.	Palestine formed its distinctive topic in our 5 topics model, the first one, in which it focused on its relationship with Israel and conveyed its will for justice and how Israel is a threat to their existence. The rest of the topics are all Israel, and despite making a range of topics through their speeches, Israel focused on peace negotiation and its address of democratic values more often in speeches when and after Palestine was allowed in the UNGD on its way to formally join the United Nation: Topic 3, which included more speeches after 1998, mentioned the word “Palestine” much more often than topic 5. A careful examination of the text shows us that many texts from topic 3 showed that Israel is fully aware of the attention and expectation from the international community regarding the regional policy issues, especially the peace deal with Palestine. Before 1998, Palestines is mentioned less by Israel.

### 4.	What do you learn about your research question using the topic model?
a.	Our group learned that the statements of Israel changed much  towards topics around Palestine after Palestine was able to speak at UNGD. Before 1998, Israeli statements topics were focused on agreements with Arab countries and other international issues. After 1998, Israeli statements started to draw attention to its commitment to peace and saying Palestine failed to do that. Similarly, Palestinian statements were also trying to promote their efforts to peace and critizing Israel’s threat to them. These results suggest that the conflicts between these two countries were embedded in their statements, and Palestine’s participation at UNGD may be associated with the change of topics of Israeli statements. 

### 5.	Assess its validity -- what are some of the limitations of this approach for your research question?
a.	Our results on the topic of Palenstinian statements were consistent with Pressman’s findings. We found the metadata corresponding to the topic covered the same topics to Pressman’s description of Palenstinian statements. On the other hand, we found the Israeli statements after 1998 also covered Iran nuclear issues, but it was not mentioned in Pressman’s paper.
b.	The limitation of our approach is that we can’t tell if Palestine was able to speak at UNGD is the causal effect of the changes in Israeli statements, or there were other confounding political changes. For example, geopolitical reasons behind Palestine’s allowance to participation could be one of the reasons that caused Israel’s change in speech topics.
