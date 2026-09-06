# Mediaquest EPG Data

This repository hosts the raw EPG (Electronic Program Guide) data for Mediaquest (Cignal) channels in XMLTV format. 
The data is fetched securely and updated automatically.

## How to Use in your IPTV Player

Simply copy and paste one of the URLs below into your IPTV player (such as TiviMate, IPTV Smarters, etc) as your EPG Source URL.

**Compressed GZ Format (Recommended - Loads faster):**
```text
https://raw.githubusercontent.com/djdoolky76/Mediaquest-EPG/main/cignal_epg.xml.gz
```

**Standard XML Format:**
```text
https://raw.githubusercontent.com/djdoolky76/Mediaquest-EPG/main/cignal_epg.xml
```

## Channel `tvg-id` Mapping

To ensure your channels map perfectly to this EPG data in your M3U file, you must use the exact `tvg-id` listed below. 

Example M3U entry:
```text
#EXTINF:-1 tvg-id="bbcworld_news_sd" tvg-name="BBC News", BBC News
http://your-stream-url.com
```

### Supported Channel IDs:

60 channel IDs from this repository's generated EPG, updated September 6, 2026.
Use the ID before ` - ` as your M3U `tvg-id`; the text after it is the channel name.
Channel availability and names follow the upstream feed and may change.

```text
abc_australia - ABC Australia
amagi - A3G
arirang_sd - Arirang
bbcworld_news_sd - BBC World News
bilyonaryoch - Bilyonaryo News Channel
bloomberg_sd - Bloomberg
cg_a2z - A2Z
cg_abante_news - Abante News TV
cg_animax_sd_new - Animax
cg_axn_sd - AXN
cg_bbcearth_hd1 - BBC Earth HD
cg_bbclifestyle - BBC Lifestyle
cg_cnnhd - CNN HD
cg_dreamworks_hd1 - DreamWorks HD
cg_dreamworktag - DreamWorks Tagalog
cg_hitsnow - HITS Now
cg_moonbug_kids_sd - Moonbug Kids
cg_ncaa - NCAA NXT
cg_onesports_hd - One Sports HD
cg_onesportsplus_hd1 - One Sports+ HD
cg_pbarush_hd1 - PBA Rush HD
cg_ps_hd1 - Premier Sports HD
cg_ptv4_sd - PTV 4
cg_spotvhd - SPOTV HD
cg_studio_universal_hd - Studio Universal
cg_tapmovies_hd1 - TAP Movies HD
cg_tvnmovie - tvN Movies
cg_tvnpre - tvN Premium
cg_uaap_cplay_sd - UAAP Varsity Channel
cgnl_nba - NBA TV Philippines
cgtn - CGTN
cgtn-test - CGTN
channelnewsasia - Channel NewsAsia (CNA)
cnn_rptv_prod_hd - RPTV HD
depedch_sd - DepEd Channel
dr_aljazeera - Al Jazeera
dr_cctv4 - CCTV-4
dr_historyhd - History HD
dr_lifetime - Lifetime
dr_nhk_japan - NHK World Japan
dr_nickelodeon - Nickelodeon
dr_rockentertainment - ROCK Entertainment
dr_rockextreme - ROCK Extreme
dr_spotv2hd - SPOTV2 HD
dr_tapsports - TAP Sports
fashiontvhd - FashionTV HD
fifafast - F1F
globaltrekker - Global Trekker
hits_hd1 - HITS HD
hits_movies - HITS Movies
ibc13_sd_new - IBC 13
kapatid_hd - Kapatid Channel HD
knowledge_channel - Knowledge Channel
lotusmacau_prd - Lotus Macau
onenews_hd1 - One News HD
oneph_sd - One PH
pl_sdi10 - PL SDI 10
premiersports2hd - Premier Sports 2 HD
tv5 - TV5
tvmaria_prd - TV Maria
```
