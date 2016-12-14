# ClTonnetz
Tonnetz implementation in Common Lisp for Opusmodus (http://www.opusmodus.com)

Example:

(apply-tonnetz '(c4 e4 g4) '(l r n s p))

=> ((c4 e4 g4) (b3 e4 g4) (b3 d4 g4) (c4 eb4 g4) (b3 eb4 fs4) (b3 d4 fs4))

Ability to not include a move in the output:

(apply-tonnetz '(c4 e4 g4) '(l r n (s) p))

=> ((c4 e4 g4) (b3 e4 g4) (b3 d4 g4) (c4 eb4 g4) (b3 d4 fs4))
