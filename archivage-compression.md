###archive

tar -cf archive.tar data.txt doc.txt : create archive of data.txt & doc.txt

tar -tf archive.tar : show files inside archive

tar -xf archive.tar : extract archive

###compression

zip archive.zip data.txt doc.txt : create compressive archive of data.txt & doc.txt

unzip archive.zip : extract archive

zip cls.pdf ==>add cls.pdf to archive

zip -d cls.pdf ==> remove cls.pdf from archive


zip -[0,9]: compression level
    0 => no compression, like tar
    9 => high level of compression

zip -Z deflate|bzip2 : set compression mode
    bzip2 =>better than deflate

zip -T : test archive (integrite)

zip -e : set password on archive 


tar -zcf out.tar.gz : create archive compressed gzip(gz)


tar -jcf out.tar.gz : create archive compressed bzip(bz2)




