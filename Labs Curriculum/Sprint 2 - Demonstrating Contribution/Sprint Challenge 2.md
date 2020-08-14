# Sprint Challenge: Sprint 2

## Objectives

- Student can articulate their delivery process in contributing to and completing individual tasks.
- Student can demonstrate, in detail, how their solution relates to the specification and architectural standards.
- Student can articulate the challenges and lessons learned from managing their time working on a complex project in a team.

## Prompt 1 - Communicating Individual Contribution

On the job, you will be responsible for shipping features regularly. Engineers are given tickets and are expected to deliver them. Hiring managers want to see that you are capable of delivering a feature.

Here are some examples of hiring manager interview questions:

- "Tell me about a project you've built."
- "What were some technical challenges on that project? How did you overcome them?"

We took these questions and cooked them into your labs experience. This week, you should have shipped at least one feature. Answer the following questions like you would in an interview:

1. Describe what you built this week. Link any relevant pull requests or paste screenshots of code.

This week was a lot of thoughtful problem-solving as a team. We got together and programed our first visual of the data. The visual was a map of the data points we could get that included location information. The data is not ideal for our stake-holder, so we brainstormed multiple ways we might retreve the data location from social media. Our focus is Twitter since that particular media source tends to be a "go-to" for people on the streets experiencing the actual events we are seeking to uncover. Reddits are another option with an accessible API but many of those are actually reposts from Twitter. I soley proved we can get keywords pulled from the twitter API and it can be filtered by location data. However, we also only have a very limited dataset due to lack of location data. 

2. How does what you built contribute to the overall product your team is building? What user problems does it help solve?

Data visualization off of the Twitter API and into a map helped us see what the over work-flow might look like. It also helped us define the issues we are having with Twitter data which is the first step to solving this problem. Getting data into a map is also our MVP goals. Achieving MVP is important to deliver a proof of concept to our team.

3. Describe your delivery process for what you built this week from ideation to breakdown to implementation. What challenges occurred during the delivery process that you didn't foresee?

Getting the data into a visualization whas our main goal this week. As a team we were able to come together on a Zoom call and place various pieces of code we worked on into the plotly-dash and FastAPI. We packaged that visual into JSON and delivered that to the Web team to use. The challenge was working with a new framework such as plotly-dash and FastAPI. The products were intitive and no issues occured but we did have to learn how to use them and this slowed the process slightly. Our team has been testing a lot of code on Google Colab so we can avoid having branch conflicts on Github and still save our own work. This makes communication amongst us very important so we can see what each person is doing and not have redundant tasks. Some redundancy is good, such as all of us working on an ML model, but we don't all have to create our own dataset. We need to be sure and share the parts that are best shared while independently working on the parts that can afford to have several options such as an ML model.


## Prompt 2 - Communicating Teamwork

As a software developer, you will almost always be on a team. As a result, engineering hiring managers want to see how you work on a team. As a junior developer, you will often pair with seniors on features. Here are some examples of interview questions you may get asked concerning teamwork:

- "Tell me about a time you worked on a team. What was hard about it?"
- "What is your greatest weakness as a team player? How have you improved?"

This week we taught you how to pair with other team members. You should have worked with at least one other person to deliver a feature. Reflect on that experience and answer the following questions like you would in an interview:

1. How did you work with another team member to deliver a feature this week? What role did you play?

This week we worked together daily to get data from various sources then find location data and put it into a visual such as a map. I helped push the team to not just do this work in their own notebooks, but to but it in our viz.py folder in git hub and connect it to the scaffolding we have so that we can get that MVP. I had already gotten the map visual running locally so I knew we just needed to update the data and plug it in. I had the team do this together over a Zoom call so we could all see the progress.

2. What did you learn this week from working in a team? How are you going to improve your teamwork in the future?

Working as a team is really important in moving progress forward. Our team has a lot of talent but we all prefer to just work indepdently and pick away at problems. Although this is great for exploring ideas, it can be misfocused in relation to the bigger goals. When we meet daily to discuss the needs to get to our next MVP, it helps us use our skills together and accomplish a lot in a shorter period of time. I think we could improve this by setting a daily time to meet and this would also have an intrinsic "deadline" to show progress to one another.

## Prompt 3 - Professional Development Resume Updates

This week you gained more clarity surrounding your individual contributions and what is happening with your project. Use this clarification, along with your understanding of power statements, to update the projects sections of your resume. When adding a project to your resume, you should include power statement bullets describing the project as if it were a job! Without these bullets you're simply sharing the name of a project (and maybe a tech stack) with little to no clarity on what you did on that project.

To ensure you are creating a robust and ready to use job search resume, use this [resume checklist](https://www.notion.so/lambdaschool/Resume-30f5e6add3324891823192487798cb6d) as a way to organize and add content. If you skipped the resume lesson earlier in the curriculum and are starting from scratch, you'll want to review [this assignment worksheet](https://docs.google.com/document/d/1yAvlgwSPTdXxAbtx3mgfWp6dkNnqtzGGLlRy2yQ7fiA/edit) to establish a resume draft (though the resume checklist will help you establish a draft as well).

### To complete the career portion of this challenge:

1. Updated your resume to include your labs project, with power statements articulating your individual tasks.
2. Upload this resume version to CV compiler for feedback:

    1️⃣ Go to the website [https://cvcompiler.com/students/lambda](https://cvcompiler.com/students/lambda)

    2️⃣ Log in (using LinkedIn or GitHub) -> Fill out the form

    3️⃣ Enter the special promo code [LSalumni, ANDresumes, iOSresumes, DSresumes, WEBresumes, UXresumes] during checkout

    4️⃣ Upload your resume and start working on improving it with CV Compiler

3. After making the recommended CV Compiler edits, submit a final resume draft to your TL.

4. Update your LinkedIn to include any new content you made for your resume. The experience bullets you created for your resume and projects are great examples of content you should consider bringing over to your profile.

## [Sprint Challenge Rubric](https://www.notion.so/1f9fa8ec9c4b4453a3fb21b60cc5352c)

## Additional Resources

- [How to Respond to Interview Questions About Teamwork](https://www.thebalancecareers.com/how-to-respond-to-interview-questions-about-teamwork-2061100)
