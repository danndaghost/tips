# TIPS

Eliminar carpetas de produid dolibarr ERP

find -type d  | grep -i '^\.\/[0-9]\/[0-9]\/[0-9]\{3,4\}$' | awk -F/ '{ if($4 > 567) print $0}'

