# DIY and Crafts - Static Site

Ready-to-deploy static site for Pinterest blogging. 1 Pinterest account -> 1 site.

## Files
- index.html - homepage, lists Day 1 posts
- posts/thrifted-dresser-flip.html
- posts/hand-embroidery-beginners.html
- posts/beaded-bag-charm-diy.html
- posts/crochet-tote-bag-beginners.html
- posts/diy-christmas-gifts-under-1-hour.html
- style.css
- ../pins-day1.md - Day 1 pin titles, descriptions, keywords

## Deploy - GitHub + Cloudflare
1. Create a GitHub repo, e.g. diy-and-crafts-site
2. Upload the contents of site/ to the repo root
3. In Cloudflare Pages: Create application > Pages > Connect to GitHub > select this repo > Build command: none, Output directory: /
   Or: GitHub Pages: Settings > Pages > Deploy from branch, main, root
4. Add your custom domain in Cloudflare, point DNS to Pages
5. Add HTTPS, it is automatic in Cloudflare Pages

## Pinterest claim
1. Pinterest > Settings > Claimed accounts > Claim website
2. Add the meta tag Pinterest gives you to index.html head, replace the TODO comment
3. Verify, then all pins from this domain will show your profile

## AdSense
1. Add About, Contact, Privacy Policy pages before applying - this template links to them in the footer, create them next
2. Apply in Google AdSense with your domain
3. After approval, paste the AdSense code in index.html head, replace the TODO comment
4. Keep content in US English, Tier 1 focused, no copied text or images

## Next steps
- Add real photos for each post, 1000x1500px vertical for Pinterest, 1200x800px for the post
- Create About, Contact, Privacy Policy pages
- Create 5 pins in Canva, 1000x1500px, link each pin to its post URL
- Boards: Furniture Flips, Embroidery for Beginners, Crochet Patterns, DIY Gifts, Christmas Crafts
