+++
date = '2026-10-04T18:21:46-04:00'
draft = false
title = 'Cutting US Travel Roaming Costs with a MobiMatter eSIM and Dual SIM Setup'
tags = ['esim', 'rogers', 'iphone', 'travel', 'road-trip']

[params.cover]
  image = "banner.jpg"
  alt = "Cutting US Travel Roaming Costs with a MobiMatter eSIM and Dual SIM Setup"
  relative = true
+++

## A Canada-Only Plan and a $16-a-Day Problem

A few weeks ago I switched my Rogers plan to a 175GB package. The local data bucket was massive, but reading the service terms later turned up something important: my previous plan included calling and data across Canada and the United States, and this new tier was Canada only. Taking the line across the border meant Rogers would bill Roam Like Home at $16 a day for the United States. Use a ten-day trip as the example and that fee reaches $160 before tax, for a drive that only needs map navigation, quick searches, and messaging.

Rogers is not limited to the daily rate, and the honest comparison has to say so. It also sells US Travel Passes, $60 for 14 days and $80 for 30 days, and a pass keeps your own number working for calls, texts, and data with no setup at all. A travel data eSIM still undercuts both options by a wide margin, at the cost of about ten minutes of configuration before you leave.

I opened the MobiMatter app and compared the US bundles. I picked a 10GB package valid for 30 days, running on the BICS wholesale network, for $16.50 Canadian. That single upfront payment costs about the same as one day of Rogers roaming, and 10GB is more than enough volume for a short road trip.

## Installing the eSIM Before the Border

Installing the profile took two minutes at home. MobiMatter delivers a QR code in the app. In iOS, open Settings, tap Cellular, and select Add eSIM to open the camera scanner. The phone reads the profile, downloads the carrier credentials, and adds the line to the list. I labeled the new line Travel USA so it could never be confused with my primary number.

On the listing I bought, the activation policy in the app says the package activates when it connects to a network, so installing it at home did not start my 30 days. That policy line is worth checking before any purchase, because other listings start the clock at installation. A US-only package also has nothing to connect to while it sits in Canada, which is why this one stayed dormant until the border.

## The Five Settings That Keep Rogers Quiet

The purchase is the easy part. The real work is setting up the dual SIM options so the travel data works immediately while the Rogers line stays dormant. A stray data packet, an answered voice call, or an outgoing text message over an American tower triggers the $16 daily fee at once.

First, open Cellular Data at the top of the Cellular screen and select Travel USA as the active data line. Directly below the list of lines, switch Allow Cellular Data Switching off. With that toggle on, the iPhone will grab Rogers data on its own whenever the travel network drops into a weak pocket, and the day is billed immediately.

Second, tap into the Rogers line under the SIMs list. Leave Turn On This Line on, and turn Data Roaming completely off. Keeping the line on lets standard incoming text messages arrive, which matters because banks send two-factor codes by SMS. In practice, the codes arrived all through our trip and no daily fee appeared on my bill for receiving them. I would still treat that point with care, because Rogers' own roaming checklist counts receiving texts as roaming usage, and two related traps are unambiguous: retrieving voicemail or letting Apple Live Voicemail fetch a message counts as usage, and a picture message travels as data. I left voicemail alone for the whole drive.

Third, tap into the Travel USA line and switch Turn On This Line on. On this line, Data Roaming goes on. The eSIM works through an international wholesale routing partner, so the profile has to roam onto local American host networks such as AT&T or T-Mobile to move packets. Data roaming off on the travel profile leaves you with dead air at the border.

Fourth, open the Travel USA line, tap Data Mode, and select Low Data Mode. That pauses heavy background work, cloud photo uploads, and automatic App Store downloads while driving, so navigation and messaging run cleanly without burning the 10GB allowance in the background. The Rogers line needs no data mode setting, since it carries no data in this setup.

Fifth, check Default Line in the Cellular settings, and check the line label shown on any Messages thread before sending. The data settings can be perfect and an outgoing text can still escape onto the Rogers line because a thread defaults to it. Ten seconds of checking the label is cheaper than $16.

## The Bank Alert Trap

One trap deserves its own section. CIBC sends automated fraud alert texts asking the cardholder to reply Y to confirm an unusual purchase. If the phone is sitting on an American tower, that single character is an outbound transmission, and Rogers charges the $16 day for it.

The clean way to reply is Rogers Wi-Fi Calling, switched on before leaving Canada, with the emergency 911 address registered during setup. It works on any Wi-Fi where the status reads Rogers Wi-Fi, a hotel, a café, or a friend's house. The check takes two seconds: if the phone shows a US carrier with signal bars, do not send. Airplane Mode on, then Wi-Fi back on, forces the Rogers line onto the Wi-Fi tunnel so there is no cellular path left. Over Wi-Fi Calling from outside Canada, incoming calls and texts from anywhere and outgoing calls and texts to Canadian numbers come out of your plan with no roaming charge. One limit matters: an outgoing call or text to a US number over Wi-Fi Calling triggers the daily fee anyway, so a US hotel's front desk is a job for the eSIM data and a calling app, not for the Rogers line.

There is a further step for the road. If the Rogers line has no cellular service at all, which you can force under Network Selection by turning Automatic off and picking a network the Rogers line cannot join, the iPhone can run the Rogers line's Wi-Fi Calling over the travel line's data connection. The status then shows the Rogers line using cellular data. In that state a reply to CIBC works from the highway, over the MobiMatter data, still with no roaming fee. Verify the status wording actually changed before sending anything.

Calling the bank beats replying anyway. My iTalkBB plan includes 60 minutes of free long distance a month, and its iPhone app places VoIP calls over the eSIM data connection or Wi-Fi. A call to the 1-800 number on the back of the card uses a few of those minutes, confirms the purchase by voice, and never touches the Rogers network. Any VoIP app you already have does the same job; the point is that the call travels as data.

## On the Road, and Sharing the Connection

For highway navigation I brought our standalone car GPS unit for the dashboard. A programmed route needs no live data, and keeping the phone off the windshield mount keeps it out of direct sunlight and away from overheating. In town, Google Maps on the phone handles traffic, parking, and food searches, and downloading offline map sectors in Google Maps before leaving cuts the data load further. Even with the GPS on the dash, Google Maps fed by the eSIM turned out to be the critical tool of the whole trip, the app reached for at every stop and every detour.

Sharing the connection with my wife took no extra hardware. Check your own listing first, because hotspot support is a line on the product page: mine said Hotspot Available. Under Settings, open Personal Hotspot, set a password, and toggle Allow Others to Join on. Her iPhone then connects to mine like regular Wi-Fi, and the data runs through the 10GB MobiMatter package without touching either of our Rogers lines. On her phone, tapping the info icon beside my hotspot name in Wi-Fi settings and enabling Low Data Mode stops her handset from pulling background system downloads over the shared link.

Preparation took ten minutes at home. On the ten-day example, the setup saves $143.50 against the daily roaming rate and $43.50 against even the 14-day Travel Pass, and the 30-day clock on my package started when the phone first registered on an American tower at the border. The number that settled the size question came at the end of the trip: after ten days of long driving and heavy Google Maps use, 3.5GB of the 10GB was still unused. Both phones stayed fully usable for the entire drive, and the Rogers line never made a sound.

[![Buy Me A Coffee](https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png)](https://buymeacoffee.com/robertluwang)
