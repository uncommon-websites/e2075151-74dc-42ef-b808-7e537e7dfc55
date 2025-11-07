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
	title="Turn your Twitter header into passive income"
	subtitle="Join the marketplace connecting creators with advertisers. Set your price, approve every ad, and start earning from your header space."
	imageSrc="/generated/image-a-content-creator-celebrating-a-subtle-w.webp"
	centered={false}
	callsToAction={[
		{
			href: "/contact",
			label: "Join the waitlist"
		},
		{
			href: "/about",
			label: "Learn how it works"
		}
	]}
/>
<LogoScroller
	label="Trusted by leading creator brands"
	logoUrls={[
		'https://cdn.brandfetch.io/shopify.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/convertkit.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/notion.so/w/400/h/400/logo',
		'https://cdn.brandfetch.io/beehiiv.com/w/400/h/400/logo'
	]}
/>

<Summary
	title="How it works"
	text="RentMyHeader connects Twitter creators with advertisers through a simple marketplace for header space. You set your rates, approve every campaign, and earn passive income while brands reach your engaged audience. It's the easiest way to monetize your Twitter presence without creating extra content."
/>

<Testimonials
	testimonials={[
		{
			name: "Marcus Chen",
			position: "Tech Creator",
			company: "42K followers",
			quote:
				"I was leaving money on the table every single day. Within my first week, I made $600 from header space I wasn't even using. Zero time investment after the 5-minute setup.",
			image: "/generated/image-documentary-style-professional-headshot-.webp"
		},
		{
			name: "Elena Rodriguez",
			position: "Growth Marketer",
			company: "SaaS Startup",
			quote:
				"We spent $2,500 testing influencer campaigns on other platforms with mixed results. RentMyHeader gave us direct access to engaged audiences for a fraction of the cost and we saw conversions within 48 hours.",
			image: "/generated/image-documentary-style-professional-headshot-.webp"
		},
		{
			name: "Amit Patel",
			position: "Finance Creator",
			company: "28K followers",
			quote:
				"The approval system means I never worry about brand safety. I've rejected three ads that didn't fit my audience, and the ones I approved generated $1,200 last month while I focused on content.",
			image: "/generated/image-documentary-style-professional-headshot-.webp"
		}
	]}
/>

<Features
	title="Everything you need to monetize your header"
	subtitle="Complete control over your earning potential with tools designed for creators who value their brand"
	features={[
		{
			title: "Set your own price",
			description:
				"Control your earnings with flexible daily, weekly, or monthly rates that reflect your audience value."
		},
		{
			title: "Approve every ad",
			description:
				"Review and approve every advertisement before it goes live on your profile with one-click controls."
		},
		{
			title: "Get paid securely",
			description:
				"Receive automatic payouts through Stripe with our money-back guarantee and 24/7 support."
		},
		{
			title: "Brand safety first",
			description:
				"All advertisements are pre-screened to protect your reputation and maintain audience trust."
		},
		{
			title: "One-click control",
			description:
				"Pause or disable advertising instantly without losing your account status or earnings history."
		},
		{
			title: "Live preview system",
			description:
				"See exactly how ads will appear on your header with real-time preview before approval."
		}
	]}
/>
<AboutTeaser />
<CallToAction
	title="Join the exclusive creator network"
	subtitle="Limited spots available"
	description="Get early access to RentMyHeader and start earning from your header space before the public launch. You keep full control, approve every ad, and set your own rates. Join 250M+ followers already in our marketplace."
	imageSrc="/generated/image-a-happy-content-creator-mid-20s-sits-at-.webp"
	callsToAction={[
		{
			href: "/contact",
			label: "Join the waitlist",
			variant: "primary"
		},
		{
			href: "/about",
			label: "Learn more",
			variant: "secondary"
		}
	]}
/>
