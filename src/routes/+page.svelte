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
	title="Draft legal documents 10x faster with AI precision"
	subtitle="Transform your practice with instant legal document drafting that combines AI code completion with comprehensive legal precedent databases. Spend 30% more time on high-value legal strategy, not repetitive document creation."
	imageSrc="/generated/image-a-professional-lawyer-sits-confidently-a.webp"
	centered={false}
	callsToAction={[
		{
			href: "#contact",
			label: "Start your free trial"
		},
		{
			href: "#features",
			label: "See how it works"
		}
	]}
/>
<LogoScroller 
	label="Trusted by legal professionals"
	logoUrls={[
		'https://cdn.brandfetch.io/skadden.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/kirkland.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/cooley.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/goodwinlaw.com/w/400/h/400/logo'
	]}
/>

<Summary
	generating
	title="What we do"
	text="Our technology delivers measurable results through secure, adaptable solutions that directly increase productivity and drive growth."
/>

<Testimonials
	generating
	testimonials={[
		{
			name: "Jane Smith",
			position: "CTO",
			company: "Tech Innovations",
			quote:
				"Their cutting-edge automation boosted our productivity by 35%.\nThe intuitive interface reduced training time and improved team adoption.",
			image: "https://www.unc.mn/image-placeholder.svg"
		},
		{
			name: "John Doe",
			position: "Director of Operations",
			company: "Global Solutions",
			quote:
				"Their robust security protocols gave us confidence in handling sensitive data.\nThe 24/7 support team resolved issues within hours, not days.",
			image: "https://www.unc.mn/image-placeholder.svg"
		},
		{
			name: "Sarah Johnson",
			position: "Product Manager",
			company: "Future Systems",
			quote:
				"The scalable platform grew seamlessly with our business needs.\nTheir customization options allowed us to tailor solutions perfectly to our workflows.",
			image: "https://www.unc.mn/image-placeholder.svg"
		}
	]}
/>

<Features
	generating
	title="Features"
	subtitle="Some features"
	features={[
		{
			title: "Streamlined Workflows",
			description:
				"Automate repetitive tasks and connect systems to improve productivity with our industry-leading 87% time savings."
		},
		{
			title: "Data Analysis",
			description:
				"Extract meaningful insights from your data with powerful analytical tools backed by proprietary AI algorithms that are 3x more accurate than competitors."
		},
		{
			title: "Secure Collaboration",
			description:
				"Work together seamlessly while maintaining strict data privacy standards with our zero-knowledge architecture and military-grade encryption."
		}
	]}
/>
<AboutTeaser />
<CallToAction 
	title="Stop losing billable hours to document drafting"
	subtitle="Join 5,000+ legal professionals saving 30% more time"
	description="While you're manually drafting contracts, your competitors are handling 30% more clients with AI-powered document creation. Transform repetitive legal writing into strategic advantage and reclaim your time for high-value legal work that builds your practice."
	imageSrc="/generated/image-a-confident-lawyer-standing-in-a-bright-.webp"
	callsToAction={[
		{
			href: "#contact",
			label: "Start free trial today",
			variant: "primary"
		},
		{
			href: "#features", 
			label: "See live demo",
			variant: "secondary"
		}
	]}
/>
