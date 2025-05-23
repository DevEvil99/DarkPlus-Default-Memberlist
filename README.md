# Default Member List Versions of Dark+ and Azurite Now Integrated!

The default member list variants of the **Dark+** and **Azurite** themes are now part of their main theme version!

If you're using the default member list version, please download the latest versions of the themes directly from the BetterDiscord website:

* [Dark+ Theme](https://betterdiscord.app/theme/Dark%2B)
* [Azurite Theme](https://betterdiscord.app/theme/Azurite)

Once downloaded, follow the steps below to enable the default member list version in each theme:


## Dark+

1. **Open the theme file** in a text editor.
2. **Comment out** the main theme import by wrapping it in `/*` and `*/`:

   ```css
   /*@import url('https://devevil99.github.io/devevil/BetterDiscordAddons/Theme/Dark+/Dark+.theme.css');*/
   ```
3. **Uncomment** the default member list version by removing the `/*` and `*/`:

   ```css
   @import url('https://devevil99.github.io/devevil/BetterDiscordAddons/Theme/Dark%2B/Dark%2B-Default-Member-List.css');
   ```
4. **Save the file** and reload your theme in BetterDiscord.
