Introduction

The aim of this handbook provide numerous different series of the best and worst practices for software engineers working within our rapidly evolving startup. As our team expands, it is crucial to adopt a standard approach to software development, to make sure that our code remains of the highest quality and that we continue to enhance predictability across our projects. This guide has three primary areas of focus: Task Estimation in Scrum, Code Reviews, and DevOps.

The handbook is organised by providing a brief introduction to each topic, followed by guidelines presented in bullet points along with some diagrams. We have also included links to necessary discussed reference articles for those interested in delving deeper into the subjects. Our aim is to create a user-friendly resource that allows team members to quickly review and grasp the best practices.

Lets take a look at our first topic.

Task Estimation in Scrum

Task estimation in Scrum is a critical part of project management, as it enables teams to allocate resources effectively and set realistic expectations for stakeholders. In the world of Agile and Scrum, accurate task estimation is essential for ensuring the successful delivery of projects on time and within budget. In this article, we will explore good practices and bad practices to avoid, providing a comprehensive look at task estimation in Scrum.

![Benefits of agile scrum](https://www.7pace.com/wp-content/uploads/2022/03/01_Image_Benefits-Agile_system-scaled.jpg)

Good Practices:
1.	Use planning poker to estimate tasks collaboratively: Planning poker is a consensus based estimation technique that involves the entire team in the estimation process. Team members use a deck of cards with numbers representing different levels of effort to estimate a given task. This technique encourages discussion and helps the team reach a shared understanding of the task's level of difficulty.
[Planning Poker: An Effective Estimation Technique](https://www.mountaingoatsoftware.com/agile/planning-poker)
![Take a look at an how its done !](http://www.scrum-tips.com/wp-content/uploads/2016/03/Tasks_ScrumTips.png)

2.	Break down tasks into smaller, more manageable tasks: Larger tasks can be challenging to estimate accurately. By dividing them up into smaller tasks, team members can better understand the goals and requirements therefore providing more precise estimates. This practice also makes it easier to manage and track progress and identify bottlenecks.

3.	Consider using relative estimation such as story points rather than time-based estimates: Relative estimation also known as T-shirt sizing involves comparing tasks to one another based on their complexity, rather than estimating the time required to complete them. This method can be more accurate, as it factors in the team's expertise and allows for greater flexibility when adapting to changes in the project.
[Top 5 Scrum Estimation Techniques](https://www.knowledgehut.com/blog/agile/top-5-scrum-estimation-techniques-find-your-best-fit)
![T-shirt sizing diagram](https://blog.zenhub.com/wp-content/uploads/2022/11/T-ShirtSizingEstimationChart.webp)

4.	Revisit and adjust estimates as needed during the project lifecycle: As the project progresses and new information emerges, it is essential to revisit and adjust estimates accordingly. This practice ensures that the team remains aligned with the project's goals and can adapt to any changes in scope or requirements.

5.	Engage all team members in conversations about estimations: Ensuring every team member participates in the estimation process allows for a wide array of viewpoints and skills to be taken into account. This cooperative method contributes to achieving more precise estimates and a deeper comprehension of the tasks being considered.

6.	Examine historical estimation precision to enhance subsequent estimations: By assessing past successes and shortcomings in estimations, the team can discern trends and derive lessons from errors made. This knowledge can be employed to boost the accuracy of estimations in the future.

Bad Practices to Avoid:
1.	Relying on a single individual for estimations: Depending on one person to estimate tasks can lead to biased or inaccurate estimates. Involving the entire team in the estimation process ensures a more balanced and accurate result.

2.	Estimating without enough information about the task: Attempting to estimate tasks without enough information can lead to overly optimistic or pessimistic projections. It is essential to gather as much information as possible before starting the task estimation process.

3.	Being overly optimistic or pessimistic with estimates: Overly optimistic estimates can lead to missed deadlines and disappointed stakeholders, while overly pessimistic estimates can result in wasted resources and reduced team morale. Team members must strive for a balanced, realistic approach to task estimation.
![Overly optimistic Scrum estimation](https://apmg-international.com/sites/www.apmg-international.com/files/styles/paragraph_media/public/medias/paragraphs/optimism_bias_1_0.png?itok=OyoQmWBt)

4.	Not reviewing or adjusting estimates as new information emerges: Failing to revisit and adjust current estimates as the project continues to progresses can result in misaligned expectations and wasted resources. Regularly review and update estimates to ensure the team remains on track and aligned with the project's goals.



Common Themes:

1. Collaboration: Involving the entire team in the estimation process ensures more accurate and balanced results.

2. Task Decomposition: Breaking down tasks into smaller, more manageable units helps improve estimation accuracy and project management.

3. Relative Estimation: Using methods like story points or T-shirt sizing allows for better flexibility and accuracy in task estimation.

4. Continuous Adjustment: Revisiting and adjusting estimates throughout the project lifecycle is essential for staying aligned with project goals and adapting to changes.

5. Learning from History: Analyzing past estimation successes and shortcomings can help improve future estimation accuracy.




Code Reviews

A code review normally takes place when a software developer completes a task which may have been assigned to them through an agile workspace.  The review will mainly consist of another employee (who has an expert knowledge in that particular area) to review the code and functionality to see if the code will contain any bugs or will it impact any other features within the entire project.

![Code review process](https://www.researchgate.net/profile/Toshiki-Hirao/publication/303097906/figure/fig2/AS:637825489838081@1529080855326/An-Overview-of-Modern-Code-Review-Processes.png)

Good Practices:
1. Duration of review: The duration of reviewing code at one time is very important. It is important to not exceed a certain amount of code as it is not focused enough and may be very easy to overlook something that may hinder the code.
 [Best Practices for Code Review](https://smartbear.com/learn/code-review/best-practices-for-peer-code-review/)
![Best Practices for Code Review](https://static1.smartbear.co/smartbear/media/images/product/collaborator/code-review-best-practices-figure-01.gif)
![Best Practices for Code Review](https://static1.smartbear.co/smartbear/media/images/product/collaborator/code-review-best-practices-figure-02.gif)

2. Positive attitude: When another member of the team is reviewing code, it is essential that when they are providing feedback that they construct it in a positive manner. This ensures that when that member will not feel they are not capable of doing the work assigned to them and will not fear taking on work in the future.


3. Qualifications: To be certain that the code provided is of the highest quality possible, it is necessary that employee reviewing the code has the correct qualifications to review code and will have the strongest understanding of what the code is doing and will be likely to spot potential errors that may occur if code is included into the release.
[Whats the purpose of code reviews?](https://betterprogramming.pub/the-purpose-of-code-review-c9942ee551e2)


Bad Practices to Avoid:
1. Reviewing too much code at time: When reviewing code, it is important not to take too much code to review at a certain time and not to exceed a time limit also.  don’t review over 400 lines at a time.

2. Do not rush a code review: Taking the necessary time to review code and not overlook chunks of code. It would be very easy to glance through code provided and not having a clear understanding of what the code is actually doing.

3. Unconstructive feedback: By the code reviewer not giving clear and constructive feedback, this can lead to a hostile environment within the team and will make employees reluctant to work with one another.

4. Security level: When speaking about security in coding it is a very serious matter. Ensuring the highest level of security is reached is a very important among coding so that data and knowledge of the company is not stolen from hackers.

![Benefits of coding reviews](https://distantjob.com/wp-content/uploads/2021/09/1st-Sep-DJ-Visual-Benefits-of-Code-Reviews.jpg)


Common themes among resources:
1. Identifying bugs: By the code reviewer identifying bugs that have gone unnoticed, this makes the code secure that by when adding a new implementation of code, it will not hamper any previous code written.

2. Code reviewer: Ensuring that the reviewer must be of a senior level and have a high understanding of the code particularly that is being implemented and whether it can successfully be added to the current code.

3. Consistency: It is very important that when a team of coders are working together on a project that the code being implemented is to the same consistency of each other. It is important that code will be efficient and will run smoothly at all stages.

4. Code Quality: By everyone writing the code to the level of what is expected this will result in the outcome of the project that has been undertaken.





Extra Topic - DevOps
DevOps is a set of practices and tools that integrates and automates the work of software development and IT operations to improve and shorten the systems development life cycle in the software development and IT industry. DevOps is primarily aimed at increasing an organization's ability to deliver applications and services quickly, evolving and improving products at a faster pace than those using traditional software development and infrastructure management processes. 

Good practices:
1. Continuous Integration and delivery (CI/CD): This is a DevOps practice that involves automating the process of testing, integrating, and deploying code changes.It startes with frequent code changed being pushed to the repository where they are tested on the testing framework . Once the code passes all tests in the staging environment it is automatically deployed to the production environment giving faster and more reliable software.
![Continuous integration continuous delivery](https://razorops.com/images/blog/Arrow%20Timeline%20Process%20Diagram%20Infographic%20Brainstorm.png)

2. Configuration management: Configuration management is in place to ensure consistency and reliability through the configuration of applications and systems. It makes use of tools like Chef, Puppet and Ansible to help automate this process which makes it much easier for more complex environments. Configuration management is essential as it ensures predictability of the deployment of applications and its infrastructure.

3. Automation: Automation is a core aspect of DevOps that provides massive benefits which includ consistency, speed, and scalability. Automated processes are  reliable which eliminates human errors. Automation is essential for scalability because it allows teams to manage multiple applications and deploy them to various environments without any issues.

4. Agile Management: Agile is a management approach that prioritizes individuals, working software, customer collaboration and response to change. It acknowledges that solutions and requirements will change throughout a project and encourages people to adapt to the changes they need to make. The combination of DevOps and agile means a team can release small pieces of functionality, get customer feedback and and iterate on it which leads to higher quality products and faster deployment.
![Agile Management](https://cdnb.ganttpro.com/uploads/2020/12/Why-Agile.png)



Bad Practices to Avoid:
1. Silos: Maintaining silos between development and operations teams is a hindrance to effective communication and collaboration in software development. Silos can lead to slower delivery processes and increased risk of errors. DevOps addresses this issue by breaking down silos and promoting cross-functional teams. By fostering a culture of shared responsibility and collaboration, DevOps enables effective communication throughout the software development lifecycle, resulting in a more efficient and effective delivery process with fewer errors.

1. Silos: Having silos between development and operations teams can seriously effect communication ad collaboration in the development process. Silos can also lead to slower delivery and increase the risks of errors in the project. DevOps aims to tackle this by breaking down silos and promotes cross functional teams. By promoting collaboration and shared responsibility DevOps pushes effective communication which results in more efficient and effective delivery process with fewer errors.
![Breaking down silos in DevOps](https://d3eeke16mv0lt7.cloudfront.net/sites/default/files/graf2-antipatterns_1.jpg)

2. Lack of testing: Testing and quality assurance are essential in software development to stop the release of software containing bugs. In DevOps, testing is integrated into the development process through continuous testing practices that involve automated testing and continuous integration. When testing is prioritized the risk of defects are a lot lower and which helps improve software stability and functionality which means higher quality products for customers.

3. Poor Communication: Lack of communication and collaboration between teams is a common DevOps bad practice. DevOps is all about breaking down silos and fostering a culture of collaboration to achieve the desired outcomes. Without proper communication, there can be misunderstandings, delays, and other issues that can negatively impact the efficiency and effectiveness of your DevOps processes.

4. Over-Reliance on Tools: Over-reliance on tools is a DevOps bad practice that can lead to a lack of understanding of the underlying processes. While DevOps tools can be helpful, they should not be the sole focus of DevOps. It's important to have a strong understanding of the principles behind DevOps and to use tools to support and enhance the processes, rather than relying on them to do all the work.


Common themes among resources:

Automation: All of the articles emphasize the importance of automation in DevOps, whether it's in the form of continuous integration and delivery (CI/CD), testing, or other processes.

Collaboration: DevOps is about breaking down silos between teams and promoting collaboration between developers and operations. All of the articles touch on this theme  highlighting the importance of communication and teamwork in DevOps.

Best practices: Each of the articles provides insights into best practices for DevOps, whether it's specific techniques for automation, tips for building a DevOps culture, or strategies for integrating testing into the development process.



References:
1.	How to Estimate Tasks in Scrum: A Practical Guide(https://www.cybermedian.com/pl/how-to-scrum-a-practice-guide/)

2.	The Art of Task Estimation in Agile Development (http://www.jamesshore.com/v2/books/aoad1/estimating)

3.	Common Pitfalls in Scrum Task Estimation (https://www.agilequalitymadeeasy.com/post/agile-estimations-common-pitfalls-and-patterns-to-avoid-david-tzemach)

4.	Planning Poker: An Effective Estimation Technique (https://www.mountaingoatsoftware.com/agile/planning-poker)

5.	Top 5 Scrum Estimation Techniques (https://www.knowledgehut.com/blog/agile/top-5-scrum-estimation-techniques-find-your-best-fit)

6.  Devops best practices (https://www.cloudzero.com/blog/devops-best-practices)

7.  Continuous Integration / Continuous Delivery (https://razorops.com/blog/what-is-continuous-integration-and-continuous-delivery/)

8.  Automation in DevOps (https://www.sumologic.com/blog/devops-automation-best-practices-benefits/)

9. Importance of braking down silos:  https://devops.com/devops-the-ultimate-way-to-break-down-silos/

10. Will Devops Kill Testing: https://techbeacon.com/app-dev-testing/will-devops-speed-kill-testing

11. https://about.gitlab.com/topics/version-control/what-is-code-review/#:~:text=Code%20reviews%2C%20also%20known%20as,developers%20learn%20the%20source%20code.

12. https://www.atlassian.com/agile/software-development/code-reviews

13. https://smartbear.com/learn/code-review/best-practices-for-peer-code-review/

14. https://www.pluralsight.com/blog/tutorials/code-review	

