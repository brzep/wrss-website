# wrss_wi website

I am using Hugo Static Site Generator with Blowish Theme (with a few tweaks).

## adding new team members
members are categorized under 3 categories:
- *head* - przewo, vice, senat
- *official* - all official members
- *unofficial* - all unofficial members

all members are defined in [team.toml](/data/team.toml) file
each member consists of two fields:
- `description`
  - `name` - obligatory
  - `function1` - non obligatory
  - `function2` - non obligatory
- `image` - obligatory, path to image, which should be placed in `/static/img/team` folder, it should be `1x1` `.jpg` file

after adding new record in [team.toml](/data/team.toml) file, everything should render automatically (hopefully)

## adding new events
events are defined if [events.toml](/data/events.toml) file
each event consists of four fields:
- `name` - obligatory
- `description` - obligatory (shouldn't be too long, I don't know how it will look like with longer texts [probably like shit])
- `image` - obligatory, path to image, which should be placed in `/static/img/team` folder, it should be `3x2` `.jpg` file

after adding new record in [events.toml](/data/events.toml) file, everything should render automatically (hopefully)
