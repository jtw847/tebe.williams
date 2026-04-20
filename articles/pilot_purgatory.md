# Pilot Purgatory

**Tebe Williams · April 2026**

---

> Getting a Physical AI pilot approved is the easy part. Getting out of one is where most companies lose months they never recover. The teams that stall share three mistakes: they order parts without identifying their deepest constraint first, they build prototypes without supplier redundancy and scramble when something fails, and they apply less risk tolerance to the pilot than it actually deserves. The pilot does not need to be perfect. It needs to accomplish the primary goal without destroying inordinate value against that same primary goal. Once you reach that goal, the pilot is sufficiently successful.

---

Getting a Physical AI pilot approved is not the hard part. Everyone approves pilots. They are low-commitment, easy to sell internally, and give everyone involved a reason to feel like progress is happening. The hard part is getting out of one.

IDC research found that 88% of AI proofs of concept never make it to production. For every 33 pilots a company launches, only four graduate to real deployment. The gap is not a technology problem. It is three compounding operational mistakes that most founding teams make in the same order, every time.

## Your Deepest Constraint Arrives Last

Physical AI prototypes run on hardware, and hardware has lead times. Most teams approach procurement the same way: order broadly, order concurrently, and assume things will come together. The problem with concurrent timelines is that they hide your actual constraint. You find yourself 90% complete, waiting on one component with a six-week lead time, only to discover it has the wrong tolerance or is not as durable as the spec suggested. The prototype stalls. The timeline slips. The stakeholder who approved the pilot starts asking questions.

The discipline is to identify your hardest dependency before anything else gets ordered. Not the most expensive part, not the most technically complex: the one that takes the longest to get right and has the fewest alternatives if it is wrong. That part comes first. Everything else gets scheduled around it. Nobody does this on the first prototype. Almost everyone learns it the hard way on the second.

## You Found a Bad Part and Have Nowhere to Go

Prototypes get rushed because urgency feels like momentum. The team wants to get something in the field, leadership wants to see results, and the machine gets assembled from parts that were available rather than parts that were right. When one of those parts fails in the field, which it will, the team scrambles to find an alternative supplier. That work, finding a second source, vetting a replacement, qualifying the tolerance against the original spec, could have taken hours at the beginning of the project. Under pressure at the end, it takes weeks, and the replacement you find is not one you are confident in. It is simply the one you could think of.

Supplier redundancy is not a procurement luxury. It is a prototype design requirement. The team that has identified two qualified sources for every critical component before the build starts will spend its time learning from the field. The team that has not will spend its time on the phone trying to find one.

## You Are Treating the Pilot Like a Product

This is the mistake that costs the most time and the least money, which is why it is so easy to rationalize. Teams treat the pilot as something that must be refined, tested, and perfected before it can leave their hands. The risk tolerance goes down when it should go up. A pilot is not a product. It does not need to handle every scenario. It needs to reliably do one thing: prove the core thesis.

The software world already knows this and largely does not care. Every LLM on the market hallucinates. ChatGPT hallucinates. Claude hallucinates. They did it far more often in 2022 than they do today, and the world deployed them anyway, learned from what broke, and iterated toward something better. Yum Brands deployed AI voice ordering at Taco Bell drive-thrus in 2023. The system misinterpreted orders in noisy environments, one customer was entered for 18,000 cups of water, and repeated upselling prompts frustrated customers. Yum expanded the rollout to more than 100 locations across 13 states. New York City launched an AI chatbot to help small business owners navigate city processes. It gave illegal advice, including suggesting employers could fire workers for reporting sexual harassment. The city kept it online. In neither case was the product ready. In both cases, the organizations made a reasonable judgment: the thing works well enough against its primary purpose to keep going, and we will fix what breaks in the field.

That is the correct risk tolerance for a pilot. The question is not whether the system is ready. The question is whether it accomplishes the primary goal without destroying inordinate value against that same primary goal. If the answer is yes, the pilot is done. Move to the next one. Learn from deployment, not from another iteration in the lab. Perfect is the enemy of good enough, and in Physical AI, good enough in the field teaches you more in two weeks than perfect in the lab teaches you in six months.

We launched Volley on platform tennis. Not tennis. Not pickleball. Not padel. One sport, and a niche one at that. The prototype worked, the pilot proved the thesis, and that was the only question that mattered. There was no reason to delay a working deployment until we could also serve a tennis ball and handle a padel court. Those came later, from operating in the field, from watching what the system did in real conditions against real players. The second sport, the third, the fourth: none of them came from waiting. They came from going.

The companies stuck in pilot purgatory are not waiting on better technology. They are waiting on permission they have already earned.
