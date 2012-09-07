# 29

## An experimental summercamp call-in Show

### Panel

* Daniel Shaw ( @dshaw )
* Max Ogden ( @maxogden )
* James Halliday ( @substack )
* Visnu Pitiyanuvath ( @visnup )

Daniel Shaw: Hi everybody. Welcome to NodeUp 29. A very expirimental NodeUp.
 I am Daniel Shaw (dshaw). I'm joined by Max Ogden,

Max Ogden: What up, Internet?

Daniel Shaw: James Halliday (substack).

James Halliday: Hello.

Daniel Shaw: And Visnu!

Visnu Pitiyanuvath: Yo.

Daniel Shaw: Today we are sponsored by Clock and Node Knockout. And we're gonna
 do a NodeConf SummerCamp retrospective and a little bit of a preview, and then
 we're gonna do this crazy idea where we're gonna try and do call-ins and invite
 friends from the Internet to join us on the podcast. And nothing could go wrong
 with that, right? So, hopefully that'll be good. I had a few people email their
 stuff in. Make sure you get in touch with cfm on the IRCs. So let's get into
 summer camp last year. Summer camp kicked off last year with a bus ride out
 into the middle of nowhere.

Visnu Pitiyanuvath: Well, it's a preface actually. This will be the third year
 of doing events at Walker Creek Ranch.

Daniel Shaw: That's right!

Visnu Pitiyanuvath: So, the first year was actually not related. It was actually
 the Couch camp, for CouchDB. And at the time, Mikeal Rogers was working in
 Oakland. We actually took a bus from Oakland up there to Walker Creek Ranch,
 and it was amazing. It was the first time that most people had been to that
 ranch. It was the first time that there had been a Node event there. The venue
 itself is a summer camp for seventh graders.

Daniel Shaw: It's literally a summer camp. So you very much get the vibe of
 you're at a summer camp. If you've ever been to summer camp, you feel very much
 at home. You've got huts, and little tents, and it's crazy.

Visnu Pitiyanuvath: They warn you about bear and raccoons, coyote... This will
 be my third year up there. Not to sound too promotional about it, but it's the
 best thing in terms of tech-related conferences. I don't really think the word
 "conference" really does it justice.

Daniel Shaw: Yeah, totally.

Visnu Pitiyanuvath: But it's my favorite one of the year. I go to a ton of
 conferences. I only try to go to conferences that I think will be fun and
 interesting and give you a lot of social mixing time, and actually meet the
 community. I think nothing is really at the same level as Couch Camp. It's in
 an area that's completely gorgeous, natural beauty, you're isolated with a
 group of nerds that you mostly only interact with online most of the time, and
 there's no cellphone signal.

Daniel Shaw: (laughs) Yup, no cellphone signal, limited Internet, so you don't
 get pulled into work stuff or anything like that. You're just there discussing
 what's going on with your life and sharing. It's totally amazing.

Visnu Pitiyanuvath: It turns out substack is a pretty mean football player.

James Halliday: I dunno about that.

Daniel Shaw: Very friendly! (laughs)

Visnu Pitiyanuvath: He showed displays of dexterity unknown to the rest of
 humanity last year on the foursquare field as well. Foursquare.. court, I guess
 it would be? It's that. He's got the long arms, the low-angle shots, takin'
 people out.

Daniel Shaw: Very athletic. So we get to summer camp, and we have three times
 just hang out and meet everybody. There's a baseball league field, and we
 played kickball and foursquare. What the hell is foursquare? We're not talking
 about when everybody checks in with an app...

Visnu Pitiyanuvath: We should mention -

James Halliday: It's a playground game. In a lot of American elementary and
 middle schools there's these squares, and there's four of them on the
 pavement. Kids just get a cheap bouncy ball for their recess time, just punt
 it back and forth between the squares. There's rules and such, but...

Visnu Pitiyanuvath: It actually took us our first day to figure out what the
 rules really are. But there was a lot of Node-related jokes going on because we
 had two courts, and one line. And so, it was a constant like, flow-control
 jokes, should've used threads, spun up a coroutine, what's the flow-control for
 this line, what module are you using, I *promise* I'm going to play in the next
 one...You know, all sorts of really bad puns. So that was fun. I also at
 summer camp last year, bonded with members of the community who I had
 previously not thought I would be bonding with. For instance, Marak Squires.
 If you're out there listening, I used to think you were a giant jerk! Let's be
 honest, you would call me neckbeard in IRC. I never really hung out with you
 and met you. But summer camp happened, and we're now friends. Good friends,
 in fact. And, at summer camp, last year was the first time I got to throw a
 dodgeball at you, and that really brought us on to a level playing field. So,
 there's nothing to gel a nerd community like being able to interact in nature
 with each other, and I think summer camp is a beautiful example of that.

Daniel Shaw: What were some of the highlight topics that we discussed last year?

Max Ogden: I remember last year, as we sat outside under a tree in kind
 of a shady spot, Ryan [Dahl] talked about domains for the first time. It
 was all very experimental. Before they had ever even been implemented, he
 talked about what they were and there was a big discussion about error handling
 in general. Now they're landed, so maybe we can get some initial feedback.
 I think, like streams, it took 'till [Node.js version] 0.6 and a half before
 people actually started using streams and domains just landed in 0.8 so maybe
 it'll be a while before it gets a lot of uptake I think.

Daniel Shaw: Unfortunately, for us, for example, at Voxer, we still haven't been
 able to deploy 0.8 fully. We've been having issues with TLS and buffer
 allocation at peak load that is not fun. It's been a bit of a deal-breaker.
 We've been gradually rolling it out, but we had to pull the plug, because of
 some things that have been happening at high load. Hopefully we'll get that
 sorted out. I'm definitely looking forward to introducing more domains, but
 that's some of that stuff where you really need to be in the mix, and totally
 on the platform to really roll that out.

Visnu Pitiyanuvath: Oh, and Mr. DNK on IRC mentions that "more tutorials would
 be awesome on domains and using them."

Daniel Shaw: Absolutely.

Visnu Pitiyanuvath: As one of the newer features, it's hard to keep up if you're
 only reading the git commits on the joyent node repo.

