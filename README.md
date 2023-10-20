<!-- This content will not appear in the rendered Markdown -->
<!-- This content will not appear in the rendered Markdown -->
# performance-web

> ➤ Definition of KPIs  
/➤ Testing tools (Waterfall, Breakdown, Connection, Latency)  
- Google Chrome DevTools and  [Lighthouse opportunities](https://developer.chrome.com/docs/lighthouse/performance/)  
- [gtmetrix.com](https://gtmetrix.com/)  
- [webpagetest.org](https://www.webpagetest.org/)  
- [dareboost.com](https://www.dareboost.com/fr/compare)'s two page comparison##
/➤ Mobile first rendering (media queries set by min-width)  
/➤ Limit DNS Lookups, HTTP requests and dependencies  
- remove iframe  
- JS files loaded only before </body> (closing tag)  
- images, icons and fonts embedded through data URI scheme (or inline SVG | custom font - icomoon.io)  
\➤ Caching (Content Delivery Network, Merge HTTP...  
\➤ Use compression (JSON Data object, Gzip ⚠️ mitigating BREACH Attack, ...)  
\➤ keep it smart and simple  
- limit widgets (replace by link or use the src attr tick on $(document).ready...)  
- limit font families to essential fonts or commonly used  
- keep the use of JS to a minimum  
- limit expensive CSS (box-shadow, gradient, border-radius, outline, opacity)  
\➤ combine all into a single file, use Minify | uglify and optimized Loadings  
- images combined as sprites (CSS background-position property)  
- images shrinked and cropped or switched (Color Quantizer, weight budget, most frequent witdhs, <picture> element | CSS resolution <img srcset...)  
- JPG progressive format (very large images)  
- animated GIF to FFmpeg or CSS3 animation  
...  
