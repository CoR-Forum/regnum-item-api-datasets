# Regnum Item API Datasets

|function|data|example|
|---|---|---|
|``id``|unique identifier|This should be the ID of the item ingame. For custom items, please start at ...tbd|
|``name_en``, ``name_de``, ``name_es``|Name of the Item in each language, excluding material and quality||
|``category``|Category of the item|Possible values:|
|``class``|Class of the item|Possible values: ``normal``, ``special``, ``magic``, ``epic``, ``legend``|
|``bound_char``|any|Info will be displayed if this data is not empty|
|``bound_acc``|any|Info will be displayed if this data is not empty|
|``icon_url``|file name of the icon|``icon.png`` - should be placed inside ``/icons`` directory|
