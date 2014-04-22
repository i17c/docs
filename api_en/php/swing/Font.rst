Font
--------------

.. php:class:: php\\swing\\Font

 .. php:method:: __construct($name, $style, $size)

  :param $name: 
  :param $style: :doc:`int </api_en/int>` - PLAIN, BOLD, ITALIC
  :param $size: 

 .. php:method:: isBold()

  :returns: :doc:`bool </api_en/bool>` 

 .. php:method:: isItalic()

  :returns: :doc:`bool </api_en/bool>` 

 .. php:method:: isPlain()

  :returns: :doc:`bool </api_en/bool>` 

 .. php:method:: isTransformed()

  :returns: :doc:`bool </api_en/bool>` 

 .. php:method:: getBaselineFor($symbol)

  :param $symbol: :doc:`string </api_en/string>` - one char
  :returns: :doc:`int </api_en/int>` 

 .. php:method:: canDisplay($symbol)

  :param $symbol: :doc:`string </api_en/string>` - one char
  :returns: :doc:`bool </api_en/bool>` 

 .. php:method:: canDisplayUpTo($string)

  Indicates whether or not this Font can display a specified String.

  :param $string: 
  :returns: :doc:`int </api_en/int>` - an offset into $string that points to the first character in $string that this
  Font cannot display; or -1 if this Font can display all characters in $string.

 .. php:staticmethod:: decode($str)

  Decode font by using a specified string

  :param $str: 
  :returns: :doc:`php\\swing\\Font </api_en/php/swing/Font>` 

 .. php:staticmethod:: create($source, $trueType = true)

  Create new font by using Stream or File

  :param $source: 
  :param $trueType: 
  :returns: :doc:`php\\swing\\Font </api_en/php/swing/Font>` 

 .. php:staticmethod:: get($name)

  Get font by name

  :param $name: 
  :returns: :doc:`php\\swing\\Font </api_en/php/swing/Font>`, :doc:`null </api_en/null>` - return null if not exists
