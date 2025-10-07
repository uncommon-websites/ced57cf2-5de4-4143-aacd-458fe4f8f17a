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
	title="Draft legal documents in seconds, not hours"
	subtitle="AI-powered legal drafting with real-time citation verification that embeds directly into your workflow."
	imageSrc="/generated/image-a-professional-lawyer-exudes-quiet-confi.webp"
	centered={false}
/>
<LogoScroller
	label="Trusted by innovative law firms"
	logoUrls={[
		'https://cdn.brandfetch.io/cooley.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/wsgr.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/orrick.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/lw.com/w/400/h/400/logo'
	]}
/>

<Summary
	generating
	title="What we do"
	text="Our technology delivers measurable results through secure, adaptable solutions that directly increase productivity and drive growth."
/>

<Testimonials
	testimonials={[
		{
			name: "Priya Narayan",
			position: "Managing Partner",
			company: "Narayan & Associates",
			quote:
				"Nomica cut our contract drafting time from 4 hours to 45 minutes. The real-time citation verification eliminated my biggest fear around AI hallucinations, and now my small firm competes with big firms on turnaround time.",
			image: "/generated/image-confident-asian-female-lawyer-in-a-sophi.webp"
		},
		{
			name: "Marcus Washington",
			position: "Solo Practitioner",
			company: "Washington Law Group",
			quote:
				"I was drowning in repetitive NDA work until Nomica. Now I draft NDAs in 20 minutes instead of 2 hours, saving me 15 hours every week. That's $7,500 in recovered billable time monthly, and the citation feature gives me confidence every clause is defensible.",
			image: "/generated/image-professional-black-male-attorney-in-a-pr.webp"
		},
		{
			name: "Elena Rodriguez",
			position: "Partner",
			company: "Rodriguez Legal Services",
			quote:
				"Nomica transformed our 6-attorney firm from constantly behind to consistently ahead of deadlines. We reduced malpractice risk with verified citations on every document, and increased our client capacity by 40% without adding headcount.",
			image: "/generated/image-confident-hispanic-female-lawyer-in-a-st.webp"
		}
	]}
/>

<Features
	title="Built for legal precision"
	subtitle="AI-powered drafting that understands the stakes of your work"
	features={[
		{
			title: "Real-time citation verification",
			description:
				"Every generated clause shows exact source documents, eliminating the fear of AI hallucinations. Draft with confidence knowing each provision is backed by verifiable legal authority."
		},
		{
			title: "Embedded in your workflow",
			description:
				"Works directly within the tools you already use, not as another platform to learn. Nomica integrates seamlessly into your daily practice without disrupting established processes."
		},
		{
			title: "Legal-specific intelligence",
			description:
				"Unlike generic AI tools, Nomica understands jurisdiction-specific requirements, court rules, and compliance standards. Our models are trained exclusively on legal content to ensure accuracy that matters."
		},
		{
			title: "Instant document generation",
			description:
				"Transform hours of drafting into seconds while maintaining your firm's style and precedents. Generate complete contracts, motions, and agreements that require minimal review."
		},
		{
			title: "Contract intelligence",
			description:
				"Analyze agreements in seconds to identify risks, missing clauses, and non-standard terms. Surface critical issues before they become problems."
		},
		{
			title: "Secure by design",
			description:
				"Attorney-client privilege protection with enterprise-grade encryption and zero data retention. Your client information never trains our models or leaves your control."
		}
	]}
/>
<AboutTeaser />
<CallToAction
	title="Start drafting with confidence"
	subtitle="Every clause backed by verifiable sources"
	description="Join the lawyers who've already transformed their practice. See how Nomica eliminates AI hallucination risk while saving 15+ hours per week on contract work. Your first document takes minutes to generate, not hours to draft."
	imageSrc="/generated/image-a-confident-lawyer-elegantly-dressed-in-.webp"
	callsToAction={[
		{
			href: "/get-started",
			label: "Start free trial",
			variant: "primary"
		},
		{
			href: "/contact",
			label: "Book a demo",
			variant: "secondary"
		}
	]}
/>
