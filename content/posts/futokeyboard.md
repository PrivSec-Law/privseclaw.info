---
title: "FUTO Keyboard Review: An Android Keyboard that is Private and Functional"
date: 2024-07-03
author: Luke Arbuthnot
cover:
  image: "/images/futokeyboardlogo.jpg"
  alt: ""
  caption: ""
summary: If you use Android your keyboard could be a security and privacy risk. Here is why you should use FUTO Keyboard instead!
---

### Your Android Keyboard is Most Likely Spying on You

If you are using an Android device it is possible that your keyboard application is highly insecure and spying on you. 

If you are using a third party keyboard (one that is not provided by default on your phone's operating system) this risk is highly likely. This is because most third party keyboard applications offer much more than simple text input. Personalized text prediction and auto correct is often delivered through your personal key inputs (how and what you type) being uploaded to the keyboard provider's severs. While making your life more convenient, [this is a privacy nightmare](https://www.howtogeek.com/335428/smartphone-keyboards-are-a-privacy-nightmare/#why-keyboards-are-so-dangerous). Think about all the things that you have typed into your phone's keyboard: highly intimate messages to loved ones and friends; sensitive medical records and confidential business information. You do not want this sort of information leaving your device and being sent to another party's servers. Why?

Because the keyboard app you use may be malicious (malware deliberately designed to spy on you). In 2022 Google removed many malicious apps, including keyboards, that collectively had been downloaded a [staggering 10 million+ times.](https://wp.nyu.edu/itsecurity/2022/07/29/android-users-confirm-you-dont-have-malicious-apps-on-your-device/)

Furthermore, even if the keyboard application you use is not deliberately and actively malicious, you still cannot trust it to keep your information secure and private. Some examples: 

>*"SwiftKey (a Microsoft product) users started reporting that their keyboard was suggesting random foreign words and even unfamiliar email addresses."* - [**SwiftKey suspends cloud syncing after data leak, Android Authority**](https://www.androidauthority.com/swiftkey-suspends-service-data-leak-706680/)

>*"A team of security researchers at the Kromtech Security Center has discovered a massive trove of personal data belonging to more than 31 million users of the popular virtual keyboard app, AI.type, accidentally leaked online for anyone to download without requiring any password."* - [**Massive Breach Exposes Keyboard App that Collects Personal Data On Its 31 Million Users, The Hacker News**](https://thehackernews.com/2017/12/keyboard-data-breach.html)

These risks are not exclusively limited to third party keyboard applications either. A recent investigation by the University of Toronto's Citizen Lab found that ["almost every Chinese keyboard app has a security flaw that reveals what users type,"](https://www.technologyreview.com/2024/04/24/1091740/chinese-keyboard-app-security-encryption/) leaving nearly 1 billion people "vulnerable to eavesdropping," potentially by the Five Eyes (an intelligence gathering alliance between the USA, UK, Australia, New Zealand and Canada).

>*"We analyzed the security of cloud-based pinyin keyboard apps from nine vendors — Baidu, Honor, Huawei, iFlytek, OPPO, Samsung, Tencent, Vivo, and Xiaomi — and examined their transmission of users’ keystrokes for vulnerabilities."
>
>"Our analysis revealed critical vulnerabilities in keyboard apps from eight out of the nine vendors in which we could exploit that vulnerability to completely reveal the contents of users’ keystrokes in transit. Most of the vulnerable apps can be exploited by an entirely passive network eavesdropper."
>
>"we estimate that up to one billion users are affected by these vulnerabilities. Given the scope of these vulnerabilities, the sensitivity of what users type on their devices, the ease with which these vulnerabilities may have been discovered, and that the Five Eyes have previously exploited similar vulnerabilities in Chinese apps for surveillance, it is possible that such users’ keystrokes may have also been under mass surveillance."* - [**The not-so-silent type, Vulnerabilities across keyboard apps reveal keystrokes to network eavesdroppers, Citizen Lab** ](https://citizenlab.ca/2024/04/vulnerabilities-across-keyboard-apps-reveal-keystrokes-to-network-eavesdroppers/)

All of this raises the question. Why does your phones keyboard application need an internet connection? I'm going to hazard a guess that its because these companies want to extract your personal information for profit. The internet's business model is [Surveillance Capitalism](https://www.theguardian.com/books/2019/oct/04/shoshana-zuboff-surveillance-capitalism-assault-human-automomy-digital-privacy) after all! 

This is where [FUTO Keyboard](https://keyboard.futo.org/) comes in! 

### About FUTO

Futo is an organization that describes itself as:

>*"an organization dedicated to developing, both through in-house engineering and investment, technologies that frustrate centralization and industry consolidation."* - **[What is FUTO?](https://futo.org/about/what-is-futo/)** 

with the mission statement:

>*"Computers should belong to you, the people. We develop and fund technology to give them back."* 

It was founded in 2021 by Eron Wolf, an 18 year Silicon Valley veteran and billionaire who has become disillusioned with the current oligopolistic grip Big Tech has over our digital lives. 

>*"Through a combination of in-house engineering projects, targeted investments, generous grants, and multi-media public education efforts, we will free technology from the control of the few"* 

Amongst many other offerings the organization has created a private and secure keyboard application free to download and use. 
### Installation and Setup

Installing FUTO Keyboard on your Android device is extremely easy. You can choose to install it from the **[Google Play Store,](https://play.google.com/store/apps/details?id=org.futo.inputmethod.latin.playstore)** alternative Android app store **[F-Droid,](https://app.futo.org/fdroid/repo/)** or through Obtanium using their **[Github repository.](https://github.com/futo-org/android-keyboard/releases)** 

Once installed, open the app and click through the popups which will ask you to set FUTO Keyboard as your default Android keyboard.

### Features 

#### Privacy Respecting

FUTO Keyboard does not connect to the internet and it does not request or require network privileges. This means that the application is incapable of sending your keystrokes, inputs and voice data to any party. I verified this myself using GrapheneOS, an operating system which allows for more granular control of application network permissions compared to normal Android. Upon opening the permissions section in my phone's settings it was clear that FUTO Keyboard does not connect to the internet. See below (microphone permissions are an optional permission if you want to use the voice to text feature): 

{{< figure src="/images/futokeyboardpermissions.jpg#center" alt="text" width="50%" >}}

#### Everything you Need from a Keyboard App

FUTO Keyboard has a wide range of features that has everything you could need from a keyboard application: 

* A wide variety of light and dark themes available for use that all look great.
* All the emoji support you may need.
* A clipboard manager to manage copied text and images.
* Many typing preferences including emoji suggestions, text prediction and swipe typing.
* Support for many languages with an easy way to swap between them in the keyboard.
* Voice to text support .
* Support for imported voice to text models which can be discovered through a link in the application.

Here is what the keyboard itself looks like:

{{< figure src="/images/futokeyboard.jpg#center" alt="text" width="50%" >}}

And the application's settings:

{{< figure src="/images/futokeyboardsettings.jpg#center" alt="text" width="50%" >}}

#### Source Code is Available and Verifiable

In the spirit of FUTO's mission the source code for the application is available to see in what the organization calls "source first", a new software licencing standard created by the organization. For all intents and purposes source first is open source, with code being publicly viewable and verifiable and individuals being able to download, view, modify and redistribute it for personal use. How this differs from traditional open source licencing is that it ["will not force programmers to let others, especially the tech oligopoly, profit from their work for free."](https://futo.org/about/futo-statement-on-opensource/) 

#### Honor Based Payment 

FUTO has chosen to implement an honor based payment method for the application. Choosing to not pay for FUTO Keyboard and use it during the eternal free trial period will not impact your ability to use it or enjoy all the features. As put by Louis Rossman, a prominent Right to Repair activist and FUTO member, using it without paying ["will be between you and your god."](https://www.youtube.com/watch?v=GYX92lLpZ20)

### Final Remarks

With essentially everything you do on an Android smartphone making use of the keyboard it is great to have the peace of mind that it does not connect to the internet. Highly intimate messages typed to loved ones and friends, sensitive medical records and confidential business information all go through your keyboard application. They should be private and secure. I don't trust Google, Samsung, Motorola or Huawei in the slightest and neither should you. The record is very clear on their anti-consumer and surveillance based business models. 

In place of these internet connected keyboard options, I would highly recommend FUTO's offer instead! 

For more information about FUTO as an organization, its mission and the backing behind it see this below video:

{{< youtube ugkWm6XGWo8 >}}

* * *

_Disclaimer: I do not, by any means, claim to be an expert in matters relating to privacy, security and law or offer what can be construed as guaranteed fool-proof advice. What I do offer is an insight into these matters from someone who is highly invested in personal privacy/ security themselves and who is studying technology law at the level of higher education._

* * *

{{< substackiframe src="https://privseclaw.substack.com/embed" >}}

* * * 

{{< chat futokeyboard >}}