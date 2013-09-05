Usage examples
===============

LineBreakAt
-----------
 `:LineBreakAt ( )	 Insert newline after each '(' and ')' in current line.
 :10,20LineBreakAt ( )	 Same, in lines 10 to 20 inclusive.
 :%LineBreakAt ( )	 Same, whole buffer.
 :LineBreakAt! ( )	 Insert newline before each '(' and ')' in current line.
 :%LineBreakAt	 Insert newline after each occurrence of last-used search pattern.
 :%LineBreakAt!	 Insert newline before each occurrence of last-used search pattern. `

