##PBTech Style for phpBB


![Screenshot](/contrib/screenshot.png)

This style was inspired by the Battlenet forums 2015. example
http://web.archive.org/web/20141207163104/http://us.battle.net/en/forum/topic/10423582376

#### Requirements
- phpBB 3.3.15 or higher
- prosilver

#### Customizing
In the contrib folder you can find a photoshop psd with another icon set. 

### Support
For more information and support, we suggest you visit
- [avathar.be] (https://www.avathar.be/forum/viewforum.php?f=82)  

### Changes
3.0.18 (27-03-2026)
- added missing template events for phpBB 3.3.15 compliance (forumlist_body, search_results)
- added last poster username display to forum list
- removed custom quickstyle_event; use default overall_header_breadcrumbs_after location
- fixed poll block dark background and thick black border
- fixed UCP message colour legend thick border
- fixed incomplete text-shadow in online user guillemets (content.css)
- fixed duplicate closing tag in navbar_footer.html
- fixed broken child-arrow-big.gif reference (now .png)
- removed dead CSS: video-background, mChat, pf_pbbnetavatar, action-bar.compact
- consolidated duplicate CSS rules (vote-submitted, postprofile avatar, poll styles)
- replaced deprecated jQuery .bind() with .on()
- fixed schema.org URL to use HTTPS
- fixed non-standard background-repeat-x/y
- added cache-bust parameter to imageset.css import

3.0.17 (22-02-2026)
- fixed hardcoded assets_version in prosilver stylesheet link
- removed unnecessary prosilver en/stylesheet.css
- removed tweaks.css IE conditional
- use T_FONT_AWESOME_LINK instead of hardcoded CDN URL
- updated webfont URL in simple_header.html
- removed dead CSS rules referencing missing images (poll icons, imageset)
- replaced missing border images with CSS borders in responsive view
- simplified quick-login panel styling (removed missing image references)

3.0.16 (08-02-2026)
- updated for phpBB 3.3.15
- updated post display links to use AJAX anchors (viewtopic)
- added viewtopic_body_postrow_content_before event
- added viewtopic_body_online_list_after event
- added forum link type detection in forumlist tooltips
- updated autocomplete attributes on login forms
- simplified search results sort condition
- merged overall_header.html from prosilver 3.3.15

3.0.15 (10/01/2020)
- updated for phpbb 3.3.2

3.0.14 (03/01/2020)
- updated for phpbb 3.2.10

3.0.13 (24-10-2020)
- updated for phpbb 3.1.11
    
3.0.12 (21-02-2017)
- stylesheet.css refactored into separate files
- pbwow.css merged to other css files

3.0.11.1 (21-02-2017)
- style validation fix.

3.0.11 (15-12-2016)
- style validation fix.

3.0.9 (05-11-2016)
- updated for phpbb 3.1.10

3.0.8.2 (05-11-2016)
- fix top margin of avatar

3.0.8.1 (26-6-2016)
- new design for Polls
- new design for Top bar
- new design for Rules
- changed colors for Bbcode code box
- updated Fontawesome to 4.6
- fix for Recent topics

3.0.8 (12-6-2016)
- updated for phpbb 3.1.9
- updated for Recent Topics v2.1

3.0.7 (05-3-2016)
- updated for phpbb 3.1.8

3.0.6 (05-3-2016)
- updated for phpbb 3.1.7

3.0.5 (05-3-2016)
- updated for phpbb 3.1.6

### License
[GNU General Public License v2](http://opensource.org/licenses/GPL-2.0)

© 2014 - PayBas
