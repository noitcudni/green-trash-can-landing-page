---
date: "2021-07-14"
title: "Bulk URL Removal for Google Search Console, Now 100× Faster"
image: "images/blog/overclocked-fire-tv-speed-guage.jpg"
author: "Lih Chen"
draft: false
---
I’ve been maintaining this project since 2013. Over the years, countless edge cases and bugs have been resolved, and many UI/UX improvements have been introduced. Through it all, the core mission has remained the same: automate tedious tasks and give you back time to focus on what matters most.

Today, I’m excited to share an update that takes that mission even further. With this release, you can now remove up to 1,000 URLs in roughly 10 minutes in one session. What once took hours is now a true set-and-forget process. There’s no need to babysit the workflow or periodically check that everything is running smoothly—just click submit, grab a coffee, and come back to a completed task.

The workflow itself remains unchanged. You start by preparing a CSV file containing the URLs you want removed and submit it to the extension. The extension performs the initial removal through Google Search Console’s UI. After that, you’ll no longer see visible UI activity in Search Console, but the progress bar will continue to update in real time. Once all URLs have been submitted for removal, a confirmation alert will appear. After clicking OK, the page will automatically refresh, and you’ll see that all URLs have been successfully submitted.

In the interest of full transparency, there is a small caveat. Because the removal process no longer runs entirely through Google Search Console’s UI, error messages may not always be precise and can be misleading. For now, all errors are reported as duplicate request errors.

If you’ve ever had to remove URLs fast, this update is built for you

> With this release, you can now remove up to 1,000 URLs in roughly 10 minutes in one session
>
> <cite></cite>
