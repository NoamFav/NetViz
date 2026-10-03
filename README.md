<div align="center">
<picture>
  <source media="(prefers-color-scheme: dark)" srcset=".github/brand/banner-night.svg">
  <img alt="NetViz: Rust + WebGL network visualization engine (planned). Currently a two-file scaffold — no rendering or packet ingestion implemented yet." src=".github/brand/banner-paper.svg" width="100%">
</picture>
<br><br>
<a href="#what-its-meant-to-be"><picture><source media="(prefers-color-scheme: dark)" srcset=".github/brand/tab-what-its-meant-to-be-night.svg"><img alt="what it's meant to be" src=".github/brand/tab-what-its-meant-to-be-paper.svg"></picture></a>
<a href="#status"><picture><source media="(prefers-color-scheme: dark)" srcset=".github/brand/tab-status-night.svg"><img alt="status" src=".github/brand/tab-status-paper.svg"></picture></a>
</div>

<p>
<a name="what-its-meant-to-be"></a>
<picture><source media="(prefers-color-scheme: dark)" srcset=".github/brand/section-what-its-meant-to-be-night.svg"><img alt="what it's meant to be" src=".github/brand/section-what-its-meant-to-be-paper.svg" width="100%"></picture>
</p>

A base network-visualization engine — real-time packet ingestion rendered as a live graph in WebGL, with a plugin API for extensions.

> Note: this is a separate, unrelated experiment from [Setka](https://github.com/NoamFav/Setka), which also touches network visualization but is a different (and further along) Go project.

<p>
<a name="status"></a>
<picture><source media="(prefers-color-scheme: dark)" srcset=".github/brand/section-status-night.svg"><img alt="status" src=".github/brand/section-status-paper.svg" width="100%"></picture>
</p>

| | Today | Planned |
|---|-------|---------|
| `main.rs` | Prints `"NetViz engine starting..."` and exits | Engine bootstrap, packet ingestion loop |
| `renderer.rs` | Empty placeholder | WebGL-based graph renderer, plugin API |

> [!NOTE]
> No rendering or packet ingestion exists yet — this is a two-file scaffold, not a working tool.

```sh
git clone https://github.com/NoamFav/NetViz && cd NetViz
cargo run
```

<div align="center">
Made with ♥ by <a href="https://github.com/NoamFav">NoamFav</a>
</div>

<br>

<a href="https://nf-software.com">
<picture>
  <source media="(prefers-color-scheme: dark)" srcset=".github/brand/footer-night.svg">
  <img alt="NF Software" src=".github/brand/footer-paper.svg" width="100%">
</picture>
</a>
