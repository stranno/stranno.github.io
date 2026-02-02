telegram-upload --caption "{file.stem} / {file.size.for_humans}" --large-files split --force-file --directories recursive .

ia upload **ID** **file1** **file2** **file3** --retries=300 --no-derive --no-backup --checksum --sleep=30  
ia copy **item/"file.extension"** --no-backup --no-derive  
ia metadata **item** --modify="title:TÍTULO"  
ia metadata **item** --modify="description:Descripción con código HTML"  
ia metadata **item** --remove="source:torrent"
