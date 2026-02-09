# TF2C-Be-the-Sentry-Buster
A fork of MasterOfTheXP's "Be the Sentry Buster" module from "[Be the Robot](https://forums.alliedmods.net/showthread.php?t=193067)" for use in [TF2 Classified](https://store.steampowered.com/app/3545060/Team_Fortress_2_Classified/).



This was created for the sole purpose of not having to install TF2Items for it to function on my server, lol.



Thirdperson will NOT be enabled when enabling Sentry Buster, (trust me, I tried adding that and it suuucked.) so you will have to enable it manually via sv_cheats or by using [my fork of DarthNinja's Third Person plugin](https://github.com/Lododar/SM-ThirdPerson-Fixed).



# You need Be the Robot installed for this to work!

## Includes

| Include | Description  |
|---------|------------|
|[betherobot.inc](https://forums.alliedmods.net/attachment.php?attachmentid=113505&d=1356209096) | Be the Robot |
|[sdkhooks.inc](https://www.sourcemod.net/new-api/sdkhooks/__raw) | SDKHooks extension include to stop compiler giving errors |
|[sdktools_functions](https://www.sourcemod.net/new-api/sdktools_functions/__raw) | SDKTools functions extensions for player code |

### Commands
| Command | Usage | Description |
|---------|-------|-------------|
| sm_betherobot_buster_announce | 0-3 | Who should hear announcer on Sentry Buster spawn? 0 = No one, 1 = Enemy Team, 2 = Sentry Buster's team, 3 = Both Teams |
| sm_buster / sm_sentrybuster | `<target>`/ `@all`/ `@blue` / `@red`| Enable Sentry Buster |
| sm_bethebuster_admin | `<target>`/ `@all`/ `@blue` / `@red`  | Admin command for enabling Sentry Buster |
