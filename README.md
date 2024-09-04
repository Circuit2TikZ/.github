# Circuit2TikZ: a GUI for CircuiTikZ



The [Circuit2Ti*k*Z](https://github.com/Circuit2TikZ) project is based on [CircuiTi*k*Z](https://github.com/circuitikz) (which was partially maintained at the [institute of electronics engineering](https://www.lte.tf.fau.de)) and aims to provide several productivity applications to simplify and speed up the design flow of drawing circuits with CircuiTi*k*Z. These applications make it easier to create circuit drawings, suitable for use in LaTeX and TeX based environments.

The project was started at the Institute for Electronics Engineering (LTE) of Friedrich-Alexander-Universität Erlangen-Nürnberg

[CircuiTi*k*Z-Designer](https://circuit2tikz.tf.fau.de/designer)
----------------------------------------------------------------

CircuiTi*k*Z-Designer is a browser-based progressive web application that serves as a GUI for CircuiTi*k*Z. This JavaScript-based, multi-platform browser application can draw circuits, supporting most CircuiTi*k*Z components and rectangular wire connections. The project consists of two parts: the [GUI](https://github.com/Circuit2TikZ/CircuiTikZ-Designer) itself and the [SymbolConvert Tool](https://github.com/Circuit2TikZ/SymbolConvert), allowing the addition and update of components to the GUI when CircuiTi*k*Z introduces changes. Check the GUI out on [GitHub](https://github.com/Circuit2TikZ/CircuiTikZ-Designer) for feature requests and bug reports.

[![](https://circuit2tikz.tf.fau.de/images/designer.png)](https://circuit2tikz.tf.fau.de/designer) <!-- CircuiTi*k*Z-Designer -->

[![](https://circuit2tikz.tf.fau.de/images/designer_code.png)](https://circuit2tikz.tf.fau.de/designer) <!-- CircuiTi*k*Z code -->

[abl2TikZ](https://github.com/Circuit2TikZ/abl2tikz)
----------------------------------------------------

abl2TikZ ("ADS Board Link to TikZ") is a Converter Tool that converts schematics already designed in your EDA design tool to CircuiTi*k*Z. The idea is to avoid redrawing the circuitry for your document if you already have it drawn in your simulation tool. It supports every EDA tool allowing for XML export (such as Cadence Allegro, Cadence Virtuoso, Altium, etc.), though it is currently mostly maintained for Keysights Path Wave Advanced Design System (ADS). The tool runs on Windows and Unix-based systems as a command-line tool, providing Ti*k*Z code from your XML file exported from your simulation tool.

[![](https://circuit2tikz.tf.fau.de/images/ads.png)](https://github.com/Circuit2TikZ/abl2tikz) <!-- Keysight ADS -->

[![](https://circuit2tikz.tf.fau.de/images/circuitikz.png)](https://github.com/Circuit2TikZ/abl2tikz) <!-- CircuiTi*k*Z -->

GitHub Repositories
-------------------

All projects were initiated as research projects at the [institute of electronics engineering](https://www.lte.tf.fau.de) and are available on [GitHub](https://github.com/orgs/Circuit2TikZ/repositories). We welcome support and new ideas.

©️ Copyright Institute of Electronics Engineering (LTE) 2024

Contact: [christof.pfannenmueller@fau.de](mailto:christof.pfannenmueller@fau.de)
