---
authors: Sye Williams
title: Generic Account Management FAQ
slug: generic-email-accounts
---

import TOCInline from '@theme/TOCInline';  

<TOCInline toc={toc} />

## What is a generic account?

A generic account is an ASC account that is meant for general departmental purposes. This account may act as the first point of contact for people with inquires for your department. 

We recommend that every generic account has at least one Account Manager, *who is the one person who has the password and the default MFA verification associated with their device*. 
## Several people need to be able to check a generic email account. Any recommendations? 

If the generic account's email needs to be check by one or more people at any point point, we recommend setting up email delegation. This way, multiple people can check the account without having to interact with MFA. 

The Account Manager should do the following to setup email delegation:
1. Open an Incognito ([Chrome](https://support.google.com/chrome/answer/95464?hl=EN&co=GENIE.Platform%3DDesktop)) or a Private ([Firefox](https://support.mozilla.org/en-US/kb/private-browsing-use-firefox-without-history#w_how-do-i-open-a-new-private-window) | [Safari](https://support.apple.com/guide/safari/browse-privately-ibrw1069/mac)) window in your respective browser. Doing this will thwart potential sign-in conflicts with your personal ASC account. 
2. Navigate to https://scottiemail.agnesscott.edu 
3. Sign in and complete the MFA process.
4. Follow these instructions from Google to invite your personal ASC account and others to check the generic account without having to do MFA: https://support.google.com/mail/answer/138350?hl=en

## Multiple people need to use the generic account to access a browser-based licensed application (Smartsheet, etc). What should we do?

In this case, it would be best if the Account Manager added everyone who needs to access those applications as an MFA alternative. 

Please refer to [MFA at Agnes FAQ > I want to be able to use MFA on a second device. How do I set that up?](https://asc-testsite2.netlify.app/docs/account-access-id-cards/MFA#i-want-to-be-able-to-use-mfa-on-a-second-device-how-do-i-set-that-up) to add other individuals to the MFA. We recommend using their Avaya Cloud Office or personal number as alternative verifications for the sake of ease. *Alternatively*, the Account Manager can collaborate with whomever needs access to set up alternative Authenticator app users.

:::info
When anyone besides the Account Manager signs into the generic account and this person's authentication method for the generic account is a phone number, they must hit "**I can't use my Authenticator app right now**" and find the verification method associated with themselves. 
:::

