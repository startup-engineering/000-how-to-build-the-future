### [Peter Thiel's CS183: Startup - Class 3 Notes Essay][7]

   [7]: http://blakemasters.tumblr.com/post/20955341708/peter-thiels-cs183-startup-class-3-notes-essay

Here is an essay version of my class notes from Class 3 of CS183: Startup. Errors and omissions are my own. Credit for good stuff is Peter’s entirely.  Please note that I actually missed this class (I was on my honeymoon!). Thanks to [@erikpavia][8] and [@danrthompson][9] for sending me their notes to work from.

   [8]: https://twitter.com/#!/erikpavia (Erik Pavia on twitter)
   [9]: https://twitter.com/#!/danrthompson (Dan Thompson on twitter)

**CS183: Startup—Notes Essay—Value Systems**

 The history of the ‘90s was in many ways the history of widespread confusion about the question of value. Valuations were psychosocial; value was driven by what people said it was. To avoid herd-like confusion of decades past, we need to try and figure out whether it’s possible to determine businesses’ objective value and, if it is, how to do it.

As we discussed back in Class 1, certain questions and frameworks can anchor our thinking about value. The questions are necessarily personal: What can _I_ do? What do _I think_ is valuable? _What do I see others not doing_? A good framework might map globalization and technology as the two great axes of the 21st century. Synthesizing all this together forges the higher-level question: _What valuable company is nobody building_? 

A somewhat different perspective on technology—going from 0 to 1, to revisit our earlier terminology—is the financial or economic one. Since that perspective can also shed considerable light on the value question, it’s worth covering in detail now.

**I. Great Technology Companies**

Great companies do three things. First, they create value. Second, they are lasting or permanent in a meaningful way. Finally, they capture at least some of the value they create.

The first point is straightforward. Companies that don’t create value simply can’t be great. Creating value may not be sufficient for greatness, but it’s hard to see how it’s not at least necessary.

Great companies last. They are durable. They don't create value and disappear very fast. Consider disk drive companies of the 1980s. They created a lot of value by making new and better drives. But the companies themselves didn't last; they were all replaced by others. Not sticking around limits both the value you can create and the value you can capture.

Finally—and relatedly—you have to capture much of the value you create in order to be great. A scientist or mathematician may create a lot of lasting value with an important discovery. But capturing a meaningful piece of that value is another matter entirely. Sir Isaac Newton, for example, failed to capture much of the immense value that he created through his work. The airline industry is a less abstract example. The airlines certainly create value in that the public is much better off because they exist. And they employ tons of people. But the airlines themselves have never really made any money. Certainly some are better than others. But probably none can be considered a truly great company.

**II. Valuation**

One way that people try and objectively determine a company’s value is through multiples and comparables. This sort of works. But people should be on guard against social heuristics substituting for rigorous analysis, since analysis tends to be driven by standards and conventions that exist at the time. If you start a company at an incubator, certain conventions exist there. If everyone is investing at a $10M cap, the company might be deemed to be worth $10M. There are a bunch of formulas that incorporate metrics like monthly page views or number of active users that people use sometimes. Somewhat more rigorous are revenue multiples. Software companies are often valued at around 10x annual revenues. Guy Kawasaki has suggested a particularly unique (and possibly helpful) equation:

> pre-money valuation = ($1M*n_engineers) - ($500k*n_MBAs).

The most common multiple is the price-earnings ratio, also known as P/E ratio or the PER. The PER is equal to market value (per share)  / earnings (per share). In other words, it is the price of a stock relative to a firm’s net income. The PER is widely used but does not account for growth.

To account for growth, you use the PEG, or Price/Earnings to Growth ratio. PEG equals (market value / earnings) / annual earnings growth. That is, PEG is PER divided by annual growth in earnings. The lower a company’s PEG ratio, the slower it’s growing and thus the less valuable it is. Higher PEG ratios tend to mean higher valuations. In any case, PEG should be less than one. The PEG is a good indicator to keep an eye on while growing your business.

One does valuation analysis at a given point in time. But that analysis factors in many points in time. You look not just at cash flows for the current year, but over future years as well. Sum all the numbers and you get the earnings value. But a quantity of money today is worth more than it is in the future. So you discount the time value of money, or TVM, since there are all sorts of risks as you move forward in the future. The basic math for TVM is:

       ![][10]

   [10]: http://media.tumblr.com/tumblr_m2cv0qBg1d1qbb0b4.png

Things are harder when cash flows aren’t constant. Here is the math for variable cash flows:

         ![][11]

   [11]: http://media.tumblr.com/tumblr_m2cv13P8681qbb0b4.png

So to determine the value of a company, you do the applicable DPV or NPV calculation for the next X (or infinite) years. Generally, you want _g _to be greater than _r_. Otherwise your company isn’t growing enough to keep up with the discount rate. Of course, in a growth model, the growth rate must eventually decline. Otherwise the company will approach infinite value over time—not likely. 

Valuations for Old Economy firms work differently. In businesses in decline, most of the value is in the near term. Value investors look at cash flows. If a company can maintain present cash flows for 5 or 6 years, it’s a good investment. Investors then just hope that those cash flows—and thus the company’s value—don’t decrease faster than they anticipate.

Tech and other high growth companies are different. At first, most of them _lose_ money. When the growth rate—_g_, in our calculations above—is higher than the discount rate _r_, a lot of the value in tech businesses exists pretty far in the future. Indeed, a typical model could see 2/3 of the value being created in years 10 through 15. This is counterintuitive. Most people—even people working in startups today—think in Old Economy mode where you have to create value right off the bat. The focus, particularly in companies with exploding growth, is on next months, quarters, or, less frequently, years. That is too short a timeline. Old Economy mode works in the Old Economy. It does not work for thinking about tech and high growth businesses. Yet startup culture today pointedly ignores, and even resists, 10-15 year thinking.

PayPal is illustrative. 27 months in, its growth rate was 100%. Everybody knew that rate would decelerate, but figured that it would still be higher than the discount rate. The plan was that most of the value would come around 2011. Even that long-term thinking turned out to undershoot; the discount rate has been lower than expected, and the growth rate is still at a healthy 15%. Now, it looks like most of PayPal’s value won’t come until in 2020.

LinkedIn is another good example of the importance of the long-term. Its market cap is currently around around $10B and it’s trading at a (very high) P/E of about 850. But discounted cash flow analysis makes LinkedIn’s valuation make sense; it’s expected to create around $2B in value between 2012 and 2019, while the other $8B reflects expectations about 2020 and beyond. LinkedIn’s valuation, in other words, only makes sense if there’s durability, i.e. if it’s around to create all that value in the decades to come.

**III. Durability**

People often talk about “first mover advantage.” But focusing on that may be problematic; you might move first and then fade away. The danger there is that you simply aren’t around to succeed, even if you do end up creating value. More important than being the first mover is being the last mover. You have to be durable. In this one particular at least, business is like chess. Grandmaster José Raúl Capablanca put it well: to succeed, “you must study the endgame before everything else.”

**IV. Capturing Value**

The basic economic ideas of supply and demand are useful in thinking about capturing value. The common insight is that market equilibrium is where supply and demand intersect. When you analyze a business under this framework, you get one of two options: perfect competition or monopoly.

In perfect competition, no firms in an industry make economic profit. If there are profits to be made, firms enter the market and the profits go away. If firms are suffering economic losses, some fold and exit. So you don’t make any money. And it’s not just you; _no one _makes any money. In perfect competition, the scale on which you’re operating is negligible compared to the scale of the market as a whole. You might be able to affect demand a little bit. But generally you’re a price taker. 

But if you’re a monopoly, you own the market. By definition, you’re the only one producing a certain thing. Most economics textbooks spend a great deal of time talking about perfect competition. They tend to treat monopoly as somehow being within, or as some small exception to perfect competition. The world, say these books, defaults to equilibrium.

But perhaps monopoly is not some strange exception. Perhaps perfect competition is only the default in economics textbooks. We should wonder whether monopoly is a valid alternative paradigm in its own right. Consider great tech companies. Most have one decisive advantage—such as economies of scale or uniquely low production costs—that make them at least monopoly-esque in some important way. A drug company, for instance, might secure patent protection for a certain drug, thus enabling it to charge more than its costs of production. The really valuable businesses are monopoly businesses. They are the last movers who create value that can be sustained over time instead of being eroded away by competitive forces.

**V. The Ideology of Competition**

**A. PayPal and Competition**

PayPal was in the payments business. There were considerable economies of scale in that business. You couldn’t compete with the big credit card companies directly; to compete, you had to undercut them in some way. PayPal tried to do that in two ways: through technical innovation and through product innovation.

The primary technical problem that PayPal faced was fraud. When Internet payments started to get going, there was much more fraud than people expected. Also unexpected was how hard it was to stamp it out. Enemies in the War on Fraud were many. There was “Carders World,” a dystopian web marketplace that vowed to bring down Western Capitalism by transacting in stolen identities. There was a particularly bothersome hacker named Igor, who evaded the FBI on jurisdictional technicalities. (Unrelatedly, Igor was later killed by the Russian mafia.) Ultimately, PayPal was able to develop really good software to get a handle on the fraud problem. The name of that software? “Igor.”

Another key innovation was making funding sources cheaper. Getting users’ bank account information drove down blended costs. By modeling how much money was in an account, PayPal could make advance payments, more or less circumvent the Automatic Clearing House system, and make payments instantaneous from the user’s perspective. 

These are just two examples from PayPal. Yours will look different. The takeaway is that it’s absolutely critical to have some decisive advantage over the next best service. Because even a small number of competing services quickly makes for a very competitive dynamic.

**B. Competition and Monopoly**

Whether competition is good or bad is an interesting (and usually overlooked) question. Most people just assume it’s good. The standard economic narrative, with all its focus on perfect competition, identifies competition as the source of all progress. If competition is good, then the default view on its opposite—monopoly—is that it must be very bad.  Indeed, Adam Smith adopted this view in _The Wealth of Nations_:

> People of the same trade seldom meet together, even for merriment and diversion, but the conversation ends in a conspiracy against the public, or in some contrivance to raise prices.

This insight is important, if only because it’s so prevalent. But exactly why monopoly is bad is hard to tease out. It’s usually just accepted as a given. But it’s probably worth questioning in greater detail.

**C. Testing for Monopoly**

The Sherman Act declares: “The possession of monopoly power will not be found unlawful unless it is accompanied by an element of anticompetitive conduct.” So in order to determine whether a monopoly is illegal or not, we just have to figure out what “anticompetitive conduct” means.

The DOJ has 3 tests for evaluating monopolies and monopoly pricing. First is the Lerner index, which gives a sense of how much market power a particular company has. The index value equals (price – marginal cost) / price. Index values range from 0 (perfect competition) to 1 (monopoly). The intuition that market power matters a lot is right. But in practice the Lerner index tends to be intractable with since you have to know market price and marginal cost schedules. But tech companies know their own information and should certainly pay attention to their Lerner index. 

Second is the Herfindahl-Hirschman index. It uses firm and industry size to gauge how much competition exists in an industry. Basically, you sum the squares of the top 50 firms’ market shares. The lower the index value, the more competitive the market. Values below 0.15 indicate a competitive market. Values from 0.15 to .25 indicate a concentrated market. Values higher than 0.25 indicate a highly concentrated and possibly monopolistic market. 

Finally, there is the m-firm concentration ratio. You take either the 4 or 8 largest firms in an industry and sum their market shares. If together they comprise more than 70% of the market, then that market is concentrated.

**D. The Good and Bad of Monopoly**

First, the cons: monopolies generally produce lower output and charge higher prices than firms in competitive markets do. This may not hold true for some natural monopolies. And some industries have monopolies of scale, which are a bit different. But monopolies generally get to be price setters, not price takers. There also might be price discrimination, since monopolists may capture more consumer surplus by charging different groups different prices. Another criticism is that monopoly stifles innovation; since it earns profits whether it innovates or not, a monopoly business might grow complacent and not develop any new technology.

But the innovation argument can go the other way too. Monopoly might net incentivize innovation. If a company creates something dramatically better than the next best thing, where’s the harm in allowing it to price it higher than its marginal cost of production? The delta is the creators’ reward for creating the new thing. Monopolistic firms can also conduct better long-term planning and take on deeper project financing, since there’s a sense of durability that wouldn’t exist in perfect competition where profits are zero.

**E. Biases for Perfect Competition**

An interesting question is why most people seem biased in favor of perfect competition. It’s hard to argue that economists don’t tend to idolize it. Indeed the very term “perfect competition” seems pregnant with some normative meaning. It’s not called “insane competition” or “ruthless competition.” That’s probably not an accident. Perfect competition, we’re told, is perfect. 

To start, perfect competition may be attractive because it’s easy to model. That probably explains a lot right there, since economics is all about modeling the world to make it easier to deal with. Perfect competition might also seem to make sense because it’s economically efficient in a static world. Moreover, it’s politically salable, which certainly doesn’t hurt.

But the bias favoring perfect competition is a costly one. Perfect competition is arguably psychologically unhealthy. Every benefit social, not individual. But people who are actually involved in a given business or market may have a different view—it turns out that many people actually want to be able to make a profit. The deeper criticism of perfect competition, though, is that it is irrelevant in a dynamic world. If there is no equilibrium—if things are constantly moving around—you can capture some of the value you create. Under perfect competition, you can’t. Perfect competition thus preempts the question of value; you get to compete hard, but you can never gain anything for all your struggle. Perversely, the more intense the competition, the less likely you’ll be able to capture any value at all. 

Thinking through this suggests that competition is overrated. Competition may be a thing that we’re taught, and that we do, unquestioningly. Maybe you compete in high school. Then more, tougher competition in college and grad school. And then the “rat race” in the real world. An apt, though hardly unique example of intense professional competition is the Big Law model for young lawyers from top law schools. You graduate from, say, Stanford Law and then go work at a big firm that pays you really well. You work insanely hard to try and make partner until you either do or you don’t. The odds aren’t in your favor, and you’ll probably quit before you get the chance to fail. Startup life can be tough, but also less pointlessly competitive. Of course, some people like the competitiveness of law firms. But it’s probably safe to say that most don’t. Ask anyone from the latter camp and they may well say that they never want to compete at anything again. Clearly, winning by a large margin is better than ruthless competition, if you can swing it.

Globalization seems to have a very competitive feel to it. It’s like a track and field sprint event where one runner is winning by just a few seconds, with others on his heels. That’s great and exciting if you’re the spectator. But it’s not a natural metaphor for real progress.  

If globalization had to have a tagline, it might be that “the world is flat.” We hear that from time to time, and indeed, globalization starts from that idea. Technology, by contrast, starts from the idea that the world is Mount Everest. If the world is truly flat, it’s just crazed competition. The connotations are negative and you can frame it as a race to the bottom; you should take a pay cut because people in China are getting paid less than you. But what if the world isn’t just crazed competition? What if much of the world is unique? In high school, we tend to have high hopes and ambitions. Too often, college beats them out of us. People are told that they’re small fish in a big ocean. Refusal to recognize that is a sign of immaturity. Accepting the truth about your world—that it is big and you are just a speck in it—is seen as wise.

That can’t be psychologically healthy. It’s certainly not motivating. Maybe making the world a smaller place is exactly what you want to do. Maybe you don’t want to work in big markets. Maybe it’s much better to find or make a small market, excel, and own it. And yet, the single business idea that you hear most often is: the bigger the market, the better. That is utterly, totally wrong. The restaurant business is a huge market. It is also not a very good way to make money.

The problem is that when the ocean is really big, it’s hard to know exactly what’s out there. There might be monsters or predators in some parts who you don’t want to run into. You want to steer clear of the parts painted red by all the carnage. But you can’t do that if the ocean is too big to get a handle on. Of course, it _is_ possible to be the best in your class even if your class is big. After all, _someone_ has to be the best. It’s just that the bigger the class, the harder it is to be number one. Well-defined, well-understood markets are simply harder to master. Hence the importance of the second clause in the question that we should keep revisiting: what valuable company _are other people not building_?

**F. On VC, Networks, and Closing Thoughts**

 Where does venture capital fit in? VCs tend not to have a very large pool of business. Rather, they rely on very discreet networks of people that they’ve become affiliated with. That is, they have access to a unique network of entrepreneurs; the network is the core value proposition, and is driven by relationships. So VC is anti-commoditized; it is personal, and often idiosyncratic. It thus has a lot in common with great businesses. The PayPal network, as it’s been called, is a set of friendships built over the course of a decade. It has become a sort of franchise. But this isn’t unique; that kind of dynamic arguably characterizes all great tech companies, i.e. last mover monopolies. Last movers build non-commoditized businesses. They are relationship-driven. They create value. They last. And they make money.

[![Creative Commons License][12]][13]

   [12]: http://i.creativecommons.org/l/by-nc-nd/3.0/88x31.png
   [13]: http://creativecommons.org/licenses/by-nc-nd/3.0/

Originally posted by [Blake Masters][14]. You can find the [set of class notes on his site][15]

   [14]:https://twitter.com/bgmasters
   [15]:http://blakemasters.tumblr.com/peter-thiels-cs183-startup/.
