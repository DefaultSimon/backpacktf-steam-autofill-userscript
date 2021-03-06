# backpacktf-steam-autofill-userscript
<div>
    <img alt="Improved Steam Trade Offer Enhancer" src="https://img.shields.io/static/v1?label=Improved%20Steam%20Trade%20Offer%20Enhancer%20version&message=1.5.4&style=flat-square&color=9B9030">
    <img alt="backpack.tf Auto-fill Integration" src="https://img.shields.io/static/v1?label=backpack.tf%20Integration%20version&message=1.0.2&style=flat-square&color=8C71BF">
</div>

A pair of userscripts meant to ease **Steam** (more specifically **TF2**) **trading**. **Autofills currencies (keys, ref, reclaimed, scrap) for [bacpack.tf](https://backpack.tf) orders in the Steam new trade offer window.**

While the backpack.tf integration was written completely by me, the original Steam Trade Offer Enhancer was made by [**HusKy**](https://forums.backpack.tf/topic/17946-script-steam-trade-offer-enhancer/) ([Steam](http://steamcommunity.com/id/H_s_K/)). The improved version has a few new features, such as a warning when you do not have enough items, and the backpack.tf integration support.

## 1. Installation
To install these two userscripts, use a userscript manager like [Tampermonkey](https://www.tampermonkey.net/). Browser addons are available for Chrome, Firefox, Edge and a bunch of other browsers.

**Once installed, install both userscripts by clicking on the links below:**
<div>
    <a href="https://raw.githubusercontent.com/DefaultSimon/backpacktf-steam-autofill-userscript/master/improved-steam-trade-offer-enhancer.user.js">
        <img alt="Install Improved Steam Trade Offer Enhancer" src="https://img.shields.io/static/v1?label=install&message=Improved%20Steam%20Trade%20Offer%20Enhancer&style=for-the-badge&color=4386bc">
    </a>
    <a href="https://raw.githubusercontent.com/DefaultSimon/backpacktf-steam-autofill-userscript/master/backpacktf-improved-trade-integration.user.js">
        <img alt="Install backpack.tf Auto-fill Integration" src="https://img.shields.io/static/v1?label=install&message=backpack.tf%20Auto-fill%20Integration&style=for-the-badge&color=C76F38">
    </a>
</div>

## 2. Features & Usage
`Improved Steam Trade Offer Enhancer` features everything from the latest `1.4.2` *HusKy* version. In addition, it warns the user when trying to add more items than you have available, as well as supports auto-fillling currencies on load by specifying URL parameters, which is in turn used by the backpack.tf integration. Another feature is a button shortcut for adding pure (keys/ref/rec/scrap) currencies without having to search them each time.

The `Backpack.tf Integration` run on [backpack.tf](https://backpack.tf) classifields pages where it scans each one for the requested value and auto-fills the Steam Trade Offer window when/if you click on the trade link on the classifield. Always double check the results, the script is not foolproof!
