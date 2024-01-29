# Tips and Tricks

## Remote Upload

MultiUp Direct comes adaptive data streaming upload support, meaning you can upload links that normally fail with
regular remote upload, with a [caveat](#data-streaming-experimental-feature).

First, the link is attempted to be uploaded to the server using regular remote upload. If this fails, it will utilise
data streaming instead. This means you can combine links that work with remote upload and ones that don't and the
appropriate method will be used.

### Data Streaming (Experimental feature)

- Data streaming works by streaming the content of the link to MultiUp using your computer.
- This has the advantage of uploading files without having to download and write the files to disk, but also has the
  disadvantage of using the same bandwidth as downloading and uploading the file manually.
- This allows you to upload files stored on services that do not allow remote upload, such as Debrid services.
