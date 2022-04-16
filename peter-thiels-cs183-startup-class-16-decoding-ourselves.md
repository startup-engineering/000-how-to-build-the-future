### [Peter Thiel's CS183: Startup - Class 16 - Decoding Ourselves][7]

   [7]: http://blakemasters.tumblr.com/post/24253160557/peter-thiels-cs183-startup-class-16-decoding

He is an essay version of my class notes from Class 16 of CS183: Startup. Errors and omissions are mine. Thanks to [@1wu][8] for some supplementary notes!

   [8]: http://graphics.stanford.edu/~lwu2/ (L Wu)

Three guests joined the class for a conversation after Peter’s remarks:

  1. Brian Slingerland. Co-Founder, President & COO at Stem CentRx;
  2. Balaji S. Srinivasan, CTO of Counsyl; and
  3. Brian Frezza, Co-founder, Emerald Therapeutics

Credit for good stuff goes to them and Peter. I have tried to be accurate. But note that this is not a transcript of the conversation.

**_Class 16 Notes Essay—Decoding Ourselves_**

 **I. The Longevity Project**

How much longer can people actually live? It’s a very open ended question. It may not be very easy to answer at all. But there is a sense that biotech may be well positioned to try. Biotech, on the wake of the computer revolution, seems quite exciting if we think that a whole series of problems—e.g. cancer, aging, dying—is close to being solved.

[![][9]][10]

   [9]: http://media.tumblr.com/tumblr_m4zhar4qBe1qbb0b4.png
   [10]: http://puu.sh/yiyM

Even without the biotech revolution, life expectancy has been rising impressively. The rate has been something like 2.5% decade over decade. In the mid to late 19th century, expected lifespans were going up at a rate of 2.3 to 2.5 years with each passing decade. If you plot the data points corresponding to each country’s single demographic (typically women) with the longest life expectancy, you get a very straight line on a scattershot basis. This isn’t quite equivalent to Moore’s law, but it’s analogous. In 1840, life expectancy was just 45 or 46 years. For century and a half now, keeping people alive longer has been an exponentially harder problem.

[![][11]][12]

   [11]: http://media.tumblr.com/tumblr_m4zhepVOHF1qbb0b4.png
   [12]: http://puu.sh/yizy

To some extent, the U.S. has fallen a bit behind in the effort. Life expectancy here is several years below the global max. There are all sorts of idiosyncratic explanations for this; Americans eat bad food, are too inactive, etc. But a little U.S. lag notwithstanding, there has been a relentless trend upwards.

[![][13]][14]

   [13]: http://media.tumblr.com/tumblr_m4zhg1sFdZ1qbb0b4.png
   [14]: http://puu.sh/yizD

Another way to think about it is this: every day you survive, you add 5 of 6 hours to your life. That is a startling realization. The question is what happens next. Is the straight line going to continue? Slow down? Accelerate? Before 1840, life expectancy was pretty flat for thousands of years. Only recently has it really picked up. Whether this is a short burst that will stagnate or just the beginning of a fierce acceleration remains to be seen.

[![][15]][16]

   [15]: http://media.tumblr.com/tumblr_m4zhhjOCv31qbb0b4.png
   [16]: http://puu.sh/yizS

**II. Luck, Life, and Death**

**A. Death as Bad Luck**

In a sense, longevity is the opposite of bad luck. At the broadest level, you get into trouble when something unlucky happens to you. Think of everything that can go wrong. Maybe a piece of your DNA mutates and starts a cancer. Maybe you get run over by a car. Or maybe you get hit by an asteroid. There are many different unlucky things that could happen. So the question of longevity can be rephrased as the question of whether and to what extent luck can be overcome.

From the 17th to the mid-19th centuries, the prevailing view was that we _could_ overcome all these accidents. Francis Bacon’s _New Atlantis_ was the classic vision of an accident-free utopia. It was a _new _Atlantis because, unlike the old one that the Gods destroyed, new Atlanteans had complete mastery over nature. 

[![][17]][18]

   [17]: http://media.tumblr.com/tumblr_m4zhj7NPMC1qbb0b4.png
   [18]: http://puu.sh/yiA0

This view has been receding since about 1850. Luck and indeterminacy have become increasingly dominant as frameworks for thinking about the future. This shift was probably driven by the emergence of actuarial science and life insurance. When people started to map out the data, they realized that life and death could be reduced to probability functions. A 30-year-old has a 1 in 1000 chance of dying in given year. But at age 100 that chance is 50%.

If we run with this math for a bit, living forever becomes just a matter of solving a simple equation:

[![][19]][20]

   [19]: http://media.tumblr.com/tumblr_m4zhxgfMC51qbb0b4.png
   [20]: http://puu.sh/yiJa

Unchecked probabilistic thinking can be dangerous. It defeats one’s ability to shape the future. No County For Old Men captures this well; eventually, your luck runs out and you get shot in a deli in Texas. If everything is just a probability distribution, you have to resign to it. But that ignores your ability to think and avoid playing games that are too dependent on luck.

Random historical footnote: 1700, the claim that people could live forever seemed stronger than it would today, simply because there were people running around claiming to be 150 years old. Since record-keeping wasn’t always great back then, good salespeople could persuade others that they were, in fact, radically old. Today, of course, it’s easy to identify these longevity salesmen’s movies. If you’re 70 years old in early 18th century London, you’re perceived as kind of wretched and you get no special treatment. But if you’re 150 years old, that’s really something special. You might even get a pension from the King. 

**B. Shift to Determinacy?**

Can we move biology away from the realm of the statistical/probabilistic and toward being something that is determinate and solvable? 

It depends.

You can think of death as an accident. There are different kinds of accidents. You can lay these out on a spectrum, from microscopic accidents (genetic mutations) to macroscopic accidents (car crashes) to cosmic accidents (asteroid strikes). To solve the longevity problem completely, you have to get rid of all of these kinds of accidents. But there’s a sense in which certain macro and cosmic accidents are and will continue to be pretty probabilistic things. There is good reason to take those on later; if we can just get to the microscopic solution, the best estimates have people living to between 600 and 1,000 years.

[![][21]][22]

   [21]: http://media.tumblr.com/tumblr_m4zi14rgzQ1qbb0b4.png
   [22]: http://puu.sh/yiAR

**III. CS and Biology**

**A. Difficulty of the Problem**

Like death itself, modern drug discovery is probably too much a matter of luck. Scientists start with something like 10,000 different compounds. After an extensive screening process, those 10,000 are reduced to maybe 5 that might make it to Phase 3 testing. _Maybe_ 1 makes it through testing and is approved by the FDA. It is an extremely long and fairly random process. This is why starting a biotech company is usually a brutal undertaking. Most last 10 to 15 years. There’s little to no control along the way. What looks promising may not work. There’s no iteration or sense of progress. There is just a binary outcome at end of a largely stochastic process. You can work hard for 10 years and still not know if you’ve just wasted your time.

In Internet businesses, the basic rule is that the company succeeds if every round of financing is an up round. In biotech, it’s very hard to do that. Investors get tired. Things don’t work. Some biotech investors are so candid as to state that they don’t really care about valuations, since everything will get wiped out in their favor once a company has the inevitable down round. Why negotiate valuation if luck dominates everything?

To be fair, we must acknowledge that all the luck-driven, stats-driven processes that have dominated people’s thinking have worked pretty well over the last few decades. But that doesn’t necessarily mean that indeterminacy is sound practice. Its costs may be rising quickly. Perhaps we’ve found everything that is easy to find. If so, it will be hard to improve armed with nothing but further random processes. This is reflected in escalating development costs. It cost $100 million to develop a new drug in 1975. Today it costs $1.3 billion. Probably all life sciences investment funds have lost money. Biotech investment has been roughly as bad a cleantech.

[![][23]][24]

   [23]: http://media.tumblr.com/tumblr_m4zi9ytG0e1qbb0b4.png
   [24]: http://puu.sh/yiLX

**B. The Future of Biotech**

Drug discovery is fundamentally a search problem. The search space is extremely big. There are lots of possible compounds. An important question is thus whether we can use computer technology to reduce scope of luck. Can CS make biotech more determinative? At the most basic level, biological processes can be thought of as involving some quantum of luck in the face of irreversible degradation. Traditional therapeutics largely mirrors those processes. But computational processes are reversible. You can dive in and re-program things as necessary. So one big question is the extent to which biological problems can be reduced to computer problems?

[![][25]][26]

   [25]: http://media.tumblr.com/tumblr_m4zibgYSpk1qbb0b4.png
   [26]: http://puu.sh/yiBD

The cost of DNA sequencing is falling rapidly. It cost $500 million to sequence a genome in 2000. Now that’s down to something like $5,000. Within a year or two, it will probably cost $1,000. The question is whether we can do as much as people have been assuming we can with all the information this will yield.

![][27]

   [27]: http://media.tumblr.com/tumblr_m4zidfCyGF1qbb0b4.png

The Human Genome Project was seen as incredibly revolutionary in late 1990s. But it hasn’t quite lived up to the hype. Perhaps it was all too early or too costly. But the second cut may be that it’s because the main problem is not a sequencing problem at all. The biggest problem may be that we just don’t know what to do with the data. Exactly how much of biology is computational is still an open question.

![][28]

   [28]: http://media.tumblr.com/tumblr_m4zils9PSc1qbb0b4.jpg

**IV. Examples**

We’ll highlight and then have a discussion with people from 3 companies who are doing very interesting things in biotech: Stem CentRx, Counsyl, and Emerald Therapeutics.

[![][29]][30]

   [29]: http://media.tumblr.com/tumblr_m4zif6vmA01qbb0b4.png
   [30]: http://puu.sh/yiCl

Of these 3, Stem CentRx is the closest to traditional biotech. But there is still a heavy computational piece to it. The basic goal is to cure all cancer. Their claim is that cancers have stem cells that are very different from core cancer cells. This stem-cell subset drives cancer/tumor growth. So they aim to target the stem cells and thereby knock out the cancer.

Backing up a step, the problem is that chemotherapy can be really ineffective at threating cancer. It is very hard to get chemo dosages exactly right. Too low a dosage is ineffective at stopping the cancer. Too high a dosage kills the patient along with the cancer. So if you can identify the subset of cancerous cells that are driving the growth and target those cells precisely, chemotherapy would be much less destructive and considerably more effective. So far, Stem CentRx’s studies on mice have been very promising. We should find out whether the approach works for human cancers over the next year or two.

Counsyl is a bioinformatics company whose goal is to become the default for pregnancy genetic screening. They have developed single simple test for the 100 or so genes that can be screened for inherited traits. They focus just on the Mendelian diseases, since beyond that it is currently very hard to know how more complicated genetic combinations work. So Counsyl has identified a tractable and well-defined subset of the problem. Today, Counsyl is involved in screening about 2% of all births in the U.S., and expects that figure to rise quite dramatically in coming years.

[![][31]][32]

   [31]: http://media.tumblr.com/tumblr_m4zigq7nsv1qbb0b4.png
   [32]: http://puu.sh/yiCF

Emerald Therapeutics is the most computational of these companies. The basic goal is to cure all viral infections by reprogramming cells, i.e. turning cells into code-based machines. The idea is to build a molecular machine that tags cells that contain viruses, and then to release a sequence that causes those cells to self-destruct. Emerald is in stealth mode, so we can’t say too much. But the high degree of paranoia for companies doing programmable anti-viral therapies is understandable. These are big secrets that play out over long time horizons, not web apps that have a 6-week window to take over the world.

So with that, we’ll have a discussion with Brian Slingerland of Stem CentRx, Balaji Srinivasan of Counsyl, and Brian Frezza of Emerald Therapeutics.

**V. Perspectives**

**Peter Thiel:** Marc Andreessen visited this class a few weeks ago. His claim about the Internet in the late ‘90s was that many of the ideas were right, but were just too early. Even if one agrees that next phase in biotech is about to start—things are going to get much more computational—how do you know that _now _is the right time? How do you know you’re not paddling too early?

**Balaji Srinivasan:** The sequencing of the genome is like the first packets being sent over ARPANET. It’s a proof of concept. This technology is happening, but it isn’t yet compelling. So there is a huge market if one can make something compelling enough for people to actually go and get a genome sequenced. It’s like e-mail or word processing. Initially these things were uncomfortable. But when they become demonstrably useful, people leave their comfort zones and adopt them. Pregnancy testing is a major on ramp. People find it important to make sure their children are as healthy as possible. And then there is likely to be tons of positive things that can be done with the data beyond that.

**Peter Thiel:** So the question is how you can overcome pervasive fear of getting genome sequencing? And the answer is: “Do it for the kids?”

**Balaji Srinivasan:** Yes. No one spends $1000 to get computer so they can use Twitter. But once you have computer, there is zero marginal cost to use Twitter. So solving the install problem is the first step. Empirically, we’re starting to see very strong adoption. So we are confident that we can solve the install problem. 

**Peter Thiel:** Tackling the cancer problem is exciting but also worrisome at the same time. It’s an old problem. Nixon said in 1970 that we’d win the War on Cancer by ’76. People have been working on it for 40 years. So while we’re 40 years closer to a solution, it also seems farther away than ever. Doesn’t the fact that it’s taken so long mean that it’s an incredibly hard problem that won’t be solved soon?

**Brian Slingerland:** People have largely followed the same path over the past 40 years. The usual approach to cancer is to carpet bomb it with chemotherapy or the like. The approaches that have been attempted are remarkably similar. So we decided to take really different path. 40 years of failures have taught us something important. The endpoint that everyone focuses on is therapeutic efficacy measured by tumor shrinkage. But this isn’t the best metric; tumors can shrink and then come back. Focusing on shrinkage may lead to attacking the wrong cells. Embracing bioinformatics helps us illuminate better approaches. So we disagree that the problem won’t be solved soon; we strongly believe that we have a very good chance of doing just that.

**Brian Frezza:** Half of the timing question is taken care of for us; we’re certainly not too late, since viruses still exist. So are we too early? I don’t think so. People’s perspective on healthcare development is quite different from reality. Industry players tend to be very paranoid and secretive until they have a product to release. People discount that quite a bit, since they just pay attention to what is brought to market and when. What most people see at any given point was started decades before they even thought about it.

Biotech got quite a burst in late 70s early 80s, with new recombinant DNA and molecular biology techniques. Genentech led the way from the late 70s to the early 80s. Nine of the 10 biggest American biotech companies were founded during this really short time. Their technology came out some 7-8 years later. And that was the window; not very many integrated biotech companies have emerged since then. There was a certain amount of stuff to find. People found it. And before Genentech, the paradigm was pharma, not biotech. _That_ window (becoming an integrated pharmaceutical company) had been closed for about 30 years before Genentech.

So the bet is that while the traditional biotech window may be closed, the comp bio window is just opening. Whoever gets in during that window gets installed. There are enormous monopoly barriers to getting to market. Here, first mover advantage often becomes last mover advantage. Imagine if IE or Chrome had to go through clinical trials just to get to market. It would be much harder to get in the game. So whoever manages to develop great technology and get it out first is in good shape. 

**Peter Thiel:** Talk about your corporate strategy. Even if your technology works, how do you distribute it?

**Balaji Srinivasan:** If you think of drugs, biotech, and now genomics as qualitatively different entities, you’ll see that genomics companies can do things quite differently. Genomics is much more computational than pharma or traditional biotech. With molecular diagnostics—but unlike traditional therapeutics—once you’ve assayed a sample, you’re on info superhighway. Internet rules apply. You can go from conception to product and sales within 15-18 months. It’s not quite as fast as Internet businesses. But it’s considerably faster than the 7-8 years it takes in biotech. In the early ‘90s there was an opening for web 1.0. In the late ‘90s there was the web 2.0 window. Now it’s genomics. We think that bio should just be sensors and gathering data. Everything else should be done at the command line.

**Brian Slingerland:** Stem CentRx has more of a traditional biotech process. We spent 3 years on the proof of concept phase. Now that we’ve finished all the efficacy studies in cancers in mice, we are in full-blown drug development mode. This process can be accelerated by adopting best practices from tech culture. It’s like SpaceX; if the competition is so screwed up, you can radically improve things by cutting bureaucracy and taking on a Silicon Valley culture. 

**Brian Frezza:** We are creating a platform, not an isolated product. We create infrastructure for all sorts of future antiviral technologies. So being able to handle the science in a routine and scalable way is key. The culture is an important part too. Even though we have PhD organic chemists and molecular biologists, we shoot for a hardcore tech startup culture. We automate processes in the lab using advanced robotics. We use git to track our lab notebooks. We write a ton of software. We are the first movers in our space, and we’re trying to move very quickly, but we're also building a platform that's designed to scale exponentially.

**Peter Thiel:** How do you know that there isn’t someone else secretly pursuing the same strategy? And if you’re confident as to what other people are or aren’t doing, how do you know that they don’t know about you and that _your _secrecy is working?

**Balaji Srinivasan:** It’s like the Rumsfeld quip: there are known unknowns. Ultimately we think most people miss the key secrets in health industry because they are so caught up in the status quo that they actually can’t think their way to good solutions. Contrast the healthcare industry with the fitness industry. Ultimately, your fitness is your responsibility. You can join good gyms or get personal trainers. All that’s great. But the buck stops with you—_you _have to take the initiative. But consider how that initiative plays out in healthcare. If you come to a doctor’s appointment wanting to talk about something you’ve researched, doctors get pissed. You are either undermining their authority or you’re an idiot. But that’s odd; you are with your body for a lifetime, whereas the doctor is with you for 20 minutes each year. The one area of medicine that works—fitness—operates orthogonally to the rest of medicine in practice.

When these systems get build up, it’s very hard to clear away the overhang. People have thought themselves out of thinking about non status quo solutions. Stuff that actually works is perceived as crazy.

**Brian Frezza:** One bad vestige of the biotech boom is what happened to patents. In pharma, traditionally compounds got patents. But in biotech, general techniques became patentable. Genentech, for example, managed to patent recombinant antibodies as a general concept . So biotech is littered with really broad patents. Some biotech companies literally generate millions in revenue just from patent licensing; they produce no drugs at all. So it's best not to generate a large amount of public interest in new techniques you're developing if you don't want to encourage stray IP to accumulate.

Ultimately, you can’t prove a negative. It is distinctly possible that there is a Ruby Therapeutics out there that is doing the same thing we are. But we very much doubt it, given how unique what we're doing is. Even knowing that they may be out there, it still makes sense for both companies to stay quiet until you’re ready for revenue.

**Brian Slingerland:** There’s really no rush to spill the secret plans. This space is very much unlike fast-moving consumer Internet startups. Here, if you have something unique, you should nurse it. One good rule of thumb is to issue no press releases until you push a drug. That said, it’s a balancing act. Since our approach has been proven out and we’ll be moving to human trials, we are becoming a more public-facing company. No one wants to take a drug made by a stealth company with no info on its website. You just want to make sure that you don’t divulge too much too early. 

Of course, people should assume there are 10 companies coming after them. It’s always safe to assume that you have to work better and faster to come out ahead.

**Peter Thiel:** If you thought that a Ruby Therapeutics—or 10 different versions of them—was actually out there, wouldn’t it make sense to be more open and collaborate? And how do you recruit people if you’re so secretive? 

**Balaji Srinivasan:** In ecology, when you want to know how many species are in a jungle, you take a sample and project out. Sizing up the competition is a similar task. If you take a hard look at your network—search through the Silicon Valley part of the forest—and see no capital being deployed and no one working on the same problems, you can be reasonably confident that you’re alone. People would really have to come out of nowhere.

Personal referrals are very important for recruiting. We try and get each engineer to refer 2 people. 2^n scales very well. You get great people, but also get to stay under the radar.

**Peter Thiel:** That recruiting strategy has worked well in every company that I’ve been involved with. You have to keep a clear head about it. If you ask MBAs to refer talented people who are good to work with, you’ll get far too many recruits. But if you put the same question to engineers—and maybe it’s _their _friends who you really want to recruit—you may get a shocking silence because they are too shy. So you have to find a way to get them comfortable with referring people.

**Brian Frezza:** One strategy that works for that is to sit down with your engineers and go through their Facebook friends with them, one by one, and ask them who is good and who they’d like to work with. 

**Peter Thiel:** The bias for Silicon Valley entrepreneurs is to go work on a web or mobile app. Why should more people think about doing biotech/computational stuff instead?

**Balaji Srinivasan:** The thing to remember is that the next big thing won’t look like the last big thing. Search didn’t look like the desktop. Social didn’t look like search.

The human genome will never become obsolete. Mobile/local/social? It’s hard to say. Mobile seems to have a lot of growth ahead of it. So that’s at least a reasonable bet. Local? There’s not really a defensible advantage anymore. And social has been colonized. Flags have been planted.

Ultimately you simply have to care about what you’re doing. Another dating app really doesn’t matter. It’s hard to bleed/sweat/cry for. Meaningfulness is a big part of why people should think differently. And we think genomics is really meaningful.

**Brian Frezza:** Elon Musk is a master recruiter. The narrative is stark and simple:   
> “We don’t pay as well as Google. But this is the most exiting project you can work on in your life.” You want to attract the people who find that narrative attractive. People can always try to find a lottery ticket of a startup. But the satisfaction of creating a tech revolution is much bigger than what comes from just chasing dollars.<span>

**Brian Slingerland:** One reason that CS people may be ignoring biotech is that they think that they’ll be relegated to supporting roles. But that’s far from true at many biotech companies. CS people are at the very core of what we do at Stem CentRx. So if CS people have an interest in curing cancer or things like that, it’s certainly something they should think about. Have I mentioned that we’re hiring?

**Peter Thiel:** We usually say that advertising works best if it is hidden. But sometimes it actually works if it’s completely transparent. [laughter]

Being opaque can be so tiring. The standard wisdom in the VC world is: “If you want money, ask for advice. If you want advice, ask for money.” That game is exhausting. Sometimes it can be refreshing to hear someone say, “I really just want money.”

 

**Question from the audience: **[unintelligible]

**Peter Thiel: **I think this is basically just the regulatory question. So talk about regulatory risks and whatnot.

**Brian Slingerland:** The regulatory system is a necessary step at this point. There is very little upside for the FDA to approve drugs faster. And they get in lots of trouble if they approve things too quickly and a trial goes wrong. There is a lot of talk about doing trials in China or India right now. These expedited processes are certainly interesting. Perhaps people should think about them more. And how the FDA responds will be interesting as well.

**Peter Thiel:** It is very odd that the FDA has a bottleneck on _global_ drug development. There has to be some tipping point beyond which the U.S. no longer gets to dictate what drugs are developed in the entire world. Past that inflection point, the U.S. may have to compete with China on how quickly drugs can be developed. That could be a huge paradigm shift. So while things look pretty bad now, the future may be quite promising. SpaceX was very heavily regulated at first, but persevered and got through it. And the aero regulations have eased up in the last decade. So the sheer unfriendliness of the baseline could be a great opportunity.

**Question from the audience: **When you disclose your secret to prospective hires, do they try to use that knowledge as leverage to hold you up and negotiate more?

**Brian Frezza:** It hasn’t been a problem at all. VCs don’t sign NDAs, but job candidates will. And it would take years for anyone we talk with to replicate our technology on their own. 

**Question from the audience: **What role does HIPPA play in tech innovation?

**Balaji Srinivasan:** HIPAA could be seen as tech problem. How can we follow such and such standards, etc.

But it’s also an interesting genomics problem. A person’s genome provides a great deal of information about their relatives. On one hand, this data is private medical data. On the other hand, it’s inherently statistical and requires aggregation to do anything very useful with it. So the trick is to figure out how to do private aggregations. To get value out of your genome, you simply must allow some computation on it. The challenge is catalyzing this very important social shift toward becoming okay with that while preserving strong privacy controls. 

 

**Question from the audience: **Unlike the web, where you can get feedback in minutes, how do you know if you’re on the right track in computational biotech? 

**Brian Frezza:** We use physical models and actual validation experiments. We don’t just use statistical approaches. But our processes are internal. We don’t go outside and seek external validation. Just like Instagram doesn’t get outside people to come in and appraise its code base. You develop a plan and execute it internally. Sometimes you have a multi-year cycle to get data back. You just work as efficiently as possible to shorten cycle times.

**Balaji Srinivasan:** Slow iteration is not law of nature. Pharma and biotech usually move very slowly, but both have moved pretty fast at times. From 1920-1923 Insulin moved at the speed of software. Today, platforms like Heroku have greatly reduced iteration times. The question is whether we can do that for biotech. Nowhere is it written in stone that you can’t go from conception to market in 18 months.

**Brian Frezza:** That depends very much on what you’re doing. Genentech was founded the same year as Apple was, in 1976. Building a platform and building infrastructure take time. There can be lots of overhead. Ancillary things can take longer than a single product lifecycle to accumulate.

 

**Question from the audience: **How does biotech VC compare to regular VC?

**Brian Slingerland:** We never did the classic venture capital route because VC is broken with respect biotech. Biotech VCs have all lost money. They usually have time horizons that are far too short. VCs that say they want biotech tend to really want products brought to market extremely quickly.

**Brian Frezza:** “Integrated drug platform” is an ominous phrase for VCs. More biotech VCs are focused on globalization than on real technical innovation. VCs typically found a company around a single compound and then pour a bunch of money into it to push it through the capital-intensive trial process. Most VCs not interested in multi-compound companies doing serious pre-clinical research.

 

**Question from the audience: **How useful are end-stage trials in trying to figure out how to cure cancer? Don’t you get inaccurate or just different genome data from terminal patients?

**Brian Slingerland:** Not being able to trial on earlier stage people is always a challenge. But our technology it is designed to apply to patients at all stages. All I can say is that our approach is stage agnostic for a variety of technical reasons. But generally speaking yours is a valid concern. That’s why traditional drugs that show initial progress often fizzle out in extended trials.

 

**Question from the audience: **What were some of your early struggles or challenges?

**Brian Frezza:** The amount of time it took to set up a lab was shockingly large. 100% of our time went into acquiring equipment, negotiating price, dealing with initialization failures, etc. We greatly underestimated the time required to get up and running because we were coming out of existing, well-supplied labs. It basically takes a whole year to get up and running. There’s just a huge difference from the computer/Internet tech world.

**Peter Thiel:** With Internet businesses, you can be up and running without doing hardly anything. At PayPal, the biggest interface with reality was that, on Max’s orders, people had to assemble their own desks. But Luke Nosek thought even that was too much. So he found a company called Delegate Everything, who dispatched this elderly woman handyperson out to assemble the desk for him so that he could do more work on the computer.

**Balaji Srinivasan:** Startups are always hard at the start. There are futons and ironing boards in the office. You have to rush to clean up for meetings. But maybe the hardest thing is just to get your foundation right and make sure you plan to build something valuable. You don’t have to do a science fair project at the start. You just have to do your analytical homework and make sure what you’re doing is valid. You have to give yourself the best chance of success as things unfold in the future.

* * *

[![Creative Commons License][33]][34]

   [33]: http://i.creativecommons.org/l/by-nc-nd/3.0/88x31.png
   [34]: http://creativecommons.org/licenses/by-nc-nd/3.0/

If you're interested in these companies, do check out [jobs.counsyl.com][35] and [stemcentrx.com/careers][36].

   [35]: http://jobs.counsyl.com/
   [36]: http://stemcentrx.com/careers.html (StemCentrix careers)

Originally posted by [Blake Masters][37]. You can find the [set of class notes on his site][38]

   [37]:https://twitter.com/bgmasters
   [38]:http://blakemasters.tumblr.com/peter-thiels-cs183-startup/.
