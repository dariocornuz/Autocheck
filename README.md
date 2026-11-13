# Autocheck

App web de una sola página para revisar antecedentes de un vehículo a partir de su patente chilena o de su VIN.

- **Patente chilena:** reconoce el formato, calcula el dígito verificador (patentes LLLL·NN), indica el mes de revisión técnica y enlaza a las consultas oficiales (PRT, Autoseguro, Registro Civil).
- **VIN:** fabricante, país, año modelo, planta, serie y dígito de control calculados localmente; consulta en vivo a NHTSA vPIC y enlaces a fuentes de siniestros para importados (NICB VINCheck, remates Copart/IAAI, NMVTIS).

No usa servidor ni claves: todo corre en el navegador. Los datos calculados no reemplazan un certificado oficial.
