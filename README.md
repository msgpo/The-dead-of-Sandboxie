# The dead of Sandboxie

> We are the [GAFAM](https://en.wikipedia.org/wiki/GAFAM)! Lower your shields and surrender your privacy. We will add your biological and technological distinctiveness to our own telemetry. Your buying behavior will adapt to our ad-services. Resistance is futile!


I was a long time Sandboxie user (by Invincea), until [Sophos took over it](https://community.sophos.com/products/sandboxie/f/forum/115109/major-sandboxie-news-sandboxie-is-now-a-free-tool-with-plans-to-transition-it-to-an-open-source-tool/), which was in my opinion a bad decision. Sandboxie is currently freeware and the Sophos team [promised to open source it](https://community.sophos.com/products/sandboxie/f/forum/115109/major-sandboxie-news-sandboxie-is-now-a-free-tool-with-plans-to-transition-it-to-an-open-source-tool/).


## Download

The latest (free) version v5.31.4 can be downloaded from [here](https://www.sandboxie.com/DownloadSandboxie). You can fill-in fake [eMail](https://temp-mail.org/) data to get to the real download links (I'm not permitted to post any direct download URL). The official forum can be found over [here](https://community.sophos.com/products/sandboxie/f/forum) (no login required).



## Paid customers f*ck'ed again?
This what happens to Sandboxie right now is a perfect example why online activation should be illegal to begin with. _I have a lifetime license for Sandboxie_. The application license term has no expiration date. This reminds me on the old AnyDVD story, they did not converted by license to their "HD version" (basically they renamed it to avoid giving old customers a new lic.).

### Refund?
Not possible because the EULA changed during the time I bought Sandboxie and I can't recall the EULA verbiage from for X years.


## Yay! Open Source!

Well, I did not (yet) found any source code, there is a promise but that's it (for now). Of course, this can change however I believe that will not go well. The reasons are obvious, maintaining such a program is a huge task and most people just don't want to spent that much time on testing, developing and improving the product.

Sophos wrote that sandboxie is not their main priority and this worries me, they might integrate it into one of their products which then forces you to use their solution. I see that someone could compile (based on the source code leak) his own binary, however it's unclear if Sophos really uploads an "untouched" version or if its bound together with something else which would make it even harder to _get the original sandoxie_ program back.

It's also questionable if the new product will come with "telemetry" (see CCLeaner) to improve their product or not, this worries me, from my experience telemetry itself never really helped any software product to improve something. In most cases it was exactly the opposite e.g. privacy leaks or MITM attacks in order to obtain victims private data.

## Alternatives?

Not much, Windows 10 got his own "sandbox". Sandboxies concept is (or was) not bad, however keep in mind that the program itself is from XP ages, nowadays we are using hardware virtualization as sandbox solution, not software (like sandboxie does). Alternatives are Comodo, 360, Windows or software with [hardened security features](https://www.bromium.com/our-tech/bromium-secure-platform/). On Linux there is basically only Firejail.


## Why this repo?

Well, I'm (again) disappointed and it makes me "_angry_" that paid customers are "screwed" again (yes it's now freeware, yes it will be [open source'd](https://community.sophos.com/products/sandboxie/f/forum/115109/major-sandboxie-news-sandboxie-is-now-a-free-tool-with-plans-to-transition-it-to-an-open-source-tool) - _I get that!_). As said, I'm worried that no one is really working with the source code (once it was finally uploaded). Personally, I can only _hope_ Microsoft improves their own [Windows Sandbox solution](https://askleo.com/whats-the-difference-between-a-sandbox-and-a-virtual-machine/), but we will see how "stable" that will be (the current sandbox is not really "usable" in its current state).

Basically to show the world, that:
* ... there are alternatives like Comodo etc.
* .. my point of view on this, I could have just created a gist but my gists often getting spammed by bots.
* . we should keep an eye on this topic.


## Timeline
- 09.04.2020 - [Sophos open source'd Sandboxie](https://twitter.com/TheHackersNews/status/1248310760242991104), the source code is avbl. over [here](https://github.com/DavidXanatos/Sandboxie) it's licensed under GPLv3.
- Sept. 2019 - Sophos switched to a new license.
- Febr. 2017 - Sophos announced the acquisition of Invincea. Invincea posted an assurance in Sandboxie's website that for the time being Sandboxie's development and support would continue as normal.
- ~Dec. 2013 - Invincea announced the acquisition of Sandboxie.
- ~ 05 2004  - Sandboxie was initially released in 2004 as a tool for sandboxing Internet Explorer. Over time, the program was expanded to support other browsers and arbitrary Win32 applications.
