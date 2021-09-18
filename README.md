# Proyecto2-DS
# Detección de covid en radiografías de tórax:
El virus SARS-COV 2 causante de la enfermedad COVID 19 ataca principalmente los pulmonescausando neumonía viral. En una gran parte de los casos, los pacientes terminan en una unidad decuidados intensivos con ventilación mecánica invasiva. En estos momentos en nuestro país se vive un incremento de casos asociados a la entrada de la variante delta, 60% más infecciosa que la alfa.
Las imágenes de neumonías producidas por virus son variadas y poco específicas, pudiéndose veren otros procesos infecciosos o inflamatorios pulmonares. La radiografía simple de tórax muestraun patrón intersticial en más del 85% de los casos, y se presenta de forma bilateral en más del 75%Por otra parte, se ha relacionado la mayor afectación en la radiografía simple con la necesidad deingreso en una unidad de cuidados intensivos. Existen hallazgos en imágenes que obligan a realizar un diagnostico diferencial entre covid 19 yotras   afecciones   pulmonares   como   el   Síndrome   Respiratorio   de   Oriente   Medio   (MERS).   Encomparación  con otros  virus de la misma familia, parece  existir una mayor  tendencia a la afectación bilateral que en el SARS (síndrome respiratorio agudo grave humano) y una ausencia deun patrón de distribución específico similar al MERS (González-Castro etal., 2020).

El objetivo final del proyecto es que para cada imagen se pueda predecir un cuadro delimitador yuna clase para todos los hallazgos. Si se predice que no se encontraron hallazgos de la enfermedadse debería crear una categoría de la siguiente forma “ninguno 1 0 0 1 1” "ninguno" es el ID declase para ningún hallazgo, y esto proporciona un cuadro delimitador de un píxel con unaconfianza de 1.0). Para cada estudio del conjunto de prueba debe clasificar la imagen en:
  -Negativo para neumonía
  -Aspecto típico
  -Aspecto indeterminado
  -Aspecto atípico
