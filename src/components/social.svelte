<script>
    export let thumb_url;
    export let redir_url;
</script>

<button id="user-social" class="social-button" onclick="window.location.href = '{redir_url}';">
    <div id="social-image" class="social-image image-defaults" style="background-image: url('{thumb_url}')"></div>
</button>