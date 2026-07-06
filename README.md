<div align="center">

<img src="https://capsule-render.vercel.app/api?type=venom&height=200&color=gradient&customColorList=12&text=NETVIZ&fontSize=90&fontColor=fff&animation=twinkling&desc=A+Network+Visualization+Engine%2C+Not+Yet+Visualizing&descSize=15&descAlignY=65&stroke=FFFFFF&strokeWidth=1" alt="NetViz Banner" />

<img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=18&pause=1000&color=00D9FF&center=true&width=900&height=50&lines=Rust+%2B+WebGL+(planned)+%C2%B7+%E2%9A%A0%EF%B8%8F+scaffold+stage" alt="Typing SVG" />

<br>

[![Rust](https://img.shields.io/badge/Rust-CE422B?style=for-the-badge&logo=rust&logoColor=white&labelColor=0D1117)](https://www.rust-lang.org)
[![Status](https://img.shields.io/badge/Status-Scaffold-FF4444?style=for-the-badge&labelColor=0D1117)](#status)

</div>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

### What it's meant to be
A base network-visualization engine — real-time packet ingestion rendered as a live graph in WebGL, with a plugin API for extensions.

> Note: this is a separate, unrelated experiment from [Setka](https://github.com/NoamFav/Setka), which also touches network visualization but is a different (and further along) Go project.

### Status: today vs. planned

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

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

<div align="center">
Made with ♥ by <a href="https://github.com/NoamFav">NoamFav</a>
<img src="https://capsule-render.vercel.app/api?type=waving&height=90&color=gradient&customColorList=12&section=footer" />
</div>
