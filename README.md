<h1>REDO</h1>

An easy way to redo rails migrations. Just use a partial name:

```bash
$ redo add
redo: be more specific, candidates are:

add_slug_to_post : 20140301150615
add_locations_to_users : 20140606083843
add_name_to_users : 20120708181947
[...]

$ redo add_slug
redo: executing:
++ bundle exec rake db:migrate:redo VERSION=20140301150615
```
