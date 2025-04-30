# marks.nvim
show mark on sign bar

![marks](https://github.com/user-attachments/assets/dc41210c-93f4-4688-9733-ee967c52cce4)

## 📦 Installation

### [lazy.nvim](https://github.com/folke/lazy.nvim)

```lua
    {
        "edte/cmp-go-pkgs.nvim",
        ft = "go",
        config = function()
            require("cmp.cmp_go_pkgs").new()
            require("cmp").register_source("go_pkgs", require("cmp.cmp_go_pkgs"))
            vim.api.nvim_create_user_command("CurNode", function(c)
                require("cmp_go_pkgs.source").kek(c)
            end, {})
        end,
    },
```


## 📝 Configuration
```lua
{
}

```


## 🚀 Usage

## 📄 Thanks
- [marks.nvim](https://github.com/chentoast/marks.nvim)
