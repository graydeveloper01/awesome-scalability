[![Logo](/logo.png)](http://awesome-scalability.com/)

An updated and organized reading list for illustrating the patterns of scalable, reliable, and performant large-scale systems. Concepts are explained in the articles of prominent engineers and credible references. Case studies are taken from battle-tested systems that serve millions to billions of users.

#### If your system goes slow
> Understand your problems: scalability problem (fast for a single user but slow under heavy load) or performance problem (slow for a single user) by reviewing some [design principles](#principle) and checking how [scalability](#scalability) and [performance](#performance) problems are solved at tech companies. The section of [intelligence](#intelligence) are created for those who work with data and machine learning at big (data) and deep (learning) scale.

#### If your system goes down
> "Even if you lose all one day, you can build all over again if you retain your calm!" - Thuan Pham, former CTO of Uber. So, keep calm and mind the [availability](#availability) and [stability](#stability) matters! 

#### If you are having a system design interview
> Look at some [interview notes](#interview) and [real-world architectures with completed diagrams](#architecture) to get a comprehensive view before designing your system on whiteboard. You can check some [talks](#talk) of engineers from tech giants to know how they build, scale, and optimize their systems. There are some selected [books](#book) for you (most of them are free)! Good luck!

#### If you are building your dream team
> The goal of scaling team is not growing team size but increasing team output and value. You can find out how tech companies reach that goal in various aspects: hiring, management, organization, culture, and communication in the [organization](#organization) section.

#### Community power

> Contributions are greatly welcome! You may want to take a look at the [contribution guidelines](CONTRIBUTING.md). If you see a link here that is no longer maintained or is not a good fit, please submit a pull request!

> Many long hours of hard work have gone into this project. If you find it helpful, please share on Facebook, [on Twitter](https://ctt.ec/V8B2p), [on Weibo](http://t.cn/RnjFLCB), or on your chat groups! Knowledge is power, knowledge shared is power multiplied. Thank you!

## Content
- [Principle](#principle)
- [Scalability](#scalability)
- [Availability](#availability)
- [Stability](#stability)
- [Performance](#performance)
- [Intelligence](#intelligence)
- [Architecture](#architecture)
- [Interview](#interview)
- [Organization](#organization)
- [Talk](#talk)
- [Book](#book)

## Architecture
* [Systems We Make](https://systemswemake.com/)
* [Tech Stack (2 parts) at Uber](https://eng.uber.com/tech-stack-part-two/)
* [Tech Stack at Medium](https://medium.engineering/the-stack-that-helped-medium-drive-2-6-millennia-of-reading-time-e56801f7c492)
* [Tech Stack at Shopify](https://engineering.shopify.com/blogs/engineering/e-commerce-at-scale-inside-shopifys-tech-stack)
* [Building Services (4 parts) at Airbnb](https://medium.com/airbnb-engineering/building-services-at-airbnb-part-4-23c95e428064)
* [Architecture of Evernote](https://evernote.com/blog/a-digest-of-evernotes-architecture/)
* [Architecture of Chat Service (3 parts) at Riot Games](https://engineering.riotgames.com/news/chat-service-architecture-persistence)
* [Architecture of League of Legends Client Update](https://technology.riotgames.com/news/architecture-league-client-update)
* [Architecture of Ad Platform at Twitter](https://blog.twitter.com/engineering/en_us/topics/infrastructure/2020/building-twitters-ad-platform-architecture-for-the-future.html)
* [Basic Architecture of Slack](https://slack.engineering/how-slack-built-shared-channels-8d42c895b19f)
* [Back-end at LinkedIn](https://engineering.linkedin.com/architecture/brief-history-scaling-linkedin)
* [Back-end at Flickr](https://yahooeng.tumblr.com/post/157200523046/introducing-tripod-flickrs-backend-refactored)
* [Infrastructure (3 parts) at Zendesk](https://medium.com/zendesk-engineering/the-history-of-infrastructure-at-zendesk-part-3-foundation-team-forming-and-evolving-9859e40f5390)
* [Cloud Infrastructure at Grubhub](https://bytes.grubhub.com/cloud-infrastructure-at-grubhub-94db998a898a)
* [Real-time Presence Platform at LinkedIn](https://engineering.linkedin.com/blog/2018/01/now-you-see-me--now-you-dont--linkedins-real-time-presence-platf)
* [Settings Platform at LinkedIn](https://engineering.linkedin.com/blog/2019/05/building-member-trust-through-a-centralized-and-scalable-setting)
* [Nearline System for Scale and Performance (2 parts) at Glassdoor](https://medium.com/glassdoor-engineering/building-a-nearline-system-for-scale-and-performance-part-ii-9e01bf51b23d)
* [Real-time User Action Counting System for Ads at Pinterest](https://medium.com/@Pinterest_Engineering/building-a-real-time-user-action-counting-system-for-ads-88a60d9c9a)
* [API Platform at Riot Games](https://engineering.riotgames.com/news/riot-games-api-deep-dive)
* [Games Platform at The New York Times](https://open.nytimes.com/play-by-play-moving-the-nyt-games-platform-to-gcp-with-zero-downtime-cf425898d569)
* [Kabootar: Communication Platform at Swiggy](https://bytes.swiggy.com/kabootar-swiggys-communication-platform-e5a43cc25629)
* [Simone: Distributed Simulation Service at Netflix](https://medium.com/netflix-techblog/https-medium-com-netflix-techblog-simone-a-distributed-simulation-service-b2c85131ca1b)
* [Seagull: Distributed System that Helps Running > 20 Million Tests Per Day at Yelp](https://engineeringblog.yelp.com/2017/04/how-yelp-runs-millions-of-tests-every-day.html)
* [PriceAggregator: Intelligent System for Hotel Price Fetching (3 parts) at Agoda](https://medium.com/agoda-engineering/priceaggregator-an-intelligent-system-for-hotel-price-fetching-part-3-52acfc705081)
* [Phoenix: Testing Platform (3 parts) at Tinder](https://medium.com/tinder-engineering/phoenix-tinders-testing-platform-part-iii-520728b9537)
* [Hexagonal Architecture at Netflix](https://netflixtechblog.com/ready-for-changes-with-hexagonal-architecture-b315ec967749)
* [Architecture of Play API Service at Netflix](https://qconsf.com/system/files/presentation-slides/qcon_netflix_play_api.pdf)
* [Architecture of Sticker Services at LINE](https://www.slideshare.net/linecorp/architecture-sustaining-line-sticker-services)
* [Stack Overflow Enterprise at Palantir](https://medium.com/@palantir/terraforming-stack-overflow-enterprise-in-aws-47ee431e6be7)
* [Architecture of Following Feed, Interest Feed, and Picked For You at Pinterest](https://medium.com/@Pinterest_Engineering/building-a-dynamic-and-responsive-pinterest-7d410e99f0a9)
* [API Specification Workflow at WeWork](https://engineering.wework.com/our-api-specification-workflow-9337448d6ee6)
* [Media Database at Netflix](https://medium.com/netflix-techblog/implementing-the-netflix-media-database-53b5a840b42a)
* [Member Transaction History Architecture at Walmart](https://medium.com/walmartlabs/member-transaction-history-architecture-8b6e34b87c21)
* [Sync Engine (2 parts) at Dropbox](https://dropbox.tech/infrastructure/-testing-our-new-sync-engine)
* [Architectures of Finance and Banking Systems](https://www.sesameindia.com/images/core-banking-system-architecture)
	* [Bank Backend at Monzo](https://monzo.com/blog/2016/09/19/building-a-modern-bank-backend/)
	* [Trading Platform for Scale at Wealthsimple](https://medium.com/@Wealthsimple/engineering-at-wealthsimple-reinventing-our-trading-platform-for-scale-17e332241b6c)
	* [Core Banking System at Margo Bank](https://medium.com/margobank/choosing-an-architecture-85750e1e5a03)
	* [Architecture of Nubank](https://www.infoq.com/presentations/nubank-architecture)
	* [Tech Stack at TransferWise](http://tech.transferwise.com/the-transferwise-stack-heartbeat-of-our-little-revolution/)
	* [Tech Stack at Addepar](https://medium.com/build-addepar/our-tech-stack-a4f55dab4b0d)
	* [Avoiding Double Payments in a Distributed Payments System at Airbnb](https://medium.com/airbnb-engineering/avoiding-double-payments-in-a-distributed-payments-system-2981f6b070bb)

## Interview
* :white_check_mark:[Designing Large-Scale Systems](https://www.somethingsimilar.com/2013/01/14/notes-on-distributed-systems-for-young-bloods/)
	* :white_check_mark:[My Scaling Hero - Jeff Atwood (a dose of Endorphins before your interview, JK)](https://blog.codinghorror.com/my-scaling-hero/)
	* [Software Engineering Advice from Building Large-Scale Distributed Systems - Jeff Dean](https://static.googleusercontent.com/media/research.google.com/en//people/jeff/stanford-295-talk.pdf)
	* :white_check_mark:[Introduction to Architecting Systems for Scale](https://lethain.com/introduction-to-architecting-systems-for-scale/)
	* [Anatomy of a System Design Interview](https://hackernoon.com/anatomy-of-a-system-design-interview-4cb57d75a53f)
	* [8 Things You Need to Know Before a System Design Interview](http://blog.gainlo.co/index.php/2015/10/22/8-things-you-need-to-know-before-system-design-interviews/)
	* [Top 10 System Design Interview Questions ](https://hackernoon.com/top-10-system-design-interview-questions-for-software-engineers-8561290f0444)
	* [Top 10 Common Large-Scale Software Architectural Patterns in a Nutshell](https://towardsdatascience.com/10-common-software-architectural-patterns-in-a-nutshell-a0b47a1e9013)
	* [Cloud Big Data Design Patterns - Lynn Langit](https://lynnlangit.com/2017/03/14/beyond-relational/)	
	* [How NOT to design Netflix in your 45-minute System Design Interview?](https://hackernoon.com/how-not-to-design-netflix-in-your-45-minute-system-design-interview-64953391a054)
	* [API Best Practices: Webhooks, Deprecation, and Design](https://zapier.com/engineering/api-best-practices/)
* [Explaining Low-Level Systems (OS, Network/Protocol, Database, Storage)](https://www.palantir.com/how-to-ace-a-systems-design-interview/)	
	* [OSI and TCP/IP Cheat Sheet](http://jaredheinrichs.com/mastering-the-osi-tcpip-models.html)
	* [The Precise Meaning of I/O Wait Time in Linux](http://veithen.github.io/2013/11/18/iowait-linux.html)
	* [Paxos Made Live – An Engineering Perspective](https://research.google.com/archive/paxos_made_live.html)
	* [How to do Distributed Locking](https://martin.kleppmann.com/2016/02/08/how-to-do-distributed-locking.html)
	* [SQL Transaction Isolation Levels Explained](http://elliot.land/post/sql-transaction-isolation-levels-explained)
* ["What Happens When... and How" Questions](https://www.glassdoor.com/Interview/What-happens-when-you-type-www-google-com-in-your-browser-QTN_56396.htm)
	* [Netflix: What Happens When You Press Play?](http://highscalability.com/blog/2017/12/11/netflix-what-happens-when-you-press-play.html)
	* [Monzo: How Peer-To-Peer Payments Work](https://monzo.com/blog/2018/04/05/how-monzo-to-monzo-payments-work/)
	* [Transit and Peering: How Your Requests Reach GitHub](https://githubengineering.com/transit-and-peering-how-your-requests-reach-github/)
	* [How Spotify Streams Music](https://labs.spotify.com/2018/08/31/smoother-streaming-with-bbr/)

## Organization
* [Engineering Levels at SoundCloud](https://developers.soundcloud.com/blog/engineering-levels)
* [Engineering Roles at Palantir](https://medium.com/palantir/dev-versus-delta-demystifying-engineering-roles-at-palantir-ad44c2a6e87)
* [Scaling Engineering Teams at Twitter](https://www.youtube.com/watch?v=-PXi_7Ld5kU)
* [Scaling Decision-Making Across Teams at LinkedIn](https://engineering.linkedin.com/blog/2018/03/scaling-decision-making-across-teams-within-linkedin-engineering)
* [Scaling Data Science Team at GOJEK](https://blog.gojekengineering.com/the-dynamics-of-scaling-an-organisation-cb96dbe8aecd)
* [Scaling Agile at Zalando](https://jobs.zalando.com/tech/blog/scaling-agile-zalando/?gh_src=4n3gxh1)
* [Scaling Agile at bol.com](https://hackernoon.com/how-we-run-bol-com-with-60-autonomous-teams-fe7a98c0759)
* [Lessons Learned from Scaling a Product Team at Intercom](https://blog.intercom.com/how-we-build-software/)
* [Hiring, Managing, and Scaling Engineering Teams at Typeform](https://medium.com/@eleonorazucconi/toby-oliver-cto-typeform-on-hiring-managing-and-scaling-engineering-teams-86bef9e5a708)	
* [Scaling the Datagram Team at Instagram](https://instagram-engineering.com/scaling-the-datagram-team-fc67bcf9b721)
* [Scaling the Design Team at Flexport](https://medium.com/flexport-design/designing-a-design-team-a9a066bc48a5)
* [Team Model for Scaling a Design System at Salesforce](https://medium.com/salesforce-ux/the-salesforce-team-model-for-scaling-a-design-system-d89c2a2d404b)
* [Building Analytics Team (4 parts) at Wish](https://medium.com/wish-engineering/scaling-the-analytics-team-at-wish-part-4-recruiting-2a9823b9f5a)
* [From 2 Founders to 1000 Employees at Transferwise](https://medium.com/transferwise-ideas/from-2-founders-to-1000-employees-how-a-small-scale-startup-grew-into-a-global-community-9f26371a551b)
* [Lessons Learned Growing a UX Team from 10 to 170 at Adobe](https://medium.com/thinking-design/lessons-learned-growing-a-ux-team-from-10-to-170-f7b47be02262)
* [Five Lessons from Scaling at Pinterest](https://medium.com/@sarahtavel/five-lessons-from-scaling-pinterest-6a699a889b08)
* [Approach Engineering at Vinted](http://engineering.vinted.com/2018/09/04/how-we-approach-engineering-at-vinted/)
* [Using Metrics to Improve the Development Process (and Coach People) at Indeed](https://engineering.indeedblog.com/blog/2018/10/using-metrics-to-improve-the-development-process-and-coach-people/)
* [Mistakes to Avoid while Creating an Internal Product at Skyscanner](https://medium.com/@SkyscannerEng/9-mistakes-to-avoid-while-creating-an-internal-product-63d579b00b1a)
* [RACI (Responsible, Accountable, Consulted, Informed) at Etsy](https://codeascraft.com/2018/01/04/selecting-a-cloud-provider/)
* [Four Pillars of Leading People (Empathy, Inspiration, Trust, Honesty) at Zalando](https://jobs.zalando.com/tech/blog/four-pillars-leadership/)
* [Pair Programming at Shopify](https://engineering.shopify.com/blogs/engineering/pair-programming-explained)
* [Distributed Responsibility at Asana](https://blog.asana.com/2017/12/distributed-responsibility-engineering-manager/)
* [Rotating Engineers at Zalando](https://jobs.zalando.com/tech/blog/rotating-engineers-at-zalando/)
* [Experiment Idea Review at Pinterest](https://medium.com/pinterest-engineering/how-pinterest-supercharged-its-growth-team-with-experiment-idea-review-fd6571a02fb8)
* [Tech Migrations at Spotify](https://engineering.atspotify.com/2020/06/25/tech-migrations-the-spotify-way/)
* [Improving Code Ownership at Yelp](https://engineeringblog.yelp.com/2021/01/whose-code-is-it-anyway.html)
* [Agile Code Base at eBay](https://tech.ebayinc.com/engineering/how-creating-an-agile-code-base-helped-ebay-pivot-for-apple-silicon/)
* [Code Review](https://ai.google/research/pubs/pub47025)
	* [Code Review at Palantir](https://medium.com/@palantir/code-review-best-practices-19e02780015f)
	* [Code Review at LINE](https://engineering.linecorp.com/en/blog/effective-code-review/)
	* [Code Reviews at Medium](https://medium.engineering/code-reviews-at-medium-bed2c0dce13a)
	* [Code Review at LinkedIn](https://engineering.linkedin.com/blog/2018/06/scaling-collective-code-ownership-with-code-reviews)
	* [Code Review at Disney](https://medium.com/disney-streaming/the-secret-to-better-code-reviews-c14c7884b9ac)
	* [Code Review at Netlify](https://www.netlify.com/blog/2020/03/05/feedback-ladders-how-we-encode-code-reviews-at-netlify/)

## Talk
* :white_check_mark:[Distributed Systems in One Lesson - Tim Berglund, Senior Director of Developer Experience at Confluent](https://www.youtube.com/watch?v=Y6Ev8GIlbxc)
* [Building Real Time Infrastructure at Facebook - Jeff Barber and Shie Erlich, Software Engineer at Facebook](https://www.usenix.org/conference/srecon17americas/program/presentation/erlich)
* [Building Reliable Social Infrastructure for Google - Marc Alvidrez, Senior Manager at Google](https://www.usenix.org/conference/srecon16/program/presentation/alvidrez)
* [Building a Distributed Build System at Google Scale - Aysylu Greenberg, SDE at Google](https://www.youtube.com/watch?v=K8YuavUy6Qc)
* [Site Reliability Engineering at Dropbox - Tammy Butow, Site Reliability Engineering Manager at Dropbox](https://www.youtube.com/watch?v=ggizCjUCCqE)
* [How Google Does Planet-Scale for Planet-Scale Infra - Melissa Binde, SRE Director for Google Cloud Platform](https://www.youtube.com/watch?v=H4vMcD7zKM0)
* [Netflix Guide to Microservices - Josh Evans, Director of Operations Engineering at Netflix](https://www.youtube.com/watch?v=CZ3wIuvmHeM&t=2837s)
* [Achieving Rapid Response Times in Large Online Services - Jeff Dean, Google Senior Fellow](https://www.youtube.com/watch?v=1-3Ahy7Fxsc)
* [Architecture to Handle 80K RPS Celebrity Sales at Shopify - Simon Eskildsen, Engineering Lead at Shopify](https://www.youtube.com/watch?v=N8NWDHgWA28)
* [Lessons of Scale at Facebook - Bobby Johnson, Director of Engineering at Facebook](https://www.youtube.com/watch?v=QCHiNEw73AU)
* [Performance Optimization for the Greater China Region at Salesforce - Jeff Cheng, Enterprise Architect at Salesforce](https://www.salesforce.com/video/1757880/)
* [How GIPHY Delivers a GIF to 300 Millions Users - Alex Hoang and Nima Khoshini, Services Engineers at GIPHY](https://vimeo.com/252367076)
* [High Performance Packet Processing Platform at Alibaba - Haiyong Wang, Senior Director at Alibaba](https://www.youtube.com/watch?v=wzsxJqeVIhY&list=PLMu8-hpCxIVENuAue7bd0eCAglLGY_8AW&index=7)
* [Solving Large-scale Data Center and Cloud Interconnection Problems -  Ihab Tarazi, CTO at Equinix](https://atscaleconference.com/videos/solving-large-scale-data-center-and-cloud-interconnection-problems/)
* [Scaling Dropbox - Kevin Modzelewski, Back-end Engineer at Dropbox](https://www.youtube.com/watch?v=PE4gwstWhmc)
* [Scaling Reliability at Dropbox - Sat Kriya Khalsa, SRE at Dropbox](https://www.youtube.com/watch?v=IhGWOaD5BYQ)
* [Scaling with Performance at Facebook - Bill Jia, VP of Infrastructure at Facebook](https://atscaleconference.com/videos/performance-scale-2018-opening-remarks/)
* [Scaling Live Videos to a Billion Users at Facebook - Sachin Kulkarni, Director of Engineering at Facebook](https://www.youtube.com/watch?v=IO4teCbHvZw)
* [Scaling Infrastructure at Instagram - Lisa Guo, Instagram Engineering](https://www.youtube.com/watch?v=hnpzNAPiC0E)
* [Scaling Infrastructure at Twitter - Yao Yue, Staff Software Engineer at Twitter](https://www.youtube.com/watch?v=6OvrFkLSoZ0)
* [Scaling Infrastructure at Etsy - Bethany Macri, Engineering Manager at Etsy](https://www.youtube.com/watch?v=LfqyhM1LeIU)
* [Scaling Real-time Infrastructure at Alibaba for Global Shopping Holiday - Xiaowei Jiang, Senior Director at Alibaba](https://atscaleconference.com/videos/scaling-alibabas-real-time-infrastructure-for-global-shopping-holiday/)
* [Scaling Data Infrastructure at Spotify - Matti (Lepistö) Pehrs, Spotify](https://www.youtube.com/watch?v=cdsfRXr9pJU)
* [Scaling Pinterest - Marty Weiner, Pinterest’s founding engineer](https://www.youtube.com/watch?v=jQNCuD_hxdQ&list=RDhnpzNAPiC0E&index=11)
* [Scaling Slack - Bing Wei, Software Engineer (Infrastructure) at Slack](https://www.infoq.com/presentations/slack-scalability)
* [Scaling Backend at Youtube - Sugu Sougoumarane, SDE at Youtube](https://www.youtube.com/watch?v=5yDO-tmIoXY&feature=youtu.be)
* [Scaling Backend at Uber - Matt Ranney, Chief Systems Architect at Uber](https://www.youtube.com/watch?v=nuiLcWE8sPA)
* [Scaling Global CDN at Netflix - Dave Temkin, Director of Global Networks at Netflix](https://www.youtube.com/watch?v=tbqcsHg-Q_o)
* [Scaling Load Balancing Infra to Support 1.3 Billion Users at Facebook - Patrick Shuff, Production Engineer at Facebook](https://www.youtube.com/watch?v=bxhYNfFeVF4)
* [Scaling (a NSFW site) to 200 Million Views A Day And Beyond - Eric Pickup, Lead Platform Developer at MindGeek](https://www.youtube.com/watch?v=RlkCdM_f3p4)
* [Scaling Counting Infrastructure at Quora - Chun-Ho Hung and Nikhil Gar, SEs at Quora](https://www.infoq.com/presentations/quora-analytics)
* [Scaling Git at Microsoft - Saeed Noursalehi, Principal Program Manager at Microsoft](https://www.youtube.com/watch?v=g_MPGU_m01s)
* [Scaling Multitenant Architecture Across Multiple Data Centres at Shopify - Weingarten, Engineering Lead at Shopify](https://www.youtube.com/watch?v=F-f0-k46WVk)

## Book
* [Big Data, Web Ops & DevOps Ebooks - O'Reilly (Online - Free)](http://www.oreilly.com/webops/free/)
* [Google Site Reliability Engineering (Online - Free)](https://landing.google.com/sre/book.html)
* [Distributed Systems for Fun and Profit (Online - Free)](http://book.mixu.net/distsys/)
* [What Every Developer Should Know About SQL Performance (Online - Free)](https://use-the-index-luke.com/sql/table-of-contents)
* [Beyond the Twelve-Factor App - Exploring the DNA of Highly Scalable, Resilient Cloud Applications (Free)](http://www.oreilly.com/webops-perf/free/beyond-the-twelve-factor-app.csp)
* [Chaos Engineering - Building Confidence in System Behavior through Experiments (Free)](http://www.oreilly.com/webops-perf/free/chaos-engineering.csp?intcmp=il-webops-free-product-na_new_site_chaos_engineering_text_cta)
* [The Art of Scalability](http://theartofscalability.com/)
* [Web Scalability for Startup Engineers](https://www.goodreads.com/book/show/23615147-web-scalability-for-startup-engineers)
* [Scalability Rules: 50 Principles for Scaling Web Sites](http://scalabilityrules.com/)

## Donation
Roses are red. Violets are blue. [Binh](https://nguyenquocbinh.org/) likes sweet. [Treat Binh a tiramisu?](https://paypal.me/binhnguyennus) :cake:
