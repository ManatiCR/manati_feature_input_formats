# Manati Feature Input Formats

## Dependencies
 - ckeditor
 - ckeditor_entity_embed
 - features
 - filter
 - token_filter

## How to use it

You need to create a content type to be embedded (ex. image); then add it to the settings.php as follows:

```
// CKEditor Embed allowed bundles.
$conf['ckeditor_entity_embed_entity_bundles'] = array(
  'node' => array('image'),
);
```

After that, clear all caches; you now will have a ckeditor embed view mode for your content type; configure it as necessary and add tpl file if necessary.
