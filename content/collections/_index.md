+++
title = "serene::collections"
description = "Demo collections page of zola-theme-serene"
template = "prose.html"

[extra]
lang = "en"

title = "Collections"
subtitle = "Special blocks for showcasing your list"

+++


## Books

{{ collection(file="books.toml") }}

## Theatre

{{ collection(file="theatre.toml") }}