# My Portfolio Site

## Reflection

Making a portfolio is hard — not because it’s coding, not because it’s making a website, but rather making a website that reflects you, in a way. For this reason, I chose to add a trio-theme. Not only does it display the skills I wish for people to see, but it also truly tells a story about me.

In a way, it shows how one person, or one site, can have many faces — can be multidimensional. While working on this project, I started using Tailwind differently. Rather than using long trailing class names for each element, I used Tailwind utilities to create macro classes for my elements, keeping the HTML much cleaner than usual.

It was also incredibly fun to try out different themes and vibes. Originally, *poppy* was going to be a theme with all colors very multicolor and, well… poppy. Instead, I kept it cohesive and thematic — not to hold back on the identity of the site and how it reflects me, but rather for a better UX. In a way, it now reflects my personality better.

## AI Usage

AI is actually pretty good at generating SVGs for websites. I had asked ChatGPT to generate me a very pop, colorful website banner SVG full of colorful round shapes with no white space.

```html
<svg width="100%" height="100%" viewBox="0 0 1200 800" xmlns="http://www.w3.org/2000/svg" preserveAspectRatio="xMidYMid slice">
  <defs>
    <filter id="softShadow" x="-20%" y="-20%" width="140%" height="140%" color-interpolation-filters="sRGB">
      <feDropShadow dx="0" dy="8" stdDeviation="12" flood-color="#000000" flood-opacity="0.15"/>
    </filter>
  </defs>

  <rect width="1200" height="800" fill="#E0F2FE"/>

  <rect x="-100" y="-50" width="600" height="500" rx="100" ry="100" fill="#4F46E5" filter="url(#softShadow)" opacity="0.95"/>
  <rect x="200" y="-100" width="700" height="600" rx="120" ry="120" fill="#10B981" filter="url(#softShadow)" opacity="0.9"/>
  <rect x="500" y="0" width="800" height="500" rx="100" ry="100" fill="#3B82F6" filter="url(#softShadow)" opacity="0.85"/>
  <rect x="650" y="150" width="700" height="600" rx="110" ry="110" fill="#EF4444" filter="url(#softShadow)" opacity="0.8"/>
  <rect x="0" y="400" width="600" height="500" rx="90" ry="90" fill="#2563EB" filter="url(#softShadow)" opacity="0.85"/>
  <rect x="400" y="500" width="700" height="500" rx="100" ry="100" fill="#22C55E" filter="url(#softShadow)" opacity="0.8"/>

  <circle cx="200" cy="600" r="250" fill="#8B5CF6" filter="url(#softShadow)" opacity="0.85"/>
  <circle cx="600" cy="650" r="300" fill="#22D3EE" filter="url(#softShadow)" opacity="0.8"/>
  <circle cx="950" cy="600" r="220" fill="#F59E0B" filter="url(#softShadow)" opacity="0.85"/>
  <circle cx="1050" cy="350" r="180" fill="#F472B6" filter="url(#softShadow)" opacity="0.8"/>
</svg>
```

https://github.com/JoshuaDesrosiers/portfolio/blob/main/public/shapes.svg

This was going to be the original image for the poppy theme, with a light blue nav, but it didn’t cook as much as I wanted to eat — so I switched it up. I then went for a monochrome vibe.

`make it a monochrome black and white cool one`

```html 
Here’s a clean, cool monochrome black & white remix of your SVG — same layered, soft, modern vibe, just stripped down to grayscale elegance. Think glossy magazine background, but behaving itself 😌

<svg width="100%" height="100%" viewBox="0 0 1200 800" xmlns="http://www.w3.org/2000/svg" preserveAspectRatio="xMidYMid slice">
  <defs>
    <filter id="softShadow" x="-20%" y="-20%" width="140%" height="140%" color-interpolation-filters="sRGB">
      <feDropShadow dx="0" dy="10" stdDeviation="18" flood-color="#000000" flood-opacity="0.25"/>
    </filter>
  </defs>

  <!-- background -->
  <rect width="1200" height="800" fill="#F5F5F5"/>

  <!-- layered rounded rectangles -->
  <rect x="-100" y="-50" width="600" height="500" rx="100" ry="100" fill="#111111" filter="url(#softShadow)" opacity="0.9"/>
  <rect x="200" y="-100" width="700" height="600" rx="120" ry="120" fill="#2A2A2A" filter="url(#softShadow)" opacity="0.85"/>
  <rect x="500" y="0" width="800" height="500" rx="100" ry="100" fill="#3A3A3A" filter="url(#softShadow)" opacity="0.8"/>
  <rect x="650" y="150" width="700" height="600" rx="110" ry="110" fill="#1C1C1C" filter="url(#softShadow)" opacity="0.75"/>
  <rect x="0" y="400" width="600" height="500" rx="90" ry="90" fill="#333333" filter="url(#softShadow)" opacity="0.8"/>
  <rect x="400" y="500" width="700" height="500" rx="100" ry="100" fill="#0F0F0F" filter="url(#softShadow)" opacity="0.7"/>

  <!-- circles -->
  <circle cx="200" cy="600" r="250" fill="#1A1A1A" filter="url(#softShadow)" opacity="0.8"/>
  <circle cx="600" cy="650" r="300" fill="#2F2F2F" filter="url(#softShadow)" opacity="0.75"/>
  <circle cx="950" cy="600" r="220" fill="#444444" filter="url(#softShadow)" opacity="0.8"/>
  <circle cx="1050" cy="350" r="180" fill="#5A5A5A" filter="url(#softShadow)" opacity="0.75"/>
</svg>


```

I started making it monochrome, but I realized midway… this isn’t me. I’m cooler than this. So I wrote:

`give some outlines using a "tailwind blue" outline or undertone keep it dark just add subtle accents how you want`

I shouldn’t have said “how you want” — it didn’t add accents enough. So to get the final one, I simply wrote:

`you didnt add it enough`

Thats how i got the final image for the poppy section, did something similar for the devvy section as well!
