## Apple and Google accelerate coronavirus contact tracing apps plan

keywords: apple tracing version accelerate google contact users apps system authorities coronavirus plan data

authors: Leo Kelion, Technology Desk Editor

publish date: None

![](https://ichef.bbci.co.uk/news/1024/branded_news/15D8/production/_111929550_mediaitem111929549.jpg)

[中文翻译](Apple%20and%20Google%20accelerate%20coronavirus%20contact%20tracing%20apps%20plan_zh.md)

[Original Article](https://www.bbc.com/news/technology-52415593)

Apple and Google have tightened privacy measures in the contact-tracing scheme they are offering to health authorities and brought forward its launch.

The tech giants now intend to release a software building block to developers on Tuesday, allowing them to build compatible apps. A fortnight ago, the firms said it would take until mid-May.

Apple's version will require an updated version of its mobile operating system.

Some countries, however, would prefer the firms to be less prescriptive.

France and Germany have confirmed they are pursuing designs of their own, and are pressing Apple to let them have greater access to the iPhone's capabilities without having to adopt the initiative.

In a blog published earlier, NHSX, the digital wing of the NHS, confirmed it was "working with Apple and Google" on its UK contact tracing app, but stopped short of committing itself to the companies' framework.

Media playback is unsupported on your device Media caption WATCH: What is contact tracing and how does it work?

Virus alerts

Contact-tracing apps are based on the principle that people's smartphones can be used to log when two people are in close enough proximity for long enough that there's a high risk of contagion if one of them has the coronavirus.

If one of the phone-owners is subsequently diagnosed as having caught the virus, others they might have infected can be sent alerts advising them to get tested or go into self-isolation.

By combining the use of such apps with other measures - including manual contact tracing by humans and frequent handwashing - the hope is that the spread of the disease can be slowed or suppressed.

Apple and Google's system is based on the use of Bluetooth Low Energy (LE) beacons. Effectively, the two handsets wirelessly "shake hands" with each other, and in doing so exchange a string of randomly-generated numbers that can be used to log matches without revealing the users' names, location or other identifying information.

Representatives from the team responsible said they had listened to feedback received from health authorities, governments and data protection watchdogs, and made changes to both increase security and to make it easier for apps to be built using the API (application programming interface) building block they are providing.

These changes include:

giving information about different devices' Bluetooth power levels, to help developers better estimate how far two handsets are from each other

letting developers decide for themselves how close together phones should be and for how long to trigger a handshake

preventing the phones from logging any meeting as having lasted longer than 30 minutes

encrypting data about the transmission power of the phones, to prevent anyone retrospectively using the logs to reveal what models had been involved

changing to a different encryption algorithm - AES - to reduce the toll on battery life

Apple will require users to install a new version of iOS 13 to use the API. That means any handset older than the iPhone 6S - which was released in September 2015 - will be incompatible.

Any Android device running version 6 of Google's operating system, which launched in October 2015, or higher will work without needing an update.

Background Bluetooth

Apple and Google's system has been described as "decentralised" as the contact-matching takes place on the users' devices, preventing the authorities being able to see who got an alert unless a user decides to disclose the fact - for example to request a diagnostic test.

But some countries are pursuing "centralised" designs. This would give them more insight into the number of alerts being sent out and potentially the ability to re-identify users, meaning they would not truly be anonymous.

However, these nations face a problem with the iPhone versions of their software. Apple places restrictions on third-party apps' use of Bluetooth, which it is only dropping if the authorities adopt its scheme.

"Bluetooth is heavily restricted on iOS when the app is in the background," explained Quentin Zervaas, a developer who is building a Google-Apple compliant app.

"It can be used to occasionally broadcast or receive data while backgrounded, but there are no guarantees how frequently this would be, and the app would be competing against any other apps on your phone trying to use Bluetooth.

"So for contact tracing it can't constantly send or receive the necessary data necessary to effectively keep track of every device you come into contact with.

"[This] is why I think all the contact tracing apps should be using the system level tools Apple and Google are rolling out."

Apple and Google declined to discuss the implications of countries that opt to go it alone.