## What is system design?

Before we dive in, let's define exactly what we are building toward.

System design is the process of defining the architecture, components, modules, interfaces, and data for a system to satisfy specific requirements.

Think of it as urban planning for software. You aren't just building a single house (writing a feature); you are designing the entire city's infrastructure-the roads, water lines, and power grids-to ensure it can scale and survive disasters.

  - INFRASTRUCTURE  (Load Balancers, CDNs, Gateways)     
  - APPLICATION     (Monoliths vs. Microservices, APIs)  
  - DATA LAYER      (SQL vs. NoSQL, Sharding, Caching)


### Why is System Design so important?

When you build a small app, you can usually just start coding. But when you build a massive platform like Netflix, Instagram, or Amazon, you can't just wing it.

- Imagine building a 50-story skyscraper. If you realize on floor 40 that the concrete foundation at the bottom is too weak, you can't easily fix it. You might have to tear the whole building down.
System design happens at the very beginning. It makes sure your software's foundation is strong before you spend months writing code.

- It stops your app from crashing
If 100 people visit your website, it runs fine. But what if 1,000,000 people show up at the exact same time?Without design: Your servers get overwhelmed and the website crashes.
With design: You have a plan to automatically share the workload across hundreds of servers so the app stays fast for everyone.

- It makes your app easy to change
A good system is built like LEGO blocks. If you want to change the wheels on a LEGO car, you don't have to break the roof. System design helps you split your software into independent pieces. That way, you can upgrade your database or add a new feature later without breaking the rest of the app.

In short: System design is the ultimate plan. It takes what the business needs and turns it into a blueprint, making sure your software doesn't just work today, but keeps working tomorrow.
