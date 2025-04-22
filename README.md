A Neovim plugin to count the total number of lines for every function in a `.c` file.

## Installation

To install with Lazy.nvim:

```lua
{
  "joshw34/c_count_line",
  ft = "c",
  config = function()
    require("ft_count_lines").setup({
        enable_on_start = true --Default is false
    })
  end
}
```

Original Version can be found at: https://github.com/FtVim/ft_count_lines.nvim
