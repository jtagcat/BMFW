---
title: Best Motherfucking Website
navbar: false
titleAsH1: false
---
# This is _the best_ motherfucking website. {#}
{{< aside >}}And it’s fucking perfect.{{< /aside >}}

## Seriously, what the fuck else do you want? {#}
You keep forgetting. Let me describe the perfect-ass website:
 - Shit’s lightweight and loads fast.
 - Fits on all your shitty screens.
 - Looks the same in all your shitty browsers.
 - Accessible to every asshole that visits your site.
 - Shit’s legible and gets the fucking point across (if you had one instead of just a 5MB background video of hipsters poking at their iPhones).

You do it every day. You take [a fucking masterpiece](//motherfuckingwebsite.com/ "Motherfucking Website") and incrementally [ruin it](//bettermotherfuckingwebsite.com/ "Better Motherfucking Website") for the sake of design. Let me remind you: design is {{< dfn "design" >}}to plan and make something for a specific purpose{{< /dfn >}}. The most basic purpose of text on a website is to be read. Yet you keep doing shit that gets in the way.

### Quit fucking around with grey text. {#grey-text}
[Text contrast is not a bad thing](//contrastrebellion.com/ "Contrast Rebellion"). The print on your newspaper is not true black, nor is the text on your screen. These are limitations, not ideals. Stop making it worse.

### Remote fonts are wasting your time and mine. {#remote-fonts}
Why the fuck are you loading 500kB of font to render 50kB of shitty content? Are your users even going to notice that it’s not their default serif or sans-serif? Why do you even bother when Chrome is going to render it like ass anyways? Use a [font stack your users already have](//www.awayback.com/index.php/2010/02/03/revised-font-stack/ "Revised Font Stack").

## Your website is more than just HTML. {#}
### You have no excuse for using HTTP. {#use-https}
Why are you still delivering sites over HTTP? My shitty Atom 330 CPU from 2008 can perform aes-256-cbc encryption via OpenSSL at 110 megabits per second. My Xeon E5-2670 CPU without AES-NI enabled hits 444 megabits per second. With AES-NI enabled it hits a staggering 2.2 gigabits per second. Your server probably can’t even load your stupid fucking JavaScript framework’s dependencies that fast.

TLS certificates are cheap. Seriously, you can [get them for US$6](//www.namecheap.com/security/ssl-certificates/comodo/positivessl). You paid twice that much for your idiotic domain name. You can even get them for free from [Let’s Encrypt](//letsencrypt.org/ "Let’s Encrypt Free Certificate Authority").

HTTPS [improves your search ranking](//webmasters.googleblog.com/2014/08/https-as-ranking-signal.html "Google announces HTTPS support to affect pagerank") so people are more likely to find your ramblings on the Google. It’s also required for [HTTP/2 support](//http2.github.io/faq/#does-http2-require-encryption "HTTP/2 Frequently Asked Questions") which allows browsers to fetch resources more efficiently.

### This shit is gzipped. {#compression}
Your webserver is perfectly capable of compressing HTML. My Atom 330 CPU can perform single-core `gzip -6` on random data at 51 megabits per second. My Xeon E5-2670 from 2012 can do this at 216 megabits per second. Your meme website isn’t as random as you think it is and will compress much faster.

### Cache is Money {#caching}
It’s bad enough you’re forcing users to load 5MB of hero image and JavaScript framework. Why are you making them reload it every time they visit your shitty website? Bandwidth is cheap but it isn’t free. Via data charges or waiting, someone is paying for your fucking laziness.

## This is a website. Look at it. You’ve never seen one before. {#}
Like the man who’s never grown out his beard has no idea what his true natural state is, you have no fucking idea what a website is. All you have ever seen are shitty skeuomorphic bastardizations of what should be text communicating a fucking message. This is a real, naked website. Look at it. It’s fucking beautiful.

### Yes, this is fucking satire, you fuck {#}
I’m not actually saying your shitty site should look like this. What I’m saying is that all the problems we have with websites are **ones we create ourselves**. Websites aren’t broken by default, they are functional, high-performing, and accessible. You break them. You son-of-a-bitch.

## Even the best can be improved. {#}
If you can bring this website further beyond perfection, [send a pull request on GitHub](//github.com/KeenRivals/bestmotherfucking.website "KeenRivals/bestmotherfucking.website on GitHub").
