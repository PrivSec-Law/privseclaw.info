---
title: "Reclaim your Privacy | Part 1: Threat Modelling"
date: 2024-01-08
draft: false
image: /images/threatmodelcover.jpg
description: "Part 1 out of 3 on how to protect yourself online and regain control over your privacy."
toc: true
---

{{< substack >}}

### 1. Down the Rabbit Hole

If you are reading this post it is safe to assume that you are interested, to some degree, in protecting your personal privacy and security (PrivSec) in our age of hyper-digitization.

Strategies to protect your online PrivSec are constantly evolving. Misinformation, conflicting advice and inadequate recommendations of counter-measures to state and private surveillance are rife on the internet, particularly within privacy-focused communities online. Rather than focus on specific software and hardware that you can use to manage your PrivSec, this blog post will focus on establishing and maintaining an effective threat model tailored to your distinct needs as an individual.

### 2. A 3 Tiered Series of Posts

There will be 2 further posts as part of this 3 part series. I have broken down the steps you can take into 3 distinct tiers, each with its own post, which vary in the effort, time and research for you to implement in practice. These will be:

1.  This post - how to create a threat model and actionable privacy and security management strategy
2.  A security guide for the average internet user
3.  A privacy guide for those seeking to regain their fundamental right to privacy online
    

The steps that you will take to enhance your digital security and privacy will depend on your personal threat model and your action plan will not fit into any of the three perfectly.

It is all to common in digital privacy related online communities to see such questions along the lines of: “what is the most private email service?” or “should I use Tor?” with varying misinformed answers being given. Such questions are extremely vague with no clear cut answer as privacy solutions will differ based on your personal digital needs. It must be remembered that digital privacy (and anonymity) and security is a spectrum. The recommended actions for an ordinary person who wants greater security from the myriad of threats online will differ from someone who opposes the current model of ubiquitous state/ corporate surveillance and even more significantly from a dissident journalist for example. See below for a serious representation of this spectrum.

![Privacy Spectrum](/images/ericmurphyprivspectrum.jpg)

Credit goes to [Eric Murphy](https://www.youtube.com/watch?v=H414XdcbC4Q)

I should stress that you should avoid going too hard too fast. By this I mean you should not go completely down the rabbit hole, use Tor exclusively, nuke your social media accounts and retire to a cabin in the woods donning a tinfoil hat. This will lead to you burning out from the sheer scope of trying to become 100% anonymous online (you cant); reading and researching mountains of conflicting recommendations online and the constant inconveniences from the software and services you would give up. Most of those who choose to pursue digital privacy, security and anonymity in this way will inevitably give up and become disillusioned, returning to their old internet habits. This is why threat modelling is so important as a vital first step to begin your privacy journey as you will soon discover.

### 3. Threat Modelling: 101

#### 3.1 Why Threat Model?

Protecting your digital data in today’s age of hyper connectivity can be tiresome and disorientating. It seems like almost every other day that your personal data is being exposed from services and software that you use [everyday](https://www.reuters.com/technology/twitter-hacked-200-million-user-email-addresses-leaked-researcher-says-2023-01-05/) in numerous [data breaches](https://www.infosecurity-magazine.com/news/toyota-data-leak-customers/). [Services](https://www.nytimes.com/2023/01/05/technology/personaltech/lastpass-breach-password-safety.html) and [hardware](https://www.businessinsider.nl/hacker-breaks-into-smart-home-google-nest-devices-terrorizes-couple-2019-9?international=true&r=US) that are supposedly privacy and security respecting turn out to be [compromised](https://www.wsj.com/video/how-the-fbi-tricked-suspects-into-using-messaging-platform-anom/D5A9F66A-A9FF-4BCA-BEFD-3215D674CF2C.html), become [outdated](https://github.com/gorhill/uMatrix), [do not adequately inform their users](https://fossbytes.com/duckduckgo-allows-microsoft-trackers/) about privacy protections or were [never that secure](https://www.cnet.com/tech/services-and-software/why-you-should-be-skeptical-about-a-vpns-no-logs-claims/) to [begin with](https://www.vice.com/en/article/gvzw5x/secure-messaging-app-wire-stores-everyone-youve-ever-contacted-in-plain-text). Navigating this ever evolving landscape is confusing and there is no fault in feeling that. For example the DuckDuckGo search engine can still, as of this posts date, be trusted however [until very recently](https://arstechnica.com/gadgets/2022/08/microsoft-trackers-run-afoul-of-duckduckgo-get-added-to-blocklist/) the browser could not be recommended from a privacy point of view due to allowing Microsoft trackers without express user consent or knowledge. This case illustrates that simply relying on specific services is a flawed way to maintain and protect your personal PrivSec and that something more is needed, namely a comprehensive privacy and security management strategy: [a threat model](https://www.cisco.com/c/en/us/products/security/what-is-threat-modeling.html).

#### 3.2 What is a Threat Model?

In essence a [threat model](https://ssd.eff.org/glossary/threat-model) is a comprehensive plan, or management strategy, that at its core aims to identify what your digital assets are, who your threats are and how you should go about protecting said assets from said threats.

The concept of threat modelling is [widely used](https://owasp.org/www-community/Threat_Modeling) in the cyber-security field and for good reason. Threats change and so do the tools needed to counteract them. Nothing is ever 100% secure. What is needed is a specific tailored methodology that is as rigorous as you need it to be.

### 4. PrivSec Fundamentals

Before I delve into the process of creating a threat model, I will go over some basic fundamental knowledge covering some key terminology. If you are more technically adept or already have knowledge in this field feel free to skip this part of the post.

**Security, Privacy and Anonymity:** These three terms often get conflated but they differ substantially.

*   **Security** can be described simply as efforts to keep your data secure from malicious third parties. What you define as a malicious third party would depend on your specific threat model.
-   **Privacy** can be defined as keeping elements of your [digital life to yourself](https://proton.me/blog/anonymity-vs-privacy), for example, using an end-to-end encrypted messaging service in which the content of what you send is only accessible by you and the recipient. Your Internet Service Provider (ISP) and state intelligence agencies may be able to work out who you are and who you are communicating with but the content of that would be deemed private.
*   A real world example of how these two terms differ and relate would be the use of Google services. Google is renowned in its industry for having among the best security for its users shielding them from malicious third party attacks everyday. However, your data is not private from Google itself. If avoiding state bulk collection and surveillance capitalism is a part of your threat model, using Google services would be [deemed as insecure](https://www.eff.org/deeplinks/2013/03/new-statistics-about-national-security-letters-google-transparency-report).
-   **Anonymity** is described as the decoupling of your real identity from your online actions. An example of this would be utilizing the Tor Network. While it can be deduced what you are doing online, being anonymous means that your online presence cannot be attributed to who you are.
*   **Further reading:** [Security vs. Privacy vs. Anonymity](https://www.businesstechweekly.com/cybersecurity/data-security/security-privacy/)
    

**Adversary:** An online actor that you want to protect your digital data from.

**Targeted Attacks:** These refer to attacks by malicious parties such as hackers that attempt to gain access to _specifically_ _your_ digital data and devices.

**Passive Attacks:** These refer to events and attacks such as widely proliferated malware, database breaches and hacks that affect and are targeted at _multiple people and companies_.

**Service Providers:** These are the entities that act as your gate-keeper to the internet, such as your search engine and browser, email provider, ISP, communication provider and many more.

**Doxing:** ‘Doxing’ or public exposure refers to having your personal information available to the public at large online.

**Mass surveillance:** The bulk data collection programs operated by law enforcement and intelligence agencies across the world.

**Surveillance capitalism:** The current revenue model on the internet of the collection and processing of individual’s personal data by tech corporations and data brokers for the purpose of profit, typically seen through the use of highly personalized advertising.

**Assets:** The elements of your digital life that you want to protect.

**Threats:** The entities that you want to protect your assets from.

### 5. Establishing an Effective Threat Model

Establishing your effective PrivSec threat model revolves around five key questions. It is important to take your time in thoroughly answering them, taking heed what it is exactly that you want out of your efforts.

#### 5.1 What is it Exactly That You Want to Protect?

First you will need to figure out what elements of your digital life, or assets, you want to put effort in protecting. These assets can be limited to certain sensitive parts of your digital identity such as an anonymous messaging account or your search engine queries or more generally encompass all the personal digital information that you produce by nature of being connected online.

In order to do this I would advise making a list:

1.  Identifying your assets that you want to protect
2.  Identifying where it is stored
3.  Identifying who has access to it
4.  Identifying what stops others from accessing it
    

The digital data that you produce is generally split into two classes: **content** and **metadata** and you should, when making a list of your assets, factor in this categorization.

Content refers to your actual digital content, whether it be the words used in a message or a post online while metadata refers to data about data, including but not limited to I.P addresses, geo-location data and the ‘URLs’ of websites you visit online. Neither is more important than the other from a PrivSec viewpoint, [as is often touted](https://www.youtube.com/watch?v=HO6fNDMGRmg), as both types of data about you can paint an intimate picture about your life, who you are, your daily activities, who you interact with and much more. The ability of metadata to provide actionable information about an individual is clearly elucidated by former NSA and CIA director General Michael Hayden when he testified to Congress: [“we kill people based on metadata.”](https://abcnews.go.com/blogs/headlines/2014/05/ex-nsa-chief-we-kill-people-based-on-metadata)

Depending on the level of effort you personally want to invest you may want to create a diagram including what entities have your personal data, where this data is stored and what third parties it can be shared with as seen below. Much of this data can be found in the privacy policies and terms and conditions for any given service. I would recommend using [‘Terms of Service; Didn’t Read’](https://tosdr.org/) for this unless you enjoy sifting through legalese. I won’t judge ;). Such an index of your data will help you see if the data collected by an entity is truly necessary and proportional to its purposes.

![Threat Model Table 1](/images/threatmodelentitydatatable.jpg)

#### 5.2 What do You Want to Protect it From?

The next stage of creating your personal threat model involves sorting out and identifying exactly who and what your threat adversaries are. Depending on whether your aim is security, privacy or anonymity this step will differ radically from person to person. Under the most extreme threat models, such as if you are trying to avoid state and corporate surveillance, even actors with legitimate access, such as Google, can be a threat.

For simplicity’s sake threat actors/ adversaries can be divided into three groups:

1.  **External Adversaries:** Threat actors external to the systems you use, such as hackers, criminal groups or state institutions.
2.  **Organizational Adversaries:** Entities, such as a company or service provider you use, which manages your data in ways in which you do not approve. This also covers [rogue employees](https://www.telegraph.co.uk/news/2021/07/12/exclusive-extract-facebooks-engineers-spied-women/) abusing your personal data. 
3.  **Receiving Parties:** Entities that can have your personal data shared to them, or the receiving end of your communications (such as message recipients).
    

Once you have done this it is time to move onto the sub-step of what threats you want to protect your data from. This is where the [LINDDUN](https://www.linddun.org/linddun-go-categories) model of privacy/ security threats proves highly useful. Use this methodology to assess the following threats based on the information gathered previously in your threat model journey.

**Linkability:** The ability of an adversary to “sufficiently distinguish whether two IOI \[items of interest\] are linked or not, even without knowing the actual identity of the subject of the linkable IOI”. An example would be using the same login credentials, such as an email, across multiple different services. This can lead to inferences, singling out of an individual and identifiability which [can](https://www.justsecurity.org/81547/with-roe-v-wade-at-risk-digital-surveillance-threatens-reproductive-freedom/) and [has](https://www.forbes.com/sites/thomasbrewster/2021/10/04/google-keyword-warrants-give-us-government-data-on-search-users/) lead to unwanted potentially [discriminatory practices](https://tcf.org/content/report/disparate-impact-surveillance/).

**Identifiability:** The capability of an adversary to “sufficiently identify the subject within a set of subjects”. This occurs when “data items can be linked to the identity of the data subject, with a certain probability.” An example of this would be if you provide personal identifying data to a service, such as an email with your real name or official documentation.

**Non-Repudiation:** Privacy and security goals can, on occasion, come into conflict with each other and be mutually exclusive. Put simply non-repudiation is when a “data subject cannot deny they know, have done or have said something.” For things like online banking or logging into your employers network this is vital for security, to verify that only those with authorized access to a service can gain access. However, for other things “non repudiation leads to data subject accountability: when a person is not able to be repudiate an action or piece of information, he can be held accountable (e.g. a whistleblower can be prosecuted)”. If you need to have ‘plausible deniability’/ avoid non-repudiation I would advise you to ask yourself the questions found on LINDDUN GO under this threat category.

**Detectability:** Under certain threat models the outright presence of a piece of data can be an issue regardless of the protections afforded to it. LINDDUN defined this as “being able to sufficiently distinguish whether an item of interest (IOI) exists or not.” Detectability can result in the “deduction of personal data” and be used to “extend a data subject’s profile (linkability) and/ or identify the data subject”. An example of this would be the presence of an individual’s records in a rehabilitation center that if [breached](https://healthitsecurity.com/news/healthcare-data-breach-at-pa-rehab-center-impacts-130k) would lead adversaries to deduce sensitive health information.

**Unawareness:** Today it is highly common for your personal data to be stored by services in ‘the cloud’ (a fancy and obscure way of saying on another entity’s computer) subject to their data protection policies and procedures. Services fall victim to [data breaches and hacks](https://www.linddun.org/disclosure-of-information) everyday, exposing the personal information of [millions](https://www.statista.com/statistics/273550/data-breaches-recorded-in-the-united-states-by-number-of-breaches-and-records-exposed/). You may trust a specific service provider but this does not change the reality. The more time that your data is stored on another entity’s computer systems the higher the likelihood is that it will be leaked and such a breach for the purposes of any threat model should be assumed to be inevitable. While less common attacks on individual’s personal devices are also a threat. This leads us to the concept of **Unawareness**. User unawareness is one of the biggest threats to an individual’s security and privacy and the main cause of privacy and security tools and methodologies failing. In today’s hyper-digitized age most individuals think nothing of handing over their personal data to a manifold of different applications, service providers etc. When a data subject is “unaware if, or unable to intervene in, the collection and further processing of their personal data” the end result can lead to a violation of their fundamental rights. This happens through a:

1.  **Lack of transparency/ predictability:** if “a data subject is unaware of collection and/ or processing of personal data related to them.” An example of this would be if there are no notices of data collection in the first place or of third party sharing.
2.  **Lack of intervenability:** if **“**a data subject cannot access or manage their own personal data (including managing access settings).” An inability for individual’s to access, change or remove data or update privacy settings would be an example of this.
    

In order to avoid this scenario of unawareness I would advise your PrivSec management strategy be supported by rudimentary research from reputable sources asking the following questions:

-   Are you adequately informed about the collection and further processing of your personal data?
*   Does the service you are utilizing provide user-friendly privacy controls with privacy by design/ default settings?
-   Does the service you use provide an easy to use way to request, change and/ or remove your personal data?
*   Does the service you are using require your informed consent before any data is collected or processed and can this consent be easily withdrawn?
    

**Non-Compliance:** The final category in the LINDDUN threat model focuses on basic data protection principles, influenced by the EU’s GDPR but best practice in the industry regardless of applicable legislation. You should assess whether the service you are using or are considering using adheres to the basic data protection principles of:

*   **Purpose limitation:** A service provider should only collect and process data for an express predetermined purpose.
-   **Proportionality:** A service provider should only collect and process the amount of data required for the purpose (data minimization/ principle of least privilege)
*   **Storage limitation:** A service provider should only store data for as long is strictly necessary for the purpose
    

Again a diagram can prove very useful depending on the level of effort you want to invest. When an answer to a question leads to a threat in a corresponding category for a service you utilize, you can easily mark it off as seen in the below example. This would require the previous diagram. I would also highly recommend you ‘play’ [LINDDUN GO](https://www.linddun.org/go) while doing this for a complete, fully exhaustive, intuitive and easy to follow experience to ensure that your threat model is tailored to you.

![Threat Model Table 2](/images/linduntable.png)

#### 5.3 How Likely is it That you Will Need to Protect it?

This stage of creating your personal threat model revolves around the ideas of risk, threats and capabilities. In this stage, heavily linked to the previous step, you should list the threats you are going to treat seriously and those that are too harmless or rare to worry about.

> “the likelihood that a particular threat against a particular asset will actually occur. It goes hand-in-hand with capability. While your mobile phone provider has the capability to access all of your data, the risk of them posting your private data online to harm your reputation is low.” _\-EFF’s Surveillance Self-Defense_

An important note to take into account is the difference between the threat event that may occur and the likelihood that it will occur. Remember, assessing risk is highly subjective and personal. What one person may deem as an acceptable amount of risk may be unacceptable to you based on your threat model and vice-versa.

#### 5.4 What are the Consequences of Failure?

This stage of the threat modelling process asks what are the potential ramifications of a breach to your threat model. You should note down and list what adversaries could do with your data for this step.

> “Security planning involves understanding how bad the consequences could be if an adversary successfully gains access to one of your assets. To determine this, you should consider the [capability](https://ssd.eff.org/glossary/capability) of your adversary. For example, your mobile phone provider has access to all your phone records. A hacker on an open Wi-Fi network can access your unencrypted communications. Your government might have stronger capabilities.” _\-EFF’s Surveillance Self-Defense_

#### 5.5 How Much Effort are You Willing to go Through to Mitigate the Threats and Consequences?

The amount of time, effort and resources you are willing to dedicate to creating an effective personal PrivSec management strategy will primarily be determined by steps three and four. Depending on your level of risk and your perceived threats, you may want to go through greater or lessor efforts. For example a lawyer or journalist working on matters related to national security or within a repressive regime will have a considerably different and more exhaustive threat model than a family member who regularly posts amusing videos online.

Once you have completed this stage you would have successfully created a personally tailored threat model!

**The next step would be to mitigate these threats that you identified.** **This will be done in the follow up posts to this series!**

### 6. Every Threat Model is Different

I can’t stress enough that every individual’s PrivSec threat model is different. All these steps are not necessarily to be taken in order as they are all highly interconnected and inter-related. It is my hope that this post has proven useful and informative to you and has offered a decent introductory guide into how to effectively establish a personal privacy and security management strategy. Even if you choose not to implement this methodology today or tomorrow you should be equipped, should you need it, for whatever the future may hold.

For a more in depth look into how to create an effective threat model and PrivSec management strategy I would highly recommend the sources that were heavily consulted with in the creation of this post which can be seen at the end of this post.

### 7. Main Sources Used

*   [EFF’s Surveillance Self-Defense](https://ssd.eff.org/)
-   [PrivacyGuides](https://www.privacyguides.org/)
*   [LINDDUN](https://www.linddun.org/)
-   [Threat Modeling Manifesto](https://www.threatmodelingmanifesto.org/)
*   [How To Protect Your Online Privacy With A Threat Model | Tutorial 2022](https://www.youtube.com/watch?v=6AXkJ3dot2s), The Hated One, YouTube
    
* * * 

_“Security is a process, not a product.”_ __-Bruce Schneier__

* * * 

{{< substack >}}