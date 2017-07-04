# Experimentation with Tableau

Experimenting with Tableau and doing data visualuzation with help of node.js. Tableau helps the world’s largest organizations unleash the power of their most valuable assets: their data and their people.

## Concepts

In 2020 the world will generate 50 times the amount of data as in 2011. And 75 times the number of information sources (IDC, 2011). Being able to use this data provides huge opportunities and to turn these opportunities into reality, people need to use data to solve problems.

This Specialization, in collaboration with Tableau, is intended for newcomers to data visualization with no prior experience using Tableau. We leverage Tableau's library of resources to demonstrate best practices for data visualization and data storytelling. You will view examples from real world business cases and journalistic examples from leading media companies.

By the end of this specialization, you will be able to generate powerful reports and dashboards that will help people make decisions and take action based on their business data. You will use Tableau to create high-impact visualizations of common data analyses to help you see and understand your data. You will apply predicative analytics to improve business decision making. The Specialization culminates in a Capstone Project in which you will use sample data to create visualizations, dashboards, and data models to prepare a presentation to the executive leadership of a fictional company.

### Currently Implemented
* app.js file as a point of startup and configuration, but not routing. [link](https://github.com/EAAppFoundry/tableau/blob/master/app.js)
* routes living in a dedicated route.js file. [link](https://github.com/EAAppFoundry/tableau/blob/master/routes.js)
* dealing with configuration for multiple environments. [link](https://github.com/EAAppFoundry/tableau/blob/master/config/config.js)
* encapsulating controller code into separate, dedicated js files. [link](https://github.com/EAAppFoundry/tableau/blob/master/controllers/site.js)

##### A note about models
We purposely did not implement any models in this example.  The answer for 'how do I properly implement my models' is 'it depends'.  While this example is biased toward MongoDB, it doesn't choose to specify an ODM.  For an example of using the mongo driver, check out [HiProfile](https://bitbucket.org/EATurner/hiprofile).  For a Mongoose example, take a look at [Flow](https://bitbucket.org/EATurner/flow).

### TBD
* make the .jade views a bit richer and more relevant.
* handle session data
* illustrate dealing with authentication
* anything else?

## We miss something?
I'm sure we did.  We would love feedback, or better yet, pull requests.  
