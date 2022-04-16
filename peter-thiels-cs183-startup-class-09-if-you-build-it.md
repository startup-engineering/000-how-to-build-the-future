### [Peter Thiel's CS183: Startup - Class 9 Notes Essay][7]

   [7]: http://blakemasters.tumblr.com/post/22405055017/peter-thiels-cs183-startup-class-9-notes-essay

Here is an essay version of my class notes from Class 9 of CS183: Startup. Errors and omissions are my own. Credit for good stuff is Peter’s entirely. 

**_Class 9 Notes Essay—If You Build It, Will They Come?_**

 **I. Definitions** 

Distribution is something of a catchall term. It essentially refers to how you get a product out to consumers. More generally, it can refer to how you spread the message about your company. Compared to other components that people generally recognize are important, distribution gets the short shift. People understand that team, structure, and culture are important. Much energy is spent thinking about how to improve these pieces. Even things that are less widely understood—such as the idea that avoiding competition is usually better than competing—are discoverable and are often implemented in practice.

But for whatever reason, people do not get distribution. They tend to overlook it. It is the single topic whose importance people understand least. Even if you have an incredibly fantastic product, you still have to get it out to people. The engineering bias blinds people to this simple fact. The conventional thinking is that great products sell themselves; if you have great product, it will inevitably reach consumers. But nothing is further from the truth.

There are two closely related questions that are worth drilling down on. First is the simple question: how does one actually distribute a product? Second is the meta-level question: why is distribution so poorly understood? When you unpack these, you’ll find that the first question is underestimated or overlooked for the same reason that people fail to understand distribution itself.

The first thing to do is to dispel the belief that the best product always wins. There is a rich history of instances where the best product did not, in fact, win. Nikola Tesla invented the alternating current electrical supply system. It was, for a variety of reasons, technologically better than the direct current system that Thomas Edison developed. Tesla was the better scientist. But Edison was the better businessman, and he went on to start GE. Interestingly, Tesla later developed the idea of radio transmission. But Marconi took it from him and then won the Nobel Prize. Inspiration isn’t all that counts. The best product may not win. 

**II. The Mathematics of Distribution**

Before getting more abstract, it’s important to get a quantitative handle on distribution. The straightforward math uses the following metrics:

  * Customer lifetime value, or CLV
  * Average revenue per user (per month), or ARPU
  * Retention rate (monthly, decay function), or _r_
  * Average customer lifetime, which is 1 / (1-_r_)
  * Cost per customer acquisition, or CPA

CLV equals the product of ARPU, gross margin, and average customer lifetime.

The basic question is: is CLV greater or less than CPA? In a frictionless world, you build a great business if CLV > 0. In a world with some friction and uncertainty, you build a great business if CLV > CPA. 

Imagine that your company sells second-tier cell phone plans. Each customer is worth $40/month. Your average customer lifetime is 24 months. A customer’s lifetime revenue is thus $960. If you have a 40% gross margin, the customer’s lifetime value is $384. You’re in good shape if it costs less than $384 to acquire that customer.

One helpful way to think about distribution is to realize that different kinds of customers have very different acquisition costs. You build and scale your operation based on what kinds of things you’re selling. 

On one extreme, you have very thin, inexpensive products, such as cheap steak knives. You target individual consumers. Your sales are a couple of dollars each. Your approach to distribution is some combination of advertising and viral marketing—hoping that the knives “catch on.”

Things are fundamentally different if you’re selling a larger package of goods or services that costs, say, $10,000. You’re probably targeting small businesses. You try to market your product accordingly. 

At the other extreme, you’re selling to big businesses or governments. Maybe your sales are $1m or $50m each. As the unit value of each sale goes up, there is necessarily a shift towards more people-intensive processes. Your approach to these kinds of sales must be to utilize salespeople and business development people, who are basically just fancy salespeople who do three martini lunches and work on complex deals.

**III. The Strangeness of Distribution   **

**A. Fact versus Sales Pitch**

People say it all the time: this product is so good that it sells itself. This is almost never true. These people are lying, either to themselves, to others, or both. But why do they lie? The straightforward answer is that they are trying to convince other people that their product is, in fact, good.  They do not want to say “our product is so bad that it takes the best salespeople in the world to convince people to buy it.” So one should always evaluate such claims carefully. Is it an empirical fact that product _x _sells itself? Or is that a sales pitch? 

The truth is that selling things—whether we’re talking about advertising, mass marketing, cookie-cutter sales, or complex sales—is not a purely rational enterprise. It is not just about perfect information sharing, where you simply provide prospective customers with all the relevant information that they then use to make dispassionate, rational decisions. There is much stranger stuff at work here.

Consider advertising for a moment. About 610,000 people work in the U.S. ad industry. It’s a $95bn market. Advertising matters because it works. There are competing products on the market. You have preferences about many of them. Those preferences are probably shaped by advertising. If you deny this it’s because you already know the “right” answer: your preferences are authentic, and ads don’t work on you. Advertising only works on other people. But exactly how that’s true for everybody in the world is a strange question indeed. And there’s a self-referential problem too, since the ad industry has had to—and did—convince the people who buy ads that advertising actually works.

_If you buy Levis jeans, your apartment blows up. Or is it the other way around?_ 

_Comparisons to price or how fast computers work? No. Something strange is going on._

The U.S. sales industry is even bigger than advertising. Some 3.2 million people are in sales. It’s a $450bn industry. And people can get paid pretty well. A software engineer at Oracle with 4-6 years experiences gets a $105k salary and an $8k bonus. But a sales manager with 4-6 years experiences gets $112k and a $103k bonus. The situation is very much the same at Google, which claims to be extremely engineering driven; at a $96k base, $86k in commissions, and a $40k bonus, Google salespeople earn quite a bit more than their engineering counterparts. This doesn’t mean everyone should go into sales. But people who are good at it do quite well. 

_Self-referential version of sales question.   _

**B. Salesman as Actor**

The big question about sales is whether all salesmen are really just actors of one sort or another. We are culturally biased to think of salespeople as classically untrustworthy, and unreliable. The used car dealer is the archetypical example. Marc Andreessen has noted that most engineers underestimate the sales side of things because they are very truth-oriented people. In engineering, something either works or it doesn’t. The surface appearance is irrelevant. So engineers tend to view attempts to change surface appearance of things—that is, sales—as fundamentally dishonest.

What is tricky about sales is that, while we know that it exists all around us, it’s not always obvious who the real salesperson is. Tom Sawyer convinced all the kids on the block to whitewash the fence for him. None of those neighborhood kids recognized the sale. The game hasn’t changed. And that’s why that story rings true today.

![][8]

   [8]: http://media.tumblr.com/tumblr_m3ir0fNO6w1qbb0b4.png

Look at the images above. Which of these people is a salesman? President Eisenhower? He doesn’t _look _like a salesman. The car dealer in the middle _does_ look like a salesman. So what about the guy on the right?

The guy on the right is Bill Gross, who founded IdeaLab, which was more or less the Y-Combinator of the late 1990s. IdeaLabs’ venture arm invested in PayPal. In late 2001, it hosted a fancy investor lunch in southern California. During the lunch, Gross turned to Peter Thiel and said something like:

> “I must congratulate you on doing a fantastic job building PayPal. My 14-year-old son is a very apathetic high school student and very much dislikes writing homework assignments. But he just wrote a beautiful e-mail to his friends about how PayPal was growing quickly, why they should sign up for it, and how they could take advantage of the referral structure that you put in place.”

On some level, this was a literary masterpiece. If nothing else, it was impressive for the many nested levels of conversation that were woven in. Other people were talking to other people about PayPal, possibly at infinite levels on down. The son was talking to other people about those people. Bill Gross was talking to his son. Then Gross was talking to Peter Thiel. And at the most opaque and important level, Gross was talking to the other investors at the table, tacitly playing up how smart he was for having invested in PayPal. The message is that sales is hidden. Advertising is hidden. It works best that way.

There’s always the question of how far one should push this. People push it pretty far. Pretty much anyone involved in any distribution role, be it sales, marketing, or advertising, should have job titles that have nothing to do with those things. The weak version of this is that sales people are account executives. A somewhat stronger version is that people trying to raise money are not I-bankers, but rather are in corporate development. Having a job title that’s different from what you actually do is an important move in the game. It goes to the question of how we don’t want to admit that we’re being sold to. There’s something about the process that’s not strictly rational.

To think through how to come to an organizing principle for a company’s distribution, consider a 2 x 2 matrix. One axis is product: it either sells itself, or it needs selling. The other axis is team: you either have no sales effort, or a strong one.

Consider the quadrants:

  *  Product sells itself, no sales effort. _Does not exist_.
  * Product needs selling, no sales effort. _You have no revenue_.
  * Product needs selling, strong sales piece. _This is a sales-driven company_.
  * Product sells itself, strong sales piece. _This is ideal_. 

**C. Engineering versus Sales**

Engineering is transparent. It’s hard. You could say it’s transparent in its hardness. It is fairly easy evaluate how good someone is. Are they a good coder? An ubercoder? Things are different with sales. Sales isn’t very transparent at all. We are tempted to lump all salespeople in with vacuum cleaner salesmen, but really there is a whole set of gradations. There are amateurs, mediocrities, experts, masters, and even grandmasters. There is a wide range that exists, but can be hard to pin down. 

A good analogy to the engineer vs. sales dynamic is experts vs. politicians. If you work at a big company, you have two choices. You can become expert in something, like, say, international tax accounting. It’s specialized and really hard. It’s also transparent in that it’s clear whether you’re actually an expert or not.

The other choice is to be a politician. These people get ahead by being nice to others and getting everyone to like them. Both expert and politician can be successful trajectories. But what tends to happen is that people choose to become politicians rather than experts because it seems easier. Politicians _seem _like average people, so average people simply assume that they can do the same thing.

So too in engineering vs. sales. Top salespeople get paid extremely well. But average salespeople don’t, really. And there are lots of below average salesmen. The failed salesman has even become something of a literary motif in American fiction. One can’t help but wonder about the prehistory to all these books. It may not have been all that different from what we see today. People probably thought sales was easy and undifferentiated. So they tried it and learned their error the hard way. The really good politicians are much better than you think. Great salespeople are much better than you think. But it’s always deeply hidden. In a sense, probably every President of the United States was first and foremost a salesman in disguise.

**IV.  Methods of distribution**

To succeed, every business has to have a powerful, effective way to distribute its product. Great distribution can give you a terminal monopoly, even if your product is undifferentiated. The converse is that product differentiation itself doesn’t get you anywhere. Nikola Tesla went nowhere because he didn’t nail distribution. But understanding the critical importance of distribution is only half the battle; a company’s ideal distribution effort depends on many specific things that are unique to its business. Just like every great tech company has a good, unique product, they’ve all found unique and extremely effective distribution angles too.

**A. Complex Sales**

One example is SpaceX, which is the rocket company started by Elon Musk from PayPal. The SpaceX team has been working on their rocketry systems in Southern California for about 8 years now. Their basic vision is to be the first to send a manned mission to Mars. They went about doing this in a phenomenal way. Time constrains make it impossible to relate all of Elon’s many great sales victories. But if you don’t believe that sales grandmasters exist, you haven’t met Elon. He managed to get $500m in government grants for building rockets, which is SpaceX, and also for building electric cars, which is done by his other company, Tesla.

That was an even bigger deal than it may initially seem. SpaceX has been busy knocking out dramatically inferior rocket technologies for the past 10 years, but it’s been a very tricky, complicated process. The company has about 2,000 people. But the U.S. Space Industry has close to 500,000 people, all distributed about evenly over the 50 states. It’s hard to overstate the extent of the massive congressional lobbying that goes to keeping the other space companies—almost the entire industry—alive. Things are designed to be expensive, and SpaceX’s mission is to cut launch costs by 90%. To get where it is now—and to get to Mars later—SpaceX basically took on the entire U.S. House of Representatives and Senate. And so far, it seems to be winning. It’s going to launch a rocket next week. If all doesn’t go well, you’ll certainly here about it. But when things go well, you can predict the general response: move along, nothing to see here, these aren’t the rockets we’re looking for.

Palantir also has a unique distribution setup. They do government sales and sales to large financial institutions. Deals tend to range from $1m to $100m. But they don’t have any salespeople—that is, they don’t employ “salespeople.” Instead they have “forward deployed engineers” and a globetrotting CEO who spends 25 or 26 days each month traveling to build relationships and sell the product firsthand. Some argue that the traveling CEO-salesman model isn’t scalable. It’s a fair point, but the counterpoint is that, at that level, people really only want to talk to the CEO. You certainly can’t just hire army of salespeople, because that sounds bad.  So you have forward deployed engineers double up in a sales capacity.  Just don’t call them salespeople.

Knewton is a Founders Fund portfolio company that develops adaptive learning technology. Its distribution challenge was to figure out a way to sell to big educational institutions. There seemed to be no direct way to knock out existing players in the industry. You would have to take the disruptive sales route where you just try to come in and outsell the existing companies. But much easier is to find a non-disruptive model. So Newton teamed up with Pearson, the big textbook company. Without that partnership, Knewton figured it would just be fighting the competition in the same way at every school it approached, and ultimately it’d just lose. 

**B. Somewhat Smaller Sales**

As we move from big, complex sales to sales, the basic difference is that the sales process involves a ticket cost of $10k-100k per deal. Things are more cookie cutter. You have to figure out how to build a scalable process and build out a sales team to get a large number of people to buy the product. David Sacks was a product guy at PayPal and went on to found Yammer. At PayPal, he was vehemently anti-sales and anti-BD. His classic lines were: “Networking is _not working!_” and “People doing networking are not _working!_” But at Yammer, Sacks found that he had to embrace sales and build out a scalable distribution system. Things are different, he says, because now the sales people report to him. Because of its focus on distribution, Yammer was able to hire away one of the top people from SalesForce to run its sales team. 

ZocDoc is a doctor referral service. It’s kind of a classic internet business; they are trying to get doctors’ offices to sign up for the service at a cost of $250/month. Growth is intensively sales-driven, and ZocDoc does market-by-market launches. There is even a whole internal team of recruiters who do nothing else but try to recruit new salespeople. Toward the lower end of things—and $250 per month per customer is getting there—things get more transactional and marginal. 

**C. The Missing Middle**

There is a fairly serious structural market problem that’s worth addressing. On the right side of the distribution spectrum you have larger ticket items where you can have an actual person driving the sale. This is Palantir and SpaceX. On the extreme left-hand side of the spectrum you have mass marketing, advertising, and the like.   There is quite possibly a large zone in the middle in which _there’s actually no good distribution channel to reach customers_. This is true for most small businesses. You can’t really advertise. It wouldn’t make sense for ZocDoc to take out a TV commercial; since there’s no channel that only doctors watch, they’d be overpaying.  On the other hand, they can’t exactly hire a sales team that can go knock on every doctor’s door. And most doctors aren’t that technologically advanced, so internet marketing isn’t a perfect solution. If you can’t solve the distribution problem, your product doesn’t get sold—even if it’s a really great product.

The opposite side of this is that if you do figure out distribution—if you can get small businesses to buy your product—you may have a terminal monopoly business. Where distribution is a hard nut to crack, getting it right may be most of what you need. The classic example is Intuit. Small businesses needed accounting and tax software. Intuit managed to get it to them. Because it nailed distribution, it’s probably impossible for anyone to displace Intuit today. Microsoft understood the great value of Intuit’s distribution success when it tried to acquire Intuit. The Department of Justice struck down the deal, but the point is that the distribution piece largely explains Intuit’s durability and value.

**D. Marketing**

Further to the left on the distribution spectrum is marketing. The key question here is how can one advertise in a differentiated way. Marketing and advertising are very creative industries. But they’re also quite competitive. In order to really succeed, you have to be doing something that others haven’t done? To gain a significant advantage, your marketing strategy must be very hard to replicate.

Advertising used to be a much more iconic and valued industry. In the 1950s and ‘60s it was iconic and cutting edge. Think Mad Men. Or think Cary Grant, who, in the classic movie North by Northwest, played the classic advertising executive who is cool enough to be mistaken for a spy. Advertising and espionage were debonair enterprises, roughly equal in glamorousness.

But it didn’t last. As the advertising industry developed in 70s and 80s, more people figured out ways to do it. Things became much more competitive. The market grew, but the entrants grew faster. Advertising no longer made as much money as they had been before. And ever since there has been a relentless, competitive push to figure out what works and then dial up the levers.

Advertising is tricky in the same way that sales is. The main problem is that, historically at least, you never quite know if your ads are working. John Wanamaker, who is billed as the father of advertising, had a line about this: “Half the money I spend on advertising is wasted: the trouble is I don’t know which half.” You may think your ad campaign is good. But is it? Or are the people who made your ad campaign just telling you that it’s good? Distinguishing between fact and sales pitch is hard.

In most ways, Priceline.com represents certain depressing decline of our society. It points to a very general failure. But one specific thing Priceline does well is its powerfully differentiated marketing, which makes it very hard to replicate or compete against. PayPal once staged a PR event where James Doohan—Scotty from Star Trek—would beam money using a palm pilot. It turned out to be a total flop. It turns out that Captain Kirk—that is, William Shatner—is in a league of his own. 

Advertising’s historical opaqueness is probably the core of why Google is so valuable; Google was the first company that enabled people to figure out whether advertising actually worked. You can look at all sort of metrics—CPM, CTR, CPC, RPC—and do straightforward calculations to determine your ROI. This knowledge is important because people are willing to pay a lot for advertising if it actually works. But in the pre-internet magazine age before Google, ad people never really had a clue about how they were doing.

Zynga has excelled at building on top of Google’s ad work. Everyone knows that Zynga experienced great viral growth as its games caught on. Less known is that they spent a lot of money on targeted advertising. That allowed them to monetize users much more aggressively than people thought possible. And then Zynga used that revenue to buy more targeted ads. Other gaming companies tried to do just viral growth—build games that had some social element at their core. But Zynga went beyond that distribution strategy and got a leg up by driving rapid growth with aggressive marketing. 

The standard bias on the internet is that advertising does not work. But that’s an interesting double standard. There are an awful lot of websites whose businesses model is ad sales. And then they turn around and say that they don’t actually believe ads are good way of getting customers. The Zynga experience shows that creatively rethinking the standard narrative can be quite lucrative. There is a lot of room for creativity in distribution strategy. 

**E. Viral Marketing**

Viral marketing is, of course, the classic distribution channel that people tend to think of as characteristic of Internet businesses. There are certainly ways to get it to work. But it’s easy to underestimate how hard it is to do that. William Shatner and James Doohan seemed similar. In fact they were a world apart. Salesmen may seem similar. But some get Cadillac’s, while others get steak knives. Still others get fired and end up as characters in novels.

**[**Section on viral marketing math excluded. You can learn about this stuff elsewhere, e.g. [here][9]. The gist is twofold:  first, viral cycle time is important. Shorter is better. Second, there is a metric called viral coefficient, and you need it to be > 1 to have viral growth.**]**

   [9]: http://www.forentrepreneurs.com/lessons-learnt-viral-marketing/ (viral math)

PayPal’s initial user base was 24 people. Each of those people worked at PayPal. They all knew that getting to viral growth was critical. Building in cash incentives for people to join and refer others did the trick. They hit viral growth of 7% daily—the user base essentially doubled every 10 days. If you can achieve that kind of growth and keep it up for 4-5 months, you have a user base of hundreds of thousands of people.

Certain segments grow fasters than others. The goal is to identify the most important segment first, so that anybody who enters the market after you has a hard time catching up. Consider Hotmail, for instance. It achieved viral growth by putting sign-up advertising at the bottom of each e-mail in their system. . Once they did that successfully, it was really hard to copy with the same success. Even if other providers did it and had similar growth curves, they were a whole segment behind. If you’re the first mover who is able to get a product to grow virally, no one else can catch up. Depending on how the exponential math shakes out in a particular case, the mover can often be the last mover as well.

PayPal is a classic example. The first high-growth segment was power buyers and power sellers on eBay. These people bought and sold a ton of stuff. The high velocity of money going through the system was linked to the virality of customer growth. By the time people understood how and why PayPal took off on eBay, it was too late for them to catch up. The eBay segment was locked in. And the virality in every other market segment—e.g. sending money to family overseas—was much lower. Money simply didn’t move as fast in those segments. Capturing segment one and making your would-be competitors scramble to think about second and third-best segments is key.

Dropbox is another good example of a very successful company that depended on viral growth. Pinterest may be as well. It’s sort of hard to tell at this point. Is Pinterest actually good? Or is it a fad? Will it become a ghost town that no one uses? It’s not entirely clear. But it has certainly enjoyed exponential growth.

Marketing people can’t do viral marketing. You don’t just build a product and then choose viral marketing. There is no viral marketing add-on. Anyone who advocates viral marketing in this way is wrong and lazy. People romanticize it because, if you do it right, you don’t have to spend money on ads or salespeople. _But viral marketing requires that the product’s core use case must be inherently viral_. Dropbox, for example, let’s people share files. Implicit is that there’s someone—a potential new user—to share with. Spotify does this with its social music angle. As people use the product, they encourage other people to use it as well. But it’s not just a “tell your friends” button that you can add-on post-product.

**F. The Power Law Strikes Again**

We have seen how startup outcomes and VC performance follow a power law. Some turn out to be a lot better than others. People tend to underestimate how extreme the differences are because our generally egalitarian society is always telling us that people are essentially the same.

We’ve also heard Roelof Botha explain that LinkedIn was the exception that proves the rule that companies do not have multiple revenue streams of equal magnitude. The same is true for distribution, and exceptions are rare. Just as it’s a mistake to think that you’ll have multiple equal revenue streams, you probably won’t have a bunch of equally good distribution strategies. Engineers frequently fall victim to this because they do not understand distribution. Since they don’t know what works, and haven’t thought about it, they try some sales, BD, advertising, and viral marketing—everything but the kitchen sink.

That is a really bad idea. It is very likely that one channel is optimal. Most businesses actually get zero distribution channels to work. Poor distribution—not product—is the number one cause of failure. If you can get even a single distribution channel to work, you have great business. If you try for several but don’t nail one, you’re finished. So it’s worth thinking really hard about finding the single best distribution channel. If you are an enterprise software company with a sales team, your key strategic question is: who are the people who are most likely to buy the product? That will help you close in on a good channel. What you want to avoid is not thinking hard about which customers are going to buy it and just sending your sales team out to talk to everybody.

Distribution isn’t just about getting your product to users. It’s also about selling your company to employees and investors. The familiar anti-distribution theory is: the product is so good it sells itself. That, again, is simply wrong. But it’s also important to avoid the employee version: this company is so good, people will be clamoring to join it. The investor version—this investment is so great, they’ll be banging down our door to invest—is equally dangerous. When these things seem to happen, it’s worth remembering that _they almost never happen in a vacuum_. There is something else going on that may not be apparent on the surface.

**G. PR and Media**

PR and Media add yet another layer to the distribution problem. How the message of your company gets distributed is worth thinking hard about. PR and media are very linked to this. It is a sketchy and very problematic world. But it’s also very important because we live in a society where people don’t usually have a rational idea of what they want. 

Consider an example from the VC world. It’s almost never the case that a company finds just one interested investor. There are always zero or several. But if the world were economically rational, this wouldn’t be true at all. In a perfectly rational world, you’d see single investor deals all the time. Shares would be priced at the marginal price where you get a single highest bidder—your most bullish prospective investor. If you get more than one person interested in investing, you’ve done it wrong and have underpriced yourself. But investors obviously aren’t rational and can’t all think for themselves. So you get either zero investors or many. 

It’s easy and intuitive for smart people to be suspicious of the media. For many years, Palantir had a very anti-media bias. But even if media exposure wasn’t critical for customers or business partners, it turned out to be very important for investors and employees. Prospective employees Google the companies they’re looking at. What they find or don’t matters, even if it’s just at the level of people’s parents saying “Palantir? Never heard of it. You should go work at Microsoft.” And you can’t just plug yourself on your own website; PR is the art of getting trusted, objective third parties to give you press.

**H. On Uncertainty**

It’s fairly difficult to overestimate how uncertain people are and how much they don’t know what they actually want. Of course, people usually insist that they _are_ certain. People trick themselves into believing that they do know what they want. At the obvious level, “Everyone wants what everyone wants” is just a meaningless tautology. But on another level, it describes the dynamic process in which people who have poorly formed demand functions just copy what they believe everyone else wants. That’s how the fashion world works, for instance.

**V. Distribution is Inescapable**

Engineers underestimate the problem of distribution. Since they wish it didn’t exist, sometimes they ignore it entirely. There’s a plot line from The Hitchhiker’s Guide to the Galaxy in which some imminent catastrophe required everybody to evacuate the planet. Three ships were to be sent into space. All the brilliant thinkers and leaders would take the A ship. All the salespeople, consultants, and executives would take the B ship. All the workers would take the C ship. The B ship gets launched first, and all the B passengers think that’s great because they’re self-important. What they don’t realize, of course, is that the imminent destruction story was just a trick. The A and C people just thought the B people were useless and shipped them off. And, as the story goes, the B ship landed on Earth.

So maybe distribution shouldn’t matter in an idealized, fictional world. But it matters in this one. It can’t be ignored. The questions you must ask are: how big is the distribution problem? And can this business solve it?

We live in a society that’s big on authenticity. People insist that they make up their own minds. Ads don’t work on them. Everything they want, they want authentically. But when you drill down on all these people who claim to be authentic, you get a very weird sense that it’s all undifferentiated. Fashionable people all wear the same clothes.

Understanding this is key. You must appreciate that people can only show tip of the iceberg. Distribution works best when it’s hidden. Question is how big the iceberg is, and how you can leverage it. Every tech company has salespeople. If it doesn’t, there is no company. This is true even if it’s just you and a computer. Look around you. If you don’t see any salespeople, you are the salesperson.

Corporate development is important for the same reasons that distribution is important. Startups tend to focus—quite reasonably—on the initial scramble of getting their first angel or seed round. But once it scales beyond that—once a company is worth, say, $30m or more—you should have a full-time person whose job it is to do nothing but travel around the world and find prospective investors for your business. Engineers, by default, won’t do this. It’s probably true that if your company is good, investors will continue show up and you’ll have decent up rounds. But how much money are you leaving on the table?

Say your company could reasonably be valued at $300m. Valuation is as much art as it is science. At that range it can fluctuate by a ratio of 2:1. If you raise $50m at $300m, you give away 16% of the company. But if you raise that $50m at $500m, you give away 10%. A 6% delta is huge. So why not hire the best person you can and give them 1% of the company to make sure you capture that value?

A similar thing exists with employee hiring. It’s trickier to know what to do there. But traditional recruiters do not take the distribution problem seriously enough. They assume that people are always rational, and that by giving them information, people will make good decisions. That’s not true at all. And since the best people tend to make the best companies, the founders or one or two key senior people at any multimillion-dollar company should probably spend between 25% and 33% of their time identifying and attracting talent.

[![Creative Commons License][10]][11]

   [10]: http://i.creativecommons.org/l/by-nc-nd/3.0/88x31.png
   [11]: http://creativecommons.org/licenses/by-nc-nd/3.0/

Originally posted by [Blake Masters][12]. You can find the [set of class notes on his site][13]

   [12]:https://twitter.com/bgmasters
   [13]:http://blakemasters.tumblr.com/peter-thiels-cs183-startup/.

