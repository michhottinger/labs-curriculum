# Module Inquiry 2

## Questions

1. What technical choices did you make today? 

Today I decided that my first pass solution needs to be simple. I'm going to get the data from the Twitter API, put it into a relational database, and then use that data to create the map we need with plotly dash. This should be a quick easy way to give something to the web team to work with. Next,we will need to refine details such as how often we update the twitter data (daily? hourly?) and how to deal with words outside of our cached list.

2. Pick two technical choices you're happy with. What was your thought process as you made those choices? What did you consider and what did you decide against?

I like that we are limiting our scope to get a solid first pass solution. Once we get this first pass solution, it will be easier to see where we need to grow. 
I also saw that we need to create a docker image to create an envirinment across our team. This is something I think we can all create together.
    - Take a moment to think about the advantages in choosing the route that you did.
    
    The advantage of a simple first pass solution is that I know where to start and I can make progress towards the solution even if its the minimal version of the product. This will also allow the web team to envision their solution quickly.
    - Now take a moment to consider the disadvantages.
    
    The disadvantages is that it may create more complications down the line if my firt pass solution is done with too narrow of a scope and I need to redo code so that I can encompass a larger scope.
    
3. In one or two sentences, summarize why you ultimately made the choice you did.

I want to get familiar with the data as qickly as possible so that I can rule out any obstacles that may prevent me from delivering the results I promised to deliver. With this project, I want to be sure I have location information and key word searches that can be graphed. Once I have proven that part is obtainable, the rest of the details can fall into place and be revised as needed.

4. Extracting useful conclusions from your process: 
    - According to your understanding, what makes a good technical choice?
    
    A good technical choice is one that enables the project to move forward with a good proof of concept while requiring little or no technical dept.
