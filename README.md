La data se extrajo de varios videos de youtube.com en los que se ha conversado sobre la migración venezolana o sobre migrantes venezolanos. La data tiene los siguientes campos:
id
channelId
title
thumbUrl
description
publishDate
viewCount
comments
likes
dislikes
responseCode
Las cuatro primeras variables tienen que ver con identificadores tanto del comentario, del usuario, del canal, etc. Nos interesa, para el análisis las variables: "description" que ofrece el nombre de usuario de quien postea.
"publishDate": fecha de publicación, "viewCount" cuántas veces se ha visto el comentario, "comments", "likes", "dislikes".

Adicionalmente el archivo "about" ofrece información sobre el procedimiento seguido para extraer lo comentarios: día, hora, año, el tipo de búsqueda. Está en formato .json
Finalmente el archivo "videos" ofrece información sobre los videos que se han bajado, lo cual es importante, especialmente si hemos olvidado anotar el nombre del video, dirección del canal, etc.

