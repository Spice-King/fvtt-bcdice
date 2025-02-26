# BCRoller

![Foundry Version Compatability](https://img.shields.io/badge/Foundry-v0.7.9-informational)
![Latest Release Download Count](https://img.shields.io/github/downloads/jsinme/fvtt-bcdice/latest/module.zip)

A module to query the BCDice API for dice rolls. BCDice is the largest dice rolling bot in Japan, containing 100s of different TRPG systems and playstyles.　You can find the sourcecode [here](https://github.com/bcdice/BCDice). Please feel free to join their Discord and discuss your favorite Japanese TRPGs. You can even submit localization files for them.
Alternatively, if you have a system which foundry does not support, you can submit how that system does dice rolls and it can be implemented in BCDice (thus allowing you to use that system in foundry). Currently, the majority of users are from Japan and Korea. Looking forward to seeing others joing the team!

## BCDice
日本で最も使われている、TRPG用ダイスロール処理システムです。どどんとふ、ココフォリア、ユドナリウム、TRPGスタジオなど様々なオンセツールで使われています。（https://bcdice.org/ より引用）
Modの使い方はWikiよりご確認ください。
https://foundryvtt.wiki/ja/BCDice

また、このModは日本コミュニティの支援により開発されました。
プログラマの方はどうぞ気軽にIssueやPRをしてください。その他の方は以下のWikiにあるコミュニティDiscordに入り（事前確認不要）、BCDiceチャンネルで要望をご報告ください。
https://foundryvtt.wiki/ja/home

## Changelog

0.1

- BCDice Control in left controls bar
- Roller Application that allows a user to select from a list of available systems, input a command, and submit that command to the api
- Chat Message containing result fo the roll

  0.2

- Added keyboard shortcut for launching Roller (Ctrl + Shift + B)
- Browser will focus on the command input field when Roller is brought up
- Roller will not close after submitting a roll
  - Unless "Shift + Enter" is used. Then the Roller will submit the roll, close, and focus the browser on the Chat Message input
- Roller will now remember the last selected game system when reopened
- Result chat message will now also contain the original command below the result

  0.2.1

- Added help button to get info on a System
- Added a sound to be played when a roll occurs

  0.2.2

- Fixed formatting for System help messages

  0.2.3

- Changed dice rolling sound to native foundry sound
- Special characters in commands are now escaped properly
- Long single line commands outputs should now wrap properly
- Multi line results will now be properly displayed
- Roller outputs have been reformated for clarity
- Added link to bcdice docs at the top of each System help message

  0.2.4

- Added localization for Japanese

  0.3 Dice So Nice!

- Added support for DSN

  0.4

- Added System Search
- Added Secret Roll Support
- Added Roller Persistance setting
- Bug Fixes
