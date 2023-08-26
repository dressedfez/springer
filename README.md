# Springer

Official template for Springer journals

![](thumbnail.png)

- Author: Springer Nature (Springer Nature Group)
- Author Website: https://www.springernature.com/
- [Submission Guidelines](https://www.springernature.com/gp/authors/campaigns/latex-author-support)

## Steps to creating your own template!

- [x] 🆕 Create this repository. Nailed it. 🚀
- [x] 📑 Replace the `template.tex` with your existing LaTeX template/article
- [x] 👯‍♀️ Copy in any other style, definitions or images necessary for the template
- [x] 👩‍🔬 Add the files necessary into `files` list in the `template.yml` ([documentation](https://myst-tools.org/docs/mystjs/jtex/template-yml))
- [x] 🧙‍♀️ Start replacing template values with `[-options.my_value-]` and put in `[# if parts.abstract #]` conditions to toggle sections on and off ([documentation](https://myst-tools.org/docs/mystjs/jtex/template-rules))
- [x] 👩🏿‍💻 Install [jtex](https://myst-tools.org/docs/mystjs/jtex) (`npm install -g jtex`) and run `jtex check` ([documentation](https://myst-tools.org/docs/mystjs/jtex/command-line))
- [x] 🪄 Continue to improve the options in your template for `parts` and `options` ([documentation](https://myst-tools.org/docs/mystjs/jtex/document))
- [x] 💾 When ready, save your `template.yml` and run `jtex check --fix`, this will add various packages that are auto detected and fix document options ([documentation](https://myst-tools.org/docs/mystjs/jtex/command-line))
- [x] 🧪 Test with real content: `myst build my-document.md --template ../path/to/template` ([documentation](https://myst-tools.org/docs/mystjs/guide/creating-pdf-documents))
- [x] 📸 Create a `thumbnail.png` with an accurate screenshot of the template
- [x] 🧭 Update this README, and check all values in the `template.yml`
- [ ] 🚀 Push to GitHub, and contribute to the [community templates repository](https://github.com/myst-templates/templates)


## Options provided by Springer `myst`-Template

The Springer documentation used to setup this template can be found here:


- [LaTeX Author Support](https://www.springernature.com/gp/authors/campaigns/latex-author-support)

- [User Manual](./original/user-manual.pdf)

This is a table of options the template provides based on the above information (release 2.1):

| Option               | Type    | Default   | Required | Functionality|
| -------------------- | ------- | --------- | -------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `reference_style`              | choice | default     | false    | Defines the bibliograhy style used by the templated. The following options are available <table> <thead>   <tr> <th>  Bibliography style</th>  <th>Citation style</th> <th>Option to be used</th> </tr> </thead> <tbody><tr>  <td>LaTex Default Style</td>  <td>numbered</td>  <td>default</td> </tr><tr>  <td>Basic Springer Nature Nature/Chemistry Reference Style</td>  <td>authoryear</td>  <td>basic</td> </tr> <tr>  <td>Math and Physical Sciences Reference Style</td>  <td>numbered</td>  <td>mathphys</td> </tr><tr>  <td>American Physical Society (APS) Reference Style</td>  <td>numbered</td>  <td>aps</td> </tr><tr>  <td>Vancouver Reference Style</td>  <td>numbered</td>  <td>vancouver</td> </tr><tr>  <td>APA-based Social Sciences/Psychology Reference Style</td>  <td>authoryear</td>  <td>apa</td> </tr><tr>  <td>Chicago-based Humanities Reference Style</td>  <td>authoryear</td>  <td>chicago</td> </tr><tr>  <td>Nature Portfolio Reference Style</td>  <td>numbered</td>  <td>nature</td> </tr></tbody> </table> |
| `pdf_latex`              | boolean | true     | false  |Enables `pdflatex` option to compile the file with “pdflatex/xelatex”.|
| `line_numbers`              | boolean | false     | false    |Enables line numbers in the margin.|
| `referee`              | boolean | false     | false    |Enables double-line spacing requested for the peer review and editoral stages.|
| `formatting`  | choice | onecolumn     | false    | `twocolumn` enables double column layout to suit journal-level submission requirements.|
