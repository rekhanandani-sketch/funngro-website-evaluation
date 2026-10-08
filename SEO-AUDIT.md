# Funngro Website SEO Audit

**Audit date:** 9 October 2026  
**Scope:** Publicly visible content on [funngro.com](https://www.funngro.com/), the requested `/teen` route, and the linked [For Brands page](https://www.funngro.com/for-brands). This is a limited review of pages observed in a browser, not a crawl, source-code audit, or performance lab test.

## Summary

The observed pages address two clear audiences: young people exploring brand projects and companies looking to work with young people. The homepage presents the youth journey, while `/for-brands` presents company-facing campaign formats and a contact path. The requested `/teen` URL redirected to `/earn` during this review. Search-oriented copy is prominent on the youth page; a focused metadata, technical, or Core Web Vitals assessment could not be established from the rendered-page observations alone.

## Observations and recommendations

### Technical SEO and indexability

- **Observed:** The browser loaded the homepage, `/earn` and `/for-brands`; the requested `/teen` URL resolved to `/earn` during inspection.
- **Not verified:** HTTP response headers, redirect status codes, canonical tags, robots directives, XML sitemap availability, robots.txt contents, structured data, crawl directives, and index status. These require source, response, or search-index inspection.
- **Recommendation:** Confirm that the redirect is intentional, ensure each intended audience page has a stable crawlable URL, and review canonicalization, indexability, sitemap, and structured data directly against the deployed HTML and responses.

### Titles and meta descriptions

- **Observed:** The homepage browser title was “Earn Money Online with India's Biggest Brands | Funngro”. The `/earn` title was “Earn Money Online Through Online Jobs & Remote Work”. The `/for-brands` title was “Brand Promotion & Influencer Campaigns in India | Funngro”.
- **Not verified:** Meta description, Open Graph and social metadata, canonical values, and title markup in the source were not established in this rendered-page review.
- **Recommendation:** Check the source for a unique, accurate description and social metadata on every indexable page. Keep titles descriptive, audience-specific, and consistent with visible page content.

### Headings and content quality

- **Observed:** The homepage presented one prominent H1 about flexible remote opportunities and multiple sections about brands, campaign types, how the platform works, and FAQs. The `/for-brands` page presented a clear H1 about working with young Indians, followed by campaign-format sections including promotion, sampling, referrals, influencer marketing, content, surveys, app testing, ideation, sales support, loyalty, campus ambassadors, and partnerships.
- **Observed:** The youth-facing copy describes projects and a flow from joining and choosing a campaign to completing work and submitting it for review. The brand page includes a campaign inquiry path.
- **Recommendation:** Preserve the audience-specific information architecture and make sure headings describe each section accurately. Review promotional claims and figures against current, publishable evidence before relying on them as SEO copy.

### Internal links

- **Observed:** The homepage navigation includes a “For brands” link to `/for-brands`; the brand page includes a “Home” breadcrumb and links to other site destinations, including contact.
- **Recommendation:** Provide a clear, crawlable link between the primary youth and company experiences. Check that navigation, breadcrumbs, campaign information, and contact destinations remain consistent across devices.

### Images and alternative text

- **Observed:** The rendered homepage included named app and campaign imagery; a Shark Tank India pitch image was also present further down the page. The brand page content observed in this review primarily communicates through text and campaign sections.
- **Not verified:** Whether all meaningful images have suitable source-level `alt` text, decorative images are correctly ignored by assistive technology, image files are appropriately sized, or image loading is optimized.
- **Recommendation:** Audit each image in the page source. Provide concise contextual alt text for informative images, empty alt text for decorative imagery, and appropriately sized modern image formats.

### Performance and mobile experience

- **Not verified:** No network waterfall, Lighthouse report, Core Web Vitals, real-user data, or systematic viewport/responsive test of the original site was collected for this audit.
- **Recommendation:** Measure representative mobile and desktop URLs using field data where available and a repeatable lab test. Inspect image transfer sizes, font loading, render-blocking resources, layout shifts, and responsive overflow before prioritizing performance work.

### Accessibility

- **Observed:** The rendered pages exposed navigation labels, headings, link names, and image names in the browser’s accessibility snapshot. This does not establish complete WCAG conformance.
- **Not verified:** Keyboard operation, focus visibility, contrast ratios, screen-reader behavior, heading order across the full source, form labeling, and reduced-motion behavior.
- **Recommendation:** Test the pages with keyboard-only navigation and a screen reader; measure text and control contrast; verify semantic landmarks, heading order, descriptive links, image alternatives, and accessible behavior at narrow viewports.

## Priority recommendations

1. Confirm the intended `/teen` URL behavior and maintain a clear route for the youth experience.
2. Verify each live page’s title, description, canonical, robots, social metadata, and sitemap entries from deployed source and HTTP responses.
3. Validate visible performance and mobile behavior using measured data rather than assumptions.
4. Review image alternatives and interactive elements with assistive technology and keyboard-only checks.
5. Keep campaign claims, statistics, and audience descriptions accurate and supported by current information.
