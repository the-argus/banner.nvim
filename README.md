# nvim-base16

Neovim plugin for applying banner colorschemes to highlight groups.

```lua
-- NOTE: the builtin colorschemes are not currently functional
-- All builtin colorschemes can be accessed with |:colorscheme|.
vim.cmd('colorscheme base16-gruvbox-dark-soft')
vim.cmd('colorscheme banner-rosepine')

-- Alternatively, you can provide a table specifying your colors to the setup function.
local colorscheme = require('colorscheme')
colorscheme.setup({
    base00 = '#16161D', base01 = '#2c313c', base02 = '#3e4451', base03 = '#6c7891',
    base04 = '#565c64', base05 = '#abb2bf', base06 = '#9a9bb3', base07 = '#c5c8e6',
    base08 = '#e06c75', base09 = '#d19a66', base0A = '#e5c07b', base0B = '#98c379',
    base0C = '#56b6c2', base0D = '#0184bc', base0E = '#c678dd', base0F = '#a06949',
    urgent =    '#e06c75', pfg_urgent = '#16161D',
    warn =      '#e5c07b', pfg_warn = '#16161D',
    confirm =   '#98c379', pfg_confirm = '#16161D',
    link =      '#0184bc', pfg_link = '#c5c8e6',
    highlight = '#c678dd', pfg_highlight = '#16161D',
    hialt0 =    '#c678dd', pfg_hialt0 = '#16161D',
    hialt1 =    '#c678dd', pfg_hialt1 = '#16161D',
    hialt2 =    '#c678dd', pfg_hialt2 = '#16161D'
})
```

# Builtin Colorschemes

```txt
base16-3024
base16-apathy
base16-ashes
base16-atelier-cave-light
base16-atelier-cave
base16-atelier-dune-light
base16-atelier-dune
base16-atelier-estuary-light
base16-atelier-estuary
base16-atelier-forest-light
base16-atelier-forest
base16-atelier-heath-light
base16-atelier-heath
base16-atelier-lakeside-light
base16-atelier-lakeside
base16-atelier-plateau-light
base16-atelier-plateau
base16-atelier-savanna-light
base16-atelier-savanna
base16-atelier-seaside-light
base16-atelier-seaside
base16-atelier-sulphurpool-light
base16-atelier-sulphurpool
base16-atlas
base16-bespin
base16-black-metal-bathory
base16-black-metal-burzum
base16-black-metal-dark-funeral
base16-black-metal-gorgoroth
base16-black-metal-immortal
base16-black-metal-khold
base16-black-metal-marduk
base16-black-metal-mayhem
base16-black-metal-nile
base16-black-metal-venom
base16-black-metal
base16-brewer
base16-bright
base16-brogrammer
base16-brogrammer2.0
base16-brushtrees-dark
base16-brushtrees
base16-chalk
base16-circus
base16-classic-dark
base16-classic-light
base16-codeschool
base16-cupcake
base16-cupertino
base16-darktooth
base16-default-dark
base16-default-light
base16-darcula
base16-dracula
base16-eighties
base16-embers
base16-flat
base16-fruit-soda
base16-github
base16-google-dark
base16-google-light
base16-grayscale-dark
base16-grayscale-light
base16-greenscreen
base16-gruvbox-dark-hard
base16-gruvbox-dark-medium
base16-gruvbox-dark-pale
base16-gruvbox-dark-soft
base16-gruvbox-light-hard
base16-gruvbox-light-medium
base16-gruvbox-light-soft
base16-harmonic-dark
base16-harmonic-light
base16-heetch-light
base16-heetch
base16-helios
base16-hopscotch
base16-horizon-dark
base16-ia-dark
base16-ia-light
base16-icy
base16-irblack
base16-isotope
base16-macintosh
base16-marrakesh
base16-materia
base16-material-darker
base16-material-lighter
base16-material-palenight
base16-material-vivid
base16-material
base16-mellow-purple
base16-mexico-light
base16-mocha
base16-monokai
base16-nord
base16-ocean
base16-oceanicnext
base16-one-light
base16-onedark
base16-outrun-dark
base16-papercolor-dark
base16-papercolor-light
base16-paraiso
base16-phd
base16-pico
base16-pop
base16-porple
base16-railscasts
base16-rebecca
base16-schemer-dark
base16-schemer-medium
base16-seti
base16-shapeshifter
base16-snazzy
base16-solarflare
base16-solarized-dark
base16-solarized-light
base16-spacemacs
base16-summerfruit-dark
base16-summerfruit-light
base16-synth-midnight-dark
base16-tomorrow-night-eighties
base16-tomorrow-night
base16-tomorrow
base16-tube
base16-twilight
base16-unikitty-dark
base16-unikitty-light
base16-woodland
base16-xcode-dusk
base16-zenburn
```
