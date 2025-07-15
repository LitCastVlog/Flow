<img src="./images/logo.png" width="50%"/>

# **Plex-inspired theme for Jellyfin WebUI**
### **Built on [Scyfin](https://github.com/loof2736/scyfin/), [Ultrachromic](https://github.com/CTalvio/Ultrachromic)**

[Go to installation](#installation)

Also avaliable as a [Userstyle](https://userstyles.world/style/21576/flow-for-jelyfin)

---
<img src="./images/screen.jpg" width="100%"/>

<img src="./images/details.png" width="100%"/>

### **Outline Cards on hover**
<img src="./images/outline_hover.gif" width="100%"/>
<img src="./images/outline.gif" width="100%"/>

### **Backdrop Support**
<img src="./images/backdrop_setting.gif" width="100%"/>

### Base Theme
`@import url('https://cdn.statically.io/gh/LitCastVlog/Flow/main/CSS/ScyFlow-main.css');`


### Extras (*smaller cast/crew, etc*) 
`@import url('https://cdn.statically.io/gh/LitCastVlog/Flow/main/CSS/ScyFlow-Extras.css');`

 - B/W Logo (credits: [RoyalxZealot](https://www.steamgriddb.com/logo/128502))
 - Smaller Cast/Crew section
 - Hide "Upcoming on TV" and "Next Up" section in Season View

### Options (Add these after/under the base theme)
- Enable Collapsable Drawer/Menu 
    - `@import url('https://cdn.statically.io/gh/LitCastVlog/Flow/main/CSS/ScyFlow-Drawer-Toggle.css');`
      <img src="./images/drawer-toggle.gif" width="100%"/>
- Bigger logo (for High DPI/Jellyfn Media Player)
    - `@import url('https://cdn.statically.io/gh/LitCastVlog/Flow/main/CSS/ScyFlow-HighDPIExtras.css');`
      <img src="./images/highdpi.png" width="100%"/>
- Episode Grid (from [Ultrachromic](https://github.com/CTalvio/Ultrachromic))
    - `@import url('https://cdn.statically.io/gh/LitCastVlog/Flow/main/CSS/ScyFlow-EpisodeGrid.css');`
      <img src="./images/episodegrid_uc.png" width="100%"/>
- Round Cast/Crew/Guests
    - `@import url('https://cdn.statically.io/gh/LitCastVlog/Flow/main/CSS/ScyFLow-RoundCastCrew.css');`
      <img src="./images/roundcastcrew.png" width="100%"/>      
- Themes:
    - Orange
        - `@import url('https://cdn.statically.io/gh/LitCastVlog/Flow/main/CSS/Themes/ScyFlow-Orange.css');`
        - <img src="./images/orange.png" width="100%"/>
    - Pink
        - `@import url('https://cdn.statically.io/gh/LitCastVlog/Flow/main/CSS/Themes/ScyFlow-Pink.css');`
        - <img src="./images/pink.png" width="100%"/>
    - White
        - `@import url('https://cdn.statically.io/gh/LitCastVlog/Flow/main/CSS/Themes/ScyFlow-White.css');`
        - <img src="./images/white.png" width="100%"/>
    - Blue
        - `@import url('https://cdn.statically.io/gh/LitCastVlog/Flow/main/CSS/Themes/ScyFlow-Blue.css');`
        - <img src="./images/blue.png" width="100%"/>

   - Darker icons/accents (Add this after everything else):
        - `@import url('https://cdn.statically.io/gh/LitCastVlog/Flow/main/CSS/Themes/ScyFlow-Dark.css');`
   
  # Compatible with Scyfin/Ultrachromic themes:     
    - Seafoam
        - `@import url('https://cdn.jsdelivr.net/gh/loof2736/scyfin@latest/CSS/theme-seafoam.css');`
    - Coral
        - `@import url('https://cdn.jsdelivr.net/gh/loof2736/scyfin@latest/CSS/theme-coral.css');`
    - Snow
        - `@import url('https://cdn.jsdelivr.net/gh/loof2736/scyfin@latest/CSS/theme-snow.css');`
  # Experimental (Works in progress)
    - Episode Grid Outline/Dim on hover
        - `@import url('https://cdn.statically.io/gh/LitCastVlog/Flow/main/CSS/ScyFlow-EpisodeGrid-outline.css');`
        - <img src="./images/episodegrid-outline.gif" width="100%"/>
    - Horizontal-Scroll Episodes
        - `@import url('https://cdn.statically.io/gh/LitCastVlog/Flow/main/CSS/ScyFlow-Scrollable-Episodes-WIP.css');`
        - <img src="./images/sidescroll-episodes-wip.gif" width="100%"/>
    - Horizontal-Scroll Episodes (alt, contorls overlayed)
        - `@import url('https://cdn.statically.io/gh/LitCastVlog/Flow/main/CSS/ScyFlow-Scrollable-Episodes-ALT.css');`
        - <img src="./images/sidescroll-episodes-alt.gif" width="100%"/>  
---

### **Installation:**

### Easy install (one-liner) 
`@import url('https://cdn.statically.io/gh/LitCastVlog/Flow/main/CSS/ScyFlow-oneliner.css');` 

**(Mobile/Android one-liner)**: `@import url('https://cdn.statically.io/gh/LitCastVlog/Flow/main/CSS/ScyFlow-oneliner-mobile.css');` 


 <img src="./images/ios.gif" width="60%"/><img src="./images/android.gif"  height="8%"/>
- **Mobile/App fixes:** *if the logo is too big or doesn't apply (iOS, Android), append this line as well (per client)* 
  - `@import url('https://cdn.statically.io/gh/LitCastVlog/Flow/main/CSS/ScyFlow-mobilefixes.css');`
- **Smaller Screen/Android fixes:** *if the indicators are too big* 
  - `@import url('https://cdn.statically.io/gh/LitCastVlog/Flow/main/CSS/ScyFlow-smallscreen-fixes.css');`


**Server-wide install:**
* Click the hamburger icon (Top left)
* Navigate to "Dashboard" (If you don't see this, make sure you are signed in to your admin account)
* Navigate to "General"
* Near the bottom, under "Custom CSS code", paste the `@import url` for the base theme
    * Example:
    * <img src="./images/install-server-base.png" alt="install-server-base" width="80%"/>
* Optional - Paste the `@import url` for any options / themes you may want
    * Example:
    * <img src="./images/install-server-options.png" alt="install-server-options" width="80%"/>
* Click "Save"

---


**Single client install:**
* Click the hamburger icon (Top left)
* Navigate to "Settings"
* Navigate to "Display"
* Near the middle, under "Custom CSS code", paste the `@import url` for the base theme
    * Note - 
        * If there is any server-wide custom CSS, you may want to enable "Disable server-provided custom CSS code", as the two themes WILL interfere with each other
    * Example:
    * <img src="./images/install-client-base.png" alt="install-client-base" width="80%"/>
* Optional - Paste the `@import url` for any options / themes you may want
    * Example:
    * <img src="./images/install-client-options.png" alt="install-client-options" width="80%"/>
* Click "Save"
