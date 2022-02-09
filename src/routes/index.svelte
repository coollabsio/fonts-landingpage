<script context="module">
	export const hydrate = true;
</script>

<script>
	import Subscribe from '$components/Subscribe.svelte';
</script>

<div class="">
	<div class="max-w-7xl mx-auto pt-16 pb-6 px-4 sm:px-6 lg:px-8">
		<div class="text-center flex flex-col justify-center items-center">
			<p class="mt-1 font-extrabold text-white text-5xl  lg:text-6xl text-center gradient">Fonts</p>
			<h2 class="text-2xl md:text-3xl font-extrabold text-white pt-8">
				Privacy-focused <span class="text-sky-500">Google Fonts</span> alternative
			</h2>
		</div>
	</div>
</div>
<div class="bg-coolblack">
	<div class="max-w-7xl mx-auto text-center pt-8 px-4 sm:px-6  lg:pt-8 lg:px-8">
		<div class="text-base font-extrabold tracking-tight text-white pb-4">Change:</div>
		<div class="flex justify-center pb-4">
			<div class="tracking-tight text-white font-mono bg-black px-4 py-2 rounded text-sm">
				fonts.googleapis.com
			</div>
		</div>
		<div class="text-base font-extrabold tracking-tight text-white pb-4">To:</div>
		<div class="flex justify-center pb-4">
			<div class="tracking-tight text-white font-mono bg-black px-4 py-2 rounded text-sm">
				api.fonts.coollabs.io
			</div>
		</div>

		<div class="text-base font-extrabold tracking-tight text-white sm:text-2xl">
			In your <span class="font-bold text-purple-500">head</span> tags. That's all!
		</div>
		<div>
			<a
				href="https://github.com/coollabsio/fonts#how-to-use"
				target="_blank"
				class="tracking-tight text-gray-300 text-xs font-mono hover:underline">(see an example)</a
			>
		</div>
	</div>
</div>
<div class="py-16 pb-20">
	<div class="max-w-7xl sm:mx-10  lg:mx-auto px-4 sm:px-6 lg:px-8">
		<div class="mt-10">
			<div class="space-y-10 lg:space-y-0 mx-auto lg:grid lg:grid-cols-3 lg:gap-8 w-custom">
				<div>
					<div
						class="flex items-center justify-center h-12 w-12 rounded-md bg-green-500 text-white"
					>
						<svg
							class="h-6 w-6"
							xmlns="http://www.w3.org/2000/svg"
							fill="none"
							viewBox="0 0 24 24"
							stroke="currentColor"
						>
							<path
								stroke-linecap="round"
								stroke-linejoin="round"
								stroke-width="2"
								d="M5 12h14M5 12a2 2 0 01-2-2V6a2 2 0 012-2h14a2 2 0 012 2v4a2 2 0 01-2 2M5 12a2 2 0 00-2 2v4a2 2 0 002 2h14a2 2 0 002-2v-4a2 2 0 00-2-2m-2-4h.01M17 16h.01"
							/>
						</svg>
					</div>
					<div class="mt-5">
						<div class="text-lg leading-6 font-extrabold text-white">Hosted on Bare Metal</div>
						<div class="mt-2 text-base text-gray-300">
							The API is hosted on bare metal servers and not on a cloud provider, with <a
								class="font-bold text-green-500 underline"
								href="https://coolify.io"
								target="_blank">Coolify</a
							>.
						</div>
					</div>
				</div>
				<div>
					<div
						class="flex items-center justify-center h-12 w-12 rounded-md bg-yellow-500 text-white"
					>
						<svg
							class="w-6 h-6"
							fill="none"
							stroke="currentColor"
							viewBox="0 0 24 24"
							xmlns="http://www.w3.org/2000/svg"
							><path
								stroke-linecap="round"
								stroke-linejoin="round"
								stroke-width="2"
								d="M13 10V3L4 14h7v7l9-11h-7z"
							/></svg
						>
					</div>
					<div class="mt-5">
						<div class="text-lg leading-6 font-extrabold text-white">Cached by BunnyCDN</div>
						<div class="mt-2 text-base text-gray-300">
							Fonts and API requests cached at <a
								class="text-yellow-500 font-bold underline"
								href="https://bunny.net"
								target="_blank">BunnyCDN</a
							>, with logging turned off completely and it's super fast (as a
							<span class="text-yellow-500 font-bold">bunny</span>)! 🐰
						</div>
					</div>
				</div>

				<div>
					<div
						class="flex items-center justify-center h-12 w-12 rounded-md bg-purple-500 text-white"
					>
						<svg
							xmlns="http://www.w3.org/2000/svg"
							class="h-6 w-6"
							fill="none"
							viewBox="0 0 24 24"
							stroke="currentColor"
						>
							<path
								stroke-linecap="round"
								stroke-linejoin="round"
								stroke-width="2"
								d="M3 15a4 4 0 004 4h9a5 5 0 10-.1-9.999 5.002 5.002 0 10-9.78 2.096A4.001 4.001 0 003 15z"
							/>
						</svg>
					</div>
					<div class="mt-5">
						<div class="text-lg leading-6 font-extrabold text-white">Fully open-sourced</div>
						<div class="mt-2 text-base text-gray-300">
							Yeah, fully. Check out on <a
								class="font-bold underline text-purple-500"
								href="https://github.com/coollabsio/fonts"
								target="_blank">Github</a
							> for more details, like why I built it!
						</div>
					</div>
				</div>
			</div>
		</div>
	</div>
</div>

<div class="text-center pb-4">
	<h2 class="text-xl font-extrabold tracking-tight text-white sm:text-2xl">
		<span class="block"
			><span class="text-blue-500">Follow</span> for updates
			<a href="https://twitter.com/andrasbacsai" target="_blank"
				><span class="sr-only">Twitter</span>
				<svg
					class="inline-block w-12 h-12 text-blue-500"
					fill="currentColor"
					viewBox="0 0 24 24"
					aria-hidden="true"
				>
					<path
						d="M8.29 20.251c7.547 0 11.675-6.253 11.675-11.675 0-.178 0-.355-.012-.53A8.348 8.348 0 0022 5.92a8.19 8.19 0 01-2.357.646 4.118 4.118 0 001.804-2.27 8.224 8.224 0 01-2.605.996 4.107 4.107 0 00-6.993 3.743 11.65 11.65 0 01-8.457-4.287 4.106 4.106 0 001.27 5.477A4.072 4.072 0 012.8 9.713v.052a4.105 4.105 0 003.292 4.022 4.095 4.095 0 01-1.853.07 4.108 4.108 0 003.834 2.85A8.233 8.233 0 012 18.407a11.616 11.616 0 006.29 1.84"
					/>
				</svg></a
			>
			and <span class="text-yellow-400">star</span> it on
			<a
				href="https://github.com/coollabsio/fonts"
				target="_blank"
				class="text-center text-white pt-10 hover:text-gray-300"
			>
				<svg
					class="inline-block h-12 w-12"
					fill="currentColor"
					viewBox="0 0 24 24"
					aria-hidden="true"
				>
					<path
						fill-rule="evenodd"
						d="M12 2C6.477 2 2 6.484 2 12.017c0 4.425 2.865 8.18 6.839 9.504.5.092.682-.217.682-.483 0-.237-.008-.868-.013-1.703-2.782.605-3.369-1.343-3.369-1.343-.454-1.158-1.11-1.466-1.11-1.466-.908-.62.069-.608.069-.608 1.003.07 1.531 1.032 1.531 1.032.892 1.53 2.341 1.088 2.91.832.092-.647.35-1.088.636-1.338-2.22-.253-4.555-1.113-4.555-4.951 0-1.093.39-1.988 1.029-2.688-.103-.253-.446-1.272.098-2.65 0 0 .84-.27 2.75 1.026A9.564 9.564 0 0112 6.844c.85.004 1.705.115 2.504.337 1.909-1.296 2.747-1.027 2.747-1.027.546 1.379.202 2.398.1 2.651.64.7 1.028 1.595 1.028 2.688 0 3.848-2.339 4.695-4.566 4.943.359.309.678.92.678 1.855 0 1.338-.012 2.419-.012 2.747 0 .268.18.58.688.482A10.019 10.019 0 0022 12.017C22 6.484 17.522 2 12 2z"
						clip-rule="evenodd"
					/>
				</svg></a
			></span
		>
	</h2>
	<div class="flex justify-center py-8">
		<a
			href="https://www.producthunt.com/posts/privacy-focused-google-fonts-alternative?utm_source=badge-featured&utm_medium=badge&utm_souce=badge-privacy-focused-google-fonts-alternative"
			target="_blank"
			><img
				src="https://api.producthunt.com/widgets/embed-image/v1/featured.svg?post_id=330902&theme=dark"
				alt="Privacy-focused Google Fonts alternative - Same API, privacy-focused, fast & zero logging. | Product Hunt"
				style="width: 250px; height: 54px;"
				width="250"
				height="54"
			/></a
		>
	</div>
</div>

<Subscribe />
