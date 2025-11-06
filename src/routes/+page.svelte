<script lang="ts">
	// Components
	import Summary from "$lib/components/layout/Summary.svelte";
	import Features from "$lib/components/layout/Features.svelte";
	import Testimonials from "$lib/components/layout/Testimonials.svelte";
	import CallToAction from "$lib/components/layout/CallToAction.svelte";
	import AboutTeaser from "$lib/components/layout/AboutTeaser.svelte";
	import LogoScroller from "$lib/components/layout/LogoScroller.svelte";
	import Hero from "$lib/components/layout/hero-sections/Hero.svelte";
</script>

<Hero
	title="Your AI growth assistant for local business"
	subtitle="One simple system that coordinates your tools, handles routine work, and delivers insights through channels you already use."
	imageSrc="/generated/image-editorial-documentary-photograph-of-a-sm.webp"
	centered={false}
/>
<LogoScroller
	label="Trusted by growing local businesses"
	logoUrls={[
		'https://cdn.brandfetch.io/sweetgreen.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/warbyparker.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/bluestonelane.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/purebarre.com/w/400/h/400/logo'
	]}
/>

<Summary
	title="One system that grows your business"
	text="Ocally connects your existing tools—from Square to email to reviews—and handles the routine work automatically. No new dashboards to learn, no technical expertise required.

Small business owners in retail, food, and wellness use Ocally to recover 15+ hours per week while reaching more customers and driving measurable revenue growth."
/>

<Testimonials
	testimonials={[
		{
			name: "Maria Chen",
			position: "Owner",
			company: "Bloom Coffee Roasters",
			quote:
				"Ocally saves me 12 hours every week on marketing and customer follow-ups. I used to spend my evenings responding to reviews and planning campaigns. Now the AI handles it automatically while I focus on what I love—roasting coffee and serving customers.",
			image: "/generated/image-editorial-documentary-portrait-of-a-conf.webp"
		},
		{
			name: "David Patel",
			position: "Owner",
			company: "Riverside Hardware",
			quote:
				"Within two months, Ocally increased our repeat customer visits by 28%. The system automatically sends reminders to customers who haven't visited in a while, bringing back business I would have lost. It's like having a marketing team without the cost.",
			image: "/generated/image-editorial-documentary-portrait-of-a-matu.webp"
		},
		{
			name: "Sophia Martinez",
			position: "Founder",
			company: "Haven Wellness Studio",
			quote:
				"I was drowning in five different apps for payments, reviews, emails, and scheduling. Ocally connected everything into one simple system. Now I get text updates about what's working and what needs attention. No more logging into dashboards or wondering what to do next.",
			image: "/generated/image-editorial-documentary-portrait-of-a-fema.webp"
		}
	]}
/>

<Features
	title="One intelligent system that does it all"
	subtitle="Ocally coordinates your tools, automates routine work, and delivers clear insights through the channels you already use every day."
	features={[
		{
			title: "AI coordination layer",
			description:
				"Our AI agents connect your payment systems, review platforms, and marketing tools automatically. No manual integration work or technical expertise required."
		},
		{
			title: "Works where you already work",
			description:
				"Get insights and updates through SMS, email, and POS alerts—no new dashboard to check or app to learn."
		},
		{
			title: "Automated routine work",
			description:
				"We handle customer follow-ups, review requests, and campaign adjustments in the background while you focus on running your business."
		},
		{
			title: "Plain language insights",
			description:
				"Clear, actionable reports in everyday language. Your campaign reached 130 new customers this week—no complex metrics to decipher."
		},
		{
			title: "Connect existing tools",
			description:
				"Ocally works with Square, Toast, Google, and other platforms you're already using. Keep your current tools, just coordinate them better."
		},
		{
			title: "Success-based pricing",
			description:
				"Our pricing grows with your results, not your team size. We succeed when you succeed—simple, transparent, and aligned with your growth."
		}
	]}
/>
<AboutTeaser />
<CallToAction 
	title="Ready to grow without the overwhelm?"
	subtitle="Join local businesses already saving 15+ hours per week"
	description="Start with a simple conversation. No technical setup, no lengthy onboarding. Just tell us about your business and we'll handle the rest. Your AI growth assistant is ready when you are."
	imageSrc="/generated/image-a-happy-local-business-owner-mid-40s-sta.webp"
	callsToAction={[
		{
			href: "/get-started",
			label: "Get started today",
			variant: "primary"
		},
		{
			href: "/contact",
			label: "Talk to our team",
			variant: "secondary"
		}
	]}
/>
