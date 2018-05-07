# Codeigniter-Grocery-crud-Relation_n
Just replace the files in your system and use the feature you're upgrading set_relation.

# Example
void set_relation( string $field_name , string  $related_table, string  $related_title_field  [, mixed $where [, string $order_by ] ], array ( $field_name => $related_title_field ) );

$crud->set_relation('category_name', 'categories', 'category_id', null, null, array('slug' => 'category_slug'))
