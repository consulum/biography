<script>
	import Banner from "../components/banner.svelte";
	import Card from "../components/card.svelte";
</script>

<Banner />
<div id="profile-content" class="page-content full-width">
    <div id="content-root" class="content-root">
        <Card 
            card_type={"user"} 
            profile_url={"https://media.tenor.com/pVcJvsYHAmsAAAAC/discord-meme.gif"} 
            username={"consulum"} 
            user_quote={"silly little guy"}
            message={"come over here and kiss me on my hot mouth"}
            image_url={"https://media.discordapp.net/attachments/827687195929477161/1043759406187294800/observer.gif"}
            custom_role={"full-stack web dev"}
            github_url={"https://github.com/consulum"}
            discord_url={"https://discord.com/users/978278299560198174"}
            telegram_url={null}>
        </Card>
        <Card
            card_type={"user"}
            profile_url={"https://cdn.discordapp.com/avatars/773960165195776050/a_8b0c4fd10c2a190643a0922d58656423.gif?size=1024&width=0&height=256"}
            username={"crackerbites"}
            user_quote={"lorem ipsum dolor"}
            message={"lorem ipsum dolor sit amet"}
            image_url={"https://cdn.discordapp.com/avatars/773960165195776050/a_8b0c4fd10c2a190643a0922d58656423.gif?size=1024&width=0&height=256"}
            custom_role={"lorem ipsum dolor"}
            github_url={null}
            discord_url={null}
            telegram_url={null}>
        </Card>
        <Card
            card_type={"user"}
            profile_url={"https://cdn.discordapp.com/attachments/1158003181331173397/1160574049861247079/d186c3d12ac98391b5d7eb4a8e4dab2e.png"}
            username={"retpild"}
            user_quote={"penguin overlord"}
            message={"penguins are sexy"}
            image_url={"https://cdn.discordapp.com/attachments/1158003181331173397/1160577218175586304/Screenshot_2023-08-08-10-33-14-958_com.png"}
            custom_role={"sex"}
            github_url={null}
            discord_url={"https://discord.com/users/776851561815998484"}
            telegram_url={null}>
        </Card>
        <Card
            card_type={"user"}
            profile_url={"https://cdn.discordapp.com/avatars/1001591723035725975/a_0caedb2b2db7a0ac1ddd25cc250476b7.gif?size=1024&width=0&height=256"}
            username={"rofl dofl"}
            user_quote={"agency of rofl"}
            message={"join the rofl agency today"}
            image_url={"https://cdn.discordapp.com/banners/1001591723035725975/a_c357f121e4df7283b53cc751ed4e8c9d.gif?size=1024&width=0&height=256"}
            custom_role={"#1 agency shareholder"}
            github_url={"https://github.com/roflmaybe"}
            discord_url={null}
            telegram_url={null}>
        </Card>
        <Card
            card_type={"user"}
            profile_url={"https://cdn.discordapp.com/avatars/440599126401613865/af48187c7816f4ddb965d94f7ac8a872.webp?size=1024&width=0&height=256"}
            username={"zumo"}
            user_quote={"the zumo of zumos"}
            message={"meow meow meow meow meow meow meow"}
            image_url={"https://cdn.discordapp.com/banners/440599126401613865/4d3cd6870454f991dac3088c4f2da360.webp?size=1024&width=0&height=256"}
            custom_role={"very cool person"}
            github_url={null}
            discord_url={"<https://discord.com/users/440599126401613865>"}
            telegram_url={null}>
        </Card>
    </div>
    <h3 id="copyright-text" class="cr-disclaimer">copyright (c) 2023 consulum</h3>
</div>