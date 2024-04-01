XZ Backdoor
===

Jia Tan
---
## Jia Tan [github profile](https://github.com/JiaT75)
This is the account which was caught pushing a backdoor to the xz repository. 
The backdoor is quite intricate and advanced. To create such a well obfuscated backdoor
someone has to have a huge amount of technical expertise. 

**General Info**
- GitHub
    - Name: Jia Tan
    - Aliases:
        - Jia Cheong Tan (Github full name before it changed to just "Jia Tan")
        - JiaT75 (Github username)
        - jiat0218 (email shortname/a few commits?)
    - Created on: `2021-01-06`
    - Email used: `jiat0218@gmail.com`
    - Primary Timezone: +0800 ([Wikipedia > UTC+08:00](https://en.wikipedia.org/wiki/UTC%2B08:00))
    - Other Timezones:
        - ?
- Username: "JiaT75", Full Name: "Jia Tan"

**Notable things**
- Full Name was "Jia Cheong Tan" at least up until 2022-10-06 (see [Archive.org > Github/JiaT75](https://web.archive.org/web/20221006184706/https://github.com/JiaT75)
- Profile Picture is has dimensions 255 by 255, which is odd. Maybe this can be used to identify the true original source of the image?
  > The picture can be found in several clipart websites, eg: https://urbanhacker.net/wp-content/uploads/2024/04/image.png
- Pretty active on the mailing list
  > Under the name "Jia Tan" since 2021-10-29
  > Under the name "jiat0218" once on 2022-04-28 // why? why does it show up once under a slightly different name
- There is an unused github account called jiat0218 also created in 2021 https://github.com/JiaT0218

**(Rather incomplete) Collection of text that Jia wrote:**
This is just pull requests, but might be useful.
Jia seems to speak english perfectly well. No langauge
abnormalities etc. visible on first glance.

https://github.com/libarchive/libarchive/pull/1598
https://github.com/keithn/seatest/pull/29
https://github.com/keithn/seatest/pull/28
https://github.com/libarchive/libarchive/pull/1609
https://github.com/libarchive/libarchive/pull/1682
https://github.com/google/oss-fuzz/pull/9960
https://github.com/llvm/llvm-project/issues/63957
https://github.com/bytecodealliance/wasmtime/pull/6839
https://github.com/google/oss-fuzz/pull/11286


## The Mailing list [mail-archive.com](https://www.mail-archive.com/xz-devel@tukaani.org/)
This is the general purpose mailing list for the xz project. Its notable that Lasse Collin
has been active on it since at least 2011 (see https://www.mail-archive.com/xz-devel@tukaani.org/msg00000.html)

The mailing list is notable/relevant to this because it not only has more text written by Jia, but also features
what are generally thought to be Socketpuppet accounts (accounts created and controlled by whoever is behind this backdoor).






## Socketpuppet accounts
It is generally suspected that whoever is behind this used several "Socketpuppet accounts" to pressure Lasse into merging patches/commits
that Jia made.

- Jigar Kumar (`jigarkumar17@protonmail.com`)
  > Only 6 mails between 2022-04-27 and 2022-06-22 (see https://www.mail-archive.com/search?l=xz-devel%40tukaani.org&q=from:"Jigar+Kumar"&o=newest)
  
- Dennis Ens (`dennis3ns@gmail.com`)
  > Also only 6 mails, but way more spread out between 2022-05-19 and 2024-03-05 (thats only a month ago)

## Person of interest


## Unorganised Links (sort of an info dump so we dont loose focus/forget things)
- The public xz mailing list (https://www.mail-archive.com/xz-devel@tukaani.org/)
- https://www.mail-archive.com/xz-devel@tukaani.org/msg00556.html (28 Apr 2022)



## Blogs & useful for more general info
[“Everything I know about the xz backdoor”](https://boehs.org/node/everything-i-know-about-the-xz-backdoor)

## Todo
(Just a list of things to complete in this doc, leads to follow/keep following)
- Investigate Jigar Kumar on the mailing list
- Check have I been pwned for all emails that come up during this investigation
- How did Jia communicate with the fedora devs? Can we trace him from there?
- check out git log to get exact date of name change
- add interesting graphs like commit history vs authors(?)
    - Add that one graph from twitter that shows how the malicous commits were all from an unusual timezone for Jia