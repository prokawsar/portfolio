<script>
	import Capsule from '$lib/components/Capsule.svelte'
</script>

<div class="fixed sm:relative flex flex-col items-center w-full p-4 md:p-10 md:mx-20">
	<p class="animate-bounce hidden lg:flex font-roboto font-light text-black dark:text-slate-400">
		Right-click to open menu
	</p>
	<p class="lg:hidden dark:text-slate-400 animate-bounce">Tap anywhere to open menu</p>
	<div class="flex flex-col lg:flex-row gap-2 md:gap-5 w-full">
		<div class="flex flex-col justify-center gap-2 w-full">
			<h1 class="text-6xl text-black dark:text-slate-100">Hi, <br /> I am Kawsar Ahmed</h1>
			<h2 class="text-[26px] sm:text-3xl dark:text-slate-100 flex items-center gap-3">
				Software Engineer | Frontend
				<span class="outline outline-blue-500 px-5 py-1 rounded-full text-sm font-semibold"
					>Available to hire</span
				>
			</h2>
			<p class="text-gray-600 dark:text-gray-300 text-justify">
				I'm delighted to have you here! As a dedicated Software Engineer specializing in frontend
				development, my focus revolves around crafting top-notch web applications in any tech yet
				specially with React, Next.js, Svelte, SvelteKit. I take pride in writing clean and
				optimized code, ensuring that your applications perform at their best.
			</p>
			<div class="flex flex-row gap-1 mt-5 flex-wrap">
				<Capsule text="React" />
				<Capsule text="Next.js" />
				<Capsule text="Svelte" />
				<Capsule text="SvelteKit" />
				<Capsule text="JavaScript" />
				<Capsule text="TypeScript" />
				<Capsule text="Tailwind" />
				<Capsule text="Nodejs" />
				<Capsule text="PostgreSQL" />
				<Capsule text="Rest API" />
			</div>
			<div class="flex flex-row gap-2">
				<Capsule text="Git" bg="bg-gray-300" textColor="!text-gray-600 dark:!text-gray-400" />
				<Capsule text="Docker" bg="bg-gray-300" textColor="!text-gray-600 dark:!text-gray-400" />
				<Capsule text="Learner" bg="bg-gray-300" textColor="!text-gray-600 dark:!text-gray-400" />
			</div>
		</div>
		<div class="lg:flex lg:justify-center w-full hidden relative bg-hero-bg bg-no-repeat bg-cover">
			<img
				class="left-2 md:left-0 scale-75 sm:scale-75 lg:scale-100"
				src="/images/avatar.png"
				alt="avatar"
			/>
		</div>

		<div class="flex w-full relative lg:hidden">
			<svg class="" viewBox="0 0 200 200" xmlns="http://www.w3.org/2000/svg">
				<path
					fill="#D0E2FF"
					d="M47,-71.7C61.7,-63.6,75.2,-52,81.2,-37.5C87.2,-23,85.7,-5.4,82,10.9C78.2,27.1,72.1,42.2,62.5,55.4C53,68.6,39.9,79.9,24.8,84.2C9.8,88.4,-7.3,85.6,-23.9,80.9C-40.5,76.2,-56.7,69.7,-68.7,58.2C-80.7,46.7,-88.5,30.3,-91.4,12.9C-94.3,-4.5,-92.3,-22.9,-84,-37.2C-75.7,-51.5,-61,-61.8,-46,-69.9C-30.9,-77.9,-15.5,-83.7,0.3,-84.2C16.1,-84.6,32.2,-79.9,47,-71.7Z"
					transform="translate(100 100)"
				/>
			</svg>

			<img
				class="absolute left-2 md:left-0 md:top-18 scale-75 object-cover"
				src="/images/avatar.png"
				alt="avatar"
				height="100%"
				width="100%"
			/>
		</div>
	</div>
</div>
