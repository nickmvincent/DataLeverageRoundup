# Data Leverage Roundup

## What's Data Leverage?
Powerful data-dependent technologies rely on the public (including you and everyone you know) to fuel them with data. This means collective action that involves withholding, deleting, manipulating, and/or transfering data can help the public exert [data leverage](https://arxiv.org/abs/2012.09995) against technology companies, potentially pushing for meaningful change (which could range from taking privacy more seriously to [making changes to the data economy](https://www.datadividends.org/)).

For more info, see the [paper](https://arxiv.org/abs/2012.09995) or this [recent](https://www.technologyreview.com/2021/03/05/1020376/resist-big-tech-surveillance-data/) [coverage](https://fortune.com/2021/02/23/your-data-is-a-weapon-that-can-help-change-corporate-behavior/) of data leverage.

The goal of this repository/document is to provide a roundup of tools, news, social movements, civic initiatives, and resources related to data leverage.

This is by no means complete and we welcome contributions! See "Contributing" at the bottom of this document.

## How is this different from initiatives related to data protection, privacy, obfuscation, surveillance, etc.?
As we hope to show you below, data leverage draws *heavily* on tools, movements, initiatives, and research related to all the above topics. Data leverage focuses on gaining leverage to win concessions for the public from large powerful organizations. In other words, many (if not most) efforts related to data protection, privacy, obfuscation, and surveillance can *also* help to advance data leverage. We've also tried to highlight some active research in these areas below.

In short: this document is not just about "tools developed for data leverage"; it is about "tools (developed for many purposes) that support data leverage".

## Is Data Leverage About Bringing Down All Data-dependent Technologies?
Not necessarily! While some data levers (specifically, data strikes and data poisoning) involve lowering the performance of a data-dependent technology, data leverage can also involve boosting up a data-dependent technology and contributing to knowledge artifacts (conscious data contribution).

There is active research on identifying the harms of different technologies. See, for instance, work in the [ACM FAccT Conference](https://facctconference.org/2021/). This research can help us to navigate the ethics of data leverage: which technologies *should* be harmed and which *should* be helped? These are tough, inherently contextual and political questions that will require deep societal conversations involving many perspectives.

That said, there is some overlap between data leverage and active movements aimed at mitigating the impacts of harmful technologies (with harm, of course, being contexually defined). See below for more.

# Tools that Support Data Leverage

## Data Strikes
### Web browsing
- [PrivacyBadger](https://privacybadger.org/) - "stops advertisers and other third-party trackers from secretly tracking where you go and what pages you look at on the web"
  - This tool has explicit concessions in mind: companies can avoid being blocked if they comply with Do Not Track headers.
- [Firefox Containers](https://support.mozilla.org/en-US/kb/containers) - "lets you separate your work, shopping, or personal browsing without having to clear your history, log in and out, or use multiple browsers"
  - anything you do in one container will be kept separate from other containers
  - Can be set to automatically open specific websites in their own container, to make it harder for companies to track you across the web
- [Cover Your Tracks](https://coveryourtracks.eff.org/) - "Test your browser to see how well you are protected from tracking and fingerprinting"
  - Provides suggestions for increasing your tracking protection
  - Provides a primer on ["browser fingerprinting"](https://coveryourtracks.eff.org/about#browser-fingerprinting)
- [Ghostery](https://www.ghostery.com/) - "Ghostery demystifies online privacy by exposing the forces that lurk behind your screen and enabling you to block them."
  - Free suite of tracking blockers, with paid upgrades such as customization, VPN, etc.
- [DuckDuckGo's Mobile App](https://duckduckgo.com/app) - "Seamlessly take control of your personal information, no matter where the Internet takes you."
- [Tor](https://www.torproject.org/) - "Defend yourself against tracking and surveillance. Circumvent censorship."

### Advertising
- There are many choices for ad blockers. Some popular ones include:
  - [uBlockOrigin](https://ublockorigin.com/)
  - [Adblock Plus](https://adblockplus.org/)
  - [Adblock](https://getadblock.com/)

### Deletion Requests
- [Mine](https://saymine.com/) - "Discover where your personal data is and manage your digital footprint."
  - a tool for finding which companies have data about you and submitting deletion requests
  - website includes a [table](https://saymine.com/privacy-in-action) with statistics about how quickly and frequently companies complete deletion requests

## Data Poisoning
### Ad Targeting
- [AdNauseam](https://adnauseam.io/) - "clicking ads so you don't have to."
  - Browser extension that "clicks" every ad your browser sees, as a form of *obfuscation*.
### Search
- [TrackMeNot](http://trackmenot.io/) - "With TrackMeNot, actual web searches, lost in a cloud of false leads, are essentially hidden in plain view."
  - See this [paper](http://trackmenot.io/resources/trackmenot2009.pdf) about the project.
### Images
- [LowKey](https://lowkey.umiacs.umd.edu/) - "Prevent your images from
being used to track you."
  - Upload your images to get a perturbed copy.
- [adversarial.io](https://adversarial.io/about/) - "easy-to-use webapp for altering image material, in order to make it machine-unreadable. "
- [Fawkes](https://sandlab.cs.uchicago.edu/fawkes/) - "Image 'Cloaking' for Personal Privacy"

### Phone Contacts Data
- [fake_contacts](https://github.com/BillDietrich/fake_contacts) - "feeds fake data to any apps or companies who are copying our private data to use or sell it"

### NLP
- [Customizing Triggers with Concealed Data Poisoning](https://www.ericswallace.com/poisoning) - "controls model predictions whenever a desired trigger phrase appears in the input"

## Conscious Data Contribution
### build personal data infrastructure now
- [Building data liberation infrastructure](https://beepb00p.xyz/exports.html) - "How to export, access and own your personal data with minimal effort"
  - highly comprehensive post covering design principles and practical technqiues for managing many sources and types of data

- [Promnesia](https://beepb00p.xyz/promnesia.html) - "Promnesia is a browser extension (Chrome/Firefox/Firefox mobile) that serves as a web surfing copilot by enhancing your browsing history, improving your web exploration experience, and integrating with your knowledge base."

- [Solid](https://solidproject.org/) - "Your data, your choice.
Advancing Web standards to empower people."

### Downloading Data from Tech Companies
- [How to Download Your Google Data](https://support.google.com/accounts/answer/3024190?hl=en)
  - Official help docs from Google
- [How to Download Your Twitter Achive](https://help.twitter.com/en/managing-your-account/how-to-download-your-twitter-archive)
  - Official help docs from Twitter

- [The Data Transfer Project](https://datatransferproject.dev/) - "a collaboration of organizations committed to building a common framework with open-source code that can connect any two online service providers, enabling a seamless, direct, user initiated portability of data between the two platforms."
  - "DTP is still in very active development"
  - Currently only usable with some coding experience. See [bottom of this page](https://datatransferproject.dev/documentation).


# Motivating Data Leverage
Many tools have focused on showing how our data is used and how pervasive data collection systems are. These may be very useful for convincing people to join data leverage movements.

- [Exposing.AI](https://exposing.ai/about/) - "Check if your Flickr photos were used to build face recognition"
  - Search to find if your images have been used in facial recognition datasets
  - Connection with data strikes: could be useful in raising public awareness about how image data is being used
- [Big Tech Detective](https://bigtechdetective.net/) - "What would the web look like without big tech companies? "
- [NYT - "The Secretive Company That Might End Privacy as We Know It"](https://www.nytimes.com/2020/01/18/technology/clearview-privacy-facial-recognition.html)
- [The sad state of personal data and infrastructure](https://beepb00p.xyz/sad-infra.html) 


# Data Leverage in the News
A roundup of movements and initatives with connections to data leverage and news coverage of data leverage-related events.

- [Wired - "How To Stop Instagram From Tracking Everything You Do"](https://www.wired.com/story/how-to-stop-instagram-from-tracking-everything-you-do/) 
- [Fast Company - "Giving Facebook less data is a good idea. Even better: Just use it less"](https://www.fastcompany.com/90516050/giving-facebook-less-data-is-a-good-idea-even-better-just-use-it-less)
- [WSJ - "Google to Stop Selling Ads Based on Your Specific Web Browsing "](https://www.wsj.com/articles/google-to-stop-selling-ads-based-on-your-specific-web-browsing-11614780021)
  - [See also the EFF's related commentary](https://www.eff.org/deeplinks/2021/03/googles-floc-terrible-idea)


# Data Related Social Movements and Civic Initiatives
- [Data Dividend Project](https://www.datadividendproject.com/)
- [Consumer Reports tests "authorized agent opt-outs"](https://advocacy.consumerreports.org/press_release/consumer-reports-study-finds-authorized-agents-can-empower-people-to-exercise-their-digital-privacy-rights-in-california/)
  - [More on the Digital Lab](https://digital-lab.consumerreports.org/)

- [Repair Cafés for Digital Rights](https://lsts.research.vub.be/repair-caf%C3%A9s-for-digital-rights) - "innovatively explores ways to make sure that the digital rights that individuals have are effectively strong"

- [OpenSCHUFA](https://www.startnext.com/en/openschufa) - "Are the scores created by SCHUFA, Germany's largest credit score company, unjust? Donate money or your SCHUFA data to help us find out. "
  - highly successful "data donation" project in Germany

## Related Movements
There are many ongoing social movements with goals that are very aligned with data leverage (e.g. addressing negative impacts of computing, reducing power imbalance between the public and tech companies).
### Surveillance
- [Surveillance Technology Oversight Project](https://www.stopspying.org/exposing-ai) - non-profit "working to abolish local governments’ systems of mass surveillance."
- [Stop LAPD Spying Coalition](https://stoplapdspying.org/) - "Our vision is the dismantling of government-sanctioned spying and intelligence gathering, in all its multiple forms."
### Harms of Facial Recognition
- [Ban Facial Recognition](https://www.banfacialrecognition.com/)
- [Nature News, 2020 - "Resisting the rise of facial recognition"](https://www.nature.com/articles/d41586-020-03188-2) - an overview of many efforts to mitigate negative impacts of facial recognition
- [CACM, 2021 - "Can the Biases in Facial Recognition Be Fixed; Also, Should They?"](https://cacm.acm.org/magazines/2021/3/250698-can-the-biases-in-facial-recognition-be-fixed-also-should-they/fulltext)
### Harms of Social Media
  - [Center for Humane Technology](https://www.humanetech.com/)   


# Important Areas of Active Research
This is not meant to be comprehensive, but rather provide some helpful starting points anyone interested in the research in this space.


## Contesting Optimization Systems
- [Protective Optimization Technologies](https://arxiv.org/abs/1806.02711) - "POTs provide means for affected parties to address the negative impacts of systems in the environment, expanding avenues for political contestation."

##  Data Rights in Practice
- ["Shattering One-Way Mirrors. Data Subject Access Rights in Practice"](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3106632)
- Ongoing or complete attempts to measure if deletion requests are fulfilled
  - [from Mine](https://saymine.com/privacy-in-action)
- [Researching with Data Rights](https://techreg.org/index.php/techreg/article/view/61) - "This article positions data rights as a useful tool in researchers’ toolbox to obtain access to enclosed datasets"
  - Can gain "informational leverage" over firms

## Reproducible Research on Data Poisoning
- [Just How Toxic is Data Poisoning? A Unified Benchmark for Backdoor and Data Poisoning Attacks](https://arxiv.org/abs/2006.12557) - "we find that existing poisoning methods have been tested in contrived scenarios, and many fail in more realistic settings. In order to promote fair comparison in future work, we develop standardized benchmarks for data poisoning and backdoor attacks. "

## Data Portability
- [EFF on Data Portability](https://www.eff.org/deeplinks/2018/09/what-we-mean-when-we-say-data-portability)

## Data Poisoning and Crowdsourcing systems 
- [Data Poisoning Attacks and Defenses to Crowdsourcing Systems](https://arxiv.org/abs/2102.09171)
  - Data poisoning is not unique to "machine learning".


# Choosing Alternative Products
- [TechCrunch, 2021: These 6 browser extensions will protect your privacy online](https://techcrunch.com/2021/01/10/these-6-browser-extensions-will-immediately-improve-your-privacy-online/)
- [alternativeto](https://alternativeto.net/) - A database for searching "I want an alternative to..."
- [nomoregoogle](https://nomoregoogle.com/) - A guide to google alternatives.
- [r/privacy's guide to de-google](https://old.reddit.com/r/privacy/wiki/de-google) -the r/privacy subreddit's guide to google alternatives
- [NYT, 2020 - "Our Favorite Ad Blockers and Browser Extensions to Protect Privacy"](https://www.nytimes.com/wirecutter/reviews/our-favorite-ad-blockers-and-browser-extensions-to-protect-privacy/)

# Contributing
This is an incomplete list and we welcome contributions! Feel free to use email, Github issues, or pull requests to suggest additional tools, news, movements, and resources to include.

Some general goals for this page:

- Let links mostly speak for themselves. To start, we've include a brief quote from each link that tries to give a high-level summary.
- For each link, we also include a very brief summary and highlight unique strengths
  - Was the tool designed with explicit concessions in mind? In other words, are users of the tool already actively working to *exert leverage*?
  - Does the tool work well for collective action?
  - etc.
- Emphasize tools that are particularly easy to use. We're eager for people to share their experiences using these tools.

In addition to content contributions, we're also in interested in feedback about what kinds of structured information would be useful. In particular, we hope to eventually create structured data (for instance, a CSV file) that describes data leverage tools. What attributes (i.e. columns) would you like to see? 
