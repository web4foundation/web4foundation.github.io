<br /><br /><br /><br />
<img src="https://brand.web4.dev/web4/header/light.svg">
<br /><br /><br /><br />

```html
<!-- MyButton.html -->

<script lang="C#">
    // 🚨🚨🚨 ⬆︎ HTML support for ANY language! 🚨🚨🚨
    void OnClick(Event e)
    {
        c++;
    }
</script>

<button onclick={e => OnClick(e)}>
    Clicks:  {c}
    <!--🚨🚨🚨 ⬆︎ HTML support for reactivity – no framework! 🚨🚨🚨-->
</button>

<!--
  Compile your HTML
    • to a native binary for multiplayer-reactivity + zero-cost dependencies  (mutates the DOM from a WebSocket)
    • to a WASM binary for offline-reactivity + static hosting                (mutates the DOM from WebAssembly)
-->
```

About
-----

The Web4 Foundation is a nonprofit organization dedicated to the advancement of the open web through its fourth chapter: local-first, native webapps. The foundation is currently being organized as a 501(c)(6). Formal status is in progress.  Similar to organizations like W3C and WHATWG, the Web4 Foundation also stewards, defines, and extends the standards of the open web. However, since Web4 executes extramurally instead of inside the browser, its scope of influence is not targeted towards browser vendors but rather towards language communities. Web4’s directive is to support the consistent implementation of these standards across all language communities to maximize skill-portability and minimize framework-fatigue.

Why Web4?
---------

The story of the web is written in chapters not generations.  Generations replace what came before.  Chapters contribute to a single, holistic story.  Web1 was not replaced by Web2 and the intentions of Web3 was never to supplant the database.  Each new chapter coincides with the emergence of a new computing paradigm and its unique combination of constraints and superpowers that it unlocks.  From these new first principles, yesterday’s best practices become the new anti-patterns and a new species proliferates across the web.

| Chapter | Computing Paradigm | What it Enabled | Execution Location | Categories Unlocked |
|---|---|---|---|---|
| Web1 | Personal Computing | Static documents | Server-side | Long-form content<br /><sub>academic papers, news, blogs, marketing sites, etc</sub> |
| Web2 | Cloud Computing | Dynamic webpages | Client-side | Short-form content<br /><sub>e-commerce, social media, etc</sub> |
| Web3 | Decentralized Computing | Smart contracts | Peer-to-peer | Transactional content<br /><sub>DeFi, digital ownership, etc</sub> |
| Web4 | Edge Computing | Local-first apps | Edge-side / WASM | Function over content<br /><sub>utilities, games, collaborative, productivity, etc</sub> |

Infrastructure for Edge Computing has reached an interesting tipping point recently where, thanks to geo-various datacenter build-outs, long-haul fiber installations, and even 5G rollouts, ubiquitous low latency has been achieved globally.  In a world where it’s possible to roundtrip to an edge server with lower latency than your screen’s own refresh rate, suddenly it makes sense to move a whole class of workloads off the client.  The architecture of these new edge-native opportunities are neither server-side, nor client-side, they are middle-out and must be local-first.

### A New Species: Local-First Apps (LFA)

Local-first applications (LFA) emphasize function over content.  Typical categories include utilities, games, collaborative software, and productivity tools (categories far more prevalent in native app stores).  In this species, the concept of a “page” is eliminated entirely and URLs are used, not as locations of resources, but as bookmarks for state.  Local-first apps (LFA) differ from single-page apps (SPA) in a few fundamental areas:

|  | Single-page apps (SPA) | Local-first apps (LFA) |
|---:|---|---|
| Artifacts | Scripts | Binaries |
| State | Client-side | Extramural |
| Protocol | Request/response | Bidirectional |

### Core Benefits

- **Language Choice**<br />
  Web4 ends JavaScript’s monopoly on building dynamic user interfaces on the web.
- **Multiplayer Reactivity**<br />
  When application state lives on the server, multiple connected clients can react to the same state change.
- **Offline Reactivity**<br />
  Bidirectional protocols enable local-first synchronizations and apps continue to function even without a network connection.
- **Zero-Cost Dependencies**<br />
  When applications execute remotely, binaries can grow to gigabytes in size without impacting user experience because they are never transferred to the browser.
