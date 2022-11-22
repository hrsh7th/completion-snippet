# vsnip-completion-snippet

The vim-vsnip snippet collection for completion.

# Concept

- Intented to use with completion
- Prefix should be similar to the language syntax elements
- Block-wise statement should expand `$TM_SELECTED_TEXT`

# Usage

```vim
let g:vsnip_snippet_dirs = get(g:, 'vsnip_snippet_dirs', [])
let g:vsnip_snippet_dirs += [g:vsnip_completion_snippet#path]
nnoremap c <Plug>(vsnip-cut-text)
xnoremap c <Plug>(vsnip-cut-text)
```

