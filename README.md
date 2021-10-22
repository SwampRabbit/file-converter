# file-converter

A simple application created using YAD to convert between various Document, Image, PDF, Video and Audio file formats.

- Supports batch conversion of multiple files
- Drag N Drop functionality
- Works on almost any Linux distro
- Progress bar

### The following formats and their equivalents are supported:
1) PDF
   - Can be converted (page-by-page) to jpg, png, tiff (Uses pdftoppm).
   - Can also be converted to a jpg containing only the first page (Uses pdftoppm).
   - Can be converted to html , odg (Uses LibreOffice).
2) Documents: pdf docx xlsx pptx odt ods odp odg odf odb doc ppt rtf xls epub html slk csv txt xml mml .... etc.,
   - Some formats and conversions are specifically supported if LibreOffice is install, others will still work without it
4) Images: jpg png gif tiff bmp heic ico webp
   - Any of these can be interconverted
   - Uses convert-im6.q16
5) Audio: mp3 ogg wav aiff aac flac voc
   - Any of these can be interconverted
   - Uses ffmpeg
6) Video: mp4 mkv webm 3gp avi dat flv m4v mov rm
   - Any of these can be interconverted
   - Uses ffmpeg

### Status of this application
I will update this application more when I find time, it appears to function fairly well for what it is intended to do.  I just wanted it saved so that even if I do not do much with it, others can submit commits, and it can be somewhat maintained. *See note below as to why*


###### ***Notice original application source:***

This application was created by GitHub user TimothySimon123 at github.com/TimothySimon123/file-converter.  The actual user of this account is unknown and was
created under false pretext.  I originally was assisting with this application on the MX Linux forums and created the debianization for it.  I had a fork off the original, but decided to split it off as contact with the user is no longer possible, and I would like for the application to be somewhat maintained.

I do not even know if the original code was actually created by the false user or not.  If by chance you come across this Repo and can substantiate that part of all of the original code is yours, please let me know, and I will update copyright and credits accordingly.
