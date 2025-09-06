# OSRS Chat Filter Regex

A community-maintained collection of **regular expressions** designed to filter out spam, scams, advertisements, and other unwanted messages from the Old School RuneScape (OSRS) chat box.  
This project is primarily intended for use with the **RuneLite** client plugin **Chat Filter**, but may be useful in other contexts where OSRS chat moderation is needed.

---

## Features

- Blocks **gold selling & swapping ads**
- Filters **account sales and services** (questing, skilling, inferno capes, etc.)
- Detects **gambling spam** (dice, 55x2, flower poker, casino ads)
- Removes **phishing & impersonation attempts** (fake Jagex mod messages, support scams)
- Catches **autotyper spam** and Unicode/emoji floods
- Continuously updated via **community contributions**

---

## Installation (Manual Updates)

1. Open your RuneLite client.
2. Enable the **Chat Filter** plugin.
3. Download the [`osrs_regex_chat_filter.txt`](./osrs_regex_chat_filter.txt) file from this repository.
4. In the Chat Filter plugin settings:
   - Check **Use Regular Expressions**.
   - Import or copy/paste the regex list into the filter configuration.
5. Save, and enjoy a cleaner chat box.

## Installation (Automatic Updates)

1. Open your RuneLite client.
2. Download and enable the **Chat Filter Updater** plugin.
3. Copy the regex file URL: [`osrs_regex_chat_filter.txt`](./osrs_regex_chat_filter.txt)
4. In the Chat Filter plugin settings:
   - Paste the URL into the **Filter URL** field.
5. Click Back, and enjoy a cleaner chat box.

---

## Contributing

We welcome community contributions!  

- Found a spam message slipping through?  
- Notice a false positive blocking legitimate chat?  

Open an **Issue** with:
- The exact message (screenshot or text sample).
- Suggested regex (if you have one).

Or submit a **Pull Request** directly with changes to `osrs_regex_chat_filter.txt`.

Please ensure new expressions:
- Do not unintentionally block common, legitimate OSRS chat.
- Are written efficiently (avoid catastrophic backtracking).
- Do not duplicate existing patterns.

---

## Disclaimer

- This project is **not affiliated with Jagex, RuneScape, or RuneLite**.  
- Filters are provided **as-is**, with no guarantee they will catch all spam or avoid all false positives.  
- Use at your own discretion.

---

## License

This project is licensed under the **MIT License**.  
See [LICENSE](./LICENSE) for details.
