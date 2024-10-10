return {
    'github/copilot.vim',
    config = function()
        vim.keymap.set('i', '<C-J>', 'copilot#Accept("")', {
            expr = true,
            replace_keycodes = false,
            desc = 'Copilot: Accept copilot suggestion',
        })
        vim.g.copilot_no_tab_map = true
    end
}
