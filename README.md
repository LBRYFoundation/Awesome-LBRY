[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

# Awesome-LBRY-Projects <!-- omit in toc -->
A list of community run projects built on and for the LBRY protocol.

<!-- omit in toc -->
## Contents
- [LBRY clients](#lbry-clients)
- [LBRY web-based front-ends](#lbry-web-based-front-ends)
- [Tools](#Tools)
- [Applications bots and addons](#applications-bots-and-addons)
- [Scripts & one-purpose applications](#scripts--one-purpose-applications)
- [Analytics](#analytics)
- [LBRY infrastructure monitoring](#lbry-infrastructure-monitoring)
- [Browser extensions](#browser-extensions)
- [LBC wallets](#lbc-wallets)
- [LBC mining pools](#lbc-mining-pools)

## LBRY clients
- [FastLBRY Terminal](https://notabug.org/jyamihud/FastLBRY-terminal) - A fully featured, terminal application to interact with LBRY. It will allow watching videos, download files, view and send comments, upload new files.
- [Odysee Unofficial (Roku App)](https://github.com/OdyseeTeam/odysee-roku) - A unofficial Odysee app which is on Roku.
- [FastLBRY-GTK](https://notabug.org/jyamihud/FastLBRY-GTK) - GTK version of FastLBRY.
- [LBRY App - Community Edition](https://github.com/lbry-foss/lbry-desktop) - A fork of the LBRY desktop app with no analytics and also adds some features back.
- [LBRY-GTK](https://codeberg.org/MorsMortium/LBRY-GTK) - Another GTK version of FastLBRY.
- [LyBerry](https://notabug.org/MyBeansAreBaked/lyberry) - A LBRY client. Uses Qt or Curses and written in Python.
- [Actarius LBRY browser](https://github.com/Shroom2020/actarius-lbry-browser) - Electron based web browser that supports LBRY protocol.
- [lbry_flutter](https://github.com/dakontiva/lbry_flutter) - Flutter based LBRY browser app.

## LBRY web-based front-ends
- https://madiator.com/ - [GitHub](https://github.com/kodxana/madiator.com) - P2P Powered LBRY Instance.
- [Madiator Speaks](https://speak.madiator.com/) - [GitHub](https://github.com/kodxana/spee.ch) - An image hosting service on top of the LBRY protocol based on spee.ch.
- [Odysee chatter](https://live.odysee-chatter.com/) - Bot listing Odysee live streams.
- [Hound.fm](https://hound.fm) - [GitHub](https://github.com/Hound-fm/web) - Discover music and podcasts.

## Tools
- [lbrytools](https://github.com/belikor/lbrytools) - A Python library with various methods built on top of the terminal `lbrynet` client. It includes methods to download and manage multiple claims, list downloaded claims, list the existing blobs, add, remove and change the support to claims, calculate the seeding ratio, and others. It includes various tools inspired by [Brendon Brewer](https://odysee.com/$/list/3a8c64f781ab2ed2d17f8f808c708a5ee0b04423), tuxfoo, miko, and other members of the community.
- [zeedit](https://github.com/belikor/zeedit) - A terminal program to download claims from specific channels by using a configuration file. This program can be used in a headless server to create a seedbox. It is based on [lbrytools](https://github.com/belikor/lbrytools).
- [lbrydseed](https://github.com/belikor/lbrydseed) - Graphical interface to perform various actions on the LBRY network. It is basically a graphical interface to many methods of the [lbrytools](https://github.com/belikor/lbrytools) library.
- [lbt](https://gitlab.com/gardenappl/lbt) - lbt is a collection of command-line tools for interacting with the LBRY network, written in POSIX shell.
- [Email Over Blockchain](https://github.com/mlibre/email-on-blockchain) - Uses the LBRY blockchain to allow you to send emails as claims. 
- [wol-api](https://github.com/devbrones/wol-api) - WOL-API (API for future impl. in Watch-on-LBRY)
- [Podcatcher](https://github.com/Hound-fm/podcatcher) - An open source audio media crawler for lbry. Helps you discover music and podcasts.

## Applications bots and addons
- [lbry_discord_repost_bot](https://github.com/neofutur/lbry_discord_repost_bot) - Discord bot to post new uploads on a LBRY channel to a specific discord channel.
- [LBRY on Kodi](https://github.com/stellartux/plugin.video.lbry) - This is a Kodi addon for allowing access to the Lbry network.
- [Curate](https://github.com/LBRYFoundation/curate) - A discord bot that works through the LBRY SDK to allow placing supports on content creators channels.


## Scripts
- [lbry-sync-ytdl](https://gitlab.com/gardenappl/lbry-sync-ytdl) - lbry-sync-ytdl is a shell script for uploading content to LBRY using youtube-dl.
- [lbry-channel-feed](https://gitlab.melroy.org/melroy/lbry-channel-feed) - LBRY RSS Feed provider - Support channels at the moment (RSS, Atom & JSON).
- [LBRY Utility Scripts](https://odysee.com/$/list/3a8c64f781ab2ed2d17f8f808c708a5ee0b04423) -
     Various python scripts for LBRY by Brendon Brewer:
     - A Python script to download all content (or just recent content) from a single LBRY channel
     - A Python script to check all your LBRY vanity names (LBRY Desktop)
     - A Python tool to manage stalled LBRY downloads
     - A Python script to delete files from your LBRY Library on a per-channel basis
     - Estimate your LBRY seeding ratio with this little Python script
- [LBRYFileUploader](https://github.com/Blanxs/LBRYFileUploader) - Java based mass file uploader for LBRY.
- [lbry-cloner](https://github.com/johndoe0039/lbry-cloner) - This program downloads videos from YouTube and uploades them to LBRY.
- [lbry-resigner](https://github.com/nikooo777/lbry-resigner) - Tool to resign streams with an existing channel [lbry-resigner tutorial](https://odysee.com/@LBRYClass:f/odysee-resigner:b)
- [blogchain](https://github.com/lyoshenka/blogchain) - Blogging with LBRY and Gatsby.
- [lbry-trending-algos](https://github.com/eggplantbren/lbry-trending-algos) - Various LBRY trending algorithms by Brendon Brewer.
- [better-lbry-resolver](https://github.com/LavRadis/better-lbry-resolver) - Simple tool to easily resolve LBRY network claims to get the associated metadata.
- [Wordpress LBRY sync](https://odysee.com/@tuxfoo:e/wordpress-sync:3) - Syncing LBRY content to a Wordpress blog.

## Analytics
- [LBRYnomics](https://lbrynomics.com/) - A website with tons of data on the top channels on the LBRY protocol, general data widgets and graphs.
- [LBRYlytics](https://www.lbrylytics.com/) -  A tool to visualize your stats pulled from LBRYio ChainQuery, LBRY API and CryptoCompare public APIs to get your data and is in no way affiliated with LBRY, Inc.

## LBRY infrastructure monitoring
- https://status.madiator.com/ - Madiator uptime tracker
- https://nodes.madiator.com/ - Public LBRY Blockchain Network Overview

## Browser extensions
- Watch on Odysee - [Firefox](https://addons.mozilla.org/en-GB/firefox/addon/watch-on-odysee/) [Chromium](https://chrome.google.com/webstore/detail/watch-on-odysee/kofmhmemalhemmpkfjhjfkkhifonoann) [GitHub](https://github.com/kodxana/Watch-on-Odysee) - Plugin that automatically redirects you to the Odysee version of any video on YouTube that is available on Odysee.
- Watch on LBRY - [Firefox](https://addons.mozilla.org/en-US/firefox/addon/watch-on-lbry/) [Chromium](https://chrome.google.com/webstore/detail/watch-on-lbry/jjmbbhopnjdjnpceiecihldbhibchgek) [GitHub](https://github.com/LBRYFoundation/Watch-on-LBRY) - Plugin for web browsers that allows you to find people you watch on YouTube that are available on the LBRY Protocol, allows you to easily check your subscribtion list and much more!
- LBRY Link - [Chromium](https://chrome.google.com/webstore/detail/lbry-link/bnhpdmdbfbnopgncbpgdkidpnmkbidfa) [GitHub](https://github.com/seanyesmunt/lbry-link) - Makes `lbry://` links clickable.
- LBC Today - [Firefox](https://addons.mozilla.org/en-GB/firefox/addon/lbc/) [Chromium](https://chrome.google.com/webstore/detail/lbc-today/ealgadmpgaefckfpclemccenfkjihedn) [GitHub](https://github.com/VladHZC/lbc-today/) - Check LBC price live on your browser.

## LBC wallets
- [LBRY Vault for Ledger devices](https://github.com/LBRYFoundation/LBRY-Vault) - Lightweight LBRY Credit client, based on Electrum.
- [Coinomi](https://www.coinomi.com) - A closeds-source blockchain wallet with LBC support along with 1,700+ more cryptocurrencies.

## LBC mining pools - [LBRYPools Discord](https://discord.gg/lbrypool)
- [LBRYPool](https://lbrypool.net/) - [GitHub](https://github.com/LBRYFoundation/pool) - Fork of the yiimp Mining Pool focused on compatibility for mining LBRY Credits.
- [LBRYPool DE](https://lbrypool.de) - A clone of LBRYPool originating in Germany, not affiliated with LBRYPool.net.
- [ZergPool](https://zergpool.net) - A Multi-Coin Mining Pool based on Yiimp that now supports LBC Mining.
