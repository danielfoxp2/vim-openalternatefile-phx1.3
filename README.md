## INTRODUCTION

This plugin is intended to help you find the alternate test or production file faster in elixir.
When you are editing the production code, the plugin will open the spec file of it and vice-versa.

The plugin has a limitation because it works under a convention: the spec and production code has the 
same name (almost - see USAGE).

### WARNING

If you are working in a webapp using phoenix framework, this plugin will only work to versions starting at 1.3 of 
phoenix.

## USAGE

`<leader>.` is the way to go.

Let's say that you are editing the `my_file_spec.exs`, when you type in normal mode `<leader>.` the plugin 
will alternate to the file `my_file.ex`. If you type `<leader>.` again, you will be back to `my_file_spec.exs`.

It works to cucumber too (white-bread flavor).

When you are editing your `my_awesome.feature` and type `<leader>.` the plugin brings you the `my_awesome_contexts.exs`
and vice-versa.

