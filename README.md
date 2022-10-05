# The concept of protected javascript (pro-script)
## The main issue of javascript

The javascript has lots of advantages and the flexibility is most important. But the flexibility gives and the disadvantages. The Important of them is the code ambiguity. Often the javascript code has an unexpected behaviour. The types checking can fix this problem. But the type checking is removing a flexibility.  Strict types and the flexibility is opposite to each other. When you use strict type you lose flexibility. When you are developing the flexible code you can't use strict types in all places. The Second disadvantage of strict typing it is a more time for development. In other hand to maintain code without type checking is hard and expensive.

## The principle of readable code
Making code understandable to computers is easier than making code understandable to humans.
Readable code is code that clearly communicates its intent to the reader. While it’s easier said than done and often a challenge for inexperienced developers, creating readable code is as important as solving any software problem—this is why it’s often one of the first techniques a developer learns on the job. Code readability has two key requirements: The first is that the code must produce the expected result, and the second is that the code should be easy for other developers to read. Messy code is like a messy coffee cup; if it’s not clean, others won’t choose to clean it themselves simply so they’re able to use it!

### Your code should tell a story.
```javascript
    I.want.to.tell.you.a.story(myStory)
```

## The history of One percent Improvement

The fate of British Cycling changed one day in 2003.

The organization, which was the governing body for professional cycling in Great Britain, had recently hired Dave Brailsford as its new performance director. At the time, professional cyclists in Great Britain had endured nearly one hundred years of mediocrity. Since 1908, British riders had won just a single gold medal at the Olympic Games, and they had fared even worse in cycling’s biggest race, the Tour de France. In 110 years, no British cyclist had ever won the event.

In fact, the performance of British riders had been so underwhelming that one of the top bike manufacturers in Europe refused to sell bikes to the team because they were afraid that it would hurt sales if other professionals saw the Brits using their gear.

Brailsford had been hired to put British Cycling on a new trajectory. What made him different from previous coaches was his relentless commitment to a strategy that he referred to as “the aggregation of marginal gains,” which was the philosophy of searching for a tiny margin of improvement in everything you do. Brailsford said, “The whole principle came from the idea that if you broke down everything you could think of that goes into riding a bike, and then improve it by 1 percent, you will get a significant increase when you put them all together.”

During the ten-year span from 2007 to 2017, British cyclists won 178 world championships and 66 Olympic or Paralympic gold medals and captured 5 Tour de France victories in what is widely regarded as the most successful run in cycling history.

## Startup Life Cycle

There are three startup stages: early-stage, venture-funded (growth) stage and late stage. 

### The early-stage
An early-stage startup begins with a scalable idea that attracts funding. At this stage, the startup team must make their solution as cost-effective as possible, very quickly, and then show it to potential sponsors or enter the market. If you use type checking at this point, you're wasting money that you can spend on additional features.

### The venture-funded (growth) stage
Series A funding enables you to build out your team and infrastructure.
You’re in this stage if you have:
- A working product
- Proven product ROI
- Evidence that sales cycles are fast and sales are efficient
- Secured Series A funding
  
If you don't currently have type checking and lots of tests, you're in serious trouble. Probably, when you make a feature, you spend the same amount of time looking for bugs. At this stage, your technical debt grows exponentially.

### The late stage
For late-stage startups, it's all about performance and stability. Congratulations, you have come out of the death plateau for startups and your solution is in demand by the market. Now you need to be scalable. First, to be scalable, it's good to have flexible and reusable code. With strict type checking, you've lost flexibility. But your code is reusable if you've thought about it before. At this point, you need to refactor your code for flexibility and reusability. After refactoring, some parts of your code look like code at an early stage and need to be thoroughly tested.

### The Conclusion
Now, as you can see,  strict type checking is not needed at all stages of the development life cycle. And even this is not necessary for all parts of the application. It's good to be able to use type checking partially and when it's really needed.

## Killer features of Pro-script
1. You can partially use type checking and easily add it or remove it at any time without losing javascript flexibility.
2. You can use the principle of readable code for type checking.
3. You can improve your simple type checking to interface checking when you need it without any challenges.
4. The Pro-script solution is the same javascript which means you can use it in browser and server without any changes.
5. A micro-test is better than no tests. Pro-script has a micro-test framework that makes it quick and easy to run small tests. The same code runs well in the browser and on the server without any changes.

Well, the pro-script concept is not a silver bullet. You still need to have knowledge and experience. But pro-script gives you the ease and flexibility to create your future application. The [as-is](https://www.npmjs.com/package/@pro-script/as-is) module has everything you need to do this. Enjoy it.
