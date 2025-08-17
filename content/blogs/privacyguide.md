---
title: "Reclaim your Privacy | Part 3: Escaping the Privacy Paradox"
date: 2024-04-04
draft: false
image: /images/facebookwatchingscreen.jpg
description: "Part 3 out of 3 on how to protect yourself online and regain control over your privacy."
toc: true
---

{{< substack >}}

### 1. The Private Individual

Are you growing concerned about the increasing concentration, consolidation, and expansion of informational power in the hands of seemingly unaccountable technology corporations and state actors? Do you wish to mitigate the sense of constant digital surveillance and monitoring every day? If so, let this post act as an introductory guide for you.

Following this guide will necessitate effort on your part to educate yourself and keep yourself updated with the latest developments concerning personal digital privacy. Depending on your personal threat model and how far and deep you want to go on your privacy journey some basic technical know how will be required. I will link the sources that I regularly follow at the end of this post as well as point you to helpful resources and online communities.

If you have not already, I would highly advise checking out the previous two posts in this series that deal with: how to effectively create a personal privacy/ security threat model and management strategy and how to increase your digital security. It will be assumed within this post that you have. These can be seen [here]({{< ref "/blogs/threatmodel" >}} "Threat modelling") and [here]({{< ref "/blogs/securityguide" >}} "Security Guide").

I cannot stress enough that you don’t have to implement all of the steps found within these guides in order to increase your digital privacy. Certainly do not go nuclear and implement all of these, all at once lest your suffer from burnout, confusion and ultimately go back to the digital products and services you used before. Remember: any step taken towards protecting your digital privacy is worthwhile, but not every step may be worthwhile to you. What may be a sound privacy choice for one individual may not make sense for another. Always keep in mind your threat model and what exactly you are trying to achieve.

### 2. User Control

Ultimately, it is my opinion that digital privacy is fundamentally underpinned by the notion of user control. By this I am not referring to the ‘privacy’ settings and toggles available on most applications and digital services but rather the concepts of autonomy and self-sovereignty. Many of the recommendations within this introductory guide will not only serve to increase your privacy but also unshackle you from the exploitative surveillance capitalistic business model that drives the modern internet. By using privacy respecting, free and open source software; ‘Big Tech’ mega-corporations will no longer be the gatekeepers to your digital life.

> _Control does not guarantee privacy but it is an absolute imperative. Privacy cannot be given, it can only be taken._
> 
> [\-The Hated One](https://www.youtube.com/watch?v=nQ9LR8homt4)

### 3. Back to LINDDUN

Applying the LINDDUN threat model is a must if you want to effectively use the below recommendations to become more private online. As such a quick recap is in order. For more detail I refer you to the first post in this series.

**Linkability:** As a general rule you want to aim to prevent the different aspects of your digital life from being linked with each other. An example of this would be using email aliasing instead of reusing the same email address across multiple different accounts

**Identifiability:** As a general rule you want to avoid being having your real world identity linked to the data that you produce. An example of this would be if you avoid provide personal identifying data to a service, such as an email with your real name or official documentation.

**Non-Repudiation:** Privacy and security goals can, on occasion, come into conflict with each other and be mutually exclusive. Put simply non-repudiation is when a “data subject cannot deny they know, have done or have said something.” For things like online banking or logging into your employers network this is vital for security, to verify that only those with authorized access to a service can gain access. However, for other things “non repudiation leads to data subject accountability: when a person is not able to be repudiate an action or piece of information, he can be held accountable (e.g. a whistleblower can be prosecuted)”. If you need to have ‘plausible deniability’/ avoid non-repudiation I would advise you to ask yourself the questions found on LINDDUN GO under this threat category.

**Detectability:** Under certain threat models the outright presence of a piece of data can be an issue regardless of the protections afforded to it. Detectability can result in the “deduction of personal data” and be used to “extend a data subject’s profile (linkability) and/ or identify the data subject”. An example of this would be the presence of an individual’s records in a rehabilitation center that if breached would lead adversaries to deduce sensitive health information.

**Unawareness:** Often it is the user themselves that poses the biggest threat to digital privacy and security through unawareness of risks. In order to avoid this scenario of unawareness I would advise your PrivSec management strategy be supported by rudimentary research from reputable sources asking the following questions:

*   Are you adequately informed about the collection and further processing of your personal data?
-   Does the service you are utilizing provide user-friendly privacy controls with privacy by design/ default settings? 
*   Does the service you use provide an easy to use way to request, change and/ or remove your personal data?
-   Does the service you are using require your informed consent before any data is collected or processed and can this consent be easily withdrawn?   

**Non-Compliance:** The final category in the LINDDUN threat model focuses on basic data protection principles, influenced by the EU’s GDPR but best practice in the industry regardless of applicable legislation. You should assess whether the service you are using or are considering using adheres to the basic data protection principles of:

*   Purpose limitation: A service provider should only collect and process data for an express predetermined purpose.
-   Proportionality: A service provider should only collect and process the amount of data required for the purpose (data minimization/ principle of least privilege)
*   Storage limitation: A service provider should only store data for as long is strictly necessary for the purpose
    

Now that you have been refreshed on the LINDDUN method of threat modelling we can delve into some recommendations for software, services and practices. Remember to keep these 7 elements in mind when tailoring the services and software you use to your individual threat model.

### 4. Mobile Recommendations

#### 4.1 Use a Secure and Privacy Respecting Mobile Operating System (OS)

##### 4.1.1 Iphone Recommendations

While Apple in recent years has pushed heavily to create a brand image of respecting privacy the reality is a much more nuanced and grey. I would highly recommend the below video for reference.

{{< youtube nQ9LR8homt4 >}}

If you decide to stick with Apple’s IOS I would highly recommend you follow [this configuration page on Privacy Guides](https://www.privacyguides.org/en/os/ios-overview/) for which features and settings to enable/ disable.

##### 4.1.2 Android Recommendations

It is very hard for me to recommend a stock OEM Android operating system. By this I mean an operating system that comes by default preinstalled such as on Samsung, Huawei, Google Pixel phones. While Android at its core may be open source the versions of Android installed on end user devices are a complete privacy nightmare with invasive Google Play Services being baked into the OS and uninstallable apps such as Facebook (shudder) being ever present on your device.

> When you buy an Android phone, the default operating system comes bundled with apps and functionality that are not part of the Android Open Source Project. Many of these apps—even apps like the dialer which provide basic system functionality—require invasive integrations with Google Play Services, which in turn asks for privileges to access your files, contacts storage, call logs, SMS messages, location, camera, microphone, and numerous other things on your device in order for those basic system apps and many other apps to function in the first place. Frameworks like Google Play Services increase the attack surface of your device and are the source of various privacy concerns with Android. - [Privacy Guides](https://www.privacyguides.org/en/os/android-overview/)

However there is an exception: installing a non stock custom Android operating system that respects your digital privacy. Some notable and recommended custom Android operating systems all of which are open source are as follows:

1.  [GrapheneOS](https://grapheneos.org/)
2.  [DivestOS](http://divestos.org)
3.  [LineageOS](https://lineageos.org/)
    
These are all simple to install but are limited to certain devices. Keep in mind that all custom Android operating systems other than GrapheneOS have security issues due to the requirement for an unlocked bootloader.

[GrapheneOS](https://grapheneos.org/) is what I would strongly recommend to those seeking to maximize mobile privacy. It has the gold standard of mobile security being [recommended by the likes of NSA whistleblower Edward Snowden](https://x.com/Snowden/status/1588472045960327168), and in recent news beating out IOS and stock Android in security to [Cellebrite attacks](https://x.com/GrapheneOS/status/1791833221165965567?t=Oad6u8E41vUtLZobprTgPQ&s=19) (hacking software used by intelligence agencies, law enforcement and criminals). A full in depth review and explanation of this phenomenal operating system warrants its own post so for now I will link [GrapheneOS’s many privacy and security enhancing features.](https://grapheneos.org/features)

#### 4.2 End-to-end Encrypted Communications is a Must!

Using end to end encryption (E2EE) for your digital communications is a must. E2EE means that only you and the recipient of the message can see the content of the message being sent. See below for an great easy to understand illustration of how E2EE works.

{{< youtube c2OkOckSD20 >}}

You may want to shift your conversations to [Signal](https://signal.org/) which has identical functionality to WhatsApp, is just as easy to set up and even looks very similar. While WhatsApp is also E2EE, what sets Signal apart from it is in its collection of metadata. [WhatsApp collects data such as: your contacts list; who you chat with, when you chat with them and for how long](https://www.forbes.com/sites/zakdoffman/2021/01/03/whatsapp-beaten-by-apples-new-imessage-update-for-iphone-users/?sh=3181c6933623) all while linking this to a Meta advertising identity. While the content of your messages and calls is encrypted this metadata is able to paint a highly accurate image of your social connections and the way that you live your life. Remember the former Director of the CIA and NSA stated in Congressional testimony that [“we kill people based on metadata”](https://www.justsecurity.org/10311/michael-hayden-kill-people-based-metadata/). In contrast to this, Signal only collects your phone number, when you created your account and the time you last logged in as per this recent [US Federal Subpoena.](https://signal.org/bigbrother/cd-california-grand-jury/) Even if you manage to convince only your close family and friends to swap to Signal that is still a win. These conversations would undoubtedly be more intimate than those of your extended social network of friends and acquaintances and will certainly benefit from the additional protection Signal provides.

#### 4.3 Consider Cutting Out or Back on Your Social Media Accounts

You may want to consider cutting out Big Tech social media such as Instagram, Facebook, TikTok and Twitter. These platform’s applications amass an incredible amount of information on you to profile you and serve you advertisements and content. And this is not limited to just what you do in the application. These platforms track you across the internet such as with Meta’s tracking pixels imbedded in websites or through IP and browser fingerprinting. If you live within the EEA/ EU make sure you send in a GDPR right to be forgotten request if you choose to delete your accounts.

If this is not possible or you are unwilling to part ways with your social media, consider using fake information to create ‘anonymous’ accounts for platforms that permit it such as X or Reddit and limiting the information you provide them. For example don’t use your personal email address or upload an image of yourself/ your location etc. This is made much easier by using aliasing services (covered in depth below). Additionally, you can elect to only access these platforms through a privacy respecting browser as social media apps are notorious for acting similarly to spyware on your device.

#### 4.4 Use a Secure and Privacy Respecting Web browser_

For mobile browsing I would recommend either Brave Browser on Android with some settings tweaks or Safari on IOS with tweaks. See this page on [Privacy Guides](https://www.privacyguides.org/en/mobile-browsers/) for more up to date information on how to configure your browser.

#### 4.5 Consider Paying for your SIM in Cash

If legally possible and financially prudent you may elect to use a prepaid/ pay as you go number that you can top up with cash at an in person store location. This may be more costly and inconvenient but your mobile number will not be linked to your government identity and your mobile provider will not be able to sell useful information to data brokers and cold callers. Again keep in mind your personal threat model as this step may not be for everyone.

#### 4.6 Pay Close Attention to Application Permissions

You should pay very close attention to the permissions that you allow the applications installed on your device to have. By permissions I am referring to whether your installed applications are able to access: wifi, bluetooth, bluetooth LE, locations services, contacts, images and videos, files etc. Ask yourself if an application really needs a permission, for example: are you comfortable with Instagram having access to your entire photo and video gallery?

In recent years mobile operating systems such as IOS have allowed you to select only those files which you would like an application to access. Make use of this feature.

GrapheneOS deserves a mention here in that you are able to control these permissions to a much greater degree compared to other operating systems. With GrapheneOS you are able to: set up storage scopes (create sandboxed folders which applications can see only what you choose to let them); revoke Bluetooth, sensor and WiFi permissions (even before installing apps) amongst many other application [sandboxing](https://en.wikipedia.org/wiki/Sandbox_(computer_security)) features.

#### 4.7 Reduce your Attack Surface and Data Leakage by Limiting the Apps That You Have Installed on Your Device

Tied in with the above point is the need to limit the amount of applications that you have installed on your device. The more apps you have downloaded the larger your threat vector is for data collection. Go through all of your apps, if there are any that you don’t use very often or at all consider uninstalling them. Many applications can also be accessed from a computer or browser, if possible use that option. This will have the effect of reducing your [attack surface](https://www.techtarget.com/whatis/definition/attack-surface) and the overall data collection occurring on your phone. As well it does wonders for peace of mind and productivity to have a decluttered phone in which only those apps you actually need are installed.

Do you really need that McDonalds app for the occasional free Big Mac when the same app is tracking your geolocation and creating a profile of you [“reflecting the consumer’s preferences, characteristics, psychological trends, predispositions, behaviour, attitudes, intelligence, abilities, or aptitudes”](https://imgur.com/gallery/mcdonalds-app-tracks-location-info-things-like-psychological-trends-wPoauAF)? Or the [Tim Hortons app that collected constant precise geolocation data on their customers movements and habits](https://www.wired.com/story/tim-hortons-coffee-app-location-data-tracking/) in return for an occasional ‘free’ (in my opinion) overpriced and subpar coffee? There are many more examples of this that can be cited but I hope the point is clear. Even the most innocuous applications are siphoning you data constantly to feed the surveillance capitalist digital economy.

#### 4.8 Mobile Conclusion

If you want to be fully anonymous and ‘untrackable’ you would have to forgo your mobile device entirely, something which is unfortunately not possible in today’s digital world. By using a mobile device you have to accept that you have a tracker in your pocket by the very nature of how mobile cellular technology works. However, by implementing the above steps to fit your threat model, your privacy greatly enhanced compared to someone who has not implemented any of them. Remember, never let perfect be the enemy of good.

### 5. Desktop and Laptop Recommendations

#### 5.1 Use Linux

You may want to consider using a Linux distribution instead of MacOS or Windows. With Microsoft announcing the implementation of what can only be described as [literal AI spyware](https://www.bbc.com/news/articles/cpwwqp6nx14o) into Windows 11 it has never been a better time to make the swap.

Linux has never been easier to install and get running. Gone are the days of command line installations and driver issues. Linux today is perfectly capable of being installed and used by the average user. Whether you want to use your PC/ laptop for internet browsing, gaming, editing or document writing Linux has never been more accessible and intuitive.

But why use a Linux distribution instead of Windows or MacOS?

Unlike its proprietary (closed source) counterparts, Linux distributions are free and open-source software (FOSS), providing much needed transparency in the age of Big Tech oligopoly. Just take a look at how quickly a [malicious backdoor was discovered and patched.](https://arstechnica.com/security/2024/04/what-we-know-about-the-xz-utils-backdoor-that-almost-infected-the-world/) While such an example may make you think Linux is insecure or prone to hacking the fact that the code was open source (available for anyone to view) and very quickly detected and patched before any damage could be done is a testament to the power of FOSS for security and privacy. Contrast this with Windows, MacOS and other proprietary operating systems that intelligence agencies, such as the [CIA, stockpile zero days](https://wikileaks.org/ciav7p1/) for (publicly unknown critical security flaws) in which it can take years if ever for these flaws to be discovered.

With Linux, you're not subject to the invasive telemetry and data collection present in Windows and other operating systems. Whereas Windows constantly sends to Microsoft how the operating system is used, with Linux what you do on your machine is no one else’s business. Additionally, Linux distributions offer only the apps you choose to install with no forced app integrations such as Edge, Office365 or Teams, giving you more control over your own device and further reducing the avenues for data collection and telemetry.

So what Linux distribution should you choose?

I would recommend [Fedora](https://fedoraproject.org/) or [PopOS](https://pop.system76.com/) as they both offer an easy installation, do not require any use of the command line or terminal and are very user friendly. See the [Privacy Guides section on desktop operating systems](https://www.privacyguides.org/en/desktop/) for more information about Linux and the privacy benefits of using it.

#### 5.2 Use a Secure and Private Web Browser with Good Habits

Use an open source privacy respecting browser such as privacy ‘hardened’ Firefox (or its forks such as Librewolf or Mullvad Browser) or Brave Browser. Check out [Privacy Guides section on desktop browsers](https://www.privacyguides.org/en/desktop-browsers/) for more up to date information and configuration options. Avoid Google Chrome like the plague.

A good habit to get into is to isolate and separate your different digital identities online using different browser profiles or separate browsers entirely. For example a user could use a hardened Firefox for basic internet surfing, content consumption and personal emailing, Brave Browser for school/ college/ university work and Mullvad Browser for digital banking and government bureaucracy. This would have the effect of compartmentalizing the different aspects of your digital life reducing the ability for tracking to occur across different data points. As browser fingerprinting becomes the dominant form of user tracking and more advanced -[check this website and be terrified](https://fingerprint.com/)\- this habit is essential.

#### 5.3 Limit your Attack Surface

Again, much like this point under the mobile section of this post you should seek to limit the attack surface of your device by limiting the applications you have installed to what you actually need.

### 6. General Recommendations

#### 6.1 Use a Reputable and Privacy Respecting Email Service_

When looking for an email service to use you should be picking one that does not scan your messages to serve you targeted adverts or train its AI models (looking at you [Google](https://www.theguardian.com/technology/2021/may/09/how-private-is-your-gmail-and-should-you-switch)). Some great options are:

1.  [Proton Mail](https://proton.me/mail) hosted in Switzerland
2.  [Tuta](https://tuta.com/) hosted in Germany

With these email providers you will be getting less storage than Gmail, however you can pay a very low amount per month/ year to get more. This is to be expected as in these companies cases you are not the product and thus pay with money and not your privacy. Have a look at the [Privacy Guides section on email](https://www.privacyguides.org/en/email/) for more in depth information on how to choose the best provider for you.

Keep in mind however that email is fundamentally flawed as a way of communicating securely as it is not end to end encrypted. Avoid using it for anything sensitive (medical records for example) or utilize encryption and password protect the email before sending - a feature available on Proton and Tuta.

#### 6.2 Utilize Aliasing Services

Other than a phone number, email addresses are the current de facto digital identity that people present on the internet. Most people use the same email address for every service and product which comes with the massive drawback of your different digital accounts being able to be easily linked together.

This is where email aliasing services come in. An email aliasing service lets you quickly create a fresh email address for each website you sign up for. These new email addresses then forward incoming mail to your chosen email inbox, keeping your main email address and email provider hidden. See [this section on aliasing on Privacy Guides](https://www.privacyguides.org/en/email-aliasing/) for more information and recommended services. This is perhaps one of the most important steps you can do to regain a degree of privacy on the internet by reducing the ability for data brokers to link your digital activities together under a single identity.

#### 6.3 Utilize a Reputable and Privacy Respecting VPN Service

A VPN (Virtual Private Network) routes your internet traffic through the VPN providers servers in an encrypted ‘tunnel’. All this does is shift the trust that you have to give in order to access the internet from your ISP (Internet Service Provider) to the VPN company. Contrary to the VPN industry’s marketing not all threat models require a VPN. Since the [2013 Mass Surveillance Disclosures](https://www.theguardian.com/us-news/the-nsa-files) most [internet traffic on the most popular websites is now routed through HTTPS (encrypted)](https://www.welivesecurity.com/2018/09/03/majority-worlds-top-websites-https/), something any modern browser will notify you of (usually a padlock next to the URL) with warnings before accessing a non HTTPS webpage.

![How a VPN Works](/images/howvpnworks.jpg)

So why use a VPN provider for privacy reasons? Other than to get around geolocked content on Netflix for example or censored/ blocked sites, VPN’s are useful in order to shift trust away from your ISP. By using a VPN your ISP is unable to view anything other than that you are connecting to a VPN’s server. This can be useful if you do not want your ISP to see what webpages you are connecting to. If you torrent or access pirated content or are trying to circumvent state censorship then a VPN is a must.

Using a VPN also has the additional benefit of hiding your true IP address from third-party websites and services, helping you blend in to the crowd of other users on the network and preventing IP based tracking.

However keep in mind that a VPN does not provide anonymity. Do not believe VPN company marketing. With a reputable VPN you will most likely be paying with your bank details (although some offer cash and cryptocurrency payments) which creates a paper trail directly to your real world identity. If you really need to be anonymous the [TOR](https://www.torproject.org/) browser would be your best bet.

When choosing a VPN provider keep in mind the following. For more depth and recommendations see [Privacy Guides](https://www.privacyguides.org/en/vpn/):

*   Where is the VPN provider based? Ideally you would want to choose one that is outside of the jurisdiction of the [14 Eyes](https://tuta.com/blog/fourteen-eyes-countries), a group of western countries intelligence agencies. This is due to these countries legally permitting the forced surveillance/ wiretapping of VPN servers without public disclosure.
-   Does the VPN provider have a no logs policy that is regularly audited by outside independent third parties?
*   Is the applications and even server code open source? Having the code used in the VPN applications and servers being open source and viewable by anyone is a must to ensure security and transparency!
-   **Stay away from free VPNs!!!!!!** If you are not paying for the product you are the product! While there are exceptions such as ProtonVPN offering a very limited free option, non paid [VPNs as a rule are not to be trusted.](https://www.top10vpn.com/research/free-vpn-investigations/ownership/)
*   Look into exactly who is behind the VPN provider. As of this year [105 popular VPNs on the market are run by just 24 companies, many of them being advertising and/ or adware related.](https://vpnpro.com/blog/hidden-vpn-owners-unveiled-97-vpns-23-companies/)
    
#### 6.4 Use a Cloud Storage Service that Offers End-to-end Encryption

Many cloud storage providers require your full trust in them. Google Drive for example [scans all of your files](https://www.nytimes.com/2017/09/06/technology/personaltech/security-google-cloud.html) and prevents/ deletes illicit files such as suspected [copyrighted content](https://torrentfreak.com/google-drive-uses-hash-matching-detect-pirated-content/). If your aim is to achieve a modicum of digital privacy this is clearly unacceptable and you may want to swap to an open source end to end encrypted alternative such as [Proton Drive](https://proton.me/drive) or self host. See [Privacy Guides](https://www.privacyguides.org/en/cloud/) for all your options.

If swapping to a privacy respecting end to end encrypted alternative is not feasible for you due to budgetary or practical reasons you should consider encrypting your files using encryption software like [Cryptomator](https://cryptomator.org/) prior to uploading your files. See [Privacy Guides](https://www.privacyguides.org/en/encryption/) for more encryption options.

#### 6.5 Separate Your Work/ Education From Your Personal Life

You should be separating your personal digital life from your work/ schooling. This is even more important if you have software that has to be downloaded or if your work/ educational institute provides you with a device. There are many cases of [schools](https://www.wired.com/story/student-monitoring-software-privacy-in-schools/), [colleges](https://www.washingtonpost.com/technology/2019/12/24/colleges-are-turning-students-phones-into-surveillance-machines-tracking-locations-hundreds-thousands/) and [workplaces](https://www.brookings.edu/articles/how-employers-use-technology-to-surveil-employees/) using surveillance technology to monitor their students and employees.

As such do not use a company/ school provided phone or laptop for personal matters and vice versa. Or at the very least compartmentalize the two using different browsers/ browser profiles and profiles if on Android.

#### 6.6 Use Free Libre Open Source Software When Possible

I would highly recommend changing the applications and services you use to free and open source alternatives. These are often just as functional if not more convenient to use due to there typically being less invasive and annoying account creation requirements and online connectivity checks.

Privacy Guides yet again has a great selection of vetted alternatives under their [tools page](https://www.privacyguides.org/en/tools/). Some examples of alternatives you could use are:

*   LibreOffice instead of Microsoft Office
-   The browsers mentioned previously instead of Chrome
*   A privacy respecting search engine such as DuckDuckGo, Brave or StartPage instead of Google
    
Most applications will have a FOSS alternative. All you have to do is an internet search to see what is out there!

#### 6.7 Use Privacy Respecting Frontends for Popular Services

A frontend is the part of a software or application that users directly interact with. It includes the user interface and experience design elements, enabling users to access the software's functionality.

There are many privacy respecting frontends for popular services that you may use. Using a frontend can offer privacy benefits by you with more control over your data and interactions. Since frontends are often developed independently from the backend services they connect to, they can implement privacy-focused features such as ad-blocking and tracker-blocking. By accessing services through a frontend, you can reduce your exposure to tracking cookies and invasive data collection practices employed by some websites and applications. Additionally, frontends may offer alternative authentication methods or proxying services, allowing users to access content anonymously or without revealing personally identifiable information.

Some great examples are as follows:

*   [FreeTube](https://freetubeapp.io/) or [Invidious](https://invidious.io/) to replace YouTube on desktop
-   [NewPipe](https://newpipe.net/) or the amazing [GrayJay](https://grayjay.app/) (which will be the topic for a future post) to replace the YouTube application on Android
*   [Yattee](https://github.com/yattee/yattee) on IOS, MacOS and TvOS
-   [ProxiTok](https://github.com/pablouser1/ProxiTok/wiki/Public-instances) instead of TikTok   

See more on the [Privacy Guides section on frontends](https://www.privacyguides.org/en/frontends/)!

### 7. Resources for Further Research

* [Privacy Guides](https://www.privacyguides.org/en/) (an excellent resource for everything privacy and security)
-  [Surveillance Self Defense from the EFF](https://ssd.eff.org/) (a great resource from a non-profit fighting for privacy rights)
*  [PrivSec.dev](https://privsec.dev/posts/) (a blog from a highly talented cybersecurity researcher)
-  [The Hated One](https://www.youtube.com/@TheHatedOne) (high quality video essay YouTube channel focusing on privacy, surveillance and digital matters)
*  [NBTV](https://www.youtube.com/@NaomiBrockwellTV) (YouTube channel from a non-profit focusing on privacy and digital sovereignty)
-  [Mental Outlaw](https://www.youtube.com/@MentalOutlaw) (more comedic YouTube channel focusing on digital security, privacy and general technology news)
*  [Side of Burritos](https://www.youtube.com/@sideofburritos) (YouTube channel focusing primarily on GrapheneOS)
    
### 8. A final note from me

With regards to this post I would highly advise that you do some of your own research. While I have tried to highlight the best practices and privacy solutions these are always subject to change. I cannot encompass everything that will make you more secure and private online in any series of posts. I do hope however that this digital privacy guide is of use to you and proves a valuable resource for you. For those seeking to learn more I cannot recommend [Privacy Guides](https://www.privacyguides.org/en/) enough!

I also recommend checking out the Privacy and Security [Resources Page]({{< ref "/resources" >}} "Privacy & Security Resources") on my website for great reading/ watching recommendations and repositories of PrivSec knowledge!

* * * 

_When people want privacy, they do not want to hide away their information from everyone; instead, they want to share it selectively and make sure that it is not used in harmful ways. Privacy is not all-or-nothing—it is about modulating boundaries and controlling data flow._ __-The Myth of the Privacy Paradox, Daniel J. Solove__

* * * 

{{< substack >}}