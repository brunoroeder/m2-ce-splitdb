
[![MageMojo](https://magetalk.com/wp-content/uploads/2017/11/q7xJZaM5TImMN7mUIb0c.png)](https://magemojo.com/)

# SplitDb
#### Magento 2 module to redirect SELECT queries to another database connection.  

![Version 1.0.0](https://img.shields.io/badge/Version-1.0.0-green.svg)

## Manual Install

- [Download this ZIP](https://github.com/magemojo/m2-ce-splitdb/archive/master.zip) and paste in your folder `app/code`.

- Add a new connection in your file `app/etc/env.php` called **readonly**, like the image below.

![MageMojo SplitDb](https://user-images.githubusercontent.com/610598/36800790-1ffcd17c-1c8f-11e8-813f-ac62933c26db.png)

- Run these commands in your terminal:

```bash
bin/magento module:disable MageMojo_SplitDb
bin/magento setup:upgrade
bin/magento module:enable MageMojo_SplitDb
bin/magento indexer:reindex
```

## License

© 2018 [MageMojo](https://magemojo.com/).

