<div class="flex items-center">
    <!--a rel="prefetch" class="mr-6 font-thin text-gray-500 capitalize lg:text-base high-contrast-grey" href="/about">about</a>
    <a rel="prefetch" class="mr-6 font-thin text-gray-500 capitalize lg:text-base high-contrast-grey" href="/contact">contact</a>
    <a rel="prefetch" class="mr-6 font-thin text-gray-500 uppercase lg:text-base high-contrast-grey" href="/cv">cv</a-->
    <button aria-label="Colour Theme Button" on:click={toggle} class="focus:outline-none focus:border-transparent focus:shadow-none">
        <svg class="h-6 svg sun" viewBox="0 0 246 246" aria-hidden="true">
            <path d="M189.024 122.5c0 36.188-29.336 65.524-65.524 65.524S57.976 158.688 57.976 122.5 87.312 56.976 123.5 56.976s65.524 29.336 65.524 65.524zM122.667 43c4.143 0 7.5-3.357 7.5-7.5v-28c0-4.143-3.357-7.5-7.5-7.5a7.499 7.499 0 00-7.5 7.5v28c0 4.143 3.357 7.5 7.5 7.5zm61.777 25.438a7.478 7.478 0 005.304-2.197l14.849-14.85a7.498 7.498 0 00-.001-10.606 7.5 7.5 0 00-10.606.001l-14.849 14.85a7.498 7.498 0 005.303 12.802zm5.922 109.702a7.5 7.5 0 00-10.607 10.607l14.85 14.85a7.481 7.481 0 005.304 2.196 7.5 7.5 0 005.304-12.803l-14.851-14.85zm-133.113.619l-14.85 14.85a7.5 7.5 0 1010.608 10.607l14.85-14.85a7.5 7.5 0 10-10.608-10.607zm-.619-111.9a7.476 7.476 0 005.304 2.197 7.498 7.498 0 005.304-12.802l-14.849-14.85a7.5 7.5 0 00-10.606-.001 7.498 7.498 0 00-.001 10.606l14.848 14.85zM238.5 114.5h-28a7.499 7.499 0 00-7.5 7.5c0 4.143 3.357 7.5 7.5 7.5h28c4.143 0 7.5-3.357 7.5-7.5s-3.357-7.5-7.5-7.5zM123.667 202a7.499 7.499 0 00-7.5 7.5v29c0 4.143 3.357 7.5 7.5 7.5s7.5-3.357 7.5-7.5v-29c0-4.143-3.357-7.5-7.5-7.5zM44 123c0-4.143-3.357-7.5-7.5-7.5h-29A7.499 7.499 0 000 123c0 4.143 3.357 7.5 7.5 7.5h29c4.143 0 7.5-3.357 7.5-7.5z" fill-rule="nonzero"/>
        </svg>
        <svg class="h-6 svg moon" viewBox="0 0 246 263" aria-hidden="true">
            <g fill-rule="nonzero">
                <!--path d="M176.852 94.36L154 99.21l15.652 17.433L167.178 140l21.322-9.585L209.822 140l-2.474-23.357L223 99.21l-22.852-4.85L188.5 74zM246 188.426l-14.903-3.16L223.5 172l-7.597 13.266-14.903 3.16 10.208 11.357L209.595 215l13.906-6.245L237.408 215l-1.615-15.217z"/-->
                <path d="M117.234 131.5c0-51.54 29.63-96.147 72.766-117.708C172.353 4.97 152.45 0 131.383 0 58.822 0 0 58.874 0 131.5S58.822 263 131.383 263c21.066 0 40.97-4.971 58.617-13.792-43.136-21.561-72.766-66.168-72.766-117.708z"/>
            </g>
        </svg>
    </button>
</div>

<script>
    function toggle() {
        window.document.body.classList.toggle('light-mode')
    }
</script>