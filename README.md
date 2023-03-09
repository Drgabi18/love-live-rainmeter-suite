I originally had the intention of making a skin for the LP counter and then develop other skins for the suite so you can replicate the Main Menu.

I hate paying money for games, especially gacha games, so I usually automate stuff or lose interest in them.

If you're paying a single cent for a lootbox, capsule, card or case, you've fallen for their predatory practices, take a better look at yourself and stop it. 

Anyways, for this skin, what I should have done is to not use Lua and Loop/Calc measure, but to use the Windows Timestamp feature instead with the Uptime meter (this also makes the skin work after you unload and load it, so it would work with Game Mode too).

All I needed to do is `EndTimeStamp = CurrentTimestamp + (<End N of LP> - <Current N of LP>) * 60 * 6` to get the the timestamp for the end, and then on the Uptime measure just do `SecondsValue = EndTimestamp - CurrentTimeStamp` to transform the seconds remaning with `Format`.

Project is abandoned because SIF LL1 got axed (and you can't transfer your cards at all, which is dumb; and can't transfer anything if you're European, which is dumber as to circumvent GDPR, which they are afraid of, all you needed to do is make an aknowladgement tickbox) and I lost interest in the series.

([still find it funny this happened](https://www.reddit.com/r/TwoBestFriendsPlay/comments/tk916g/warning_collabing_with_persona_has_high_chance_of/))
