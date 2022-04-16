### [Peter Thiel's CS183: Startup - Class 15 Notes Essay][7]

   [7]: http://blakemasters.tumblr.com/post/24122680868/peter-thiels-cs183-startup-class-15-notes-essay

Here is an essay version of my class notes from Class 15 of CS183: Startup. Errors and omissions are mine.

Four guests joined the class for a conversation after the lecture:

  1. Danielle Fong, Co-founder and Chief Scientist of LightSail Energy;
  2. Jon Hollander, Business Development at RoboteX;
  3. Greg Smirin, COO of The Climate Corporation; and
  4. Scott Nolan, Principal at Founders Fund and former aerospace engineer at SpaceX (Elon Musk was going to come, but he was busy launching rockets).

Credit for good stuff goes to them and Peter. I have tried to be accurate. But note that this is not a transcript of the conversation. 

_Class 15 Notes Essay—Back to the Future_

**I. The Future of The Past**

Sometimes the best way to think about the future is to think about the way the future used to be. In the mid-20th century, it was still possible to talk about a future where the weather would be precisely predicted or even controlled. Maybe someone would figure out how to predict tornadoes. Or maybe cloud seeding would work. Transportation was the same way; people expected flying cars and civilian submarines. Robotics was yet another exciting frontier that people thought would be big.

[![][8]][9]

   [8]: http://media.tumblr.com/tumblr_m4vrcuR7L81qbb0b4.png
   [9]: http://puu.sh/xSvj

But fast-forward to the present. Things haven’t really worked out as people thought they would in the ‘50s and ‘60s. Weather still kind of just happens to us. People have pretty much accepted that as inevitable. The prevailing sense is that trying to control the weather is dangerous, and we shouldn’t tinker too much with it. Transportation has been similarly disappointing. Forget flying cars—we're still sitting in traffic. There has been some progress in robotics. But certainly not as much as everybody expected. We wanted the General Utility Non-Theorizing Environmental Control Robot from Lost in Space. Instead we got the Roomba vacuum cleaner.

[![][10]][11]

   [10]: http://media.tumblr.com/tumblr_m4vreeerYq1qbb0b4.png
   [11]: http://puu.sh/xSvq

All this is in stark contrast with computer science. There are no CS visions of the future that haven’t happened yet. We’ve seen Moore’s Law hold up, a relentless reduction in power consumption, and ever-increasing connectivity. Visions of the future from the past are more or less here. The 2-Way Wrist Radio/TV wristwatch from Dick Tracy watch is essentially an iPod nano. Arthur C. Clark basically predicted the Internet in his 1956 book _The City and the Stars_. So in computer science at least, it’s possible that you can’t get very much new insight by going back to the past.

![][12]

   [12]: http://media.tumblr.com/tumblr_m4vtiplkOu1qbb0b4.jpg

But in most areas, things got seriously off track. The future didn’t work. Nuclear power is another area that we were all but certain would work well. Instead, it turned out to be far more dangerous than people expected. There were all kinds of ways that people thought it was going to work that didn’t pan out, or at least haven’t happened yet.

So what might work today? One way to tackle that question is to think seriously about going back to the future. There may be lines of research that people didn’t pursue at particular points in the past that are worth revisiting. Not everything that has gone underexplored deserves to be lost. We talked about thorium power in our last class. There are various complicated reasons why that may or may not work. But if you suspect it was underexplored because the military favored plutonium/uranium R&D, it’s at least worth taking a look at.

Going back to future can be fun. Past visions of the future—think robots or space travel as imagined in the ‘60s—are culturally iconic. But the catch is that simply reminiscing doesn’t do us any good. We can’t simply go back to the past and copy it to make a better future. We have to remember that the future of the past didn’t work. The goal, then, is to tap into the past, learn all we can, and deploy that knowledge in some new, important way.

**II. Where The Future Has Failed**

There are many areas in which the future could be said to have failed. Let’s explore four: energy storage, weather, robotics, and space. After a quick, more abstract run-through of each, we’ll have a discussion with some people from companies that are doing interesting things in those spaces.

**A. Energy Storage**

The main problem with energy is that production costs are quite variable. Energy is considerably more expensive during peak usage times. But since it's very hard to store power that is produced off-peak, good solutions have been elusive.

Batteries have been the primary energy storage technology. But there is reason to believe that we are running up against serious and possibly unyielding limits to battery technology. Batteries are 200 years old. There have certainly been considerable improvements along the way. But the trajectory feels asymptotic. There are limits to the number of batteries that you can pack into a given space. There is a corrosion problem. Since most batteries involve positively and negatively charged particles, there may be chemistry limits. At this point coming up with better battery technology may be like finding a new element on the periodic table. 

So the future of energy storage is interestingly unclear. The chemical storage paradigm has done wonders, but maybe it’s done doing them. The question then becomes whether it is fruitful to think about energy storage in completely different ways? Are there other, non-chemical ways to attack the problem?

![][13]One company to highlight here is LightSail Energy. LightSail is developing a way to store energy more effectively. Again, this would enable a sort of incredible arbitrage where you can take advantage of the difference between the cost of peak vs. off-peak power production. Batteries and hydroelectric technologies are expensive and very limited. So their radically different approach treats energy storage not as a chemical problem, but rather as physics problem. 

   [13]: http://media.tumblr.com/tumblr_m4vrq8dolb1qbb0b4.png

[![][14]][15]

   [14]: http://media.tumblr.com/tumblr_m4vrrmPo8N1qbb0b4.png
   [15]: http://puu.sh/xSAg

At one level, it’s basic Boyle’s law. You use power to compress air into steel tanks. Later, when you want power, you decompress the air to release it. The main challenge is that air becomes very hot when you compress it. That allows power to dissipate. The fix is to basically spray water into their air to cool it down. Naturally, there are myriad complicated details on how to actually get it to work, but it’s a simple idea on a high level. LightSail says they’re tackling a trillion dollar market. We should push them on whether that means it’s huge opportunity or a rather huge competitive ocean where you can’t actually defend yourself. But physical instead of chemical storage is very orthogonal approach, and the technology is very promising. 

**B. Weather**

[![][16]][17]

   [16]: http://media.tumblr.com/tumblr_m4vs5ee8kE1qbb0b4.png
   [17]: http://puu.sh/xSyd

People have been interested in predicting the weather for a very long time. It’s sort of amazing that we are still really bad at it. Short-term forecasts are notoriously bad. There are all sorts of excuses for this. We know the systems are chaotic and complicated. But there’s a sense in which people given up and just stopped trying. If weather forecasting currently looks like fortunetelling, maybe we can make it less so. Maybe we can get more accurate. Certainly that would be quite valuable. 

And then there’s the question of whether you can control the weather. This is mostly abandoned territory because the question is perceived to be quite dangerous. Cloud seeding strikes some people as even crazier than terraforming Mars. This is a huge backlash against trying to control the weather, or even thinking about it. Pick your preferred mix of impossible/undesirable/unnecessary.

![][18]

   [18]: http://media.tumblr.com/tumblr_m4vt1kOCgV1qbb0b4.jpg

An interesting company in this fighting this reactionary consensus is The Climate Corporation, formerly known as Weatherbill.  They are trying to improve the crop loss insurance markets by precisely predicting the weather experience at a particular parcel of land and then making quick adjustments based on advanced computer modeling. It’s a statistical approach, so perhaps some initial skepticism is in order. That said, it’s a statistical approach in an area where people have grown wary of statistical approaches because they have all failed before. So interesting statistics approaches are possibly underexplored because people have given up on them. The secret is further hidden by the fact that hardly anyone looks into Agritech as a sector—by definition everything happens outside of Silicon Valley and so things like this tend to be overlooked and undervalued.

[![][19]][20]

   [19]: http://media.tumblr.com/tumblr_m4vu6162M71qbb0b4.jpg
   [20]: http://puu.sh/xSUh

**C. Robotics**

In the 1950s and ‘60s people had all kinds of ideas about how robots would improve things in the future. A common vision was the household butler/maid/cook/driver model, where the robot would raise standards of living by doing all these chores for free. That obviously hasn’t happened. There has been progress, but robotics has been just as much about limits to progress in recent decades. It’s quite expensive to build humanoid bots. And abilities are pretty limited. The state of the art is sort of a laundry-folding robot that can fold one piece of laundry in 45 minutes. When you ask experts when we should expect a Lost In Space-style robot, they usually estimate that won’t come for another 25 to 50 years. That may be right. And thinking long-term is good. But 25-50 years is _really _long-term; it’s just beyond the horizon where people are no longer accountable. So that prediction may be code for, “It will happen, but I don’t have to do anything. Someone else will do it.”

![][21]

   [21]: http://media.tumblr.com/tumblr_m4vvhk4m3a1qbb0b4.jpg

There are many ways in which we can re-imagine what robots can and should do.

RoboteX is a Silicon Valley-based robotics company that is doing just that.

Modern robots fall into one of the four quadrants on the following 2x2 matrix:

[![][22]][23]

   [22]: http://media.tumblr.com/tumblr_m4vsniR6bK1qbb0b4.jpg
   [23]: http://puu.sh/xSJV

The basic idea behind RoboteX that humans currently have to do lots of dangerous things. SWAT teams, hazardous materials experts, and bomb squad people all have very dangerous jobs. Instead of sending people in first, you can send in a robot to see what’s going on and maybe even take care of the situation. RoboteX robots, for instance, have a history of being quite effective at resolving hostage situations. Bad guys who are all amped up and determined to fight the police sort of psychologically break when they see a little robot come in instead, and surrender on the spot. It turns out that lots of organizations are willing to pay a considerable amount to avoid putting their people in harm’s way. So RoboteX’s reconceiving of robots as intermediaries, and not as humanoid things that duplicate human tasks, is quite valuable.

**D. Space**

Space was the final frontier for Star Trek in 1967. But ever since it has felt like a frontier that has become quite closed. Space museums feel quite static, almost like history museums. The Apollo 11 moon landing occurred in July of 1969. Apollo 17—the last U.S. lunar landing ever—was in December of ‘72.  So the entire period of moon landings lasted just 3.5 years. It has now been about 40 years since anyone was on the moon. Mars seems extremely ambitious considering that our generation hasn’t even done a lunar mission. 

Space has always been the iconic vision of the future. But a lot has gone wrong over the past couple of decades. Costs escalated rapidly. The Space Shuttle program was oddly Pareto inferior. It cost more, did less, and was more dangerous than a Saturn V rocket. It’s recent decommissioning felt like a close of a frontier. But maybe not. Exciting new perspectives and approaches suggest that a new era of space technology might be at hand. Can we produce more advanced software in telemetry? Develop radically new kinds of rockets? Can new technology take us back to the future? 

[![][24]][25]

   [24]: http://media.tumblr.com/tumblr_m4vtlkaIww1qbb0b4.png
   [25]: http://puu.sh/xSBl

We have been launching rockets into space for more than half a century now. But the cost to launch 1kg of mass into orbit hadn’t changed very much in 40 years. There were all sorts of reasons for this. The key insight is that most of the accounting for traditional space industry work was done on a cost-plus basis. Aerospace contractors charged for a rocket. Cushy profit margins were built in. Since people had lots of incentives to inflate costs, things became increasingly expensive. There’s also an argument that they became more dangerous.

The big question was whether it was even possible to re-approach the problem from a radically different angle. That is exactly what SpaceX is doing; focusing on getting the cost structure right and to drive launch costs down, and revisiting basic designs and revitalizing them with new technology and new materials. By most accounts, their radical improvements have been quite successful. SpaceX is arguably ushering in a new era of space flight.

[![][26]][27]

   [26]: http://media.tumblr.com/tumblr_m4vtrdbpeN1qbb0b4.jpg
   [27]: http://www.flickr.com/photos/astro_andre/7272242062/sizes/l/in/photostream/

**E. The Retrofuture Goal**

The retrofuture idea is simply this: think about where the past failed, learn the right lessons, and make it work this time. But it’s important to resist just being pulled in by the iconic future of old. There’s no sense in making the same mistakes over again. The key is to approach old problems from a very different perspective. 

**III. Perspectives –Conversation with LightSail Energy, The Climate Corporation, RoboteX, and SpaceX**

**Peter Thiel:** Your companies all represent vary different ways of thinking about the future. We’ve discussed in this class how radical uniqueness can be a very good thing in business. But does it make it hard to recruit people?

**Scott Nolan:** SpaceX recruited me out of my aero program. It was kind of an easy sell, actually: “You can go work for Boeing or Lockheed. Or you can come to SpaceX.” The established players had the cost-plus accounting model. There was a sense that there would be no meaningful opportunity to contribute there. Problem-solving mainly involved throwing more people at problems. But young engineers crave responsibility. So you see a startup like SpaceX and think, wow, I can surround myself with 30-50 amazing people and I’ll get all this responsibility. I can actually change something. 

So I think it’s pretty easy for SpaceX to get young engineers who are more startup kind of people. The harder part was probably attracting the more experienced aerospace veterans. It’s a lot trickier when industry people are and have been making well over a hundred thousand dollars per year. Trading a cushy job for startup equity can be a tough sell to risk-averse people. 

**Danielle Fong:** We haven’t had too much trouble recruiting at LightSail. There are many talented engineers in Silicon Valley who are doing electronics and hardware. All the members of our founding team joined up pretty easily. We started out in a garage machine shop. We couldn’t just grab experienced people in industry, though; there simple aren’t that many people who specialize in reiciprocating aerocompressors. So we really had to search. We went through over 1000 resumes and did about 400 interviews. Many of our best people have actually come from the auto racing industry. These are startup-compatible people. They understand hard work, small teams, and deadlines. If your car isn’t ready come race time, you lose. And the rules change all the time, so they are used to redesigning engines year after year. Learning enough about the racing industry to recruit from it was kind of a challenge. But ultimately, we had some success by asking these amazingly talented people whether they really wanted to spend the rest of their lives making cars go around in a circle.

**Greg Smirin:** That kind of narrative can be powerfully persuasive. In our business we need lots of quants and sophisticated software engineers. But Facebook and Google and all these me-too ad optimization companies suck up lots of talent. So we frame it rather provocatively; solving weather prediction is more important than helping middle-aged women send virtual pigs to each other. Gaming is a really cool industry. But a lot of people aren’t satisfied by building games, and want to do something bigger.

**Jon Hollander**: RoboteX’s founders, Adam and Nathan Gettings, started off building robots in their garage. Adam did the mechanical piece and Nathan did the software piece. The humble roots were important. Many people make the mistake of trying to build really advanced stuff right off the bat. But far more important is to start with basic machines that can deal with the laws of physics. A robot that can’t climb stairs or move across terrain is useless, no matter how advanced  its computers or cooling systems. Most of our competitors are quite fancy, but the basic things have problems. The tracks fall off the robots.

Once we had the first prototype, it wasn’t very difficult to get engineers. Robotics is pretty sexy. Our pitch is compelling: We build robots that save lives. Customers applaud us every day. Just today, one of our robots ended one of those hostage negotiation situations you mentioned. This guy who was holding his wife at knifepoint was spooked into surrendering peacefully. We’re not interested in building humanoid Rosy Robot or C-3PO. We build effective, low-cost robots for police departments, power plants—anybody with sort of dangerous or tactical needs. 

**Peter Thiel:** Let’s talk about the substance of your underlying technology. At least on a superficial level, you’re all trying to solve old problems. The retrofuture element raises two questions: What went wrong in the past? And why do you think you can solve these problems now? 

**Danielle Fong:** It turns out that the idea of using air as a medium for energy storage has been around for very long time. It was very popular in the 1870s, some 10 years before the electrical grid. And during that “golden age of compressed air,” people actually tried improving efficiency by spraying water in air! They knew that water has a very high heat capacity. But the technology was completely abandoned. All we can dig up is that there were “problems.” We don’t know any more than that. It’s possible that they didn’t have right materials. Maybe they had corrosion problems. It’s really hard to debug the mental processes of long-dead inventors. But what’s really amazing is that if things were done in the right sequences—if they had gotten aerocompression right—the history of technology would have unfolded extremely differently. There is a powerful path dependency to the history of energy.

**Greg Smirin:** People have been thinking about predicting the weather for a long time. And the concept of farming insurance isn’t new either. It’s probably been around since biblical times in some form or another. People would calculate odds the best they could and write policies as best they could. There are plenty of newspaper references to crop insurance in the late 1800s and early 1900s. But people then obviously didn’t have the computational power or the data to calculate very well. There was imperfect information on one side or the other. Today, we have that computational power. And we have the data. We’ve got a thousand CPUs spinning, crunching data from remote sensors that are measuring things very granularly at various points across a given plot of land. One of the challenges is how to boil all this data down in ways that are understandable and accessible to the farmers themselves—in a sense, the opposite problem that people faced 100 years ago.

**Jon Hollander**: One reason people haven’t gotten robots right in the past is a lack of focus on the mechanical side.  Science fiction is very good at getting people excited about robots. But it also gives them biases. People see humanoid bots on the silver screen and then go try to build robots with legs. That makes no sense. Tracks are much better. But even more important is that very high production costs have held the industry back. Low-cost robots would be ubiquitous, like laptops. But very few companies can build them. To keep costs down, RoboteX leverages the computer industry. There is this huge, efficient Asian infrastructure that has been developed to build computer components. So we take advantage of that and power our bots using off-the-shelf computer components. And then there are other materials innovations. Instead of cutting pieces out from aluminum blocks, for instance, we use strong plastics to make the same piece for maybe 1% of the cost.  

**Scott Nolan:** Since launch costs hadn’t been decreasing before SpaceX, it was clear that the rocket industry wasn’t really progressing. The reason a startup like SpaceX could succeed—and hopefully continue to dominate—was that it radically restructured the development process. Large, established players would spec out a system and outsource things. There was a lot of friction in the design process, and the incentives were to keep costs high. SpaceX changed all that. They disrupted the industry through clean sheet design, in-house vertical integration and a Silicon Valley culture. They came up with new engine designs, new structural designs, and new avionics. They took the concept of composites to the extreme. There were lighter components and new welding techniques that were used. Somewhat forgotten fuel injectors were resurrected. The number of innovations or radical re-thinkings of things is staggering.

**Jon Hollander**: Though RoboteX started really horizontal to drive down costs, it is becoming increasingly vertically integrated. We now have our own molds, chip designs, radio card deigns, etc. You can bring down production costs quite a bit if you design things that do exactly what you want and no more. You don’t have to pay anyone’s markup.

**Danielle Fong:** SpaceX was incredibly bold in this regard. Usually cost structures have little to do with the actual cost of components, and more to do with what people have historically been able to charge for those components. Shaking up an entire industry that ran on a cost-plus basis surely ruffled some feathers. But it was a huge opportunity. One tactic I’ve learned is to simply tell any supplier who provides a gigantic price quote that I can just make the part myself. They go into negotiation mode very quickly, and lower the price. Then you take _that _price to another supplier, and basically let them bid against each other. The goal is to be efficient where you’re not vertically integrated and also efficient where you are.

 

**Question from the audience: ** What has been your experience recruiting from or working with academia?

**Greg Smirin:** We’ve got about 20 people with PhDs at the Climate Corporation, and for many of them this is their first job outside academia. There’s certainly a transitional period. We have to help people learn how to use their talents to actually impact an organization instead of just applying for research grants or things like that. There is lots of screening on both sides before we bring someone on. Everybody’s looking for a good cultural fit. Not everyone fits, of course. But the ones that do are incredibly energizing and enthusiastic. Being able to contribute and have product impact in their areas of interest is intensely rewarding for them.

**Danielle Fong:** We work with professors on research topics all the time. Their input can be very helpful in terms of shifting discussion and vetting new ideas that we come up with. Professors are also pretty honest with us when we do reference checks and ask whether prospective hires are any good.

 

**Question from the audience: **How do you solve the distribution problem when you have to sell to the government or very large enterprises?

**Jon Hollander**: You can basically approach government sales in one of two ways.   The conventional way is to approach the military and do deals or research contracts there. The unconventional way, which is what RoboteX did, is to start small, target institutions like local police departments, and grow bottom-up. Staying thoroughly private was very important to us. Taking government funding often imposes serious constrains later down the line. By selling to lots of smaller agencies, we maintain a sense of freedom, get feedback from enthusiastic users, and can build up a nice revenue stream. And the plan, of course, is to scale that up and now we’re going after any and every large commercial business that has some sort of hazardous material problem.

**Peter Thiel:** A general rule of thumb on distribution is the larger the cost of a product, the slower the process. The classic mistake people make is to indulge the fantasy that you can just get that single contract for $100 million and everything will be golden. In practice it almost never works out that way. Theoretically it makes sense for a large nuclear power plant to deploy robots. RoboteX bots would have been very useful during the Fukushima disaster. But you generally can’t just go and sell to the theoretically ideal customer. There are sorts of processes in place. When thinking about sales and distribution, you have to remember that people don’t know what they want. It’s never completely objective. So even if your technology is an order of magnitude better, you can’t just make the golden sale. The person writing that $100 million check will ask who else has bought the product. If the answer is no one, they may well stop writing that check, since that means there is probably something wrong with it.

Very successful enterprise startups tend to have iterative sales models. They achieve a 50-100% growth rate year over year for several years. They might make $5M in the first year, and if things go really well, that will double every year for a decade. You might wonder why the revenue doesn’t just 10x in the fourth year when everybody understands the product’s superiority. But it doesn’t work like that. It usually turns out that no customer is willing to do a deal that’s 10x the size of your largest deal to date. Maybe 2x your biggest deal is a more realistic hope.

There is a venture capital version of this too. VCs fantasize about finding one really rich LP to invest in a fund. Find that golden investor and then you don’t have talk to anyone else. But it never works. LPs, like everyone else, cluster together. Everybody likes to act like they know what they’re doing. But in reality no one has a clue. Everyone is affected by everyone else in a hidden, unspoken way.

So the strategy should be to get the smallest customer that is also a good reference customer. Move quickly and acquire good references. RoboteX sells a robot to a local police department. The sale itself may not be huge, but the company can leverage any success in that narrow deployment. If the robot is good enough to stop a guy from shooting hostages, maybe it’s good for other things too. 

**Danielle Fong:** The exception is when someone is desperate for something that you can provide.

**Peter Thiel:** Yes. Always start with those people.

**Danielle Fong:** People who are in a pinch when other suppliers fail or flake out on them are often excellent customers.

**Greg Smirin:** Most sales models fail because people miscalculate the sales cycle. They underestimate just how long it takes to land the ideal clients. So a good recipe for success is to get the smallest, best customers you can, _quickly_. Jump the easy hurdles first. Then you’ll know more about how to deal with the larger enterprise customers.

**Scott Nolan:** And you can appeal to people’s sense of urgency. SpaceX would approach a customer and ask: Do you want to launch your satellite in 4 years? Or do you want to launch at dramatically less cost and fly next year? 

  
><span>

**Question from the audience: **How do you think about long-term exit strategy? Do you plan on being acquired or going public?

**Danielle Fong:** In theory, we would consider an acquisition. The issue would be whether the acquirer would likely mess up what we are doing. That seems fairly likely, since we’re taking such a unique approach to energy storage. But one never knows. The goal has to be to build a great business that can and will eventually trade publicly.

**Greg Smirin:** Any compelling technology that is released onto the market will attract acquisition offers. A company’s board of directors has a fiduciary duty to maximize shareholder value. So you quite literally have to consider acquisition offers. But from an operating perspective, there are all kinds of reasons that many or most acquisition proposals don’t seem right for hardcore technology startups working on hard problems.

**Peter Thiel:** Remember that sales works best when it’s disguised. Even uncompelling companies with terrible ideas would not say that they are planning to sell. If you want to sell, the best thing to do would be to act like you don’t. The VC version of this is: If you want advice, ask for money. If you want money, ask for advice. The political version is solemnly affirming that you have no interest in running for President. So a good first step toward selling your company is declaring that you’ll never sell it.

Typically, M&A is done for two reasons. First is to grind out inefficiencies. Banks, for example, just buy up smaller banks fire half the people. This creates somewhat larger, but more efficient banks. But simple efficiency is not what typically drives M&A in technology companies. In the tech world, M&A is usually about product synergy. It makes sense to merge when there is deep complementarity between two companies. There were big synergies between PayPal and eBay, for example. But that is the exception, not the rule. In practice, such synergy rarely exists. This is especially true where really unique technology is involved. Genuine complementarity between truly novel technology and what existing people are doing is very unlikely.

 

**Question from the audience: **Can you comment on the fundraising process for hardcore tech companies?

**Danielle Fong:** Well…it’s really fucking hard!  [laughter]

**Scott Nolan:** Elon had to put $100 million of his own money into SpaceX. There’s little doubt that he would have spent everything he had if he needed to. It didn’t come to that. But it goes to show that founders of these companies are, and maybe have to be, ready to go in all the way. They aren’t relying on investors to get it.

**Peter Thiel:** NASA more or less required SpaceX to take outside funding back in 2008. Founders Fund invested then. Various VC firms in Silicon Valley warned  expressed concern about this. They warned us that investing in SpaceX was risky and maybe even crazy. And this wasn’t even at the very early stage—this was after the company had built rockets and attempted some launches.

**Danielle Fong:** People like to act like they like being disruptive and taking risks. But usually it’s just an act. They don’t mean it. Or if they do, they don’t necessarily have the clout within the partnership to make it happen. So you have to find people who have opinions that dovetail with your mission.

**Peter Thiel:** It is very hard hard for investors to invest in things that are unique. The psychological struggle is hard to overstate. People gravitate to the modern portfolio approach. The narrative that people tell is that _their_ portfolio will be a portfolio of different things. But that seems odd. 

Things that are truly different are hard to evaluate. Suppose someone wants to start a rocket company. You might ask, quite reasonably, “What experience do you have with rockets?” The answer might be “zero.” Elon didn’t have any experience in making rockets before he started SpaceX. Or suppose a VC wants to invest in a rocket company. The question becomes: “What on earth do you know about rockets?” Again, the answer is probably “nothing.” No one has invested in rockets in over 40 years. 

iPhone games, by contrast, are entirely familiar. If you ask a gaming entrepreneur what experience he has with games, he’ll tell you about all the games he’s made before. Ask a VC what they know about games and they’ll go on and on about the many gaming companies in their portfolio.

The upside to doing something that you’re unfamiliar with, like rockets, is that it’s likely that no one else is familiar with it, either. The competitive bar is lowered. You can focus on learning and substantive things over process, which is perhaps better than competing against experts. 

[![Creative Commons License][28]][29]

   [28]: http://i.creativecommons.org/l/by-nc-nd/3.0/88x31.png
   [29]: http://creativecommons.org/licenses/by-nc-nd/3.0/

Originally posted by [Blake Masters][30]. You can find the [set of class notes on his site][31]

   [30]:https://twitter.com/bgmasters
   [31]:http://blakemasters.tumblr.com/peter-thiels-cs183-startup/.
