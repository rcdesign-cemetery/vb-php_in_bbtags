Description:
------------

vBulletin addon. Allows php code in custom tag definitions.

1. Start replacement with "#php" string.
2. Add somerthing like: $result = your_function_here( $option, $param )

(!) If you entered invalid php code and it crashes - disable mod, fix problem,
and enable mod back.


Example:
--------

#php
$result = $option . " " . $param;
