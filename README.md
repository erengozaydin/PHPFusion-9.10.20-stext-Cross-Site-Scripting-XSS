# PHPFusion 9.10.20 - 'stext' Cross Site Scripting (XSS)

1. Description:
----------------------

PHPFusion 9.10.20 allows Cross Site Scripting (XSS) via parameter 'stext' in
localhost/PHPFusion/search.php  Exploiting this issue could allow an attacker to compromise.

2. Proof of Concept:
----------------------

'+alert(0x00F8100)+'
