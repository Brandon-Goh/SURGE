# SURGE
### EnactusHacks2.0
*Supporting Underrepresented Groups Everywhere: A safe space for people interested/passionate about helping under-respresented minorities*

![SURGE logo](https://challengepost-s3-challengepost.netdna-ssl.com/photos/production/software_photos/001/262/296/datas/gallery.jpg)


     1. Feasibility-Execution plan

**In-depth plan and timeline from idea to product**

Firebase could be used for small scale - ready in 2 weeks. Realistic would be 1 month to get it running, change the program to support more traffic (switch to larger server).
Possible algorithms to detect fake news, could be added in the following 2-4 weeks of development.

**Identification of risks**

- Platform transforming into a political eco chamber
- Hate speech
- Certain groups not receiving recognition

**Methods to mitigate the risks**

Our market research has shown that this is unlikely.
We will keep a close eye on platform comments
Over 80% of respondents wanted to use this platform as a  way to obtain legitimate information
 Over 70% are interested in becoming positively involved in social justice issues.
Implementation of an algorithm to sift out comments containing certain terms.
Use analytics to measure the performance of various posts and try to balance interactions


     2. Feasibility- Financial

**In-depth financial projection for short term- < 1 year**

Expenses - little to no operating cost under 10,000 users.
Expected Revenue - $3750-$7500 at 50 cents per ad. (250-500 ads per day)
- 50 Cents per ad 
- 250-500 ads per day 30 days a month
- Translates to less than 0.05 ads per user per day

**Long term financial projections > 1 year**

Expenses - $370-$500 per month, up to 100,000 users (cost for server).
Expected Revenue -  $45,000-$90,000 per month, at  60 cents per ad. (2500-5000 ads per day)
- 60 Cents per ad ✖ 2500-5000 ads per day✖ 30 days a month
- Translates to less than 0.05 ads per user per day

**Projections of expenses and revenues**

Done above 

**Summary of Business model**

Ad-based revenue model.
Similar to Facebook/LinkedIn model, businesses will be charged on an ad-per-day basis.
Bid-based model will increase the price as more businesses compete for space.

**Methods of raising starting capital**

Government Grants (Canada Student Summer Business Grant)
University Incubators (Western University Propel, Ryerson DMZ)
Early Stage Venture Funds (Front Row Ventures)

       3. Feasibility- Market Strategy

**Include internal and external factors affecting the business**

Underrepresented groups are more likely to live in poverty - restricting access to social media.
 Program accessibility for disabled users
 Do not display ads from unethical organizations
90% of 18-29 year olds use social media
82% of 30-49 year olds use social media.
Good chance our intended audience will be comfortable using a social media platform.

**Product, Price, Place and Promotion**

A user friendly social media platform. Discussion based, community emphasis, diverse support.
There is no cost to members, as this application is being developed with inclusivity and ease of use in mind.
All required funding will be obtained through ad revenues, so members can make full use of our services, free of charge.

**Segmentation & Target Market**

Demographics: 18-49 years old, own an electronic device (computer, smartphone, tablet), all genders.
Psychographics: activism, social justice, community building, mentorship, prosocial.
Competition Analysis
There does not appear to be any similar app which provides a safe space for all underrepresented groups to meet collectively. 
Political, Economic, Social and Technological factors
Many people belonging to underrepresented groups may not personally know anyone who experiences the same struggles as them.  Our platform will enable them to connect with others like them and feel less social isolation.
Individuals interested in increasing their social activism can join these groups to learn about issues important to them and join in events. This will also be a great platform for any questions to be asked of those who can provide representative answers.

        4. Tech Implementation- Technical Decision Making

**Determining the correct technologies**

This idea was created in the form of a responsive web application that can be optimized for mobile devices as well. This allows us to gain the maximum reach through mobile and desktop users. 

The front-end of this application was built using HTML 5, JavaScript, CSS, and Node.JS. The decision to not use a framework was due to the time constraint and learning curve of complex frameworks such as React or Angular as this allowed us to create a simple yet effective user experience.

The back-end was taken care of using Google’s Firebase platform which made the back-end functionalities very easy to follow. Firebase was chosen due to the various features it provides such as authentication, realtime databases, storage, hosting and GET/POST API functions. 

**Feasible plan**

Currently, this application’s maintenance cost is free due to the Spark Plan on Firebase. This includes 10GB of hosting data, 50,000 fetches of data / day and 125,000 invocations / month. The 10GB is needed for storage of posts and data, the fetches of data are needed to load other users’ data and the invocations are for the functions users will trigger by uploading data. 

As we gain new users our Firebase plan will switch to a pay as you go plan called Blaze Plan. From various research and calculations, at 10,000 users it will cost roughly $370/month. This cost will cover 500GB of stored and transferred data, 58M invocations, and 500,000 pages of static content.

**Future implementations**

Furthermore, we will transition to React and Postgres as front and back-end systems within the coming weeks. The React framework was not used initially due to the steep learning curve, but as we have more time we will implement a cleaner and organized front-end system through this framework. Postgres will need to be implemented once our app surpasses 10,000 users in order to reduce costs by creating our own database and backend system which does not rely on the Firebase platform. This will be significantly cheaper as we will only need to cover costs of hosting and storage directly without Firebases service fee. React will consume GET/POST API requests to fetch data while Postgres(SQL) will manage internal databases for storing users’ data.


       5 . Tech Implementation- User Experience Design

**Design philosophies**

We wanted to curate a friendly and easily accessible environment for the user. The front page displays the logo and the mission statement of our application with a friendly and welcoming design. The webpage deploys the basic functionalities of a social media application such as the ability to create an account and to log on to the platform. 

Users are allowed to post any types of media ranging from videos, pictures, articles, links to fundraisers, petitions, and other resources. Users can also create and join groups based on sub categories of a certain interest they follow.

To keep the ideology of creating a safe space for those to educate themselves and others and give support to all these groups, the application features the ability to like a post, which will allow the most popular and most credible posts to be seen. A report button was also incorporated to ensure that users have the ability to moderate other users as well as their feed. Another way to add credibility to the information posted on our platform, the badge system was added to allow users to build their reputation as a trusted user. Badges are awarded based on interaction with the app and the community, the number of posts someone makes, the amount of positive feedback someone receives, etc. One last feature is the filter. Users can directly access information and resources about a particular group by filtering out their posts. This allows all information about a single group to be easily found in one channel.

One other neat feature is the ability to link all other social media platforms on a user’s profile so that users can stay more connected. There is also a feature where your feed will show posts that relate to your interests, which in turn expands the user’s knowledge and allows them to explore more about their interests that they would have otherwise not seen. This feature can be turned off so that users have full control of the posts they do and do not want to see.



### Devpost:
https://devpost.com/software/surge-5rno7c



### Created by:

Danielle Dizon, Emma Brain, Saideep Kumar and Brandon Goh