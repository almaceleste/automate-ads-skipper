# 🏴‍☠️ Ads Skipper (Automate flow)

⚠️ Requires .lib-config library <https://llamalab.com/automate/community/flows/41815>  
⚠️ Recommended: disable flow logging.

👹 Ad providers are inventing more and more ways to get your attention, spend your time and make money from you. These methods could be very annoying and even... spoofing. For example, some providers create ads with a looping video that plays infinitely until you click on the close cross. Either use fake close buttons, or make the real button very small and hard to click.

🏴‍☠️ Ads Skipper keeps a vigilant eye on ads activities and closes them as soon as the close button appears. So you can relax and go about your business while the ad is playing, and when you return the ad view will be closed.

🔇 Works well when coupled with Muted Activities flow:
<https://llamalab.com/automate/community/flows/41710>

⛔ Ads Skipper now recognizes these ad providers:

* AdColony Ads
* MyTarget Ads
* Supersonic (IronSource) Ads
* Unity Ads
* Vungle Ads

## 📑 TODO

* Add recognition for Google Ads and Facebook Ads
* Add update mechanism

-------

v2: change rule key to a hash of the rule content to fix an issue where you can't add a rule with the same xpath but a different timeout
