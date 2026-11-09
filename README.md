# Awesome-Automated-Cross-Browser-Screenshot-Testing
# Awesome-Automated-Cross-Browser-Screenshot-Testing

I can't create the file, commit, or push—I have no filesystem, no shell, and no Git credentials. Everything I produce is text. You will need to save and push it yourself.



I also have to flag what the search results actually support, because **several entries in your list have no usable pricing**, and one acquisition changes the landscape.



## The data problems



**Screener.io was acquired by Sauce Labs.** Crunchbase confirms the acquisition is complete, with Screener becoming a subsidiary . **Do not list Screener as an independent product.** If you mention it, note it is now part of Sauce Labs.



**Applitools pricing changed dramatically in 2026.** The free Eyes plan **no longer exists**—the Internet Archive shows it on 2025-08-12 but not on 2026-01-31. The lowest tier is **Starter at $667/month paid annually**, with 100,000 component checkpoints or 1,000 page checkpoints . A university benchmark puts Applitools' entry-level package at **$20,000/year** . The "$99–199/month" figure from a Tencent blog is outdated .



**LambdaTest pricing is contradictory across sources.** TestMu AI's own page shows "Live Testing" pricing per parallel session but no clear screenshot tier . A third-party listing shows **Live $15/month**, **Real Device $25/month**, and **Kane CLI Starter $19/month** . **Do not present a single figure as LambdaTest's screenshot testing price**—the product has been rebranded to TestMu AI and the pricing structure is in flux.



**CrossBrowserTesting's only price is $104/month Standard** from GoodFirms , which is a directory listing, not vendor-published. PeerSpot reviews confirm per-minute licensing but no rate .



**BrowserStack's pricing is fragmented.** The pricing page shows **Individual $39/month**, **Single User $150/month**, and **Team $249/month** , but these appear to be for different products (App Live, App Automate) and the screenshot-specific tier is not isolated. **Do not present $39 as the screenshot testing price.**



## What the search results actually contain



**SaaS pricing (usable, with caveats):**



| Platform | Pricing | Caveat |

|---|---|---|

| **Percy (BrowserStack)** | **Free: 5,000 screenshots/month, unlimited users/projects**  | Generous free tier; overages charged |

| **Applitools** | **Starter $667/month annual** (100K component or 1K page checkpoints)  | Free tier removed |

| **Visualping** | Business **$100–300/month** (up to 500 pages, 50K checks, 11 users); **Solutions from $3,000/year**  | Change monitor, not visual regression |

| **Urlbox** | **Hi-Fi $49/mo** (5K renders); **Ultra $99/mo** (15K)  | Screenshot API, not comparison |

| **ApiFlash** | **Free 100/mo**; **Lite $7/mo** (1K); **Medium $35/mo** (10K)  | Screenshot API, not comparison |

| **Stillio** | **$29/month starting**  | Change monitor |

| **CrossBrowserTesting** | **$104/month Standard**  | Directory listing, not vendor-published |

| **LambdaTest** | **Live $15/mo, Real Device $25/mo**  | Third-party listing; product rebranded |



**Open-source projects (usable):**



| Project | Stars | What it actually does |

|---|---|---|

| **BackstopJS** | **6,328**  | Visual regression with Puppeteer/Chromium; JSON config; reference/test screenshot paths; mismatch threshold; CI report  |

| **gooddata-neobackstop** | Not surfaced | Go-based visual regression tool with BackstopJS-compatible config; Chromium/Firefox support; hover/click/keyPress interactions  |



**BackstopJS is the only significant open-source project surfaced** . It is Chromium-only (via Puppeteer), which is a real limitation for cross-browser testing . The university benchmark notes BackstopJS is **faster than cloud tools** but cannot run browsers simultaneously . **gooddata-neobackstop** adds Firefox support but has no star count surfaced .



## What I recommend



**Remove Screener.io**—acquired by Sauce Labs .



**Split into three honest categories:**



**1. Visual Regression Platforms** (proprietary): Percy (free 5K screenshots) , Applitools ($667/month Starter) , BrowserStack, CrossBrowserTesting ($104/month directory) , LambdaTest/TestMu AI (pricing in flux) .



**2. Screenshot APIs** (proprietary): Urlbox (Hi-Fi $49/mo) , ApiFlash (Free 100/mo) .



**3. Website Change Monitors** (proprietary): Visualping (Business $100–300/mo) , Stillio ($29/mo) .



**The open-source section has one strong entry: BackstopJS (6,328 stars)** . It is Chromium-only, which is a limitation for true cross-browser testing . State that clearly.



**Flag the pricing model differences explicitly:** per-screenshot (Percy, Applitools), per-render (Urlbox, ApiFlash), per-page/check (Visualping), and per-minute (CrossBrowserTesting) produce incomparable costs at the same testing volume.



If you paste your current `README.md` and confirm you want this framing, I will produce the complete file as text for you to save. I will not list Screener as independent, cite Applitools' removed free tier, or present LambdaTest's contradictory third-party pricing as vendor-confirmed.
