
# Personal DNS Blocklist

My personal collection of domains I choose to block, intended to supplement existing DNS blocklists rather than replace them.

Entries reflect my own privacy preferences and findings. The list may cover telemetry, tracking, unwanted connections, and other domains I don't want my devices contacting.

This is an ongoing personal project. Its contents may change as I investigate software, discover new endpoints, and refine my setup.

## Installation

Add the following URL to your DNS filtering software's blocklist subscriptions:

https://raw.githubusercontent.com/Nirvaxstiel/kei-blocklist/refs/heads/master/vivaldi-telemetry.txt

For Pi-hole, add the URL under **Lists / Adlists**, then update Gravity.

Replace the URL above with the actual raw URL for this repository.

## Other Blocklists Worth Exploring

These are independent projects that may complement this list. They have different scopes, overlaps, and trade-offs. Review their documentation before subscribing.

### General-purpose filtering

- [StevenBlack/hosts](https://raw.githubusercontent.com/StevenBlack/hosts/master/hosts)
- [HaGeZi Pro](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/adblock/pro.txt)
- [HaGeZi Pro++](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/adblock/pro.plus.txt)
- [GoodbyeAds](https://raw.githubusercontent.com/jerryn70/GoodbyeAds/master/Hosts/GoodbyeAds.txt)

**Note:** Choose either HaGeZi Pro or Pro++; avoid subscribing to both unless you have a specific reason.

### Category-specific filtering

- [Mullvad — advertising](https://raw.githubusercontent.com/mullvad/dns-blocklists/main/output/doh/doh_adblock.txt)
- [Mullvad — privacy and trackers](https://raw.githubusercontent.com/mullvad/dns-blocklists/main/output/doh/doh_privacy.txt)
- [Mullvad — malware](https://raw.githubusercontent.com/mullvad/dns-blocklists/main/output/doh/doh_malware.txt)
- [Mullvad — gambling](https://raw.githubusercontent.com/mullvad/dns-blocklists/main/output/doh/doh_gambling.txt)
- [Mullvad — social media](https://raw.githubusercontent.com/mullvad/dns-blocklists/main/output/doh/doh_social.txt)

Check each project's documentation and maintenance status before relying on its lists.