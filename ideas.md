# CAMS
Culture
Autmation
Measurement
Sharing


KISS
- simple
- répétable
- ré-étulisabble

Augmente la vitesse de communication,
Diminue les confusions, les risques, les erreurs

Relationships

Engage early, engage often




Developers also bring skills, knowledge and tools that can help make your environment easier to manage, more efficient and cleaner.
Learn to code or if you’re a hack-n-slash systems programmer like me then learn to code better.
Concepts like building tools with APIs rather than closed interfaces, distributed version control, test driven development, and methodologies like Agile Development, Kanban and Scrum can revolutionise operational practises in the same way they’ve changed the way code is cut.

Process

Don’t underestimate the power of process and automation.

Link process together across domains – software deployment, monitoring, capacity planning and other “operational” processes have their start in the development world. 
Software deployment is the logical conclusion of the software development life cycle and should be viewed as such rather than a separate operational process.
Another example is metrics and monitoring, it is hard to measure anything  without understanding the baselines and assumptions made in the development domain.  
Joint processes also mean more opportunity for development and operations interaction, understanding and joint accountability. Finally, joint process development means single repositories for documentation and other opportunities for economies of scale.

Automate, automate, automate.
Build or make use of simple and extensible tools (make sure they have APIs and machine readable input and output – see James White’s Infrastructure Manifesto).  Use tools like Puppet (or others) to manage your configuration.  Remember to extend your automation umbrella cross-domain and end-to-end in your environment – manage development, testing, staging and production environments with the same tools and processes.  Not only does this have economies of scale benefits in support and management but it means you can test deployment and management alongside functionality as your application and new codes rolls toward production.

Finally, when building process and automation always keep the KISS principle in mind. Complexity breeds opportunities for error. Build simple processes and tools that are easy to implement, manage and maintain.

Continuous Improvement

Don’t stop innovating and learning.  Technology moves fast.  So do customer requirements. Build continuous improvement and integration into your tools and processes.  Here is a good place operations people can learn from (good) developers about practises like test-driven development.  A good example here is to build tests for your software deployment process and infrastructure.  They are often an application in their own right and should be developed and maintained correctly. Your monitoring could also be extended with behavioural testing to deliver better business value.  Look at using development domain tools, like Hudson for example, to explore and measure the operational domain.

Learn from mistakes and from outages.  Seek root cause aggressively AND cross-domain.  If you have an outage and a post-incident review then bring development and operational teams together to review the incident.  Sometimes some simple code refactoring can save making infrastructure changes.  Work together to fix root cause, treat it with the same process you develop to conduct project to production software deployment, rather than relegating them to incident review reports or batting issues between teams.

tools : configuration management, deployment, monitoring, securaity, testing, DVCS, agile continuous deployment, 

Lean / devops


    * The enabler: just as the electric motor enabled automation within manufacturing, virtualization and in it&#39;s extend cloud has made many more things possible
    * Reducing waste: similar to the focus of the engineers in manufacturing, people are trying to improve cycle time by eliminating waste. F.i. cucumber-nagios reduces the waste of rewriting monitoring scripts when you already have testing scripts. Config Management tools like chef or puppet reduce the setup time of a machine again decreasing cycle-time.
    * Avoid Batches: by using continuous deployment in small steps, people avoid both large inventory of features and better understanding of when things fails because they do it in small steps.
    * Poka Yoke/FailProof: using Continuous Integration with test, they create a harness to make sure things don&#39;t fail. Some companies are getting so confident that they let new employees deploy their own code, because they trust their failproofing of the system.
    * Takt Time: the ability to produce at the requested speed of the customer. Sysadmins make sure that the last mile to the customers keeps on working and even though they don&#39;t develop software, they still add value to the process. Also the fact that scaling can happen
    * Andon/Stop the line: It requires the complete attention of everybody to fix it, as the cycle time is broken. Teams performing Continuous Integration already have this habit for the build status. It should always be fixed first. Similar sysadmins that have monitoring software that goes red, assign it the highest priority. To take it even further both should be focused to fix each other&#39;s problems if one of these go wrong.
    * Kanban: the equivalent has been introduced in Software development by David Anderson, to visualize the process and work out the required buffers, waste and other things to improve in your process. It is described in more detail here by Stephen Nelson-Smith
    * Measuring cycle time: a lot of companies are actively providing metrics of their # of deploys, errors they have (or tickets). While they improve things they can measure their progress. If you don&#39;t measure things you don&#39;t know what&#39;s happening.
    * Zero defect: it doesn&#39;t matter if its a functional defect or things like security and performance. Things need to be fixed as early as possible in the process
    * Listen to the people on the floor: Lean instructs management to listen to people that do the job and encourages them to watch and learn first. They are not better then anyone else and t
    * Understanding the tools you use: it might be a biased observation, but Open Source allows you better to inspect problems and potentially fix them. It&#39;s one of it&#39;s strengths of using it.
    * Single piece flow: Single piece flow is the ideal state where parts are manufactured one at a time, and flow throughout the manufacturing and supply chain as single unit, transferred as customer’s order. You could the fact that people push out single feature out all of the time as a kind of single piece flow.


