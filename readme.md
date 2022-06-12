# Privacy

<!-- ## How You Are Tracked

## You Have Patterns & So Do The Things You Use

[Browser Fingerprints](http://blog.add0n.com/2016/03/23/html5-apis-fingerprint-users-how-to-prevent.html) -->

## Electronic Payments

I recommend a combination of all of these options.

### Prepaid Visa/Mastercard giftcards

Visa and Mastercard offer giftcards that are loadable up to $500 and cost around $5.
They are available in many grocery, gas stations and other stores that sell
selections of giftcards.

What this service can _possibly_ know about you:
- Everything in [Common Identifiers and Solutions](#common-identifiers-and-solutions).

Pros:
- Widely available.
- Accepted at most merchants.

Cons:
- Some merchants don't accept them.
- Merchants can know that you're using a giftcard.

Things to keep in mind:
- Do not get the reloadable type.
- Read the back to make sure there is no expiration or maintanance fees.
- Some vendors won't accept them.
- Pay with cash and the card is tied to your identity at all (other than security cameras).

You have to register your card online with a desired billing name, address and
phone number when you need to make purchases that verify the billing data matches
what's registered with the cardholder.

You also have to use a website to view your balance and transactions.

### Bitcoin

Bitcoin transactions are public and can be traced to you with much effort.
However, when certain steps are followed, it is much more private than using a standard credit/debit card.

Here is a nice overview about bitcoin privacy: https://bitcoin.org/en/protect-your-privacy

What this service can _possibly_ know about you:
- Everything in [Common Identifiers and Solutions](#common-identifiers-and-solutions).
- Your wallet can be tied to your true ID if you convert money through common echanges.

### Monero

[Monero](https://www.getmonero.org/) is a cryptocurrency designed for privacy.
It is not as widely accepted by vendors as bitcoin though.

What this service can _possibly_ know about you:
- Everything in [Common Identifiers and Solutions](#common-identifiers-and-solutions).
- Your wallet can be tied to your true ID if you convert money through common echanges.

### Virtual Visa/Mastercard

What this service can _possibly_ know about you:
- Everything in [Common Identifiers and Solutions](#common-identifiers-and-solutions).
- Your true ID, because they are linked into your bank account.

Pros:
- Most services allow you to use any name, billing address for each card
- very convenient
- create as many virtual cards as you want
- can limit the funds available on a specific card
- can limit a card to a specific merchant
- no fee, because the provider makes money from the transaction fees like regular
  card providers

Cons:
- They know your true ID. Cards are funded from your bank so that means the
  virtual card provider knows your true identity.

### Privacy.com

https://privacy.com/virtual-card

Pros:
- Free
- Use any name, billing address for each card

Cons:
- They know your true ID.

## Email

What this service can _possibly_ know about you:
- Everything in [Common Identifiers and Solutions](#common-identifiers-and-solutions).
- Contents of unencrypted emails.
- Email addresses of senders and recipients.

It is best to have at least two accounts:
- At least one account that is used with [services that KNOW your ID](#common-services-that-know-your-id).
- At least one account for services that don't know your ID.

Create non-identifying domain names to use for the email accounts. That will allow
you to use wildcard email addresses. For example, you can have a domain of
`example.com` and any email sent to `@example.com` will go into your inbox. This
has the benifit of being able to instantly create a unique email address whenever
you want. Give service A an email of `serviceA@example.com`, for example. This
has these benifts:
- A service can't see if your email address matches any other provided by a
  data broker.
- You can tell if a service sells your email, or it was stolen in a breach,
  because you'll start getting other emails sent to that address.
- You can completely block all emails being received to that address if they
  start spamming you.
### Tutanota

[Homepage](https://tutanota.com/)

Pros:
- Privacy focus
- Low price
- End-to-end encryption

Cons:
- You have to use their custom app for email notifications on mobile devices.
  This is because of the end-to-end encryption. So it's OK.
- Only 5 email alias can be created. More cost money. Email alias are needed to
  respond email services using the unique email you gave them. The limit is only
  a minor inconvenience, becasue you can easily change them whenever you desire.

### Email Aliases

See https://www.privacyguides.org/email/#email-aliasing-services.

## Domain Registrar

What this service can _possibly_ know about you:
- Everything in [Common Identifiers and Solutions](#common-identifiers-and-solutions).
- Your email or other servers that you configure in your DNS record.
  **No possible solution.**

https://njal.la/domains/

## Encrypt Network Traffic

### Tor

Use [Tor](https://www.torproject.org/) when you want true anonimity.

### VPN

VPNs do **NOT** provide anonimity, but they do provide an important layer of privacy.

Please see also https://www.privacyguides.org/vpn/. Any of their recommendations
are good.

What this service can _possibly_ know about you:
- Everything in [Common Identifiers and Solutions](#common-identifiers-and-solutions).
- Your true IP address while using their data network.
  **No possible solution while using their data network.**  
- The domain names resolved using their default DNS.  
  **Solution[easy-expert]:** Use [DNScrypt](https://www.dnscrypt.org/).
- IP addresses that you communicate with.  
  **Solution[easy]:** Route all your network traffic through Tor.
- Content of network traffic.  
  **Solution[easy]:** Always use services that have encrypted traffic.
  **Solution[easy]:** Route all your network traffic through Tor.

#### ExpressVPN

[Homepage](https://www.expressvpn.com/)

Not fully evaluated, but they are recommended by many.


## Voice, SMS, MMS & Internet Access

### End-to-End Encrypted Voice/Video/Messaging

What this service can _possibly_ know about you:
- Everything in [Common Identifiers and Solutions](#common-identifiers-and-solutions).
- Maybe: Who you are contacting and who is contacting you.

See this guide: https://www.privacyguides.org/real-time-communication/

### No-Contract Mobile Service

How this service enhances your privacy:
- You can use a fake ID for the account and billing.
- You can change your account more frequently.

What this service can _possibly_ know about you:
- Everything in [Common Identifiers and Solutions](#common-identifiers-and-solutions).
- Your true IP address while using their data network.
  **No possible solution while using their data network.**  
- Your VPN or Tor exit node IP address used when visiting thier website. They
  already know your true IP while connecting through their data network.
  **No possible solution while using their data network.**  
- Fingerprint of your mobile device. This includes various unique numbers.  
  **Reduce Impact[easy]:** Purchase your phone using a private payment method.
  Don't use your phone with any mobile carriers that know your ID.
- Your physical location. Can't be avoided while your phone isn't in airplane mode.
  **Solution[easy]:** Use airplane mode when you don't need their service.
- The domain names resolved using their default DNS.  
  **Solution[easy-expert]:** Use a VPN or Tor.  
  **Solution[easy-expert]:** Use [DNScrypt](https://www.dnscrypt.org/).
- IP addresses that you communicate with.  
  **Solution[easy]:** Route all your network traffic through a VPN or Tor.
- Content of network traffic.  
  **Solution[easy]:** Always use services that have encrypted traffic.
  **Solution[easy]:** Route all your network traffic through a VPN or Tor.
- Phone numbers and then possibly IDs of incoming callers and of the numbers
  you call/message.  
  **No clear solution if you need to use voice/SMS/MMS.**  
  **Solution[easy]:** Use a secure and private alternative to traditional
  messages.
- Content of voice calls.  
  **No clear solution if you need to use voice/SMS/MMS.**  
  **Solution[easy]:** Use a secure and private alternative to traditional
  messages.
- Content of SMS/MMS messages.  
  **No clear solution if you need to use voice/SMS/MMS.**  
  **Solution[easy]:** Use a secure and private alternative to traditional
  messages.

#### RedPocket Mobile

-[Homepage](https://www.redpocket.com/)
-[Rates](https://www.redpocket.com/plans/annual)
-[Privacy Policy](https://www.redpocket.com/privacy)
-[Terms of Service](https://www.redpocket.com/terms_and_conditions)

Pros:
- Good coverage.
- Low rates.
- Can prepay by the year.
- Lax ID verification.

Cons:
- Not privacy focused.

### VOIP Voice and SMS/MMS

How this service enhances your privacy:
- Inexpensive method of having multiple phone numbers that can be given out.
- Prevents giving out your true mobile number that can be used to derive your location.
- Caller ID can be blocked or changed however you like.

What this service can _possibly_ know about you:
- Everything in [Common Identifiers and Solutions](#common-identifiers-and-solutions).
- E911 service address when registering a number.  
  A name and address are supposed to be registered for a number that is a possible
  line of 911 emergency response.  
  **Solution[easy]:** Opt out of E911 support.
- Phone numbers and then possibly IDs of incoming callers and of the numbers
  you call/message.  
  **No clear solution if you need to use voice/SMS/MMS.**  
  **Solution[easy]:** Use a secure and private alternative to traditional
  messages.
- Content of voice calls.  
  **No clear solution if you need to use voice/SMS/MMS.**  
  **Solution[easy]:** Use a secure and private alternative to traditional
  messages.
- Content of SMS/MMS messages.  
  **No clear solution if you need to use voice/SMS/MMS.**  
  **Solution[easy]:** Use a secure and private alternative to traditional
  messages.

I recommend having multiple accounts. One account and a phone number that is kept
for life and given out soley to services that already know your true identity and
need to call/text you, or you call/text them. These services would be government
and tax agencies. Government agencies can share a number. It is best to have
a dedicated number for your banks, brokers. Have a number that family and friends
can always use to reach you.

Have another account that holds phone numbers that you don't want to keep. Have
a number or two that can be given out to strangers without worry, since you can
delete the number at anytime.

Recommended Accounts and Unique Phone Numbers:
- Account 1 has numbers that are tied to your identity:
  - 1 number with SMS for governmental interaction.
  - At least 1 number with SMS for financial services.
  - At least 1 number for other services that know your identity.
  - A lifelong number for your close friends and family.
- Account 2 has numbers not tied to your identity:
  - At least one number with SMS/MMS that can be given out freely and deleted
    on a whim.
  - One or more numbers for services that don't know your identity, but where
    communication through voice/SMS is needed.

You need a VOIP client to use the VOIP number.
I recommend [Linphone](https://apps.apple.com/us/app/linphone/id360065638) for a free VOIP client app.
There may be better ones that cost money, but Linphone has worked for me. Here is a link that explains how to configure Linphone with voip.ms: https://wiki.voip.ms/article/Linphone_iOS

**Note:**  
There may be a VOIP app that makes this easier, but you must keep track of which
number to use when calling or sending SMS/MMS messages. Always use the number you
gave to the service when calling them.

#### voip.ms

- [Rates](https://voip.ms/en/rates/united-states)
- [Privacy Policy](https://voip.ms/privacy-policy)
- [Terms of Service](https://voip.ms/terms-of-service)

Pros:
- Supports encryption between their servers and your phone app.
- Supports SMS and MMS so that you can send/receive texts like a normal mobile number.

Cons:
- Not focused on privacy.
- They log identifying information.
- Voicemails are not stored in an ecrypted manner that prevents their staff from
  listening to them.
- Their TOS says they use a third party service to analyze the IP addresses when you
  signup and login to the online customer portal. It says the account may be flagged
  and access denied if the security rank is too high. That means it probably best not
  to use Tor with their service. Use a VPN instead.

Cost: ~$14/month (depends on minutes used and other optional features)
- Account for services that _know your ID_:
  - government #: $1/month
  - financial #: $1/month
  - general #: $1/month
  - personal #: $1-$5/month
- Account for services that _don't know your ID_:
  - throw away #: $1/month
  - general #: $1-5/month

### Public SMS phone number

There are multiple online websites that provide phone numbers that SMS messages
can be sent to. They are public though, so anyone can see the contents. This can
be useful if you need to get a message that isn't sensitive. Not often useful.

Pros:
- Free

Cons:
- Anyone can see the message content.
- You can't respond.


## Postal Services

### Mail Scanning and Forwarding

You can create an account with companies that receive your mail.

What this service can _possibly_ know about you:
- Everything in [Common Identifiers and Solutions](#common-identifiers-and-solutions).
- They will know your true ID, because they are legally required (in USA) to get
  it from you in order to act as a mail agent on your behalf.
- Any address you have mail forwarded to.
- Sender name and address of any mail they receive.
- Mail contents of any mail you have them scan for you.

Pros:
- Having your mail scanned for you is very convenient.
- Prevents services from knowing your true physical address.
- Less paper trash.
- Very helpful while traveling.

Cons:
- Monthly cost for basic services.
- Forwarding mail/packages can be costly because you add the forwarding postage.
- There are postal address verification services that can tell that the address
  is not your physical address.

#### Traveling Mailbox

[Homepage](https://travelingmailbox.com)

Pros:
- Many locations to choose from.
- Reasonable cost.
- Nice user interface.
- Mail can be open and scanned or forwarded.
- Mail can be shredded.
- They operate their own mail processors.

Cons:
- Not privacy focused.

## Tenets of Reducing Privacy Invasion

- Use companies and technologies that have a record of valuing privacy. They
  should be engineered so that there is limited information that can be gleaned.
- Even a company that truly hates privacy invasion and fights against it will
  succomb to legal/governmental pressure.
- Use layers of protection.
- Avoid online advertising.
- Give unique identifiers to services.
- Don't divulge more identifying info than required to fulfill service with you.
- Find services that require less identifiers.
- Find services that don't validate the uneeded identifiers.
- All network traffic should go through a VPN or Tor.
- Use fake identifiers.
- Alter digital fingerprints.


## Common Identifiers and Solutions

This is a list of common knowledge and identifiers that all services can glean
from your interactions with them:

- IP address when visiting thier site or using their service.  
  **Solution[easy]:** Route all your network traffic through a VPN or Tor.
- Fingerprint of your network traffic with them to determine what kind of operating
  system and version you're using.  
  **Solution[expert]:** Use software on your computer that can alter the network
  signature.  
  **Solution[expert]:** Use a virtual machine of different OSes.  
  **Solution[wishful]:** A VPN that can alter you network traffic signature.
- Fingerprint of your computer/phone.  
  **Solution[easy]:** Use a phone that sandboxes the service's app and limits
  the identifiers accessible to the app.  
  **Solution[easy]:** Use the service through a web browser if the service cn be
  completely used through a website.  
  **Solution[expert]:** Run the app from a virtual machine.  
- Fingerprint of your web browser that can be unique within a large group of users.  
  **Solution[easy]:** Use browser extensions that reduce or alter the fingerprint.  
  **Solution[easy]:** Use Tor Browser.
- Username.  
  **Solution[easy]:** Use a deducated and unique username.  
  **Solution[easy]:** Use a deducated and unique email address as the username.  
- Email address  
  **Solution[easy]:** Use a non-existent fake email address if there is zero need
  for them to have it. This is not likey because most services require you to very
  the email address. Also, a email address will be needed if you have to communicate
  or reset your password.  
  **Solution[easy]:** Use a temporary email address if there is zero need for them to
  have it other than signup. Only do this if you'll never need to to email them, reset
  your password, or they send personal account information to the email.  
  **Solution[easy]:** Use a unique and dedicated email address for them.
- Mailing address  
  **Solution[easy]:** Use a non-existent fake address.  
  **Solution[easy]:** If they verify the address is real, but they will never need
  to mail you, then use an existing address that is real.  
  **Solution[easy]:** Use a mail forwarding address if they need your address
  to fulfill their service with you.
- Personal name  
  **Solution[easy]:** Usa a fake name.
- Account phone numbers  
  **Solution[easy]:** Use a fake phone number.  
  **Solution[easy]:** Use a VOIP number if the service needs to get in touch
  with you.
- Billing data (name, address, phone, credit card, bank account).  
  **Solution[easy]:** Use a more private form of electronic payment.
- Voice recordings, caller ID, and more info can be looked up from the caller ID
  such as carrier and registered name.  
  **Solution[easy]:** Don't call them.  
  **Solution[easy]:** Always contact them through a VOIP number dedicated to them.
- Any information shared with them or passing through their computer systems.  
  **Solution[easy]:** Fake identifiers.  
  **Solution[easy]:** Use the other guidelines to reduce the amount shared.


## Common Services That KNOW Your ID

Here are some eamples of services know your ID and open communication will be
needed with them:
- tax agencies
- other gonvermental agencies (SSA, etc)
- judicial courts
- financial institutions
  - banks
  - investment brokers
  - creditors (loans, credit cards)
- mail handlers (forwarding services)
- medical providers
- licensing agencies (vehicle, etc)
- landlords
- insurance
- employers
- most electronic payment systems (Apple Pay, Venmo, etc)


## Other Resources

https://www.privacyguides.org/

Reddit Forums:
- https://libredd.it/r/privacy
- https://libredd.it/r/PrivacyGuides/


## Own by Business Proxy

You can register a business in different states that have strong business
privacy laws and then use that business to purchase and own assets you don't
want directly tied to your ID.

Good candidate purchases:
- Real estate
- Automobiles
- Any legally registered assets

Pros:
- Prevents easily finding the assets you own.
- Reduces your ID being used in common ID search services.

Cons:
- Can cost a few hundred dollars a year to maintain the business
  registration.
