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
abc_australia
arirang_sd
asianfoodnetwork_sd
bbcworld_news_sd
bilyonaryoch
bloomberg_sd
buko
cartoonnetworkhd
celmovie_pinoy_sd
cg_a2z
cg_animal_planet_sd
cg_animax_sd_new
cg_axn_sd
cg_bbcearth_hd1
cg_cinemax
cg_cnnhd
cg_dreamworks_hd1
cg_dreamworktag
cg_foodnetwork_hd1
cg_hbofam
cg_hbohd
cg_hbohits
cg_hbosign
cg_hitsnow
cg_moonbug_kids_sd
cg_onesports_hd
cg_onesportsplus_hd1
cg_pbarush_hd1
cg_ps_hd1
cg_ptv4_sd
cg_spotvhd
cg_tagalogmovie
cg_tapmovies_hd1
cg_thrill_sd
cg_tvnmovie
cg_tvnpre
cg_uaap_cplay_sd
cg_warnerhd
cgnl_nba
cgtn
channelnewsasia
crime_invest
cnn_rptv_prod_hd
depedch_sd
discovery
dr_aljazeera
dr_cctv4
dr_historyhd
dr_lifetime
dr_nhk_japan
dr_nickelodeon
dr_nickjr
dr_rockentertainment
dr_rockextreme
dr_spotv2hd
dr_tapsports
dr_tv5_monde
fashiontvhd
fifa-ppv1
france24
globaltrekker
hgtv_hd1
hits_hd1
hits_movies
ibc13_sd_new
kapatid_hd
kbsworld
kix_hd1
knowledge_channel
lotusmacau_prd
onenews_hd1
oneph_sd
premiersports2hd
travel_channel_sd
truefm_tv
tv5
tv5vibetv
tvmaria_prd
```
