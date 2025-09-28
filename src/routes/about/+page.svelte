<script lang="ts">
	// Components
	import CallToAction from "$lib/components/layout/CallToAction.svelte";

	// Icons
	import StakeholderGrid from "$lib/components/layout/StakeholderGrid.svelte";
	import Story from "./Story.svelte";
	import SecondaryHero from "$lib/components/layout/hero-sections/SecondaryHero.svelte";
	import Culture from "$lib/components/layout/Culture.svelte";

	// Constants
	const values = [
		{
			title: "Precision",
			description: "Every line of code and legal precedent is meticulously crafted to ensure accuracy in document drafting."
		},
		{
			title: "Efficiency",
			description: "We help lawyers focus on high-value legal strategy instead of repetitive document creation."
		},
		{
			title: "Excellence",
			description: "Combining deep legal domain expertise with cutting-edge AI technology to deliver superior results."
		}
	];
</script>

<SecondaryHero
	title="Transforming legal document drafting"
	subtitle="with AI-powered precision"
	imageSrc="https://www.unc.mn/image-placeholder.svg"
/>

<!-- Story Section -->
<Story
	paragraphs={[
		"We recognized that legal professionals spend 60% of their billable hours on repetitive document creation instead of high-value legal strategy. This inefficiency costs the industry billions while limiting lawyers' potential to serve more clients.",
		"Our mission is to transform legal document drafting by combining AI code completion with comprehensive legal precedent databases. We deliver instant document generation that maintains legal accuracy and precedent compliance.",
		"Starting with solo practitioners and small law firms, we're building tools that enable 30% more billable hours through faster, more efficient document creation. Every feature we develop focuses on reducing administrative burden while enhancing legal precision.",
		"We believe technology should amplify legal expertise, not replace it. By automating routine drafting tasks, we free legal professionals to focus on strategic counsel and client relationships where they create the most value."
	]}
/>

<!-- Our Culture Section -->
<Culture {values} />

<!-- Team and Investors sections removed - no founder information available -->

<!-- CTA Section -->
<CallToAction
	title="Ready to transform your practice?"
	subtitle="Draft documents 3x faster"
	description="Join the legal professionals already using Cursor to handle more clients by spending less time on repetitive document creation and more time on high-value legal strategy."
	imageSrc="/generated/image-a-professional-lawyer-seated-at-a-desk-i.webp"
/>
