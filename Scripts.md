telegram-upload --caption "{file.stem} / {file.size.for_humans}" --large-files split --force-file --directories recursive .

ia upload **ID** **file1** **file2** **file3** --retries=300 --no-derive --no-backup --checksum --sleep=30  
ia copy **item/"file.extension"** --no-backup --no-derive  
ia metadata **item** --modify="title:TÍTULO"  
ia metadata **item** --modify="description:Repositorio de audios del servicio <b>4UD1BL3</b>, hasta Enero de 2023.<div><br></div><div>No se va a actualizar con nuevo contenido.</div>"  
ia metadata **item** --remove="source:torrent"
