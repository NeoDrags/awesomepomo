<script>
	import Footer from "../components/Footer.svelte"
</script>

<main class="bg-[#1A2238]">
	<h1 class="text-center pt-12 font-black text-5xl pl-4.8">An all inclusive pomodoro package
		<img class= "max-h-[420px] block ml-auto mr-auto" src="../../static/working.png" alt="none">
	</h1>
	<button class="p-[14px 28px] h-[40px] w-[120px] font-white-sans-extrabold-center text-[16px] ml-[45%] 
	bg-[#7c3aed] border-none rounded-[8px] no-underline">Get started</button>
	<div class="flex items-center">
		<p class="font-bold text-4xl pl-8">
			Our app is meant to help you utilise your time effectively with the help of a pomodoro timer and 
			a todo list which will help you plan out your day and make your work better.
		</p>
		<img class="max-h-[420px] pl-60" src="../../static/rocket.png" alt="none">
	</div>
	<Footer/>
</main>