<script>
    export let address = 'https://youtu.be/dQw4w9WgXcQ';
    export let tclass = "";
</script>

<a href={address} class="text-sky-500 hover:text-sky-300 {tclass}">
<slot />
</a>