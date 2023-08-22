<div style="float:right">Want a PDF version? <a href="https://github.com/Kapral67/Resume/releases/download/v2.1/CSCI_mkapral_12-2023.pdf">Click Here!</a></div>
## Maxwell Kapral

Cell: (650)-868-7892	Email: [mail@maxkapral.com](mailto:mail@maxkapral.com)	GitHub: [Kapral67](https://github.com/Kapral67)

---

### Education

<div style="float:right;">Expected Completion 2023</div><div style="font-weight:bold;">Currently Working Towards a Degree in Computer Science, GPA 3.6</div>
<div><i>California State University, Chico</i></div>

---

### Relevant Coursework

<table>
	<tr>
		<th style="text-align:center">Course</th>
		<th style="text-align:center">Description</th>
		<th style="text-align:center">Grade</th>
	</tr>
	<tr>
		<td style="text-align:center"><b>CSCI 370</b></td>
		<td style="text-align:center"><i>Introduction to Databases</i></td>
		<td style="text-align:center"><b>A</b></td>
	</tr>
	<tr>
		<td style="text-align:center"><b>CSCI 311</b></td>
		<td style="text-align:center"><i>Algorithms & Data Structures</i></td>
		<td style="text-align:center"><b>A</b></td>
	</tr>
	<tr>
		<td style="text-align:center"><b>EECE 237</b></td>
		<td style="text-align:center"><i>Embedded Systems Development</i></td>
		<td style="text-align:center"><b>A-</b></td>
	</tr>
	<tr>
		<td style="text-align:center"><b>CINS 465</b></td>
		<td style="text-align:center"><i>Web Programming Fundamentals</i></td>
		<td style="text-align:center"><b>A</b></td>
	</tr>
	<tr>
		<td style="text-align:center"><b>CSCI 340</b></td>
		<td style="text-align:center"><i>Operating Systems</i></td>
		<td style="text-align:center"><b>A</b></td>
	</tr>
</table>

---

### Work Experience

<div style="float: right">January 2019 - Present</div><div style="font-weight: bold;">Maxwell Kapral IT Services</div>
<div><i>Self Employed, Redwood City, CA</i></div>

- Troubleshooted Networking issues such as Double-NAT where multiple DHCP devices exist on the same network broadcasting with the same subnet and prefix
- Setup Ring devices including camera systems and alarm systems
- Configured HomeLink Garage door systems
- Cleaned and updated customers computers, both PC and MAC
- Setup Network printing over WiFi from computers and phones

<div style="float: right">February 2020 - August 2020</div><div style="font-weight: bold;">Crew Member</div>
<div><i>Trader Joe's, San Carlos, CA</i></div>

- Cashier, stocked shelves, bagged groceries, cleaned store, and unloaded trucks
- Resolved customer issues and answered questions

<div style="float: right">June 2018 - August 2018</div><div style="font-weight: bold;">Retail Associate</div>
<div><i>Target, Redwood City, CA</i></div>

- Stocked shelves within Grocery section
- Assisted customers with merchandise related questions

---

### Skills

- Proficient with Linux Systems, especially Arch and Debian based
- Adept with various programming languages, including Python, Java, C/C++, C# and others.

---

## Project Highlights

**Weather Progressive Web App**

- Works as an app or website on both computers and phones
- Sources all data from the [National Weather Service](https://www.weather.gov)
- Front-end programmed using [Microsoft Blazor Web-Assembly](https://www.blazor.net) in C#
  - This front-end is publicly accessible at [whether.maxkapral.com](https://whether.maxkapral.com)
- Back-end programmed using [Django](https://www.djangoproject.com/) and [Django Rest Framework](https://www.django-rest-framework.org/) in Python
  - The back-end is accessed from the front-end through an API hosted at [cdn.maxkapral.com](https://cdn.maxkapral.com/daily)
- The application is hosted on the [Google Cloud](https://cloud.google.com/) using [Docker](https://www.docker.com) and [NGINX](https://nginx.org/en/)
- The full source code is publicly available on my GitHub: [github.com/Kapral67/Whether](https://github.com/Kapral67/Whether)

---

**[IntelliSense](https://code.visualstudio.com/docs/editor/intellisense) Features for C/C++ in [Jupyter](https://jupyter.org/) Notebooks**

- Modified the [LLVM Project](https://github.com/Kapral67/llvm-project1/commit/c972f366a8a7fa61b56b3045f15c25d3ff353e1d) source code to recognize the `.ipynb` file extension as a valid C/C++ source code extension with [Clangd](https://clangd.llvm.org/)
  - [See Here](https://github.com/Kapral67/llvm-project1/commit/c972f366a8a7fa61b56b3045f15c25d3ff353e1d)
  - [LLVM Info](https://llvm.org/)
- Created releases of Clangd binaries for amd64 systems with Jupyter Notebook support using [Hydra Run](https://github.com/pojntfx/hydrun)
  - The build script is available [here](https://github.com/Kapral67/Cling-Clangd/blob/dev/Hydrunfile.sh)
  - [Full Repo](https://github.com/Kapral67/Cling-Clangd/tree/dev)
- Linking a clangd binary to Jupyter Notebooks is accomplished using the [Language Server Protocol](https://microsoft.github.io/language-server-protocol/) through a [Jupyter Extension](https://github.com/jupyter-lsp/jupyterlab-lsp)
  - A python script for linking the clangd binary is hosted [here](https://github.com/Kapral67/XeusAvecClangd/blob/main/jupyter_notebook_config.py)
- A Jupyter Notebook Demonstration using [Binder](https://mybinder.org/) is available at [this link](https://mybinder.org/v2/gh/Kapral67/XeusAvecClangd.git/HEAD?urlpath=lab)
  - The full source code for this demonstration is on my [GitHub](https://github.com/Kapral67/XeusAvecClangd)
  - A full list of features and functionality is provided by the [Jupyter LSP Extension](https://github.com/jupyter-lsp/jupyterlab-lsp/blob/master/README.md)