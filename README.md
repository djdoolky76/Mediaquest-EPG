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
```text
abc_australia - ABC Australia
arirang_sd - Arirang
asianfoodnetwork_sd - Asian Food Network
bbcworld_news_sd - BBC World News
bilyonaryoch - Bilyonaryo News Channel
bloomberg_sd - Bloomberg
buko - BuKo
cartoonnetworkhd - Cartoon Network HD
celmovie_pinoy_sd - Celestial Movies Pinoy
cg_a2z - A2Z
cg_animal_planet_sd - Animal Planet
cg_animax_sd_new - Animax
cg_axn_sd - AXN
cg_bbcearth_hd1 - BBC Earth HD
cg_cinemax - Cinemax
cg_cnnhd - CNN HD
cg_dreamworks_hd1 - DreamWorks HD
cg_dreamworktag - DreamWorks Tagalog
cg_foodnetwork_hd1 - Food Network HD
cg_hbofam - HBO Family
cg_hbohd - HBO HD
cg_hbohits - HBO Hits
cg_hbosign - HBO Signature
cg_hitsnow - HITS Now
cg_moonbug_kids_sd - Moonbug Kids
cg_onesports_hd - One Sports HD
cg_onesportsplus_hd1 - One Sports+ HD
cg_pbarush_hd1 - PBA Rush HD
cg_ps_hd1 - Premier Sports HD
cg_ptv4_sd - PTV 4
cg_spotvhd - SPOTV HD
cg_tagalogmovie - Tagalog Movie Channel (TMC)
cg_tapmovies_hd1 - TAP Movies HD
cg_thrill_sd - Thrill
cg_tvnmovie - tvN Movies
cg_tvnpre - tvN Premium
cg_uaap_cplay_sd - UAAP Varsity Channel
cg_warnerhd - Warner TV HD
cgnl_nba - NBA TV Philippines
cgtn - CGTN
channelnewsasia - Channel NewsAsia (CNA)
crime_invest - Crime + Investigation
cnn_rptv_prod_hd - RPTV HD
depedch_sd - DepEd Channel
discovery - Discovery Channel
dr_aljazeera - Al Jazeera
dr_cctv4 - CCTV-4
dr_historyhd - History HD
dr_lifetime - Lifetime
dr_nhk_japan - NHK World Japan
dr_nickelodeon - Nickelodeon
dr_nickjr - Nick Jr.
dr_rockentertainment - ROCK Entertainment
dr_rockextreme - ROCK Extreme
dr_spotv2hd - SPOTV2 HD
dr_tapsports - TAP Sports
dr_tv5_monde - TV5Monde
fashiontvhd - FashionTV HD
fifa-ppv1 - FIFA PPV 1
france24 - France 24
globaltrekker - Global Trekker
hgtv_hd1 - HGTV HD
hits_hd1 - HITS HD
hits_movies - HITS Movies
ibc13_sd_new - IBC 13
kapatid_hd - Kapatid Channel HD
kbsworld - KBS World
kix_hd1 - KIX HD
knowledge_channel - Knowledge Channel
lotusmacau_prd - Lotus Macau
onenews_hd1 - One News HD
oneph_sd - One PH
premiersports2hd - Premier Sports 2 HD
travel_channel_sd - Travel Channel
truefm_tv - True FM TV
tv5 - TV5
tv5vibetv - Vibe TV
tvmaria_prd - TV Maria
```
