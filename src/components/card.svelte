<script>
	import Social from "./social.svelte";

    export let card_type;
    export let profile_url;
    export let username;
    export let user_quote;
    export let message;
    export let image_url;
    export let custom_role;
    export let github_url;
    export let discord_url;
    export let telegram_url;
</script>

{#if card_type === "user"}
    <div id="content-card" class="page-card">
        <div id="profile-avatar" class="profile-icon image-defaults" style="background-image: url('{profile_url}')" />
        <h2 id="profile-user" class="profile-user">{username}</h2>
        <h3 id="profile-quote" class="profile-quote">{user_quote}</h3>
        <div id="profile-divider" class="profile-divider" />
        <div id="message-container" class="personal-message">
            <h2 id="message-title" class="message-title">message from {username}</h2>
            <h3 id="message-text" class="message-text">{message}</h3>
        </div>
        <div id="custom-image" class="personal-image image-defaults" style="background-image: url('{image_url}')" />
        <h3 id="user-role" class="custom-role">{custom_role}</h3>
        <div id="socials-divider" class="socials-divider" />
        <div id="socials-container" class="socials-container">
            {#if github_url !== null}
                <Social thumb_url={"https://cdn.discordapp.com/attachments/1158525284790837319/1160561892931153930/github.png"} redir_url={github_url} />
            {/if}
            {#if discord_url !== null}
                <Social thumb_url={"https://cdn.discordapp.com/attachments/1158525284790837319/1160566806562480298/discord-mark-white.png"} redir_url={discord_url} />
            {/if}
            {#if telegram_url !== null}
                <Social thumb_url={"https://cdn.discordapp.com/attachments/1158525284790837319/1160570260190146581/telegram_2.png"} redir_url={telegram_url} />
            {/if}
        </div>
    </div>
{:else if card_type === "carousel"}
    <div id="content-card" class="page-card">
        <!-- TODO: implement carousel element -->
    </div>
{/if}