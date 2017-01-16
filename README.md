# Manati Feature Input Formats

## Dependencies
 - ckeditor
 - ckeditor_entity_embed
 - features
 - filter
 - token_filter

## Additional needs
Add information about allowed bundles to be used as embed in settings.php file:
```
// CKEditor Embed allowed bundles.
$conf['ckeditor_entity_embed_entity_bundles'] = array(
  'node' => array('image'),
);
```
