CMPD333
TOPIC O2: CYBER ATTACKS
OUTLINE
• Part 1: Types of Cyber Attacks
• Part 2: Malicious Software
Overview
3
• Let’s have a read:
• Hackers Are Going 'Deep-Sea
Phishing,' So What Can You Do
About It? | Threatpost
• Phishing Attacks Skyrocket with
Microsoft and Facebook as Most
Abused Brands | Threatpost
Common Threats to End Users
• Threats and vulnerabilities are the main
concern of cyber security when
protecting Asset.
• Two situations are especially critical:
1. When a threat actor acts to harm the
asset, a risk will occur. (Thief -> Steal)
2. When a Vulnerability causes the Asset
to be open to risk. (Hole on the fence)
• ATTACK causes the risk to happen
4
Term Example in Nora’s
scenario
Example in cyber
security
Asset Scooter Employee database
Threat Steal scooter Steal data
Threat actor Thief Attacker, hurricane
Vulnerability Hole in fence Software defect
Attack vector Climb through hole in
fence
Access web server
passwords through flaw in
OS
Likelihood Probability of scooter
stolen
Likelihood of virus
infection
Risk Stolen scooter Virus infection or stolen
data
PART 1: Cyber Attacks
Identifying Types of Cyber Attacks
• Client-side Attacks
• Web Attacks
• Network Attacks
• Wireless Attacks
• Social Engineering Attacks
6
Client
-side / Host Attacks
• Most common attacks are those
made on desktop PCs, often
known as clients or host. • For most companies, it means
systems that use the Windows
operating systems, as well as
those that use Mac OS and Linux.
• Most of those clients are always
connected to the organization’s
network.
• Newer attacks also focuses on
tablets and smart phones too!
7
Privilege escalation
• It begins by stealing one user’s account
then proceed to attempt to gain
elevated access to other resources.
• E.g.: Transitive attack - take advantage
of existing privileges to gain additional
attacks.
• Attackers take advantage of permissions
on one system (A) that allow access to
another system (B), which is trusted by a
third system (C).
• Then, despite not having rights to take
action on C from system A, an attacker
can use a transitive attack to pass
through otherwise strong security.
8
Insider Threats • Members of your own organization’s staff,
or others who already have privileges to
access or administrate your network and
systems, can use privilege escalation as
well.
• Even users who have been granted only
low
-level access can use privilege
escalation attacks, install malware, or
provide their credentials or data to third
parties.
• Considering insider’s threat does not
always mean the employee has ill
intentions, sometimes they were just
manipulated to do so.
9
Zero-Day attacks
• Our devices usually have
vulnerability or certain
feature to patch.
• Attacks that occur before
the vulnerability is
announced or fixed, is
known as zero-day
attack.
10
• There will be no patch available for a zero-day exploit when it occurs.
• Because a zero day attack doesn’t have a patch available, this can quickly
compromise hundreds or thousands of systems. Fortunately, when these attacks do
occur, the worldwide information security community reacts quickly.
• One example of zero day library can be accessed from: Zero-day Vulnerability Database - zeroday.cz

Zero-day exploits are when a malware exploits the vulnerability in software it is sometimes called zero hour or day zero attack in this video you will learn what zero day exploits is and how to stay away but before we start press the like button and subscribe to our Channel what is zero day exploits software is released for the users after several testing phases however it is never perfect there are always unforeseen 

 Flaws to resolve these issues the developer subsequently releases updates the problem could be reported by the user or discovered by self testing however when this vulnerability is discovered by criminally inclined people it can be exploited for nefarious purposes they can use it to gain illegal access to users computers by injecting a malware this type of vulnerability is called zero day vulnerability when an attacker exploits it 

 It's called zero day exploits attackers exploit these vulnerabilities by various means web browsers and software like Java and flash are more vulnerable so attackers might locate unsecured users through email attachments or software bundles zero-day attacks occur within a specific time frame known as a vulnerability window this is the time beginning from the first vulnerability exploit to the point at which a threat is countered zero day attacks are 

 Strategically implemented to cause maximum damage within a short span of time how to stay away from zero day exploits as you know there are no immediate fixes available to resolve the exploit because the developer is still unaware of its existence for a better protection you should have a behavioral blocker installed on your system it monitors the behavior of all programs when a program takes action that matches the malware 

 It blocks that program thus the zero-day attack is prevented malware Fox anti-malware has a behavioral blocker integrated into its system and is a proven anti-malware product that safeguards users against zero-day attacks so download and install malware Fox when the loophole is discovered the developers release security patches so you should install the security patches immediately whenever they are available by following these simple steps you 

 Could prevent zero-day exploit if the information in this video helps you don't forget to press the like button and subscribe to our channel we keep uploading such informative videos so press the bell button to receive the alert when we do that 

Identifying Types of Cyber Attacks
• Client-side Attacks
• Web Attacks
• Network Attacks
• Wireless Attacks
• Social Engineering Attacks
11
Web Attacks
• Web application are usually run from a browser.
• The attacker attempts to breach a web application.
• Common attacks of this type are:
• Cross Site Scripting (XSS)
• SQL injection
12
Cross-site scripting (XSS)
• Exploitation of a web application
vulnerability that allows
attackers to inject scripts into the
webpages that are served to
visitors of a website. XSS relies
on the user’s trust of the site.
• E.g.: The Samy worm, the
largest known XSS worm,
infected over 1 million MySpace
profiles in less than 20 hours.
13

I'm gonna show you the most popular way to hack a website where you can steal private information, hijack accounts, take over web pages and other illegal things to get you thrown in jail HOLD ON! This isn't for illegal activity,
it's for educational purposes only. Notice, the lights are on, I'm not wearing a hoodie and I don't even have a Matrix-themed terminal. So there's NO crime goin' on here. You have to promise me you'll use this information for GOOD and not EVIL. 

 So when you're ready, this is the recipe for the basics of Cross-Site Scripting. Hello, world! I'm Jesse from Chef Secure. Cross-Site Scripting, or XSS,
is a security vulnerability in web applications That allows evil hackers to inject their
own code inside a web page. Yep. That's bad. With the power of scripting,
cybercriminals can use your web applications to steal passwords, install malware or WORSE... The first step in Cross-Site Scripting
is to inject a script element into a web page Now, web pages are built using HTML,
which uses tags to create elements. Yep. There are a lot of 'em. Let's get started.
Go to the  Script Injection  example for this recipe below, 

 And pause the video when you need to,
so you can follow along and gain hands-on experience rather than just sitting there all awkwardly,
watching me do everything by myself. You can see that when you type something in and click the UPDATE button, it gets rendered on the page. So if you add more HTML,
what do you think would happen? Open an HTML tag using
less-than and greater-than characters surrounding an element name,
like p for paragraph Then add some content, and then add a closing tag after that – which is just the same as an opening tag
only there's a slash in front of the element name. Then click the  UPDATE  button. 

 You see that instead of writing text,
you actually changed the HTML of the web page by adding a new paragraph element. While simple, this is very, very powerful,
because JavaScript controls the web page. And if you can inject a  script  element instead, you now control exactly what happens in the browser. And THIS is how XSS works. So go ahead and inject  script  tags this time. Start with your opening script tag,
followed by your closing script tag. Now for the content that goes inside... This, my friends, is where we enter
the f-[bleep]-d up world of JavaScript. ( phone buzzing ) ( phone buzzing ) 

 WONDERFUL world of JavaScript! Javascript can be...
confusing at times. But what it does well, it does EXCEPTIONALLY well like letting you hack websites or... making them more INTERACTIVE. Performing actions in JavaScript is like any other programming language
where you just call functions. You can do this by typing the name followed by  parenthesis . And anything that goes inside the parenthesis gets passed as data, or arguments,
that the function can use. AND like other programming languages,
you can set values using an  equals sign . Right now, try calling the
alert function within your script tags. 

 So type in alert followed by parenthesis then click the UPDATE button
and watch your script execute. Because you see this alert pop up it means your script was
injected into the page successfully and ran due to an XSS vulnerability. While you're at it, get some practice
with arguments as well. So type in the number 1 to the alert function. Click the UPDATE button
and you'll see it alert 1. Or pass in text surrounded by
either single or double quotes to make a  string ,
and you can alert something you really love. I'm going to alert food. Because I love food. 

 I'm always thinking about – WAIT A SECOND! CHEF? Secure... Alerting is the most common function used by
both cybercriminals and security researchers alike to find vulnerabilities in websites. Now keep in mind that the alert function
is just a placeholder showing that a script can be injected. And once a vulnerability is found an attacker can easily replace this with a
malicious exploit that causes much more damage. Consider something simple: instead of alerting in our example,
let's just destroy the whole web page by removing all the HTML. 

 In JavaScript, document.documentElement.innerHTML
contains all the HTML of the web page, so just change it by setting it equal to an empty string. In our example, if we type that in: Click the UPDATE button and... it's gone. I'm gonna show you more about how
cybercriminals can exploit websites in a later recipe, but if you're just testing for vulnerabilities,
an alert is really all you need most of the time. So from here, what you really need is just
to be creative and explore so you can find more vulnerabilities. Say you need to type in something in a website,
such as a username or a status update, there's always a chance that it could
contain an XSS vulnerability, so it's worth a shot. Of course websites do have protections against XSS, 

 Some of them even built directly into
the frameworks on which they're built. But despite this, and despite
the frameworks being around for several years, the number of XSS vulnerabilities is still rising like crazy! And that's because writing secure,
resilient code can be quite tricky at times. And even with automatic protection,
you can still screw things up pretty badly. Trust me.
I've done it more than once. And I'll do it again,
I promise! But that's the point of having defense in depth,
which I will teach you as we go along in this course. But mistakes happen,
so let's look on the bright side: at least there are plenty of vulnerabilities to find and fix before cybercriminals can come
and hack your application. 

 Wait, that's not comforting at all... But that's all the time I have for now.
Good bye, friends. 

SQL Injection • Most common attacks against
web applications.
• Rely on injecting Structured
Query Language (SQL)
instructions into an application’s
input in a way that causes the
application to use its privileges
to run the commands against the
database it uses.
14

Sequel injection is one of the top three most common web app risks and it's probably in part because of how simple it is to perform so who's most vulnerable any website that sequel database driven with poor code so how does it work well this attack is very commonly done on login screens so let's first see what's happening your username and password after they're submitted your poorly designed site the name and 

 Password strings are directly inserted into a sequel statement which probably looks like this with this statement the application is asking the server do we have a user with the name Chris and the password my past one and if so it grants the user access to their account so the first thing an attacker will do is find out if the site is using a sequel database by entering a single quote into the username field I'm submitting single quotes are special characters in the 

 Sequel language and using them as part of a username will cause an error if the website doesn't check for them once the error message is displayed the attacker can confirm that the websites using sequel as well as other useful information and now the real injection begins the attacker can enter the following command logic which will render the following command the command will force the selection of a valid user name because the evaluation of one 

 Equals one is always true now most of the time the server will login the attacker with the credentials of the first user in the table the range of command manipulations is vast the record retrieval to complete table dilution so you can and how damaging this exploit can be to a website so how can we prevent this form of attack well make sure that you do the necessary string checking for special sequel characters it's really 

 Not that many more lines of code and it's most definitely worth the time there's also automated software available that can check your entire web application for injection as well as other vulnerabilities so you should check it out it's called rational AppScan it's really awesome software that's it for now I hope you learned something 

Identifying Types of Cyber Attacks
• Client-side Attacks
• Web Attacks
• Network Attacks
• Wireless Attacks
• Social Engineering Attacks
15
Type Characteristics
Spoofing
Provides false information on a network

How to prevent spoofing attacks cyberattacks come in many forms such as crippling infection DDoS attack password attack sequel injection and so on there are certain attacks that are underhanded spoofing is one such cyber attack that can breach enterprise networks without even being detected the spoof attackers have ample amount of time launch the attack against the network of spoofing attacks our email spoofing 

 This form of spoofing is done by imitating the domain our email address with slight deviations from the original the email may contain links to malicious web sites or malware caller ID spoofing this form of spoofing is done by disguising the phone numbers when making calls to the receivers and extract sensitive information such as ATM PIN password or social security number IP spoofing this involves The Masquerade 

 Of a computer IP address to keep the identity of the malicious attacker hidden the attackers use the IP address to penetrate into the networks to prevent common spoof attacks there are a range of steps you can implement to keep yourself protected from spoofing attacks some of the best ways are deploy spoof protection tool use encrypted protocols packet filters and VPNs install firewalls 

 Use antivirus software two factor authentication go here to know more about spoofing and ways to prevent it is one of the leading cybersecurity service providers in the USA we provide cutting-edge security solutions to ensure that the sensitive data is safe want to know more about our services contact us 

Packet Sniffing Access to credentials, files, and any other information
Man-in-the-middle
Read, modify, and in some cases they can even change the
packets

- Picture it, you don't have mobile data, so you need to connect to a public Wi-Fi. Then you have to buy something
from a random online store. And in a few days, your bank
account balance goes to zero. All right guys, so today I'm
going to tell you everything about man-in-the-middle attacks
and how to prevent them. But first, before you fall victim to any unsolicited attacks, or if you wanna enjoy
promotions and discounts, make sure you subscribe to our channels for the latest and all the best VPNs. 

 You might use public Wi-Fi
networks often, and why not? It's totally free and a convenient way to not spend your mobile data. But have you ever thought
about your internet and device security when doing so? Many of these public
networks are susceptible to man-in-the-middle attacks
where your data can be read, stolen and altered by cyber criminals. Man-in-the-middle attacks are some of the most common cyber attacks. Why, because it's easy and
potentially very lucrative. Not only can you expose your
financial details this way, 

 But you also risk losing
all your personal, valuable information because of it. So what are man-in-the-middle attacks? As the name suggests,
the bad guy inserts him or herself on a communication
between two devices and reads the traffic
without anyone noticing. Usually those two devices are your laptop and the Wi-Fi router. If you're not using an
encrypted connection, which usually happens when
you visit an insecure website, the man in the middle can learn all sorts of
sensitive information. 

 So in short, a man-in-the-middle
attack can lead to data and identity theft, online
bank information exposure and any other information
you don't want others to see going to someone malicious. Even HTTPS servers are very vulnerable to man-in-the-middle attacks. As recently as 2016, it was found that 95% of
HTTPS servers are vulnerable. Scary, right? It's not just about laptops either. I mean, think about it. What device do you use the most 

 And need the most protection on? That's right, your phone. You carry it with you
to the shop, to the cafe and you even connect to
strange public Wi-Fi connection so you don't have to use your mobile data. Believe it or not, phones are just as susceptible to man-in-the-middle
attacks as any other device. Fortunately, there are ways to preventing man-in-the-middle attacks and VPN providers are the best way to go. These services encrypt your connection, 

 Which will protect you from
man-in-the-middle attacks, even if you're visiting
insecure HTTP websites. Be sure to click the popup banner, to see our full list of the
best VPNs and get up to 84% off. If you're not sure
which VPNs are the best, I can tell you now that you
should either go for NordVPN, ExpressVPN or Surfshark. The reason be is that all three offer
top notch security features that especially prevent
man-in-the-middle attacks. Some security features,
including location masking, bypassing geo-blocking
and internet censorship 

 And overall internet security posture. All of these features
are especially important if you plan on regularly using
open or public connections. You can also try to prevent them yourself by making sure you don't open dodgy emails asking you to update your credentials, installing antivirus software and ensuring all the sites
you visit start with HTTPS, because the S means it's a secure page. Some common types of middlemen attacks include creating fake
interactions, websites and unsecure URLs without you noticing. 

 Unsecure server connections,
email hijacking, fake Wi-Fi connections
and stealing passwords, addresses and other sensitive information you provide the certain web pages. While internet thieves or
man-in-the-middle attacks are sly and difficult to notice, you can never hurt to learn
more about avoiding them. Getting solid VPN software and keeping your data to yourself. No one wants to wake
up with a major deposit out of their account due to
stolen banking details, right? And that's it guys. 

 Be sure to check out
some awesome VPN deals in the description below and subscribe to our channel
for more awesome videos. Thanks for watching. 

Replay Attacks
Uses previously captured data to replay a connection,
authentication, or other session

Hi this is Bob he would like to log in his web mail account let's see what happens Bob starts a login session with the server this is Eve she would like to know Bob's password so that she will be able to send emails pretending to be Bob Eve listens to Bob's login session Bob types his username and password in the login page and sends this information to server Eve by listening to the 

 Transportation between Bob and the server obtains Bob's credentials if the username and password are correct Bob gets a permission to log in Eve will now be able to log into Bob's account by using Bob's username and password this is a well-known attack named man in the middle we suggest a different authentication method that solves this problem when Bob tries to log into his email account the email server will send him a challenge a series of six random 

 Decimal digits as Eve is listening to Bob's session with the server she will also obtain the challeng the challenge the shared secret between Bob and the server is a very simple formula to manipulate this challenge let's assume Bob has chosen that the secret formula is multiplying the first number in the challenge named a with the second number in the challenge named B and then subtracting one in this case for this challenge the response equals to seven 

 Bob sends the response back to the server the server receives Bob's answer and lets him in as Bob was able to prove his identity without disclosing his password eve even if has listened to the whole login session will not be able to deduce the formula if she tries to log in she will get a new challenge she will not be able to calculate the response and thus will not be able to steal Bob's identity now after you are familiar with the new authentication 

 Method you are asked to register by choosing a username type your email address and the most important part to choose a secret formula this will be the secret you will share with the server then using the secret formula you have chosen you will have three Tri trials to log into the system the indicators in the upper left corner will show you if you succeeded to log in in each trial finally you'll be be asked to fill 

 A short survey thank you 

DoS and DDoS Crashing or disabling or damaging or destroying the
service/system
Denial of service (DoS) and distributed
denial of service attacks (DDoS)
17
DoS attack
typically uses one
computer and one
Internet
connection to
flood a targeted
system or
resource.
DDoS attack uses
multiple
computers and Internet
connections to flood
the targeted resource.
Identifying Types of Cyber Attacks
• Client-side Attacks
• Web Attacks
• Network Attacks
• Wireless Attacks
• Social Engineering Attacks
18
Wireless Attacks
• Most of us now use wireless technologies.
• Wireless attacks normally carried out to
target information that is being shared
through the networks wirelessly.
19
Type Characteristics
Rogue Access
Points
• Connects to your organization’s network that your
organization did not intend to place.
• Evil twins, rogue access points that pretend to be part of an
organization’s legitimate wireless network
War driving
Who drove around searching for wireless networks while in a
car

Hey FBI surveillance band play house parties clubhouse I got one Hendersons you about to get hacked oh hey gang what am i doing doing a little war driving what is war driving war driving is actually when somebody drives around a neighborhood driver out somewhere and actually trying to look for unsecured wireless networks all right so an easy way to prevent this an easy way to protect yourself from 

 This is actually hiding your SSID so what is your SSID your SSID is the name your network so when you go inside of Starbucks Starbucks Wi-Fi is the SSID SSID stands for service set identifier that doesn't really matter right now but the name of the network you can actually disable the neighborhood network and people won't actually see it when they're looking around another thing you can do especially for wardriving is reduce the range if I'm driving down the 

 Middle of the street I shouldn't be able to actually pick up your wireless network all right so make sure that the range is reduced to only inside your home maybe to your front porch and maybe a back porch any further than that is making you more susceptible to attacks another thing is just make sure that your network name right your network name just make it something normal because even with wardriving if you have sophisticated 

 Enough software even if you had the SSID they can still pick it up but if you reduce the range then they won't be able to pick it up in the middle of the street right and then if they are on Europe in the middle of your grass and mow your lawn and maybe hey maybe I should go talk to this guy so make sure that you reduce the range and to protect yourself from wardriving this is Duane from IT master key com this is a quick class about wardriving 

 Pop quiz waters warm driving bam because just what somebody drives wrong your neighborhood looking for unsecured wireless networks what's the easiest way to prevent that reduce the range your actual router you can do all of this through the admin portion of your router so hopefully enjoyed this and I'll see you in class 

Packet sniffing
and wireless
networks
Any data that isn’t encrypted can be captured and analysed
with ease
Identifying Types of Cyber Attacks
• Client-side Attacks
• Web Attacks
• Network Attacks
• Wireless Attacks
• Social Engineering Attacks
21
Social Engineering Attacks
• The process by which intruders gain access
to facilities, network, and even employees
by exploiting the generally trusting nature of
people.
• May come from someone posing as a
vendor, bank officer, police officer, etc.
• Using a variety of media, including phone
calls and social media, these attackers trick
people into offering them access to
sensitive information.
• Easy to accomplish in most organizations.
22
Type Characteristics
Phishing
Ask someone for a piece of information that you are missing by
making it look as if it is a legitimate request.
- Spear pishing
- Whaling
- Vishing

Phishing is a method of trying to gather personal
information using deceptive e-mails and websites. Stay tuned for what you need to know about
this increasingly sophisticated form of cyberattack. The goal of phishing is to trick an email
recipient into believing that the message is something they want or need — a request
from their bank, for instance, or a note from someone in their company — and to click
a link or download an attachment. "Phish" is pronounced just like it's spelled,
which is to say like the word "fish" — the analogy is of an angler throwing a baited
hook out there (the phishing email) and hoping you bite.
What really distinguishes phishing is that attackers masquerade as a trusted entity of
some kind, often a real — or plausibly real — person, or a company the victim might
do business with. It might be your boss, your bank or a company whose software you use.
Perhaps one of the most consequential phishing 

 Attacks in history happened in 2016, when
Russian hackers managed to get Hillary Clinton's campaign chair John Podesta to offer up the
password to his personal Gmail account. How did they do it? The hackers sent an email
warning Mr. Podesta that someone had his password and that he should change it immediately.
Clicking on a link in the email took him to a fake log-in page.
This is a classic ploy and one all of us hope we would see for what it is.
But email scammers are constantly honing their craft, trying new pitches and pulling new
strings. One way to get familiar with their tactics
is to study the email messages that scammers send.
Here are a few real-world examples and how they work:
1. Your account has been hacked The person sending this threatening phishing
message found a group email that was publicly available on the company website. Using that
list to target the message was smart. Not 

 So smart was the content of the message, in
which the would-be attacker reveals a lack of understanding of how malware works.
2. Password reset Taking advantage of the fact that no one wants
to miss a paycheck, messages like this one aim to trick the user into revealing important
data — often a username and password that the attacker can use to breach a system or
account. 3. Payment request
This email has enough information specific to the target company to give even the most
phishing-savvy recipients pause. The key to not getting caught in this trap is to know
your company's processes and be able to spot anomalies.
4. Charity donation Here the scammer is counting on the greed
and gullibility of the recipient. This theme of giving something away for free is a common
one and preys on human nature. The key thing to remember is if it sounds too good to be
true, it probably is. 

 Thanks for watching and stay safe out there! 

Tailgating or
“piggybacking”
A person impersonates a delivery driver and waits outside a
building

Cho tôi xem hai truyền phim sex Omen vs elfs wish that music comin from to me and nothing We get well niger special english with the food for the five Soul and she did you focus on the gardens of Turning and returning kem person And Again access to wishlist 

 Aborted or canceled live at Price Center for a person Who have all the voice Texas trong game king of the banker which ends Tonight I a person with love is near your pet Show and Tell Me That support and equity below to be treated with Online Super five senses of stay and the concert event was patient Again access your Network and Vietnamese for some advantages of aesthetic and Kibum etisalat in Golden Time and 

 Little Dragon people of and for you have Mercy of us on sweetness and forestry became FED up with reckoning temples palaces mô for the person per about their music And Dance With National Network and fun and Write success is certain foods for workstations and Find the way that ass for more information about Smoking and then it was seen What is the mortar or video district of business social and live if you might want to say this right đ A 

 Perfect Money is what are you doing my heart you're my office in this game you know is not elsewhere in tôi mãi đường vani justified Wow phân li fay Minion anh ạ 

Impersonation
Pretend to be someone you are not

[Music] you know getting dressed up in costumes and wearing masquerade outfits is kind of fun and it's interesting for you know Halloween maybe Mardi Gras but when it comes to a professional environment or your business people impersonating or doing hoaxes presenting themselves as someone that they're not actually isn't funny at all in a malicious cracker if they're going to do impersonation or 

 Masquerading which is really part of social engineering it's going to involve some preparation and some prior reconnaissance and information gathering before they attempt the exploit and impersonation is often a key factor masquerading is first attempted remotely through IP spoofing and then possibly over the phone maybe using email SMS texting instant messaging and then if none of those things get information that they need they'll do it in person 

 If the payoff from getting your data and your information is worth it the attacker can then obtain records about an organization your marketing plans your corporate secrets your formulas information about your employees your customers PII and other critical data if a cracker is gonna do social engineering and they're gonna pose as some other person what are some of the options they have well they can masquerade as a janitor or a cleaning service a pest 

 Control company they can be a fire inspector or a building inspector they may it poses a temporary or contract worker they may even position themselves as a security professional coming in doing a penetration test or an audit they may masquerade as a newly hired employee or a relative of somebody in management as a matter of fact use your imagination and think if you were a cracker what type of hoax or masquerade would you 

 Take on to trick somebody into getting inside to get access to a system employees should be well trained through security awareness programs to always be on the lookout for impersonators always politely ask for identification or authorization like a guest badge or a card if they notice somebody that seems like they just don't belong their policy may stay that employees don't confront suspects but instead escalate suspicious people to a supervisor a security guard 

 Or the security team a hoax is very similar and that the attacker tries to mislead people by presenting a false scenario hoaxes can come in person or through other means of communication like texting and email a hoax will often be attempted on holidays or other special days during major events like the US Super Bowl or the World Cup or the Olympics for example chain email messages are intended to trick mislead or scare recipients into forwarding the 

 Messages to many more recipients in this video we talked about the impersonation and hoaxing aspect of social engineering 

Vishing: (63) Watch this hacker break into a company - YouTube
Type Characteristics
Dumpster
Diving
Looking for treasure in someone else’s trash

Oh hey did you know that a hundred percent of dumpster crime takes place in a dumpster I didn't know that one either people will do this kind of stuff and then root around in your trash oh look tax form now I know your social don't do that kind of stuff make sure you're shredding your trash like this you want confetti cut to stuff that they can't assemble don't breathe that or you can burn your trash you may not have a 

 Burn bag like this but you can still burn your trash just take it out burn it don't throw stuff away like credit card forms either so offers that the credit card company sends you those are especially high on the list for identity thefts you never know what you can find in a dumpster there's a perfectly good Apple [Applause] 

Shoulder
Surfing
Watching someone “over their shoulder” when they enter
their sensitive data

Susan has been working with her current employer for a long time she has just recently promoted as a senior accountant in the finance department she has elevated access to a lot of sensitive financial information jon is the new employee and comes to susan's desk to discuss some technical details he watches over susan while she is 

 Entering her credentials susan doesn't know that john is an insider and trying to get elevated access to companies financial systems he now knows susan's password using susan's account john is able to authorize some fraudulent transactions susan realizes this but it is already too late the money has been transferred out shoulder surfing is a type of attack that criminals use to get elevated access to others accounts with watching 

 Over the shoulder while working on your computer be aware of people around you and protect yourself and your company 

PART 1b: Some
Examples
Malicious emails with password-protected
archives
• To make potential victims open the archives: fake
notifications about orders from large stores, various bills,
money transfers, resumes, or the promise of lots of money.
• The attached archives usually contained office documents
with macros or JavaScript scripts. When launched, the files
downloaded other malicious programs on the user’s
computer.
26
Malicious emails with password-protected archives
(cont.)
• The archive in the message contains
the Richard-CV.doc file with macros
that downloads representatives of the
spyware family.
• These malicious programs collect
confidential information about the user
and send it to the remote server.
27
Advance-fee scam
• Required to pay a fee
before receiving promised
stocks, services, money,
or products, which
ultimately are never given
28
How to Deal with
Social Engineering
Attacks?
29
How to Deal with Social Engineering
Attacks?
• DO NOT open emails in the spam folder or emails
whose recipients you do not know.
• DO NOT open attachments in emails of unknown
origin.
• Humans need to be trained – they are the weakest
link.
• Bi-annual training geared towards each user group (endusers, IT staff, managers, etc.) so that everyone is aware
of the latest attacks.
30
PART 2: Malicious
Software
Malware • What is malware (Malicious
Software)? • Software that enters a computer system
without the user’s knowledge or
consent and then performs an
unwanted and usually harmful action.
• Types of malware: • Viruses • Worms • Trojan horses • Spyware • Rootkits • Spam • Ransomware
32
Types of Malware
Malware Type Characteristics
Spyware Collects information about the user without the user’s
consent
Adware pushes you with endless ads and pop-up windows
Ransomware restricts access to your computer system and demands
that a ransom is paid
Rootkits Gain administrator-level control over a computer system
Anatomy of a Ransomware Attack: (24) Ransomware - Anatomy of an Attack – YouTube
Adware Spyware Ransomware

[Music] foreign imagine this you go online with your nice well-behaved browser only to see it fly into a virtual tantrum as an onslaught of advertisements either pops up slides in from the side or otherwise inserts itself to interrupt and even redirect your intended activity and no matter how much you click to 

 Close those windows they keep buzzing you like flies at a picnic that bothersome phenomenon is a result for madwear short for advertising supported software adware is unwanted software designed to throw advertisements up on your screen most often within a web browser typically it uses an underhanded method to either disguise itself as legitimate or piggyback on another program to trick 

 You into installing it on your pc tablet or mobile device adware generates revenue for its developer by automatically displaying online advertisements in the user interface of the software or on a screen that pops up in the user's face during the installation process and that's when you start seeing many types of ads pop up on your screen inviting you to click 

 Also you might experience new tabs opening a change in your home page findings from a search engine you never heard of mind you it does happen that legitimate software applications do use online advertising with ads that are typically bundled within the program and that display in ways the program developer specified adware is a different thing altogether you might download it without 

 Understanding its intent or it might land on your pc by means of legitimate software within which it's secretly buried whatever the path it all boils down to some program on your computer showing you advertisements that do not come from the websites you are visiting although some adware are not harmful it is still annoying to see those ads keep on popping spyware is unwanted software that 

 Infiltrates your computing device stealing your internet usage data and sensitive information spyware gathers your personal information and relays it to advertisers data firms or external users spyware is used for many purposes usually it aims to track and sell your internet usage data capture your credit card or bank account information or steal your personal identity 

 Spyware monitors your internet activity tracking your login and password information and spying on your sensitive information some types of spyware can install additional software and change the settings on your device so it's important to use secure passwords and keep your devices updated if you've ever been a victim of identity theft or credit card fraud you're not alone cyber crime statistics 

 Tell the story a total of 978 million people in 20 countries were affected by cyber crime in 2017. victims of cyber crime globally lost 172 billion dollars spyware contributed to those numbers spyware is one of the most common threats on the internet it can easily infect your device and it can be hard to identify spyware is a threat to businesses and 

 Individual users since it can steal sensitive information and harm your network ransom malware or ransomware is a type of malware that prevents users from accessing their system or personal files and demands ransom payment in order to regain access there are several different ways that ransomware can infect your computer one of the most common methods today is through malicious spam 

 Or mouse pam which is unsolicited email that is used to deliver malware the email might include booby-trapped attachments such as pdfs or word documents it might also contain links to malicious websites there are three main types of ransomware scareware scareware as it turns out is not that scary it includes rogue security software and tech support scams you might receive a pop-up message 

 Claiming that malware was discovered and the only way to get rid of it is to pay up if you do nothing you'll likely continue to be bombarded with pop-ups but your files are essentially safe a legitimate cybersecurity software program would not solicit customers in this way if you don't already have this company's software on your computer then they would not be monitoring you 

 For ransomware infection if you do have security software you wouldn't need to pay to have the infection removed you've already paid for the software to do that very job screen lockers when lock screen ransomware gets on your computer it means you're frozen out of your pc entirely upon starting up your computer a full-size window will appear often accompanied by an official looking fbi 

 Or u.s department of justice seal saying illegal activity has been detected on your computer and you must pay a fine however the fbi would not freeze you out of your computer or demand payment for illegal activity if they suspected you of piracy they would go through the appropriate legal channels encrypting ransomware this is the truly nasty stuff these are the guys who snatch up your 

 Files and encrypt them demanding payment in order to decrypt and redeliver the reason why this type of ransomware is so dangerous is because once cyber criminals get a hold of your files no security software or system restore can return them to you unless you pay the ransom they're gone and even if you do pay up there's no guarantee the cyber criminals will give you those files back 

rootkit

One type of malware is nastier than almost
any other. Let’s talk about rootkits. What is a rootkit? It’s a collection of malicious software
that’s hidden deep within the operating system of a computer. A rootkit might even hide at the level of
the kernel, which controls the entire system. It’s very hard to detect, and it may be
even harder to remove. A rootkit allows a hacker to have control
over your computer or software without you realizing it. A rootkit attack can compromise your system
in many different ways. A hacker can use it to: 

 Infect you with malware. Initiate a denial-of-service attack. Disable anti-malware software. Or even take over your device
A rootkit can end up on your system like any other malware. You can accidentally download it from an infected
website or a compromised USB drive. Or a hacker can use social engineering to
steal your access data and inject a rootkit into your computer. If you get infected, the removal can be complicated. Some rootkits can be detected and removed
by antivirus. In other cases, you may need to reinstall
your operating system. The best defense is prevention. 

 Don’t download software from unreliable
websites. Use only official websites or trusted online
stores. Don’t download shady attachments or click
on suspicious links.Do not use USB devices you don’t trust. Be wary of scammers and phishing messages. Never give personal info unless you’re sure
it’s safe. And keep your software updated. Stay safe! For all things online security, please subscribe
to our YouTube channel. 

Types of Malware
Code Type Characteristics
Virus
Attaches itself to program and propagates copies of itself
to other programs
Trojan horse Contains unexpected, additional functionality
Rabbit Replicates itself without limit to exhaust resources
Worm Propagates copies of itself through a network


Ways to Deliver Malicious Software
• Malware can be delivered in several
ways:
• Via software, messaging, and media
• Privilege escalation (exploiting the issues
of the computer's configuration to gain
elevated access to resources)
• Backdoors
• Logic bombs
• Botnets and zombies
39
Botnets and zombies • A zombie computer is similar to traditional Trojan
horse. • The difference between the two is that, instead of
only installing a keylogger and stealing your personal
data, zombies will work with other zombies, forming
what is called a “botnet” (or “zombie army”).
• The term “botnet” comes from combining the words
“robot” and “network”. For a much more fun
explanation, what this video: (24) What is a botnet? When IoT
devices attack
- YouTube
• Botnets are entire networks of computers controlled
and instructed to do a bunch of things, such as: • attack other computers, • send spam or phishing emails, • deliver ransomware, • spyware, or many other similar malicious acts.
40
Botnets and zombies
41
• Cybercriminals will lure you into a drive-by
download.
• Exploit vulnerabilities in websites and
software, such as your browser’s
outdated plugins.
• Trick you into clicking on links or opening
malicious email attachments.
• Once executed, the malicious code will
make contact with the Command & Control
server, the one that operates the botnet.
• Computer will remain idle, periodically
checking for instructions from the control
computer.
• Command & Control server will issue a
command and the botnet will launch an
attack.

[Music] malicious software or malware can harm your computer in a variety of ways and sometimes the effects are not known until it's too late what's worse your computer can become one of many infected with malware creating a botnet short for robot and network cyber criminals use special malware usually a Trojan horse to breach the security of several users computers 

 These take control of each computer and organize all of the infected machines into a network of bots which are unwitting tools that the cyber criminal can remotely manage the infected system may act completely normal with no warning signs a bot can be a PC Mac or even a smartphone oftentimes the cyber criminal will seek to infect and control thousands tens of thousands or even millions of computers so that they can act as the master of a large zombie 

 Network or bot network these botnets are capable of delivering many different types of cyber crimes such as DDoS attacks spreading malware online fraud and wide scale spam or phishing campaigns in some cases cyber criminals will establish a large network of sobbing machines and then sell access to the zombie network to other criminals either on a rental basis or as an outright sale spammers may rent or buy a network in order to operate a 

 Large-scale spam campaign the consequences of being part of a botnet can be very serious some risks include high internet bills slow and unstable computer performance potential legal implications if your computer is compromised and stolen personal data which can be used in blackmail or identity theft becoming a victim of a botnet attack is all too easy a common source of infection is downloading files from an unknown site or from 

 File-sharing even social media sites and apps can contain malware that can turn your computer into a bot high risk computers are ones with outdated internet security software or even none at all you can limit the risks by always verifying the site or app that you plan on downloading from and ensuring it is from a legitimate source however the best form of protection is installing effective anti-malware software against 

 Trojans and other threats always ensure that your computer is equipped with the latest internet security software in order to prevent becoming part of a botnet [Music] 

PART 3: Protection
Against Malware
Protecting Against Malware
Antivirus Program
• Cyber criminals develop and
deploy new threats on a daily
basis.
• The key to an effective
antivirus solution is to keep the
signatures updated. A
signature is like a fingerprint. It
identifies the characteristics of
a piece of malicious code.
Up-to-Date Software
• Today’s application-level
vulnerabilities pose the
greatest risk.
• While operating system
vendors are becoming more
and more responsive to
patching, most application
vendors are not.
User Awareness
• The weakest link in any system
is usually the user
• Inexperienced User can be
manipulated if the attackers
where their soft spots are
43
Protect Yourself Against Identity Theft
• Do not provide your personal information to anyone if it is not
necessary.
• Destroy documents that have personal information on them.
• Check your credit frequently.
44
Protect Yourself Against Cyber Stalking
• If you use public chat rooms, discussion
boards, and so forth, do not use your real
name.
• Set up a separate email account with an
anonymous service, such as Live, Gmail.
• Then use that account and a fake name online.
This makes it hard for an online stalker to trace
back to you personally.
• If you are the victim of online harassment,
keep all the e-mails in both digital and
printed format.
• Use some of the investigative techniques you
explore later in this book to try to identify the
perpetrator.
• If you are successful, then you can take the emails and the information on the perpetrator to
law enforcement officials.
45
Your task for Thursday
Watch some videos: Techniques used by
hackers
Anatomy of an IoT Attack: (24) Cisco - Anatomy of an IoT Attack
- YouTube
Anatomy of a Cyber Attack: (24) Anatomy of a Cyber Attack –
YouTube
47
