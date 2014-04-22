File
-----------

.. php:class:: php\\io\\File

 Class File

 .. php:method:: __construct($path, $child = NULL)

  :param $path: 
  :param $child: 

 .. php:method:: exists()

  :returns: :doc:`bool </api_en/bool>` 

 .. php:method:: canExecute()

  :returns: :doc:`bool </api_en/bool>` 

 .. php:method:: canWrite()

  :returns: :doc:`bool </api_en/bool>` 

 .. php:method:: canRead()

  :returns: :doc:`bool </api_en/bool>` 

 .. php:method:: getName()

  :returns: :doc:`string </api_en/string>` 

 .. php:method:: getAbsolutePath()

  :returns: :doc:`string </api_en/string>` 

 .. php:method:: getCanonicalPath()

  :returns: :doc:`string </api_en/string>` 

 .. php:method:: getParent()

  :returns: :doc:`string </api_en/string>` 

 .. php:method:: getPath()

  :returns: :doc:`string </api_en/string>` 

 .. php:method:: getAbsoluteFile()

  :returns: :doc:`php\\io\\File </api_en/php/io/File>` 

 .. php:method:: getCanonicalFile()

  :returns: :doc:`php\\io\\File </api_en/php/io/File>` 

 .. php:method:: getParentFile()

  :returns: :doc:`php\\io\\File </api_en/php/io/File>` 

 .. php:method:: mkdir()

  :returns: :doc:`bool </api_en/bool>` 

 .. php:method:: mkdirs()

  :returns: :doc:`bool </api_en/bool>` 

 .. php:method:: isFile()

  :returns: :doc:`bool </api_en/bool>` 

 .. php:method:: isDirectory()

  :returns: :doc:`bool </api_en/bool>` 

 .. php:method:: isAbsolute()

  :returns: :doc:`bool </api_en/bool>` 

 .. php:method:: isHidden()

  :returns: :doc:`bool </api_en/bool>` 

 .. php:method:: delete()

  :returns: :doc:`bool </api_en/bool>` 

 .. php:method:: deleteOnExit()

  :returns: :doc:`void </api_en/void>` 

 .. php:method:: createNewFile()

  :returns: :doc:`bool </api_en/bool>` 

 .. php:method:: lastModified()

  :returns: :doc:`int </api_en/int>` 

 .. php:method:: length()

  :returns: :doc:`int </api_en/int>` 

 .. php:method:: renameTo($newName)

  :param $newName: 
  :returns: :doc:`bool </api_en/bool>` 

 .. php:method:: setExecutable($value, $ownerOnly = true)

  :param $value: 
  :param $ownerOnly: 
  :returns: :doc:`bool </api_en/bool>` 

 .. php:method:: setWritable($value, $ownerOnly = true)

  :param $value: 
  :param $ownerOnly: 
  :returns: :doc:`bool </api_en/bool>` 

 .. php:method:: setReadable($value, $ownerOnly = true)

  :param $value: 
  :param $ownerOnly: 
  :returns: :doc:`bool </api_en/bool>` 

 .. php:method:: setReadOnly()

  :returns: :doc:`bool </api_en/bool>` 

 .. php:method:: setLastModified($time)

  :param $time: 
  :returns: :doc:`bool </api_en/bool>` 

 .. php:method:: compareTo($file)

  :param $file: 
  :returns: :doc:`int </api_en/int>` 

 .. php:method:: find($filter = null)

  :param $filter: :doc:`callable </api_en/callable>` 
  :returns: :doc:`string[] </api_en/string>` 

 .. php:method:: findFiles($filter = null)

  :param $filter: :doc:`callable </api_en/callable>` 
  :returns: :doc:`php\\io\\File[] </api_en/php/io/File>` 

 .. php:staticmethod:: createTemp($prefix, $suffix, $directory = null)

  :param $prefix: 
  :param $suffix: 
  :param $directory: 
  :returns: :doc:`php\\io\\File </api_en/php/io/File>` 

 .. php:staticmethod:: listRoots()

  List the available filesystem roots.

  :returns: :doc:`php\\io\\File[]
An </api_en/php/io/File[]
An>` array of {@code File} objects denoting the available
  filesystem roots, or empty array if the set of roots could not
  be determined.  The array will be empty if there are no
  filesystem roots.
