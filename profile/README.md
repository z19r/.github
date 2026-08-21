```
███████     ██     █████   ██████
     ██   ████    ██   ██  ██   ██
   ██       ██     ██████  ██████
  ██        ██         ██  ██  ██
███████   ██████   █████   ██   ██
```

**SOFTWARE CONSULTANCY — CHICAGO, ILLINOIS**<br>
Rails for the money. Go and Rust for the terminal. Postgres for everything.

[z19r.com](https://z19r.com) · [zack@z19r.com](mailto:zack@z19r.com)

---

### <samp>01 — WHAT THIS IS</samp>

z19r is a shop run by [@zackkitzmiller](https://github.com/zackkitzmiller). The paid work is Rails applications, AWS infrastructure, and the kind of Postgres and Sidekiq problems that show up at 2am with a Sentry link attached.

This org is the other half — tools that got built because the alternative was tolerating something annoying. Most are a single binary. Most are MIT. All of them started as a bad afternoon.

---

### <samp>02 — TERMINAL</samp>

| tool | what it does | in |
|---|---|---|
| [`tihole`](https://github.com/z19r/tihole) | Pi-hole, in a TUI, without the browser tab | Go |
| [`smbark`](https://github.com/z19r/smbark) | Mount, unmount, and stop guessing at SMB shares | Go |
| [`whoseportisitanyway`](https://github.com/z19r/whoseportisitanyway) | What is running on that port, and why | Rust |
| [`spindle`](https://github.com/z19r/spindle) | File organizer that reads the file, not the extension | Rust |
| [`stress-raiser`](https://github.com/z19r/stress-raiser) | Local HTTP load testing with no YAML in sight | Rust |
| [`initium`](https://github.com/z19r/initium) | Config and dotfile scaffolding in one command (née zackstrap) | Rust |

### <samp>03 — AGENT TOOLING</samp>

| tool | what it does | in |
|---|---|---|
| [`whetstone`](https://github.com/z19r/whetstone) | Optimization and caching for Claude Code — sharpens the loop | Rust |
| [`claude-marketplace`](https://github.com/z19r/claude-marketplace) | The plugins and skills that survived daily use | Python |

### <samp>04 — SMALL THINGS</samp>

| tool | what it does | in |
|---|---|---|
| [`waybar-unixtime`](https://github.com/z19r/waybar-unixtime) | Unix time in your Waybar, themed to match omarchy | Hyprland |
| [`gha-guestbook`](https://github.com/z19r/gha-guestbook) | A guestbook powered by GitHub Issues. Yes, really | Action |

---

### <samp>05 — ON THE WEB</samp>

Products ship under the same name. Full index at [z19r.com](https://z19r.com).

| product | what it is |
|---|---|
| [**markbin**](https://markbin.net) | Paste markdown. Get a link. That's the whole pitch |
| **XbutforY** | The editorial "X, but for Y" product directory |
| **Le Combo** | Cross-chain fast food, ordered like a tasting menu |
| **The Pile** | Wealth drawn to scale, until you stop scrolling |
| [**Flourish or Forfeit**](https://flourishorforfeit.com) | Stake real money on your habits. Skip a day, lose it |
| **Patchwork** | Sentry error in, reviewed pull request out |

---

### <samp>06 — HOUSE STYLE</samp>

The stack is deliberately boring, because boring is what you can debug on a Sunday.

- **Rails 8, Postgres, Sidekiq.** Solid Queue and Solid Cache where they fit, Redis where they don't.
- **Minitest and `rubocop-rails-omakase`.** Framework defaults are a feature. Configuration is a liability.
- **Hotwire before React.** A JSON API earns its existence or it doesn't get built.
- **Kamal or Render, Sentry on day one.** Observability is not a phase two.
- **Go or Rust** when the right answer is a static binary somebody else can run.
- **Model first, service object never** — until the model actually gets fat, and then only reluctantly.

Agentic work runs the same way: tight loops, one commit per iteration, a progress file that outlives the session, and a human reading every diff.

---

### <samp>07 — AVAILABLE FOR WORK</samp>

Hourly contract. Fractional principal engineer, Rails rescue, or the specific problem nobody on the team wants to own.

**Rails** application work and long-overdue upgrades · **AWS** on ECS/Fargate, Aurora, Terraform · **Postgres** query and index surgery · **Sidekiq** queues that stopped behaving · **Incidents**, and the postmortem after.

→ [webmaster@z19r.com](mailto:webmaster@z19r.com)

---

<details>
<summary><samp>PRIOR ART — the archive</samp></summary>

<br>

Older work, under [@zackkitzmiller](https://github.com/zackkitzmiller). Left standing on purpose.

| | |
|---|---|
| [`tiny-php`](https://github.com/zackkitzmiller/tiny-php) | Reversible base62 ID obfuscation |
| [`holmes`](https://github.com/zackkitzmiller/holmes) | Mobile detection, back when that was a problem |
| [`nil`](https://github.com/zackkitzmiller/nil) | Null object pattern for PHP |
| [`statsd-arduino`](https://github.com/zackkitzmiller/statsd-arduino) | StatsD client for Arduino |
| [`tree-weaver`](https://github.com/zackkitzmiller/tree-weaver) | ASCII tree → nested file paths, in Erlang |

`zackstrap` grew up and moved out. It's [`initium`](https://github.com/z19r/initium) now.

</details>

---

<samp>NO FRAMES. NO FOLD. STILL MADE IN CHICAGO.</samp>
