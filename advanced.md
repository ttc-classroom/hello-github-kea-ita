# Hello GitHub

<img width="100" align="left" alt="image" src="https://user-images.githubusercontent.com/155492/219313640-1328aefb-7695-41d2-bbef-5c5ffe6ab079.png">

# Exercise 3 - Advanced

### Manage Your Profile Readme

Have a look at [this GitHub Doc](https://docs.github.com/en/account-and-profile/setting-up-and-managing-your-github-profile/customizing-your-profile/managing-your-profile-readme "You can add a README to your GitHub profile to tell other people about yourself"). It's an instruction to how you can add a profile excerpt to your GitHub profile, which will automatically show, when people browse to your handle.

1. Read the description on the link above
2. Create a repo which has the same name as your handle, make it public and and a `README.md` file <br/><details><summary>Like this (Spoiler!)</summary><img width="726" alt="image" src="https://github.com/kea-dev/hello-github/assets/155492/87dafb8c-70db-459d-b174-2bc4ef9e3f5b">
</details>

3. Start by copying the content from the file you just created in teh previosu exercise, and paste it into the `README.md` file, in the repo that has the name of your handle.

**Hints:**

👉 Try to hover over the link above (_hover_ = hold your cursor still over the link, but don't click it). See the link description that emerges? Where did that come from? [^1]

[^1]: You can do amazing stuf in MarkDown - GitHub uses it's own variant _GitHub Flavored MarkDown_ [The basics](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax "Create sophisticated formatting for your prose and code on GitHub with simple syntax") are really simple, but the full capabilities of the syntax are [quite advanced](https://github.github.com/gfm/ "GitHub Flavored Markdown Spec"). At the core is [KramDown](https://kramdown.gettalong.org/syntax.html "fast, pure-Ruby Markdown-superset converter") - the most common MarkDown implementation - KramDown supports [Footnotes](https://kramdown.gettalong.org/syntax.html#footnotes)! There you have it! - Confused yet?

👉 Did you see the foot note above! 

👉 Noticed how links in `.md` files on GitHub _always_ opens in the same (current) tab - The GitHub Flavored MarkDown syntax doesn't support to spec a link to be opened in a new window or tab (KramDown does!). But no problem! Hold down `<CTRL>` on Windows or `<CMD>` on Mac while you click the link, and it opens in a new tab.

<img width="100" align="left" alt="image" src="https://user-images.githubusercontent.com/155492/219313640-1328aefb-7695-41d2-bbef-5c5ffe6ab079.png">

# Exercise? 4 - Did You know?

### One standard to rule them all ...and in darkness bind them!

MarkDown is supported in all GitHub documentation:

- `.md` files
- Issue descriptions and comments
- Discussions
- Annotated reviews
- Wiki pages
- GitHub pages (static web sites)

Both Chat GPT and Bing Chat supports generating output in MarkDown.
- Ask Chat GPT _anything_ and append _"... and by the way, please type the output in MarkDown"_ to your prompt. Then copy the output from the chat into a new `.md` file her in this repo. It appears that anything you get from prompt engineering can be pasted directly into your GitHub documentation, discussions or chats.
