---
title: "Reclaim Your Privacy | Part 2: Digital Security"
date: 2024-02-01
draft: false
image: /images/securitycover.jpg
description: "Part 2 out of 3 on how to protect yourself online and regain control over your privacy."
toc: true
---

### 1. Further Down the Rabbit Hole

The focus for today is on the tangible steps you can take to enhance your digital security. This guide will encompass the types of software you can use, best practices and things to look out for and keep in mind.

In the previous part to this series of posts, I delved into how to craft a simple yet comprehensive privacy and security management strategy. This chiefly involved how to craft an effective threat model: in order to identify what your digital assets are, who your threats are and how you should go about protecting said assets from said threats. Key terminology is also defined as well as some essential privacy and security concepts. Part 1 can be seen [here]({{< ref "/blogs/threatmodel" >}} "Threat Modelling") and I would highly recommend referring to it before delving into this post. 

Where I have recommended specific software please keep in mind that recommended privacy tools change often. I have chosen to recommend established and long running projects but these can become out of date or insecure as time passes. I would recommend consulting [Privacy Guides](https://www.privacyguides.org/en/) for up to date and in depth information on the privacy and security tools that are at your disposal.

### 2. Basic Security Steps for the Average Joe

This first tier includes practices and software that everybody concerned about their digital security should implement and make use of. Following these steps will generally not make you more private online but will increase your security from threats such as phishing, hacks and malicious software. See my previous post for the difference between privacy and security.

These actions are fully compatible with devices, services and software you are currently using (Apple, Google, Microsoft etc) and will not require much effort, time investment or research to implement. While putting these steps into action will not lend itself to increasing your privacy, they are a necessary prerequisite for attaining a higher degree of it online. It is impossible to have meaningful privacy gains if your digital life is not properly secured.

Now in no order of importance:

#### 2.1 Create Strong, Unique Passwords and Use a Reputable Password Manager

Passwords should contain a minimum of 12 alphanumeric characters (16+ is recommended), should not contain dictionary words and should only be used once per website, application or service. These passwords are of course near impossible to remember and this is why most internet users use the same [insecure, possibly leaked, recycled passwords](https://www.zdnet.com/article/were-all-still-using-the-same-passwords-even-after-theyve-been-breached/) for nearly everything online. This is where a password manager comes in.

A password manager stores all of your login information for all of the internet services you use in one application that is secured with a singular ‘master password’. So instead of having to remember dozens of complicated passwords you need to remember just one. Most modern password managers will offer additional features such as autofill, auto password generation and the storing of banking information. I would [advise against the use](https://www.zdnet.com/article/is-it-ok-to-use-your-browsers-built-in-password-manager/) of your web browsers built in password manager as these are: typically less secure, have reduced functionality, locks you in to that browsers ecosystem (Google👀) and limits your ability to access your password vault from only that browser.

Most standalone password manager can be used as a standalone app on any of your devices and as an extension within any browser. The most intuitive and easy to use password manager that I would recommend is free and open source [Bitwarden](https://bitwarden.com/), which offers a host of functions including automatic syncing between all your devices. Setup instructions can be found on its [YouTube account](https://www.youtube.com/playlist?list=PL-IZTwAxWO4VKISOqPdMBXAtKBAu0gd4_) and a host of other [tech news sites](https://www.pcworld.com/article/1339204/why-i-switched-to-bitwarden-for-my-password-manager.html). For further information and more in depth recommendations see this section of [PrivacyGuides](https://www.privacyguides.org/en/passwords/) on password managers and this section on [passwords](https://www.privacyguides.org/en/basics/passwords-overview/) more generally.

![Bitwarden](/images/bitwarden.png)

#### 2.2 Use Multifactor Authentication (MFA)

Most of your digital accounts and especially critical digital service that you use (anything tied to your banking information or your email for example) should be set up with [multifactor authentication](https://www.rsa.com/multi-factor-authentication/what-is-mfa/). Multifactor authentication can take the form of an additional question posed on login, a text message or email with an OTP (one time password) or a physical authentication key. The best option for both security and convenience is an authenticator app, such as Google Authenticator, Microsoft Authenticator or what I would personally recommend, open source [Aegis Authenticator](https://getaegis.app/) if you are on Android. The use of MFA will protect you from unauthorized access to your accounts even if attackers have your login credentials. Combining this with a strong and unique password will vastly increase your security against data breaches and password leaks.

Setting up an MFA app with your accounts is very simple and straightforward and is offered by most major service providers with easy to follow guides a quick internet search away. See the MFA section within [PrivacyGuides](https://www.privacyguides.org/en/multi-factor-authentication/) for more in depth information and suggestions.

#### 2.3 Use an Adblocker

Despite the protestations of online advertising firms and attempts from [Google to limit the functionality of adblockers](https://arstechnica.com/gadgets/2022/12/chrome-delays-plan-to-limit-ad-blockers-new-timeline-coming-in-march/), using an adblock service is a must in todays digital world. Malicious adverts or ‘[malvertising](https://www.cisecurity.org/insights/blog/malvertising)’ are all too common with the even the [FBI](https://www.ic3.gov/Media/Y2022/PSA221221) recommending the use of adblocking software. Adblockers work by filtering content that is sent to your device. The added bonus, on top of increased security, is that you won’t have to deal with annoying adverts on your favorite websites such as YouTube!

The easiest way to enable ad filtering is through the only adblocking browser extension I would recommend, the gold standard of content filtering: [Ublock Origin](https://ublockorigin.com/). For basic users, this open source extension, only requires you add the extension to your browser to properly function. For more advanced users see the Ublock Origin [wiki](https://github.com/gorhill/uBlock/wiki). Certain browsers such as [Brave](https://brave.com/) block ads by default and require little in the way of setup and are also a good choice.

*Note: Google is waging a war on adblockers and your adblocking functionality on Chrome may vary as we go into the future. Firefox and/ or Brave are what I would recommend.* 

#### 2.4 Encrypt, Encrypt and Encrypt Some More!

I cannot stress enough how important it is to make sure your devices, the services you use and your communication methods are adequately encrypted. Despite the propaganda that governments may spout regarding encryption, it is a vital tool to secure your digital life.

Your devices should be encrypted with a strong password. This ensures that if your device is lost, stolen or subject to an [evil maid](https://www.howtogeek.com/689599/what-is-an-evil-maid-attack-and-what-it-teaches-us/) attack the sensitive data contained within it cannot be accessed by a third party. Think of all the personal data that you have stored on your devices: important documents, intimate photos, banking information and more. You would not want this to fall into the wrong hands.

Modern smartphones, both IOS and Android are encrypted by default provided you use a PIN lock, password or some other form of device security. The most secure way to encrypt your phone is by using a strong, unique password but a 6 digit PIN will suffice for most users. Whether your macOS or Windows device is encrypted can vary based on your device model and operating system and can be a bit more complicated.

On macOS you can check if your device is encrypted by looking for ‘FileVault’ under ‘Privacy and Security’ in your settings. See below (may change with future macOS updates).

![MacOS encryption](/images/macencryptionimage.jpg)

On Windows devices this process is a bit more complicated. Windows 10/11 Pro, Enterprise and Education offer BitLocker encryption. Windows 10/11 Home users are limited to Windows Device Encryption and only on supported hardware. Consult the most recent Microsoft documentation as this seems to change often. If your device is unable to utilize Microsoft encryption you can always turn to a third party disk encryption program such as the audited and open source [VeraCrypt](https://www.veracrypt.fr/en/Home.html) to secure your device. I would highly recommend doing this if your device does not offer encryption by default.

Linux users probably do not need any advice regarding this but most distributions will offer full disk encryption, probably LUKS, on install. Ensure that this is enabled as this cannot be done post installation other than through 3rd party tools.

With regards to communications try and communicate with people through end-to-end encrypted (E2EE) messaging applications such as Signal or WhatsApp. At least limit the sending of very sensitive and intimate data to those applications that offer E2EE. E2EE ensures that only you and the intended recipient are able to access the content of a sent message.

#### 2.5 Practice some Basic Digital Hygiene!

Just like you wash your hands before eating and after using the toilet (hopefully), it is wise to practice the equivalent online.

*   Be very careful of what applications and files you download. Always make sure you download from a verified and authoritative source such as the Google Play Store, Windows Store, Apple Store or legitimate websites. For example if you want to download Firefox, download it from mozilla.org or an official app repository and not anywhere else. Keep in mind that downloading applications from official stores is still not 100% safe. The Google Play Store for example has served [millions of users with malware](https://www.zdnet.com/article/google-play-malware-if-youve-downloaded-these-malicious-apps-delete-them-immediately/) but this problem is not limited to just [Android](https://www.wired.com/story/apple-app-store-malware-click-fraud/). Always do you own research when downloading new apps, especially ones that are not very popular or are unknown. A good rule of thumb is to check the permissions required from the app. This can be done within the settings of your device or in the app store. A flashlight app does not require access to your call history or contacts for example. 

![appememe](/images/flashlightappmeme.jpg)

*   When in doubt don’t click it. If a link on a website seems sketchy it probably is. Rather be safe than sorry!  
-   Use fake info when you can. Of course when know your customer (KYC) rules apply, such as for banking, do not do this. By this I refer to the various apps you may download that ‘require’ personal information such as an account on a sports app or a gaming application. There is simply no need for you to be giving out your full name, date of birth and location in order to follow the Rugby! The more info you give out to more entities, the much greater the chance that data will be leaked in a breach.   
*   **ALWAYS KEEP YOUR DEVICES AND APPLICATIONS UP TO DATE WITH THE LATEST SECURITY PATCHES.** There are countless examples of massively damaging malware attacks that could have been [avoided if security updates were done in a timely manner.](https://www.zdnet.com/article/wannacry-ransomware-hospitals-were-warned-to-patch-system-to-protect-against-cyber-attack-but-didnt/) Enable auto updates, especially for security patches.
-   There is typically [no need for antivirus software](https://www.nytimes.com/wirecutter/blog/best-antivirus/). Windows defender and Apples in built software are more than adequate. Modern antiviruses are pretty much redundant, slow down your computer, can be extremely [privacy invasive](https://restoreprivacy.com/antivirus-privacy/) and can be vectors for malware in themselves. This goes for mobile phones as well.   
*   When connecting to unsecure WiFi networks use a reputable virtual private network (VPN) or at least do not transmit any sensitive data, such as conduct banking, over it.
-   Always check the websites that you visit are legitimate and use HTTPS encryption. This can be checked through looking at the web address and your browser security button within your search bar, a padlock on Chrome for example. If possible enable the option within your web browser to only connect to HTTPS sites. This can be found in Firefox and Brave browser for example.

* * * 

_"People often represent the weakest link in the security chain and are chronically responsible for the failure of security systems."_  __-Bruce Schneier__ 

* * * 