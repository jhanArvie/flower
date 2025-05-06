
## Instructions for AI Implementation for editing index.html ------------------------->
Task: Modify index.html and associated assets to reflect the company profile accurately. Follow these instructions precisely:

Company Profile Integration:
  - Replace all placeholder text, images, and metadata in index.html with the provided company information follow through instructions.
  - Ensure branding consistency (e.g., company name, slogan, colors, and tone).
  - Update headings, paragraphs, and contact details to match the company’s services/products.

File Structure & Assets:
  - Replace all images in /assets (e.g., logos, banners, icons) with the company’s official assets.
  - Rename image files logically (e.g., company-logo.png, product-showcase.jpg).
  - Update all href and src attributes in index.html to point to the correct new asset paths.

Metadata & SEO:
  - Update <title>, <meta> descriptions, and OpenGraph tags to reflect the company’s keywords and branding.

Styling (if applicable):
  - Adjust CSS (inline or linked) to align with the company’s color scheme (hex codes/fonts provided).

  Validation:
  - Ensure no broken links or missing assets after updates.
  - Maintain responsive design and accessibility (alt text for images, ARIA labels).


# Company Profile Template --------------------------->
## contstant informations------------>
## Basic Information
- **Business Name**: [Your Business Name]
- **Business Type**: [e.g., Café, Restaurant, Retail Store, etc.]
- **Tagline**: [Your Business Tagline]
- **Establishment Date**: [Year Founded]

## Contact Information
- **Address**: [Full Business Address]
- **Phone**: [Primary Contact Number]
- **Email**: [Business Email]
- **Operating Hours**:
  - Monday-Friday: [e.g., 7:00 AM - 8:00 PM]
  - Saturday-Sunday: [e.g., 8:00 AM - 9:00 PM]
  - Holidays: [Special Hours if any]

## Social Media
- **Facebook**: [URL]
- **Instagram**: [URL]
- **Twitter**: [URL]
- **LinkedIn**: [URL]
- **TikTok**: [URL]



## Changable informations------------>
## Brand Identity
- **Primary Color**:     [HEX Code] or [Check the logo font color] or [if not provided use the default]
- **Secondary Color**:   [HEX Code] or [if not provided use the default]
- **Accent Color**:      [HEX Code] or [if not provided use the default]
- **Fonts**:
  - Heading Font:        [Font Name] or [check the font of the logo] or [If not provided, use the default]
  - Body Font:           [Font Name] or [If not provided, use the default]
- **Logo**: [first check assets/logo/{logo.(png|jpg|jpeg|gif|svg|webp)}. If there is no file, use the business name as logo]

## Business Description
[{2-3 sentences describing your business, its mission, and unique value proposition}] + [if not provided, generate something that is very related to the business] then [improve it to be more engaging and interesting]

## Key Features/Services
1. [Main Feature/Service 1]
2. [Main Feature/Service 2]
3. [Main Feature/Service 3]
4. [Add more as needed]


## Menu/Products Section
- **Categories**:
  1. [Category 1]
  2. [Category 2]
  3. [Add more as needed]



## Change all the Image src and alt dinamically
- Hero Section: [`assets/hero/{best fit image for the container.png/jpg/jpeg/gif/svg/webp}`] or [if none use the default]
- About Section: [`assets/about/{best fit image for the container.png/jpg/jpeg/gif/svg/webp}`] or [if none use the default]
- Gallery: [`assets/gallery/{best fit image for the container.png/jpg/jpeg/gif/svg/webp}`] or [if none use the default]
- Menu-Service Section: [`assets/menu-service/{best fit image for the container.png/jpg/jpeg/gif/svg/webp}`]   or [if none use the default]
- Customer-Feedback Section: [`assets/customer-feedback/{best fit image for the container.png/jpg/jpeg/gif/svg/webp}`] or [if none use the default]
- Contact Section: [`assets/contact/{best fit image for the container.png/jpg/jpeg/gif/svg/webp}`] or [if none use the default]
- Testimonials Section: [see assets/testimonials/{images related to the testimonials.(png|jpg|jpeg|gif|svg|webp)}] or [if none use the default]


## Testimonials if section provided
- testimonial 1: add image from assets/testimonials/{images related to the testimonials.(png|jpg|jpeg|gif|svg|webp)} or [if none use the default]
- testimonial 2: add image from assets/testimonials/{images related to the testimonials.(png|jpg|jpeg|gif|svg|webp)} or [if none use the default]
- testimonial 3: add image from assets/testimonials/{images related to the testimonials.(png|jpg|jpeg|gif|svg|webp)} or [if none use the default]


## Mobile Navigation (Burger Menu)
- **Animation Style**: [Slide]
 **Menu Icon Style**: [Classic Three Lines]
- **Menu Type**: [Choose one]
  - [ ] Slide from Left
  - [ ] Slide from Right
  - [ ] Slide from Top
  - [ ] Slide from Bottom
  - [ ] Fade In Center
  - [ ] Full Screen Overlay