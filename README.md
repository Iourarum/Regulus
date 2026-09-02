## Regulus - Riemannian Embeddings and Graphs Unified for Large-scale, Uncharted Single-cells 

###### <b>Important Note:</b> <i>This is a novel R library under active development, designed for work involving incredibly large omics datasets and profoundly detailed data analysis through advanded mathematical techniques without overlapping with the existing R eco-system, but building upon it. Currently not-released yet and under active development. To find out more about it please keep reading below.</I>

---
![<b>Figure 1.</b> The logo of this project is the bird <i><u>Regulus regulus</u></i>, the goldcrest, Europe's smallest bird — folklore called it "king of the birds" not by its own size but by riding the eagle to the greatest height, hiding in its feathers, and emerging when the Eagle gave out - making it the highest altitude flying bird in a competition that took place a long... long time ago... that only folk tales remain to speak of.](RegulusRegulus.png)

<i>Project <b>Regulus</b></i> respects the <i>folk</i> described in <b><i>Fig. 1</i></b>: it builds <i>no new graphics stack</i>, however it <i>wisely</i> <u>binds together and builds upon</u> the best of the already existing <b>R</b> eco-system <i>wgpu</i>, <i>extendr</i>, <i>htmlwidgets</i>, and <b>R</b>'s existing manifold and kernel packages in order to offer <i>a well-detailed sneak-peek</i> of new heights in <b><i>Omics data-analysis and novel visualizations</i></b> for which <b>R</b> <i>is very much used</i> and <i>very well known - a top Bioinformatician's programming language</i>.

----

### Abstract

In anticipation of <u>future and current</u>, ongoing <i>efforts</i> regarding the building of diverse <i>cell-atlases</i>, the <b><i>Regulus</i></b> project comes to deliver <b><i>novel, 3D-native, fast</i></b> and <b><i>highly optimized</i></b> interactive visualizations for <b>R</b> and <b>Omics-data</b>. 

<b><i>Regulus</i></b> is currently being built built on a <b>Rust</b> <i>wgpu</i> renderer compiled to <b>WebAssembly</b> and shipped as a standard <i>htmlwidget</i>, of <i>high-dimensional spaces</i> specific of omics data, <i>Riemannian</i> clustering, <i>reproducing kernel Hilbert Spaces (RKHS)</i> methods on manifolds, <i>kernel density estimation</i> and <i>differential-geometry techniques</i> - fast and optimized. As previously mentioned, <b><i>Regulus</i></b> is meant to bring about a <u>novel</u>, yet <u>consolidated</u> pipeline of visualizing very large omics datasets in anticipation of the scientific efforts regarding the compilation of <i>cell atlases</i> across different <i>bio-protocols</i>, <i>species</i> and <i>modalities</i>.

Bridging <i>wet-lab science</i> and <i>different bio-protocols</i> with <i>advanced mathematics</i> and <i>data science</i>, we believe there is much left not-analysed enough from placing -omics data <i>solely on a flat plane</i>. Single-cell profiles may occupy curved or even non-Euclidean high-dimensional spaces; cell-cycle phase and RNA-velocity direction are directional data on spheres. With the rise of AI and new and improved hardware developments - new ways of thinking and representing data become more accessible to researchers! As <b>R</b> already has excellent computational infrastructure for this — <i>Riemann</i>, <i>manifold</i>, <i>riemtan</i>, <i>kernlab</i> — and yet, almost no way to help create much needed novel visualizations: existing <b>R</b> visualization is 3D but unscalable (<i>rgl</i>, on WebGL2, which has no compute shaders), scalable but strictly 2D (picker, rscatter), or fast but static (scattermore), we're bringing it to the community through the <b><i>Regulus</i> project</b>.

<b><i><u>This is an active work-in-progress project.</u></i></b>

## License

<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons Licence" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br /><span xmlns:dct="http://purl.org/dc/terms/" property="dct:title">ISC Boilerplate</span> by <a xmlns:cc="http://creativecommons.org/ns#" href="https://github.com/stephlocke" property="cc:attributionName" rel="cc:attributionURL">Stephanie Locke</a> is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.<br />Based on a work at <a xmlns:dct="http://purl.org/dc/terms/" href="https://github.com/RConsortium/isc-proposal" rel="dct:source">https://github.com/RConsortium/isc-proposal</a>.
