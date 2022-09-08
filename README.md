# fix-admin-system-kick-owl-gaming
Fix bug in GM OWL of /pkick not kicking correctly//Arreglar el error en la GM OWL de el /pkick que no kickea correctamente


Para arreglar este error que no deja Expulsar||Kickear gente en la GM OWL 2016 debes reemplazar la siguiente funcion en la linea 1338 o 1337

				+kickPlayer(targetPlayer, getRootElement(), reason)
        -kickPlayer(targetPlayer, thePlayer, reason)

Debes eliminar el + y el - para que te funcione correctamente.
