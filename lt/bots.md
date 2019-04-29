<!-- TITLE: [LT] Bot'ai -->
<!-- SUBTITLE: Informacija apie įvairias Discord bot'ų bibliotekas -->
* *Šis straipsnis yra apie Discord bot'us. Jei nori skaityti straipsnį apie pačio The Discord Wiki bot'ą, pažiūrėk [WikiBot](/wikibot).*

Discord leidžia nariams kurti Bot'us ir juos pakviesti į serverius. Discord leidžia nariams kurti programas, kurios sąveikauja su API. API dokumentaciją gali rasti [čia](https://discordapp.com/developers/docs/intro).
Bendruomenės valdomą, bet oficialų Discord API serverį gali rasti [čia](http://discord.gg/discord-api).

# Paprasti Bot'ai
Paprasti Bot'ai turi *tam skirtas* bot'ų paskyras, kurios yra sukūriamos per kūrėjų svetainę. Bot'ų paskyros turi kitokias funkcijas ir kitokius draudimus negu paprastos paskyros. Kad pakviestum bot'ą į savo serverį, tau reikia turėti **Tvarkyti serverį** leidimo, ir turi autorizuoti jį naudojant specialią autorizavimo nuorodą, kuri yra specialiai sukurta bot'ui. Kad pakviestum bot'ą; nuspausk ant autorizavimo nuorodos, pasirink serverį, atimk arba suteik bot'ui leidimus, nurodytus puslapyje ir nuspausk 'Authorize'. Kad pašalintum bot'ą iš serverio, tiesiog išmesk arba užblokuok jį kaip tai darytum ir su paprastu nariu. Iš naujo pakviečiant bot'ą, jeigu jis yra užblokuotas iš serverio, atblokuos jį. Bot'ų paskyros turi Bot'o žymę šalia savo vardo, kad atskirtum jį nuo paprasto nario. Jeigu norėtum susikurti savo paties bot'ą, tau tai daryti reikės per Discord programėlių svetainę. Šią svetainę rasi [čia](https://discordapp.com/developers/applications/me).

# Selfbot'ai
Selfbots'ai - tai, kai narys naudoja Discord API, kas automatizuotų savo paskyrą. Selfbot'as veikia tiesiogiai naudojant tavo paskyrą ir naudojant tavo nario žymę (token), kad automatizuotų paskyrą. Selfbot'ai pažeidžia Discord API [OAuth](https://discordapp.com/developers/docs/topics/oauth2#bot-vs-user-accounts) politiką ir tai gali privesti prie paskyros terminacijos. Kitaip negu Userbot'ai, selfbot'ai atsako tik į komandas, kurias išsiuntė narys, kurio paskyra veikia Selfbot'as. **Niekam neduok savo nario žymės (Token). Jei kas nors gaus tavo nario žymę, jie galės padaryti didelę žalą tavo paskyrai, taip pat galės skaityti žinutes, siųsti žinutes ir sugriauti serverius, kuriuose turi leidimų.**
# Userbot'ai
Userbot'ai yra pilnai veikiantys bot'ai, kurie veikia naudojant paprastą paskyrą. Tai pažeidžia Discord [Naudojimosi Sąlygas](https://discordapp.com/terms). Kaip ir kiti Naudojimosi Sąlygų pažeidimai, tu gali apie Userbot'us pranešti Discord Pasitikėjimo ir Saugumo komandai per [support@discordapp.com.](mailto:support@discordapp.com).

# Bibliotekos
Nariai sukūrė daug skirtingų bibliotekų, kurie paverčia naudojimąsi Discord API lengvesniu.
* [Discord.io](https://github.com/izy521/discord.io)
* [Discord.js](https://github.com/hydrabolt/discord.js)
* [Discord.net](https://github.com/RogueException/Discord.Net)
* [Disco](https://github.com/b1naryth1ef/disco)
* [Discord.py](https://github.com/Rapptz/discord.py)
* [Discord-rs](https://github.com/SpaceManiac/discord-rs)
* [Discord4J](https://github.com/austinv11/Discord4J)
* [Discordcr](https://github.com/meew0/discordcr)
* [Discordia](https://github.com/SinisterRectus/Discordia) *Not to be confused with https://discordia.me*
* [Discordie](https://github.com/qeled/discordie)
* [DiscordGo](https://github.com/bwmarrin/discordgo)
* [Discordrb](https://github.com/meew0/discordrb)
* [DSharpPlus](https://github.com/NaamloosDT/DSharpPlus)
* [Eris](https://github.com/abalabahaha/eris)
* [Javacord](https://github.com/BtoBastian/Javacord)
* [JDA](https://github.com/DV8FromTheWorld/JDA)
* [Nostrum](https://github.com/Kraigie/nostrum)
* [Restcord](https://github.com/restcord/restcord)
* [Serenity](https://github.com/zeyla/serenity)
* [SwiftDiscord](https://github.com/nuclearace/SwiftDiscord)
* [Sword](https://github.com/Azoy/Sword)

### Discord Kuruojamos Bibliotekos

Discord turi [sąrašą kuruojamų bibliotekų](https://discordapp.com/developers/docs/topics/community-resources#libraries) "kurie atitinka [Discord'o] APIs standartus pagal autentifikavimą ir pertraukas tarp užklausų."