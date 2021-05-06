This document explains the data that's collected by each of my extensions, and how it's used.

# Snippets

[Snippets][] requires a GitHub personal access token. The token is used to authenticate with GitHub when loading or saving. Snippets also requires a GitHub Gist ID. Snippets requests a personal access token and Gist ID when you install it.

Your personal access token is stored in Chrome's sync storage. Code you write with Snippets is stored as a GitHub Gist. See [Chrome's Privacy Policy][chrome privacy] and [GitHub's Privacy Policy][github privacy].

A personal access token is required for Snippets to work. However, if you would like to remove your personal access token, open the Snippets editor, navigate to the settings (gear icon in the bottom left), and delete the value in the "Github Access Token" input. You may be prompted for a new personal access token.

The code you save with Snippets can always be accessed through [GitHub Gists][gists], without using the Snippets extension.

# Git Reveal

[Git Reveal][] transmits some URLs to Google DNS and GitHub to determine if the URL is a GitHub Pages site. URLs are only checked in specific situations, to minimize requests to Google and GitHub. URLs are stored in local storage to remember the result. See the [Google DNS Privacy Policy][gdns privacy] and [GitHub's Privacy Policy][github privacy].

# GitHub 404 Breakdown

[GitHub 404 Breakdown][] tries to determine why GitHub returned a 404, by transmiting each part of the URL to GitHub. Github 404 Breakdown never stores any data, and never transmits data besides URLs that are being checked by GitHub. See [GitHub's Privacy Policy][github privacy].

# Back To Search

[Back To Search][] uses your browser history to find the most recent Google Search. Back to Search stores history in memory and never transmits data outside of your computer.

[snippets]: https://chrome.google.com/webstore/detail/snippets/fakjeijchchmicjllnabpdkclfkpbiag
[git reveal]: https://chrome.google.com/webstore/detail/git-reveal/momcopneegabfanhfajaoofjbjcdldek
[github 404 breakdown]: https://chrome.google.com/webstore/detail/github-404-breakdown/pnhdlhabpckpibnkkddmgcimdejbljge
[back to search]: https://chrome.google.com/webstore/detail/back-to-search/ciipoifnpngckoghfgicbfdchchbgjlo
[gdns privacy]: https://developers.google.com/speed/public-dns/privacy
[chrome privacy]: https://www.google.com/chrome/privacy/#signed-in-chrome-mode
[github privacy]: https://docs.github.com/en/github/site-policy/github-privacy-statement
[gists]: https://gist.github.com/
