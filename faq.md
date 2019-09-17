# FAQ

## What is the idea in one sentence?
COI allows everyone to chat on basis of the current email infrastructure, the experience gets better with a COI compatible client and even better with a COI compliant server.

## What about end to end encryption?
COI currently uses [Autocrypt](https://autocrypt.org) for automatic and effortless end to end encryption of messages.
Additionally Open-Xchange has launched and supports the  [Trusted Email Services](https://TESMail.org) to describe a secure email setup. 
For the future we are considering further encryption schemes like the emerging Message Layer Security standard.

## Isn't COI just adding another silo?
COI is an extension to the email protocols, COI does not "add another one". 
COI is designed with full backwards compatibility in mind, so that anyone with an email address can participate in the communication. 
The experience is only improved by using a COI compatible client and potentially selecting COI supporting 
service provider / email server software. Email is a federated, established and world's largest messaging environment
- there are 7 billion active email accounts. You can also host your own email service - even when you are not a technician, 
you can use solutions like [Helm](https://thehelm.com/).

## IMAP - seriously? Why not JMAP?
IMAP and SMTP are the most ubiquitous message technologies, so it makes sense to base COI on that. 
JMAP provides alternate means to talk to the email backend, that is very (mobile) client friendly and brings in contacts and 
calendar. Very cool! We hope JMAP will pull in the enhancements COI provides as well. 

## Where can I download clients? How can I test this?
OX - the initiator of the COI initiative - is working on its own COI messenger. This one is MPL licensed and available at 
[github.com/open-xchange/ox-coi](https://github.com/open-xchange/ox-coi).
We are cooperating with Delta.Chat for it to also use COI to provide more features, we are contributing to the Rust-Kernel of it. 
We are cooperating with other client developers such as Thunderbird or Spike to get more clients use COI, and invite all ISV's to join in. There are soooo many variants of Chat / Slack / Social Clients out there. Let's put them on COI and make them interoperable and give users control over where all that data sits!

## Where can I find a COI compliant server?
Dovecot is working on becoming COI compliant and we hope to share developer previews soon. At the same time we are working on the server specification drafts and cooperate with bodies such as the IETF.

## What about Matrix.org? Did you forget about Matrix interoperability with email?
COI is complementary to Matrix. And XMPP for that matter. We do not try to replace any of them. COI has the advantage of global distribution and ubiquity. We believe this network effect is necessary to replace the silos.

In theory Matrix provides the option to communicate with email recipients via an email bridge. However, COI is built on email and does not need a gateway or any translation, COI messages are email messages, thus avoiding any gateways, transcoding etc., which usually means asking for trouble.

## Why would anyone switch to COI?
You don't need to switch. From a COI client you can communicate with any active email account (btw, 7 billion worldwide!). COI clients will enhance the email experience in various ways, we expect the following reasons to be the main drivers for adoption:

* Opinion leaders that realize that COI is the best way to overcome the dominance of WhatsApp and Co.
* An easier, more modern email experience. By providing a chat messaging experience, COI compatible clients can provide the fresh 21st century email experience that many look for.
* Client specific enhancements - COI is an open ecosystem based on free standards, so anyone can participate and innovate - without fearing to be locked out.
* Taking back control of your data: COI sits in your mailbox, you chose where your mailbox is hosted and how it's protected, according to your security profile
* It's ubiquitous, most people don't care about many of the things above, but there will be a plethora of cool clients that people will love to use, and even if they don't get a client, everybody (up a certain age) has an email address.

## Where can I learn more?
* Visit [coi-dev.org](https://coi-dev.org).
* Join the COI developer mailing list by sending a mail to [dev-join@coi-dev.org](mailto://dev-join@coi-dev.org?subject=subscribe&body=please%20subscribe%20me%20to%20the%20COI%20mailing%20list.).
* Watch our FOSDEM talk:
  * https://video.fosdem.org/2019/H.1309/chat_over_imap.mp4
  * https://video.fosdem.org/2019/H.1309/chat_over_imap.webm
