# Projects

## Model conversion and syntax

- [csv2sacs][]: Convert Metocean data into sea-state files
- [fltr][]: Convert member-end releases from [STAAD] to [USFOS]
- [gendata][]: Generate formatted model data from CSV file
- [sacs_st][]: [SACS] syntax for [Sublime Text] editor
- [usfos_st][]: [USFOS] syntax for Sublime Text editor 

[STAAD]: https://www.bentley.com/software/staad/
[Sublime Text]: https://www.sublimetext.com
[csv2sacs]: https://github.com/ckunte/csv2sacs "Convert Metocean data into a SACS seastate input file"
[fltr]: https://gist.github.com/ckunte/98fc79713b8d111b0aa6fec792b194b3 "Member end release conversion from STAAD to USFOS"
[gendata]: https://gist.github.com/ckunte/2819cf28a565bb0163671d92cb26eb03 "Generate formatted model data from CSV file"
[sacs_st]: https://github.com/ckunte/sacs_st "SACS syntax for Sublime Text"
[usfos_st]: https://github.com/ckunte/usfos_st "USFOS syntax for Sublime Text"

## Publishing

- [chisel][ch]: A static site generator in [python]
- [tce][tce]: Sneha's thesis on tourism into a mini-book project
- [m-one][m1]: Turning my collection of notes into a monograph

[git]: https://git-scm.com
[python]: https://www.python.org
[ch]: https://github.com/ckunte/chisel/tree/ck "A simple python static blog generation utility"
[tce]: https://github.com/ckunte/tce "Sneha's thesis into a mini-book project"
[m1]: https://github.com/ckunte/m-one "A collection of my notes turned into a monograph"

## Snippets for Sublime Text

- [latex-snippets-st][lst]: [LaTeX] snippets
- [typst-snippets-st][tst]: [Typst] snippets
- [autopair-underscores-backticks][abs]
- [datestamp][sds] with a shortcut (`ctrl`+`shift`+`d`)

[LaTeX]: https://www.latex-project.org
[Typst]: https://typst.app
[typst-py]: https://pypi.org/project/typst/
[lst]: https://github.com/ckunte/latex-snippets-st "LaTeX UltiSnips snippets for Sublime Text."
[tst]: https://github.com/ckunte/typst-snippets-st "Typst snippets for Sublime Text."

## Terminal utilities

- [hkp][hkp]: Scripts to manage files, folders, etc.
- [mkvim][mkv]: Compiling [Vim] from source with python3 enabled
- [w2p][w2p]: Batch convert Word files into pdf files

[Vim]: https://www.vim.org
[abs]: https://gist.github.com/ckunte/4700941 "Autopair underscores and backticks in Sublime Text"
[mkv]: https://gist.github.com/ckunte/80a9ba208b58a5b1aa8f122d602a55f4 "Compiling Vim from source with python3 interpreter enabled"
[sds]: /notes/dsst "Get date stamp (in Y-m-d H:M format) in Sublime Text from a shortcut (ctrl+shift+d)"
[hkp]: https://github.com/ckunte/hkp "A collection of scripts to manage files, folders, set permissions, prune empty folders, combine/compress pdf files, etc."
[w2p]: https://gist.github.com/ckunte/994a0894575555f27dda2b6de9239ece "Batch convert Word files to pdf files"

## Typesetting

- [Build from LaTeX][blx]: Ways to compile
- [Build from Typst][btt]: Ways to compile
- [latex-snippets-vim][lsv]: LaTeX snippets for Vim and [Neovim]
- [templates][tmpl]: For notes, letters, etc. (see also [wiki][w])
- [typst-snippets-vim][tsv]: Typst snippets for Vim and Neovim
- Alias `ctd.py` for running as `tc <filename>.typ`:
```
alias tc='_tc() { python3 /path-to/ctd.py -f $1 ;}; _tc'
```
[blx]: https://gist.github.com/ckunte/80ea9b0ba4905d1e52bc3fd0b21daa33
[btt]: https://gist.github.com/ckunte/6f7a1e8d3a3053d92c70c6b9ea5138ef
[Neovim]: https://neovim.io
[lsv]: https://github.com/ckunte/latex-snippets-vim "LaTeX UltiSnips snippets for Vim and Neovim."
[tmpl]: https://github.com/ckunte/templates "LaTeX templates (with styles) for notes, letters, forms."
[tsv]: https://github.com/ckunte/typst-snippets-vim "Typst snippets for Vim and Neovim"

## Useful utilities OS specific

- [mackeyboard][mk]: Mac keyboard to Windows key mappings
- [pi_sysinfo.sh][si]: Raspberry Pi system info function
- [raspberrypi-yubikey][ry]: Setting R.Pi for U2F with yubikey
- [scripting replies][or] in Outlook with AutoHotkey v2
- [wsl-howto][wsl]: Access linux environment from within Windows
- [Airprint][br]: Setup Brother HL-L2321D for AirPrinting

[si]: https://gist.github.com/ckunte/e0cb5d49a4baf9f9a9fef67052bf112d "Pi SysInfo function"
[or]: https://gist.github.com/ckunte/5709bb372a371b5f48a5068bbe051bbd "Scripting replies in Outlook with AutoHotkey v2"
[mk]: https://github.com/ckunte/mackeyboard "Mac Keyboard to Windows Key Mappings"
[ry]: https://gist.github.com/ckunte/047cd68684634fba74fcbd0888e966b1 "Setting Raspberry Pi Desktop for U2F with YubiKey"
[wsl]: https://gist.github.com/ckunte/eef5df56dc94941655e168575bda247b "Access linux environment from within Windows (via Windows Subsystem for Linux)"
[br]: https://gist.github.com/ckunte/fa1ff885a09d71f3d2cba31c9f8bd237 "Set up Brother HL-L2321D as a network-enabled AirPrint printer"

## Viewgraphs
- [git-talk][gt]: Version control for engineers
- [offshore-lifts][ol]: An overview
- [structural-dynamics][sd]: historical beginnings + introduction

[gt]: https://github.com/ckunte/git-talk "Version control for engineers"
[ol]: https://github.com/ckunte/offshore-lifts "Offshore lifts"
[sd]: https://github.com/ckunte/structural-dynamics "Structural dynamics"

## Web (related) services
- [ddns][]: Dynamic DNS setup for IP refresh using [DNSimple](https://dnsimple.com)
- [search-email][sm]: Email search (to add rule) in [Fastmail](https://www.fastmail.com)
- [srv][]: [http.server] script with clean URLs in python

[http.server]: https://docs.python.org/3/library/http.server.html
[ddns]: https://gist.github.com/ckunte/d2bacfd69bea1975b1c23e2c5247f1c7 "DDNS setup for IP refresh using DNSimple"
[sm]: https://gist.github.com/ckunte/2beaab5944d57b4cc3ed6bfe6817575c "Email search (to add rule) in Fastmail"
[srv]: https://gist.github.com/ckunte/c7f54d485b79730ddfe4c4dce1c451aa "SimpleHTTPServer script with clean URLs"

## Work related
- [tlp][tlp]: List of tension leg platforms
- [usfos-on-linux][uol]: Get USFOS to run on linux ([script])
- [w2w][w2w]: Walk-to-work elevation on platforms

[LaTeX]: https://www.latex-project.org "Document preparation system"
[prompt]: https://gist.github.com/ckunte/5adb355dec294e369ce7d1508e84eed0 "Simple colorful bash prompt with git status"
[SACS]: https://www.bentley.com/software/sacs-offshore-structure/ "Offshore Structural Analysis And Design Software"
[sc]: https://gist.github.com/ckunte/ab1993fbba0a2c31e240c64382558dca "Turn uppercase words into smallcaps in Typst"
[script]: https://gist.github.com/ckunte/cb829338ae7fc24cc2ca "Install USFOS on Debian script"
[sr]: https://gist.github.com/ckunte/4f58679de506917fae17383bdc0b2691 "Scripting replies in Outlook with AutoHotkey script"
[tcp]: https://gist.github.com/ckunte/0c5c7941db3ced7f079fd5227ee12dd4 "Copy and paste in tmux"
[tlp]: https://gist.github.com/ckunte/b0a204548a2ca72a0771bcc834a947dd "Tension leg platforms"
[tp]: https://gist.github.com/ckunte/6988a2b4ea9cc1cbebd3e3d8a0dc3daa "TransPerth bus timings"
[uol]: https://gist.github.com/ckunte/4829ba8180afb9413861dc5a2e3092c0 "Getting USFOS to run on Linux"
[USFOS]: https://www.usfos.com "USFOS non-linear static and dynamic analysis of space frame structures"
[vds]: https://gist.github.com/ckunte/2d7a750e6cf8b96f98f028e90c8ab712 "Get date stamp (in Y-m-d H:M format) in Vim from an abbreviation (ds)"
[w2w]: https://gist.github.com/ckunte/26ccccf02a747babde354e9a0e913a7d "Walk-to-work elevation on platforms"
[w]: https://github.com/ckunte/templates/wiki "Templates wiki"
[zsh]: https://gist.github.com/ckunte/0d3f0a8d18504f769adf3badde12abf4 "Setting zsh as default shell on Windows + Cygwin"

## RSS feeds
- [gists][]: [feed][gfeed] 
- [projects][]: [feed][pfeed]

[gists]: https://gist.github.com/ckunte
[projects]: https://github.com/ckunte
[gfeed]: https://gist.github.com/ckunte.atom
[pfeed]: https://github.com/ckunte.atom

