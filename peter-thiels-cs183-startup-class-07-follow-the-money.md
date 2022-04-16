### [Peter Thiel's CS183: Startup - Class 7 Notes Essay][7]

   [7]: http://blakemasters.tumblr.com/post/21869934240/peter-thiels-cs183-startup-class-7-notes-essay

Here is an essay version of my class notes from Class 7 of CS183: Startup. Errors and omissions are mine.

Roelof Botha, partner at Sequoia Capital and former CFO of PayPal, and Paul Graham, partner and co-founder of Y Combinator, joined this class as guest speakers. Credit for good stuff goes to them and Peter. I have tried to be accurate. But note that this is not a transcript of the conversation.

_Class 7 Notes Essay—Follow the Money_

_I.  Venture Capital and You_

Many people who start businesses never deal with venture capitalists. Founders who do interact with VCs don’t necessarily do that early on. First you get your founders together and get working. Then maybe you get friends, family, or angels to invest. If you do end up needing to raise a larger amount of capital, you need to know how VC works. Understanding how VCs think about money—or, in some cases, how they don’t think about it and thus lose it—is important. 

VC started in late 1940s. Before that, wealthy individuals and families were investing in new ventures quite frequently. But the idea of pooling funds that professionals would invest in early stage companies was a product of the ‘40s. The Sand Hill road, Silicon Valley version came in the late 1960s, with Sequoia, Kleiner Perkins, and Mayfield leading the field. 

Venture basically works like this:  you pool a bunch of money that you get from people called limited partners. Then you take money from that pool and invest it in portfolio companies that you think are promising. Hopefully those companies become more valuable over time and everybody makes money. So VCs have the dual role of encouraging LPs to give them money and then finding (hopefully) successful companies to back.

Most of the profits go back to LPs as returns on their investment. VCs, of course, take a cut. The typical model is called 2-and-20, which means that the VC firm charges an annual management fee of 2% of the fund and then gets 20% of the gains beyond the original investment. The 2% management fee is theoretically just enough to allow the VC firm to continue to operate. In practice, it can end up being a lot more than that; a $200m fund would earn $4m in management fees under a 2-and-20 structure. But it’s certainly true that the real payout that VCs look for come with the 20% cut of the gains, which is called the carry.

VC funds last for several years, because it usually takes years for the companies you invest in to grow in value. Many of the investments in a given fund either don’t make money or go to zero. But the idea is that the companies that do well get you all your money back and then some; you end up with more money in the fund at the end than LPs put in to begin with.

There are many dimensions to being a good VC. You have to be skilled at coming up with reasonable valuations, identifying great entrepreneurs, etc. But there’s one dimension that is particularly important, yet surprisingly poorly understood. It is far and away the most important structural element of venture capital: exponential power. This may seem odd because it’s just basic math. But just as 3rd grade arithmetic—knowing not just how many shares you get, but dividing that by the shares outstanding—was crucial to understand equity, 7th grade math—understanding exponents—is necessary to understand VC.

The standard Einstein line on this is that the most powerful force in universe is compound interest. We see the power of compounding when companies grow virally. Successful businesses tend to have an exponential arc to them. Maybe they grow at 50% a year and it compounds for a number of years. It could be more or less dramatic than that. But that model—some substantial period of exponential growth—is the core of any successful tech company. And during that exponential period, valuations tend to go up exponentially.

So consider a prototypical successful venture fund. A number of investments go to zero over a period of time. Those tend to happen earlier rather than later. The investments that succeed do so on some sort of exponential curve. Sum it over the life of a portfolio and you get a J curve. Early investments fail. You have to pay management fees. But then the exponential growth takes place, at least in theory. Since you start out underwater, the big question is when you make it above the water line. A lot of funds never get there. 

To answer that big question you have to ask another: what does the distribution of returns in venture fund look like? The naïve response is just to rank companies from best to worst according to their return in multiple of dollars invested. People tend to group investments into three buckets. The bad companies go to zero. The mediocre ones do maybe 1x, so you don’t lose much or gain much. And then the great companies do maybe 3-10x. 

But that model misses the key insight that actual returns are _incredibly skewed_. The more a VC understands this skew pattern, the better the VC. Bad VCs tend to think the dashed line is flat, i.e. that all companies are created equal, and some just fail, spin wheels, or grow. In reality you get a power law distribution.

![][8]

   [8]: http://media.tumblr.com/tumblr_m34ireYrLP1qbb0b4.png

An example will help clarify. If you look at Founders Fund’s 2005 fund, the best investment ended up being worth about as much as all the rest combined. And the investment in the second best company was about as valuable as number three through the rest. This same dynamic generally held true throughout the fund. This is the power law distribution in practice. _To a first approximation, a VC portfolio will only make money if your best company investment ends up being worth more than your whole fund_. In practice, it’s quite hard to be profitable as a VC if you don’t get to those numbers. 

PayPal sold to eBay for $1.5bn. PayPal’s early stage investors had a large enough stake such that their investment was ultimately worth about the size of their fund. The rest of the fund’s portfolio didn’t do so well, so they more or less broke even riding on PayPal. But PayPal’s series B investors, despite doing quite well with the PayPal investment, didn’t break even on their fund. Like many other VC funds in the early 2000’s, theirs lost money. 

That investment returns take a power law distribution leads to a few important conclusions. First, you need to remember that, management fees aside, you only get paid if you return all the money invested plus more. You have to at least hit the 100% of fund size mark. So given power law distribution, you have to ask the question: “Is there a reasonable scenario where our stake in this company will be worth more than the whole fund?” 

Second is that, given a big power law distribution, you want to be fairly concentrated. If you invest in 100 companies to try and cover your bases through volume, there’s probably sloppy thinking somewhere. There just aren’t that many businesses that you can have the requisite high degree of conviction about. A better model is to invest in maybe 7 or 8 promising companies from which you think you can get a 10x return. It’s true that in theory, the math works out the same if try investing in 100 different companies that you think will bring 100x returns. But in practice that starts looking less like investing and more like buying lottery tickets. 

Despite being rooted in middle school math, exponential thinking is hard. We live in a world where we normally don’t experience anything exponentially. Our general life experience is pretty linear. We vastly underestimate exponential things. If you backtest Founders Fund’s portfolios, one heuristic that’s worked shockingly well is that you should always exercise your pro rata participation rights whenever a smart VC was leading a portfolio company’s up round. Conversely, the test showed that you should never increase your investment on a flat or down round. 

Why might there be such a pricing inefficiency? One intuition is that people do not believe in a power law distribution. They intuitively don’t believe that returns could be that uneven. So when you have an up round with a big increase in valuation, many or even most VCs tend to believe that the step up is too big and they will thus underprice it. The practical analogue would be to picture yourself working in a startup. You have an office. You haven’t hit the exponential growth phase yet. Then the exponential growth comes. But you might discount that change and underestimate the massive shift that has occurred simply because you’re still in the same office, and many things look the same. 

Flat rounds, by contrast, should be avoided because they mean that the VCs involved believe things can’t have gotten that much worse. Flat rounds are driven by people who think they might get, say, a 2x return from an investment. But in reality, often something has gone very badly wrong—hence the flat round’s not being an up round. One shouldn’t be mechanical about this heuristic, or treat it as some immutable investment strategy. But it actually checks out pretty well, so at the very least it compels you to think about power law distribution. 

Understanding exponents and power law distributions isn’t just about understanding VC. There are important personal applications too. Many things, such as key life decisions or starting businesses, also result in similar distributions. We tend to think about these things too moderately. There is a perception that some things are sort of better than other things, sometimes. But the reality is probably more extreme than that.

Not always, of course. Sometimes the straighter, perceived curve actually reflects reality quite closely. If you were to think about going to work for the Postal Service, for example, the perceived curve is probably right. What you see is what you get. And there are plenty of things like that. But it’s also true that we are, for some reason or other, basically trained to think like that. So we tend to miscalculate in places where the perceived curve does not, in fact, accurately reflect reality. The tech startup context is one of those places. The skew of distributions for tech startups is really vast. 

This means that when you focus on the percentage of equity you get in a company, you need to need to add a modifier: given something like a power law distribution, where your company is on that curve can matter just as much or more than your individual equity stake.

All else equal, having 1% of a company is better than having 0.5%. But the 100th employee at Google did much better than the average venture-backed CEO did in the last decade.  The distribution is worth thinking hard about. You could spin this into argument against joining startups. But it needn’t go that far. The power law distribution simply means you have to think hard about a given company is going to fall on the curve.

The pushback to this is that the standard perception is reasonable—or at least is not unreasonable—because the actual distribution curve turns out to be random. The thesis is that you are just a lottery ticket. That is wrong. We will talk about why that is wrong later. For now, it’s enough to point out that the actual curve is a power law distribution. You don’t have to understand every detail and implication of what that means. But it’s important to get some handle on it. Even a tiny bit of understanding of this dimension is incredibly valuable.

 

_II.  The View from Sand Hill Road_

**Peter Thiel:** One thing we should talk about is what secrets VCs use to make money. Well, actually most don’t make money. So let’s talk about that.

**Roelof Botha:** The unprofitability of venture capital is pretty well documented. Average returns have been pretty low for a number of years now. One theory is that when venture was doing very well in the 1990s, it became a big deal to more or less blindly follow advice to put more money in venture. So the industry may be overinvested, and it’s hard for most firms to make money.

 

**Peter Thiel:** Paul, what can entrepreneurs do to avoid getting taken advantage of by VCs?

**Paul Graham:** There’s nothing inherently predatory about VC. Y-Combinator is a minor league farm club. We send people on _up_ to VCs. VCs aren’t evil or corrupt or anything. But in terms of getting a good deal and not a bad one, it’s the same with any deal; the best way to get a good price is to have competition. VCs have to be competing to invest in you. 

**Peter Thiel:** We’ve discussed in this class how competition can be a scary thing. Maybe it’s less bad when you make VCs compete against each other. In practice, you never really land just one investor. Chances are you have at least two people who are interested or you have zero. The cynical explanation of this is that most VCs have little or no confidence in their ability to make decisions. They just wait to ape others’ decisions. 

**Paul Graham:** But investors also have an interest to wait, if they can. Waiting means that you’re able to get more data about a given company. So waiting is only bad for you if founders raise the price while you wait. VCs are looking for startups that are the next Google, or not. They are cool with 2x returns. But more than that they don’t want to lose a Google.

  
><span>

**Peter Thiel:** How do you avoid being a VC that loses money?

**Roelof Botha:** Since the distribution of startup investment outcomes follows a power law, you cannot simply expect to make money by simply cutting checks. That is, you cannot simply offer a commodity. You have to be able to help portfolio companies in a differentiated way, such as leveraging your network on their behalf or advising them well.  Sequoia has been around for more than 40 years. You cannot get the returns that we have if you are just providing capital.

**Paul Graham:** The top VC funds have to be able to make up their own minds. They cannot follow everybody else because it’s everyone that follows them! Look at Sequoia. Sequoia is very disciplined. This is not a bunch of B-school frat boys who are screening founders for guys who look like Larry and Sergey. Sequoia prepares careful research documents on prospective investments…

**Roelof Botha:** But _succinct_ research. If you make or believe you need a 100-page document, you miss the forest for trees. You must be able to condense it into 3-5 pages. If there can be no succinct description, there’s probably nothing there.

**Peter Thiel:** Even within an individual business, there is probably a sort of power law as to what’s going to drive it. It’s troubling if a startup insists that it’s going to make money in many different ways. The power law distribution on revenues says that one source of revenue will dominate everything else. Maybe you don’t know what that particular source is yet. But it’s certainly worth thinking about. Making money with A is key. Making money with A through E is terrifying, from an investor’s perspective. 

**Roelof Botha:** LinkedIn is exception that proves the rule there. It had 3 revenue streams that are pretty equal. No one else really has that. At least it’s very unusual.

  
><span>

**Peter Thiel:** Do Y-Combinator companies follow a power law distribution? 

**Paul Graham:** Yes. They’re very power law.

**Peter Thiel:** Incubators can be tricky. Max Levchin started one. It had a really long cycle—maybe even a year-long cycle. That made for some crazy intercompany dynamics. All these people start in similar boats but, because of the power law dynamic, end up in very different ships. The perceptions are quite jarring. What happens with different people as they reach these different stages can be very complicated.

**Roelof Botha:** People don’t always appreciate or understand rapid increases in value when businesses take off. They underestimate the massive asymmetry of returns. They hear that a company has joined the billion-dollar club and are perplexed because only 6 months ago, it was worth $200m. The alternative to understanding the exponential growth is believing that Silicon Valley VCs have gone crazy.

**Peter Thiel:** PayPal’s most successful up round resulted in a 5x increase in valuation. But it was pitched in a forward-looking context. It wasn’t about taking _x _and multiplying by 5. The narrative was that the valuation made sense because of the promising future ahead. The real value is always in the future. Absent a very specific future you can point to, people anchor to a very specific past. And that is where you get the pushback of: “How can it possibly be worth 5x what it was 3 months ago?”

**Paul Graham:** You could even say that the whole world is increasingly taking power law shape. People are broken into so many different camps now. If everyone were forced to work for 1 of 10 GM-like companies—maybe like Japan—it would straighten the power law curve and make it taught. Distributions would be clustered together because everyone is bound together. But when you have lots of slack and people break apart, extremes form. And you can bet on this trend continuing in the future.

**Roelof Botha:** One thing that people struggle with is the notion that these massive companies can be built very quickly, often seemingly overnight. In the early PayPal days, there were perhaps 300 million internet users. Now there are 2 billion. We have more mobile phones. We have cloud computing. There are so many ways to grow. Consequently there is a qualitative difference in one’s ability to have such a huge impact as an entrepreneur.

 

**Question from audience**: Do up, flat, and down rounds reflect power law distributions, or specifically where a company will fall on the distribution?

**Peter Thiel:** First, it’s important to note that when you join or start a startup, you’re investing in it. All your eggs are in that basket. But because of the power law distribution, your investors aren’t in a radically different place than you are. In a sense, VCs’ eggs are in your basket too. They have a few more baskets than you do, but again, because of the power law, not many. VC isn’t private equity where you shoot for consistent 2x or 3x returns.

One way to rephrase the question would be: is there a market inefficiency here? My backtesting claim is that one should do a full pro rata investment whenever one of your companies does an up rounds led by a smart VC.

**Roelof Botha:** I don’t have the data you’re looking at, but my intuition is that’s true. But only for the best VCs. Where the VC leading the round isn’t as smart or as trusted, the reverse can happen. Companies can end up with too much cash. They might have a 15-month runway. They get complacent and there’s not enough critical thinking. Things go bump at 9 months and it turns into a crisis. And then no one wants to invest more.

**Peter Thiel:** Even factoring in dilution, you tend to do quite well if every round is an up round. But even a single down round tends to be disastrous, mainly because it destroys relationships among all the relevant players. If you’re going to go with a not-so-intelligent investor who gives you a really huge valuation, you should take it only if it’s the last money you’re going to take.

 

**Question from audience:**  Does the shape of the distribution curve change or depend on the time or stage of the investment?

**Peter Thiel:** The curve is fairly fractal-esque all the way up. Founders Fund tries to invest in 7 to 10 companies per fund. The goal is to get to 10x return. How hard is it to get to 10x? It’s about as hard to get from $10m to $100m as it is from $100m to $1bn or $1bn to 10bn. Taking $100bn to a trillion is harder because the world isn’t that big. Apple’s market cap is $500bn. Microsoft’s is $250bn. There’s a pretty incredible power law all the way up.

The same is probably true on angel level. The angel investment landscape is sort of saturated for angel piece, especially now with the JOBS Act. But some would say that angel investors are less aware of power law dynamics than other people are, and so they tend to overestimate a given company as a result. 

**Roelof Botha:** There is a 50% mortality rate for venture-funded businesses. Think about that curve. Half of it goes to zero. There are some growth investments—later stage investments—which makes things less drastic. Some people try for 3-5x returns with a very low mortality rate. But even that VC model is still subject to power law. The curve is just not as steep.

 

**Question from audience:**  What if your business is just worth $50m and you can’t grow it any more?

**Paul Graham:** That assumption is nonsense. Grow it, if you want to. There’s no such thing as an immutable company size. Companies are not intrinsically or inherently limited like that. Look at Microsoft or Apple. They started out making some small thing. Then they scaled and branched out as they succeeded.

To be clear, it’s totally cool to have low aspirations. If you just want to make a $50m company, that’s great. Just don’t take venture capital, or at least don’t tell VCs about your plans!

**Peter Thiel:** It would raise a big red flag if you were to put a slide at the end of your deck that says you’re looking to sell the company for $20m in 18 months.

 

**Question from audience:**  What happens when you take out a bunch of rounds and things don’t go well and your current investors don’t want to put in more?

**Paul Graham:** In that scenario you are essentially wasting one of your investors’ board seats. Their opportunity cost of having you going sideways is very high. People can only stand being on a dozen or so boards. Any more than that and they go crazy. So they’ll try to get you sold.

**Peter Thiel:** Such unequal outcomes produces another cost of ending up on multiple boards. There are big reputational costs to just switching boards. So there is a big disconnect between public branding—narratives about how VCs pay loving attention to all their companies and treat them all equally—and the reality of the power law. 

**Roelof Botha:** And it can be even worse than that; the problem companies can actually take up _more_ of your time than the successful ones.

**Peter Thiel:** That is a perverse misallocation. There are differing perspectives on what to do in these situations. At one extreme, you just write checks and check out. At the other, you help whoever needs it as much as they need it. The unspoken truth is that the best way to make money might be to promise everyone help but then actually help the ones who are going to provide the best returns.

 

**Question from audience:** Bill Gates took no funding and he ended up with a large piece of Microsoft. If a startup can bootstrap instead of take venture capital, what should it do?

**Paul Graham:** VC lets you borrow against future growth. You could wait until your revenues are high enough to fund _x_. But, if you’re good enough, someone will give you money to do _x _now. If there’s competition, you may need to do _x_ quickly. So if you don’t screw things up, VC can often help you a great deal. 

**Roelof Botha:** We would not be in the business if it were just writing checks. The entrepreneurs make it happen; they are the ones building the companies. But the board and VCs can roll up their sleeves, offer counsel, and assist as needed. They can be there for the entrepreneurs. We shouldn’t overstate the importance of that, but neither should we dismiss it.

**Paul Graham:** Just being backed by a big VC firm will help you open lots of doors. It will help considerably with your hiring.

**Peter Thiel:** If you’re doing something where you don’t need to move as quickly as possible, you might want to rethink taking venture funding. But if there’s any sort of winner-take-all dynamic—if there is a power law distribution at play, then you want VC. Giving up 25% of your business is worth it if it enables you to take over your industry.

 

**Question from audience:** Do Sequoia or other top-tier VC firms offer tougher term sheets to account for the extra value they provide? Is all the stuff about non-monetary value-add just overplayed? 

**Roelof Botha:** It’s not overplayed. It really is personal. Who are you getting in business with? Can you trust them? I wouldn’t send my brother to most VC firms. But some are great. You really have to get to know the people you might be working with. You’re essentially entering a long-term relationship.

Just look at you. There’s information contained in your Stanford degree. The signaling helps you quite a bit. The same is true if you’re backed by certain VCs. There’s a lot of value in the name, independent of things like making important introductions. And strategic direction is hard to pinpoint, but it can accumulate in many interesting and beneficial ways. Even if we don’t have the answers, we have probably seen similar problems before and we can help entrepreneurs think through the questions.

 

**Question from audience:**  Right now, entrepreneurs are trying to flip companies for $40m in 2 years or less. The incentive is to flip easy stuff instead of create hard technical stuff. What’s the cause and what’s the effect? Entrepreneur greed? VCs who don’t value technical innovation?

**Paul Graham:** I disagree with the premise that there’s a lack of innovation. $50m companies innovate. Mine did. We basically invented the web app. We were doing complex stuff in LISP when everyone else was doing CGI scripts. And, quite frankly, $50m is no small thing. We can’t _all _get bought for $1.5bn, after all…  [looks at Peter].

**Peter Thiel:** Let me rephrase the question: are VCs looking for quicker profits? Are we getting thinner companies that we should be?

**Paul Graham:** I don’t think investors have too much effect on what companies actually do. They don’t push back and say no, do this cool thing _x _instead of that dumb thing _y_. Of course, tons of people just try and imitate what they see and think is easy. Y-Combinator is probably going to be filtering out thousands of Instagram-like applications next cycle.

**Roelof Botha:** If someone came to me and I got the sense that he was trying to just flip a company quickly, I’d run. But most founders aren’t B-school finance mechanics who calculate exactly what space would be most profitable to enter. Most good founders are people solving problems that frustrate them. Google grew out of a research project stemming from frustration with AltaVista.

**Peter Thiel:** One strange corollary to the power curve dynamic is that the people who build the really great companies are usually hesitant to sell them. Almost necessarily that’s the case. And it’s not for lack of offers. Paradoxically, people who are heavily motivated by money are never the ones who make the most money in the power law world.

 

**Question from audience:** If the most money comes from people who aren’t trying to make the most money, how do you handle that paradox as a VC?

**Roelof Botha:** Consider a simple 2 x 2 matrix: on one axis you have easy to get along with founder, and not.  On the other, you have exceptional founder, and not. It’s easy to figure out which quadrant VCs make money backing.

 

**Question from audience:**  If the power law distribution is so extreme, how can Y-Combinator succeed?

**Paul Graham:** There is a very steep drop-off. Y Combinator essentially gets the first pick of a very good national and even international applicant pool.

**Peter Thiel:** I won’t come out as pro- or anti- Y Combinator. They do some things well and maybe some other things less well. But I will something anti-_not_-Y Combinator. If you go to incubator that’s not Y Combinator, that is perceived as negative credential. It’s like getting a degree at Berkeley. Okay. It’s not Stanford. You can a complicated story about how you had to do it because your parents had a big mortgage or something. But it’s a hard negative signal to get past. 

 

**Question from audience:**  Do you back founders or ideas?

**Paul Graham:** Founders. Ideas are just indicative of how the founders can think. We look for relentlessly resourceful people. That combination is key. Relentlessness alone is useful. You can relentlessly just bang your head against the wall. It’s better to be relentless in your search for a door, and then resourcefully walk through it. 

**Roelof Botha:** It is so rare to find people who can clearly and concisely identify a problem and formulate coherent approach to solve it.

**Peter Thiel:** Which is why it’s very important to drill down on the founding team.

**Roelof Botha:** You can discover a lot about founders by asking them about their choices. What are the key decisions you faced in your life and what did you decide? What were the alternatives? Why did you go to this school? Why did you move to this city?

**Paul Graham:** Another corollary to the power law is that it’s OK to be lame in a lot of ways, so long as you’re not lame in some really important ways. The Apple guys were crazy and really bad dressers. But they got importance of microprocessors. Larry and Sergey got that search was important.

**Peter Thiel:** Isaiah Berlin wrote an essay called “The Hedgehog and the Fox.” It revolved around a line from an ancient Greek poet: foxes know many little things, but hedgehogs know one big thing. People tend to think that foxes are best because they are nimble and have broad knowledge. But in business, it’s better to be a hedgehog if you have to choose between the two. But you should still try and know lots of little things too.

  
><span>

**Question from audience:**  You mentioned “smart VCs” in your backtesting example. Who are the smart VCs?

**Peter Thiel:** The usual suspects. Next question.

**Question from audience:**  What keeps you guys up at night? What do you fear most?

**Paul Graham:** I fear that something will come along that causes me personally to have to do a lot more work. What’s your greatest fear, Roelof? Andreessen Horowitz?

**Roelof Botha:**  Suffice it to say that you’re only as good as your next investment.

 

**Question from audience:**  Can entrepreneurs raise venture capital if they’ve raised and failed before? 

**Paul Graham:** Yes.

**Roelof Botha:** Max fell twice before PayPal, right? Here, it’s a myth that failure is stigmatized. In some places, such as France, that is true. Failure is looked down upon. But much less so in the U.S., and in Silicon Valley in particular.

**Peter Thiel:** One still shouldn’t take failure lightly, though. There is still a reasonably high cost of failure.

**Paul Graham:** It largely depends on _why _one failed, though. Dalton Caldwell got killed by the music business. Everyone knows that wasn’t his fault. It’s like getting shot by the mafia. You can’t be blamed for it.

**Roelof Botha:** Sometimes having experience with failed startups can make an entrepreneur even better. If they learn from it, maybe they get inspiration or insight for their next company. There are plenty of examples. But you should not fail for sake of failure, of course.

 

**Question from audience:**  Do you fund teams of 1? 

**Paul Graham:** Yes. Drew Houston was a team of one. We suggested that he find a co-founder. He did. It worked well.

**Peter Thiel:** A core founding team of two people with equal shares tends to work very well. Or sometimes it makes sense to have one brilliant founder that’s far and away above anyone else.

**Paul Graham:** Four is too many.

**Peter Thiel:** Think about co-founders from a power law perspective. Having one means giving up half the company. Having two means giving up 2/3. But if you pick the right people, it’s likely that the outcome will be more than 2x or 3x what it would’ve been without them. So co-founders work pretty well in power law world.

[![Creative Commons License][9]][10]

   [9]: http://i.creativecommons.org/l/by-nc-nd/3.0/88x31.png
   [10]: http://creativecommons.org/licenses/by-nc-nd/3.0/

Originally posted by [Blake Masters][11]. You can find the [set of class notes on his site][12]

   [11]:https://twitter.com/bgmasters
   [12]:http://blakemasters.tumblr.com/peter-thiels-cs183-startup/.
