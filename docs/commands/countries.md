# Country commands

Countries are sourced from MusicBrainz.

To enter countries, you can either enter the full name or the 2 letter ISO code.

### .topcountries(`.tc`)

Shows a list of you or your friends top countries over a certain time period.

Options:

* Time period - Time period of your top countries. Defaults to weekly
* Billboard - Show recent changes in your top list in a billboard style
* User - Select another user by mention, Discord ID or Last.fm username (`lfm:username`)

Time periods: 

* `weekly`, `monthly`, `quarterly`, `half`, `yearly` or `alltime`. (`w`, `m`, `q`, `h`, `y` or `a`)
* Also supports year/month timeframes: `2023`, `Mar 2020`, `August`

!!! note "Examples"
    `.tc`

    `.topcountries billboard`
    
    `.topcountries weekly @user`

    `.tc alltime @Voaz bb`

    `.topcountries monthly lfm:fm-bot`

---

### .country (`.from`)

Shows country information for your current artist or your top artists for the country you're searching for.

!!! note "Examples"
    `.from`

    `.country`

    `.country Netherlands`

    `.country Mac DeMarco`


<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js?client=ca-pub-5817610257612647"
     crossorigin="anonymous"></script>
<!-- In-docs -->
<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-5817610257612647"
     data-ad-slot="9031186671"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>
<script>
     (adsbygoogle = window.adsbygoogle || []).push({});
</script>