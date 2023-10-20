<!-- This content will not appear in the rendered Markdown -->
<!-- This content will not appear in the rendered Markdown -->
# performance-web

> <details>
>  <summary>Definition of KPIs</summary>
> </details>

<details open>
  <summary>Testing tools (Waterfall, Breakdown, Connection, Latency)</summary>
  <li>Google Chrome DevTools and  [Lighthouse opportunities](https://developer.chrome.com/docs/lighthouse/performance/)</li>
  <li>[gtmetrix.com](https://gtmetrix.com/)</li>
  <li>[webpagetest.org](https://www.webpagetest.org/)</li>
  <li>[dareboost.com](https://www.dareboost.com/fr/compare)'s two page comparison</li>
</details>

<details>
  <summary>Mobile first rendering (media queries set by min-width)</summary>
</details>

<details open>
  <summary>Limit DNS Lookups, HTTP requests and dependencies</summary>
  - remove iframe  
  - JS files loaded only before </body> (closing tag)  
  - images, icons and fonts embedded through data URI scheme (or inline SVG | custom font - icomoon.io)  
</details>

<details>
  <summary>Caching (Content Delivery Network, Merge HTTP...</summary>
</details>

<details>
  <summary>Use compression (JSON Data object, Gzip ⚠️ mitigating BREACH Attack, ...)</summary>
</details>
  
<details open>
  <summary>keep it smart and simple</summary>
  - limit widgets (replace by link or use the src attr tick on $(document).ready...)  
  - limit font families to essential fonts or commonly used  
  - keep the use of JS to a minimum  
  - limit expensive CSS (box-shadow, gradient, border-radius, outline, opacity)  
</details>

<details open>
  <summary>combine all into a single file, use 'Minify | uglify' and optimized Loadings</summary>
  - images combined as sprites (CSS background-position property)  
  - images shrinked and cropped or switched (Color Quantizer, weight budget, most frequent witdhs, '<picture>' element \| CSS resolution '<img srcset'...)
  - JPG progressive format (very large images)  
  - animated GIF to FFmpeg or CSS3 animation  
</details>

...  
